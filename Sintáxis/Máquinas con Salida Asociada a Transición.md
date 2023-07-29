---
sr-due: 2023-07-25
sr-interval: 4
sr-ease: 270
---

#review
Conocido también como Autómata de Mealy
![[Pasted image 20230710193630.png]]
 Para describir a una máquina de estados finitos particular, es necesario especificar la función de transición de estados y la función de salida. Existen dos representaciones standard: la **tabla de estados** y el **diagrama de estados**.

## Tabla de estados
es una representación tabular de las dos funciones, empleando una fila para cada estado y una columna para cada símbolo de entrada.
![[Pasted image 20230710195550.png]]

## Diagrama de estados
Es un grafo dirigido en el cual los nodos corresponde a los estados de la máquina y los arcos indican las posibles transiciones de un estado a otro. Cada arco está rotulado con el símbolo de entrada que causa la transición y el símbolo de salida que es generado.
![[Pasted image 20230710195557.png]]

Las secuencias de estados se indican como pares (estado, símbolo de salida) unidos por flechas rotuladas con el símbolo de entrada que causa la transición indicada.
$$q\rightarrow^{{s}/{r}}q'\quad para \quad indicar

\left\{
\begin{aligned}
f(q,s)=q'\\
g(q,s)=r
\end{aligned}
\right.

$$


Tiene una potencia computacional equivalente a las [[Máquinas con Salida Asociada a Estado]].