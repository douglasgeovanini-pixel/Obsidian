O Delineamento de blocos Casualizados (DBC) é um modelo experimental, dentro do [[ANOVA]].
Para utilizar temos como pressupostos:
- As unidades são heterogenias em duas direções;
![[Pasted image 20240923153744.png]]
- Foi feito o controle local duas vezes seguindo o [[Princípio do controle local]] ou seja em duas direções;
![[Pasted image 20240923153932.png]]
- O número de parcelas a constituírem o experimento é sempre um quadrado perfeito, já que cada linha e cada coluna deverá conter todos os tratamentos uma única vez.
- O número de linhas e colunas é igual.
- As [[Unidades experimentais]] são atribuídas aleatoriamente e aparecem apenas uma vez em cada linha e coluna;
- Obedece os [[Princípio de casualização]] e[[ Princípio repetição]].

Foram formados blocos nas linhas e colunas. Ou seja a organização dos blocos é em dois sentido (linhas x colunas)
Cada bloco é formado com unidade similares ([[Homogêneo]]s), sendo o sorteio feito bloco a bloco de forma que haja homogeneidade dentro de cada bloco e que todos os tratamentos estejam presentes, estes também sendo distribuídos aleatoriamente dentro do bloco. 

Vantagens em relação ao [[DIC]]: e ao [[DBC]]:
Possibilita controlar duas fontes de variação diferentes, evitando a superestimação dos erros([[Erro aleatório]]);
Obtêm

Desvantagens do DBX:
Quando não há heterogeneidade o controle local por blocos não é eficiênte, tendo um número de [[Grau de liberdade]] do [[Resíduo]] menor que o DIC.

Quanto menor o valor do $GL_{resíduo}$ maior o quadrado médio ([[QM]]) do resíduo, assim menor será o $F_{tab}$

O modelo linear que explica as variações da variável resposta no DIC, é dado da seguinte forma:
$$y_{ij}=m+t_{ij}+l_i+c_j+e_{ij}$$
sendo:
$y_{ij}$ o valor da [[Variável]] resposta
$m$ a constante inerente a toda parcela
$t_{i}$ representa o efeito do [[Tratamento]]
$e_{ij}$ representa o [[Resíduo]]
$l_i$ representa o erro dos blocos das linhas
$c_j$ representa o erro dos blocos das colunas

Tabela do DBC:

| FV           | GL  | [[SQ]] | [[QM]] | F$_{cal}$ | F$_{tab}$ |
| ------------ | --- | ------ | ------ | --------- | --------- |
| Tratamentos  |     |        |        |           |           |
| Linhas       |     |        |        |           |           |
| Colunas      |     |        |        |           |           |
| [[Resíduo]]s |     |        |        |           |           |
| Total        |     |        |        |           |           |
*GL é o valor do [[Grau de liberdade]]
Tabela do DBC([[P valor]]):

| FV           | GL  | [[SQ]] | [[QM]] | P valor |
| ------------ | --- | ------ | ------ | ------- |
| Tratamentos  |     |        |        |         |
| Linhas       |     |        |        |         |
| Colunas      |     |        |        |         |
| [[Resíduo]]s |     |        |        |         |
| Total        |     |        |        |         |
O F$_{cal}$ é calculado pelo [[Teste F]], onde o valor do QM dos tratamentos é o [[Numerador]] e o QM dos resíduos é o [[Denominador]] .

[[Teste de hipótese]] do DQL:
Para os tratamentos
$H_0$ <- as médias dos tratamentos são igual ou não existe diferença entre os tratamentos.

$H_Ø$ <- p ≠ pelo menos uma das médias dos tratamentos é diferente dos demais.

Para as linhas
$H_0$ <- controlar a heterogeneidade no sentido horizontal não foi eficiente para avaliar o efeito do tratamento

$H_Ø$ <- p ≠ controlar a heterogeneidade no sentido horizontal foi eficiente para avaliar o efeito do tratamento

Para as colunas
$H_0$ <- controlar a heterogeneidade no sentido vertical não foi eficiente para avaliar o efeito do tratamento

$H_Ø$ <- p ≠ controlar a heterogeneidade no sentido vertical foi eficiente para avaliar o efeito do tratamento


Pressupostos do teste 
1. **Independência**: o valor de uma observação possui um erro, que deve ser independente dos demais, seja em um mesmo tratamento, seja em tratamentos diferentes.
2. **Normalidade**: os erros devem possuir uma distribuição normal
3. **Controle local**: Há heterogeneidade em duas direção que foram controladas pela repartição em blocos do experimento;
4. **Aditividade**: o efeito de cada um dos termos que compõem o modelo devem ser aditivos.

![[Imagem do WhatsApp de 2024-09-24 à(s) 13.32.59_5639d0dc.jpg]]