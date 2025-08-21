A função de [[taxa]] de falha acumulada, função de risco, hazard function ou  λ(t).
Vamos começar a elaboração
Dado que temos um intervalo de tempo ($\Delta t$) e queremos a probabilidade de falha nesse intervalo, seguiremos com:
$$S(t_1)-S(t_2)$$
Vejamos... E se quisermos a taxa? 
Teremos algo como

$$\frac{S(t_1)-S(t_2)}{(t_1-t_2)\times S(t_1)}$$
Colocando tudo em razão do $t_1$
$$\frac{S(t_1)-S(t_1+\Delta t)}{(\Delta t)\times S(t_1)}$$
$$\lambda(t)=\frac{S(t_1)-S(t_1+\Delta t)}{(\Delta t)\times S(t_1)}$$
E se o $\Delta t$ for muito pequeno?

$$\lambda(t)=\lim_{x \to a} \frac{S(t_1)-S(t_1+\Delta t)}{(\Delta t)\times S(t_1)}$$

Concluindo a a função da taxa de risco é
$$\lambda(t)=\frac{P(t\leq T< t+\Delta t | T \geq t  )}{\Delta t}$$


