# 既約分数
$A$ : GCD 整域
## 定理： $\forall x\in \mathrm{Frac} A,\ \exists a,b\in A,\ x=\frac a b\land \gcd (a,b) = 1$
$x\in \mathrm{Frac} A$ を任意にとる。  
$x=\frac {a'} {b'}$ となる $a'\in A$, $b'\in \mathrm{Reg} A$ が存在する。  
$a',b'$ の gcd $d'\in A$ がとれる。  
$a'=ad'$, $b'=bd'$ となる $a,b \in A$ が存在する。 $b,d'\in \mathrm{Reg} A$ なので $x=\frac a b$ である。  
- $a,b$ の公約元 $d\in A$ を任意にとる。  
$dd'$ は $a',b'$ の公約元なので $d'$ の約数。よって $dd',d'$ は同伴。
$d'\in \mathrm{Reg} A$ なので $d,1$ は同伴。

よって $\gcd(a,b)=1$ である。
