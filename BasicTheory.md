# 基礎理論
## Wheatstone bridge : ホイートストンブリッジ
https://wakariyasui.sakura.ne.jp/p/elec/kairo/hoi-to.html

## キルヒホッフの法則
電流則 : キルヒホッフの第1法則(Kirchhoff's current law : KCL)
回路網中の任意の接続点に流出入する電流の和は0である
電圧則 : キルヒホッフの第2法則(Kirchhoff's voltage law : KVL)
回路網中の任意の閉路を一巡するとき、起電力の総和と電圧降下の総和は等しい
https://wakariyasui.sakura.ne.jp/p/elec/kairo/kiruhi.html



## 静電容量の計測
https://www.fluke.com/ja-jp/learn/blog/digital-multimeters/how-to-measure-capacitance

https://article.murata.com/ja-jp/article/basics-of-capacitors-7


## インダクタンスの計測
https://sakamoto-tt.sakura.ne.jp/wordpress/wp-content/uploads/2013/07/e4af4a5f72b3b86a1d6ec788ae8b7a8d.pdf


# 単相交流回路

## 抵抗と誘導性リアクタンスの直列回路
単相交流電源に、負荷RとコイルLが直列
(負荷Rの抵抗はR [Ω]、コイルLのリアクタンスは $X_{L}$ [Ω])
$$V_{R} = IR [V] , V_{L} = IX_{L} [V]$$

電圧 $V = \sqrt{{V_{R}}^{2} + {V_{L}}^{2}}$ [V]
インピーダンス $Z = \sqrt{R^{2} + {X_{L}}^{2}}$ [Ω]
電流 $I = \frac{V}{Z} = \frac{V}{\sqrt{{V_{R}}^{2} + {V_{L}}^{2}}}$ [A] 
力率 $cos θ = \frac{R}{Z} = \frac{R}{\sqrt{{V_{R}}^{2} + {V_{L}}^{2}}}$ 
電力 $P= VI cos θ$ [W] 

https://detail-infomation.com/rl-series-circuit-impedance/

## 抵抗と誘導性リアクタンスの並列回路
単相交流電源に、負荷RとコイルLが並列
(負荷Rの抵抗はR [Ω]、コイルLのリアクタンスは $X_{L}$ [Ω])
$$V = I_{R}R [V] , V = I_{L}X_{L} [V]$$

インピーダンス $Z = \frac{RL}{\sqrt{R^{2} + {X_{L}}^{2}}}$ [Ω]
全電流 $I = \sqrt{{I_{R}}^{2} + {I_{L}}^{2}}$ [A] 
力率 $cos θ = \frac{I_{R}}{I} = \frac{I_{R}}{\sqrt{{I_{R}}^{2} + {I_{L}}^{2}}}$
電力 $P= VIcos θ = {I_{R}}^{2}R = VI_{R}$ [W]

https://detail-infomation.com/rl-parallel-circuit-impedance/


# 基本素子

https://ja.m.wikibooks.org/wiki/%E9%9B%BB%E6%B0%97%E5%9B%9E%E8%B7%AF%E7%90%86%E8%AB%96/%E5%9B%9E%E8%B7%AF%E7%B4%A0%E5%AD%90

## 抵抗(レジスタ)
$$R = \frac{V}{I}$$


導体の抵抗
長さL
断面積S
の導体の抵抗値Rは
$R=ρ\frac{L}{S}$

ρ(ロー)[Ωm]は下表(× $10^{-8}$ )
|金属|ρ|
|:--|--:|
|銀　|1.6|
|銅　|1.7|
|金　|2.4|
|アルミ|2.8|
|鉄　|9.0|


## コンデンサ(キャパシタ)
平行板コンデンサ
電極板の面積を A、電極板の間隔を d とすると、
静電容量 $C ≃ \frac{εA}{d}$
比例係数 ε (epsilon)は電極板間を絶縁する誘電体の誘電率。
この近似が成り立つには電極板の間隔 d が充分に小さい（
$𝑑 ≪ \sqrt{A}$
あるいは電極板の面積 A が充分に大きい（
$𝐴 ≫ 𝑑^{2}$という条件が必要。

カップリング = DCブロッキングキャパシタ
デカップリング = バイパスコンデンサ : 直流電源の電圧が変動するのを避けるために、電源ラインとグラウンドとを接続するコンデンサ


https://industrial.panasonic.com/jp/ss/technical/b3



## コイル(インダクタ)

