# 基于GitHub的课程实验管理平台的分析与设计
### 成都大学信息科学与工程学院
|学号|班级|姓名|照片|
|:-------:|:-------------: | :----------:|:---:|
|201610414113|软件(本)16-1|屠鹏|![image](https://github.com/tupengbox/is_analysis/blob/master/myself.png?raw=true)|

## 1. 概述
- 基于GitHub的实验管理平台的作用是在线管理实验成绩的Web应用系统。学生和老师的实验内容均存放在GitHUB
页面上。
- 学生的功能主要有：设置自己的GitHub用户名，修改登录密码，查询自己的实验成绩，选择课程，查询已选课程和退选课程。学生的GitHub用户名是公开的，但成绩不公开。
- 老师的功能主要有：发布课程实验，修改和删除课程实验，批改每个学生的成绩，查看每个学生的成绩。每个实验可有多个评分细项，每个评分项对应各自的评分标准，老师在批改实验的时候，对每个评分项进行评分并输入对应的文字评价。
- 老师和学生都能通过本系统的链接方便地跳转到学生的每个GitHUB实验目录，以便批改实验或者查看实验情况。
- 实验成绩按数字分数计算，每项实验的满分为100分，最低为0分。
- 系统自动计算每个学生的所有实验的平均分即为该学生的实验总成绩。
- 系统设计在界面上和操作上方便老师查询和评阅学生的实验成绩，应该方便学生查询实验成绩。
    
## 2. 系统总体结构

![image](https://github.com/tupengbox/is_analysis/blob/master/test6/Github系统总体结构.png?raw=true)

界面设计参见：https://tupeng.github.io/is_analysis/test6/ui/index.html
    
## 3. 用例图设计 [源码](src/UseCase.puml)

![image](https://github.com/tupengbox/is_analysis/blob/master/test6/Github用例图设计.png?raw=true)

## 4. 类图设计 [源码](src/Class.puml)
![image](https://github.com/tupengbox/is_analysis/blob/master/test6/Github类图设计.png?raw=true)


## 5. 数据库设计
- ### [参见数据库设计](./数据库设计.md)

## 6. 用例及界面详细设计

- ### [“登录”用例](./用例/登录.md),[界面](https://tupeng.github.io/is_analysis/test6/ui/登录.html)
- ### [“学生列表”用例](./用例/学生列表.md),[界面](https://tupengbox.github.io/is_analysis/test6/ui/index.html)
- ### [“评定成绩”用例](./用例/评定成绩.md),[界面](https://tupeng.github.io/is_analysis/test6/ui/评定成绩.html)
- ### [“查看成绩”用例](./用例/查看成绩.md),[界面](https://tupeng.github.io/is_analysis/test6/ui/查看成绩.html)
- ### [“修改密码”用例](./用例/修改密码.md),[界面](https://tupeng.github.io/is_analysis/test6/ui/顶部菜单.html)
- ### [“修改用户信息”用例](./用例/修改用户信息.md),[界面](https://tupeng.github.io/is_analysis/test6/ui/顶部菜单.html)
- ### [“查看用户信息”用例](./用例/查看用户信息.md),[界面](https://tupeng.github.io/is_analysis/test6/ui/顶部菜单.html)
- ### [“登出”用例](./用例/登出.md),[界面](https://tupeng.github.io/is_analysis/test6/ui/顶部菜单.html)

    