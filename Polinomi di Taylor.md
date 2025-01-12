# Notazione di $o$
$f:D\to \mathbb{R}$, $x_{0}$ punto di accumulazione per $D$ o $x_{0}=\pm \infty$

### $o(1)$
$f$ è infinitesima per $x\to x_{0}$ se $\lim_{ x \to x_{0} }f(x)=0\implies f(x)=o(1)$ per $x\to x_{0}$

Proprietà: per $x\to x_{0}$
- $o(1)+o(1)=o(1)$
- $a\cdot o(1)=o(1)\;\;\forall a\in \mathbb{R}$
- $o(1)-o(1)=o(1)$
- $o(1)\cdot o(1)=o(1)$

### $o(f(x))$
$o(f(x))=f(x)\cdot o(1)$ per $x\to x_{0}$

$g(x):D\to \mathbb{R}$
$g(x)=o(f(x))$ per $x\to x_{0}\iff g(x)=f(x)\cdot o(1)\iff \frac{g(x)}{f(x)}=o(1)$

Altre operazioni: per $x\to x_{0}$
- $x^{\alpha}\cdot o(x^{\beta})=o(x^{\alpha+\beta})\;\;[x^{\alpha}\cdot x^{\beta}\cdot o(1)=o(x^{\alpha}\cdot x^{\beta})]$
- $o(o(x^{n}))=o(x^{n})\;\;[o(x^{n}\cdot o(1))=x^{n}\cdot o(1)\cdot o(1)]$
- $(o(x^{\alpha}))^{\beta}=o(x^{\alpha\cdot\beta})\;\;[(o(o(1)\cdot x^{\alpha}))^{\beta}=o(1)\cdot o(1)^{\beta}\cdot x^{\alpha\cdot\beta}]$
- $o(x^{n}+o(x^{n}))=o(x^{n})\;\;[o(x^{n}+o(1)\cdot x^{n})=o(1)\cdot x^{n}\cdot o(1)\cdot o(1)\cdot x^{n}]$

# Retta tangente come migliore approssimante affine
$f:(a,b)\to \mathbb{R}$ derivabile in $x_{0}\in(a,b)$
$$\begin{flalign}\lim_{ x \to x_{0} } \frac{f(x)-f(x_{0})}{x-x_{0}}=f'(x_{0})\;\;\lim_{ x \to x_{0} } \frac{f(x)-f(x_{0})-f'(x_{0})\cdot(x-x_{0})}{x-x_{0}} &&\end{flalign}$$
Sia $T_{1}(x):=f(x_{0})+f'(x_{0})\cdot(x-x_{0})$ polinomio di grado al più uno
$$\begin{flalign}\lim_{ x \to x_{0} } \frac{f(x)-T_{1}(x)}{x-x_{0}} = 0&&\end{flalign}$$
$$\begin{flalign}\frac{f(x)-T_{1}(x)}{x-x_{0}}=o(1)\;\;f(x)-T_{1}(x)=o(x-x_{0})\;\;f(x)=T_{1}+o(x-x_{0}) &&\end{flalign}$$per $x\to x_{0}$ e
$$\begin{flalign}\begin{cases}
T_{1}(x_{0})=f(x_{0}) \\
T_{1}'(x_{0})=f'(x_{0})
\end{cases} &&\end{flalign}$$
Supponendo $f$ derivabile $n$ volte, il polinomio candidato $T_{n}(x)$ che approssima $f$ intorno a $x_{0}$ deve soddisfare 
$$\begin{flalign}\begin{cases}
T_{n}(x_{0})=f(x_{0}) \\
T_{n}'(x_{0})=f'(x_{0}) \\
\dots \\
T_{n}^{(n)}(x_{0})=f^{(n)}(x_{0})
\end{cases} &&\end{flalign}$$
Il polinomio di Taylor di $f$ in $x_{0}$ di ordine $n$ è definito come
$$\begin{flalign}T_{n}(x)=\sum_{k=0}^{n} \frac{f^{(k)}(x_{0})}{k!}(x-x_{0})^{k} &&\end{flalign}$$
e per costruzione soddisfa tutte le proprietà del sistema
Osservazione: $T_{0}(x)=f(x_{0})$
Se $x_{0}=0$ il polinomio si dice polinomio di MacLaurin

# Formula di Taylor con resto di Peano
$f:(a,b)\to \mathbb{R}$ derivabile $n$ volte in $x_{0}\in(a,b)$
$$\begin{flalign}f(x)=\sum_{k=0}^{n} \frac{f^{(k)}(x_{0})}{k!}(x-x_{0})^{k}+o((x-x_{0})^{n}) &&\end{flalign}$$

# Sviluppi di MacLaurin di alcune funzioni elementari
$$\begin{flalign}e^{x}=\sum_{k=0}^{n} \frac{1}{k!}x^{k}+o(x^{n}) &&\end{flalign}$$
$$\begin{flalign}\ln(1+x)=\sum_{k=0}^{n} \frac{(-1)^{k-1}}{k}x^{k}+o(x^{n}) &&\end{flalign}$$
$$\begin{flalign}\sin(x)=\sum_{k=0}^{n} \frac{(-1)^{k}}{(2k+1)!}x^{2k+1}+o(x^{2n+2}) &&\end{flalign}$$
$$\begin{flalign}\cos(x)=\sum_{k=0}^{n} \frac{(-1)^{k}}{(2k)!}x^{2k}+o(x^{2n+1}) &&\end{flalign}$$
$$\begin{flalign}\arctan(x)=\sum_{k=0}^{n} \frac{(-1)^{k}}{2k+1}x^{2k+1}+o(x^{2n+2}) &&\end{flalign}$$
$$\begin{flalign}(1+x)^{\alpha}=\sum_{k=0}^{n} \binom{\alpha}{k}x^{k}+o(x^{n}) &&\end{flalign}$$

# Formula di Taylor con resto di Lagrange
$f:(a,b)\to \mathbb{R}$, $x_{0}\in(a,b)$, $f$ derivabile $n+1$ volte in $(a,b)$
$\forall x \in(a,b)\setminus \{ x_{0} \}\;\exists \xi:\xi$ compreso tra $x$ e $x_{0}$ e
$$\begin{flalign}f(x)=\sum_{k=0}^{n} \frac{f^{(k)}(x_{0})}{k!}(x-x_{0})^{k}+\frac{f^{(n+1)}(\xi)}{(n+1)!}(x-x_{0})^{n+1} &&\end{flalign}$$
$$\begin{flalign}f(x)=T_{n}(x)+\frac{f^{(n+1)}(\xi)}{(n+1)!}(x-x_{0})^{n+1}\;\;|f(x)-T_{n}(x)|=\left|\frac{f^{(n+1)}(\xi)}{(n+1)!}(x-x_{0})^{n+1}\right| &&\end{flalign}$$
$$\begin{flalign}|f(x)-T_{n}(x)|\leq \sup_{t\in(a,b)}|f^{(n+1)}(t)|\cdot\frac{|x-x_{0}|^{n+1}}{(n+1)!} &&\end{flalign}$$
