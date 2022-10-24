## $Z(\mathrm{End}\ V)$
$R$ : 環  
$0\in I$ , $V:=\bigoplus_{i\in I}R$ （自由でなくても augmentation の代わりとなる関数（つまり全射準同型 $V\to R$ ）があれば良い）  
$f:V\to R$ , $fe_i:=1$ (augmentation)  
$v\in V$ に対して $B_v\in\mathrm{End}\ V$ を $B_vx:=(fx)v$ と定める。
### 命題1： $A\in Z(\mathrm{End}\ V)$ なら $\forall v\in V,\ Av=f(Ae_0)v$ （特に $A$ は $\mathrm{id}$ の定数倍）
$AB_ve_0=Av$ , $B_vAe_0=f(Ae_0)v$ だから。
### 例
$\mathbb{Z}$-加群 $\mathbb{Q}$ に対し、 $\phi\in Z(\mathrm{End}\ \mathbb{Q})$ , $\phi x:=x/2$ は $\mathrm{id}$ の整数倍でない。
## 一般化
$R$ : 環、 $M$ : $R$-左加群  
$I\subset R$ : 両側イデアル、 $I\subset \lbrace x\in R : xR=0 \rbrace$ （ $M$ を $R/I$-左加群とみなせる）  
$f:M\to R/I$ : 全射準同型、 $fm=1$  
$y\in M$ に対して $g_y\in \mathrm{End}\_R \ M$ を $g_y x := (fx)y$ と定める。
### 命題2： $\phi\in Z(\mathrm{End}\ M)$ なら $\forall y\in M,\ \phi y=f(\phi m)y$ （特に $\phi$ は $\mathrm{id}$ の定数倍）
$\phi g_ym=\phi y$ , $g_y \phi m = f(\phi m)y$ だから。  
射影 $R\to R/I$ で $f(\phi m)\in R/I$ に行く元 $r\in R$ をとると、 $\phi = r\ \mathrm{id}$.
