## Σ-category
### 定義
Σ-category $(x:B)\times E(x,x)$ を以下のように定める：
- 対象は組 $(x,a):(x:B)\times E(x,x)$
- $(x,a)$ から $(y,b)$ への射は、組 $(f,\alpha):(f:x\to_B y)\times (a\to_{E,f}b)$
- id, 合成を以下のように定める：
  - id は $(1_x,1_a):(x,a)\to (x,a)$
  - $(f,\alpha):(f:x\to_B y)\times (a\to_{E,f}b)$ と $(g,\beta):(f:y\to_B z)\times (b\to_{E,f}c)$ の合成は $(gf,\beta\alpha):(f:x\to_B z)\times (a\to_{E,f}c)$
  
  単位律と結合律が成り立つことは [Heterogeneous morphism](heterogeneous-morphisms.md) で確認した。
### 基本的な性質
- 第1射影関手 $\pi_1:(x:B)\times E(x,x)\to B$ を以下のように定める：
  - 対象について $\pi_1(x,a):=x$
  - 射について $\pi_1(f,\alpha):=f$
  - 関手性をみたすことが確認できる。
- $E$ が constant なら、 Σ-category は product category
### 色々な性質
- 第2射影関手 $\pi_2:(p:(x:B)\times E(x,x))\to E(\pi_1^{\mathsf{op}}p,\pi_1p)$ (dependent functor) を以下のように定める（currying で定めた方が良いかも）：
  - 対象について $\pi_2(x,a):=a$
  - 射について $\pi_2(f,\alpha):=\alpha$
  - 関手性をみたすことが確認できる。
