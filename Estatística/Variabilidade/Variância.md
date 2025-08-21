É uma [[Estatísticas]] que mede a [[Variabilidade]] da [[amostra]], ou seja, quanto maior a variância maior é a variabilidade da amostra e vice-versa.

Diferenças entre Variância amostral e Variância populacional:
Quando tratamos de uma análise de população temos todos os valores da população, porém quando tratamos de uma amostra, mesmo sendo representativa, ela não contêm todos os valores da população, se calcularmos pela mesma fórmula do Variância populacional subestimamos o valor, que será via de regra menor que o Variância real. Então ao invés de utilizarmos o valor do tamanho amostral, usamos o valor do quanto os valores dentro da amostra podem variar ([[Grau de liberdade]]).


Variância amostral -Dp- (S)
$$\frac{\sum(\bar{x}-x)}{n-1}$$
Variância populacional -Dp- (σ)
$$\frac{\sum(μ-x)}{N}$$

Outra forma de visualizar:

$$σ=\frac{\sum\limits_{i=1}^{n}(μ-x_i)}{N}\rightarrow \frac{\sum\limits_{i=1}^{n}(x^2-2μx_i+μ^2)}{N}$$
$$=\frac{\sum\limits_{i=1}^{n}(x_i^2)}{N}- \frac{\sum\limits_{i=1}^{n}(2μx_i)}{N}+\frac{\sum\limits_{i=1}^{n}(μ^2)}{N}$$
$$=\frac{\sum\limits_{i=1}^{n}(x_i^2)}{N}- \frac{2μ\sum\limits_{i=1}^{n}(x_i)}{N}+\frac{μ^2\sum\limits_{i=1}^{n}(1)}{N}$$
lembremos que μ é a [[Média]] da população
ou seja $\frac{\sum\limits_{i=1}^{n}(x_i)}{N}$ , com isso vamos manipular mais um pouco a equação
$$=\frac{\sum\limits_{i=1}^{n}(x_i^2)}{N}- 2μ\mathbf{\frac{\sum\limits_{i=1}^{n}(x_i)}{N}}+\frac{μ^2\sum\limits_{i=1}^{n}(1)}{N}$$
$$=\frac{\sum\limits_{i=1}^{n}(x_i^2)}{N}- 2μμ+μ^2\frac{\sum\limits_{i=1}^{n}(1)}{N}$$
outro detalhe importante $\sum\limits_{i=1}^{n}(1)=N$

$$=\frac{\sum\limits_{i=1}^{n}(x_i^2)}{N}- 2μ^2+μ^2\frac{N}{N}$$
$$=\frac{\sum\limits_{i=1}^{n}(x_i^2)}{N}- 2μ^2+μ^2$$
$$=\frac{\sum\limits_{i=1}^{n}(x_i^2)}{N}- μ^2$$
por fim temos
$$\frac{\sum\limits_{i=1}^{n}x_i^2}{N}- \frac{(\sum\limits_{i=1}^{n}x_i)^2}{N^2}$$