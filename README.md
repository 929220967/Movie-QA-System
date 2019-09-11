# Movie-QA-System

手把手教你用Python搭建基于知识图谱的电影自动问答系统


这是我Python课程上的一个项目，这个项目是用Python搭建了一个基于知识图谱的电影自动问答系统，并且最后以网页呈现出来。在这里我将给大家讲解一遍整个过程，大家也将学会如何使用图数据库Neo4j、如何用Python搭建自动问答系统、建立一个自己的网站以及把这个问答系统部署到自己的网站上。

这是demo示意图，
![主页图片1](demo/1.png)

![主页图片2](demo/2.png)
 
![输入问题](demo/3.png)
 
![回答问题](demo/4.png)
 

使用的图数据包含5000部电影、300位演员和超过100000条实体间的关系。


整个流程分为以下几个部分：
* 安装Neo4j数据库
* 获取电影数据，并将数据导入到neo4j数据库
* 用Python和机器学习实现电影问答部分
* 用Python Flask将问答系统部署到自己的网站上
* (扩展)添加一个“猜你喜欢”的推荐功能


最初我也是参考https://blog.csdn.net/Appleyk/article/details/80331997 这个博主的博客才写出了这个电影问答系统，不过我所实现的和该博主有几点不同：
* 用Python实现，造福不会java的同学
* 没有使用Spark，简化了搭建流程
* 添加了推荐功能
* 将demo部署在了个人网站上

项目github：https://github.com/ChandlerBang/Movie-QA-System


（上）电影数据的获取与处理

（中）用Python搭建电影问答系统

（下）将问答系统部署到个人网站上

To be continued...



