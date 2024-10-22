# Teorema degli zeri
$f:[a,b]\to \mathbb{R}$ continua in $[a,b]$
$f(a)\cdot f(b)<0 \implies \exists x_{0}\in(a,b):f(x_{0})=0$

# Metodo di bisezione
1) Calcolo $$\begin{flalign}x_{m}=\frac{b+a}{2} &&\end{flalign}$$
	- Se $f(x_{m})=0$: l'algoritmo si ferma
	- Altrimenti valuto il segno:
		- Se $f(x_{m})\cdot f(x_{a})<0$: $f$ ammette soluzione in $(a,x_{m})$
		- Altrimenti: $f$ ammette soluzione in $(x_{m},b)$
2) Itero il passo 1

# Intersezione di funzioni
$f,g:[a,b]\to \mathbb{R}$ continue
$f(a)>g(a), f(b)<g(b) \implies \exists x_{0}\in(a,b):f(x_{0})=g(x_{0})$
Applicazione del teorema degli zeri alla funzione $f(x)-g(x)$

# Teorema dei valori intermedi
$f:[a,b]\to \mathbb{R}$ continua $\implies f$ assume tutti i valori compresi tra $\inf_{x \in[a,b]}f(x)$ e $\sup_{x \in[a,b]}f(x)$, ovvero
$$\begin{flalign} \forall y \in(\inf_{x \in[a,b]}f(x), \sup_{x \in[a,b]}f(x))\; \exists x \in[a,b]:f(x)=y &&\end{flalign}$$

# Massimo e minimo assoluto
$f:D\to \mathbb{R}$ continua
- $M$ si dice massimo assoluto di $f$ in $D$ se
	- $\forall x \in D\;f(x)\leq M$
	- $\exists x_{0}\in D:f(x_{0})=M$ detto punto di massimo
- $m$ si dice minimo assoluto di $f$ in $D$ se
	- $\forall x \in D\;f(x)\geq m$
	- $\exists x_{0}\in D:f(x_{0})=m$ detto punto di minimo

# Teorema di Weierstrass
$f:[a,b]\to \mathbb{R}$ continua $\implies \exists M,m$ massimo e minimo di $f$ in $[a,b]$ e $f([a,b])=[m,M]$