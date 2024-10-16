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
### Sin e cos
| $\theta$     | $0$ | $\frac{\pi}{6}$      | $\frac{\pi}{4}$      | $\frac{\pi}{3}$      | $\frac{\pi}{2}$ |
| ------------ | --- | -------------------- | -------------------- | -------------------- | --------------- |
| $\sin\theta$ | $0$ | $\frac{\sqrt{3}}{2}$ | $\frac{\sqrt{2}}{2}$ | $\frac{1}{2}$        | $1$             |
| $\cos\theta$ | $1$ | $\frac{1}{2}$        | $\frac{\sqrt{2}}{2}$ | $\frac{\sqrt{3}}{2}$ | $0$             |
### Disuguaglianza triangolare
$\forall x_{1}, x_{2} \in \mathbb{R} \space \mid x_{1} + x_{2} \mid \space \leq \space \mid x_{1} \mid + \mid x_{2} \mid$
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
- Modulo: $\mid z \mid = \sqrt{x^{2} + y^{2}}$
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
- Proprietà
	- $\overline{z+w}=\bar{z}+\bar{w}$
	- $\overline{z\cdot w}=\bar{z}\cdot \bar{w}$
	- $z+\bar{z}=2\mathrm{Re}(z)$
	- $z-\bar{z}=2i\mathrm{Im}(z)$
	- $|z|=0\iff z=0$
	- $|z+w|\leq |z|+|w|$
	- $z\cdot\bar{z}=|z|^{2}$
	- $|z\cdot w|=|z|\cdot |w|$
