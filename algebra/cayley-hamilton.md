## Cayley-Hamilton
$A$ : 可換環、 $M$ : 有限生成 $A$ 加群  
$M=\langle m_1,\ldots,m_n\rangle$  
$f\in \mathrm{End}\ M$  
$I\leq A$ , $fM\leq IM$  
作用を $\rho:A\to\mathrm{End}\ M$ と表す。

### 定理1： $f$ は $\rho (I)$ 上整
$fm_i=\sum_jy_{i,j}m_j\quad (y_{i,j}\in I)$ と表せる。  
よって $(fI_n-(\rho y_{i,j}))[m_1,\ldots,m_n]^\top=[0,\ldots,0]^\top$ で、余因子かけると $\det(fI_n-(\rho y_{i,j}))=0_{\mathrm{End}\ M}$.  
注： $(fI_n-(\rho y_{i,j}))\in M_n(A[f])$ で、
$A[f]$ （ $\mathrm{ev}_f:A[X]\to \mathrm{End}\ M$ の像）は可換。
