Somatório de quadrados é o valor dado através da seguinte fórmula:
$$Sq=\sum\limits_{i=1}^{n}(μ-x_i)\rightarrow \sum\limits_{i=1}^{n}(x^2-2μx_i+μ^2)$$
$$=\sum\limits_{i=1}^{n}(x_i^2)-\sum\limits_{i=1}^{n}(2μx_i)+\sum\limits_{i=1}^{n}(μ^2)$$
$$=\sum\limits_{i=1}^{n}(x_i^2)- 2μ\sum\limits_{i=1}^{n}(x_i)+μ^2\sum\limits_{i=1}^{n}(1)$$
detalhe importante $\sum\limits_{i=1}^{n}(1)=N$
$$=\sum\limits_{i=1}^{n}(x_i^2)- 2μ\sum\limits_{i=1}^{n}(x_i)+μ\mu N$$
Como $\mu =$ $\frac{\sum\limits_{i=1}^{n}(x_i)}{N}$ , vamos manipular mais um pouco a equação
$$=\sum\limits_{i=1}^{n}(x_i^2)- 2μ\sum\limits_{i=1}^{n}(x_i)+μN\frac{\sum\limits_{i=1}^{n}(x_i)}{N}$$
$$=\sum\limits_{i=1}^{n}(x_i^2)- 2μ\sum\limits_{i=1}^{n}(x_i)+μ\sum\limits_{i=1}^{n}(x_i)$$
$$=\sum\limits_{i=1}^{n}(x_i^2)- μ\sum\limits_{i=1}^{n}(x_i)$$
$$=\sum\limits_{i=1}^{n}(x_i^2)-\frac{\sum\limits_{i=1}^{n}(x_i)}{N}\sum\limits_{i=1}^{n}(x_i)$$

$$=\sum\limits_{i=1}^{n}(x_i^2)- \frac{(\sum\limits_{i=1}^{n}(x_i))^2}{N}$$
vamos chamar $\frac{\sum\limits_{i=1}^{n}x_i}{N}$ de C temos
$$\frac{\sum\limits_{i}^{n}x_{i}^2}{N}- C$$
Se considerarmos $N= i*j$ e que o somatório é de valores em uma matriz, temos a fórmula do Somatório de quadrados Totais
$$\frac{\sum\limits_{i,j}^{I,J}x_{i,j}}{I,J}- C$$
Se pegarmos apenas de um tratamento temos que o somatório de quadrados dos [[Tratamento]]s, temo que SQ é igual a
$$\frac{\sum\limits_{i}^{I}x_{i}}{J}- C$$
Nesse caso $J$ representa o número de tratamentos

Se for um [[DIC]]
O SQ dos [[Resíduo]]s é calculado pela diferença:
$$SQ_{total}-SQ_{tratamentos}$$
Caso for um [[DBC]] temos mais um SQ para calcular antes:
O somatório de quadrados dos Blocos
$$\frac{\sum\limits_{j}^{J}x_{j}}{I}- C$$
E seu SQ de resíduo é calculada pela seguinte diferença:
$$SQ_{resíduos}=SQ_{total}-SQ_{tratamentos}-SQ_{blocos}$$
Caso for um [[DQL]] temos mais 2 SQ, em comparação ao DIC, para calcular antes:
