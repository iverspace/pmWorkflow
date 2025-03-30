<p align="center"><img src= "https://cdn.tobebetterjavaer.com/stutymore/pmhub_%E7%AE%80%E4%BB%8B%E7%89%88.png" alt="MaxKB" width="300" /></p>
<h3 align="center">PmHub，一个基于 SpringCloud & LLM 的智能项目管理系统</h3>
<p align="center">
  <a href="https://opensource.org/license/MIT"><img src="https://img.shields.io/github/license/laigeoffer/pmhub?color=rgb(25%2C%20121%2C%20255)" alt="The MIT License"></a>
  <a href=""><img src="https://img.shields.io/github/forks/laigeoffer/pmhub?color=green" alt="Forks"></a>
  <a href="https://laigeoffer.cn/"><img src="https://img.shields.io/badge/PmHub-%E5%AE%98%E7%BD%91-green" alt="Official"></a>
  <a href="https://github.com/laigeoffer/pmhub"><img src="https://img.shields.io/github/stars/laigeoffer/pmhub?style=flat-square&color=rgb(25%2C%20121%2C%20255)" alt="Stars"></a>    
  <a href="https://pmhub.laigeoffer.cn/"><img src="https://img.shields.io/badge/PmHub-%E4%BD%93%E9%AA%8C%E5%9C%B0%E5%9D%80-blue" alt="Experience"></a>  
</p>

<hr/>
PmWorkflow 是一套基于 SpringCloud & LLM 的微服务智能项目管理系统，这个项目旨在帮助小伙伴们快速掌握微服务/分布式项目的架构设计和开发流程，如果想在校招或者社招中拿到一个满意的 offer，PmHub 将是一个非常 nice 的选择。

## 项目亮点

- **热门技术**：采用时下企业最热门的技术框架，如 SpringCloud-Gateway、Nacos、Sentinel 等，主打一个硬核，与真实的企业项目接轨。
- **单体与微服务**：提供单体和微服务两个版本，完美照顾零基础和需要进阶的同学，带大家体验从单体到微服务架构的改造全过程，并深入理解两种架构的优缺点。
- **硬核面试题**：我们将结合付费球友的实际面试体验，为大家提供可以真正吊打面试官的真是面试场景和题目，并提供 1v1 的简历修改服务，主打一个投了就有、面了就拿 offer 的快乐体感。
- **代码质量**：由蚂蚁金服工作过的技术专家苍何亲自下场，严格遵循代码规范和最佳实践，帮大家养成优雅的代码编写习惯。
- **持续集成**：提供持续集成和持续部署的完整配置，带你从 0-1 用 Docker 上线 生产环境级别的真实项目。
- **产品设计**：[提供完整的产品设计文档](https://lanhuapp.com/link/#/invite?sid=qxZji4oa)，包括产品需求、产品架构、产品原型等，这是别的项目不曾给你的，但工作后又不可或缺的能力。
- **企业工作流**：提供企业级的工作流系统，代码完全开源，你可以在此基础上进行二开，为公司节省巨额的研发成本，从而升职加薪。


## 一、项目简介

PmWorkflow 包括认证、流程、项目管理、用户、网关等服务。包含了 Redis 缓存、RocketMQ 消息队列、Docker 容器化、Jenkins 自动化部署、Spring Security 安全框架、Nacos 服务注册和发现、Sentinel 熔断限流、Seata 分布式事务、Spring Boot Actuator 服务监控、SkyWalking 链路追踪、OpenFeign 服务调用，Vue3 前端框架等互联网开发中需要用到的主流技术栈，可以帮助同学们快速掌握微服务/分布式项目的核心知识点。

并且同时 PmWorkflow 也是一套企业工作流的开发框架，您可以根据自身需求，快速定制出适合自己公司的企业工作流系统。



## 二、项目详情
### 2.1 技术架构

下面这张系统架构图可以帮助大家快速了解 PmWorkflow 项目的系统架构，从前端到网关、从服务应用到基础服务组件、从存储技术到运维部署，可以说是一目了然。

![pmWorkflow-系统架构图](https://cdn.tobebetterjavaer.com/stutymore/01.什么是PmHub-20240708113736.png)

下面这张架构选型图可以帮助大家快速了解 PmWorkflow 项目的技术选型，以及在[官方手册](https://laigeoffer.cn/pmhub/tech-architecture/)中会更详细的说明我们为什么选择该技术，毕竟授人以鱼不如授人以渔嘛。

![pmWorkflow-架构选型](https://cdn.tobebetterjavaer.com/stutymore/PmHub%E6%9E%B6%E6%9E%84%E9%80%89%E5%9E%8B.png)

下面这张技术架构图可以帮助大家快速了解 PmWorkflow 项目的技术架构，以及各个模块之间的交互关系。

![pmWorkflow-技术架构图](https://cdn.tobebetterjavaer.com/stutymore/01.什么是PmHub-20240702103552.png)

优质的项目，离不开一张清晰的鸟瞰图（😄）。


### 2.2 开发环境

|      工具       | 版本        | 下载                                                                                                                     |
|:-------------:|:----------|------------------------------------------------------------------------------------------------------------------------|
|      jdk      | 1.8+      | [https://www.oracle.com/java/technologies/downloads/#java8](https://www.oracle.com/java/technologies/downloads/#java8) |
|     maven     | 3.4+      | [https://maven.apache.org/](https://maven.apache.org/)                                                                 |
|     mysql     | 5.7+/8.0+ | [https://www.mysql.com/downloads/](https://www.mysql.com/downloads/)                                                   |
|     redis     | 5.0+      | [https://redis.io/download/](https://redis.io/download/)                                                               |
| elasticsearch | 8.0.0+    | [https://www.elastic.co/cn/downloads/elasticsearch](https://www.elastic.co/cn/downloads/elasticsearch)                 |
|     nginx     | 1.10+     | [https://nginx.org/en/download.html](https://nginx.org/en/download.html)                                               |
|   rocketmq    | 5.0.4+    | [https://www.rabbitmq.com/news.html](https://www.rabbitmq.com/news.html)                                               |
|    ali-oss    | 3.15.1    | [https://help.aliyun.com/document_detail/31946.html](https://help.aliyun.com/document_detail/31946.html)               |
|      git      | 2.34.1    | [http://github.com/](http://github.com/)                                                                               |
|    docker     | 4.10.0+   | [https://docs.docker.com/desktop/](https://docs.docker.com/desktop/)                                                   |
|    freessl    | https证书   | [https://freessl.cn/](https://freessl.cn/)                                                                             |


## 三、内置功能
> 内置功能我们使用了若依的框架，为什么要用若依，一来我们觉得基础的后台功能没有必要再重复造轮子，我们需要节省时间花力气在项目核心业务上，二来我们希望站在巨人的肩膀上，若依是后台系统中很优秀的框架，我们基于其做的二次开发，相信也能再创辉煌！

1.  用户管理：用户是系统操作者，该功能主要完成系统用户配置。
2.  部门管理：配置系统组织机构（公司、部门、小组），树结构展现支持数据权限。
3.  岗位管理：配置系统用户所属担任职务。
4.  菜单管理：配置系统菜单，操作权限，按钮权限标识等。
5.  角色管理：角色菜单权限分配、设置角色按机构进行数据范围权限划分。
6.  字典管理：对系统中经常使用的一些较为固定的数据进行维护。
7.  参数管理：对系统动态配置常用参数。
8.  通知公告：系统通知公告信息发布维护。
9.  操作日志：系统正常操作日志记录和查询；系统异常信息日志记录和查询。
10. 登录日志：系统登录日志记录查询包含登录异常。
11. 在线用户：当前系统中活跃用户状态监控。
12. 定时任务：在线（添加、修改、删除)任务调度包含执行结果日志。
13. 代码生成：前后端代码的生成（java、html、xml、sql）支持CRUD下载 。
14. 系统接口：根据业务代码自动生成相关的api接口文档。
15. 服务监控：监视当前系统CPU、内存、磁盘、堆栈等相关信息。
16. 缓存监控：对系统的缓存信息查询，命令统计等。
17. 在线构建器：拖动表单元素生成相应的HTML代码。
18. 连接池监视：监视当前系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈。



## 十三、许可证

[MIT License (MIT)](https://opensource.org/licenses/MIT)<hr/>
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

Copyright (c) 2023-2024 PmWorkflow


