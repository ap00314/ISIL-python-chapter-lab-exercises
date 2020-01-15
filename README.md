# ISIL-python-chapter-lab-exercises
#### 该项目主要为ISIL的python实现，包括章节、实验和习题。
&emsp;&emsp;ISIL全称《An Introduction to Statistical Learning with Applications in R》中文译名《统计学习导论 基于R应用》，是著名的ESL《Element of statisical learining》的R语言简明版，弱化了数学推导过程，非常适合统计学（及机器学习）的入门。主要讲述了一些统计学的基本概念，大部分章节讲述监督学习-线性回归/Logistic模型/LDA/QDA/KNN/样条/GAM/决策树/Bagging/Random Forests/Boosting/SVM，以及监督学习相关的交叉验证、模型选择及正则化方法，非监督学习介绍了PCA/K-Means/系统聚类法等。

&emsp;&emsp;本人是机器学习及PYTHON的初学者（之前只有单片机开发的经验），考虑到原书的实验及网上的习题答案均为R语言实现，通过改写为PYTHON实现，掌握统计学（及机器学习）的入门知识的同时，熟悉PYTHON的一些机器学习相关库（主要为numpy/pandas/matplotlib/statsmodels/sklearn/patsy）。该项目对大部分章节、实验和习题均进行了PYTHON实现，但因本人代码能力及经验问题，一些代码并不完善，主要为1.一部分程序如子集选择通过python自编函数实现，与R语言运行速率相比，相差甚远，网上也未找到好的库；2.包括光滑样条/局部回归/PLS的解释方差等均未能实现。同时在一些TREE和SVM的图形实现参考了一些GITHUB上已有代码，对以下表示感谢，以下库的代码写的更为专业，只是在该书的实现上只包含了部分章节且无习题，未整体实现：

https://github.com/JWarmenhoven/ISLR-python

https://github.com/hyunblee/ISLR-with-Python

