# 平方根による拡大
$R$ : Heyting integral ring （つまり $(x\in\mathrm{Reg}\ R)'\to x=0$ を満たす可換環。ただし $P':= P\to (1=_R0)$ ）。  
$E$ : 可換環、 $R\subseteq E$  
## 1元拡大の場合
$r\in R$ , $\alpha\in E$ , $\alpha^2=r$  
$\varphi:R[X]/(X^2-r)\to R[\alpha]$ , $\varphi(X):=\alpha$
### 補題1 : $b\in \mathrm{Reg}\ R$ , $\varphi(a+bX)=0$ ならば $r=(a/b)^2$.
$a+b\alpha=0$ , $b^2r=a^2$ , $r=(a/b)^2$.
### 補題2 : $(\exists x\in \mathrm{Frac}\ R.\ r=x^2)'\iff R[X]/(X^2-r) \text{ is Heyting integral}$
- $(\Rightarrow)$. $(a+bX\in\mathrm{Reg}(R[X]/(X^2-r)))'$ を仮定する。
  - $b\in \mathrm{Reg}\ R$ を仮定する。
    - $(a+bX)(c+dX)=_{R[X]/(X^2-r)}0$ とする。  
      $(a+bX)(c+dX)\in (X^2-r)$ なので $(a+bX)(c+dX)=bd(X^2-r)$ である。
      - $d\in \mathrm{Reg}\ R$ を仮定する。 $bd((-a/b)^2-r)=_{\mathrm{Frac}\ R}0$ , $r=(-a/b)^2$ , $1=_R0$.
    
      よって $d=0$ , $c=0$
    
    よって $a+bX\in\mathrm{Reg}(R[X]/(X^2-r))$ , $1=_R0$.
  
  よって $b=0$.
  - $a\in \mathrm{Reg}\ R$ を仮定する。
    - $a(c+dX)=_{R[X]/(X^2-r)}0$ とすると $(c,d)=(0,0)$.
    
    よって $a\in\mathrm{Reg}(R[X]/(X^2-r))$ , $1=_R0$.

  よって $a=0$.
- $(\Leftarrow)$. $r=(a/b)^2$ $(b\in \mathrm{Reg}\ R)$ とする。  
  $(a+bX)(a-bX)=a^2-b^2r=\_{(\mathrm{Frac}\ R)[X]/(X^2-r)}0$ より $(a+bX)(a-bX)=_{R[X]/(X^2-r)}0$.
  - $a+bX\in\mathrm{Reg}(R[X]/(X^2-r))$ を仮定する。  
    $a-bX=0$ , $b=0$ , $1=_R0$.
  
  よって $a+bX=0$ , $b=0$ , $1=_R0$.
### 定理3 : $(\exists x\in \mathrm{Frac}\ R.\ r=x^2)' \iff$ 「 $\varphi$ が同型かつ $R[\alpha]$ が Heyting integral」
- $(\Rightarrow)$. 
  - $a,b\in R$ , $a+b\alpha=0$ とする。
    - $b\in \mathrm{Reg}\ R$ とすると補題1より $1=_R0$.

    よって $b=0$ , $a=0$.

  よって $\varphi$ は同型。補題2より $R[\alpha]$ は Heyting integral.
- $(\Leftarrow)$. $R[X]/(X^2-r)$ が Heyting integral なので補題2より示せる。
## 平方根による拡大（n元拡大）
$r_i\in R$ , $\alpha_i\in E$ （ $i=1,\ldots,n$ ）  
$R_k:=R[\alpha_1,\ldots,\alpha_k]$  
$\varphi_k:R[X_i;i\leq k]/(X_i^2-r_i;i\leq k)\to R_k$ , $\varphi(X_i):= \alpha_i$
### 補題4 : $a,b,c\in R_{n-2}$ , $2bc\in \mathrm{Reg}\ R_{n-2}$ , $a\alpha_n=b+c\alpha_{n-1}$ ならば $r_{n-1}=((a^2r_n-b^2-c^2r_{n-1})/(2bc))^2$.
$a^2r_n=b^2+c^2r_{n-1}+2bc\alpha_{n-1}$ , $r_{n-1}=((a^2r_n-b^2-c^2r_{n-1})/(2bc))^2$.
### 補題5 : $a,b\in R_{n-2}$ , $a\in \mathrm{Reg}\ R_{n-2}$ , $a^2r_n=b^2$ ならば $r_n=(b/a)^2$.
<!-- 2 reg を仮定。a,b が reg の場合に使う。このとき c=0。結局 b=0 に帰着。 -->
### 補題6 : $a,c\in R_{n-2}$ , $a\in \mathrm{Reg}\ R_{n-2}$ , $a\alpha_n=c\alpha_{n-1}$ ならば $r_nr_{n-1}=(cr_{n-1}/a)^2$.
<!-- 2 reg を仮定。a が reg の場合に使う。結局 a=0 に帰着。 -->
### 定理7 : ある条件のもとで $\varphi_n:R[X_i;i]/(X_i^2-r_i;i)\to R[\alpha_i;i]$ が同型
- ある条件とは、
  - $2\in \mathrm{Reg}\ R$.
  - $r_1,\ldots,r_n$ から1元以上選ぶと、どう選んでもそれらの積 $r$ について $(\exists x\in \mathrm{Frac}\ R.\ r=x^2)'$.

帰納法で示す。 $R_k=R[\alpha_1,\ldots,\alpha_k]$ とおく。
- $n=0$ のとき、成り立つ。
- $n=1$ のとき、定理1より成り立つ。
- $n\geq2$ とする。帰納法の仮定より $\varphi_{n-1}:R[X_1,\ldots,X_{n-1}]/(\cdots)\to R_{n-1}$ は同型なので、 $\varphi_{n-1}$ によってこの二つを同一視する。 
  条件とこの同型によって
  $\varphi:R_{n-1}[X_n]/(X_n^2-r_n)\to R_n$ が同型であることを示す。
