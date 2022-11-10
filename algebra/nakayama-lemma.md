## 中山の補題
$A$ : 可換環、 $M$ : 有限生成 $A$ 加群  
$M=\langle m_1,\ldots, m_n\rangle$  
$I\leq A$ , $IM=M$  
作用を $\rho:A\to \mathrm{End}\ M$ と表す。
### 定理1： $(1-x)M=0$ をみたす $x\in I$ が存在する
Cayley-Hamilton より $\rho(1)=\mathrm{id}_M$ は $\rho (I)$ 上整だから。
<!--
$m_i=x_i\sum_ja_{i,j}m_j\quad (x_i\in I)$ と表せる。  
よって $m_i=\sum_jy_{i,j}m_j\quad (y_{i,j}\in I)$ と表せる。  
よって $(I_n-(y_{i,j}))M=0$ で、余因子かけると $\det(I_n-(y_{i,j}))M=0$.  
展開すると $\det(I_n-(y_{i,j}))=1-x\quad(x\in I)$.
-->
