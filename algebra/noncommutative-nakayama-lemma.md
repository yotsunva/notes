## 環に対する中山の補題
$R$ : 環、 $M$ : 有限生成左 $R$-加群  
$M=Rm_1+\cdots+Rm_n$ とする。  
$R$ の Jacobson radical を $J:=\lbrace x\in R:\forall r\in R.\ 1-rx\text{ has left inverse}\rbrace$ と表す。
### $M=JM$ ならば $M=0$
$n$ に関する帰納法で示す。
- $n=0$ のとき成り立つ。
- $n\geq 1$ とする。 $M=JM$ より $m_n=\varepsilon_1m_1+\ldots+\varepsilon_nm_n$ $(\varepsilon_i\in J)$ と表せる。
  $m_n=(1-\varepsilon_n)^{-1\text{(left)}}\varepsilon_1m_1+\ldots+\varepsilon_{n-1}m_{n-1}$ なので $M$ は $n-1$ 元で生成され、帰納法の仮定より $M=0$.
