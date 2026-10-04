Given Commutative ring R and 2 R-modules $M,N$ a tensor product is another  R-module denoted $M_{R} \otimes {}_{R}N$ with a bilinear map,
$\phi:M\times N \to M \otimes N, \quad (m,n) \mapsto (m \otimes n )$, 
With the properties
- $\phi(rm_1 + sm_2, n) = r\phi(m_1,n) + s\phi(m_2,n)$
- $\phi(m, rn_1 + sn_2) = r\phi(m,n_1) + s\phi(m,n_2)$

And it has the universal property
```tikz
\begin{document}
\begin{tikzpicture}[>=stealth]

\node (MN) at (0,2) {$M \times N$};
\node (T) at (4,2) {$M \otimes_R N$};
\node (P) at (4,0) {$P$};

\draw[->] (MN) -- node[above] {$\otimes$} (T);
\draw[->] (MN) -- node[below left] {$\phi$} (P);
\draw[->, dashed] (T) -- node[right] {$\exists!\,\widetilde{\phi}$} (P);

\end{tikzpicture}
\end{document}
```

- [[tensor product guidlines]]
- [[intuitively what is a tensor product]]
- tensor products between vector spaces 
- example of tensor products 
- commutative ring tensor product
- [[showing existence of tensor products]]
- [[tensor algebra]]
- 