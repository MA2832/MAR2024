<h1>
  <a href="https://www.google.com" target="_blank">
    test
  </a>
</h1>
\( T(n) = \begin{cases} 
\Theta(n^{\log_b a}) & f(n) = O(n^{\log_b a - \varepsilon}) \\
\Theta(n^{\log_b a} \log n) & f(n) = \Theta(n^{\log_b a}) \\
\Theta(f(n)) & f(n) = \Omega(n^{\log_b a+\varepsilon}) \text{ AND } \\
             & af(n/b) < cf(n) \text{ for large } n
\end{cases} \)

where \( \varepsilon > 0 \) and \( c < 1 \).
