$\DeclareMathOperator{\op}{op}$
## Dependent functor
### 定義
dependent functor $F:(x:B)\to E(x,x)$ とは、以下の組のこと：
- 対象関数 $F:(x:B)\to E(x,x)$
- $x,y\in B$ に対して、射関数 $F:(f:x\to y)\to (Fx\to_{E,f}Fy)$
- 以下の関手性の証明：
  - $F1_x=1_{Fx}$ , $F(gf)=(Fg)(Ff)$
### 基本的な性質
- 恒等関手 $1_B:(x:B)\to B$ がある。
- $E$ が constant ( $E=\lambda xy.\ C$ ) なら $(x:B)\to E(x,x)=B\to C$ 。
### dependent functor は $\pi_1:(x:B)\times E(x,x)\to B$ の section
- dependent functor $F:(x:B)\to E(x,x)$ から関手 $F':B\to (x:B)\times E(x,x)$ が作れる。
  - 対象について、 $F'x:=(x,Fx)$
  - 射について、 $F'f:=(f,Ff)$
  - この $F'$ は $\pi_1\circ F'=1_B$ をみたす。
- 逆に、 $\pi_1\circ F'=1_B$ をみたす関手 $F':B\to (x:B)\times E(x,x)$ から dependent functor $F:(x:B)\to E(x,x)$ が作れる。
  - 対象について、 $Fx:=\pi_2(F'x)$
  - 射 $f:x\to y$ について、 $Ff:=\pi_2(F'f)$
    - $\pi_1(F'f)=f$ より $\pi_2(F'f):Fx\to_{E,f}Fy$

これらの構成は互いに逆になっている。
### 色々な性質
- 関手 $F:(x:B)\to E(x,x)$ , $G:(x:B)\to (a:E(x,x))\to D((x,a),(x,a))$ の合成 $GF:(x:B)\to D((x,F^{\op}x),(x,Fx))$ を以下のように定める：
  - 対象について $(GF)x:=G(Fx)$
  - …
