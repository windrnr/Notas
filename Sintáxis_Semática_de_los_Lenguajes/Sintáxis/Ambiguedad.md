Una misma sentencia puede ser generada mediante múltiples derivaciones diferentes en una gramática dada; esto no causa problemas siempre que **todas ellas se correspondan a un único árbol de derivación**. El problema de la ambigüedad surge cuando, para determinada sentencia, la gramática provee árboles de derivación distintos.

![[Pasted image 20230710183014.png]]

Si una gramática es [[Ambiguedad|ambigua]], posiblemente existe una gramática no ambigua que genere el mismo lenguaje; sin embargo, no existe un algoritmo que permita decidir si tal gramática existe.

Un lenguaje $L$ es inherentemente ambiguo si **todas** las gramáticas que lo generan son ambiguas; igual que el caso anterior, no hay manera de decidir si un lenguaje es inherentemente ambiguo.

Existe una propiedad donde, si **en cada etapa de la derivación se reescribe el símbolo no terminal ubicado más a la izquierda en la forma sentencial**, estas derivaciones permiten una definición precisa de las gramáticas ambiguas.
![[Pasted image 20230710183046.png]]

**Cada oración generada por una gramática libre de contexto y asociada a un dado árbol, tiene una única derivación por izquierda**.

![[Pasted image 20230710183153.png]]

Hay dos maneras por las cuales puede surgir ambigüedad en una gramática libre de contexto:
1. Alguna sentencia tiene dos árboles de derivación estructuralmente diferentes. **(Ambigüedad estructural)**
2. Alguna sentencia tiene dos árboles de derivación estructuralmente similares pero con diferentes rótulos en sus nodos interiores. **(Ambigüedad asociada a rótulo)**