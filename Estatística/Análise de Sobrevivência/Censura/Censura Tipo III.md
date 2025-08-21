Um terceiro mecanismo de [[Censura na AS]], o do tipo aleatório, é o que mais ocorre na prática.
Esse é caso mais comum onde temos censuras por vários motivos e espalhados longitunalmente.

```tikz
\begin{document}

\begin{tikzpicture}[x=0.6cm, y=0.5cm]
  % Eixos
  \draw[->] (0,0) -- (21,0) node[right] {Anos};
  \draw (0,0) -- (0,7) node[above] {Pacientes};
  
  % Linha pontilhada vertical (final do estudo em 20)
  \draw[dashed, gray] (18,0) -- (18,6.5);
  
  % Marcas de tempo
  \foreach \x in {5,10,15,20} {
    \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
  }
  
  % Rótulos dos pacientes (1-6)
  \foreach \y in {1,...,6} {
    \node[left] at (0,\y) {\y};
  }
  
  % Pontos CHEIOS (1,2,3,5)
  \foreach \y/\x in { 4/15, 6/10} {
    \draw[gray] (0,\y) -- (\x,\y);
    \filldraw[black] (\x,\y) circle (2.5pt);
  }
  
  % Pontos VAZIOS (4,6) - censurados
  \foreach \y/\x in {1/6, 2/18, 3/10, 5/18} {
    \draw[gray] (0,\y) -- (\x,\y);
    \draw[thick] (\x,\y) circle (3pt);
  }
\end{tikzpicture}

\end{document}
````

|   Icone   | $\delta$ | Condição  |
| :-------: | :------: | :-------: |
|  $\circ$  |    0     | censurado |
| $\bullet$ |    1     |   Falha   |

