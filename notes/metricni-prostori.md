# Metrični prostori

## def 1.1 - Metrični prostor

Naj bo $M$ množica. Razdalja oz. *metrika* je funkcija
$d: M \times M \rightarrow \mathbb{R}$, za katero velja (za $\forall x,y,z
\in M$):

1. $d(x,y) = 0 \Leftrightarrow x = 4$
2. $d(x,y) = d(y,x) \qquad \text{(simetrična)}$
3. $d(x,y) \leq d(x,z) + d(z,y)$

Če je $d$ razdalja na množici $M$, potem je $(M,d)$ **metrični prostor**.

### Opomba 1.2

$d:M \times M \rightarrow R$. Pravilno bi bilo pisati $d:(x,y) \mapsto
d((x,y)) \in \mathbb{R}$.

### Opomba 1.3

Če je $M = \empty$, potem $M \times M = \empty$. Obstaja natanko ena
funkcija $d: \empty \rightarrow \mathbb{R}$, ki je *prazna* funkcija,
torej $d = \empty$.

> Tu se spomnimo definicijo funkcije, po kateri je funkcija $f: A \rightarrow
B$ podmnožica od $A \times B$, da velja za $\forall x \in A$, da $\exists!
y \in B$, da velja ...f.

Tedaj $f = \empty \subset \empty \times \mathbb{R} = \empty$.
