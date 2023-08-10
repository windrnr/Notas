# Secuencias de estados
La secuencia de estados asociados con un camino del diagrama de estados de una máquina corresponde a la aplicación de un string de símbolos de entrada y a la emisión de un string de símbolos de salida.

Ahora, definido de forma más precisa un estado sucesor es:
![[Pasted image 20230711164320.png]]

Mediante esta definición, hemos extendido el dominio de la función de transición de estados de forma que incluya a todos los **strings de entrada**, en lugar de simples **símbolos de entrada**.
$$f:Q\times S^{*}\rightarrow Q$$
donde:
$$f(q,\omega) = q' \iff q \xRightarrow{\omega}q' \qquad y \qquad f(q,\lambda)=q \quad \forall q\in Q$$

Luego las siguientes afirmaciones son equivalente:
1. Hay una secuencia de
2. estados admisible desde $q$ a $q'$ para el string de entrada $\omega = s(1)s(2)\dots s(t))$.
3. $q\xRightarrow{\omega}q'$
4. $f(q,\omega)=q'$
5. Hay un camino dirigido entre $q$ y $q'$ en el diagrama de estados de $M$ cuyas transiciones están rotuladas mediante los símbolos de entrada $s(1),s(2),\dots ,s(t)$

![[Pasted image 20230711164329.png]]

# Conversión entre máquinas con salida asociada a transición y salida asociada a estado

**Las [[Máquinas con Salida Asociada a Estado]] tienen una respuesta para el string vacío**.

Entonces, para decidir que dos máquinas son equivalentes, decidimos que:
![[Pasted image 20230711165953.png]]
![[Pasted image 20230711170020.png]]

Para construir una $M_t$ a partir de una $M_s$ se observará la siguiente regla: **Si un estado $q \in M_s$ tiene salida $r$, cada transición de $M_t$ que finalice en el estado $q$ se rotulará con la salida $r$**.

El caso inverso, es algo más complicado debido a que $M_t$ puede contener un estados $q$ cuyas transiciones de entrada estén rotuladas por más de un símbolo de salida.

Es por eso que permitimos que los estados $M_s$ sean el conjunto de pares estado-salida $Q_{t}\times R$ definidos en $M_t$. La máquina $M_s$ va a ingresar al estado $(q,r)$ cada vez que $M_t$ ingresa al estado $q$ y emite un símbolo de salida $r$.

De esta manera, podemos concluir que los dos modelos de máquina de estados finitos ([[Máquinas con Salida Asociada a Estado|salida asociada a estados]] y [[Máquinas con Salida Asociada a Transición|salida asociada a transición]]) tienen una potencia computacional equivalente, con la excepción de que la máquina con salida asociada a estado provee una respuesta al **string vacío**.
