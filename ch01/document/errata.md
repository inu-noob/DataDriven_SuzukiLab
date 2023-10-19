# 正誤表
| 箇所  | 内容  | 修正  | 備考  |
| :-: | --- | --- | --- |
| p. 15, para. 1  |  $$S^{n-1} \triangleq\left\lbrace\mathbf{x} \mid\|\mathbf{x}\|_2=1\right\rbrace \subset \mathbb{R}^n, $$ maps into an ellipsoid, $$\left\lbrace\mathbf{y} \mid \mathbf{y}=\mathbf{X} \mathbf{x} \text { for } \mathbf{x} \in S^{n-1}\right\rbrace \subset \mathbb{R}^{m},$$    |  $$S^{m-1} \triangleq\left\lbrace\mathbf{x} \mid\|\mathbf{x}\|_2=1\right\rbrace \subset \mathbb{R}^m, $$ maps into an ellipsoid, $$\left\lbrace\mathbf{y} \mid \mathbf{y}=\mathbf{X} \mathbf{x} \text { for } \mathbf{x} \in S^{m-1}\right\rbrace \subset \mathbb{R}^{n},$$   |     |
| p. 17, para. 4, Eq. (1.26b) | $\mathbb{R}^n$ |  $\mathbb{R}^m$ |         |
* para. c: 前ページから続いているパラグラフを指す．


# グレーゾーンな内容
| 箇所    | 内容  | 修正  | 備考  |
| :---: | --- | --- | --- |
| p. 5, para. 1 | "The SVD is a unique matrix decomposition ..."    |     | 一意 (unique) ではないです．独特の (unique) とかそういう意味でしょうか（そうも見えませんが…）．unique up to ** （** に関する差異を除いて一意）みたいな記述があれば正しくできるとは思います．<br> 参考: https://math.stackexchange.com/questions/644327/how-unique-are-u-and-v-in-the-singular-value-decomposition |
| p. 18, para. 4 | "Computing the pseudo-inverse ..." のパラグラフ |       |    比較してはいけないものを比較していると思います．逆行列を求めるコスト $\mathcal{O}(n^3)$ は SVD を求めるコスト（ $\mathcal{O}(mn \ {\rm min}(m,n))$，正方行列なら $\mathcal{O}(n^3)$ ）と比較すべきです．SVD の結果として得られる $\tilde{U}, \tilde{V}$ との行列積をとるコストは，逆行列との行列積をとるコスト（これはもちろん $\mathcal{O}(n^2)$ ）と比較すべきです．