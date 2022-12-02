$\DeclareMathOperator{\op}{op}$
## Identity morphism
### 関手性
関手 $i:(x:B)\to \hom_B(\bar x,x)$ を以下のように定める：
- 対象について、 $ix:=1_x$
- 射 $f:x\to y$ について、 $if:1_x\to_{\hom_B,f}1_y$ を定める必要がある。

$$
\begin{align}
1_x\to_{\hom_B,f}1_y&=\hom_{\hom_B(x,y)}(\hom_B(1_x^{\op},f)(1_x),\hom_B(f^{\op},1_y)(1_y))\\
&=\hom_{\hom_B(x,y)}(f,f)\\
\end{align}
$$

- $\hom_B(x,y)$ は離散圏なので、これは一元集合。よって $if$ が定まる（ $if:=1_f$ ）。
- $i$ の関手性はこれが一元集合であることから従う。
