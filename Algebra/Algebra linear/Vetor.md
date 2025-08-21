

```latex
\begin{tikzpicture}[scale=1.5, >=stealth]
  % Eixos coordenados
  \draw[->] (-0.5,0) -- (3,0) node[below] {$x$};
  \draw[->] (0,-0.5) -- (0,3) node[left] {$y$};
  
  % Vetor A (azul)
  \draw[->, thick, blue] (0,0) -- (2,1) 
    node[midway, below left] {$\vec{A}$};
  
  % Vetor B (verde)
  \draw[->, thick, green!70!black] (0,0) -- (1,2) 
    node[midway, above left] {$\vec{B}$};
  
  % Vetor resultante C = A + B (vermelho)
  \draw[->, thick, red] (0,0) -- (3,3) 
    node[midway, below right] {$\vec{C} = \vec{A} + \vec{B}$};
  
  % Paralelogramo (linhas tracejadas)
  \draw[dashed, gray] (2,1) -- (3,3);
  \draw[dashed, gray] (1,2) -- (3,3);
\end{tikzpicture}
```

