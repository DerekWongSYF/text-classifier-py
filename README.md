# text-classifier-py
python实现文本分类的常用方法，目前实现了两种ML算法，朴素贝叶斯和SVM，都是业界较常用的方法。

## 朴素贝叶斯

代码使用参考子文件夹下README文件

## SVM

代码使用参考子文件夹下README文件

## 实验数据

百度网盘：链接: https://pan.baidu.com/s/1nvz47Jb 密码: hxda


## 实验结果

两种方法都只是使用了chi作为特征选择方法，并且选择了词汇集的40%作为特征词。训练数据为5.6w条新闻，测试数据为3.78w条，准确率如下：
NB：59.79%
SVM：57.46%

训练时间没有明确测量，但是SVM快很多。

准确率稍低一方面是因为没有很好的调参（目前我的主要目的是实现算法从而加深算法的理解），二是因为训练数据是真实的新闻数据，新闻质量进一步提高的话也可以提高准确率。

## 进一步工作

最近正在学习深度学习，也看到很多使用CNN，DNN的文本分类方法，可以多做一些研究。
