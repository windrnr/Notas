Es una gramática en donde **se requiere** que los strings $\phi$ y $\psi$, que denotan contexto en la producción $\phi A\psi \rightarrow\phi\omega\psi$, sean vacíos. Así, la posibilidad de reemplazar una letra o símbolo no terminal en una forma sentencial, es independiente de los símbolos adyacentes, es decir, **independiente al contexto**.

Todas las producciones tienen la forma $A\rightarrow\omega$ donde $A\in N \cup \textbraceleft\Sigma\textbraceright$ y $\omega\in(N\cup T)^*-\lambda$

Si A es $\Sigma$ o $A \in N$ y $\omega\in T^*$ es un string derivable a partir de A, decimos que **$\omega$ es denotado por A:**
$$L(G,A)=\textbraceleft\omega\in T^{*}/A\Longrightarrow^*\omega\textbraceright$$
Si una forma sentencial A es derivable a partir de $\Sigma$, luego $L(G,A) \subseteq L(G)$, pero la inclusión no es válida en el otro sentido. **No es generalmente cierto que $L(G,A) \supseteq L(G)$.**