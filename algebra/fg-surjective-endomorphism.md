## 有限生成加群の全射自己準同型は同型
$A$ : 可換環、 $M$ : 有限生成 $A$ 加群  
$M=\langle m_1,\ldots ,m_n \rangle$  
$f:M\to M$ , $f$ は全射
$B:=A[f]\subseteq \mathrm{End}\ M$ とする。 $B$ は可換環で、 $M$ を $B$ 加群とみなせる。 $I:=(f)\subseteq B$
### 定理1： $f$ は同型
$IM=M$ なので中山より $(1-i)M=0$ をみたす $i\in I$ が存在する。
$1-i=0_B$ である。  
$i=gf\quad (g\in B)$ と表せて $fg=gf=1_B$.
<!--
$m_i=f(\sum_j a_{ij}m_j)=\sum_j a_{ij}fm_j$ と表せる。  
よって $(I_n-(a_{ij}f)\_{i,j})M=0\quad ((a_{ij}f)\_{i,j}\in M_n(B))$ で、
$\det (I_n-(a_{ij}f)\_{i,j})=0_B$ となる。
展開すると $\det (I_n-(a_{ij}f)\_{i,j})=1_B-fg\quad (g\in B)$ なので $fg=gf=1_B$.
-->
### 系2： $M/N\cong M$ なら $N=0$
同型を $g:M/N\cong M$ 、標準全射を $p:M\to M/N$ とすると、
$gp$ は全射なので同型。よって $p$ は単射。
