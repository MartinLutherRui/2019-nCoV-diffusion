## 2019-nCoV疫情传播模型

### 概述

此次2019-nCoV报道以来，出现了以下两个预测模型：

- SIR模型：德国哥廷根大学于晓华教授在[微博上给出的SIR模型](https://weibo.com/u/1684992301?is_hot=1#_rnd1579701992368)，采用SARS的模型参数。
- 城际传播模型：世卫组织传染病建模合作中心、英国帝国理工学院MRC全球传染病分析中心（MRC Centre for Global Infectious Disease Analysis）提供的城际传播模型及简单估计，原文请参阅[这里](http://www.imperial.ac.uk/mrc-global-infectious-disease-analysis/news--wuhan-coronavirus/)。

我们分别改善了这两个模型，并采用二者**相互印证**，以期得到较为准确的结果。

### SIR模型

我们在SIR模型中考虑了：平均7天的潜伏期。

### 城际传播模型

我们在城际传播模型中，分别就以下情形估计了模型：

- 国际传播
- 城际传播

