¿Bajo qué condiciones dos autómatas exhiben el mismo comportamiento?

1. Reconocedores de Lenguajes -> sí y sólo si reconocen el mismo lenguaje.
2. Generadores de Lenguajes -> sí y sólo si generan el mismo lenguaje.
3. Traductores de Lenguajes -> sí y sólo si producen idénticas traducciones de cada string de entrada.

La cuestión de si dos autómatas presentan un comportamiento equivalente puede ser siempre resuelta cuando los autómatas sean máquinas de estados finitos. Debido a que cada uno de los autómatas puede ser puesto en una forma standard esencialmente única.

![[Pasted image 20230711171325.png]]

De la definición de equivalente se desprenden las siguientes propiedades:
- **Reflexividad**: $M\sim M$. Cada máquina es claramente equivalente a sí misma.
- **Simetría:** $M_1\sim M_{2}\Rightarrow M_{2}\sim M_1$. El intercambio de sub-índices en la definición no altera el significado de la equivalencia.
- **Transitividad**: $M_{1}\sim M_{2}\quad y \quad M_{2}\sim M_{3}\Rightarrow M_{1}\sim M_3$. Cada vez que se cumpla que $r_1(t)=r_2(t),t\geq 1 \quad y \quad r_2(t)=r_3(t),t\geq1$ se verifica que $r_1(t)=r_3(t),t\geq1$

La relación de equivalencia de máquina particiona el universo de los autómatas de estados finitos en clases de equivalencia, es decir, conjunto des máquinas mutuamente equivalentes.

## Estados equivalentes

Consideramos que **dos estados de una máquina determinada son equivalentes si es imposible distinguir entre dos copias de la máquina, cada una de ellas inicializada en cada uno de esos estados**.
![[Pasted image 20230711172111.png]]

![[Pasted image 20230711172314.png]]

## Definiciones
![[Pasted image 20230711172413.png]]

## Estados Distinguibles y k-equivalencia

![[Pasted image 20230711173120.png]]

![[Pasted image 20230711173127.png]]

## Particionado del Conjunto de Estados
![[Pasted image 20230711173231.png]]

## Construcción de una Máquina Reducida

Básicamente, construir una nueva máquina con el resultado del algoritmo de particionado.