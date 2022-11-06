## 外冪
$R$ : 可換環、 $V,M,N$ : $R$ 加群  
自然な交代多重線型写像 $\wedge:M^I \to \Lambda^IM$ が定まる。
### $\Lambda^I$ の関手性
$f:M\to N$ に対して
$\Lambda^I f : \Lambda^IM\to \Lambda^I N$ を $(\Lambda^I f) (\wedge m) = \wedge (\lambda i. f(mi))$ と定める。  
関手 $\Lambda^I:\mathrm{Mod}_R\to \mathrm{Mod}_R$ が定まる。
### $\Lambda^k R^n$
順序を保つ単射 $f:\lbrace 1,\ldots,k\rbrace \to \lbrace 1,\ldots,n\rbrace$ がなす集合を $\binom nk$ と表す。  
$R^\binom nk\to \Lambda^k R^n$ , $e_f\mapsto e_{f1}\wedge\cdots \wedge e_{fn}$は同型。  
$\Vert V\simeq R^n\Vert$ のとき、 $\Vert \Lambda^k V\simeq \Lambda^k R^n\Vert$ なので $\Vert \Lambda^k V\simeq R^\binom nk\Vert$.
### determinant
$\Lambda^n R^n\simeq R$ なので $R\simeq \mathrm{End}\ \Lambda^n R^n$ , $r\mapsto \lambda x.rx$.  
$\Vert V\simeq R^n\Vert$ のとき、 $\Vert \Lambda^n V\simeq R\Vert$ なので $R\simeq \mathrm{End}\ \Lambda^n V$ , $r\mapsto \lambda x.rx$ （truncation を外せる。つまりこの同型は基底の取り方に依存しない）。  
逆を $g:\mathrm{End}\ \Lambda^n V \to R$ と表す。 $\det : \mathrm{End}\ V\to R$ を $\det=g\circ \Lambda^n$ と定める。
### pairing
$\wedge : \Lambda^k M \otimes \Lambda^l M\to\Lambda^{k+l} M$ , $(m_1\wedge\cdots\wedge m_i) \otimes (m_1'\wedge\cdots\wedge m_j')\mapsto m_1\wedge\cdots\wedge m_i\wedge m_1'\wedge\cdots\wedge m_j'$
は $M$ に関して自然。  
### $\wedge : \Lambda^k R^n\otimes \Lambda^{n-k}R^n \to \Lambda^n R^n$ は perfect
