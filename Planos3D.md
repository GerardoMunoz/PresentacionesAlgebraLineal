# Planos en 3D

En las ecuaciones del plano se distinguen los siguientes valores:
* $v_1, v_2$ : Dos vectores dirección del plano 
* $n=\pmatrix{n_x \\\\ n_y \\\\ n_z}$ : Un vector normal al pl
* $P, Q, R$ : Tres puntos


## Representaciones No Pramétricas

Son ecuaciones que se cumplen sólo para los puntos $\vec{\chi}=(x,y,z)$

Son útiles para verificar si un punto pertenece al plano.



| Nombre | Ecuación | Limitaciones |
|---------|----------|-------|
| Una ecuación lineal de tres variables | $n_x x + n_y y + n_z z  = d$ | Varias |
| Ecuación punto, normal | $(\chi - P) \cdot \vec{n}=0$ | Varias |



## Representaciones Pramétricas

El parametro es la varible $t \in \mathbb{R}$. Cada valor de $t$ genera un punto $\vec{\chi}=(x,y,z)$.

Son útiles para encontrar puntos en el plano.

| Nombre | Ecuación | Limitaciones |
|---------|----------|-------|
| Interpolación de tres puntos|$\vec{\chi}=(1-t_1-t_2)P + t_1 Q + t_2 R$ | Varias|
|Ecuacion vectorial del plano| $\vec{\chi}=P + t_1\vec{v}_1 + t_2\vec{v}_2$| Varias|


## Descripción de las limitaciones:
* Varias: Hay varias representaciones para la misma recta.





