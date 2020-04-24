# HW 4 Lesson learn

1. 這兩周課程內容以及本次作業其實就是之前HW3 BOPM的延伸，同樣是要對選擇權的價格做定價，不過BOPM假設每一期只有兩種可能發生的情況，而本次則是假設股價會以Brownian Motion的方式遊走，未來每一期可能發生的股價會服從lognormal分配。根據這個新模擬出來的未來股價，我們就可以如同之前BOPM時定價的過程，使用Black Scholes formula和Put-Call parity去求出Call和Put的定價。
<br />

2. 在做選擇權定價的時候，我們需要用到以下三個理論(假設)：
   1) Ito process<br />
   假設股價服從Ito process，能夠用Ito process的方式表現，藉以能夠使用Ito integral對Brownian Motion做積分，讓我們可以找到未來股價服從的lognormal分配的參數。
   2) Forward contract的定價<br />
   由於不同時點下特定選擇權產生的現金流應該相同，則選擇權在當下應有的價格其實就等同假設我們現在借錢去買這個選擇權，應該要借多少來買去想(亦即選擇權在未來某個時點的履約金額折現回本期)。
   3) 資本資產定價模型(CAPM)<br />
   將風險中立的情境擴展到更符合現實的具有超額報酬的情境，將選擇權可能產生的payoff用這個超額報酬率來折現，使得在定選擇權當期價格上能夠更符合現實。
   
<br />

3. 常態分配最原始的cdf(從pdf積分過來)可以表示成 (如果無法看到圖，重新再載入網頁)
<img src="https://drive.google.com/uc?export=view&id=1F81cIk24hf4YJUuf4tyU3iQOsiSPxqmN"  width="800" height="280">
而維基百科在常態分配頁面當中cdf的表時則是如下
<img src="https://drive.google.com/uc?export=view&id=1yg4iSjg6xhVfwMKDvHKi65HPCmyykwUe"  width="800" height="150">
當中的erf即為error function，而error function的定義如下
<img src="https://drive.google.com/uc?export=view&id=1oKtma-My6a1saGnQR6zdFVEsz5tac_TR"  width="800" height="150">
erf與標準常態分配的cdf之間存在以下關係，維基百科透過erf來簡化常態分配cdf函數的呈現
<img src="https://drive.google.com/uc?export=view&id=1uo8y3dEhip9-VAzxZn6dRMjJtubn3A9j"  width="600" height="170">
