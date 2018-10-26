# shuangyun
#姓名：孙双运，学号：Y45180273 专业：计算机技术
#问题描述：
数据文件train.csv和test.csv包含多名乘客的信息。每名乘客有如下信息：

    PassengerId : 乘客的唯一ID
    Survived : 乘客最终是否存活(0 = No, 1 = Yes, 仅train.csv中包含此信息)
    Pclass : 乘客的船票的等级(1 = 1st, 2 = 2nd, 3 = 3rd)
    Name : 乘客名字
    Sex : 乘客性别(male, female)
    Age : 乘客年龄(Year)
    Sibsp ：船上兄弟姐妹/配偶的人数
    Parch : 船上父母/儿女的人数
    Ticket : 船票号码
    Fare : 船票价格
    Cabin : 船舱号
    Embarked : 出发港口(C = Cherbourg, Q = Queenstown, S = Southampton)

训练数据集train.csv包含12列，分别对应上述信息。测试数据集test.csv包含11列，不包含Survival信息。
输出格式

您需要提交一个submission.csv文件，文件应采用gender_submission.csv的格式，具体如下：对于测试集中的每位乘客，输出一行，其中包含PassengerId和预测这个乘客是否会存活的结果。 例如，如果您预测第一个乘客存活，第二个乘客不会存活，第三个乘客不会存活，那么您的提交文件将如下所示：

PassengerId,Survived
1,1
2,0
3,0 
(415 more lines)
