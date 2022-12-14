# 復習

## アフィン平面 (Affine plane)

### 定義
アフィン平面は、以下の A1 - A3 の 3 つの点と呼ばれる集合と、直線と呼ばれる部分集合の集合のことである。

> A1: 2 点 $P, Q$ を含む直線はただ 1 つ存在する。

2 つの直線が**平行**であるとは、これらの直線が等しいか、共通の点を持たないことである。

>A2: 直線 $l$ と $l$ 上にない点 $P$ に対して、$P$ を通り $l$ に平行な直線がただ 1 つ存在する。

> A3: 同一直線上にない 3 点が存在する。

## 同値関係 (Equivalence relation)

### 定義

関係 $\sim$ が**同値関係**であるとは、以下の 3 つの条件を満たすことをいう。

1. 反射律: $a \sim a$
2. 対称律: $a \sim b \Rightarrow b \sim a$
3. 推移律: $a \sim b \land b \sim c \Rightarrow a \sim c$

アフィン平面における平行は同値関係である。

## 無限遠点と射影平面 (Ideal points and the projective plane)

アフィン平面に「**無限遠点**」を加えることで完備することを目的とする。

$A$ をアフィン平面とし、任意の直線 $l \in A$ に対し、$[l]$ を $l$ と平行な直線の束とし、これを**理想点**または**無限遠点**と呼び、$P^*$ で表記する。

※「束」と言うとある点を通る直線の集合というイメージがあるが、この束は無限遠点を通るという意味で使われてるものと思われる。

アフィン平面 $A$ を**完備化**して $S$ にするとは、以下の操作を行うことである。

1. $S$ の点は $A$ の点に $A$ の全ての無限遠点を追加したものである。
2. $S$ に含まれる直線は、以下の 2 パターンである。
    - $A$ の直線 $l$ に $P^* = [l]$ を足したもの
    - $A$ の全ての無限遠点を通る直線

## 定義

**射影平面** $S$ は、以下の 4 つの公理を満たす、点と呼ばれる要素の集合と、直線と呼ばれる部分集合の集合のことである。

> P1: $S$ 上の異なる 2 点 $P, Q$ を通る直線はただ 1 つ存在する。

> P2: 任意の 2 つの直線は少なくとも 1 点で交わる。

> P3: 同一直線上にない 3 点が存在する。

> P4: 任意の直線は少なくとも 3 点を含む。

このとき、アフィン平面 $A$ を完備化したものは射影平面となり、ユークリッド幾何における実アフィン平面を完備化したものを**実射影平面**と呼ぶ。

## 実射影平面における斉次座標 (Homogeneous coordinate in the real projective plane)

$\mathbb{R}^3$ 上において、実射影平面 $S$ の点を原点を通る直線と考える。そして、$S$ の点 $P$ を $(0, 0, 0)$ と異なるある $l$ 上の点 $(x_1, x_2, x_3)$ を選ぶことで表現する。この $x_1, x_2, x_3$ を$P$ の斉次座標という。このとき、$(x_1, x_2, x_3)$ と $(\lambda x_1, \lambda x_2, \lambda x_3)\ (\lambda \in \mathbb{R})$ は同一であると見なす。

$\mathbb{R}^3$ 上の原点を通る平面の方程式は

$a_1 x_1 + a_2 x_2 + a_3 x_3 = 0\ ((a_1, a_2, a_3) \neq (0, 0, 0))$

となり、この式は $S$ 上の直線の方程式を斉次座標で表したものになる。

### 定義 (同型)

2 つの射影平面 $S, S'$ が**同型**であるとは、同一直線上にある 2 点が同一直線上に移るような全単射の写像 $T: S \rightarrow S'$ が存在することである。

### 定理

要素が実数である斉次座標によって定義された射影平面 $S$ はユークリッド幾何の普通のアフィン平面を完備化したものと同型である。

## デザルグの定理

### デザルグの定理

2 つの三角形 $ABC, A'B'C'$ が、直線 $AA', BB', CC'$ が 1 点 $O$ で交わるようなものであるとする。この時、直線 $AB$ と直線 $A'B'$ の交点 $P$ 、直線 $BC$ と直線 $B'C'$ の交点 $Q$ 、直線 $AC$ と直線 $A'C'$ の交点 $R$ は 1 直線上にある。

これは P1~P4 から証明できず、射影平面で成り立つとは限らない。しかし、実射影平面では成り立つ。

### 定義 (射影 3 次元空間)

**射影 3 次元空間**とは、以下の 6 つの公理を満たす、点と呼ばれる要素の集合と、直線と呼ばれる部分集合の集合と、平面と呼ばれる他の部分集合の集合のことである。

> S1: 異なる 2 点 $P, Q$ を通る直線はただ 1 つ存在する。

> S2: 同一直線上にない 3 点は同一平面上に存在し、そのような平面はただ 1 つである。

> S3: 任意の直線は任意の平面と少なくとも 1 点で交わる。

> S4: 任意の 2 平面は少なくとも 1 つの共線を持つ。

> S5: 同一平面上にないかつ、そのうち 3 つは同一直線上にない 4 点が存在する。

> S6: 任意の直線は少なくとも 3 点を含む。

デザルグの定理は射影 3 次元空間でも成り立つ。特に、デザルグの定理は射影 3 次元空間の任意の平面上 (これは射影平面である) でも成り立つ。

//おそらくここの証明で詰まった記憶があるのでここから再開

# 本編

## 定義 (配置)

**配置**とは、以下の公理を満たす、点と呼ばれる要素の集合と、直線と呼ばれる部分集合の集合である。

> C1: 異なる 2 点は多くても 1 つの直線上にある。

これは異なる 2 つの直線は多くても 1 つの交点を持つことを意味する。

ex. 任意のアフィン平面と射影平面は配置である。点の集合で、直線が存在しないものも配置である。デザルグの定理によって引き起こされる 10 個の点と 10 本の直線は配置である。

## 定義 (free projective plane)

$\pi_0$ を配置とする。**$\pi_0$ によって作られた free projective plane** を以下のように定義する。

$\pi_1$ を以下に従って作られた新しい配置とする。

- $\pi_1$ の任意の点は $\pi_0$ と同一である。
- $\pi_1$ の任意の直線は $\pi_0$ に含まれるものと、同一直線上にない直線 $P_1, P_2 \in \pi_0$ が存在した場合、新しい直線 $\{P_1, P_2\}$ を追加されたものである。

このとき、$\pi_1$ の任意の異なる 2 頂点は同一直線上に存在する。

$\pi_2$ を $\pi_1$ から同様に生成する。この場合、交わらない直線 $l_1, l_2$ があった場合、新しく点を追加し、 $l_1, l_2$ どちらにもこの点を追加することで交わるようにする。

このとき、任意の異なる 2 直線は 1 点で交わるが、任意の異なる 2 頂点が同一直線上に存在することがなくなる。

この操作を繰り返し、 $\pi_{n + 1}$ を、$n$ が偶数なら直線を追加し、奇数なら点を追加することで構成する。

このとき、 $\Pi = \bigcup_{n = 0}^\infty \pi_n$ とする。 $\Pi$ の直線を $n$ が大きいとき、$L \cap \pi_n$ が $\pi_n$ の直線となるような $L \in \Pi$ の部分集合とする。

## 命題 2.2

$\pi_0$ が少なくとも 4 点を含んでいて、どの 3 点も同一直線上に存在しないならば、$\Pi$ は射影平面である。

**証明**

$n$ が奇数の場合 P1 を満たし、$n$ が偶数の場合 P2 を満たす。よって、$\Pi$ は P1 と P2 を満たす。

もし $P, Q, R$ が $\pi_0$ が同一直線上にないなら、それらは $\Pi$ においても同一直線上にない。よって P3 も満たされる。

$n$ が奇数のとき、 $l$ を 2 点のみを含む直線とする。点の個数は 4 以上であるから、 $l$ に含まれない点のみで構成された直線 $m$ が存在する (この直線はこれより前の操作で追加されている)。よって、操作によって $l$ と $m$ に点が 1 つ加わるから、 $l$ は 3 点を含む。これを繰り返すことで P4 は満たされる。(要検証)

## 定義 (閉じた配置)

**閉じた配置**とは、任意の点が少なくとも 3 本の直線を通り、全ての直線が 3 点以上を含む配置のことである。

## 命題2.3

$\Pi$ の任意の有限である閉じた配置は $\pi_0$ に含まれている。

**証明**

点 $P \in \Pi$ に対して、**レベル**を $P \in \pi_n$ となる最小の $n \geqq 0$ と定義する。
同様に、直線 $L \in \Pi$ に対して、**レベル**を $L \cap \pi_n$ が直線であるような最小の $n \geqq 0$ と定義する。

$\Sigma$ を $\Pi$ に含まれる有限の閉じた配置とする。そして、 $n$ を $\Sigma$ に含まれる点、直線のレベルの最大値とする。 $\Sigma$ に含まれる直線 $l$ のレベルが $n$ であると仮定する。 $l \cap \pi_n$ は直線で、 $l \cap \pi_{n - 1}$ は直線でない。もし $n = 0$ なら $\Sigma$ は $\pi_0$ を含むので命題を満たす。もし $n > 0$ なら、

# 群と自己同型写像

## 定義 (群)

**群**とは、積と呼ばれる二項演算が付いた、以下を満たす集合 $G$ のことである。

> G1: 結合法則が成り立つ。すなわち、任意の $a,b,c \in G$ に対して $(ab)c = a(bc)$ が成り立つ。

> G2: $a \dot 1 = 1 \dot a = a$ が任意の $a \in G$ に対して成り立つ $1 \in G$ が存在する。

> G3: 任意の $a \in G$ に対して $a a^{-1} = a^{-1}a = 1$ となる $a^{-1} \in G$ が存在する。

G2 における $1$ を**単位元**といい、 $a^{-1}$ を $a$ の**逆元**という。

## 例 (群)

1. $S = \{1,2,3\}$ 、 $G$ を $S$ の置換全体の集合とする。 $g_1, g_2 \in G$ のとき、 $g_1g_2$ を $g_2$ の置換を適用した後、 $g_1$ の置換を適用したものとすると、これは群を成す。
2. $C$ を配置、 $G$ を $C$ の自己同型群とすると、 $g_1, g_2 \in G$ のとき、 $g_1g_2$ を $g_2$ によって写した後、 $g_1$ によって写したものとすると、これらは群を成し、 $\mathrm{Aut}\ C$ と呼ばれる。

## 定義 (準同型写像、同型写像)

写像 $\phi : G_1 \rightarrow G_2$ が**準同型写像**であるとは、任意の $a,b \in G_1$ に対して $\phi(ab) = \phi(a)\phi(b)$ が成り立つことである。

また、$\phi$ が**同型写像**であるとは、$\phi$ が準同型写像かつ全単射であることである。

## 定義 (部分群)

$G$ を部分群とし、 $H$ を $G$ の空でない部分集合であるとする。このとき、 $H$ が**部分群**であるとは、任意の $a, b \in H$ に対して $ab \in H$ かつ $a^{-1} \in H$ が成り立つことである。

このとき、 $1$ は必ず $H$ に含まれ、これは $H$ の中でも単位元である。

## 例 (部分群)

$G$ を $S$ の順列全体の集合とすると、ある $x \in S$ を持ってきて、 $H = \{g \in G\ |\ g(x) = x\}$ は $G$ の部分群である。

## 定義 (左剰余類)

$G$ を群とし、 $H$ の $G$ の部分群であるとする。 $g \in G$ に対して、**$g$ によって生成された左剰余類**を

$$
 gH = \{gh\ |\ h \in H\}
$$

とする。

## 命題 3.1

$G$ を群、 $H$ を $G$ の部分群とし、 $gH$ を左剰余類とする。このとき、 $H$ と $gH$ の間には全単射となる写像が存在する。

### 証明

$gh_1 = gh_2$ となる $h_1, h_2 \in H$ が存在すると仮定する。このとき、

$$
    g^{-1}(gh_1) = g^{-1}(gh_2) \\
    (g^{-1}g)h_1 = (g^{-1}g)h_2 \\
    h_1 = h2
$$

より $h \rightarrow gh$ によって定義される写像は単射である。ゆえに全射であることも示すことが出来た。

## 系 3.2

$G$ を有限群、 $H$ を $G$ の部分群とする。このとき、 $\#(G) = \#(H) \times (H の左剰余類の個数)$ である。

### 証明

前の命題より、 $H$ の左剰余類の個数は全て $H$ と同じである。

もし $g \in G$ ならば、 $g = g \times 1$ 、 $1 \in H$ より $g \in gH$ である。よって、 $G$ は $H$ の左剰余類の集合である。

## 9 点のアフィン平面の自己同型

位数は $ 9 \times 8 \times 6 = 432$ で、

## 実射影平面の自己同型

### 定義（実射影平面）

点が $(x_1, x_2, x_3)$ で表されているとき、 $0$ でない実数 $\lambda$ に対して $(x_1, x_2, x_3)$ と $(\lambda x_1, \lambda x_2, \lambda x_3)$ は同じ点を表す。

直線は、方程式 $a_1x_1 + a_2x_2 + a_3x_3 = 0\ (a_i \in \mathbb{R}, (a_1, a_2, a_3) \neq (0, 0, 0))$ を満たす点の集合である。

### 簡単な行列の復習

$n \times n$ の**実行列**とは、 $n^2$ 個の実数の集合で、 $2$ つの添え字 $i, j\ (1 \leq i, j \leq n)$ を持つものである。従って、 $A = \{a_{11}, a_{12}, \dots , a_{21}, a_{22}, \dots , a_{n1},a_{n2}, \dots , a_{n,n}\}$ となる。普通は四角形の形で表される。

$$
\begin{pmatrix}
    a_{11} & a_{12} & \cdots & a_{1n} \\
    a_{21} & a_{22} & \cdots & a_{2n} \\
    \vdots & \vdots & \vdots & \vdots \\
    a_{n1} & a_{n2} & \cdots & a_{nn}
\end{pmatrix}
$$

$2$ つの行列 $A(a_{i,j})$ と $B(b_{i,j})$ の積は

$$
    c_{ij} = \sum_{k = 1}^n a_{ik}b_{kj}
$$

となる $C(c_{i,j})$ を用いて $A \cdot B = C$ と表される。

**行列式**は、 $n \times n$ 行列から $\mathbb{R}$ への関数で、以下の性質によって特徴づけられる。

D1: $A, B$ が $2$ つの行列の時、 $\det(AB) = \det(A) \cdot \det(B)$

D2: $a \in \mathbb{R}$ について、 $(A \cdot B) \cdot C = A \cdot (B \cdot C)$ で、 $\det A \neq 0$ のときのみ行列 $A$ に対して逆行列 $A^{-1}$ がある。

従って、 $\det A \neq 0$ である $n \times n$ 行列の集合は乗法について群をなし、これを $\mathrm{GL}(n, \mathbb{R})$ と表す。

D3: 

$A = (a_{ij})$ を行列とし、

$$
a_{11}x_1 + a_{12}x_2 + \dots + a_{1n}x_n = b_1 \\
a_{21}x_1 + a_{22}x_2 + \dots + a_{2n}x_n = b_2 \\
\vdots \\
a_{n1}x_1 + a_{n2}x_2 + \dots + a_{nn}x_n = b_n \\
$$

という連立方程式について考える。

$\det A \neq 0$ のときこの連立方程式は解を持つ。逆に、任意の $b_1, b_2, \dots, b_n$ に対してこの連立方程式が解を持つならば、 $\det A \neq 0$ である。

D1, D2 から D3 が導かれる。なぜなら、 $x_1, x_2, \dots, x_n$ が連立方程式の解であることは、

$$
A
\begin{pmatrix}
x_1 \\ x_2 \\ \vdots \\ x_n
\end{pmatrix}
=
\begin{pmatrix}
b_1 \\ b_2 \\ \vdots \\ b_n
\end{pmatrix}
$$

と同値であるからである。

$A$ を $3 \times 3$ 行列、 $\pi$ を同次座標が $x_1, x_2, x_3$ である実射影平面とする。 $\pi$ の変換 $T_A$ を以下のように定義する：点 $(x_1, x_2, x_3)$ が

$$
T_A(x_1, x_2, x_3) = (x_1', x_2', x_3') \\
$$

に移る。ただし、

$$
\begin{align*}
x_1' = a_{11}x_1 + a_{12}x_2 + a_{13}x_3 \\
x_2' = a_{21}x_1 + a_{22}x_2 + a_{23}x_3 \\
x_3' = a_{31}x_1 + a_{32}x_2 + a_{33}x_3 \\
\end{align*}
$$

である。

## 命題 3.7

$A$ が $\det A \neq 0$ の $3 \times 3$ 行列の時、 $T_A$ は実射影平面 $\pi$ の自己同型写像である。

**証明**

(1) $(x_1, x_2, x_3)$ を $(\lambda x_1, \lambda x_2, \lambda x_3)$ に置き換えると、 $(x_1', x_2', x_3')$ が $(\lambda x_1', \lambda x_2', \lambda x_3')$ に置き換わること、また $(x_1', x_2', x_3') \neq (0,0,0)$ であることを示す。

$$
\begin{align*}
    A
    \begin{pmatrix}
    x_1 \\ x_2 \\ x_3
    \end{pmatrix}
    =
    \begin{pmatrix}
    x_1' \\ x_2' \\ x_3'
    \end{pmatrix}
\end{align*}
$$

ここで $\begin{pmatrix} x_1 \\ x_2 \\ x_3\end{pmatrix}$ は $\begin{pmatrix} x_1 & 0 & 0 \\ x_2 & 0 & 0 \\ x_3 & 0 & 0\end{pmatrix}$ を表す。

$\det A \neq 0$ なので $A$ は逆行列 $A^{-1}$ を持つので $A^{-1}$ を左からかけて $(x) = A^{-1}(x')$
よって、 $x_i'$ が全て $0$ なら $x_i$ も全て $0$ であるが、これは矛盾する。よって、 $x_i'$ は全て $0$ になることは無い。

ゆえに、 $T_A$ は well-defined な $\pi$ から $\pi$ への写像である。

(2) $\det A \neq 0$ より $A^{-1}$ が存在し、 $\bm{x'} = A \bm{x}$ なら $\bm{x} = A^{-1} \bm{x'}$ であるから、 $T_{A^{-1}}$ は $T_A$ の逆写像である。従って $T_A$ は全単射でなければならない。

(3) $T_A$ によって同一直線上にある点が同一直線上に移ることを示す。

$$
\begin{align*}
    c_1x_1 + c_2x_2 + c_3x_3 = 0\ \cdots (*)
\end{align*}
$$

を直線の方程式とする。 $(*)$ を満たす任意の点 $(x_1, x_2, x_3)$ について、 $T_A$ によって移った点 $(x_1', x_2', x_3')$ が別の直線上にあることを示せばよい。

$A^{-1} = (b_{ij})$ とする。すると、

$$
\begin{align*}
    x_i = \sum_{i = 1}^3 b_{ij}x_j'
\end{align*}
$$

が任意の $i$ について成り立つ。よって、 $(x_1, x_2, x_3)$ が $(*)$ を満たしているなら

$$
\begin{align*}
    c_1 (\sum_{i = 1}^3 b_{i1}x_1) + c_2 (\sum_{i = 1}^3 b_{i2}x_2) + c_3 (\sum_{i = 1}^3 b_{i3}x_3) = 0 \\
    (\sum_{i = 1}^3 c_ib_{i1}) x_1' + (\sum_{i = 1}^3 c_ib_{i2}) x_2' + (\sum_{i = 1}^3 c_ib_{i3}) x_3' = 0
\end{align*}
$$

この式は、直線の方程式である。よって、あとは

$$
\begin{align*}
    c_i' = \sum_{j = 1}^3 c_jb_{ji}\ (1 \leq i \leq 3) \cdots (**)
\end{align*}
$$

が全て $0$ でないことを示せばよい。 $(**)$ から $(c_1, c_2, c_3) = A^{-1} (c_1', c_2', c_3')$ が分かり、もし $(c_1', c_2', c_3') = (0, 0, 0)$ なら $(c_1, c_2, c_3) = (0, 0, 0)$ となり、これは $(*)$ が直線の方程式であることから矛盾。よって $(c_1', c_2', c_3') \neq (0, 0, 0)$ である。

ゆえに、 (1) ~ (3) より、 $T_A$ は $\pi$ の自己同型写像である。

## 命題 3.8

$A, A'$ を $\det A \neq 0 ,\ \det A' \neq 0$ であるような $3 \times 3$ 行列であるとする。このとき、 $\pi$ の同型写像 $T_A, T_{A'}$ は $\lambda A = A'$ となる $\lambda \in \mathbb{R},\ \lambda \neq 0$ が存在するときに限り等しい。

**証明**



