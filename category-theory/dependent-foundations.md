## Dependent category theory
ラフなスケッチなので致命的な誤りを含みうる。  
$B$ : 圏、 $E:B^\mathsf{op}\times B\to \mathsf{Cat}$ : 関手（緩めたほうが良い場面もあるかも）
### dependent functor
以下の組を dependent functor という：
- dependent function $F_o:(x:B_o)\to E(x,x)$
- dependent function $F_m:(x\xrightarrow{f}y:B_m)\to (F_ox\rightsquigarrow F_oy)$
  - $F_ox\rightsquigarrow F_oy:=\hom_{E(x,y)}(E(x,f)(F_ox), E(f^\mathsf{op},y)(F_oy))$
- 関手性の証明
  - id, 合成の保存

$E$ が constant な場合は関手になるべきである。
### natural transformation
dependent functor $F,G:(x:B)\to E(x,x)$ に対して、以下の組を $F,G$ 間の natural transformation という：
- dependent function $\alpha:(x:B)\to \hom_{E(x,x)}(Fx,Gx)$
- 自然性の証明
  - $x\xrightarrow{f}y:B_m$ に対する $Gf\circ(E(x,f)(Fx\xrightarrow{\alpha x}Gx))=(E(f^\mathsf{op},y)(Fy\xrightarrow{\alpha y}Gy))\circ Ff$

$E$ が constant な場合は自然変換になるべきである。
### dependent functor category
dependent functor category $(x:B)\to E(x,x)$ を以下のように定める
- 対象は dependent function
- 対象 $F,G:(x:B)\to E(x,x)$ 間の射は natural transformation
- id, 合成は自然に定める

$E$ が constant な場合は関手圏になるべきである。
