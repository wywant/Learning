# 机器学习的基本步骤
## 建立好预测模型
## 初始化模型参数
## 设计或选择一个Cost Function
Cost Function用来比较训练数据中的期望值和通过预测模型计算出来的值的差。在cost function中可以增加一些惩罚项，让结果更有倾向性。
在许多资料里面, cost function, lost function, error function都是同一个概念。  
在另外一些资料中，lost function倾向于函数表达， cost function倾向于数据集合的计算。
http://image.diku.dk/shark/sphinx_pages/build/html/rest_sources/tutorials/concepts/library_design/losses.html  


## 设计或者选择一个metrics
metrics是用来显示东西

## 设计或选择一个Optimizer
Optimizer主要用来监控

## 喂数据到模型，通过训练模型调整参数
### Optimizer根据Error来调整参数
### 为了更好地监控，通过metrics记录中间状态


# NN使用标准的机器学习基本步骤
NN采用了机器学习的大框架，只是使用了特有的Cost Function和Optimizer而已。
