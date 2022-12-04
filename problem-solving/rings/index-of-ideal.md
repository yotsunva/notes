$\DeclareMathOperator{\im}{Im}$
### $(a+b\sqrt{-5})\subseteq\mathbb Z[\sqrt{-5}]$ の指数を求めよ
$\alpha:=a+b\sqrt{-5}$ とする。  
$\varphi:\mathbb Z[\sqrt{-5}]\to \mathbb Z[\sqrt{-5}]$ , $\varphi x:=\alpha x$ とする。  
$(\alpha)=\im\varphi$ である。  
$\mathbb Z$ 加群同型 $\mathbb Z^2\to\mathbb Z[\sqrt{-5}]$ , $e_1,e_2\mapsto 1,\sqrt{-5}$ によって
$\mathbb Z^2$ と $\mathbb Z[\sqrt{-5}]$ を同一視する。  
$\det\varphi=N(\alpha)=a^2+5b^2$ なので、
- $a^2+5b^2=0$ のとき、指数は無限（ $\alpha=0$ で $Z[\sqrt{-5}]/(\alpha)=Z[\sqrt{-5}]$ ）
- $a^2+5b^2\neq 0$ のとき、指数は $a^2+5b^2$.
### $(1+\sqrt d,1-\sqrt d)\subseteq\mathbb Z[\sqrt d]$ の指数を求めよ
- $\sqrt d\in \mathbb Z$ のとき、 $\mathbb Z[\sqrt d]/(1+\sqrt d,1-\sqrt d)=\mathbb Z/(2,1+\sqrt d)$
  - $\sqrt d\in 2\mathbb Z$ のとき、指数1
  - $\sqrt d\in 1+2\mathbb Z$ のとき、指数2

- $\sqrt d\notin \mathbb Z$ のとき、 $Z$ は整閉なので $\sqrt d\notin \mathbb Q$ で、
  $1,\sqrt d\in \mathbb Z[\sqrt d]$ は $\mathbb Z$-一次独立。  
  $\varphi:\mathbb Z\to\mathbb Z[\sqrt d]/(1+\sqrt d,1-\sqrt d)$ , $\varphi x:=x$ は全射 ( $\sqrt d=\varphi(1)$ )。  
  $\ker\varphi=2\mathbb Z$ なので $\mathbb Z[\sqrt d]/(1+\sqrt d,1-\sqrt d)\cong \mathbb F_2$ で指数2。
