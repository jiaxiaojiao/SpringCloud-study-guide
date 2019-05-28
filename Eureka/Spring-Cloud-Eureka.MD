# Spring Cloud Eureka
> Spring Cloud Eureka 是 Spring Cloud Netflix 微服务套件中的一部分，它基于Netflix Eureka 做了二次封装，主要负责完成微服务架构中的服务治理功能（服务注册与发现）。

## 作用
实现服务治理（服务注册与发现）

## 组成
- Eureka服务端 ： Eureka服务端用作服务注册中心。支持集群部署。
- Eureka客户端 ： Eureka客户端是一个java客户端，用来处理服务注册与发现。

在应用启动时，Eureka客户端向服务端注册自己的服务信息，同时将服务端的服务信息缓存到本地。客户端会和服务端周期性的进行心跳交互，以更新服务租约和服务信息。



