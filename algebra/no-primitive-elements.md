## 原始元がない例
$R$ : 可換環、 $p$ : 素数、 $p=_R0$.
$a,b\in R$
### 命題：全射 $\varphi : R[Z]\to R[X,Y]/(X^p-a,Y^p-b)$ が存在するなら $1=_R0$
$\varphi Z = \sum a_{i,j}X^iY^j$ と表せる。  
$(\varphi Z)^p = \sum a_{i,j}^pa^ib^j\in R$ より、
自由加群 $R[X,Y]/(X^p-a,Y^p-b)\cong R^{p^2}$ は $1,\varphi Z,\ldots,(\varphi Z)^{p-1}$ で生成される。  
よって $R$ は自明。
### 例： 拡大 $\mathbb{F}_2(X,Y)\geq \mathbb{F}_2(X^2,Y^2)$ は原始元をもたない。
