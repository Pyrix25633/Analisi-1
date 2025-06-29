$D\subset \mathbb{R},\;f:D\to \mathbb{R},\; x_{0}\in \mathbb{R}$

# Intorno
> [!definizione]
> L'intorno di $x_{0}$ di raggio $r$ è l'intervallo $(x_{0}-r,x_{0}+r)=\{ x \in \mathbb{R}:|x-x_{0}|<r \}$
> $a\in R$
> L'intorno di $+\infty$ è l'intervallo $\left( a,+\infty \right)=\{ x \in \mathbb{R}:x>a \}$
> L'intorno di $-\infty$ è l'intervallo $\left(-\infty,a\right)=\{ x \in \mathbb{R}:x<a \}$

# Punto di accumulazione
> [!definizione]
> $x_{0}$ si dice punto di accumulazione per $D$ se $(x_{0}-\delta,x_{0}+\delta)\cap D\setminus \{ x_{0} \}\neq \emptyset\;\;\forall\delta>0$, equivalentemente $\exists x \in D\setminus \{ x_{0} \}:0<|x-x_{0}|<\delta\;\;\forall\delta>0$

# Limite finito in un punto
> [!definizione]
> $x_{o}$ punto di accumulazione per $D$
> $l\in \mathbb{R}$ si dice limite di $f$ per $x\to x_{0}$ se $\forall\epsilon>0\;\exists\delta>0:\forall x \in(x_{0}-\delta,x_{0}+\delta)\cap D\setminus\{ x_{0} \}\;|f(x)-l|<\epsilon$
e si indica con
> $$\begin{flalign}\lim_{ x \to x_{0} } f(x)=l &&\end{flalign}$$

# Funzione continua
> [!definizione]
> $x_{0}\in D$
> Una funzione $f$ è continua in $x_{0}$ se $\forall\epsilon>0\; \exists\delta>0:\forall x \in(x_{0}-\delta,x_{0}+\delta)\cap D\setminus\{ x_{0} \}\;|f(x)-f(x_{0})|<\epsilon$
> Ovvero $f$ è continua in $x_{0}\iff \lim_{ x \to x_{0} }f(x)=f(x_{0})$
<div class="page-break" style="page-break-before: always;"></div>

# Limite destro e sinistro
> [!definizione]
> $x_{0}$ punto di accumulazione per $D$
> $$\begin{flalign}\lim_{ x \to x_{0}^{+} }f(x)=l \iff \forall\epsilon>0\; \exists\delta>0:\forall x \in(x_{0},x_{0}+\delta)\cap D\;\; |f(x)-l|<\epsilon  &&\end{flalign}$$
> $$\begin{flalign}\lim_{ x \to x_{0}^{-} }f(x)=l \iff \forall\epsilon>0\; \exists\delta>0:\forall x \in(x_{0}-\delta,x_{0})\cap D\;\; |f(x)-l|<\epsilon  &&\end{flalign}$$
> $$\begin{flalign}\exists \lim_{ x \to x_{0} }f(x)=l\in \mathbb{R} \iff \lim_{ x \to x_{0}^{+} }f(x)=\lim_{ x \to x_{0}^{-} }f(x)=l  &&\end{flalign}$$

# Funzione continua da destra o da sinistra
> [!definizione]
> $x_{0}\in D$
> Una funzione $f$ è continua da destra in $x_{0}\iff\lim_{ x \to x_{0}^{+} }f(x)=f(x_{0})$
> Una funzione $f$ è continua da sinistra in $x_{0}\iff\lim_{ x \to x_{0}^{-} }f(x)=f(x_{0})$

# Limite infinito in un punto
> [!definizione]
> $x_{0}$ punto di accumulazione per $D$
> $$\begin{flalign}\lim_{ x \to x_{0} }f(x)=+\infty \iff \forall M>0\;\exists\delta>0:\forall x \in(x_{0}-\delta,x_{0}+\delta)\setminus \{ x_{0} \}\;\;f(x)>M &&\end{flalign}$$
> $$\begin{flalign}\lim_{ x \to x_{0} }f(x)=-\infty \iff \forall M>0\;\exists\delta>0:\forall x \in(x_{0}-\delta,x_{0}+\delta)\setminus \{ x_{0} \}\;\;f(x)<-M &&\end{flalign}$$
> La retta $x=x_{0}$ è un'asintoto verticale per $f$
<div class="page-break" style="page-break-before: always;"></div>

# Limite all'infinito
> [!definizione]
> $D$ illimitato superiormente ($\forall k>0\;\exists x \in D:x>k$)
> $$\begin{flalign}\lim_{ x \to +\infty }f(x)=l\in \mathbb{R} \iff \forall\epsilon>0\;\exists k>0:\forall x \in(k,+\infty)\cap D\;\;|f(x)-l|<\epsilon &&\end{flalign}$$
> $$\begin{flalign}\lim_{ x \to +\infty }f(x)=+\infty \iff \forall M>0\;\exists k>0:\forall x \in(k,+\infty)\cap D\;\;f(x)>M &&\end{flalign}$$
> $$\begin{flalign}\lim_{ x \to +\infty }f(x)=-\infty \iff \forall M>0\;\exists k>0:\forall x \in(k,+\infty)\cap D\;\;f(x)<-M &&\end{flalign}$$
> $D$ illimitato inferiormente ($\forall k>0\;\exists x \in D:x<-k$)
> $$\begin{flalign}\lim_{ x \to -\infty }f(x)=l\in \mathbb{R} \iff \forall\epsilon>0\;\exists k>0:\forall x \in(-\infty,-k)\cap D\;\;|f(x)-l|<\epsilon &&\end{flalign}$$
> $$\begin{flalign}\lim_{ x \to -\infty }f(x)=+\infty \iff \forall M>0\;\exists k>0:\forall x \in(-\infty,-k)\cap D\;\;f(x)>M &&\end{flalign}$$$$\begin{flalign}\lim_{ x \to -\infty }f(x)=+\infty \iff \forall M>0\;\exists k>0:\forall x \in(-\infty,-k)\cap D\;\;f(x)<-M &&\end{flalign}$$

# Cambio di variabili
> [!teorema]
> Se $\exists \lim_{ x \to x_{0} }f(x)=y_{0},\;g$ funzione definita in un intorno di $y_{0}$ tale che
> - se $y_{0}\in \mathbb{R}$, $g$ è continua in $y_{0}$
> - se $y_{0}=\pm \infty$, $\exists \lim_{ y \to y_{0} }g(y)$
> 
> allora
> $$\begin{flalign}\lim_{ x \to x_{0} }g(f(x))=\lim_{ y \to y_{0} }g(y)  &&\end{flalign}$$

# Continuità
> [!definizione]
> $A\subset D$
> $f$ è continua in $A$ se $f$ è continua in $x_{0}\;\;\forall x_{0}\in A$
> In questo caso $f\in C^{0}(A)$
<div class="page-break" style="page-break-before: always;"></div>

# Discontinuità
> [!definizione]
> Un punto di discontinuità $x_{0}$ si dice
> - Eliminabile se esiste finito $$\begin{flalign}\lim_{ x \to x_{0} }f(x)\neq f(x_{0}) &&\end{flalign}$$
> - A salto se esistono finiti $$\begin{flalign}\lim_{ x \to x_{0}^{+} }f(x)\neq \lim_{ x \to x_{0}^{-} }f(x) &&\end{flalign}$$
> - Essenziale negli altri casi

# Limiti notevoli
> [!formule]
> $$\begin{flalign}\lim_{ x \to 0 } \frac{\sin(x)}{x}=1 &&\end{flalign}$$
> $$\begin{flalign}\lim_{ x \to 0 } \frac{1-\cos(x)}{x^{2}}=\frac{1}{2} &&\end{flalign}$$
> $$\begin{flalign}\lim_{ x \to 0 } \frac{\tan(x)}{x}=1 &&\end{flalign}$$
> $$\begin{flalign}\lim_{ x \to \pm \infty } \left( 1+\frac{1}{x} \right)^{x}=e &&\end{flalign}$$
> $$\begin{flalign}\lim_{ x \to 0 } (1+x)^{1/x}=e &&\end{flalign}$$
> $$\begin{flalign}\lim_{ x \to 0 } \frac{\ln(1+x)}{x}=1 &&\end{flalign}$$
> $$\begin{flalign}\lim_{ x \to 0 } \frac{e^{x}-1}{x}=1 &&\end{flalign}$$
> $$\begin{flalign}\lim_{ x \to 0 } \frac{a^{x}-1}{x}=\ln(a) &&\end{flalign}$$
> $$\begin{flalign}\lim_{ x \to 0 } \frac{(1+x)^{\alpha}-1}{x}=\alpha &&\end{flalign}$$
