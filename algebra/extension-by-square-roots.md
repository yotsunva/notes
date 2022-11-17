## 平方根による拡大
$R$ : Heyting integral ring （つまり $(x\in\mathrm{Reg}\ R)'\to x=0$ を満たす可換環。ただし $P':= P\to (1=_R0)$ ）。  
$S$ : 可換環、 $R\subseteq E$  
$r_i\in R$ , $\alpha_i\in E$ （ $i=1,\ldots,n$）  
準同型 $(X_i\mapsto \alpha_i)$ を単に $\varphi_n$ と表す。
### 定理1 : $(\exists x\in \mathrm{Frac}\ R.\ r=x^2)'$ なら $\varphi:R[X]/(X^2-r)\to R[\alpha]$ は同型。このとき $R[\alpha]$ も Heyting integral.
- $a,b\in R$ , $a+b\alpha=0$ とする。 $b^2r=_Ra^2$ である。
  - $b\in \mathrm{Reg}\ R$ を仮定する。 $r=(a/b)^2$ なので $1=_R0$
  
  よって $b=0$ , $a=0$ となる。
  
よって $(X\mapsto \alpha)$ は同型。  
$\varphi:R[X]/(X^2-r)$ は Heyting integral?
### 定理2 : ある条件のもとで $\varphi_n:R[X_i;i]/(X_i^2-r_i;i)\to R[\alpha_i;i]$ は同型
- ある条件とは、

帰納法で示す。 $R_k=R[\alpha_1,\ldots,\alpha_k]$ とおく。
- $n=0$ のとき、成り立つ。
- $n=1$ のとき、定理1より成り立つ。
- $n\geq2$ とする。帰納法の仮定より $\varphi_{n-1}:R[X_1,\ldots,X_{n-1}]/(\cdots)\to R_{n-1}$ は同型なので、 $\varphi_{n-1}$ によってこの二つを同一視する。 
  条件とこの同型によって
  $\varphi:R_{n-1}[X_n]/(X_n^2-r_n)\to R_n$ が同型であることを示す。
