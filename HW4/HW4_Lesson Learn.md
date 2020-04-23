# HW 4 Lesson learn

1. 這兩周課程內容以及本次作業其實就是之前HW3 BOPM的延伸，同樣是要對選擇權的價格做定價，不過BOPM假設每一期只有兩種可能發生的情況，而本次則是假設股價會以Brownian Motion的方式遊走，未來每一期可能發生的股價會服從lognormal分配。根據這個新模擬出來的未來股價，我們就可以如同之前BOPM時定價的過程，使用Black Scholes formula和Put-Call parity去求出Call和Put的定價。


2. 常態分配最原始的cdf(從pdf積分過來)可以表示成
<img src="https://drive.google.com/uc?export=view&id=1F81cIk24hf4YJUuf4tyU3iQOsiSPxqmN"  width="800" height="280">
而維基百科在常態分配頁面當中的cdf使用error function來表示，藉此簡化函數的表現形式，而error function的定義如下
<img src="https://drive.google.com/uc?export=view&id=1oKtma-My6a1saGnQR6zdFVEsz5tac_TR"  width="800" height="150">




