## 関数を区別する
$A,B$ : 集合、 $f_1,\ldots,f_n:A\to B$ は相異なるとする。
### $f_i|_S$ が相異なるような、高々 $n-1$ 元からなる集合 $S\subseteq A$ が存在する
$n$ に関する帰納法で示す。
  - $n=1$ の時は成り立つ。
  - $n\geq 2$ のとき、帰納法の仮定より $f_1|\_S, \ldots, f_{n-1}|_S$ が相異なるような、高々 $n-2$ 元からなる集合 $S$ が存在する。
    $f_i|_S= f_n|_S$ をみたす $i\leq n-1$ は高々一つなので、そのような $i$ があれば $f_i,f_n$ を区別するために $S$ に一つ元を加えれば条件がみたされる。
