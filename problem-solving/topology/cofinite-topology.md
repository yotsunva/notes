## Cofinite topology
$X$ に cofinite topology を入れる。  
「 $X$ が非連結 $:\iff$ $X=U\sqcup V$ （ $U,V$ は元をもつ開集合）と表せる」とする（こうする場合、空集合は非連結でない）
### $X$ が非連結となる条件を求めよ。
- $2\leq|X| < \infty$ なら、 $X=\lbrace a \rbrace \sqcup \lbrace a \rbrace^c$ なので非連結。
- $X$ が非連結だとする。 $X=U\sqcup V$ （ $U,V$ は元をもつ開集合）と表せて、 $2\leq |U\sqcup V| < \infty$.
### $X$ がコンパクトであることを示せ。
$\bigcup_{i\in I} U_i=X$ とする。 空なものを省くことで $U_i$ が元をもつとして良い。 $\bigcap U_i^c=\emptyset$.
- $I=\emptyset$ なら元々有限被覆なのでok
- $0\in I$ とする。 $U_0^c\neq X$ は閉集合なので有限。 $x\in U_0^c$ に対して $x\in U_{i_x}$ となる $i_x$ が存在。
  $U_0\cup(\bigcup_{x\in U_0^c} U_{i_x})=X$.
### $X$ がハウスドルフになる条件。
- $|X| < \infty$ なら離散なのでハウスドルフ。
- $X$ がハウスドルフで $|X|\geq 2$ だとする。相異なる2点 $a,b\in X$ が存在。
  $U_a\cap U_b=\emptyset$ をみたす $a,b$ の開近傍 $U_a,U_b\subseteq X$ が存在。  
  $U_b\subseteq U_a^c\subsetneq X$ は有限なので $X=U_b\sqcup U_b^c$ は有限。
### $S\subseteq X$ が無限なら稠密
$S$ が無限とする。
- $x\in X$ とする。
  - $U_x\subseteq X$ を $x$ の開近傍とする。  
    $U_x^c\neq X$ は有限なので $a\in S\cap U_x$ が存在。
    
  よって $x\in \overline S$.

よって $S$ は稠密。
