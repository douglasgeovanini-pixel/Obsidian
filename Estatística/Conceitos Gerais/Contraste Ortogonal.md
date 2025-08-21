São equações matemáticas que representam as diferenças entre as [[Média]]s.  Lembrando que os contrastes tem que ser escolhidos a priori, antes mesmo do experimento.
Vamos dizer que temos um contraste Y entre duas médias:
$$Y_i = m_a-m_b$$
O contrate tem 2 detalhes muito importantes, mas para ficar mais fácil de entender vamos  usar de exemplo um experimento com quatro [[Tratamento]]s e quatro médias
T$_1$ -> $m_1$
T$_2$ -> $m_2$
T$_3$ -> $m_3$
T$_4$ -> $m_4$
Primeiro detalhe temos 4 tratamentos, o número máximo de contrastes possíveis é [[Grau de liberdade]] dos tratamentos (n-1), sendo assim 3.
Segundo detalhe a soma dos coeficientes das médias tem que ser zero, a seguir mostrarei.

Se quisermos compara $m_1$ com  $m_2$ é a mesma coisa que a primeira equação, veja que existe um coeficiente que havia sido mostrado antes;
$$\hat{C}_i = m_a-m_b$$ é o mesmo que:
$$\hat{C}_i = 1\times m_a+(-1\times m_b)$$
Esse 1 e -1 são os coeficientes do contraste e a soma deles sempre tem que dar zero:
$$\hat{C}_i = \alpha _am_a-\alpha _bm_b$$
$$\sum{\alpha_a+\alpha_b=0}$$
E se aumentarmos o números de média no calculo do contraste?
 Vamos pegar $m_1$, $m_2$, $m_3$ e $m_4$
 podemos calcular esse contraste de formas diferentes, mas preste atenção sempre que calcular um contraste o próximo vai ser com os valores com mesmo sinal
 Exemplo 1:
 $$\sum{\alpha_1+\alpha_2+\alpha_3+\alpha_4=0}$$
 $$\sum{1+1-1-1=0}$$
$$\hat{C}_1 = m_1+m_2-m_3-m_4$$
Então os próximos dois cálculos terão que ser de $m_1$ com $m_2$ e $m_3$ com $m_4$
$$\hat{C}_2 = m_1-m_2$$
$$\hat{C}_3 = m_3-m_4$$
veja que foram 3 contrastes, agora vamos fazer diferente

 Exemplo 2:
 $$\sum{\alpha_1+\alpha_2+\alpha_3+\alpha_4=0}$$
 $$\sum{3-1-1-1=0}$$
$$\hat{C}_1 = 3m_1-m_2-m_3-m_4$$
Então os próximos dois cálculos terão que ser de $m_2$, $m_3$ e $m_4$, por conta que todos os valores positivos acabaram e restaram apenas os negativos.
$$\hat{C}_2 = 2m_2-m_3-m_4$$
Agora com os últimos dois valores
$$\hat{C}_3 = m_3-m_4$$

Para avaliar se existe ou não diferença entre as médias
O valor absoluto do contraste (|$\hat{C}_i$|) é comparado com o [[DMS]]