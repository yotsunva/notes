$\DeclareMathOperator{\Aut}{Aut}$
$S_4$ において考える。
### $H:=\langle (1\ 2\ 3\ 4) ,(2\ 4)\rangle$ の構造を求めよ。
$a:=(1\ 2\ 3\ 4)$ , $b:=(2\ 4)$ とおく。  
- $a^b=(1\ 4\ 3\ 2)=a^{-1}$ より $\langle a\rangle \unlhd H$ , $H=\langle a\rangle\langle b\rangle$.
- $\langle a\rangle\cap\langle b\rangle=1$

より $H\cong \langle a\rangle\rtimes\langle b\rangle\cong D_4$.
### $G/H$ の完全代表系を一つ求めよ（ここで $V_4$ の block system と対応させておいた方が良さそう）。
$c=(1\ 2\ 3)$ とおく。
- ラグランジュの定理より $c\notin H$. よって $cH\neq H$.
- $c^2\notin H$ より $c^2H\neq H$. $cH\neq H$ より $c^2H\neq cH$.
よって $1,c,c^2$ が完全代表系。
### $\rho:S_4\to \Aut_{\mathsf{Set}} (G/H)$ , $\rho g:=(xH\mapsto gxH)$ が全射であることを示せ。
$(H\ cH),(cH\ c^2H)$ の fiber の元を探して、 codomain がこれらで生成されるから ok.
