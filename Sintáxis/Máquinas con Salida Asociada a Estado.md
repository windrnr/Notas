Especifica la salida de una máquina de estados finitos en términos del estado de la máquina.
![[Pasted image 20230710194434.png]]

Conocida también como un autómata de Moore. Estos autómatas se representan mediante **tablas de estados** y **diagramas de estados**.
![[Pasted image 20230710195531.png]]

Las secuencias de estados se indican como pares (estado, símbolo de salida) unidos por flechas rotuladas con el símbolo de entrada que causa la transición indicada.

$$(q,r)\rightarrow^{s}(q',r') \quad significa \quad

\left\{
\begin{aligned}
f(q,s)=q'\\
h(q)=r\\
h(q')=r'
\end{aligned}
\right.

$$

Tiene una potencia computacional equivalente a las [[Máquinas con Salida Asociada a Transición]].

**Las [[Máquinas con Salida Asociada a Estado]] tienen una respuesta para el string vacío**.