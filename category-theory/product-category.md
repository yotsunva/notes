## product category
$A,B$ : 圏
### 定義
product category $A\times B$ を以下のように定める：
- 対象は pair $p:A\times B$
- 対象 $(a,b),(a',b'):A\times B$ 間の射は pair $p:\hom_A(a,a')\times\hom_B(b,b')$
- id, 合成は自然に定める。
### hom について
- $(f,g)\mapsto (f,g):\hom_A(a,a')\times\hom_B(b,b')\to \hom_{A\times B}((a,b),(a',b'))$ は set 間の同型
  - 多分 $a,a',b,b'$ に関して自然
