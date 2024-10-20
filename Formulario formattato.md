
--- start-multi-column: ID_d54e
```column-settings
Number of Columns: 3
Largest Column: standard
Border: off
```

### Proposizioni

| $P$ | $Q$ | $P\implies Q$ |
| --- | --- | ------------- |
| V   | V   | V             |
| V   | F   | F             |
| F   | V   | V             |
| F   | F   | V             |

| $P$ | $Q$ | $P\iff Q$ |
| --- | --- | --------- |
| V   | V   | V         |
| V   | F   | F         |
| F   | V   | F         |
| F   | F   | V         |

### Massimo e minimo
$A \subset \mathbb{R}, A \neq \emptyset$
- Può non esistere
- Se esiste è unico
- $M \in A$ si dice massimo per $A$ ($M=\mathrm{max}(A)$) se $\forall x \in A \; M \geq x$
- $m \in A$ si dice minimo per $A$ ($m=\mathrm{min}(A)$) se $\forall x \in A \; m \leq x$

### Estremo
$A \subset \mathbb{R}, A \neq \emptyset$
- $\bar{x} \in \mathbb{R}$ si dice estremo superiore di $A$ ($\bar{x}=\sup A$) se è il più piccolo dei maggioranti, ovvero $$\begin{flalign}\begin{cases}\forall x \in A\;\;x\leq \bar{x}\\ \forall\epsilon>0\;\exists x \in A:x-\epsilon<\bar{x}\end{cases} &&\end{flalign}$$
- $\underline{x} \in \mathbb{R}$ si dice estremo inferiore di $A$ ($\underline{x}=\inf A$) se è il più grande dei minoranti, ovvero $$\begin{flalign}\begin{cases}\forall x \in A\;\;x\geq \underline{x}\\ \forall\epsilon>0\;\exists x \in A:x-\epsilon>\underline{x}\end{cases} &&\end{flalign}$$

### Disuguaglianza triangolare
$\forall x_{1}, x_{2} \in \mathbb{R} \;\;\; |x_{1} + x_{2}| \leq |x_{1}| + |x_{2}|$

--- column-break ---

### Trasformazioni di funzioni
- Riflessione rispetto all'asse delle x: $-f(x)$
- Riflessione rispetto all'asse delle y: $f(-x)$
- Valore assoluto di f: $|f(x)|$
- Parte positiva di f:  $$\begin{flalign}f_{+}(x)=\begin{cases}f(x) & f(x) \geq 0 \\0 & f(x) < 0\end{cases}&&\end{flalign}$$
- Parte negativa di f: $$\begin{flalign}f_{-}(x) \begin{cases}-f(x) & f(x) \leq 0 \\0 & f(x) > 0\end{cases}&&\end{flalign}$$
- Traslazione verticale: $f(x) + a$
- Traslazione orizzontale: $f(x + a)$
- Riscalamento verticale: $k\cdot f(x)$
	- dilatazione se $k>1$
	- compressione se $0<k<1$
- Riscalamento orizzontale: $f(k\cdot x)$
	- dilatazione se $0<k<1$
	- compressione se $k>1$
### Numeri complessi
- Forme:
	- Cartesiana: $z=x+yi$
	- Trigonometrica: $z=|z|(\cos\theta + i\sin\theta)$
	- Esponenziale: $z=|z| e^{i\theta}$
- Coniugato: $\bar{z}=x-iy$
- Modulo: $|z| = \sqrt{x^{2} + y^{2}}$
- Reciproco: $z^{-1}=\frac{\bar{z}}{|z|}$
- Somma:
	- $z_{1}+z_{2}=(x_{1}+x_{2}) + i(y_{1}+y_{2})$
- Prodotto:
	- $z\cdot a=ax+iay$
	- $z_{1}\cdot z_{2}=(x_{1}x_{2}-y_{1}y_{2}) + i(x_{1}y_{2}+x_{2}y_{1})$
	- $z_{1}\cdot z_{2}=|z_{1}||z_{2}|(\cos(\theta_{1}+\theta_{2}) + i\sin(\theta_{1}+\theta_{2}))$
	- $z_{1}\cdot z_{2}=|z_{1}||z_{2}|e^{i(\theta_{1}+\theta_{2})}$
- Quoziente:
	- $$\begin{flalign}\frac{z_{1}}{z_{2}}=\frac{|z_{1}|}{|z_{2}|}(\cos(\theta_{1}-\theta_{2}) + i\sin(\theta_{1}-\theta_{2}))&&\end{flalign}$$
	- $$\begin{flalign}\frac{z_{1}}{z_{2}}=\frac{|z_{1}|}{|z_{2}|}e^{i(\theta_{1}-\theta_{2})}&&\end{flalign}$$
- Elevamento a potenza:
	- $z^{n}=|z|^{n}(\cos(n\cdot\theta) + i\sin(n\cdot\theta))$
	- $z^{n}=|z|^{n}e^{i\cdot n\cdot\theta}$
- Proprietà:
	- $\overline{z+w}=\bar{z}+\bar{w}$
	- $\overline{z\cdot w}=\bar{z}\cdot \bar{w}$
	- $z+\bar{z}=2\mathrm{Re}(z)$
	- $z-\bar{z}=2i\mathrm{Im}(z)$
	- $|z|=0\iff z=0$
	- $|z+w|\leq |z|+|w|$
	- $z\cdot\bar{z}=|z|^{2}$
	- $|z\cdot w|=|z|\cdot |w|$

--- column-break ---

### Fattoriale
$n! := 1\cdot 2\cdot 3\cdot {\dots} \cdot n$
Proprietà:
- $n! = n\cdot(n-1)!$
- $$\begin{flalign} \frac{n!}{(n-k)!}=n\cdot (n-1)\cdot {\dots}\cdot (n-k+1) &&\end{flalign}$$
### Coefficiente binomiale
$$
\begin{flalign}
\binom{n}{k}=\frac{n!}{k!\cdot (n-1)!}=\frac{n\cdot (n-1)\cdot {\dots}\cdot (n-k-1)}{k!}&&
\end{flalign}
$$
Proprietà:
- $$\begin{flalign} \binom{n}{0}=\binom{n}{n}=1&& \end{flalign}$$
- $$\begin{flalign} \binom{n}{k}=\binom{n}{n-k}&& \end{flalign}$$
- $$\begin{flalign} \binom{n}{k}=\binom{n-1}{k-1}+\binom{n-1}{k}&& \end{flalign}$$
- Binomio di Newton
$$
\begin{flalign}
(a+b)^{n}=\sum_{k=0}^{n} \binom{n}{k}\cdot a^{n-k}\cdot b^{k}&&
\end{flalign}
$$
### Successioni
- Limitatezza delle successioni convergenti:
$a_{n} \to l \implies \forall n\in \mathbb{N} \; \exists M\in \mathbb{R}: |a_{n}|\leq M$
- Successione di Nepero:
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
- Permanenza del segno: $x_{n}\to l>0 \implies \exists \bar{n} : \forall n\geq \bar{n} \; x_{n}>0$
- Confronto: $a_{n} \to a, \; b_{n} \to b \; \exists \bar{n} : \forall n \geq \bar{n} \; a_{n}\leq b_{n} \implies a\leq b$
- Due carabinieri: $$\begin{flalign}a_{n} \to a, \; b_{n} \to b \; \exists \bar{n} :\forall n\geq \bar{n}\; a_{n}\leq c_{n}\leq b_{n} \\\implies c_{n} \to l &&\end{flalign}$$
- Criterio del rapporto: $$\begin{flalign} \forall n \in \mathbb{N}, \; a_{n}>0&&\\ \frac{a_{n+1}}{a_{n}} \to l&& \end{flalign}$$
	- $l>1 \implies a_{n}\to +\infty$
	- $l<1 \implies a_{n}\to 0$
- Gerarchia di infiniti: $\log_{a}(n); \; n^{\alpha}; \; a^{n}; \; n!; \; n^{n}$

--- end-multi-column

--- start-multi-column: ID_ksal
```column-settings
Number of Columns: 2
Largest Column: standard
Border: off
```

### Limiti notevoli
- $$\begin{flalign}\lim_{ x \to 0 } \frac{\sin(x)}{x}=1 &&\end{flalign}$$
- $$\begin{flalign}\lim_{ x \to 0 } \frac{1-\cos(x)}{x^{2}}=\frac{1}{2} &&\end{flalign}$$
- $$\begin{flalign}\lim_{ x \to 0 } \frac{\tan(x)}{x}=1 &&\end{flalign}$$
- $$\begin{flalign}\lim_{ x \to \pm \infty } \left( 1+\frac{1}{x} \right)^{x}=e &&\end{flalign}$$
- $$\begin{flalign}\lim_{ x \to 0 } (1+x)^{1/x}=e &&\end{flalign}$$
- $$\begin{flalign}\lim_{ x \to 0 } \frac{\ln(1+x)}{x}=1 &&\end{flalign}$$
- $$\begin{flalign}\lim_{ x \to 0 } \frac{e^{x}-1}{x}=1 &&\end{flalign}$$
- $$\begin{flalign}\lim_{ x \to 0 } \frac{a^{x}-1}{x}=\ln(a) &&\end{flalign}$$
- $$\begin{flalign}\lim_{ x \to 0 } \frac{(1+x)^{\alpha}-1}{x}=\alpha &&\end{flalign}$$


--- column-break ---

### Sin e cos
| $\theta$     | $0$ | $\frac{\pi}{6}$      | $\frac{\pi}{4}$      | $\frac{\pi}{3}$      | $\frac{\pi}{2}$ |
| ------------ | --- | -------------------- | -------------------- | -------------------- | --------------- |
| $\sin\theta$ | $0$ | $\frac{\sqrt{3}}{2}$ | $\frac{\sqrt{2}}{2}$ | $\frac{1}{2}$        | $1$             |
| $\cos\theta$ | $1$ | $\frac{1}{2}$        | $\frac{\sqrt{2}}{2}$ | $\frac{\sqrt{3}}{2}$ | $0$             |

| $\sin(-x)=-\sin(x)$                                 | $\cos(-x)=\cos(x)$                                  | $\tan(-x)=-\tan(x)$                                |
| --------------------------------------------------- | --------------------------------------------------- | -------------------------------------------------- |
| $\sin\left( \frac{\pi}{2}\pm x \right)=\mp \cos(x)$ | $\cos\left( \frac{\pi}{2}\pm x \right)=\mp \sin(x)$ | $\tan\left( \frac{\pi}{2}\pm x \right)=\mp\cot(x)$ |
| $\sin(\pi\pm x)=\mp \sin(x)$                        | $\cos(\pi\pm x)=-\cos(x)$                           | $\tan(\pi\pm x)=\pm \tan(x)$                       |

| $\sin(x\pm y)=\sin(x)\cos(x)\pm \cos(x)\sin(y)$      |
| ---------------------------------------------------- |
| $\cos(x\pm y)=\cos(x)\cos(y)\mp \sin(x)\sin(y)$      |
| $\sin(2x)=2\sin(x)\cos(x)$                           |
| $\cos(2x)=\cos ^{2}(x)-\sin ^{2}(x)=2\sin ^{2}(x)-1$ |

--- column-break ---

--- end-multi-column

