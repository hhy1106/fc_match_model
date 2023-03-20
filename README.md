# fc_match_model
# **_research ideas and analysis processes_**
### **1.数据预处理**
### **1.缺失情况分析**

数值为0/空值的情况需要分开讨论，且关注缺失数据是否为真实缺失

### **2.异常情况分析**

对出现“--”的情况进行分析，且关注该符号的实际意义以及占比情况

### 3.重复情况分析

对于重复数据进行删除

# **_2.用户整体印象_**
### 1.用户分布分析

根据海内外、省份分析、乡镇分析入手,找到核心差异点所在

### 2.用户活跃度分析

细分整体情况与工作日差异

### 3.用户流失情况分析

细分整体情况与用户流失风险，流失定义、流失率、流失风险

### 4.线上管理决策建议

宣传、活跃度、流失为切口进行分析

# **_3.用户课程选择分析_**

### 1.用户参与课程情况

现有课程选择分析与受欢迎度计算

### 2.用户课程推荐——基于协同过滤算法

基于协同过滤算法进行重点课程推荐

### 3.收费课程与用户学习进度相关分析

### 4.线上课程综合推荐策略制定

# **_4.所选数据_**
### 表1 user.csv：
user_id 用户id

registration_time 注册时间

recently_logged 最近访问时间

learn_time 学习时间（分）

number_of_classes_join 加入班级数

number_of_classes_out 退出班级数

school 用户所属学校

### 表2 study_information.csv
user_id 用户 id

course_id 课程 id

course_join_time 加入课程的时间

learn_process 学习进度

price 课程单价

### 表3 login.csv 
字段名 描述

user_id 

login_time 登录时间

login_place 登录地址

