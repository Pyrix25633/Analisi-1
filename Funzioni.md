# Funzione
> [!definizione]
> $D \neq \emptyset, C\neq \emptyset$
> Una funzione $f:D\to C$ è una corrispondenza (sottoinsieme dell'insieme $D \times C:=\{ (x,y):x \in D,\; y \in C \}$) che associa ad ogni elemento $x \in D$ uno ed un solo elemento $y \in C$ che si indica con $f(x)$ e si dice valore o immagine di $f$ in $x$
> $\forall x \in D \; \exists!y \in C : y=f(x)$
> - Dominio: $D$
> - Variabile indipendente: $x$
> - Codominio: $C$
> - Variabile dipendente: $y=f(x)$
> - Immagine: $\mathrm{Im}(f)=f(D)=\{ f(x):x \in D \} \subset C$
> - Una funzione si dice limitata
> 	- superiormente se $\forall x \in D\; \exists M\in \mathbb{R}:M\geq f(x)$
> 	- inferiormente se $\forall x \in D\; \exists m\in \mathbb{R}:m\leq f(x)$
> 	- se è limitata sia superiormente che inferiormente

# Iniettiva, suriettiva, biiettiva
> [!definizione]
> Una funzione $f$ si dice:
> - Iniettiva se $\forall x_{1},x_{2} \in D,\space x_{1}\neq x_{2} \implies f(x_{1}) \neq f(x_{2})$, equivalentemente $f(x_{1})=f(x_{2}) \implies x_{1}=x_{2}$
> - Suriettiva se $\forall y \in C \; \exists x \in D \mid y=f(x)$, ovvero $\mathrm{Im}(f)=C$
> - Biiettiva se $\forall y \in C \; \exists ! x \in D \mid y=f(x)$, ovvero se è sia iniettiva che suriettiva

# Composizione di funzioni
> [!definizione]
> $f:D_{f} \to C_{f}$, $g:D_{g} \to C_{g}$
> Se $C_{f} \subset D_{g}$ (quindi $\mathrm{Im}(f) \subset \mathrm{Dom}(g)$) si può definire la composizione
$g \circ f:D_{f} \to C_{g},\; (g \circ f)(x)=g(f(x))$
<div class="page-break" style="page-break-before: always;"></div>

# Funzione inversa
> [!definizione]
Se $f$ è biiettiva si può definire la funzione inversa $f^{-1}:C\to D$, $x=f^{-1}(y)$

# Grafico
> [!definizione]
> $\mathrm{Gr}(f):=\{ (x,y)\in \mathbb{R}^{2}:x \in D,\; y=f(x) \}$
> $(x,y)\in\mathrm{Gr}(f) \iff (y,x)\in \mathrm{Gr}(f^{-1})$

# Simmetrica
> [!definizione]
> Una funzione  $f$ è:
> - Pari se $f(-x) = f(x)\;\;\forall x \in D$
> - Dispari se $f(-x) = -f(x)\;\;\forall x \in D$
> - Periodica se $\exists t\in \mathbb{R} \mid f(x+t) = f(x)\;\;\forall x \in D$

# Monotona
> [!definizione]
> Una funzione $f$ si dice:
> - Crescente se $x_{1} < x_{2} \implies f(x_{1}) \leq f(x_{2})$
> - Strettamente crescente se $x_{1} < x_{2} \implies f(x_{1}) < f(x_{2})$
> - Decrescente se $x_{1} < x_{2} \implies f(x_{1}) \geq f(x_{2})$
> - Strettamente crescente se $x_{1} < x_{2} \implies f(x_{1}) > f(x_{2})$

# Disuguaglianza triangolare
> [!formule]
> La funzione modulo ha la seguente proprietà:
> $|x_{1} + x_{2}| \leq |x_{1}| + |x_{2}|\;\;\forall x_{1}, x_{2} \in \mathbb{R}$
