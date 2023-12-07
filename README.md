# Kaggle项目学习记录
学习资料 https://github.com/Kensuke-Hinata/statistic

------------------------------------------

# 2023/12/4 -- 2023/12/8 （12月第一周）
准备着手完成kaggle新手项目：titanic
项目地址：https://www.kaggle.com/competitions/titanic/
资料地址：https://blog.csdn.net/SpecialLinker/article/details/106793082
## 12.4 -- 12.6
Done:
1. 数据part，保留Pclass,Sex，Age，Sibsp，Parch，Fare，对Age和Fare max-min归一化,用随机森林模型预测null值
2. 模型part， 使用SVM+sigmoid（之前使用过的二分类网络）
3. 结果：训练验证正确率0.85，上传后准确率0.75,top88%，效果很差, 减小网络深度和宽度之后，准确率0.77, top78%
## 12.7 -- 12.8
Done：略读了《特征工程入门与实践》，以下是outline
![image](https://github.com/Wilbur0626/kaggle_notes/blob/main/docs/1.png)
## Plan for next week 
1. 继续学习特征工程；
2. 学习《python数据科学手册》，该书讲述了一些库和函数用于特征工程
   https://github.com/zhixingchou/BooksPDF/blob/master/%E6%95%B0%E6%8D%AE%E7%A7%91%E5%AD%A6/Python%E6%95%B0%E6%8D%AE%E7%A7%91%E5%AD%A6%E6%89%8B%E5%86%8C.pdf
3. 学习过程中对titanic数据集处理并记录阶段性结果
