﻿
# Cicada 框架整体介绍

首先得以肯定的是，这是一个很容易上手开发的系统框架，使开发人员不需要过多地去关注系统相对底层的一些开发，
让整个开发的注意点都落实到业务实现上。同时这样也保证了系统底层架构的统一性，可维护性，程序的可拓展性等特点。

### 1、整个系统框架封装打包了MVC,WebApi,MvcAndApi,WCF,UnitTest这几个常用的项目类型，具体介绍可点击查看相对应文档

  * 1.1 [点击查看WebMVC类型项目](HelpMd/MVC.md)
  * 1.2 [点击查看WebApi类型项目](HelpMd/WebApi.md) 
  * 1.3 [点击查看MvcAndApi类型项目](HelpMd/MvcApi.md) 
  * 1.4 [点击查看WCF类型项目](HelpMd/WCF.md) 
  * 1.5 [点击查看UnitTest单元测试项目](HelpMd/UnitTest.md)
  
### 2、系统框架有关Window服务打包的操作,系统缓存打包的使用,对于微服务架构的如何使用，请具体参考下面：
  * 2.1 [点击查看Window服务如何打包](HelpMd/WindowService.md)
  * 2.2 [点击查看Cicada框架缓存如何使用](HelpMd/Cache.md)
  * 2.3 [点击查看RPC如何配置使用](HelpMd/RPC.md)
  * 2.3 [点击查看RabbitMQ如何配置使用](HelpMd/RabbitMQ.md)
  
### 3、系统框架有关授权认证和用户信息获取的功能具体参考下面：
* 3.1 直接开放WebApi给移动端的接口有哪些？[点击查看](http://172.18.108.118/swagger/ui/index#/)
* 3.2 [点击查看授权认证如何在项目中使用](HelpMd/Authorization.md)
* 3.3 [点击查看如何通过RPC调度数据以及通过WebApi调度数据和RPC调度数据的标准是什么？](HelpMd/LYDriver.md)

  
### 4、功能模块开发过程中，一些推荐的示例，具体请参考下面（可以一块探讨）：
  * 4.1、[点击查看EntityFrameWork语句调优的示例](HelpMd/OptimalSql.md)
  * 4.2、[在线API文档自动生成如何配置](HelpMd/Swagger.md)
  
       ![uniform](/images/uniform.ico)
       
### 5、文档的相关介绍
  * 5.1、有关MySQL数据库开发规范文件请下载[下载](https://github.com/liu-rui/Cicada/blob/master/Doc)

 注：项目程序都在Samples这个文件夹里；Tools文件夹里面是框架使用到的一些软件；一些Doc类型的文档都在Doc这个文件夹里。
 



