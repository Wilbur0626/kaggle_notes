# Study Recording

## Goal: 
  Skill in data preprocessing & basic-task model buiding 

## Method: 
  Study from practicing projects on kaggle 

## Better late than never!!

------------------------------------------

# 2023/12/4 -- 2023/12/8 （12月第一周）
准备着手完成kaggle新手项目：titanic
项目地址：https://www.kaggle.com/competitions/titanic

资料地址：https://blog.csdn.net/SpecialLinker/article/details/106793082

Done:
1. 数据part，保留Pclass,Sex，Age，Sibsp，Parch，Fare，对Age和Fare max-min归一化,用随机森林模型预测null值
2. 模型part， 使用mlp+sigmoid（之前使用过的二分类网络）
3. 结果：训练验证正确率0.85，上传后准确率0.75,top88%，效果很差, 减小网络深度和宽度之后，准确率0.77, top78%
4. 略读了《特征工程入门与实践》，总结了review:
![image](https://github.com/Wilbur0626/kaggle_notes/blob/main/docs/1.png)

Plan for next week 

1. 继续学习特征工程；
2. 学习《python数据科学手册》，该书讲述了一些库和函数用于特征工程
  https://github.com/wangyingsm/Python-Data-Science-Handbook 
3. 学习过程中对titanic数据集处理并记录阶段性结果

------------------------------------------
# 2023/12/11 -- 2023/12/15 （12月第二周）
Done:
1. 数据part，经过变量分析，缺失值处理，变量转换过程后继续使用MLP+Softmax输出概率分类，又增加10个百分点，top68%。

Remarks:
1. 这周主要在忙工作上的事，hold了四天plan。
2. during工作，学习了Computational Image，深深感受到现在的网络trick算法迭代频繁，需要学习跟进的内容也很多。


