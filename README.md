# ThreeMovingAverageTradingStrategy
基于优矿的三均线交易策略（期货）

优矿网站：https://uqer.datayes.com/

## 实现逻辑

5日均线上突破10日均线开仓，5日均线下穿30日均线卖出(为了能完整吃掉一个大趋势)，

回测结果显示年化收益率能大幅超过基准收益率，缺点是最大回撤达到68%，原因是止损过于频繁。

以下是在优矿上的回测结果：

![38dade8c404affbf68925a129b128ea](https://user-images.githubusercontent.com/54057111/120301900-eaff9700-c2ff-11eb-81a9-51da4bf10acd.png)
