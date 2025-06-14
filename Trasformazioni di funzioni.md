$f(x)=\sin(x)+\ln(x)$

```desmos-graph
left=-10; right=10; top=5; bottom=-5;
width=520; height=260;
---
f(x)=\sin(x)+\ln(x)
```

# Riflessione
Rispetto all'asse $x$: $g(x)=-f(x)$ (blu)
Rispetto all'asse $y$: $g(x)=f(-x)$ (rosso)

```desmos-graph
left=-10; right=10; top=5; bottom=-5;
width=520; height=260;
---
y=-f(x)|blue
y=f(-x)|red
f(x)=\sin(x)+\ln(x)|hidden
```

# Valore assoluto
$g(x)=|f(x)|$

```desmos-graph
left=-10; right=10; top=5; bottom=-5;
width=520; height=260;
---
y=\abs(f(x))
f(x)=\sin(x)+\ln(x)|hidden
```
<div class="page-break" style="page-break-before: always;"></div>

# Parte positiva e negativa
Parte positiva di f:  $$\begin{flalign}f_{+}(x)=\begin{cases}f(x), & f(x) \geq 0 \\0, & f(x) < 0\end{cases}&&\end{flalign}$$

```desmos-graph
left=-10; right=10; top=5; bottom=-5;
width=520; height=260;
---
y=f(x)|f(x)>=0
y=0|f(x)<0
f(x)=\sin(x)+\ln(x)|hidden
```

Parte negativa di f: $$\begin{flalign}f_{-}(x) \begin{cases}-f(x), & f(x) \leq 0 \\0, & f(x) > 0\end{cases}&&\end{flalign}$$

```desmos-graph
left=-10; right=10; top=5; bottom=-5;
width=520; height=260;
---
y=-f(x)|f(x)<=0
y=0|f(x)>0
f(x)=\sin(x)+\ln(x)|hidden
```
<div class="page-break" style="page-break-before: always;"></div>

# Traslazione
Verticale: $g(x)=f(x) + a$
- Verso l'alto se $a>0$ (blu)
- Verso il basso se $a<0$ (rosso)

```desmos-graph
left=-10; right=10; top=5; bottom=-5;
width=520; height=260;
---
y=f(x)+1|blue
y=f(x)-1|red
f(x)=\sin(x)+\ln(x)|hidden
```

Orizzontale: $g(x)=f(x + a)$
- Verso sinistra se $a>0$ (blu)
- Verso destra se $a<0$ (rosso)

```desmos-graph
left=-10; right=10; top=5; bottom=-5;
width=520; height=260;
---
y=f(x+1)|blue
y=f(x-1)|red
f(x)=\sin(x)+\ln(x)|hidden
```
<div class="page-break" style="page-break-before: always;"></div>

# Riscalamento
Verticale: $g(x)=k\cdot f(x)$
- Dilatazione se $k>1$ (blu)
- Compressione se $0<k<1$ (rosso)

```desmos-graph
left=-10; right=10; top=5; bottom=-5;
width=520; height=260;
---
y=f(x)*2|blue
y=f(x)/2|red
f(x)=\sin(x)+\ln(x)|hidden
```

Orizzontale: $g(x)=f(k\cdot x)$
- Dilatazione se $0<k<1$ (blu)
- Compressione se $k>1$ (rosso)

```desmos-graph
left=-10; right=10; top=5; bottom=-5;
width=520; height=260;
---
y=f(x/2)|blue
y=f(x*2)|red
f(x)=\sin(x)+\ln(x)|hidden
```
