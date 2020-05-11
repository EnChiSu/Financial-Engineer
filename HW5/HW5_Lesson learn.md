# HW5 Lesson Learn

1. Hull-White Model除了講義上的形式，也可以寫成如下(a不要乘進括號中)：
<p align="center">
  <img src="https://render.githubusercontent.com/render/math?math=dr=a[\theta(t)/a-r] \times dt %2B \sigma \times dz">
</p>
   在Vasicek model的基礎上解釋為在t期下，short rate的移動會為revert rate a(想像為速率)乘上interest rate的均值theta(t)/a減去初始的spot rate，再加上依照volatility放大的隨機過程。
<br/>
<br/>

2. 根據此次作業的模擬，如果去調整參數做實驗，可以觀察到"reversion speed(a)"會影響long term level的interest rate，但不影響option的定價；而"volatility"會影響long term level的interest rate，但不影響option的定價；"initial interest rate"會影響long term level的interest rate以及option的定價。
<br/>

3. 
