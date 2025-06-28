# Equazione differenziale
> [!definizione]
> $F(t,y(t),y'(t),\dots,y^{(n)(t)})=0$
> $F:A\subset \mathbb{R}^{n+2}\to \mathbb{R}$ con $y(t):I\subset \mathbb{R}\to \mathbb{R}$
> Una funzione $y(t)$ è soluzione dell'equazione differenziale se è derivabile $n$ volte e tale che $(t,y(t),\dots,y^{(n)}(t))\in A$ e $F(t,y(t),\dots,y^{(n)}(t))=0\;\;\forall t\in I$
> La soluzione generale è l'insieme di tutte le soluzioni
> $n$ si definisce ordine dell'equazione differenziale

### Problema di Cauchy
> [!definizione]
> $$\begin{flalign}\begin{cases}
y'(t)=f(t,y(t)) \\
y(t_{0})=y_{0}
\end{cases} &&\end{flalign}$$
> Si chiama problema di Cauchy un sistema composto da un'equazione differenziale in forma normale e una condizione iniziale

# Esistenza e unicità locale
> [!teorema]
> $R=[a,b]\times[c,d]$, $(t_{0},y_{0})\in(a,b)\times(c,d)$, $f:R\to \mathbb{R}$
> Se $f$
> - è continua nella variabile $t$, ovvero $\forall y\in(c,d)$ $t\to f(t,y)$ è continua
> - è lipschitziana nella variabile $y$ uniformemente rispetto a $t$, ovvero $\exists L\geq0$ (costante di Lipschitz di $f$) $:\forall(t,y_{1}),(t,y_{2})\in R\;\;|f(t,y_{1})-f(t,y_{2})|\leq L\cdot |y_{1}-y_{2}|$
> 
> allora esiste un'unica soluzione locale del problema di Cauchy, ovvero esiste un intervallo aperto $I\subset[a,b]$, $t_{0}\in I$ ed esiste un'unica funzione $y:I\to \mathbb{R}$ che risolve il problema di Cauchy su $I$
<div class="page-break" style="page-break-before: always;"></div>

# Equazioni a variabili separabili
> [!formule] Formula
> Sono equazioni della forma $y'(t)=a(t)\cdot b(y(t))$, $a,b:I\to \mathbb{R}$ continue
> ovvero la funzione $f(t,y(t))$ è del tipo $f(t,y)=a(t)\cdot b(y)$
> 
> $\exists \bar{y}\in \mathbb{R}:b(\bar{y})=0\implies y(t)=\bar{y}$ è soluzione
> $\nexists \bar{y}\in \mathbb{R}:b(\bar{y})=0\implies$ $$\begin{flalign} \frac{y'(t)}{b(y(t))}=a(t)\implies \int \frac{y'(t)}{b(y(t))}\,dt=\int a(t)\,dt \implies z=y(t)\;\;dz=y'(t)dt &&\end{flalign}$$
> $$\begin{flalign}\int \frac{dz}{b(z)}=\int a(t)\,dt\implies B(z)=A(t)+c\implies y(t)=B^{-1}(A(t)+c) &&\end{flalign}$$

# Equazioni lineari del primo ordine
> [!formule] Formula
> Sono equazioni della forma $a_{1}(t)y'(t)+a_{0}(t)y(t)=g(t)$, $a_{1}(t),a_{0}(t):I\to \mathbb{R}$ continue
> Se $a_{1}(t)\neq0\;\;\forall t\in I$
> $$\begin{flalign}y'(t)+\frac{a_{0}(t)}{a_{1}(t)}y(t)=\frac{g(t)}{a_{1}(t)}\;\;\;y'(t)+a(t)y(t)=f(t) &&\end{flalign}$$
> Se $f(t)=0$ l'equazione è omogenea, altrimenti è completa
> La soluzione generale dell'equazione completa si ottiene sommando la soluzione generale dell'equazione associata ($f=0$) a una qualunque soluzione dell'equazione completa
> Si cerca una soluzione dell'equazione omogenea $y'(t)+a(t)y(t)=0$
> $e^{A(t)}y'(t)+a(t)e^{A(t)}y(t)=0\;\;\;D[e^{A(t)}y(t)]=e^{A(t)}y'(t)+a(t)e^{A(t)}y(t)\implies$
> $e^{A(t)}y(t)=c\in \mathbb{R}\;\;\;y(t)=c\cdot e^{-A(t)}$
> Si cerca una soluzione dell'equazione completa $y'(t)+a(t)y(t)=f(t)$
> $D[e^{A(t)}y(t)]=f(t)e^{A(t)}\;\;\;F(t)=\int e^{A(t)}f(t)\,dt\implies e^{A(t)}y(t)=F(t)+c$
> $y(t)=e^{-A(t)}(F(t)+c)$
> 
> Sono dette equazioni lineari perché della forma $L(y(t))=f(t)$, $L(y(t))=y'(t)+ay(t)$ e $L(\lambda f+\mu g)=\lambda L(f)+\mu L(g)$
<div class="page-break" style="page-break-before: always;"></div>

# Equazioni lineari del secondo ordine
> [!formule] Formula
> Sono equazioni della forma $a_{2}(t)y''(t)+a_{1}(t)y'(t)+a_{0}(t)y(t)=g(t)$
> Se $g(t)=0$ l'equazione è omogenea, altrimenti è completa
> Se $a_{2}(t),a_{1}(t),a_{0}(t)$ sono costanti l'equazione si dice a coefficienti costanti
> Se $a_{2}(t)\neq0\;\;\forall t\in I$
> $$\begin{flalign}y''(t)+\frac{a_{1}(t)}{a_{2}(t)}y'(t)+\frac{a_{0}(t)}{a_{2}(t)}y(t)=\frac{g(t)}{a_{2}(t)}\;\;\;y''(t)+a(t)y'(t)+b(t)y(t)=f(t) &&\end{flalign}$$
> Se $a(t),b(t),f(t)$ sono continue su $I$, $t_{0}\in I$, allora $\forall y_{0},y_{1}\in \mathbb{R}$
> $$\begin{flalign}\begin{cases}
y''(t)+a(t)y'(t)+b(t)y(t)=f(t) \\
y'(t_{0})=y_{1} \\
y(t_{0})=y_{0}
\end{cases} &&\end{flalign}$$
> ammette un'unica soluzione $y(t)\in C^{2}(I)$
> Considerando le equazioni della forma $ay''(t)+by'(t)+cy(t)=0$ omogenee e a coefficienti costanti
> Si cercano soluzioni della forma $y(t)=e^{rt}$
> $ar^{2}e^{rt}+bre^{rt}+cr^{rt}=0\;\;\;e^{rt}(ar^{2}+br+c)=0\iff ar^{2}+br+c=0\;\;\;\Delta=b^{2}-4ac$
> - $\Delta>0$:
>   $r_{1},r_{2}$ soluzioni reali distinte
>   La soluzione generale è $y(t)=c_{1}e^{r_{1}t}+c_{2}e^{r_{2}t}\;\;c_{1},c_{2}\in \mathbb{R}$
> - $\Delta<0$:
>   $r_{1}=\alpha+i\beta,\;r_{2}=\alpha-i\beta$ soluzioni complesse coniugate
>   $e^{r_{1}t}=e^{\alpha t}e^{i\beta t}=e^{\alpha t}(\cos(\beta t)+i\sin(\beta t))$
>   La soluzione generale è $y(t)=e^{\alpha t}(c_{1}\cos(\beta t)+c_{2}\sin(\beta t))\;\;c_{1},c_{2}\in \mathbb{R}$
> - $\Delta=0$:
>   $r_{1}=r_{2}=\gamma$ soluzioni reali coincidenti
>   La soluzione generale è $y(t)=e^{\gamma t}(c_{1}+tc_{2})\;\;c_{1},c_{2}\in \mathbb{R}$
