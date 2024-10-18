# Funzione
$D \neq \emptyset, C\neq \emptyset$
Una funzione $F:D\to C$ è una corrispondenza che associa ad ogni elemento $x \in D$ uno ed un solo elemento $y \in C$ che si indica con $f(x)$ e si dice valore o immagine di $f$ in $x$
$\forall x \in D \; \exists!y \in C : y=f(x)$
- Variabile indipendente: $x$
- Variabile dipendente: $y=f(x)$
- Una funzione si dice limitata
	- superiormente se $\forall x \in D\; \exists M\in \mathbb{R}:M\geq f(x)$
	- inferiormente se $\forall x \in D\; \exists m\in \mathbb{R}:m\leq f(x)$
	- se è limitata sia superiormente che inferiormente
# Corrispondenza
Sottoinsieme dell'insieme $D \times C:=\{ (x,y):x \in D,\; y \in C \}$

# Dominio, codominio, immagine
- Dominio: $D$
- Codominio: $C$
- Immagine: $\mathrm{Im}(f)=f(D)=\{ f(x):x \in D \} \subset C$

# Iniettiva, suriettiva, biiettiva
- Iniettiva: $\forall x_{1},x_{2} \in D,\space x_{1}\neq x_{2} \implies f(x_{1}) \neq f(x_{2})$, equivalentemente $f(x_{1})=f(x_{2}) \implies x_{1}=x_{2}$
- Suriettiva: $\forall y \in C \; \exists x \in D \mid y=f(x)$, ovvero $\mathrm{Im}(f)=C$
- Biiettiva: $\forall y \in C \; \exists ! x \in D \mid y=f(x)$, ovvero se è sia iniettiva che suriettiva

# Composizione di funzioni
$f:A \to B,\; g:C \to D$
Se $B \subset C$ (quindi $\mathrm{Im}(f) \subset \mathrm{Dom}(g)$) si può definire la composizione
$g \circ f:A \to D,\; (g \circ f)(x)=g(f(x))$

# Funzione inversa
Se $f$ è biiettiva si può definire la funzione inversa $f^{-1}:C\to D\;\;\;\; x=f^{-1}(y)$

# Grafico
$\mathrm{Gr}(f):=\{ (x,y)\in \mathbb{R}^{2}:x \in D,\; y=f(x) \}$
$(x,y)\in\mathrm{Gr}(f) \iff (y,x)\in \mathrm{Gr}(f^{-1})$

# Simmetrica
- Pari $f(-x) = f(x)$
- Dispari $f(-x) = -f(x)$
- Periodica $\exists T \mid f(x+T) = f(x)$

# Monotona
- Crescente $x_{1} < x_{2} \implies f(x_{1}) \leq f(x_{2})$
- Strettamente crescente $x_{1} < x_{2} \implies f(x_{1}) < f(x_{2})$
- Decrescente $x_{1} < x_{2} \implies f(x_{1}) \geq f(x_{2})$
- Strettamente crescente $x_{1} < x_{2} \implies f(x_{1}) > f(x_{2})$
