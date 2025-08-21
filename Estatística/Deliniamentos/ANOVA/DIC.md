O Delineamento Inteiramente Casualizado (DIC) é um modelo experimental, no caso do [[ANOVA]] o mais simples. 
Para utilizar temos como pressupostos:
- As unidades são idênticas ([[Homogêneo]]);
- As [[Unidades experimentais]] são atribuídas aleatoriamente;
- Obedece os [[Princípio de casualização]] e[[ Princípio repetição]].


O modelos linear que explica as variações da variável resposta no DIC, é dado da seguinte forma:
$$y_{ij}=m+t_i+e_{ij}$$
sendo:
$y_{ij}$ o valor da [[Variável Resposta]]
$m$ a constante inerente a toda parcela
$t_{i}$ representa o efeito do [[Tratamento]]
$e_{ij}$ representa o [[Resíduo]]

Tabela do DIC:

| FV           | GL  | [[SQ]] | [[QM]] | F$_{cal}$ | F$_{tab}$ |
| ------------ | --- | ------ | ------ | --------- | --------- |
| Tratamentos  |     |        |        |           |           |
| [[Resíduo]]s |     |        |        |           |           |
| Total        |     |        |        |           |           |
*GL é o valor do [[Grau de liberdade]]
Tabela do DIC([[P valor]]):

| FV           | GL  | [[SQ]] | [[QM]] | P valor |
| ------------ | --- | ------ | ------ | ------- |
| Tratamentos  |     |        |        |         |
| [[Resíduo]]s |     |        |        |         |
| Total        |     |        |        |         |
O F$_{cal}$ é calculado pelo [[Teste F]], onde o valor do QM dos tratamentos é o [[Numerador]] e o QM dos resíduos é o [[Denominador]] .

[[Teste de hipótese]] do DQL:
$H_0$ <- as médias dos tratamentos são igual ou não existe diferença entre os tratamentos.

$H_Ø$ <- p ≠ pelo menos uma das médias dos tratamentos é diferente dos demais.

Pressupostos do teste 
1. **Independência**: o valor de uma observação possui um erro, que deve ser independente dos demais, seja em um mesmo tratamento, seja em tratamentos diferentes.
2. **Normalidade**: os erros devem possuir uma distribuição normal
3. **Homogeneidade**: os erros devem ser estimados todos da mesmo população, isso implica que cada tratamento deve ter aproximadamente a mesma variância;
4. **Aditividade**: o efeito de cada um dos termos que compõem o modelo devem ser aditivos.