## Dependent functor
### 定義
dependent functor $F:(x:B)\to E(x,x)$ とは、以下の組のこと：
- 対象関数 $F:(x:B)\to E(x,x)$
- $x,y\in B$ に対して、射関数 $F:(f:x\to y)\to (Fx\to_{E,f}Fy)$
- 以下の関手性の証明：
  - $F1_x=1_{Fx}$ , $F(gf)=(Fg)(Ff)$
### 基本的な性質
- 恒等関手 $1_B:(x:B)\to B$ がある。
### 色々な性質
- 関手 $F:(x:B)\to E(x,x)$ , $G:(x:B)\to (a:E(x,x))\to D((x,a),(x,a))$ の合成 $GF:(x:B)\to D((x,F^{\mathsf {op}}x),(x,Fx))$ を以下のように定める：
  - 対象について $(GF)x:=G(Fx)$
  - …
