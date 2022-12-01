$\DeclareMathOperator{\op}{op}$
## Natural transformation
### 定義
$F,G:(x:B)\to E(x,x)$ とする。自然変換 $\sigma:F\Rightarrow G$ とは以下の組のこと：
- 関数 $\sigma:(x:B)\to \hom_{E(x,x)}(Fx,Gx)$
- 以下の自然性の証明：
  - $(Gf)\circ(\sigma x)=(\sigma y)\circ(Ff)$
### 性質
- 自然変換 $\sigma:F\Rightarrow G$ を与えることは、関手 $\sigma:(x:B)\to \hom_{E(\bar x,x)}(F^{\op}\bar x,Gx)$ を与えることと等価 (transformation extensionality)。（反変な引数にバーをつけることにした）
#### 証明
関手 $\lambda xy.\ \hom_{E(x,y)}(F^{\op}x,Gy):B^{\op}\times B\to \mathsf{Cat}$ を $H$ とおく。  
$\sigma:(x:B)\to \hom_{E(x,x)}(Fx,Gx)$ を関数とする。  
射 $f:x\to_B y$ に対して

$$
\begin{align}
\sigma x\to_{H,f}\sigma y
&=\hom_{H(x,y)}(H(1_x^{\op},f)(\sigma x),H(f^{\op},1_y)(\sigma y))\\
&=\hom_{H(x,y)}((Gf)\circ(\sigma x),(\sigma y)\circ(Ff))
\end{align}
$$

は高々1元からなる集合である（ $H(x,y)$ は集合（離散圏）だから）。
- $\sigma$ の自然性は、任意の $f$ に対してこの集合が元をもつことと同値である。  
- $\sigma$ が関手なら、任意の $f$ に対してこの集合が元をもつ（射関数のおかげ）。
- 任意の $f$ に対してこの集合が元をもつなら射関数を定められて、この集合が高々1元であることから関手性が従う。
