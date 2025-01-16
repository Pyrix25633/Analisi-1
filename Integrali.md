# Somma superiore e inferiore
$a=x_{0}<x_{1}<{\dots} <x_{N-1}=b$
$D=\{ x_{0},x_{1},\dots,x_{N-1} \}$ qualunque partizione di $[a,b]$
$$\begin{flalign}m_{i}:=\inf_{x \in[x_{i-1},x_{i}]}f(x)\;\;\;M_{i}:=\sup_{x \in[x_{i-1},x_{i}]}f(x) &&\end{flalign}$$
Le somme superiore e inferiore
$$\begin{flalign}S^{-}(D,f):=\sum_{i=1}^{N} m_{i}\cdot(x_{i}-x_{i-1}) \;\;\;S^{+}(D,f):=\sum_{i=1}^{N} M_{i}\cdot(x_{i}-x_{i-1})&&\end{flalign}$$
sono approssimazioni dell'area sottesa al grafico per difetto e per eccesso
Pertanto
$$\begin{flalign}(b-a)\inf_{x \in[a,b]}f(x)\leq S^{-}(D,f)\leq S^{+}(D,f)\leq(b-a)\sup_{x \in[a,b]}f(x) &&\end{flalign}$$
Le approssimazioni migliori sono la più grande per difetto e la più piccola per eccesso
$$\begin{flalign}\sup_{D}S^{-}(D,f):=\sup\{ S^{-}(D,f):D\text{ partizione di }[a,b] \} &&\end{flalign}$$
$$\begin{flalign}\inf_{D}S^{+}(D,f):=\inf\{ S^{+}(D,f):D\text{ partizione di }[a,b] \} &&\end{flalign}$$

# Funzione integrabile
$f:[a,b]\to \mathbb{R}$ limitata
$$\begin{flalign}\sup_{D}S^{-}(D,f)=\inf_{D}S^{+}(D,f)\implies &&\end{flalign}$$
$f$ è integrabile secondo Riemann
Il valore comune è detto integrale di Riemann di $f$ in $[a,b]$ e si indica con
$$\begin{flalign}\int_{a}^b f(x)\,dx  &&\end{flalign}$$
# Criteri di integrabilità
- $f:[a,b]\to \mathbb{R}$ è continua $\implies f$ è integrabile
- $f:[a,b]\to \mathbb{R}$ è monotona $\implies f$ è integrabile
- $f_{1}:[a,b]\to \mathbb{R}$, $f_{2}:[b,c]\to \mathbb{R}$ sono integrabili $\implies$ $$\begin{flalign}f(x)=\begin{cases}
f_1(x),\;x \in[a,b] \\
f_{2}(x),\;x \in(b,c]
\end{cases} &&\end{flalign}$$ è integrabile
<div class="page-break" style="page-break-before: always;"></div>

# Proprietà dell'integrale
$f,g:[a,b]\to \mathbb{R}$ integrabili in $[a,b]$
- linearità: $\forall\alpha,\beta \in \mathbb{R}\;\;\alpha f+\beta g$ è integrabile e $$\begin{flalign}\int_{a}^{b} (\alpha f(x)+\beta g(x))\,dx=\alpha \int_{a}^{b} f(x)\,dx+\beta \int_{a}^{b} g(x)\,dx &&\end{flalign}$$
- addittività rispetto al dominio di integrazione: $r\in(a,b)$ $$\begin{flalign}\int_{a}^{b} f(x)\,dx=\int_{a}^{r} f(x)\,dx+\int_{r}^{b} f(x)\,dx &&\end{flalign}$$
- positività: se $f\geq_{0}$ in $[a,b]\implies \int_{a}^{b} f(x)\,dx\geq0$
- monotonia: se $f\geq g$ in $[a,b]\implies \int_{a}^{b} f(x)\,dx\geq \int_{a}^{b} g(x)\,dx$
- $$\begin{flalign}\left|\int_{a}^{b} f(x)\,dx\right|\leq \int_{a}^{b} |f(x)|\,dx &&\end{flalign}$$
- $$\begin{flalign}\int_{b}^{a} f(x)\,dx=-\int_{a}^{b} f(x)\,dx\implies \int_{a}^{a} f(x)\,dx=0 &&\end{flalign}$$

# Teorema della media
$f:[a,b]\to \mathbb{R}$ limitata
$m:=\inf_{x \in[a,b]}f(x)\;\;\;M:=\sup_{x \in[a,b]}f(x)$
$m(b-a)\leq S^{-}(D,f)\leq S^{+}(D,f)\leq M(b-a)$
Se $f$ è integrabile in $[a,b]\implies m(b-a)\leq \int_{a}^{b} f(x)\,dx\leq M(b-a)$
Se $f$ è continua in $[a,b]\implies \exists x_{0}\in[a,b]: \frac{1}{b-a}\int_{a}^{b} f(x)\,dx=f(x_{0})$

# Funzione integrale
$f:[a,b]\to \mathbb{R}$ integrabile, $x_{0}\in[a,b]$
La funzione integrale di $f$ con punto base $x_{0}$ è $F:[a,b]\to \mathbb{R}$
$$\begin{flalign}F(x)=\int_{x_{0}}^{x} f(t)\,dt\;\;\forall x \in[a,b] &&\end{flalign}$$
<div class="page-break" style="page-break-before: always;"></div>

# Teorema fondamentale del calcolo integrale
$f:[a,b]\to \mathbb{R}$ integrabile, $x_{0}\in[a,b]$
$F(x)=\int_{x_{0}}^{x} f(t)\,dt$ funzione integrale di $f\implies$
- $F$ è continua in $[a,b]$
- se $f$ è continua in $\bar{x}\in(a,b)$ allora $F$ è derivabile in $\bar{x}$ e $F'(\bar{x})=f(\bar{x})$

Dimostrazione:
- $F$ è continua in $[a,b]$ $$\begin{flalign}F(x)-F(\bar{x})=\int_{x_{0}}^{x} f(t)\,dt -\int_{x_{0}}^{\bar{x}} f(t)\,dt =\int_{\bar{x}}^{x} f(t)\,dt &&\end{flalign}$$
  $$\begin{flalign}0\leq |F(x)-F(\bar{x})|=\left|\int_{\bar{x}}^{x} f(t)\,dt\right|\leq \int_{\bar{x}}^{x} |f(t)|\,dt \;\;*&&\end{flalign}$$
  siccome $f$ è limitata, allora $\forall t\in[a,b]\;\;\exists M:|f(t)|\leq M$ $$\begin{flalign}*\leq \int_{\bar{x}}^{x} M\,dt =M(x-\bar{x}) &&\end{flalign}$$
  per il teorema dei due carabinieri $\lim_{ x \to \bar{x} }F(x)-F(\bar{x})=0$
- se $f$ è continua in $\bar{x}\in(a,b)$ allora $F$ è derivabile in $\bar{x}$ e $F'(\bar{x})=f(\bar{x})$
  supponendo $f$ continua in $[a,b]$
  $$\begin{flalign}\lim_{ h \to 0 } \frac{F(\bar{x}+h)-F(\bar{x})}{h}=f(\bar{x})\;\;\; \frac{F(\bar{x}+h)-F(\bar{x})}{h}=\frac{\int_{\bar{x}}^{\bar{x}+h}f(t)\,dt}{h} &&\end{flalign}$$$$\begin{flalign} \frac{1}{h}\int_{\bar{x}}^{\bar{x}+h} f(t)\,dt-f(\bar{x})=\frac{1}{h}\int_{\bar{x}}^{\bar{x}+h} f(t)\,dt-\frac{1}{h}\int_{\bar{x}}^{\bar{x}+h}f(\bar{x}) \,dt =\frac{1}{h}\int_{\bar{x}}^{\bar{x}+h}f(t)-f(\bar{x}) \,dt &&\end{flalign}$$
  $f$ è continua in $\bar{x}$
  $\forall\epsilon>0\;\;\exists\delta>0:0<|t-\bar{x}|<\delta\;\;|f(t)-f(\bar{x})|<\epsilon$
  supponendo $h<\delta$
  $|f(t)-f(\bar{x})|<\epsilon\;\;\forall t\in[\bar{x},\bar{x}+h]$, quindi
  $$\begin{flalign} \frac{1}{h}\int_{\bar{x}}^{\bar{x}+h} f(t)-f(\bar{x})\,dt\leq \frac{1}{h}\int_{\bar{x}}^{\bar{x}+h} |f(t)-f(\bar{x})|\,dt\leq\epsilon &&\end{flalign}$$

$f\in \mathrm{C}^{k}([a,b])\implies F\in \mathrm{C}^{k+1}([a,b])$

# Primitiva
$I\subset \mathbb{R}$ intervallo, $f:I\to \mathbb{R}$
Si dice primitiva di $f$ in $I$ una qualunque funzione $G:I\to \mathbb{R}$ derivabile e tale che $G'(x)=f(x)\;\;\forall x \in I$

Ogni funzione continua ammette una primitiva e
- Se $G$ è una primitiva di $f\implies G+c$ è una primitiva di $f\;\;\forall c\in \mathbb{R}$
- Se $G_{1}$ e $G_{2}$ sono primitive di $f\implies G_{1}-G_{2}=c\in \mathbb{R}$
<div class="page-break" style="page-break-before: always;"></div>

# Integrale indefinito
L'integrale indefinito di $f$ è l'insieme di tutte le primitive di $f$
$\int f(x)\,dx:=\{ G:G'(x)=f(x) \}$

# Formula fondamentale del calcolo integrale
$f:[a,b]\to \mathbb{R}$ continua, $G$ primitiva di $f\implies$
$$\begin{flalign}\int_{a}^{b} f(x)\,dx =[G]_{a}^{b}=G(b)-G(a)&&\end{flalign}$$
Dimostrazione:
per il teorema fondamentale del calcolo integrale $F(x)=\int_{a}^{x} f(t)\,dt$ è una primitiva di $f$, anche $G$ è una primitiva di $f$
$\exists c\in \mathbb{R}:G(x)=F(x)+c$
$G(b)-G(a)=(F(b)+c)-(F(a)+c)=F(b)-F(a)=\int_{a}^{b} f(x)\,dx-\int_{a}^{a} f(x)\,dx=\int_{a}^{b} f(x)\,dx$

# Primitive fondamentali
$$\begin{flalign}\int \alpha\,dx =\alpha x+c &&\end{flalign}$$
$$\begin{flalign}\int x^{\alpha}\,dx=\frac{x^{\alpha+1}}{\alpha+1}+c &&\end{flalign}$$
$$\begin{flalign}\int \frac{1}{x}\,dx=\ln |x|+c &&\end{flalign}$$
$$\begin{flalign}\int e^{x}\,dx=e^{x}+c &&\end{flalign}$$
$$\begin{flalign}\int a^{x}\,dx=\frac{a^{x}}{\ln(a)}+c &&\end{flalign}$$
$$\begin{flalign}\int \sin(x)\,dx=-\cos(x)+c &&\end{flalign}$$
$$\begin{flalign}\int \cos(x)\,dx=\sin(x)+c &&\end{flalign}$$
$$\begin{flalign}\int \frac{1}{\cos ^{2}(x)}\,dx=\tan(x)+c &&\end{flalign}$$
$$\begin{flalign}\int 1+\tan ^{2}(x)\,dx=\tan (x)+c &&\end{flalign}$$
$$\begin{flalign}\int \frac{1}{1+x^{2}}\,dx=\arctan(x)+c &&\end{flalign}$$
$$\begin{flalign}\int \frac{1}{\sqrt{1-x^{2}}}\,dx=\arcsin(x)+c &&\end{flalign}$$
<div class="page-break" style="page-break-before: always;"></div>

# Formula di integrazione per sostituzione
$f:I\to \mathbb{R}$, $F$ primitiva di $f$ in $I$
$\varphi:[a,b]\to I$, $\varphi \in \mathrm{C}^{1}([a,b])$
$(F\circ \varphi)'(x)=F'(\varphi(x))\cdot \varphi'(x)=f(\varphi(x))\cdot \varphi'(x)$
$\int f(\varphi(x))\cdot \varphi'(x)\,dx=F(\varphi(x))+c=\int f(t)\,dt$ con $\varphi(x)=t$, $\varphi'(x)\,dx=dt$

# Simmetrie negli integrali
$f:[-a,a]\to \mathbb{R}$
- Se $f$ è pari, cioè $f(-x)=f(x)\;\;\forall x \in[-a,a]$ $$\begin{flalign}\int_{-a}^{a} f(x)\,dx =\int_{-a}^{0} f(x)\,dx +\int_{0}^{a} f(x)\,dx=-\int_{0}^{-a} f(x)\,dx+\int_{0}^{a} f(x)\,dx= &&\end{flalign}$$$$\begin{flalign}=\int_{0}^{a} f(-x)\,dx+\int_{0}^{a} f(x)\,dx=2\int_{0}^{a}f(x) \,dx &&\end{flalign}$$
- Se $f$ è dispari, cioè $f(-x)=-f(x)\;\;\forall x \in[-a]$ $$\begin{flalign}\int_{-a}^{a} f(x)\,dx =\int_{-a}^{0} f(x)\,dx +\int_{0}^{a} f(x)\,dx=-\int_{0}^{-a} f(x)\,dx+\int_{0}^{a} f(x)\,dx= &&\end{flalign}$$$$\begin{flalign}=\int_{0}^{a} f(-x)\,dx+\int_{0}^{a} f(x)\,dx=0 &&\end{flalign}$$

# Integrazione per parti
$\int f'(x)g(x)\,dx=f(x)g(x)-\int f(x)g'(x)\,dx$
$$\begin{flalign}\int_{a}^{b} f'(x)g(x)\,dx=[f(x)g(x)]_{a}^{b}-\int_{a}^{b} f(x)g'(x)\,dx &&\end{flalign}$$
<div class="page-break" style="page-break-before: always;"></div>

# Integrazione di funzioni razionali
$n\geq0$, $m\geq1$
Se $n\geq m$:
$$\begin{flalign}\int \frac{P_{n}(x)}{Q_{m}(x)}\,dx=\int S_{n-m}(x)\,dx+\int \frac{R(x)}{Q_{m}(x)}\,dx &&\end{flalign}$$
Se $n<m$:
- $n=0$, $m=1$: $$\begin{flalign}\int \frac{A}{ax+b}\,dx=\frac{A}{a}\int \frac{a}{ax+b}=\frac{A}{a}\ln |ax+b|+c &&\end{flalign}$$
- $n\in \{ 0,1 \}$, $m=2$: $$\begin{flalign}\int \frac{\alpha x+\beta}{ax^{2}+bx+c}\,dx\;\;\Delta=b^{2}-4ac &&\end{flalign}$$
	- $\Delta>0$: $$\begin{flalign}ax^{2}+bx+c=a(x-x_{1})(x-x_{2})\;\;\; \frac{\alpha x+\beta}{ax^{2}+bx+c}=\frac{A}{x-x_{1}}+\frac{B}{x-x_{2}} &&\end{flalign}$$
	- $\Delta=0$:
	  $ax^{2}+bx+c=a(x-x_{0})^{2}\;\;\;t=x-x_{0}\;\;\;dt=dx$
	- $\Delta<0$: portare alla forma dell'$\arctan$

# Integrale generalizzato in un intervallo limitato
$f:(a,b]\to \mathbb{R}$ integrabile in $[a+\epsilon,b]\;\;\forall\epsilon>0$
L'integrale improprio o generalizzato di $f$ in $(a,b)$ è
$$\begin{flalign}\int_{a}^{b} f(x)\,dx:=\lim_{ \epsilon \to 0^{+} } \int_{a+\epsilon}^{b} f(x)\,dx &&\end{flalign}$$
Se il limite esiste finito $f$ è integrabile in senso generalizzato in $(a,b)$ e l'integrale improprio è convergente, se il limite vale $\pm \infty$ l'integrale improprio è divergente

# Integrale generalizzato in un intervallo illimitato
$f:[a,+\infty)\to \mathbb{R}$ integrabile in $[a,M]\;\;\forall M>a$
L'integrale improprio o generalizzato di $f$ in $(a,+\infty)$ è
$$\begin{flalign}\int_{a}^{+\infty} f(x)\,dx:=\lim_{ M \to +\infty } \int_{a}^{M} f(x)\,dx &&\end{flalign}$$
Se il limite esiste finito $f$ è integrabile in senso generalizzato in $(a,+\infty)$ e l'integrale improprio è convergente, se il limite vale $\pm \infty$ l'integrale improprio è divergente
<div class="page-break" style="page-break-before: always;"></div>

# Criterio del confronto
$f,g:[a,b]\to \mathbb{R}$, $b\in(a,+\infty)$, $f,g$ integrabili in $[a,c]\;\;\forall c\in(a,b)$
Se $0\leq f(x)\leq g(x)\;\;\forall x \in[a,b)$ si ha che:
- $\int_{a}^{b} g(x)\,dx<+\infty\implies \int_{a}^{b} f(x)\,dx<+\infty$
- $\int_{a}^{b} f(x)\,dx=+\infty\implies \int_{a}^{b} g(x)\,dx=+\infty$

# Criterio del confronto asintotico
$f,g:[a,b)\to \mathbb{R}$, $b\in(a,+\infty]$, $f,g$ integrabili in $[a,c]\;\;\forall c\in(a,b)$
Se $f(x)>0$, $g(x)>0$, $f(x)\sim g(x)$ per $x\to b^{-}\implies$
$\int_{a}^{b} f(x)\,dx$ converge $\iff \int_{a}^{b} g(x)\,dx$ converge

# Criterio di convergenza assoluta
$\int_{a}^{b} |f(x)|\,dx$ converge $\implies \int_{a}^{b} f(x)\,dx$ converge
Inoltre $\left|\int_{a}^{b} f(x)\,dx\right|\leq \int_{a}^{b} |f(x)|\,dx$
