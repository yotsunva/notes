$f:\mathbb R\to \mathbb R$
### 問1 : $f'$ が有界ならば $f$ がリプシッツ連続であることを示せ。
$|f'| < C$ とする。
$x\neq y$ に対して平均値の定理より $\frac{|fx-fy|}{|x-y|} < C$ である。
### 問2 : $f$ がリプシッツ連続かつ微分可能なら $f'$ が有界であることを示せ。
$x\neq y\implies \frac{|fx-fy|}{|x-y|} < C$ をみたす $C$ が存在する。  
$|f'(x)|=|\lim_{y\to x}\frac{fx-fy}{x-y}|=\lim_{y\to x}\frac{|fx-fy|}{|x-y|} < C$.
### 問3 : $f$ がリプシッツ連続なら一様連続であることを示せ。
$|fx-fy| < C |x-y|$ をみたす $C$ が存在する。
- $\varepsilon > 0$ とする。  
  - $|x-y| < \varepsilon/C$ とする。 $|fx-fy| < \varepsilon$.
