# Predicting-stock-price-through-social-media

## 透過社群內容分析預測股價漲跌

![image](https://user-images.githubusercontent.com/51256347/123134246-2ca8db00-d483-11eb-89d9-982863819035.png)

###### 介紹
  * 內容分析學派的興起
  
  ![image](https://user-images.githubusercontent.com/51256347/123567240-45532100-d7f4-11eb-9f65-5a511551b2ee.png)
  來源：http://uk.businessinsider.com/ecb-twitter-bullishness-stock-market-moves-2015-7
  ![image](https://user-images.githubusercontent.com/51256347/123567519-ecd05380-d7f4-11eb-9cf6-2e8b246a8425.png)
  來源：https://devblogs.microsoft.com/cse/2017/12/04/predicting-stock-performance-deep-learning/
  
  * 許多研究論文指出，股價的走向可以從社群網站的資料內容被反應出來。事實上，股價的走向與公司重大消息、群眾心理等因素息息相關，而這些資訊可以從以下觀點在社群網站與媒體中被挖掘出來：
    1. **訊息易由社群傳播：** 不論市場訊息、專業訊息、或內部訊息，以社群傳播最為容易，進而全面擴散。
    2. **社群傳播速度快：** 不需編輯審核，發布速度最快。
    3. **群眾決定市場：** 當市場是由當市場是由群眾決定時，了解群眾的想法，即可預測市場。例如：群眾傳言將銀行破產，可能造成擠兌而真的破產。
    4. **消息不論真確度均值得參考：** 無論是流言或假消息，皆會影響大眾及市場。

###### 本專案分析方法：
  1. 資料集：2016~2018網路公開之新聞、論壇、PTT、股市價量交易資訊，並已過濾較不相關的文章(如日常例行發文、過短內容等)
  範例圖：![image](https://user-images.githubusercontent.com/51256347/123574900-42abf800-d803-11eb-9148-87953883c911.png)
  ![image](https://user-images.githubusercontent.com/51256347/123578168-d089e200-d807-11eb-8a6b-c43568392dea.png)


  3. 
