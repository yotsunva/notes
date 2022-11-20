$K$ : 体
### 問1 : $[K(X,Y):K(X^m,Y^n)]$ $(m,n\geq 1)$ を求めよ。
$Z^m-X^m\in K(X^m,Y^n)[Z]$ は既約なので、 $K(X^m,Y^n)$ 代数として $K(X,Y^n)= K(X^m,Y^n)[X]\cong K(X^m,Y^n)[Z]/(Z^m-X^m)$.  
$Z^n-Y^n\in K(X,Y^n)[Z]$ は既約なので、 $K(X,Y^n)$ 代数として $K(X,Y)= K(X,Y^n)[Y]\cong K(X,Y^n)[Z]/(Z^n-Y^n)$.  
よって $[K(X,Y):K(X^m,Y^n)]=[K(X,Y^n):K(X^m,Y^n)][K(X,Y):K(X,Y^n)]=mn$.
