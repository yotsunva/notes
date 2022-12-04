$\DeclareMathOperator{\Frac}{Frac}$
# 根の存在の判定
## 整閉性の利用
体→ED→PID→UFD→GCD整域→整閉整域
### $X^p-X-T\in \mathbb F_p(T)[X]$ は根をもたない。
$X^p-X-T\in \mathbb F_p(T)[X]$ が根をもつと仮定する。  
$\mathbb F_p[T]$ は整閉なので $f^p-f-T=0$ をみたす $f\in \mathbb F_p[T]$ が存在する。  
$T$ に $1$ を代入すると $1=_{\mathbb F_p}0$ となり矛盾。
# 既約性の判定
## 標数p
$K$ : 標数 $p$ の体
### $X^p-X-T\in K[X]$ が非自明な約数をもつなら根をもつ
$f:=X^p-X-T\in K[X]$ の最小分解体を $L$ とする。  
$f=\prod_{k=0,\ldots,p-1}(X-(\alpha+k))$ $(\alpha\in L)$ と表せる。 $L=K(\alpha)$.  
$g\in K[X]$ を $f$ の非自明な約数とする。 $1\leq\deg g\leq p-1$.  
$g=\prod_{k\in S}(X-(\alpha+k))$ と表せる。 $\deg g-1$ 次の係数を見ると $\alpha\in K$ がわかる。
#### 系 : $X^p-X-T\in \mathbb F_p(T)[X]$ は既約
