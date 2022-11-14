## Dependent category theory
ラフなスケッチなので致命的な誤りを含みうる。  
$B$ : 圏、 $E:B^\mathsf{op}\times B\to \mathsf{Cat}$ : 関手（pseudofunctor とかに緩めたほうが良い場面もあるかも）
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
  - $x\xrightarrow{f}y:B$ に対する $Gf\circ(E(x,f)(Fx\xrightarrow{\alpha x}Gx))=(E(f^\mathsf{op},y)(Fy\xrightarrow{\alpha y}Gy))\circ Ff$

$E$ が constant な場合は自然変換になるべきである。
### dependent functor category
dependent functor category $(x:B)\to E(x,x)$ を以下のように定める：
- 対象は dependent functor $F:(x:B)\to E(x,x)$
- 対象 $F,G:(x:B)\to E(x,x)$ 間の射は natural transformation
- id, 合成は自然に定める。

$E$ が constant な場合は関手圏になるべきである。
### dependent pair category
dependent pair category $(x:B)\times E(x,x)$ を以下のように定める：
- 対象は dependent pair $p:(x:B)\times E(x,x)$
- 対象 $(x,a),(y,b):(x:B)\times E(x,x)$ 間の射は以下の dependent pair：
  - 射 $x\xrightarrow{f}y:B$
  - $g:a\rightsquigarrow b(=\hom_{E(x,y)}(E(x,f)(a), E(f^\mathsf{op},y)(b)))$
- id, 合成は自然に定める。

$E$ が constant な場合は積圏になるべきである。  
関手 $F:B\to \mathsf{Cat}$ に対して $E(x,y):=F(y)$ とした場合は Grothendieck 構成になるべきである。
### sanity check
- currying が機能するか。
  - $((p:(x:B)\times E_1(x,x))\to E_2(p,p))\simeq((x:B)\to (a:E_1(x,x))\to E_2((x,a),(x,a)))$
  - 米田の証明に有用か。
- transformation extensionality が成り立つか。
  - 関手 $F,G:B\to A$ に対する $\hom(F,G)\simeq ((x:B)\to \hom_A(F^\mathsf{op}x,Gx))$
    - （set を discrete category とみなし、 $\lambda xy.\hom_A(F^\mathsf{op}x,Gy):B^\mathsf{op}\times B\to \mathsf{Cat}$ とみなす）。
- 関手 $F:A\to C$ , $G:B\to C$ に対し、 $(F\downarrow G)\simeq (x:A)\times(y:B)\times \hom_C(F^\mathsf{op}x,Gy)$ となるか。
  - 内の dependent pair では $E(z,w)=\hom_C(F^\mathsf{op}x,Gw)$ とし、外では $E(z,w)=(y:B)\times \hom_C(F^\mathsf{op}z,Gy)$ としたい。
  - あるいは $(F\downarrow G)\simeq (p:A\times B)\times \hom_C(F^\mathsf{op}({\pi_0}^\mathsf{op}p),G(\pi_1p))$ か。
- $(x:B)\to E(x,x)$ と $(x:B)\times E(x,x)$ はある意味で end/coend になるか。
