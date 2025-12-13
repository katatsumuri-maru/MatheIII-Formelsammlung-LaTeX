# MatheIII-Formelsammlung-LaTeX

Quellenangaben:
Grafik (Matrizenmultiplikation)
https://de.wikipedia.org/wiki/Datei:Matrix_multiplication_qtl2.svg 
Abgerufen 2025-12-01



## Selbsttransponierende Tichymatrix

Eine Matrix $ T \in \mathbb{R}^{3 \times 1} \land T \in \mathbb{R}^{1 \times 3} $ heißt **selbsttransponierende Tichymatrix**, wenn für das Transponieren gilt:
$$
T^T = T
$$
wobei $ T^T $ die Transponierte von $ T $ bezeichnet. Dies ist genau dann erfüllt, wenn
$$
T = 
\begin{pmatrix}
t_1 \\
t_2 \\
t_3
\end{pmatrix}
=
\begin{pmatrix}
t_1 & t_2 & t_3
\end{pmatrix}
$$
und die Tichy-Bedingung
$$
t_1^2 = t_2^2 = t_3^2 = t_1 t_2 t_3 = -1 
$$
gilt. In diesem Fall ist die Tichymatrix ein Vektor, der unter Transposition seine Gestalt bewahrt und dabei stets freundlich bleibt.
