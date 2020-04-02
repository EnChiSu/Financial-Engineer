# Week 3 Class Introduction
上週討論的YTM是直接考慮入手到合約終止日的報酬率，但現實我們有可能只想hold這個合約3個月，或是不同商品到期日不同複利時間也不同，諸如此類情況YTM並無法作為比較的基準，因而這周討論另外三個概念(Yield curve, Forward rate, and Spot rate)，可用以作為不同時點對於某一債券的評估基準。(目的都是希望區估算我們買的價格是不是划算的)<br />

# Week 3 Class Notes
1. Yield Curve <br />
* 簡述：<br />
同一種債券在不同時間點發行(所以到期日不同)，因為經歷的時間不同(經歷不同的匯率波動以及存在不同的到期日)，所以從債券售價反推回算得到的YTM會不同，這些不同的YTM繪製出來的曲線就是yield curve。

* 換算公式：
![](https://drive.google.com/uc?export=view&id=1vFkOsPnXG98C4pTG00T1UCNIkdZGMfBw)


* 功能：
   1. PV、C、F與利率r間的數學公式，有兩種用法：<br />
   若給定PV、C與F，求出的利率r就是YTM，可用來與自己心中預期的報酬率比較，看是否值得進場。<br />
   若給定C、F與利率r，求出的PV就是理論價，可用來與市場價比較看市場目前情勢。<br />
   2. 可用以判斷大家對於市場的預期：<br />
   例如：短期的yield高於長期的yied，yield curve呈現U字型，表大家對於市場短期前景樂觀，會折價拋售手上的債券(去買股票)，因此當如果你買入經折價後的債券，算出來的yield就會高。<br />

* 缺點：
無法作為債券不同時間點下的比較基準，因為YTM直接計算到合約到期日，但有時你衡量的只想從當中的某一期到另一期的獲利率，因而就需要Spot rate & Forward rate。<br />

2. Spot rate <br />
* 簡述：<br />
某一期的Spot rate即可以想像為從本期開始計算到該期的零息債券的YTM。<br />

* 換算公式：
![](https://drive.google.com/uc?export=view&id=1kd4CDKyfbo88JL5pUO1cSKiTGqo7xbIK)



* 功能：
   使能夠將相同或不同債券在有不同到期日的報酬率進行比較。<br />


3. Forward rate <br />
* 簡述：<br />
站在現在評估未來某一期到另一期的「單利」。

* 換算公式：
![](https://drive.google.com/uc?export=view&id=1Dr2nNaxQxMuxo1QiyG66H8LnuE2DxOcj)



* 功能：
   使能夠將相同或不同債券在不同時間點起始、結算點下的報酬率進行比較。<br />
   例如：第一期到第二期forward rate較第三期到第四期的高，表市場對近期展望樂觀(因為市場展望樂觀-->大家拋售債券，債券變便宜-->單利提高)。


