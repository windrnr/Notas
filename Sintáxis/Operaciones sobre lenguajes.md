# Operaciones con lenguajes
## Lenguaje
Definido sobre un alfabeto $V$ es cualquier conjunto de strings definidos sobre el conjunto $V$. Así, cada lenguaje definido en $V$ es un subconjunto del conjunto $W$ de todos los strings en $V:L\subseteq W$.

Las operaciones básicas que se aplican a los lenguajes son también las operaciones básicas aplicables a conjuntos, es decir, unión, intersección y complemento relativo a $W$.

## Concatenación de Lenguajes
Dados dos lenguajes $A$ y $B$ definimos a la concatenación de los mismos
$$A . B=\textbraceleft\omega . \phi / \omega \in A, \phi \in B \textbraceright $$
al conjunto de strings que resulta de extender cada string definido en $A$ con cada string definido en $B$.

### Propiedades de la concatenación de lenguajes:
- $\forall A \subseteq W:$ $A.\boldsymbol{\lambda} = \boldsymbol{\lambda}.A = A$ -> El conjunto $\boldsymbol{\lambda}=\textbraceleft\lambda\textbraceright$ es un elemento identidad en la concatenación de lenguajes.
- $\forall A \subseteq W:$ $A.\emptyset = \emptyset . A = \emptyset$ -> No debe confundirse el conjunto $\boldsymbol{\lambda}$ (conjunto unitario que contiene al string vacío) con el conjunto $\emptyset$ (elemento absorbente).
- $\forall A,B,C \subseteq W:$ $A.(B.C) = (A.B).C$
- $A.B$ no necesariamente igual a $B.A$ -> **La concatenación de lenguajes no es conmutativa**.
- $\forall A,B,C \subseteq W:$ $A.(B\cup C) = A.B \cup A.C$ -> la concatenación distribuye sobre la unión.
- $A.(B\cap C)$ no necesariamente igual a $A.B \cap A.C$ -> **La concatenación no distribuye sobre la intersección**.

## Clausura de un Lenguaje
Sea $V$ un alfabeto y $W$ el universo de strings generados a partir de $V$; para un lenguaje $A \subseteq W$, definimos los conjuntos $A^{k,}k \geq 0$  mediante
$$A^{0}=\boldsymbol{\lambda} \qquad A^{k+1} = A^k.A$$
Cada uno de estos conjuntos $A^k$ es un subconjunto de $W$ dado que **$W$ es cerrado a la operación concatenación**. Luego la unión de todos estos conjuntos es:
$$A^*=\bigcup\limits_{k=0}^{\infty} A^{k}$$
El cual es un subconjunto de $W$ y se denomina **clausura de A**. El operador $*$ se conoce como la estrella de Kleene. La clausura de un lenguaje contiene cada string que puede formarse mediante la concatenación de un número arbitrario de strings tomados del lenguajes.

## Reverso de un lenguaje
El reverso de un lenguaje $L$ contiene al reverso de cada string definido en $L$:
$$L^{R}=\textbraceleft\omega^{R} / \omega\in L\textbraceright$$
Si un lenguaje es igual a su reverso ello no implica que cada uno de los strings del mismo sea igual a su reverso.