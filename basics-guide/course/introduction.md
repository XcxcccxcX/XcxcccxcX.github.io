# 介绍

## 项目简介
JetLinks 是一个物联网基础平台,用于快速建立物联网相关业务系统.

- 集成了各种常见的网络协议(HTTP,TCP,UDP,CoAP)等,并对其进行封装,
实现统一管理,监控,在线调试,在线启动,停止,更新等功能.大大降低网络编程的复杂度.

- 多消息协议支持,可在线配置消息解析规则,将自定义的消息解析为平台统一的消息格式.

- 统一的设备操作API,屏蔽各个厂家`不同协议`不同设备的差异,支持`跨服务`,同步(RRpc),异步的设备消息收发.

- 可视化拖拽规则引擎设计器,灵活可拓展的多种规则节点支持,可通过规则引擎在线动态配置数据,业务处理逻辑.

- 灵活的多维度权限控制,可支持`列`,`行`级别数据权限控制.

官方QQ群: `2021514`

## 技术选型

1. [Spring Boot 2.2.x](https://spring.io/projects/spring-boot)
2. [Spring WebFlux](https://spring.io/) 响应式Web支持
3. [R2DBC](https://r2dbc.io/) 响应式关系型数据库驱动
4. [Project Reactor](https://projectreactor.io/) 响应式编程框架
4. [Netty](https://netty.io/),[Vert.x](https://vertx.io/) 高性能网络编程框架
5. [ElasticSearch](https://www.elastic.co/cn/products/enterprise-search) 全文检索，日志，时序数据存储
6. [PostgreSQL](https://www.postgresql.org) 业务功能数据管理
7. [hsweb framework 4](https://github.com/hs-web) 业务功能基础框架
