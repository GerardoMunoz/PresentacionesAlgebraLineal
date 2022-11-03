# Planos en 3D

En las ecuaciones del plano se distinguen los siguientes valores:
* $u, v$ : Dos vectores dirección del plano 
* $n=\pmatrix{n_x \\\\ n_y \\\\ n_z}$ : Un vector perpendicular al plano
* $P, Q, R$ : Tres puntos


## Representaciones No Paramétricas

Son ecuaciones que se cumplen sólo para los puntos $\vec{\chi}=(x,y,z)$

Son útiles para verificar si un punto pertenece al plano.



| Nombre | Ecuación | Limitaciones | 
|---------|----------|-------|
| Una ecuación lineal de tres variables | $n_x x + n_y y + n_z z  = d$ | Varias |
| Ecuación punto, normal | $(\chi - P) \cdot \vec{n}=0$ | Varias |



## Representaciones Paramétricas

Los parámetros son las variables $t,s \in \mathbb{R}$. Cada valor de $t$ y de $s$ generan un punto $\vec{\chi}=(x,y,z)$.

Son útiles para encontrar puntos en el plano.

| Nombre | Ecuación | Limitaciones |
|---------|----------|-------|
| Interpolación de tres puntos|$\vec{\chi}=(1-t-s)P + t Q + s R$ | Varias|
|Ecuación vectorial del plano| $\vec{\chi}=P + s\vec{u} + t\vec{v}$| Varias|


## Descripción de las limitaciones:
* Varias: Hay varias representaciones para la misma recta.





