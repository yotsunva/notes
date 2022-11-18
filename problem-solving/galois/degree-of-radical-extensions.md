$K$ : 体、 $r,s\in K$
### 問1 : 適当な条件のもとで $[K(\sqrt r):K]$ を求めよ。
- $[K(\sqrt r):K]=1\iff\sqrt r\in K$.
- $[K(\sqrt r):K]=2\iff\sqrt r\notin K$.
### 問2: 適当な条件のもとで $[K(\sqrt r,\sqrt s):K]$ を求めよ。
$[K(\sqrt r,\sqrt s):K(\sqrt r)]=1,2$ , $[K(\sqrt r):K]=1,2$ なので、 $1,2,4$ のいずれかになる。
- $[K(\sqrt r,\sqrt s):K]=1\iff\sqrt r,\sqrt s\in K$.
- $[K(\sqrt r,\sqrt s):K]=4\iff\sqrt r\notin K\land\sqrt s\notin K(\sqrt r)$.
  - $\sqrt r\notin K$ とする。  
    $\sqrt s\in K(\sqrt r)\iff \exists a,b\in K.\ s=a^2+b^2r+2ab\sqrt r$ で、これが成り立つのは以下のいずれかが成り立つ場合：
    - $a=0$ , $s=b^2r$ （つまり $\sqrt{rs}\in K$ ）
    - $b=0$ , $s=a^2$ （つまり $\sqrt s\in K$ ）
    - $2\neq 0$ , $s=a^2+b^2r$ （つまり $2=0\land\exists a,b\in K.\ s=a^2+b^2r$ ）
  
  結局 $[K(\sqrt r,\sqrt s):K]=4\iff\sqrt r,\sqrt s,\sqrt{rs}\notin K\land(2\neq 0\lor\neg(\exists a,b.\ s=a^2+b^2r))$
- $[K(\sqrt s):K]=2$ となるのは以下のいずれかが成り立つ場合：
  - $\sqrt r,\sqrt s,\sqrt{rs}$ のうち $K$ に属するものが1つだけのとき。
  - $\sqrt r,\sqrt s,\sqrt{rs}\notin K\land 2=0\land\exists a,b.\ s=a^2+b^2r$
#### 例
- $K=\mathbb{F}_2(T)$ なら、 $[K(\sqrt{T},\sqrt{T+1}):K]=2$.
