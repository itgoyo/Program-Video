课程名称:  JAVA Spring Cloud微服务项目实战 SpringBoot 2.x +SpringCloud 微服务实现方案


课程简介:

微服务架构已是当下最热门的话题，许多公司都在从传统架构系统向微服务转化。本门课程以点餐业务为例，使用Spring Boot2.x 配合SpringCloud核心组件，剖析微服务原理。并利用Rancher+Docker实现容器编排，SpringCloud Sleuth集成Zipkin实现分布式链路追踪，带你领略最潮的微服务实现方案

```
----------------------课程目录------------------------------

第1章 课程介绍
课程导学和学习建议

1-1 SpringCloud导学
1-2 获取源码说明
1-3 提问建议
1-4 点餐项目演示说明
第2章 微服务介绍
什么是微服务, 单体架构优缺点, 常见的几种架构模式。

2-1 微服务和其他常见架构
2-2 从一个极简的微服务架构开始
第3章 服务注册与发现
介绍微服务中的服务注册与发现机制，Spring Cloud Eureka组件的使用以及如何保证高可用

3-1 Spring Cloud Eureka
3-2 Eureka Server
3-3 Eureka Client的使用
3-4 Eureka的高可用
3-5 Eureka总结.mp4
3-6 分布式下服务注册的地位和原理
第4章 服务拆分
以商品服务和订单服务为例介绍微服务拆分中的业务功能拆分和数据拆分的注意点以及将项目模块进行多模块改造

4-1 微服务拆分的起点
4-2 康威定律和微服务
4-3 点餐业务服务拆分分析
4-4 商品服务API和SQL介绍
4-5 商品服务编码(上)
4-6 商品服务编码(中)
4-7 商品服务编码(下)
4-8 订单服务API和SQL介绍
4-9 订单服务dao
4-10 订单服务service
4-11 订单服务controller
4-12 再看“拆数据”
第5章 应用通信
比较HTTP REST 和 REST，同步和异步, 介绍Spirng Cloud 采用的两种HTTP方式，重点介绍Feign. 实例演示下单流程. 引出异步通信的思考.

5-1 HTTP vs RPC
5-2 RestTemplate的三种使用方式
5-3 负载均衡器：Ribbion
5-4 追踪源码自定义负载均衡策略
5-5 Feign的使用
5-6 获取商品列表(Feign)
5-7 扣库存(Feign)
5-8 整合接口打通下单流程(Feign)
5-9 项目改造成多模块
5-10 同步or异步
5-11 RabbitMQ的安装
5-12 微服务，Docker和DevOps
第6章 统一配置中心
介绍Spring Cloud Config组件搭配Spring Cloud Bus, 实现配置自动更新, 集成WebHook

6-1 统一配置中心概述
6-2 Config Server
6-3 Config Client
6-4 Spring Cloud Bus自动更新配置理论
6-5 Spring Cloud Bus实操.mp4
6-6 集成WebHooks实现动态更新
6-7 Spring Cloud Bus相关的坑和启示
第7章 消息和异步
RabbitMQ，Spring Cloud Stream组件介绍及使用, 异步通信实例演示和思考

7-1 异步和消息
7-2 RabbitMQ的基本使用（上）
7-3 RabbitMQ的基本使用（下）
7-4 Spring Cloud Stream的使用（上）
7-5 Spring Cloud Stream的使用（下）
7-6 商品和订单服务中使用MQ(上)
7-7 商品和订单服务中使用MQ(中)
7-8 商品和订单服务中使用MQ(下)
7-9 异步扣库存分析（上）
7-10 异步扣库存分析（下）
第8章 服务网关
探讨微服务架构下的服务网关，介绍Spring Cloud Zuul的使用, 路由转发, Cookie处理, 动态路由等Zuul路由相关的功能，也探讨了Zuul的高可用

8-1 服务网关和Zuul
8-2 Zuul：路由转发，排除和自定义
8-3 Zuul：Cookie和动态路由
8-4 Zuul：路由和高可用小结
第9章 Zuul综合使用
围绕过滤器，选取限流，跨域等典型场景，综合使用Zuul，集成用户服务

9-1 Zuul：Pre和Post过滤器
9-2 Zuul：限流
9-3 Zuul鉴权和添加用户服务
9-4 模拟买家卖家登录功能实现（上）
9-5 模拟买家卖家登录功能实现（下）
9-6 完结订单接口开发
9-7 完成权限校验（上）
9-8 完成权限校验（下）
9-9 Zuul：跨域
第10章 服务容错
探讨熔断机制，Spring Cloud Hystrix的使用, Feign+Hystrix服务降级.

10-1 服务容错和Hystrix
10-2 触发降级
10-3 超时设置
10-4 探讨断路器模式
10-5 使用配置项
10-6 feign-hystrix的使用
10-7 hystrix-dashboard
10-8 Zuul：超时配置
第11章 服务跟踪
Spring Cloud Sleuth的使用, Sleuth搭配Zipkin, 直观获取跟踪信息和分析请求链路明细.

11-1 服务追踪（上）
11-2 服务追踪（下）
第12章 容器部署
使用Docker容器+Rancher容器管理平台部署微服务, 资源弹性分配, 容器编排与调度.

12-1 运行第一个docker容器
12-2 rancher安装
12-3 部署eureka和config
12-4 构建eureka高可用服务
12-5 构建product服务
12-6 构建order服务
12-7 构建api-gateway
```
下载地址：

链接: https://pan.baidu.com/s/12LuVnQRkc5-_aEW5GUHJiA 密码: fbhf