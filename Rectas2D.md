# Rectas en 2D

En las ecuaciones de la recta se distinguen los siguientes valores:
* $m$: Pendiente.
* $a$, $b$: Cortes con los ejes $x$, $y$.
* $v=\pmatrix{v_x \\\\ v_y}$ : Vector dirección
* $n=\pmatrix{n_x \\\\ n_y}$ : Vector normal
* $P=\pmatrix{P_x \\\\ P_y}$, $Q$ : Dos puntos

## Representaciones No Paramétricas

Son ecuaciones que se cumplen sólo para los puntos $(x,y)$

Son útiles para verificar si un punto pertenece a la recta.



| Nombre | Ecuación | Limitaciones |
|---------|----------|-------|
| Fun. recta.| $y=mx+b$ | Vert |
| Puntos de corte | $\frac{x}{a} + \frac{y}{b} =1$ | Vert, Hor, Orig|
|Simétrica | $\frac{x - P_x}{v_x} = \frac{y - P_y}{v_y}$| Hor, Vert, Varias|
| Una Ecuación lineal de dos variables | $n_x x + n_y y  = d$ | Varias |



## Representaciones Paramétricas

El parámetro es la variable $t \in \mathbb{R}$. Cada valor de $t$ genera un punto $\vec{\chi}=(x,y)$.

Son útiles para encontrar puntos en una recta.

| Nombre | Ecuación | Limitaciones |
|---------|----------|-------|
| Interpolación de dos puntos|$\vec{\chi}=(1-t)P + tQ$ | Varias|
|Ecuación vectorial de la recta| $\vec{\chi}=P + t\vec{v}$| Varias|
| Ecuaciones paramétricas | $x=P_x + t v_x$ $y=P_y + t v_y$ | Varias |


## Descripción de las limitaciones:
* Hor: No permite rectas horizontales
* Vert: No permite rectas verticales
* Orig: No permite rectas que pasan por el origen
* Varias: Hay varias representaciones para la misma recta.









