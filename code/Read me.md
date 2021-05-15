# Read me:

## 运行说明：



1： 数据清洗 ：

运行环境：Spyder 

在 conda  的Spyder 中运 行clean.ipynb 文件 即可  ，

notes ： 但是数据清洗后的准确率更低 ， 所以建议不进行这一步 



2： 特征提取： 

运行环境： jupyter 

1: 特征提取两个训练集： 运行fea_getTrain.ipynb  文件 进行特征提取

2：特征提取一个测试题： 运行  featuregetForTest.ipynb文件  

在jupyter 中运行 文件即可 ， 但是要注意同时处理 训练集  和测试集 。

说明 ： 在模型训练中 ，我们用的模型是[`sklearn.model_selection`](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.model_selection)

用的是官方模型 ， 直接拿来用即可。

3：模型训练： 

运行环境： jupyter:

在jupyter 中运行 train.ipynb   文件即可 ，

注意把训练出来的result.csv 文件 的第一行修改为label 列名。  

