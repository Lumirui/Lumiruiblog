## 1.概念

MySQL 是一种**关系型数据库管理系统**（RDBMS），由瑞典 MySQL AB 公司开发，现属于 Oracle 旗下。它是全球最流行的开源数据库之一，被广泛用于 Web 应用程序和服务器端开发。MySQL 使用 SQL 语言来访问和管理数据库，是最常用的标准化语言。

以下是列表:



## 2.安装

安装地址:https://dev.mysql.com/downloads/mysql/,选择Archives,版本号选择8.2.0,选择你的系统,点击download下载,下载完成后打开安装包,点击next,选择accpet,点击next,自定义安装位置默认选择typical也行,next,finish

## 3.配置

保持不动,next,密码自定义,next,next,next,next

不用create,next,extract,finish

## 4.配置环境变量

此电脑-属性-环境变量,在环境变量找到系统-path,新建,复制以下地址

```
C:\Program Files\MySQL\MySQL Server 8.2\bin
```

## 5.验证

打开cmd,输入mysql --version