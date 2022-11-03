# Rectas en 3D

En las ecuaciones de la recta se distinguen los siguientes valores:
* $v=\pmatrix{v_x \\\\ v_y \\\\ v_z}$ : Vector dirección
* $n=\pmatrix{n_x \\\\ n_y \\\\ n_z}$, $m=\pmatrix{m_x \\\\ m_y \\\\ m_z}$ : Dos vectores perpendiculares
* $P=\pmatrix{P_x \\\\ P_y \\\\ P_z}$, $Q$ : Dos puntos


## Representaciones No Paramétricas

Son ecuaciones que se cumplen sólo para los puntos $(x,y,z)$

Son útiles para verificar si un punto pertenece a la recta.



| Nombre | Ecuación | Limitaciones |
|---------|----------|-------|
| Simétricas | $\frac{x - P_x}{v_x} = \frac{y - P_y}{v_y} = \frac{z - P_z}{v_z}$| Paral, Varias|
| Dos ecuaciones lineales de tres variables | $n_x x + n_y y + n_z z = d$,    $m_x x + m_y y + m_z z = e$| Varias |



## Representaciones Paramétricas

El parámetro es la variable $t \in \mathbb{R}$. Cada valor de $t$ genera un punto $\vec{\chi}=(x,y,z)$.

Son útiles para encontrar puntos en una recta.

| Nombre | Ecuación | Limitaciones |
|---------|----------|-------|
| Interpolación de dos puntos|$\vec{\chi}=(1-t)P + tQ$ | Varias|
|Ecuación vectorial de la recta| $\vec{\chi}=P + t\vec{v}$| Varias|
| Ecuaciones paramétricas | $x=P_x + t v_x$,   $y=P_y + t v_y$,   $z=P_z + t v_z$ | Varias |


## Descripción de las limitaciones:
* Paral: No permite rectas paralelas a un plano
* Varias: Hay varias representaciones para la misma recta.








