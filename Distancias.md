# Distancias entre puntos, rectas y planos (o hiperplanos) en $\mathbb{R}^n$ 

Antes de comenzar, recordemos que $\vec{P_1P_2} = P_2 - P_1 $
 

## Entre dos puntos $P_1$ y $P_2$

$$d(P_1,P_2)=|| \\vec{P_1 P_2} ||=|| P_2 - P_1 ||$$

## Entre un punto $P_1$ y una recta $r_2=\\{ P_2 + t\vec{v} \mid t\in \mathbb{R}\\}$ 

$$d(P_1,r_2)=||\vec{P_1 P_2} - \frac{\vec{P_1 P_2}\cdot \vec{v}}{\vec{v} \cdot \vec{v}}v||$$ 

## Entre un punto $P_1$ y un plano $\pi_2= \\{ \chi \in \mathbb{R}^n \mid \vec{P_2 \chi} \cdot \vec{n}= 0 \\}$ 

$$d(P_1,\pi_2)=\frac{|\vec{P_1 P_2}\cdot \vec{n}|}{||\vec{n}||}$$

## Entre dos planos paralelos $\pi_1= \\{ \chi_1 \in \mathbb{R}^n \mid \vec{P_1 \chi_1} \cdot \vec{n}= 0 \\}$ y $\pi_2= \\{ \chi_2 \in \mathbb{R}^n \mid \vec{P_2 \chi_2} \cdot \vec{n}= 0 \\}$ 

$$d(\pi_1,\pi_2)=\frac{|\vec{P_1 P_2}\cdot \vec{n}|}{||\vec{n}||}$$









