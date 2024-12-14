$f:(a,b)\to \mathbb{R},\;x_{0}\in(a,b)$

$f$ è derivabile in $x_{0}$ se esiste finito
$$\begin{flalign}f'(x_{0}):=\lim_{ x \to x_{0} } \frac{f(x)-f(x_{0})}{x-x_{0}}=\lim_{ h \to 0 } \frac{f(x_{0}+h)-f(x_{0})}{h}  &&\end{flalign}$$
Derivata destra: $$\begin{flalign}f'(x_{0}^{+})=\lim_{ x \to x_{0}^{+} } \frac{f(x)-f(x_{0})}{x-x_{0}} &&\end{flalign}$$
Derivata sinistra: $$\begin{flalign}f'(x_{0}^{-})=\lim_{ x \to x_{0}^{-} } \frac{f(x)-f(x_{0})}{x-x_{0}} &&\end{flalign}$$
$f$ derivabile in $x_{0} \implies$ ammette retta tangente con equazione $y=f(x_{0})+f'(x_{0})(x-x_{0})$

# Derivabilità implica continuità
$f$ derivabile in $x_{0}\implies f$ continua in $x_{0}$

# Punti di non derivabilità
$f$ continua in $x_{0}$
- Punto angoloso: $x_{0}$ è detto punto angoloso se esistono finiti $f'(x_{0}^{+})\neq f'(x_{0}^{-})$
- Cuspide: $x_{0}$ è detto cuspide se $f'(x_{0}^{+})=\pm \infty,\;f'(x_{0}^{-})=\mp \infty$ 
- Punto a tangente verticale: $x_{0}$ è detto punto a tangente verticale se $f'(x_{0})=\pm \infty$

# Derivate di funzioni elementari
- $\mathrm{D}[x^{n}]=n\cdot x^{n-1}$
- $\mathrm{D}[e^{x}]=e^{x}$
- $\mathrm{D}[\ln(x)]=\frac{1}{x}$
- $\mathrm{D}[\sin(x)]=\cos(x)$
- $\mathrm{D}[\cos(x)]=-\sin(x)$

# Linearità della derivata
$f(x),g(x)$ derivabili in $x_{0}$
$\forall a,b\in \mathbb{R}$ la combinazione lineare $af(x)+bg(x)$ è derivabile in $x_{o}$ e $(af+bg)'(x_{0})=af'(x_{0})+bg'(x_{0})$

# Regola di Leibnitz
$f(x),g(x)$ derivabili in $x_{0}$
La funzione prodotto $f(x)\cdot g(x)$ è derivabile in $x_{0}$ e $(f\cdot g)'(x_{0})=f'(x_{0})\cdot g(x_{0})+f(x_{0})\cdot g'(x_{0})$

# Regola della catena
$g(x)$ derivabile in $x_{0}$, $f(x)$ derivabile in $y_{0}=g(x_{0})$
La composizione $f\circ g$ è derivabile in $x_{0}$ e $(f\circ g)'(x_{0})=f'(x_{0})\cdot g'(x_{0})$

# Derivata della funzione inversa
$f(x)$ invertibile su $(a,b)$ e derivabile in $x_{0}\in(a,b)$ con $f'(x_{0})\neq0$
$(f^{-1}\circ f)(x)=f^{-1}(f(x))=x\;\;\forall x\in(a,b)$
$(f^{-1}\circ f)'(x_{0})=1$

$f^{-1}$ è derivabile in $y_{0}=f(x_{0})$ e
$$\begin{flalign}(f^{-1})(y_{0})=\frac{1}{f'(x_{0})} &&\end{flalign}$$

# Derivata del quoziente
$f(x),g(x)$ derivabili in $x_{0}$ con $g(x_{0})\neq0$
La funzione quoziente $\frac{f(x)}{g(x)}$ è derivabile in $x_{0}$ e
$$\begin{flalign}\left( \frac{f}{g} \right)'(x_{0})=\frac{f'(x_{0})\cdot g(x_{0}) + f(x_{0})\cdot g'(x_{0})}{g(x_{0})^{2}} &&\end{flalign}$$

# Derivate notevoli
- $\mathrm{D}[a^{x}]=a^{x}\ln(a)$
- $$\begin{flalign}\mathrm{D}[\log_{a}(x)]=\frac{1}{x\ln(a)} &&\end{flalign}$$

# Massimo e minimo relativo
$f:D\subset \mathbb{R}\to \mathbb{R}$
$x_{0}$ è un punto di
- minimo relativo per $f$ se $\forall x \in D\;\exists\delta>0:|x-x_{0}|\leq\delta\;\;f(x)\geq f(x_{0})$
- massimo relativo per $f$ se $\forall x \in D\;\exists\delta>0:|x-x_{0}|\leq\delta\;\;f(x)\leq f(x_{0})$

$f:(a,b)\to \mathbb{R}$, $x_{0}\in(a,b)$ punto di massimo o minimo relativo per $f$
$f$ derivabile in $x_{0}\implies f'(x_{0})=0$

# Punto critico
$x_{0}$ è un punto critico per $f$ se $f'(x_{0})=0$

# Teorema di Rolle
$f:[a,b]\to \mathbb{R}$ continua su $[a,b]$ e derivabile su $(a,b)$
$f(a)=f(b)\implies \exists c\in(a,b):f'(c)=0$

# Teorema di Lagrange
$f:[a,b]\to \mathbb{R}$ continua su $[a,b]$ e derivabile su $(a,b)$
$$\begin{flalign}\implies \exists c\in(a,b):f'(c)=\frac{f(b)-f(a)}{b-a} &&\end{flalign}$$
Dimostrazione:
$$\begin{flalign}g(x):=f(x)-\frac{f(b)-f(a)}{b-a}(x-a) &&\end{flalign}$$
$g(a)=f(a)-0=f(a)$
$g(b)=f(b)-f(b)+f(a)=f(a)$
Soddisfa le ipotesi del Teorema di Rolle $\implies \exists c\in (a,b):g'(c)=0$
$$\begin{flalign}g'(x)=f'(x)-\frac{f(b)-f(a)}{b-a} &&\end{flalign}$$

# Funzione monotona
$f:(a,b)\to \mathbb{R}$ derivabile
- $f$ è monotona crescente su $(a,b)\iff f'(x)\geq0$
- $f$ è monotona decrescente su $(a,b)\iff f'(x)\leq0$
- $f$ è costante su $(a,b)\iff f'(x)=0$

# Teorema di De L'Hospital
$-\infty\leq a<b\leq+\infty$, $f,g:(a,b)\to \mathbb{R}$ derivabili in $(a,b)$ tali che
- $g'(x)\neq0\;\;\forall x \in(a,b)$
- $$\begin{flalign}\lim_{ x \to a^{+} } f(x)=\lim_{ x \to a^{+} } g(x)=0,\pm \infty &&\end{flalign}$$
- $$\begin{flalign}\lim_{ x \to a^{+} } \frac{f'(x)}{g'(x)}=l\in \mathbb{R} \cup \{ \pm \infty \} &&\end{flalign}$$
$$\begin{flalign}\implies \lim_{ x \to a^{+} } \frac{f(x)}{g(x)}=l &&\end{flalign}$$

# Derivata seconda e successive
$f:(a,b)\to \mathbb{R}$ derivabile in $(a,b)\implies f':(a,b)\to \mathbb{R}$
$f'$ derivabile in $x_{0}\implies$
$$\begin{flalign}f''(x_{0})=D^{2}[f(x_{0})]:=\lim_{ x \to x_{0} } \frac{f'(x)-f'(x_{0})}{x-x_{0}} &&\end{flalign}$$

# Concavità
### Insiemi convessi
$E\subset \mathbb{R}^{2}$ si dice convesso se il segmento che connette $p_{1},p_{2}\in E$ è tutto contenuto in $E$

### Sopragrafico
$E=\{ (x,y)\in \mathbb{R}^{2}: x \in(a,b),\;y\geq f(x) \}$ è detto sopragrafico o epigrafico di $f$

### Funzione convessa
Una funzione il cui sopragrafico è convesso è detta convessa
Una funzione $f$ si dice concava se $-f$ è convessa
$f$ derivabile due volte:
- $f$ è convessa $\iff f''(x)\geq0\;\;\forall x \in(a,b)$
- $f$ è concava $\iff f''(x)\leq0\;\;\forall x \in(a,b)$

# Punto di flesso
$f$ derivabile in $x_{0}$
$x_{0}$ si dice punto di flesso se $\exists\delta>0:f$ è convessa in $(x_{0}-\delta,x_{0})$ e concava in $(x_{0},x_{0}+\delta)$ o viceversa

# Asintoto
### Orizzontale
Se
$$\begin{flalign}\lim_{ x \to \pm\infty }f(x) =l\in \mathbb{R} &&\end{flalign}$$
allora $y=l$ è un asintoto orizzontale di $f$

### Verticale
Se
$$\begin{flalign}\lim_{ x \to x_{0}^{\pm} } f(x) = \pm \infty &&\end{flalign}$$
allora $x=x_{0}$ è un asintoto verticale di $f$

### Obliquo
Se
$$\begin{flalign}\lim_{ x \to \pm\infty } f(x) =\pm \infty,\;\exists m\neq0,q:\lim_{ x \to \pm\infty }[f(x)-(mx+q)]=0  &&\end{flalign}$$
allora $y=mx+q$ è un asintoto obliquo di $f$
$$\begin{flalign}m=\lim_{ x \to \pm\infty } \frac{f(x)}{x},\;q=\lim_{ x \to \pm\infty } [f(x)-mx] &&\end{flalign}$$
