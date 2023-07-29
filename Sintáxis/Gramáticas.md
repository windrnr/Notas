Reglas utilizadas en la generación de las cadenas de un lenguaje.
Tener en cuenta que:

$$(G_{3}\subseteq G_{2}\subseteq G_1\subseteq G_{0})$$
- [[Gramáticas Tipo 0 (No restringidas)]] 
- [[Gramáticas Tipo 1 (Sensibles al contexto)]]
- [[Gramáticas Tipo 2 (Libres de contexto)]]
- [[Gramáticas Tipo 3 (Regulares)]]

![[Pasted image 20230710174737.png]]

**Describe** y **Genera** [[Lenguajes Abstractos]].
**Equivalente** a una [[Máquinas Abstractas|Máquina Abstracta]].

A partir de una gramática se puede construir una [[Máquinas Abstractas|máquina]] reconocedora del lenguaje generado por esa gramática.

Buscan capturar aquello relacionado con la **estructura** o **sintaxis** del lenguaje.

Una gramática es un conjunto(alfabeto), más un conjunto finitos de reglas que gobiernan cómo se pueden generar las oraciones (strings de un [[Lenguajes Abstractos|lenguaje]]).


## Gramáticas Formales

**El problema central en la descripción de un lenguaje es proveer una especificación finita para una clase de objetos esencialmente infinita.**

Dado un alfabeto $V$, el conjunto $V^*$ es la totalidad de todos los posibles strings definidos sobre $V$. Un lenguaje $L$ definido sobre $V$ es un subconjunto arbitrario de $V^*$.

Una forma de representar un lenguaje es emplear un **[[Aceptores|aceptor]]** del lenguaje. Si el aceptor posee un número finito de estados funcionalmente relevantes, él en sí mismo constituye una **representación finita**.

Otra alternativa es emplear una **[[Gramáticas|representación generativa]]** del lenguaje, empleando un conjunto de reglas que si son seguidas en un orden válido van a permitir la construcción de strings válidos al lenguaje.

**Las reglas gramaticales poseen una propiedad recursiva que permite la representación finita de un conjunto infinito de sentencias.**

Una gramática tiene tres componentes fundamentales:
- El alfabeto o colección de símbolos a partir del cual se construyen las sentencias que describen el lenguajes. Estas se denominan letras o **símbolos terminales** de la gramática.
- Un conjunto de símbolos que indiquen o denoten frases llamados letras o **símbolos no terminales**.
- Un conjunto o colección de reglas **gramaticales o producciones**.

Para completar la especificación del lenguaje, es necesario un punto inicial para la aplicación de las producciones. El signo $\Sigma$ denominado **símbolo sentencia**, se reserva para esta función.
![[Pasted image 20230710173617.png]]

La secuencia de formas sentenciales requeridas para generar una sentencia se conoce como derivación de la sentencia de acuerdo a la gramática.
![[Pasted image 20230710173714.png]]

Si $\alpha \rightarrow \beta$ es una producción de G y $\omega =  \phi \alpha \psi$ y $\omega^{'}=\phi\beta\psi$ son formas sentenciales, se dice que $\omega^{'}$ se deriva inmediatamente de  $\omega$ en G. Esta relación se indica de la forma:
$$\omega \Longrightarrow\omega^{'}$$
Si $\omega_1,\omega_{2,}\dots\omega_n$ es una secuencia de formas sentenciales tales que $\omega_1\Longrightarrow\omega_2\Longrightarrow\dots\Longrightarrow\omega_n$, se dice que $\omega_n$ es derivable de $\omega_1$. Esta relación se indica de la siguiente forma:
$$\omega_1\Longrightarrow^{*}\omega_n$$

![[Pasted image 20230710173753.png]]

No existe ningún procedimiento general que permita determina cuándo ciertas gramáticas arbitrarias generan el mismo tipo de lenguaje.