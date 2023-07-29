# Operaciones con Strings

## Alfabeto:
conjunto finito de símbolos atómicos (no divisibles que se emplean en la construcción de sentencias).

## String de longitud $K$ sobre un alfabeto $V$:
Es una secuencia de $k$ símbolos en $V$.
$$\omega=v_{1} \ v_{2} \ ... \ v_k$$
$$|\omega|=k$$
## String vacío:
Es el único string que no contiene símbolos y es indicado con la letra $\lambda$.
$$|\lambda|=0$$
## $W_k$:
Conjunto de todos los strings de longitud $k$ sobre un alfabeto $V$:
$$W_k=\textbraceleft{\omega/|\omega|=k\textbraceright}$$
$W_0$ es el conjunto que contiene el string vacío.
$$W_0=\textbraceleft \lambda \textbraceright = \boldsymbol{\lambda}$$
El conjunto: $$W=\bigcup\limits_{k=0}^{\infty} W_{k}$$
es el conjunto de todos los strings definidos sobre $V$, incluyendo el string vacío.

## Concatenación de strings
Operación binaria definida sobre el conjunto $W$. La concatenación de los strings $\omega$ y $\phi$ es la secuencia de símbolos formada al extender la secuencia $\omega$ con la secuencia $\phi$.
$$m(\omega,\phi) = v_{1}\ v_{2}\ ...v_{m}\ u_{1} \ u_{2} \ ... u_{n}=\omega . \phi=\omega\phi$$
La notación $\omega^k$ es empleada para indicar la concatenación de $k$ copias del string $\omega$.

### Propiedades de la concatenación de strings:
1. $\forall \ \omega, \phi \ \in W:$ $\omega \ . \ \phi \ \in \ W$
2. $\forall \omega, \phi, \psi \in W:$ $\omega .(\phi . \psi) = (\omega . \phi). \psi$
3. $\forall\omega\in W:$ $\omega . \lambda = \lambda . \omega=\omega$
4. $\omega . \phi$ no necesariamente igual a $\phi . \omega \rightarrow$ **la concatenación de strings no es conmutativa**
5. $\forall\omega,\phi\in W:$ $|\omega . \phi| = |\omega| + |\phi|$
### Reverso de un string
Dado el string $\omega=v_1v_{2}...v_n$ se define el reverso como:
$$\omega^R=v_{n}...v_2v_1$$