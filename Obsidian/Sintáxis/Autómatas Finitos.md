Tiene las siguientes características:
- Discreto.
- Finito.
- Determinístico,
- Efectúa acciones secuenciales.

## Propiedades de las Máquinas de Estados Finitos
Considerando el acciones de una máquina $M$ que es un [[Traductores|traductor]].

Los símbolos de entrada pertenecen a un alfabeto finito $S$, denominado **alfabeto de entrada**. $$s(t)\in S \qquad t=1,2,\dots$$
Igualmente, los símbolos de salida pertenecen al alfabeto finito $R$, o **alfabeto de salida**.

La secuencia de símbolos de entrada presentados a la máquina se denomina **estímulo**, mientras que la secuencia resultante de símbolos de salida se denomina **respuesta de $M$ al estímulo**.

Supongamos que $M$ posee $n$ partes y que $q^{(i)}(t)$ es el estado asumido por la parte $i$ en el momento $t$. El **estado total** de $M$ al tiempo $t$ es la n-upla:$$q(t)=(q^{(1)}(t),q^{(2)}(t),\dots,q^{(n)}(t))$$
Si cada parte no puede asumir más de $k$ estados, no es posible que $M$ tenga más de $\boldsymbol{k}^{n}$ estados totales. (**número finito de estados**).

Vamos a indicar con $q(t)$ el estado (total) de $M$ en el momento $t$, y vamos a emplear $Q$ para indicar el **conjunto de estados finitos** de M.

Como el comportamiento futuro de $M$ depende del estado actual de $M$, es necesario que la máquina esté en un estado fijo y conocido antes de que ningún estímulo se aplique. El estado total correspondiente a esta situación se denomina **estado inicial** $q_I$.

Cuando el símbolo de entrada $s(t+1)$ ingresa, influye en partes de las máquina que estarán en un estado representado por $q(t)$ y, establecerán un nuevo estado representado por el estado $q(t+1)$. **El nuevo estado depende solamente de cual es el símbolo que arriba y de cual es el estado de $M$ previo a su arribo**.
$$q(t+1)=f(q(t),s(t+1)) \qquad t \geq0$$
**Función de transición de estados de $M$**. Donde su dominio y rango son:
$$f:Q\times S\rightarrow Q$$
Al canal de salida de esta máquina convergen señales de ciertas partes de $M$. **El símbolo de salida generado por el arribo de un símbolo de entrada depende solamente de qué símbolo arriba y de cuál es el estado de $M$ previo al arribo de la señal.**
$$r(t+1)=g(q(t),s(t+1)) \qquad t\geq0$$
**Función de salida de $M$**. Donde su dominio y rango son:
$$g:Q\times S\rightarrow R$$

### Resumen de propiedades
1. El comportamiento de $M$ se define solamente en los momentos $t=0, 1, 2,\dots$
2. Los símbolos de entrada $s(t)$ se eligen de un alfabeto finito de entrada $S$.
3. Los símbolos de salida $r(t)$ se eligen de un alfabeto finito de salida $R$.
4. El comportamiento de $M$ se determina únicamente por la secuencia de símbolos de entrada que ingresa.
5. El comportamiento de $M$ procede a lo largo de una secuencia de estados, cada uno de los cuales es un miembro del conjunto de estados $Q$.
6. Hay un estado inicial $q_I$ de $M$ que describe la condición de las partes de $M$ antes de que se presente algún estímulo.

## Tipos de autómatas finitos

[[Máquinas con Salida Asociada a Transición]]
[[Máquinas con Salida Asociada a Estado]]



