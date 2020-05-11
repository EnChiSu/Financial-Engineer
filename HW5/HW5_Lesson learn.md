# HW5 Lesson Learn

1. Hull-White Model除了講義上的形式，也可以寫成如下(a不要乘進括號中)：
<p align="center">
  <img src="https://render.githubusercontent.com/render/math?math=dr=a[\theta(t)/a-r] \times dt %2B \sigma \times dz" width="300" height="30"></p>
    在Vasicek model的基礎上解釋為在t期下，short rate的移動會為revert rate a(想像為速率)乘上interest rate的均值theta(t)/a減去初始的spot rate，再加上依照volatility放大的隨機過程。
<br/>
<br/>

2. 根據此次作業的模擬，如果去調整參數做實驗，可以觀察到"reversion speed (a)"會影響long term level的interest rate，但不影響option的定價；而"volatility"會影響long term level的interest rate，但不影響option的定價；"initial interest rate"會影響long term level的interest rate以及option的定價。
<br/>

3. 蒙地卡羅模擬利用電腦的運算能力，直接模擬特定情況非常多次，在求平均，去近似實際預估計參數的期望值。例如我們已知下圖的正方形面積，想要估計正方形中的圓面積(或某個很不好求的面積)，我們在正方形內打非常多個點，看當中有多少個點會落入這個我們預估計的圓形當中，將這個落入的比例乘上正方形面積就會近似這個圓形的面積。<br/>
   (如果無法看到圖，請重新載入網頁，或在未顯示的圖上點滑鼠右鍵，選「載入圖片」)

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1v3Yt2XB1_lHJwdkt7kLDv8wZP4JJhZV8" width="400" height="400">
</p>
