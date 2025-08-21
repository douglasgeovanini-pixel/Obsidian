Área de estudo da [[Estatística]] que analisa tempo até que determinado fenômeno ocorra.
Segue a estrutura de uma análise com variáveis respostas binárias 0 & 1, sendo zero censura ([[Censura na AS]]) e 1 falha ([[falha na AS]]).

Podemos avaliar tempo médio até determinado fenômeno, comparar entre grupos diferentes o tempo para esse mesmo fenômeno ou até predizer a chance de acontecer até determinado tempo.


Vamos lá para a matemática seja [[T]] o tempo até que uma falha ocorra e [[C]] o tempo até que uma censura ocorra, temos que para um determinado indivíduo se T é menor ou igual a C, aquele fenômeno ocorreu, C maior que T quer dizer que aquele indivíduo foi censurado.

$$\delta = \begin{cases} 1, & T \leq C \\ 0, & T > C \end{cases}$$

Vamos além para aquele indivíduo o tempo em que ele foi analisado é sempre o que ocorrer primeiro, seja a censura ou a falha. Sendo então o tempo ([[t.]]):

$$t= min(T,C)$$


## Censura

A censura é algo esperado em uma Análise de Sobrevivência, mas existem casos em que o experimento se encerre e não tenha ocorrido nenhuma censura, como no gráfico a seguir.
```tikz
\begin{document}
\begin{tikzpicture}[x=0.6cm, y=0.4cm]
  % Eixos
  \draw[->] (0,0) -- (21,0) node[right] {Tempos};
  \draw[->] (0,0) -- (0,7) node[above] {Final do Estudo};
  
  % Linha pontilhada vertical (fim do estudo)
  \draw[dashed, gray] (20,0) -- (20,6.5);
  
  % Marcas de tempo
  \foreach \x in {5,10,15,20} {
    \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
  }
  
  % Linhas horizontais + pontos (todos preenchidos)
  \foreach \y/\x/\l in {1/5/1, 2/10/2, 3/15/3, 4/20/4, 5/5/5, 6/10/6} {
    \draw[gray] (0,\y) -- (\x,\y);
    \filldraw[black] (\x,\y) circle (2.5pt);
    \node[left] at (0,\y) {\l};
  }
\end{tikzpicture}
\end{document}
````


Caso não tenhamos nenhuma censura, 
A censura pode ocorrer devido a diversos fatores e dividimos em Tipos de Censuras:

[[Censura Tipo I]] - Censura por término do tempo da análise
[[Censura Tipo II]] - Censura por atingir um número X de falhas
[[Censura Tipo III]] - Censuras aleatórias



Analise surgiu com a guerra historinha dos aviões ------------ Importante ---------------



