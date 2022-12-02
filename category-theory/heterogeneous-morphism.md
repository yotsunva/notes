## Heterogeneous morphism
$B$ : （局所小）圏、 $E:B^\mathsf{op}\times B\to \mathsf{Cat}$ : 関手（pseudofunctor とかに緩めたほうが良い場面もあるかも）
### 定義
$x,y:B$ , $a:E(x,x)$ , $b:E(y,y)$ , $f:x\to_B y$ に対し、

$$
a\to_{E,f} b:=\hom_{E(x,y)}(E(1_x^{\mathsf{op}},f)(a),E(f^{\mathsf{op}},1_y)(b))
$$

と定める。 $a\to_{E,f} b$ の元を「 $a$ から $b$ への $f$ に沿った heterogeneous morphism」とよぶ。
### 基本的な性質
- $1_a:a\to_{E,1_x} a$ である。
- $\alpha:a\to_{E,f} b$ , $\beta:b\to_{E,g} c$ に対し、 $\beta\alpha:a\to_{E,gf} c$ を以下のように定める：

$$
\beta\alpha:=E(f^{\mathsf{op}},1_z)(\beta)\circ E(1_x^{\mathsf{op}},g)(\alpha)
$$

- $\alpha 1_a=\alpha$ , $1_b \alpha=\alpha$
- 結合律

$$
\begin{align}
\gamma(\beta\alpha)&=E((gf)^{\mathsf{op}},1_w)(\gamma)\circ E(1_x^{\mathsf{op}},h)(E(f^{\mathsf{op}},1_z)(\beta)\circ E(1_x^{\mathsf{op}},g)(\alpha))\\
&=E((gf)^{\mathsf{op}},1_w)(\gamma)\circ E(f^{\mathsf{op}},h)(\beta)\circ E(1_x^{\mathsf{op}},hg)(\alpha)\\
&=E(f^{\mathsf{op}},1_w)(E(g^{\mathsf{op}},1_w)(\gamma)\circ E(1_y^{\mathsf{op}},h)(\beta))\circ E(1_x^{\mathsf{op}},hg)(\alpha)\\
&=(\gamma\beta)\alpha
\end{align}
$$

### 例
- $E$ が constant ( $E=\lambda x.\ C$ ) な場合、 $a\to_{E,f} b=\hom_C(a,b)$ である。

### メモ
Heterogeneous morphism を射として作られる圏が Σ-category $(x:B)\times E(x,x)$ である。  
Π-category の定義にも出てくるので、独立した話として紹介した。
