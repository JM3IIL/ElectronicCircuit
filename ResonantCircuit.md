# 共振回路

http://www.gxk.jp/elec/musen/1ama/H16/html/H1608A05_.html
http://take103.blog.fc2.com/blog-entry-86.html

## LC回路
- コイル : L [H]
- コンデンサ : C [F]

直列共振条件
- $2πfL = \frac{1}{2πfC}$
並列共振条件
- $\frac{1}{2πfL} = 2πfC$

共振周波数
- $f = \frac{1}{2\pi\sqrt{LC}} [Hz]$

ROHM Tech WEB : 共振回路：共振周波数の計算方法、Q値の求め方を解説 (2024-06-28)
https://techweb.rohm.co.jp/product/power-device/si/18332/

Wikipedia (JP)
https://ja.wikipedia.org/wiki/LC%E5%9B%9E%E8%B7%AF

直列共振
https://hegtel.com/chokuretsu-kyoshin-kairo.html

https://detail-infomation.com/rlc-series-resonant-circuit-quality-factor/

並列共振
https://hegtel.com/heiretsu-kyoshin-kairo.html


## 直列共振回路

- インピーダンス : Z [Ω]

$Z = R + j(X_L + X_C) = R + j(ωL - \frac{1}{ωC})$
$Q = \frac{ωL}{R} = \frac{1}{ωCR}$

共振時には、 $(ωL - \frac{1}{ωC})$ 部分が0なので、LC部の電圧は0になり、Rの電圧は電源電圧と同じになる。
https://ameblo.jp/ja8rqd/entry-12878248724.html

## 並列共振回路

- インピーダンス : Z [Ω]

$Z = \frac{1}{\frac{1}{R} + \frac{1}{j}(\frac{1}{X_L} + \frac{1}{X_C})} = \frac{1}{\frac{1}{R} + \frac{1}{j}(\frac{1}{ωL} - ωC)}$
$Q = \frac{R}{ωL} = ωCR$

共振時には、 $(\frac{1}{ωL} - ωC)$ 部分が0なので、LC部の電圧は0になり、Rの電圧は電源電圧と同じになる。

