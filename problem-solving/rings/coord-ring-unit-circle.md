$S_R:=R[x,y]/(x^2+y^2-1)$
### 問1 : $2\in R^\times$ , $i\in R$ , $i^2=-1$ のとき、 $S$ はどんな環か。
$\varphi : R[t,t^{-1}]\to S$ , $t,t^{-1} \mapsto x+iy ,x-iy$ は同型。
- 逆は $\psi : S\to R[t,t^{-1}]$ , $x,y \mapsto (1/2)(t+t^{-1}),(-i/2)(t-t^{-1})$.
### 問2 : 問1の状況で2つの分解 $y^2, (1+x)(1-x)$ が合流することを示せ。
- $y=(-i/2)(t-t^{-1})=(-\frac{i}{2t})(t+1)(t-1)$
- $1+x=(1/2)(t+t^{-1}+2)=\frac{1}{2t}(t+1)^2$
- $1-x=-(1/2)(t+t^{-1}-2)=-\frac{1}{2t}(t-1)^2$

$\sin^2x,(1+\cos x)(1-\cos x)$ が $4\cos^2 \frac x2\sin^2 \frac x2$ で合流するのと同様の話。
### 問3 : 適当な条件のもとで $y\in S$ が既約であることを示せ。
