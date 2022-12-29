## 二項関係つき集合の和
$I$ : 二項関係つき集合、
$X_i$ : $I$ で添字付けられた二項関係つき集合の族  
disjoint sum $\sum X_i$ に $(i,x)<(j,y):\iff i< j\lor (i=j \land x< y)$ という関係を入れる。
### 普遍性
二項関係つき集合 $Y$ に対し、以下の二つは自然に同一視できる：
- 射 $f:(\sum X_i)\to Y$
- 以下をみたす射の族 $f_i:X_i\to Y$
  - $\forall i,j\in I,\forall x\in X_i,\forall y\in X_j.\ i< j\implies f_ix< f_jy$
