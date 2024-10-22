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