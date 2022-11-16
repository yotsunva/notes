## 有限生成加群の全射自己準同型は同型
$A$ : 可換環、 $M$ : 有限生成 $A$ 加群  
$M=\langle m_1,\ldots ,m_n \rangle$  
$f:M\to M$ , $f$ は全射  
作用を $\rho:A\to \mathrm{End}\ M$ と表す。  
$B:=A[f]\subseteq \mathrm{End}\ M$ とする。 $B$ は可換環で、 $M$ を $B$ 加群とみなせる。 $I:=(f)\subseteq B$
### 定理1： $f$ は同型
$IM=M$ なので中山より $\mathrm{id}_M\in I$.
### 例
- $M=\bigoplus_{n\in\mathbb{N}}A$ とする（実はこれが有限生成になることは $A=0$ と同値）。
  $(e_0\mapsto 0\ ;\ e_{n+1}\mapsto e_n):M\to M$ は全射で、これが同型になることは $A=0$ と同値。
- $A=\mathrm{End}\_{\mathbb{Z}\text{-mod}}(\bigoplus_{n\in\mathbb{N}}\mathbb{Z})$ （非可換）、 $M=A$ とする。
  $M$ は1元生成。
  $a:=(e_0\mapsto 0\ ;\ e_{n+1}\mapsto e_n)$ は右逆元 $e_n\mapsto e_{n+1}$ をもつので
  $\lambda x.\ ax :M\to M$ は全射だが、 $a(\lambda x.\ e_0)=0$ なので単射でない。
### 系2： $M/N\cong M$ なら $N=0$
同型を $g:M/N\cong M$ 、標準全射を $p:M\to M/N$ とすると、
$gp$ は全射なので同型。よって $p$ は単射。
