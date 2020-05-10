# Kaggle BreadBasket
Data [here](https://www.kaggle.com/laalarcon/breadbasket-selling-patterns).

字段：Date（日期），Time（时间），Transaction（交易ID）Item（商品名称）

min_support=0.02，min_confidence=0.5时, 一共有33个频繁项集，8种关联规则

使用efficient_apriori工具包, 效率较高，但返回参数较少

使用mlxtend.frequent_patterns工具包, 效率较低，但返回参数较多


