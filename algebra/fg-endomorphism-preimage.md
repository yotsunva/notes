# 有限生成加群の自己準同型による逆像
$A$ : 可換環， $M$ : 有限生成 $A$ 加群  
$g : M\to M$ , $N\leq M$  
## 定理1： $g^{-1}N\leq N$ なら $g^{-1}N=N$
$g^{-1}N\leq N$ を仮定する。  
$(N:N):=\lbrace f\in \mathrm{End} M : N\leq f^{-1}N\rbrace$ とおく。以下が成り立つ：
- $a\in A$ に対して $f+a\in (N:N)\to f\in (N:N)$.
- $gf\in (N:N)\to f\in (N:N)$.

$M$ は有限生成なので $g\in\mathrm{End} M$ は $A$ 上整。よって $g\in (N:N)$ である。
## 系2： $f:M\to P$ に対して、 $\ker fg\leq \ker f$ なら $\ker fg=\ker f$
## 系3： $f:M\to P$ に対して、 $fg$ が単射なら $f$ は単射
## 系4： $M\leq P$ が fgp submod. であるとき、 $f:M\to P$ が全射なら $f$ は同型
## 系5： $y_1,\ldots ,y_n\in P$ が線形独立であるとき、 $P$ が $x_1,\ldots ,x_n\in P$ で生成されるなら $x_i$ は $P$ の基底
## 系6：系4において $M$ が射影的であるという仮定は不要
$f:M\twoheadrightarrow P$ , $i:M\hookrightarrow P$ , $p:A^m\twoheadrightarrow M$  
有限階数自由加群は射影的なので、 $fpg=ip$ となる $g:A^m\to A^m$ が存在する。  
$g^{-1}p^{-1}f^{-1}0=p^{-1}i^{-1}0=p^{-1}0\leq p^{-1}f^{-1}0$ なので定理1より
$p^{-1}0=p^{-1}f^{-1}0$ である。
よって $f^{-1}0=0$ で、 $f$ は同型。
## 系7 (Orzech) ： $f:N\to M$ が全射なら $f$ は同型
$f:N\twoheadrightarrow M$ , $i:N\hookrightarrow M$ , $p:A^m\twoheadrightarrow M$  
$A^m$ の射影性より $fq=p$ を満たす $q:A^m\to N$ が存在する。  
- $x\in \ker f$ を任意にとる。  
$N':=Ax+qA^m\leq N$ は有限生成。 $fN'\geq fqA^m=pA^m=M$ なので $f|\_{N'}$ は全射。
これと系6より $f|\_{N'}:N'\to M$ は同型で、 $x\in \ker f|\_{N'}=0$ である。

よって $\ker f=0$ で、 $f$ は同型。
