## Use neural network to predict the survival probability of passengers on Titanic
--Ji Changtian   `twitter:tony16378348`
<br><br>
#### Please check the detail in Titanic_In_Keras.ipynb
<br><br>
### -----------------------------------------------------------------------------------------------------------
<br><br>
## 使用神经网络预测铁达尼号乘客生还几率
<br>
### 赛事简介
基于给定的两个数据集（train.csv，test.csv），通过机器学习对乘客生还几率进行预测。满分为1分。

### 基本思路
##### 1、发现数据关系（可用matplotlib）
##### 2、特征工程（挖掘尽可能多的信息）
##### 3、建立网络
##### 4、训练网络
##### 5、进行预测
###
### 源码
详见Titanic_In_Keras.ipynb
###
### 本轮小结
建立网络并简单训练后，得分超越0.85，明显超越传统机器学习的得分（约0.7）。

###
### 下一步改进计划：
##### 1、继续深化特征工程，从姓名中提取称呼作身份识别。
##### 2、使用交叉验证，便于得到最优模型。
##### 3、使用赛事官方提供的测试数据集，继续预测。
