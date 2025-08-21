É um teste estatístico para testar todo e qualquer contraste entre [[Média]]s.  Ele não exige que os constrates sejam [[Contraste Ortogonal]], nem exige que os contrastes sejam escolhidos anteriormente ao experimento. Usado após uma Análise de Variância ([[ANOVA]])

Hipóteses do teste
$H_0$ <- C = 0 

$H_Ø$ <- C ≠ 0

A estatística do teste:

$$s=\sqrt{(I-1)F_{tab}\frac{QM_{resíduo}}{K}\sum\limits_{i=1}^{I}(a^2)}$$
Sendo $I$ o número de níveis do [[Fator]] em estudo ([[Tratamento]])
$(I-1)$ é o GL [[Grau de liberdade]] dos tratamentos
[[QM]]$_{resíduo}$ o quadrado médio do [[Resíduo]]
$F_{tab}$ é o valor tabelado a nível de significância $\alpha$, GL do fator do estudo e GL do resíduo 
K é o número de repetições de cada média de cada tratamento