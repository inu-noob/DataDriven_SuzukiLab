# 正誤表
| 箇所  | 内容  | 修正  | 備考  |
| :-: | --- | --- | --- |
| p. 264, eqs. (7.28), (7.29) |  最右辺  | 各要素を $k-1$ 乗する  |   |
| p. 265, eq. (7.30) | 右辺第3因子 | 第 1 列の各成分を $0$ 乗する |   |   |
| p. 267, para. 1 | 前ページの内容の謎の反復がされている |  |   |   |

# グレーゾーンな内容
| 箇所    | 内容  | 修正  | 備考  |
| :-: | --- | --- | --- |
| p. 286  |   |   | 以下”Koopman作用素の定義域について”参照  |

## Koopman作用素の定義域について
この本ではKoopman作用素の定義域としてヒルベルト空間と記述していることが多いので，定義域としてヒルベルト空間を採用することが標準的であるような印象を受けてしまうと思うのですが，非線形力学系の文脈では広くそのような考え方が普及している，という印象はありません．もちろん p. 286 に"other choices of a measure space are also valid" とあるので，著者も意識しているとは思います．
Koopman 作用素の双対である Perron-Frobenius 作用素は確率密度の空間を定義域とすることが標準的です．確率密度の空間は絶対可積分性が仮定される（定義域全体で積分値が 1 になることが要請されるので当然ですね）ので，$L^1$ です．Koopman 作用素は Perron-Frobenius 作用素の双対なので，$L^1$の双対空間である$L^\infty$ を定義域とすることも標準的なやり方です．というか測度論的力学系ではこちらが標準的だと思います（たとえば A. Lasota, M. C. Mackey, "Chaos, Fractals, and Noise: Stochastic Aspects of Dynamics", Springer, 1993）．
他方で，あまり測度論的な（確率的な）扱いが前面にでてこない比較的"おとなしい"力学系だと，確かにヒルベルト空間が標準的に用いられています．たとえば平衡点，周期軌道の吸引領域上で定義される関数の空間としてはヒルベルト空間を利用します（たとえば I. Mezić, "Spectrum of the Koopman Operator, Spectral Expansions in Functional Spaces, and State-Space Geometry", Journal of Nonlinear Science, 2020）．