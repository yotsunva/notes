# $\sqrt 2$ の無理性
## 補題1： $\forall n\in \mathbb{Z},\ \forall x\in \mathbb{Q},\ x^2=n\to x\in \mathbb{Z}$
$n\in \mathbb{Z}$, $x\in \mathbb{Q}$ を任意にとる。
$x^2=n$ を仮定する。  
$x=\frac a b$, $\gcd (a,b) = 1$ を満たす $a,b\in \mathbb{Z}$ が存在する。  
このとき $a^2=nb^2$, $\gcd (a^2,b) = 1$ なので $\gcd (nb^2,b) = 1$ である。よって $b$ は $1$ の約数なので可逆。
よって $x\in \mathbb{Z}$ である。  
（同様にして GCD 整域の整閉性が示せる。）
## 主定理： $\forall x\in \mathbb{Q},\ \neg(x^2=2)$
$x\in \mathbb{Q}$ を任意にとる。 $x^2=2$ を仮定する。  
補題1より $x\in \mathbb{Z}$ となる。 $2$ は平方数でないので矛盾。
