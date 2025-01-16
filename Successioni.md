Una successione è una funzione $f:\mathbb{N}\to \mathbb{R}$ denotata con $a_{n}=f(n)$, la sua immagine si indica con $(a_{n})_{n\in \mathbb{N}}$

### Grafico
$\mathrm{Gr}(f)=\{ (n,f(n)),\; n\in \mathbb{N} \}$

### Fattoriale
$a_{n}=n! := 1\cdot 2\cdot 3\cdot {\dots} \cdot n$ si chiama successione fattoriale ed è strettamente crescente, infatti:
$a_{n}<a_{n+1} \implies n!<(n+1)! \implies n!<(n+1)\cdot(n+1-1)! \implies n!<(n+1)\cdot n! \implies 1<n+1$
Per definizione $0!=1$
Proprietà:
- $n! = n\cdot(n-1)!$
- $$\begin{flalign} \frac{n!}{(n-k)!}=n\cdot (n-1)\cdot {\dots}\cdot (n-k+1) &&\end{flalign}$$

# Coefficiente binomiale
$n,k\in \mathbb{N},\;0\leq k\leq n$

$$
\begin{flalign}
\binom{n}{k}=\frac{n!}{k!\cdot (n-1)!}=\frac{n\cdot (n-1)\cdot {\dots}\cdot (n-k-1)}{k!}&&
\end{flalign}
$$
Proprietà:
- $$\begin{flalign} \binom{n}{0}=\binom{n}{n}=1&& \end{flalign}$$
- $$\begin{flalign} \binom{n}{k}=\binom{n}{n-k}&& \end{flalign}$$
- $$\begin{flalign} \binom{n}{k}=\binom{n-1}{k-1}+\binom{n-1}{k}&& \end{flalign}$$

### Binomio di Newton
$$
\begin{flalign}
(a+b)^{n}=\sum_{k=0}^{n} \binom{n}{k}\cdot a^{n-k}\cdot b^{k}&&
\end{flalign}
$$
<div class="page-break" style="page-break-before: always;"></div>

### Successione geometrica
Dato $q\in R,\; q\neq0$ la successione geometrica di ragione $q$ è definita come la successione $a_{n}=q^{n}$
Il rapporto tra un termine della successione e il precedente è costante $\frac{a_{n+1}}{a_{n}}=q$
La somma dei primi $n+1$ termini della successione geometrica con $q\neq0$ si calcola con:
$$\begin{flalign}S_{n}:=\sum_{k=0}^{n} q^{k}=1+q+{\dots}+q^{n}=\begin{cases}
\frac{q^{n+1}-1}{q-1},\; q\neq1 \\
n+1,\; q=1
\end{cases} &&\end{flalign}$$

# Limite di una successione
$a_{n}\to0 \iff \forall\epsilon>0\; \exists\upsilon_{\epsilon}\in \mathbb{R}:\forall n>\upsilon_{\epsilon}\; -\epsilon<a_{n}<\epsilon$
$a_{n}\to+ \infty \iff \forall\epsilon>0\; \exists\upsilon_{\epsilon}\in \mathbb{R}:\forall n>\upsilon_{\epsilon}\; a_{n}>\epsilon$
$a_{n}\to- \infty \iff \forall\epsilon>0\; \exists\upsilon_{\epsilon}\in \mathbb{R}:\forall n>\upsilon_{\epsilon}\; a_{n}<-\epsilon$
$a_{n}\to l\in \mathbb{R} \iff a_{n}-l\to0$

### Unicità del limite
$a_{n}\to x,\; a_{n}\to y \iff x=y$

### Limitatezza delle successioni convergenti
$a_{n}\to l \iff \forall n\in N\; \exists M\in R:|a_{n}|\leq M$

### Sottosuccessioni
Una successione $(n_{n})_{n}$ è detta sottosuccessione di $(a_{n})_{n}$ e si ha $\forall n\in N\;\; b_{n}=a_{\Phi(n)}$, dove $\Phi:\mathbb{N}\to \mathbb{N}$ è una funzione strettamente crescente
$$\begin{flalign} \lim_{ n \to +\infty }a_{n}=l \implies \lim_{ k \to +\infty }a_{n_{k}}=l&&\end{flalign}$$

### Non esistenza del limite
Se una successione $a_{n}$ ammette due sottosuccessioni distinte le quali hanno due limiti distinti, allora $a_{n}$ non ha limite

### Monotona
- Crescente se $a_{n}\leq a_{n+1}$
- Strettamente crescente se $a_{n}< a_{n+1}$
- Decrescente se $a_{n}\geq a_{n+1}$
- Strettamente decrescente se $a_{n}> a_{n+1}$

Sia $a_{n}$ crescente, allora
$$\begin{flalign}\exists \lim_{ n \to \infty } a_{n}=\mathrm{sup}\{ a_{i}:i\in \mathbb{N},\; i\geq0 \} &&\end{flalign}$$
Analogamente, sia $a_{n}$ decrescente, allora

$$\begin{flalign}\exists \lim_{ n \to \infty } a_{n}=\mathrm{inf}\{ a_{i}:i\in \mathbb{N},\; i\geq0 \} &&\end{flalign}$$
<div class="page-break" style="page-break-before: always;"></div>

### Successione di Nepero
$a_{n}=\left( 1+\frac{1}{n} \right)^{n}$
La successione di Nepero è strettamente crescente e limitata
$$
\begin{flalign}
\exists\lim_{ n \to +\infty }\left( 1+\frac{1}{n} \right)^{n}=e&&
\end{flalign}
$$
$$
\begin{flalign}
\lim_{ n \to +\infty }|a_{n}|=+\infty \implies \lim_{ n \to +\infty }\left( 1+\frac{1}{a_{n}} \right)^{a_{n}}=e&&
\end{flalign}
$$
$$\begin{flalign}\alpha \in \mathbb{R} \;\;\; \lim_{ n \to +\infty }\left( 1+\frac{\alpha}{a_{n}} \right)^{a_{n}}=e^{\alpha}  &&\end{flalign}$$

### Permanenza del segno:
$x_{n}\to l>0 \implies \exists \bar{n} : \forall n\geq \bar{n} \; x_{n}>0$

### Confronto:
$a_{n} \to a, \; b_{n} \to b \; \exists \bar{n} : \forall n \geq \bar{n} \; a_{n}\leq b_{n} \implies a\leq b$

### Due carabinieri:
$a_{n} \to a, \; b_{n} \to b \; \exists \bar{n} :\forall n\geq \bar{n}\; a_{n}\leq c_{n}\leq b_{n} \implies c_{n} \to l$

### Algebra dei limiti finiti
$a_{n}\to a\in \mathbb{R},\;b_{n}\to b\in \mathbb{R}$
- Somma: $\lim_{ n \to +\infty }a_{n}\pm b_{n}=a\pm b$
- Prodotto: $\lim_{ n \to +\infty }a_{n}\cdot b_{n}=a\cdot b$
- Quoziente ($b\neq 0$): $\lim_{ n \to +\infty } \frac{a_{n}}{b_{n}}=\frac{a}{b}$
- Potenza: $\lim_{ n \to +\infty }a_{n}^{b_{n}}=a^{b}$

### Criterio del rapporto:
$$\begin{flalign} \forall n \in \mathbb{N}, \; a_{n}>0&&\\ \frac{a_{n+1}}{a_{n}} \to l&& \end{flalign}$$
- $l>1 \implies a_{n}\to +\infty$
- $l<1 \implies a_{n}\to 0$
- $l=0$ non si può concludere nulla
<div class="page-break" style="page-break-before: always;"></div>

### Gerarchia di infiniti
$\alpha>0,\; a>0$
Le successioni
$\log_{a}(n); \; n^{\alpha}; \; a^{n}; \; n!; \; n^{n}$
sono in ordine crescente di infinito, ovvero
$$\begin{flalign}
\lim_{ n \to +\infty } \frac{\log_{a}(n)}{n^{\alpha}}=\lim_{ n \to +\infty } \frac{n^{\alpha}}{a^{n}}=\lim_{ n \to +\infty } \frac{a^{n}}{n!}=\lim_{ n \to +\infty } \frac{n!}{n^{n}}=0 
&&\end{flalign}$$
