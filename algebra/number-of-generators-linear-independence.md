# 生成元の個数と線形独立性
$A$ : 可換環， $M$ : $A$ 加群   
$M$ が $x_1,\ldots ,x_m\in M$ で生成されている（対応する全射準同型を $x:A^m\to M$ と表す）。  
$y_1,\ldots ,y_n\in M$ が線形独立（対応する単射準同型を $y:A^n\to M$ と表す）。
- $y_i=\sum a_{i,j}x_j$ となる $a_{i,j}\in A$ が存在する。
準同型 $f:A^n\to A^m$ を $fe_i=\sum a_{i,j}e_j$ と定める。
$x\circ f=y$ となる（より一般に自由加群は射影的）。  
よって $f$ は単射。
## 定理1： $m < n$なら $A$ は自明環
$f:A^n\to A^m$ は単射準同型なので $A$ は自明環。

蛇足：「生成」の定義で $\Sigma$ ではなく $\exists$ を使う場合、自明性が h-prop になるように自明性を定義しないと厳しいかも
（ $A$ が h-set である場合を考えている限りは問題ない）。
## 系2： $A[X]$ が有限生成 $A$ 加群なら $A$ は自明
直接示しても良い。
## 系3： $\mathrm{Frac} (A[X])$ が有限生成 $A$ 加群なら $A$ は自明
## 定理4： $A$ が $0$-dim. かつ $m=n$ なら $M$ は $y_1,\ldots ,y_n$ で生成される自由加群
$m=n$ を仮定する。  
$f:A^n\to A^m$ は単射準同型なので同型。よって $y$ も全射。