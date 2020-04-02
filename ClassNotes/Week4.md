# Week 4 Class Introduction
上周介紹衡量商品的指標，本周介紹其中一種衍生性商品 ─ 選擇權(Option)、投資策略、投資組合以及選擇權權利金定價方式。<br />

# Week 4 Class Notes
1. Option <br />
   1. Call(買權)
      * 概述：
      擁有未來用某個價格買入的權利。包含約定的時間、約定的價格、選擇要不要買。
      
      * Payoff:
      C = max(0, S-X)
      ![](https://drive.google.com/uc?export=view&id=1N_OtPi90kMzm0krc56_akVrPp49nJ8Wg)
      
      * 市場含意：
      ![](https://drive.google.com/uc?export=view&id=1RBF9iNjGP8AyJAjTu_MFVSf70yX1H4wY)

      
   2. Put(賣權)
      * 概述：
      擁有未來在某個價格賣出的權利。包含約定的時間、約定的價格、選擇要不要買。
      
      * Payoff:
      P = (0, X-S)
      ![](https://drive.google.com/uc?export=view&id=1dqmK0GCkGo8Mgipd5U3ihe4YSANZ0xBc)
      
      * 市場含意：
      ![](https://drive.google.com/uc?export=view&id=1VgTYzGW9D1AQ5jsAtwZCzaUalg4LK0iQ)
   

2. 投資組合
   1. 買進Straddle(跨式部位) vs 買進Strangle(勒式部位) --> 都用在預期市場大漲大跌 
   | 投資策略 | 買進Straddle(跨式部位) | 買進Strangle(勒式部位) |
   |:-------------:|:-------------:|:-------------:|
   | 報酬線|![](https://drive.google.com/uc?export=view&id=1jAGbWBcHhiHPJxV5lABnH0CRPXQelvkZ)|![](https://drive.google.com/uc?export=view&id=18eajlNiLNB8eLGY8azBzOb4vYBhcJ6Up)
   | 使用時機 |  市場大漲大跌 | 市場大漲大跌 |
   | 差異 | 買權賣權買在履約價相同處 | 買權賣權買在履約價不相同處 |
   
   2. Strangle(勒式部位)
   | 投資策略 | 賣出Straddle(跨式部位) | 賣出Strangle(勒式部位) |
   |-------------|-------------|-------------|
   | 報酬線|![](https://drive.google.com/uc?export=view&id=19s90BK_bV9jBF_-NoS-1PVyl3-kYAIvf)|![](https://drive.google.com/uc?export=view&id=1Ehe9Ex7A7MSkGgLtEAdLJZhIxIhQG1Ft)
   | 使用時機 |  市場波動不大 | 市場波動不大 |
   | 差異 | 買權賣權買在履約價相同處 | 買權賣權買在履約價不相同處 |

3. 選擇權權利金定價方式

