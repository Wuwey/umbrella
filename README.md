# umbrella
This is a project for code2things course.

# TEAM NO._______5_____
# TEAM LEADER: 
(徐东辉，2018115180)
# TEAM PARTNER:.
1.(邹海洋，2018115184）
2.(金宇航，2014112908)

# The Background Story
设计背景：
有时候出门前看了天气预报，有雨，但由于种种原因，在出门的时候又忘记了带雨伞，因而被雨淋。

# Project Description
产品以及功用：
我们打算做一个带有灯的雨伞，通过WIFI获取天气信息，如果今天将要下雨，那么它会发光，将这把雨伞放在门口，看见发光的雨伞便不会忘记拿雨伞了。
硬件以及软件支持：
硬件部分：WIFI模块，LED灯。
软件处理思想：通过WIFI模块获取天气从而使LED灯亮。

# How to Make it?
产品设计：
1）LED灯穿在伞把上，将单片机焊接在伞把上，伞可选择透明伞，使得效果明显；
2）根据下雨的概率高低，用相应颜色的灯光（颜色越红下雨的概率越高）或者闪灯的频率（频率越高概率越高）提示；
# Executable Plan (Deadline of each part)
时间安排：
10周 确定大体材料，框架；
11周-15周 着手制作；
16周 外形修剪。

# 开发日志

# 第十三周：
## 关键词/字：ESP8266、Arduino、API、关键字比对……
    确定了天气获取的方法，即通过ESP8266+Arduino的组合，利用API从“心知天气”（https://www.seniverse.com/） ，获取特定城市（以成都为例）的天气，温度等。通过将获取的天气信息的关键字，编程实现降水概率的可视化。
## 待办事项：
    伞柄的结构设计、单片机的安放位置以及防水结构、能否用手机实现互联、防丢模式（拟开发）、电源、可视化方式

# 第十四周：
# 关键词/字：3D建模、LED、if条件句……
    利用3D建模确定了几种伞柄结构，即单片机的安装位置通过顶部密封的设计有效地实现了防水功能、伞柄直径约与一拳相当，方便抓握；将之前的关键字比对用if语句转换为相应的LED等颜色以起到提醒作用。尝试使用手机利用Tcp调试软件实现开关功能（未成功）。
# 外形1：猫爪
![Image of 猫爪](https://github.com/Wuwey/umbrella/blob/master/%E7%8C%AB%E7%88%AA.png)
# 外形2：竖条形
![Image of 竖条灯](https://github.com/Wuwey/umbrella/blob/master/%E7%AB%96%E6%9D%A1%E7%81%AF.png)
# 内部结构
其中红色部分为单片机的放置位置，内部其余位置用于走线以及电池；
![Image of 内部结构](https://github.com/Wuwey/umbrella/blob/master/%E5%86%85%E9%83%A8%E7%BB%93%E6%9E%84.png)
# 全部设计总览
白色部分为灯的位置
![Image of 全部](https://github.com/Wuwey/umbrella/blob/master/%E5%85%A8%E9%83%A8.png)
# 电源
![Image of 电源](https://github.com/Wuwey/umbrella/blob/master/%E7%94%B5%E6%BA%90.jpg)
# 待办：
    电池、手机交互、防丢模式。
# 第十五周：
# 关键词/字：3D打印……
    优化代码，取消了使用手机操控的计划，改为以断开连接为触发的延时程序。选择设计好的伞柄，使用3D打印机制作外壳，并且完成安装、调试工作。
