#flashcards 

Una gramática formal cuyas producciones son dela  forma $\sigma A \psi \rightarrow \sigma\omega\psi$ con $\sigma,\psi=\lambda$ y $\omega\neq\lambda$ se denomina:: Gramática Libre de Contexto
<!--SR:!2023-07-24,1,230-->

La expresión $f_s((q,r'),s)=(f_t(q,s),g(q,s))=(q',r) \qquad \forall q\in Q,s\in S, r'\in R$ se utiliza en:: La construcción de $M_s$ a partir de $M_t$
<!--SR:!2023-07-24,1,228-->

Los autómatas linealmente acotados se relacionan con las:: Gramáticas sensibles al contexto.
<!--SR:!2023-07-24,1,228-->

El conjunto de todos los strings de longitud K sobre un alfabeto V se denota:: $W_k$
<!--SR:!2023-07-24,1,228-->

En la construcción de una gramática lineal por derecha a partir de un AEF, la razón por la cual si $M$ tiene $q\xrightarrow{s}q'$, luego $G$ tiene $N(q)\rightarrow sN(q)$ es:: $E(q)\supseteq sE(q')$
<!--SR:!2023-07-24,1,228-->

Definición de $\lambda$-clausura de q:: $\lambda[q]={q}\cup \lambda[q'] \quad \forall q' \in P(q,\lambda)$
<!--SR:!2023-07-24,1,228-->

En la construcción de un AEF a partir de una gramática lineal por derecha, la razón por la cual si G tiene $A\rightarrow sB$, luego $M$ tiene $QA\xrightarrow{s}QB$::  $L(G,A)\supseteq sL(G,B)$
<!--SR:!2023-07-24,1,228-->

Definición formal de las gramáticas tipo 0:: $\sigma A \psi \rightarrow \sigma\omega\psi \qquad con \quad \sigma,\omega,\psi \in (N\cup T)^{*} \quad y \quad A\in N$
<!--SR:!2023-07-24,1,228-->

Definición formal de las gramáticas tipo 1:: $\sigma A \psi \rightarrow \sigma\omega\psi \quad \Sigma\rightarrow\lambda \qquad con \quad A\in N\cup \{\Sigma\} \quad y \quad con \quad \sigma,\omega,\psi \in (N\cup T)^{*}-\{\lambda\}$ 
<!--SR:!2023-07-24,1,228-->

Definición formal de las gramáticas tipo 2:: $\Sigma\rightarrow\lambda \quad y  \quad A\rightarrow\omega \qquad con \quad\omega\in (N\cup T)^{*}-\{\lambda\} \quad y \quad A\in N\cup\{\Sigma\}$
<!--SR:!2023-07-24,1,228-->

Definición formal de las gramáticas tipo 3:: $A\rightarrow aB,\quad A\rightarrow a,\quad \Sigma\rightarrow\lambda \qquad con \quad A\in N\cup\{\Sigma\}, \quad B\in N, \quad a\in T$
<!--SR:!2023-07-24,1,228-->
