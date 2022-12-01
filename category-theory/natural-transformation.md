$\DeclareMathOperator{\op}{op}$
## Natural transformation
### 定義
$F,G:(x:B)\to E(x,x)$ とする。自然変換 $\sigma:F\Rightarrow G$ とは以下の組のこと：
- 関数 $\sigma:(x:B)\to (Fx\to_{E,1_x} Gx)$
- 以下の自然性の証明：
  - $(\sigma y)\circ(Ff)=(Gf)\circ(\sigma x)$
### 性質
<!--
- 自然変換 $\sigma:F\Rightarrow G$ を与えることは、関手 $\sigma:(x:B)\to (F^{\op} x\to_{E,1_x} Gx)$ を与えることと等価 (transformation extensionality)。
  - 関数 $\sigma:(x:B)\to (Fx\to_{E,1_x} Gx)$ が自然だとする。
    $f:x\to y$ に対して $\sigma f:\sigma x\to_{(\lambda xy.\ F^{\op}x\to_{E,1_x} Gy),f} \sigma y$ を以下のように定める：
    - $\alpha:F^{\op} x\to_{E,1_x} Gx$ （つまり $\alpha:\hom_{E(x,x)}(F^{\op} x,Gx)$ ）
-->


<!--
$(\sigma f)\alpha:=(Gf)\circ \alpha \circ (F^{\op} f^{\op})$ と定める。

    - $(\sigma 1_x)\alpha=\alpha$ より $\sigma 1_x=1$
    - 
$$
\begin{align}
(\sigma (gf))\alpha&=(G(gf))\circ \alpha \circ (F^{\op} (gf)^{\op})\\
&=Gg\circ Gf\circ \alpha \circ (F^{\op} f^{\op})\circ (F^{\op} g^{\op})\\
&=(\sigma g\circ \sigma f)\alpha
\end{align}
$$

-->

<!--
$$
\begin{align}
\text{関数 } \sigma:(x:B)\to (Fx\to_{E,1_x} Gx) \text{ が自然}
&\iff \forall x,y,f.\ (\sigma y)\circ(Ff)=(Gf)\circ(\sigma x)\\
&\iff \forall x,y,f.\ E(f^{\op},1_y)(\sigma y)\circ E(1_x^{\op},1_y)(Ff)=E(1_x^{\op},1_y)(Gf)\circ E(1_x^{\op},f)(\sigma x)\\
\end{align}
$$
-->
