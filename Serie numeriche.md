$(a_{n})_{n}$ successione di numeri reali con $n\in \mathbb{N}$
$(S_{k})_{k}$ è la successione delle somme parziali con $k\in \mathbb{N}$
$$\begin{flalign}S_{k}=\sum_{n=0}^{k} a_{n}=a_{0}+{\dots}+a_{k} &&\end{flalign}$$
Una serie numerica è il limite delle somme parziali
$$\begin{flalign}\sum_{n=0}^{+\infty} a_{n}:=\lim_{ k \to +\infty } S_{k}=\lim_{ k \to +\infty } \sum_{n=0}^{k} a_{n} &&\end{flalign}$$
La serie è detta
- convergente se il limite di $S_{k}$ esiste finito
- divergente se il limite di $S_{k}$ esiste e vale $\pm \infty$
- indeterminata se il limite di $S_{k}$ non esiste

# Serie telescopiche
$(a_{n})_{n},(b_{n})_{n}$ successioni tali che $a_{n}=b_{n+1}-b_{n}\;\;\forall n\in \mathbb{N}$
$$\begin{flalign}S_{k}=\sum_{n=0}^{k} a_{n}=(b_{1}-b_{0})+(b_{2}-b_{1})+{\dots}+(b_{k+1}-b_{k})=b_{k+1}-b_{0} &&\end{flalign}$$
$$\begin{flalign}\lim_{ k \to +\infty } S_{k}=\lim_{ k \to +\infty } (b_{k+1}-b_{0}) &&\end{flalign}$$
Se $\exists \lim_{ k \to +\infty }b_{k}\implies \exists \lim_{ k \to +\infty }S_{k}$ e la serie è convergente

### Serie di Mengoli
$$\begin{flalign}\sum_{n=1}^{+\infty} \frac{1}{n(n+1)} &&\end{flalign}$$
è telescopica
$$\begin{flalign} \frac{1}{n(n+1)}=-\left( \frac{1}{n+1}-\frac{1}{n} \right)=b_{n+1}-b_{n} &&\end{flalign}$$
$$\begin{flalign}\lim_{ k \to +\infty } b_{k+1}=\lim_{ k \to +\infty } -\frac{1}{k+1}=0\implies &&\end{flalign}$$
converge e
$$\begin{flalign}\sum_{n=1}^{+\infty} \frac{1}{n(n+1)}=\lim_{ k \to +\infty } (b_{k+1}-b_{1})=0-(-1)=1 &&\end{flalign}$$
<div class="page-break" style="page-break-before: always;"></div>

### Serie logaritmica
$$\begin{flalign}\sum_{n=1}^{+\infty} \ln\left( 1+\frac{1}{n} \right) &&\end{flalign}$$
è telescopica
$$\begin{flalign}\ln\left( 1+\frac{1}{n} \right)=\ln\left( \frac{n+1}{n} \right)=\ln(n+1) -\ln(n)=b_{n+1}-b_{n}&&\end{flalign}$$
$$\begin{flalign}\lim_{ k \to +\infty } b_{k+1}=\lim_{ k \to +\infty } \ln(k+1)=+\infty\implies &&\end{flalign}$$
diverge e
$$\begin{flalign}\sum_{n=1}^{+\infty} \ln\left( 1+\frac{1}{n} \right)=+\infty &&\end{flalign}$$

# Condizione necessaria
Se $\sum_{n=o}^{+\infty}a_{n}$ converge $\implies a_{n}$ è infinitesima, ovvero
se $a_{n}$ non è infinitesima $\implies \sum_{n=0}^{+\infty}a_{n}$ non converge
Dimostrazione:
$(a_{n})_{n}$ successione, $S_{k}$ serie associata
poiché per ipotesi la serie $\sum_{n=0}^{+\infty}a_{n}$ converge si ha che $\lim_{ k \to +\infty }S_{k}$ esiste finito
dunque $S_{k}-S_{k-1}=a_{k}$ e $\lim_{ k \to +\infty }a_{k}=\lim_{ k \to +\infty }(S_{k}-S_{k-1})=0$

# Carattere di una serie
La serie $\sum_{n=0}^{+\infty}a_{n}$ ha lo stesso carattere di $\sum_{n=n_{0}}^{+\infty}a_{n}$, ma valore diverso

# Serie a termini positivi
$(a_{n})_{n}$ successione a termini positivi ($a_{n}\geq0\;\;\forall n\in \mathbb{N}$)
$S_{k}$ è monotona crescente, infatti $S_{k+1}=\sum_{n=0}^{k+1}a_{n}=\sum_{n=0}^{k}a_{n}+a_{k+1}\geq S_{k}$ e quindi ammette limite (finito o infinito), perciò la serie associata converge oppure diverge

# Criterio del confronto
$(a_{n})_{n},(b_{n})_{n}$ successioni a termini positivi, se $\exists n_{0}:a_{n}\leq b_{n}\;\;\forall n\geq n_{0}$ si ha che:
- $\sum_{n=0}^{+\infty}b_{n}<+\infty\implies \sum_{n=0}^{+\infty}a_{n}<+\infty$
- $\sum_{n=0}^{+\infty}a_{n}=+\infty\implies \sum_{n=0}^{+\infty}b_{n}=+\infty$
<div class="page-break" style="page-break-before: always;"></div>

# Criterio del confronto asintotico
$(a_{n})_{n},(b_{n})_{n}$ successioni a termini positivi, se $\lim_{ n \to +\infty } \frac{a_{n}}{b_{n}}=1\implies$ sono asintotiche $a_{n}\sim b_{n}$ ovvero $a_{n}=b_{n}+o(b_{n})$ per $n\to +\infty$
Se $\exists \lim_{ n \to +\infty } \frac{a_{n}}{b_{n}}=l\implies$
- $l=0$: $\sum_{n=0}^{+\infty} b_{n}<+\infty\implies \sum_{n=0}^{+\infty} a_{n}<+\infty$
- $l=+\infty$: $\sum_{n=0}^{+\infty} b_{n}=+\infty\implies \sum_{n=0}^{+\infty} a_{n}=+\infty$
- $0<l<+\infty$: $\sum_{n=0}^{+\infty}a_{n}$ e $\sum_{n=0}^{+\infty}$ hanno lo stesso carattere

# Serie armonica generalizzata
Funzione Zeta di Riemann: $\alpha>0$ $$\begin{flalign}\zeta(\alpha)=\sum_{n=1}^{+\infty} \frac{1}{n^{\alpha}} &&\end{flalign}$$
è convergente per $\alpha>1$ e divergente per $\alpha\leq1$

# Criterio del rapporto e della radice n-esima
$(a_{n})_{n}$ a termini positivi
Se $$\begin{flalign}\exists \lim_{ n \to +\infty } \frac{a_{n+1}}{a_{n}}=l &&\end{flalign}$$ oppure $$\begin{flalign}\exists \lim_{ n \to +\infty } \sqrt[n]{a_{n}}=l &&\end{flalign}$$
- se $l>1$ la serie associata diverge
- se $l<1$ la seria associata converge

# Criterio di convergenza assoluta
$(a_{n})_{n}$ successione generica
Se $\sum_{n=0}^{+\infty}|a_{n}|$ converge $\implies \sum_{n=0}^{+\infty}a_{n}$ converge
La serie associata converge assolutamente se la serie associata al valore assoluto converge semplicemente

# Serie a segni alterni
Serie di Leibnitz: $$\begin{flalign}\sum_{n=1}^{+\infty} \frac{(-1)^{n+1}}{n} &&\end{flalign}$$ converge semplicemente ma non assolutamente
<div class="page-break" style="page-break-before: always;"></div>

# Criterio di Leibnitz
$(a_{n})_{n}$ monotona decrescente e infinitesima $\implies \sum_{n=0}^{+\infty}(-1)^{n}\cdot a_{n}$ è convergente
Dimostrazione:
$$\begin{flalign}S_{k}=\sum_{n=0}^{k} (-1)^{n}\cdot a_{n}\;\;\;S_{k+2}=S_{k}+(-1)^{k+1}\cdot a_{k+1}+(-1)^{k+2}\cdot a_{k+2} &&\end{flalign}$$
- $k$ pari: $S_{k+2}=S_{k}-a_{k+1}+a_{k+2}\implies S_{k+2}\leq S_{k}$
- $k$ dispari: $S_{k+2}=S_{k}+a_{k+1}-a_{k+2}\implies S_{k+2}\geq S_{k}$
Inoltre $\lim_{ k \to +\infty } S_{k+1}-S_{k}=0$ quindi $\sum_{n=0}^{+\infty}(-1)^{n}\cdot a_{n}$ converge

# Serie e integrali generalizzati
$\sum_{n=0}^{+\infty}a_{n}$, definita $f(x)=a_{k}\;\;\forall x \in[k,k+1)\implies$
$$\begin{flalign}\int_{0}^{n+1} f(x)\,dx=\sum_{k=0}^{n} \int_{k}^{k+1} f(x)\,dx=\sum_{k=0}^{n}a_{k}=S_{n}  &&\end{flalign}$$
Se l'integrale è convergente allora la serie è convergente e $\sum_{n=0}^{+\infty}a_{n}=\int_{0}^{+\infty} f(x)\,dx$ e viceversa

# Criterio integrale
$n_{0}\in \mathbb{N}$, $f:[n_{0},+\infty)\to \mathbb{R}$ funzione tale che $f\geq0$ decrescente in $[n_{0},+\infty)$ e $\lim_{ x \to +\infty }f(x)=0$
Se $a_{n}=f(n)\implies$
- $\sum_{n=n_{0}}^{+\infty}a_{n}<+\infty \iff \int_{n_{0}}^{+\infty} f(x)\,dx<+\infty$
- $\sum_{n=n_{0}}^{+\infty}a_{n}=+\infty \iff \int_{n_{0}}^{+\infty} f(x)\,dx=+\infty$

# Serie armonica generalizzata
$$\begin{flalign}\sum_{n=1}^{+\infty} \frac{1}{n^{\alpha}}=\begin{cases}
+\infty,&0<\alpha\leq1 \\
\frac{1}{1-\alpha},&\alpha>1
\end{cases} &&\end{flalign}$$
