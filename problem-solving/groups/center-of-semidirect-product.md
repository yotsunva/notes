### 問 : $(n,h)\in Z(N\rtimes_\varphi H)$ となる条件を求めよ
$N\rtimes H=NH$ なので、

$$
\begin{align}
(n,h)\in Z(N\rtimes_\varphi H)
&\iff \forall x,y.\ {}^{(1,y)}(n,h)=(n,h)\land {}^{(x,1)}(n,h)=(n,h)\\
&\iff \forall x,y.\ (\varphi_yn,{}^yh)=(n,h)\land (xn(\varphi_hx^{-1}),{}^xh)=(n,h)\\
&\iff (h\in Z(H))\land (\forall y.\ \varphi_yn=n)\land (\forall x.\ xn(\varphi_hx^{-1})=n)
\end{align}
$$

- 注： $n\in Z(N)$ のとき、 $(\forall x.\ xn(\varphi_hx^{-1})=n)\iff h\in \ker\varphi$.
### 問 : $Z(C_7\rtimes_\varphi C_3)$ を求めよ
$C_7=\langle a\rangle$ , $C_3=\langle b\rangle$ とする。  
$\varphi$ が非自明なとき、 $\varphi_b=(a\mapsto a^2),(a\mapsto a^4)$ である。  
必要なら $b$ を $b^{-1}$ にとりかえることで $\varphi_b=(a\mapsto a^2)$ とできる。  
- $(n,h)\in Z(C_7\rtimes_\varphi C_3)$ とする。
  - $(\varphi_b g,h)=(1,b)(n,h)(1,b)^{-1}=(g,h)$ なので $n$ は $\varphi_b$ の不動点。  
    よって $n=1$ である。  
  - $(a(\varphi_ha^{-1}),h)=(a,1)(1,h)(a,1)^{-1}=(1,h)$ なので $h\in\ker\varphi$.  
    よって $h=1$.
  
よって $Z(C_7\rtimes_\varphi C_3)=1$.
