Las gramáticas regulares son una clase altamente restringida de las gramáticas libres de contexto en las cuales **el lado derecho de la producción puede contener como máximo un sólo símbolo no terminal**.

Una producción de la forma $A\rightarrow aB$ o $A\rightarrow a$ donde $A\in N \cup \textbraceleft\Sigma\textbraceright,\quad B\in N \quad y \quad a\in T$ se denomina **producción lineal por derecha**.

Una producción de la forma $A\rightarrow Ba$ o $A\rightarrow a$ donde $A\in N \cup \textbraceleft\Sigma\textbraceright,\quad B\in N \quad y \quad a\in T$ se denomina **producción lineal por izquierda**.

Una gramática formal es **lineal por derecha** si contiene solamente producciones lineales por derecha, igualmente en el caso de las lineales por izquierda.

Cada forma de gramática lineal puede contener la producción $\Sigma\rightarrow\lambda$. Las gramática lineales por derecha e izquierda se conocen como **gramáticas regulares**.

