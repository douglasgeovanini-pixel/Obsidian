O Delineamento de blocos Casualizados (DBC) é um modelo experimental, dentro do [[ANOVA]], no caso o mais utilizados deles.
Para utilizar temos como pressupostos:
- As unidades são heterogenias em uma direção;
- Foi feito o controle local seguindo o [[Princípio do controle local]] em uma direção;
- As [[Unidades experimentais]] são atribuídas aleatoriamente;
- Obedece os [[Princípio de casualização]] e[[ Princípio repetição]].

O bloco é formado com unidade similares ([[Homogêneo]]s), sendo o sorteio feito bloco a bloco de forma que haja homogeneidade dentro de cada bloco e que todos os tratamentos estejam presentes, estes também sendo distribuídos aleatoriamente dentro do bloco. 

Vantagens em relação ao [[DIC]]:
É mais eficiente, pois quando forma-se os blocos isola-se as variações que causam heterogeinidade, o que diminui a variação ao acaso ([[Erro aleatório]])

Desvantagens do DBX:
Quando não há heterogeneidade o controle local por blocos não é eficiênte, tendo um número de [[Grau de liberdade]] do [[Resíduo]] menor que o DIC.

Quanto menor o valor do $GL_{resíduo}$ maior o quadrado médio ([[QM]]) do resíduo, assim menor será o $F_{tab}$

O modelos linear que explica as variações da [[Variável Resposta]] no DIC, é dado da seguinte forma:
$$y_{ij}=m+t_i+\tau_i+e_{ij}$$
sendo:
$y_{ij}$ o valor da [[Variável]] resposta
$m$ a constante inerente a toda parcela
$t_{i}$ representa o efeito do [[Tratamento]]
$e_{ij}$ representa o [[Resíduo]]
$\tau_i$ representa o erro dos blocos

Tabela do DBC:

| FV           | GL  | [[SQ]] | [[QM]] | F$_{cal}$ | F$_{tab}$ |
| ------------ | --- | ------ | ------ | --------- | --------- |
| Tratamentos  |     |        |        |           |           |
| Blocos       |     |        |        |           |           |
| [[Resíduo]]s |     |        |        |           |           |
| Total        |     |        |        |           |           |
*GL é o valor do [[Grau de liberdade]]
Tabela do DBC([[P valor]]):

| FV           | GL  | [[SQ]] | [[QM]] | P valor |
| ------------ | --- | ------ | ------ | ------- |
| Tratamentos  |     |        |        |         |
| Blocos       |     |        |        |         |
| [[Resíduo]]s |     |        |        |         |
| Total        |     |        |        |         |
O F$_{cal}$ é calculado pelo [[Teste F]], onde o valor do QM dos tratamentos é o [[Numerador]] e o QM dos resíduos é o [[Denominador]] .

[[Teste de hipótese]] do DQL:
Para os tratamentos
$H_0$ <- as médias dos tratamentos são igual ou não existe diferença entre os tratamentos.

$H_Ø$ <- p ≠ pelo menos uma das médias dos tratamentos é diferente dos demais.

Para os blocos
$H_0$ <- controlar a heterogeneidade em blocos não foi eficiente para avaliar o efeito do tratamento

$H_Ø$ <- p ≠ controlar a heterogeneidade em blocos foi eficiente para avaliar o efeito do tratamento

Pressupostos do teste 
1. **Independência**: o valor de uma observação possui um erro, que deve ser independente dos demais, seja em um mesmo tratamento, seja em tratamentos diferentes.
2. **Normalidade**: os erros devem possuir uma distribuição normal
3. **Controle local**: Há heterogeneidade em uma direção que foi controlada pela repartição em blocos do experimento;
4. **Aditividade**: o efeito de cada um dos termos que compõem o modelo devem ser aditivos.

![[Imagem do WhatsApp de 2024-09-24 à(s) 13.32.59_5639d0dc.jpg]]