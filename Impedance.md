# インピーダンス

https://ja.wikipedia.org/wiki/%E3%82%A4%E3%83%B3%E3%83%94%E3%83%BC%E3%83%80%E3%83%B3%E3%82%B9


[基礎理論](./BasicTheory.md)

インピーダンスとは何？ 抵抗やリアクタンスとの違いも解説
2024.06.05
https://techweb.rohm.co.jp/product/power-device/si/15939/

用語

コンダクタンス≒インピーダンスの逆数の実数部

リアクタンス=複素インピーダンスの虚部

インダクタンス=誘導起電力　コイルの係数

# 合成インピーダンス
交流周波数 f [Hz]
抵抗 R [Ω]
インダクタンス L [H]
誘導性リアクタンス $` X_{L} [Ω] = 2πfL `$
静電容量 C [F]
容量性リアクタンス $` X_{C} [Ω] = \frac{1}{2πfC} `$

## RL直列回路
$$
Z [Ω] = \sqrt{R^2 + X_{L}^2} = \sqrt{ R^2 + (2πfL)^2}
$$

## RC直列回路
$$
Z [Ω] = \sqrt{R^2 + X_{C}^2} = \sqrt{ R^2 + (\frac{1}{2πfC})^2}
$$

## RLC直列回路
$$
Z [Ω] = \sqrt{R^2 + (X_{L}^2 - X_{C}^2)} = \sqrt{ R^2 + (2πfL - \frac{1}{2πfC})^2}
$$

## RL並列回路
$$
Z [Ω] = \frac{1}{\sqrt{(\frac{1}{R})^2 + (\frac{1}{X_{L}})^2}} = \frac{1}{\sqrt{(\frac{1}{R})^2 + (\frac{1}{2πfL})^2}}
$$

## RC並列回路
$$
Z [Ω] = \frac{1}{\sqrt{(\frac{1}{R})^2 + (X_{C})^2}} = \frac{1}{\sqrt{(\frac{1}{R})^2 + (2πfC)^2}}
$$

## RLC並列回路
$$
Z [Ω] = \frac{1}{\sqrt{(\frac{1}{R})^2 + (\frac{1}{X_{L}} - X_{C})^2}} = \frac{1}{\sqrt{(\frac{1}{R})^2 + (\frac{1}{2πfL} - 2πfC)^2}}
$$


# 測定
インピーダンスをできるだけ正確に測定する方法
https://www.aps-web.jp/academy/ec/6501/

