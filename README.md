# SSLAB
<font color=#999AAA >为了解决高校贫困生认定问题，考虑到传统认定流程存在的弊端，提出从消费数据层面对贫困生进行分类认定。</font>

<hr style=" border:solid; width:100px; height:1px;" color=#000000 size=1">

<font color=#999AAA >提示：以下是本篇文章提供的数据集，代码和结果

# 一、data
1. clean_data.csv：经清洗，数据预处理，特征构造和选择得到的数据集

数据信息：
特征     | Type
-------- | -----
per_money  | float
sumAll| float
sum_3  | float
sum_4  | float
sum_5| float
sum_6  | float
sum_deposit  | float
sum_supermarket| float
sum_restaurant  | float
count_deposit  | int
count_supermarket| int
count_restaurant  | int
max_deposit  | float
max_supermarket| float
max_restaurant | float
mean_deposit  | float
mean_supermarket| float
mean_restaurant | float
2. data850.csv:标记的850条数据
3. data1500.csv:标记的1500条数据

# 二、code
1. self_training.py：常规自训练算法
2. tri_training.py：tri_training算法
3. SSL_training.py：SSLAB算法
4. test.py：F1和AUC测试代码
5. test1.py：accuracy测试代码
# 三、result
实验结果
