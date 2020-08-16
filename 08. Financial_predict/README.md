## Action1	信用卡违约率检测:

https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset

对信用卡使用数据进行建模，预测用户是否下个月产生违约 => 分类问题

机器学习算法有很多，比如SVM、决策树、随机森林和KNN => 该使用哪个模型

可以使用GridSearchCV工具，找到每个分类器的最优参数和最优分数，最终找到最适合数据集的分类器和此分类器的参数"

## Action2	"信用卡欺诈分析：

数据集：2013年9月份两天时间内的信用卡交易数据
284807笔交易，492笔欺诈行为
https://www.kaggle.com/mlg-ulb/creditcardfraud

数据样本包括了28个特征V1，V2，……V28，以及交易时间Time和交易金额Amount

因为数据隐私，28个特征值是通过PCA变换得到的结果。

需要预测 每笔交易的分类Class，该笔交易是否为欺诈

Class=0为正常（非欺诈），Class=1代表欺诈"
