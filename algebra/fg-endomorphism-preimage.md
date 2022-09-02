# 有限生成加群の自己準同型による逆像
$A$ : 可換環， $M$ : 有限生成 $A$ 加群  
$g : M\to M$, $N\leq M$  
## 定理1： $g^{-1}N\leq N$ なら $g^{-1}N=N$
$g^{-1}N\leq N$ を仮定する。  
$(N:N):=\lbrace f\in \mathrm{End} M : N\leq f^{-1}N\rbrace$ とおく。以下が成り立つ：
- $a\in A$ に対して $f+a\in (N:N)\to f\in (N:N)$.
- $gf\in (N:N)\to f\in (N:N)$.

$M$ は有限生成なので $g\in\mathrm{End} M$ は $A$ 上整。よって $g\in (N:N)$ である。
## 系2： $f:M\to P$ に対して、 $\ker fg\leq \ker f$ なら $\ker fg=\ker f$
## 系3： $f:M\to P$ に対して、 $fg$ が単射なら $f$ は単射
## 系4： $M\leq P$ が fgp submod. に対して、 $f:M\to P$ が全射なら $f$ は同型
## 系5： $P$ が $x_1,\ldots ,x_n\in P$ で生成されるとき、 $y_1,\ldots ,y_n\in P$ が線形独立なら $x_i$ は $P$ の基底