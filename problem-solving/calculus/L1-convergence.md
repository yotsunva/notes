$f:\mathbb R\to \mathbb R$ , $\int_0^\infty f(x)dx = C$ $(|C| < \infty)$
### 問1 : $\forall\varepsilon,\delta > 0 ,\ \exists N.\  (k > N \implies |\int_{k\delta}^{(k+1)\delta} f(x)dx| < \varepsilon)$ を示せ。
$\sum_k (\int_{k\delta}^{(k+1)\delta} f(x)dx)$ は収束するので、 $\lim_{k\to \infty}(\int_{k\delta}^{(k+1)\delta} f(x)dx)=0$.  
   よって $k > N \implies |\int_{k\delta}^{(k+1)\delta} f(x)dx| < \varepsilon$ をみたす $N$ が存在する。
### 問2: $f$ が一様連続なら $\lim_{x\to\infty}f(x)=0$ となることを示せ。
- $\varepsilon > 0$ とする。
  $\limsup_{x\to\infty}f(x) > \varepsilon$ を仮定する。  
  $|x-y| < \delta \implies |fx-fy| < \varepsilon/2$ をみたす $\delta$ が存在する。  
  問1より $\exists N.\  (k > N \implies |\int_{k\delta}^{(k+1)\delta} f(x)dx| < (\varepsilon/2)\delta)$.  
  $a/\delta > N$ かつ $f(a) > \varepsilon$ をみたす $a$ が存在する。  
  $N < n \leq a/\delta < n+1$ をみたす $n$ がある。
  $\int_{n\delta}^{(n+1)\delta} f(x)dx > (\varepsilon/2)\delta$.  
  よって矛盾。
 
よって $\limsup_{x\to\infty}f(x)\leq 0$. 同様にして $\liminf_{x\to\infty}f(x)\geq 0$.  
よって $\lim_{x\to\infty}f(x)=0$.
