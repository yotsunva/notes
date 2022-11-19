$\DeclareMathOperator{\im}{Im}$
$R$ : 可換環
### 問1 : $\varphi:R[X,Y]\to R[T]$ , $X,Y\mapsto T^2-1,T^3-T$ の ker を求めよ。
$\varphi(Y^2-(X^3+X^2))=0$ より $(Y^2-(X^3+X^2))\subseteq\ker\varphi$.  
- $\varphi(f)=0$ とする。 $f=g(Y^2-(X^3+X^2))+hY+i$ $(h,i\in R[X])$ と表す。  
  $0=\varphi(f)=\varphi(h)(T^3-T)+\varphi(i)$ と $\varphi(R[X])\subseteq \bigoplus_n RT^{2n}$ より
  $h,i\in\ker\varphi$.  
  $\varphi|_{R[X]}:R[X]\to R[T]$ , $X\mapsto T^2-1$ は単射なので $h,i=0$.  
  よって $f\in\ker\varphi$.
  
よって $\ker\varphi\subseteq(Y^2-(X^3+X^2))$.
### 問2 : $\varphi:R[X,Y,Z]\to R[S,T]$ , $X,Y,Z\mapsto S,ST,T^2$ の ker を求めよ。
$\varphi(Y^2-X^2Z)=0$ より $(Y^2-X^2Z)\subseteq\ker\varphi$.  
- $\varphi(f)=0$ とする。 $f=g(Y^2-X^2Z)+hY+i$ $(h,i\in R[X,Z])$ と表す。  
  $0=\varphi(f)=\varphi(h)ST+\varphi(i)$ と $\varphi(R[X,Z])\subseteq \bigoplus_n (R[S])T^{2n}$ より
  $h,i\in\ker\varphi$.  
  $\varphi|_{R[X,Z]}:R[X,Z]\to R[S,T]$ , $X,Z\mapsto S,T^2$ は単射なので $h,i=0$.  
  よって $f\in\ker\varphi$.

よって $\ker\varphi\subseteq(Y^2-X^2Z)$.
