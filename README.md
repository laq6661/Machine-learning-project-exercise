# Machine-learning-project-exercise

#1. A simple temperature prediction project.ipynb
 keras+pandas  dataset:https://www.data.jma.go.jp/gmd/risk/obsdl/index.php
The average data of the maximum temperature every two days from 1980 to 2020 are used. The temperature of August 1, 2060 is predicted by linear regression. There are some simple data processing based on pandas.
使用了草津1980年-2020年 每两天的最高气温平均数据，用线性回归预测了2060年8月1日气温。其中有一些简单数据处理基于pandas
难点问题：日语兼容 日期格式数据 双标签下的依次排序 拿出一部分数据处理后放回df

#2.sklearn_week2.ipynb
Use sk_learn to realize logical regression and simply deal with mnist data sets, and output weight heat map dataset:https://www.openml.org/d/554
sk_learn逻辑回归简单处理了mnist数据集，并书输出了权重热图

#3.iris_data_dense_tf2.0.ipynb
The iris data set is processed with tf2.0 functional api and a few simple dense.  96% accuracy, using early stop
用tf2.0函数式api简单几个dense处理了iris数据集，96%精度，采用了早停
dataset:https://www.openml.org/d/61

#4 kaggle_race_logist.ipynb
tf2.0 和一些浮点数和类别特征处理 ， embedding和简单logist实现，数据集因为是kaggle比赛的不能提供。但代码精简漂亮可参考

#5 deepfm.ipynb
kaggle race的deepfm版本

#6 iris_GaussianNB.ipynb
iris数据集用sklearn的高斯贝叶斯包做的 93%准确率

#7 mnist784_linear.ipynb
mnist数据集用cnn进行了简单处理

#8 ga_knapsack_problem.ipynb
用遗传算法解决背包问题，使用的是单点交叉和突然变异方法
