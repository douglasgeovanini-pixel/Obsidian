O **teste t de Student** ou somente **teste t** é um [[Teste de hipótese]] usado quando as [[Estatísticas]] seguem uma [[Distribuição t Student]].

Pressupostos do teste 
1. **Os dados são independentes**: o valor de uma observação não influencia ou afeta o valor de outras observações.
2. **A variável dependente (aquela que estamos usando para calcular a média dos grupos) é distribuída conforme uma distribuição Normal.**
3. **A variável dependente possui homogeneidade de variância dentre os grupos**

[[Hipótese Estatística]]:
$H_0$ <- μ$_1$ = μ$_2$

$H_Ø$ <- μ$_1$ ≠ μ$_2$

Cálculo:
$$t_{cal}= \frac{\bar{Y_1}-\bar{Y_2}}{\sqrt{S_c^2(\frac{1}{n_1}+\frac{1}{n_2})}}$$
$$S_c^2= \frac{(n_1)S_1^2+(n_2)S_2^2}{n_1+n_2-2}$$
$S^2$ é a [[Variância]]
$S^2_c$ é a média da [[Variância]] ponderada
n - 1 é [[Grau de liberdade]]
$\bar{Y}$ é a média amostral 

Conclusão:
Se $|t_{cal}|>t_{tab}$ então rejeitamos H0
