# ベルンシュタインの定理 (CSB) と排中律 (LEM)
主に以下のような話題について述べます。
- CSB に関する事実
- searchable な無限集合
  - Martín Hötzel Escardó: Infinite sets that Satisfy the Principle of Omniscience in any Variety of Constructive Mathematics  
    https://www.researchgate.net/publication/265931047_Infinite_sets_that_satisfy_the_principle_of_omniscience_in_any_variety_of_constructive_mathematics  
    の一部
- CSB から LEM が従うこと
  - Pierre Pradic, Chad E. Brown: Cantor-Bernstein implies Excluded Middle  
    https://arxiv.org/abs/1904.09193  
    の一部
## CSB に関する事実
CSB とは、「任意の集合 $X,Y$ について、二つの単射 $f:X\to Y$ , $g:Y\to X$ が存在するなら全単射 $h:X\to Y$ が存在する」という命題のことです。

LEM から CSB が従うことが知られています。

univalent foundations (UF) において、集合とは限らない任意の型に対して CSB を拡張できて、こちらも UF における LEM から従うことが知られています。
- Martín Hötzel Escardó: The Cantor-Schröder-Bernstein Theorem for ∞-groupoids  
  https://arxiv.org/abs/2002.07079
## searchable な無限集合
この節では一見本題とは関係ない話をします。実際、本題と切り離しても有意義な話です。
### LPO
LPO とは、「任意の関数 $p:\mathbb N\to 2$ について、 $\exists n.\ pn=0\lor\neg(\exists n.\ pn=0)$」という命題のことです。
$pn=0$ をみたす $n$ を $p$ の根と呼ぶことにすると、LPO は「 $p$ の根が $\mathbb N$ の中にあるかどうかを判定できる」のように解釈することができます。

LEM から LPO が従います。 LPO は構成的には示せず、 LEM は LPO から従わないことが知られています。

LPO の中の $\mathbb N$ を一般の集合 $X$ に変えたものを LPO $X$ と表すことにします。
$X$ が有限集合の場合、根をしらみつぶしに探せるので LPO $X$ は構成的に成り立ちます。
$X$ が無限集合（ここでは $\mathbb N$ からの単射をもつ集合を指す）の場合はしらみつぶしに探す手法は使えなくなります。
「特定の無限集合 $X$ に対してしらみつぶし以外の良い探し方があって、LPO $X$ が構成的に成り立つ」というのがこの節の話です。
### 酒飲みのパラドックス
しらみつぶし以外の良い探し方とはどういうものでしょうか。ここでまた一見無関係な話をします。

酒飲みのパラドックスの主張は、「人がいるパブには以下をみたす人 $a$ が存在する： $a$ が酒を飲んでいるならパブにいる全員が酒を飲んでいる」というものです。
集合の話にすると、「元をもつ集合 $X$ と関数 $p:X\to 2$ に対して、 $\exists a\in X.\ (pa=1\to\forall x\in X.\ px=1)$ 」という命題に対応します。

「関数 $p:X\to 2$ に対して、 $\exists a\in X.\ (pa=1\to\forall x\in X.\ px=1)$ 」という命題を DP $X$ と表すことにします。
DP $X$ は LEM から従いますが、一般には構成的には示せません。
しかし、特定の無限集合 $X$ に対して DP $X$ が構成的に示せます。DP $X$ が成り立てば、 "その $a$" について $pa$ を求めることで $p$ の根の有無が判定できます。
### 特定の無限集合 $\mathbb N_\infty$
$\mathbb N_\infty$ の定義はいくつかあります。
ここでは「 $2^{\mathbb N}$ の元のうち、数列として広義単調減少なもの全体がなす部分集合」を $\mathbb N_\infty$ と表すことにします。
例えば $11000\ldots$, $00000\ldots$, $11111\ldots$ は $\mathbb N_\infty$ の元です。

$\mathbb N_\infty$ と $\mathbb N$ の間に全単射が存在することは LPO と同値です。
構成的な議論の中では集合が位相空間のようにふるまうことがあり、そのような状況では $\mathbb N$ は離散位相、 $2^{\mathbb N}$ は直積位相が入っているようにふるまいます。 $\mathbb N_\infty$ は $\mathbb N$ の一点コンパクト化のようにふるまいます。 $11111\ldots$ が追加される一点に対応します。

単射 $(-)':\mathbb N\to \mathbb N_\infty$ を $n':=1^n0^\omega$ と定めます。 $n'$ は最初の $n$ 個が1であるような列です。
$\infty:=11111\ldots$ と定めます。

$\mathbb N_\infty=\mathbb N\cup\lbrace\infty\rbrace$ は LPO と同値です。これは構成的には示せませんが、
「 $n',\infty$ 以外の元が存在する」ということではありません。
「適当に渡された元が $1111\ldots$ のような形だと、いつか0が出るのかどうかが有限桁を見るだけではわからない」という解釈があり得ます。
### "その $a$" （ $pa=1\to\forall x\in X.\ px=1$ をみたす $a$ ）
$p:\mathbb N_\infty\to 2$ に対して、 $a\in \mathbb N_\infty$ を $a(n):=\min\lbrace px:x\leq n'\rbrace$ と定めます。
$p':=p \circ (-)'\in 2^{\mathbb N}$ を数列とみなすと、 $a$ は「 $p'$ について、最初から数えて1が何回連続で出るか」を表していると解釈できます。
例えば $p'=110100\ldots$ なら $a=2'$ 、 $p'=\infty$ なら $a=\infty$ となります。

LEM を認めれば、この $a$ が "その $a$" であることがわかります。これは
- $a=n'$ なら $pa=0$ なので $a$ が（最小の）根になる
- $a=\infty$ なら $p'=\infty$ なので、 $a$ が根かどうかで $p$ が根をもつかどうかが決まる

からです。
しかし、この $a$ が "その $a$" であることを構成的に示すためにはいくつか注意すべき点があります。
### トリック1： $a$ が有限でないなら、 $a=\infty$
まず、「 $a=n'$ なら $pa=0$ で $a$ が（最小の）根になる」というのは構成的にも普通に示せます。
この次に $\exists n.\ a=n'$ or $a=\infty$ という場合分けをしたいところですが、この場合分けには LPO が必要です。
しかし、 $(\neg\exists n.\ a=n')\to a=\infty$ は構成的に示せます。これは $\neg\exists$ と $\forall\neg$ の同値性から従います。

$a$ が "その $a$" であることを示しましょう。 $pa=1$ を仮定します。
- $a$ が有限だと仮定すると $pa=0$ なので矛盾。

よって $a$ は有限でなく、 $a=\infty$ です。よって $p'=\infty$ なので、 $p$ が $\mathbb N\cup\lbrace\infty\rbrace$ 上1であることがわかりました。
### トリック2： $p$ が $\mathbb N\cup\lbrace\infty\rbrace$ 上1なら全域で1
$p$ はほぼ1であることがわかりました。

$x\in \mathbb N_\infty$ とします。
- $px=0$ と仮定すると $x\notin \mathbb N\cup\lbrace\infty\rbrace$ で、 $x$ は有限でないので $x=\infty$ となり矛盾。

よって $px=1$ です。

以上で DP $\mathbb N_\infty$ が示されました。
### CSB から LEM が従うこと
本題に戻ります。
