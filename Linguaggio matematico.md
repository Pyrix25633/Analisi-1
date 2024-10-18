# Insiemi
- Definizione: $A:=\{1,2,3,4\}$
- Appartiene: $2\in A$
- Non appartiene: $7\not\in A$
- Unione: $A \cup B = \{x:x \in A \lor x \in B\}$
- Intersezione: $A \cap B = \{x:x \in A \land x \in B\}$
- Differenza: $A \setminus B = \{ x:x \in A \land x \not\in B \}$
- Insieme vuoto: $V := \emptyset$
- Contenuto: $A \subset B \iff \forall x \in A \; x \in B$
- Contenuto strettamente: $A \subsetneq B \iff A \subset B \land \exists x \in B : x \not\in A$
- Uguaglianza: $A = B \iff A \subset B \land B \subset A$

# Proposizioni
- Proposizione: $P=\text{"3 è un numero pari"}$ è falsa
- Predicato: $P(x)=\text{"\(x\) è un numero pari"}$
- Implicazione: $P \implies Q$
	- Ipotesi: $P$
	- Tesi: $Q$
	- se $P$ allora $Q$
	- $Q$ solo se $P$
- Doppi implicazione: $P \iff Q$
	- $P$ equivale a $Q$
- Leggi di De Morgan:
	- $\neg (P \land Q) \iff (\neg P) \lor (\neg Q)$
	- $\neg (P \lor Q) \iff (\neg P) \land (\neg Q)$
- Quantificatore esistenziale: $\exists$
- Quantificatore universale: $\forall$
- Negazione di una proposizione contente quantificatori:
	- $\neg(\forall x \in A, P(x)) \iff \exists x \in A : \neg P(x)$
	- $\neg(\exists x \in A : P(x)) \iff\forall x \in A, \neg P(x)$

# Maggiorante e minorante
$A \subset \mathbb{R}, A \neq \emptyset$
- $M \in \mathbb{R}$ si dice maggiorante per $A$ se $\forall x \in A \; M \geq x$
- $m \in \mathbb{R}$ si dice minorante per $A$ se $\forall x \in A \; m \leq x$
- $A$ si dice limitato:
	- superiormente se ammette almeno un maggiorante
	- inferiormente se ammette almeno un minorante
	- se è limitato sia superiormente che inferiormente

# Massimo e minimo
$A \subset \mathbb{R}, A \neq \emptyset$
- Può non esistere
- Se esiste è unico
- $M \in A$ si dice massimo per $A$ se $\forall x \in A \; M \geq x$
- $m \in A$ si dice minimo per $A$ se $\forall x \in A \; m \leq x$

# Estremo
$A \subset \mathbb{R}, A \neq \emptyset$
- $\bar{x} \in \mathbb{R}$ si dice estremo superiore di $A$ ($\bar{x}=\sup A$) se è il più piccolo dei maggioranti
- $\underline{x} \in \mathbb{R}$ si dice estremo superiore di $A$ ($\underline{x}=\inf A$) se è il più piccolo dei maggioranti

# Assioma di completezza di $\mathbb{R}$
$A \subset \mathbb{R}, A \neq \emptyset$
se $A$ è limitato superiormente, allora $\exists \sup A \in \mathbb{R}$

# Proprietà di Archimede
$\forall x \in \mathbb{R} \; \exists n \in \mathbb{N} : n>x$, ovvero $\sup \mathbb{N} = +\infty$

# Densità di $\mathbb{Q}$ in $\mathbb{R}$
$a,b \in \mathbb{R}, \; a<b \; \exists q \in \mathbb{Q} : a<q<b$