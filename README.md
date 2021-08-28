# SSLAB
<font color=#999AAA >为了解决高校贫困生认定问题，考虑到传统认定流程存在的弊端，提出从消费数据层面和贫困信息对贫困生进行半监督分类认定。</font>

<hr style=" border:solid; width:100px; height:1px;" color=#000000 size=1">

<font color=#999AAA >提示：以下是本篇文章提供的数据集，代码和结果

# 一、data
1. clean_data.csv：经清洗，数据预处理，特征构造和选择得到的数据集，此数据集包含13309条数据，18个属性特征

数据信息：
feature     | Type
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

# 二、result
实验结果
