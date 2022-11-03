# Distancias entre puntos, rectas y planos (o hiperplanos) en $\mathbb{R}^n$ 

Antes de comenzar, recordemos que $\vec{P_1P_2} = P_2 - P_1 $
 

## Distancia entre dos puntos $P_1$ y $P_2$

$$d(P_1,P_2)=|| \\vec{P_1 P_2} ||=|| P_2 - P_1 ||$$

## Proyección ortogonal
Encontrar el punto  $\chi_0$ en la recta $r=\\{ t\vec{v} \mid t\in \mathbb{R}\\}$ más cercano al punto $P$.


$$ \chi_0=\text{Proy}_v(P)=\frac{\vec{P}\cdot \vec{v} }{\vec{v}\cdot\vec{v}}\vec{v} $$

## Distancia entre un punto $P_1$ y una recta $r=\\{ P_2 + t\vec{v} \mid t\in \mathbb{R}\\}$ 

$$d(P_1,r_2)=||\vec{P_1 P_2} - \frac{\vec{P_1 P_2}\cdot \vec{v}}{\vec{v} \cdot \vec{v}}v||$$ 

## Distancia entre un punto $P_1$ y un plano $\pi= \\{ \chi \in \mathbb{R}^n \mid \vec{P_2 \chi} \cdot \vec{n}= 0 \\}$ 

$$d(P_1,\pi_2)=\frac{|\vec{P_1 P_2}\cdot \vec{n}|}{||\vec{n}||}$$

## Distancia entre dos planos paralelos $\pi_1= \\{ \chi_1 \in \mathbb{R}^n \mid \vec{P_1 \chi_1} \cdot \vec{n}= 0 \\}$ y $\pi_2= \\{ \chi_2 \in \mathbb{R}^n \mid \vec{P_2 \chi_2} \cdot \vec{n}= 0 \\}$ 

$$d(\pi_1,\pi_2)=\frac{|\vec{P_1 P_2}\cdot \vec{n}|}{||\vec{n}||}$$

## Distancia entre una recta $r=\\{ P_1 + t\vec{v} \mid t\in \mathbb{R}\\}$   y un plano $\pi= \\{ \chi \in \mathbb{R}^n \mid \vec{P_2 \chi} \cdot \vec{n}= 0 \\}$ paralelos

Recordemos que la recta y el plano son paralelos si la dirección de la recta es perpendicular al vector normal del plano, es decir $\vec{v} \cdot \vec{n}= 0$

$$d(r,\pi)=\frac{|\vec{P_1 P_2}\cdot \vec{n}|}{||\vec{n}||}$$


## Mínimos cuadrados
Encontrar el punto $\chi_0$ de la ecuación vectorial $$\chi = t_1\vec{v_1} + t_2\vec{v_2} + \cdots + t_n\vec{v_n} = [\vec{v_1} \\ \\  \vec{v_2} \\ \\ \cdots \\ \\ \vec{v_n}]  \\pmatrix{t_1 \\\\ t_2 \\\\ \\vdots \\\\ t_n}=A\vec{t}$$  más cercano al punto $P$.

$$ \chi_0=A(A^T A)^{-1}A^TP$$

## Distancia entre dos rectas  $r_1=\\{ P_1 + t_1\vec{v_1} \mid t_1\in \mathbb{R}\\}$ y  $r_2=\\{ P_2 + t_2\vec{v_2} \mid t_2\in \mathbb{R}\\}$

Haciendo  $A=[\vec{v_1} \\ \\  \vec{v_2}]$ se tiene
$$d(r_1,r_2)=||(A(A^T A)^{-1}A^T-I)\vec{P_1P_2}||$$









