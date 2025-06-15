# Coppie ordinate di numeri reali
> [!definizione]
> L'insieme $\mathbb{C}$ dei numeri complessi è definito come l'insieme delle coppie ordinate di numeri reali: $\mathbb{C}=\mathbb{R}\times \mathbb{R}=\{ (x,y):x \in \mathbb{R},\; y \in \mathbb{R} \}$
> L'insieme dei numeri complessi contiene l'insieme dei numeri reali ($\mathbb{R}\subsetneq \mathbb{C}$)

### Casi particolari
> [!definizione]
> Convenzionalmente si identificano le coppie $(x, 0)\in \mathbb{R}^{2}$ con $x$
> Convenzionalmente si chiamano le coppie $(0,y)\in \mathbb{R}^{2}$ numeri immaginari puri
> In particolare il numero complesso $(0,1)$ è detto unità immaginaria e lo si denota con $i$

### Parte reale e parte immaginaria
> [!definizione]
> $z=(x,y)\in \mathbb{C}$
> - $x=\mathrm{Re}(z)$ denota la parte reale
> - $y=\mathrm{Im}(z)$ denota la parte immaginaria

### Operazioni
> [!formule]
> Somma
> $z_{1}+z_{2}=(x_{1},y_{2})+(x_{2},y_{2})=(x_{1}+x_{2},\;y_{1}+y_{2})\;\;\forall z_{1},z_{2}\in \mathbb{C}$
> Prodotto scalare
> $a\cdot z=a\cdot(x,y)=(ax,ay)\;\;\forall z\in \mathbb{C},a\in \mathbb{R}$

# Forma cartesiana
> [!definizione]
> $z=(x,y)=(x,0)+(0,y)=(x,0)+y(0,1)=x+iy$
<div class="page-break" style="page-break-before: always;"></div>

### Operazioni
> [!formule]
> Somma
> $z_{1}+z_{2}=(x_{1}+x_{2}) + i(y_{1}+y_{2})\;\;\forall z_{1},z_{2}\in \mathbb{C}$
> Prodotto scalare
> $a\cdot z=ax+iay\;\;\forall z\in \mathbb{C},a\in \mathbb{R}$
> Prodotto
> $z_{1}\cdot z_{2}=(x_{1}x_{2}-y_{1}y_{2}) + i(x_{1}y_{2}+x_{2}y_{1})\;\;\forall z_{1},z_{2}\in \mathbb{C}$

### Coniugato
> [!definizione]
> $\bar{z}=x-iy$

### Modulo
> [!definizione]
> $|z| = \sqrt{x^{2} + y^{2}}$

### Proprietà
> [!formule]
> $\overline{z+w}=\bar{z}+\bar{w}$
> $\overline{z\cdot w}=\bar{z}\cdot \bar{w}$
> $z+\bar{z}=2\mathrm{Re}(z)$
> $z-\bar{z}=2i\mathrm{Im}(z)$
> $|z|=0\iff z=0$
> $|z+w|\leq |z|+|w|$
> $z\cdot\bar{z}=|z|^{2}$
> $|z\cdot w|=|z|\cdot |w|$

### Reciproco
> [!definizione]
> $$\begin{flalign}z^{-1}=\frac{\bar{z}}{|z|^{2}} &&\end{flalign}$$
<div class="page-break" style="page-break-before: always;"></div>

# Forma trigonometrica
> [!definizione]
> Un punto si può individuare anche indicando la sua distanza dall'origine $\rho\geq 0$ e l'angolo formato con l'asse delle $x$ $\theta \in[0,2\pi)$
> La coppia $(\rho,\theta)$ individua le coordinate polari associate al punto
> $$\begin{flalign}\begin{cases}
x=\rho \cos(\theta) \\
y=\rho \sin(\theta)
\end{cases} &&\end{flalign}$$
> $$\begin{flalign}\begin{cases}
\rho=\sqrt{x^{2}+y^{2}}=|z| \\
\theta=\mathrm{Arg}(z)
\end{cases} &&\end{flalign}$$

### Operazioni
> [!formule]
> Prodotto
> $z_{1}\cdot z_{2}=|z_{1}||z_{2}|(\cos(\theta_{1}+\theta_{2}) + i\sin(\theta_{1}+\theta_{2}))\;\;\forall z_{1},z_{2}\in \mathbb{C}$
> Quoziente
> $$\begin{flalign}\frac{z_{1}}{z_{2}}=\frac{|z_{1}|}{|z_{2}|}(\cos(\theta_{1}-\theta_{2}) + i\sin(\theta_{1}-\theta_{2}))\;\;\forall z_{1},z_{2}\in \mathbb{C}\land |z_{2}|\neq0&&\end{flalign}$$
> Elevamento a potenza
> $z^{n}=|z|^{n}(\cos(n\cdot\theta) + i\sin(n\cdot\theta))\;\;\forall z\in \mathbb{C},n\in \mathbb{R}$

# Forma esponenziale
> [!definizione]
> L'esponenziale complesso è definito come $e^{i\theta}:=\cos(\theta)+i\sin(\theta)$

> [!osservazione]-
> $e^{i\pi}=\cos(\pi)+i\sin(\pi)=-1$
<div class="page-break" style="page-break-before: always;"></div>

### Operazioni
> [!formule]
> Prodotto
> $z_{1}\cdot z_{2}=|z_{1}||z_{2}|e^{i(\theta_{1}+\theta_{2})}\;\;\forall z_{1},z_{2}\in \mathbb{C}$
> Quoziente
> $$\begin{flalign}\frac{z_{1}}{z_{2}}=\frac{|z_{1}|}{|z_{2}|}e^{i(\theta_{1}-\theta_{2})}\forall z_{1},z_{2}\in \mathbb{C}\land |z_{2}|\neq 0&&\end{flalign}$$
> Elevamento a potenza
> $z^{n}=|z|^{n}e^{i\cdot n\cdot\theta}\;\;\forall z\in \mathbb{C},n\in \mathbb{R}$

### Risoluzione di equazioni
> [!formule]
> $$\begin{flalign}z_{1}=z_{2} \iff \begin{cases}
|z_{1}|=|z_{2}| \\
\mathrm{Arg}(z_{1})=\mathrm{Arg}(z_{2})+2k\pi,\; k\in \mathbb{Z}
\end{cases} &&\end{flalign}$$

# Radici di numeri complessi
> [!formule]
> Sia $n\in N, n>2$, dato $w\in \mathbb{C},w\neq0, w=|w|e^{i\theta}$, un numero complesso $z\in \mathbb{C}, z=|z|e^{i\alpha}$ è una radice $n$-esima di $w$ se $z^{n}=w$
> $z^{n}=|z|^{n}e^{i\cdot n\cdot\alpha}$
> $$\begin{flalign}\begin{cases}
|z|^{n}=|w| \\
n\cdot\alpha=\theta+2k\pi,\; k\in \mathbb{Z}
\end{cases} &&\end{flalign}$$
> $$\begin{flalign}\begin{cases}
|z|=\sqrt[n]{|w|}=|w|^{1/n} \\
\alpha=\frac{\theta+2k\pi}{n},\; k\in \mathbb{Z}
\end{cases} &&\end{flalign}$$

### Teorema fondamentale dell'algebra
> [!teorema]
> Un'equazione di grado $n\geq1$ in $\mathbb{C}$
> $a_{n}z^{n}+a_{n-1}z^{n-1}+{\dots}+a_{0},\;\;\forall a_{k}\in \mathbb{C}\land a_{n}\neq0$
ha esattamente $n$ soluzioni
