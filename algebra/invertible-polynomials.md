## 可逆な多項式
$R$ : 可換環
### 定理1 : $f\in R[X]^\times$ ならば $\overline f\in (R/\sqrt0)[X]$ は定数
「 $f\in (R/\sqrt0)[X]^\times$ ならば $\overline f\in (R/\sqrt0)[X]$ は定数」を示せば良い。  
「 $R$ が被約、 $f\in R[X]^\times$ ならば $f$ は定数」を示せば良い。  
$fg=1$ とする。 $g(0)\in R^\times$ である。  
$n\geq 1$ に対して $(\deg f\leq n\implies\deg f\leq n-1)$ を示せば良い。  
$\deg f\leq n$ とする。 $f$ の $n$ 次の係数を $a_n$ とおく。
- $i,m\geq 0$ に対して $(\deg a_n^ig\leq m\implies\deg a_n^{i+1}g\leq m-1)$ を示す。  
  $\deg a_n^ig\leq m$ とする。 $a_n^ig$ の $m$ 次の係数を $b_m$ とおく。  
  $f\cdot a_n^ig=a_n^i$ の両辺の $n+m$ 次の項を比較すると、
  $a_n^{i+1}b_m=0$.  
  よって $\deg a_n^{i+1}g\leq m-1$.
  
よって $a_n^{\deg g+1}g=0$ である。
両辺の定数項を比較すると $a_n^{\deg g+1}g(0)=0$ である。 $g(0)\in R^\times$ と $R$ の被約性より $a_n=0$.  
よって $\deg f\leq n-1$.
