## 準素イデアルの局所化
$A$ : 可換環、 $S\subseteq A$ : 積閉、 $I\subseteq A$ : イデアル
### 補題1: $S\cap I =\emptyset$ かつ $I$ が準素であるとき、 $x\in A$ , $s\in S$ に対して $x/s\in S^{-1}I$ ならば $x\in I$
一般に

$$ \begin{align}
x/s\in S^{-1}I &\iff \exists i\in I.\ \exists t\in S.\ x/s=i/t\\
&\iff \exists i\in I.\ \exists t,u\in S.\ utx=usi\\
&\iff \exists v\in S.\ vx\in I \quad ((\Rightarrow)\ v:=ut.\ (\Leftarrow)\ (i,t,u):=(vx,sv,1).)
\end{align} $$

である。 $S\cap I =\emptyset$ より $\forall n.\ v^n\notin I$ なので、 $I$ の準素性より $x\in I$ である。
### 例
- $A=\mathbb{Z}$ , $S=2^\mathbb{N}$ , $I=(2)$ のとき
  - $S\cap I =2^{\mathbb{N}+1}$
  - $I$ は準素
  - $1/1=2/2\in S^{-1}I$ だが $1\notin I$
- $A=\mathbb{Z}$ , $S=2^\mathbb{N}$ , $I=(6)$ のとき
  - $S\cap I =\emptyset$
  - $I$ は準素でない
  - $3/1=6/2\in S^{-1}I$ だが $3\notin I$
