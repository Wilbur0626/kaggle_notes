# Kaggle项目学习记录
学习资料 https://github.com/Kensuke-Hinata/statistic

------------------------------------------

# 2023/12/4 -- 2023/12/8 （12月第一周）
准备着手完成kaggle新手项目：titanic

项目地址：https://www.kaggle.com/competitions/titanic/

## 12.4 -- 12.6

Done:

1. 数据part，保留Pclass,Sex，Age，Sibsp，Parch，Fare，对Age和Fare max-min归一化,用随机森林模型预测null值
2. 模型part， 使用SVM+sigmoid（之前使用过的二分类网络）
3. 结果：训练验证正确率0.85，但上传后结果是0.75,top88%，效果很差, 然后减小网络深度和宽度，top78%

Plan:

1. 根据网络资料重新梳理数据part和多模型建立

资料地址：https://blog.csdn.net/SpecialLinker/article/details/106793082

