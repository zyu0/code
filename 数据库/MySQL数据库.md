# MySQL数据库

## 概念

数据库就是以一定格式进行组织的数据的集合。通俗来看数据库就是用户计算机上一些具有特殊格式的数据文件的集合。

SQL：结构化查询语言(Structured Query Language)简称SQL，是一种特殊目的的编程语言，是一种数据库查询和[程序设计语言](https://baike.baidu.com/item/程序设计语言/2317999)，用于存取数据以及查询、更新和管理[关系数据库系统](https://baike.baidu.com/item/关系数据库系统)。

![zyu0-2020-11-04_11-18-50](assets/zyu0-2020-11-04_11-18-50.png)

**作用：**

数据库就是用来存储数据的。

> 抛出问题：既然数据库本身就是一种文件，那用户可以不使用数据库而使用普通文件来进行数据的存储吗?从理论上是可以的。但是相比于普通文件，数据库有以下特点：

**优势：**

- 持久化存储
- 读写速度极高
- 保证数据的有效性
- 对程序支持性非常好，容易扩展

**根据特点分类：关系型数据库和非关系型数据库**

**关系数据库**，是指采用了==关系模型==来组织数据的数据库，简单来说，关系模型指的就是二维表格模型，一个关系型数据库就是由==二维表==及其之间关系的联系所组成的一个数组组织

> SQLite多用于移动端，不用联网

> MySQL采用了双授权政策，它分为社区版和商业版，由于其体积小、速度快、总体使用成本低，尤其是开源，一般中小型网站的开发都选择MySQL作为网站数据库。

> Oracle

> Microsoft SQL Server

非关系型数据库

非关系型数据库，又被称为==NoSQL==（Not Only SQL)，意为不仅仅是SQL，对NoSQL最普漏的定义是“非关联型的”，强调==Key-Value==的方式存储。

> MongoDB
>
> Redis

[[数据库管理系统]]