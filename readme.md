# 👍👍👍 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 收集整理一些个人工作学习中偶然看到的👍的工具以及库，以便事后查阅。 每天工作日常使用的以及都已经成标准化的东西就不列在这了。


## Contents

- [辅助工具](#辅助工具)
- [平台解决方案](#平台解决方案)
- [开箱即用](#开箱即用)
- [中间件](#中间件)
- [开发库及框架](#开发库及框架)

## 辅助工具

各种开发相关的辅助工具，加速开发

- [yo](https://yeoman.io/) 脚手架生成工具
- [CodiMD](https://demo.codimd.org/) 开源Markdown编辑

## 平台解决方案

一些平台级的解决方案，如无特殊说明，都是基于k8s的。

- [jenkinsX](https://jenkins-x.io/) 开箱即用的CI/CD
- [pachyderm](https://www.pachyderm.io/) 大数据处理平台，使用容器管理data pipelines
- [openfaas](https://www.openfaas.com/) 开源FaaS解决方案

## 开箱即用

开箱即用的PaaS, SaaS或者命令行工具等
- [now](https://zeit.co/now) 免费便捷的一键PaaS
- [MachineBox](https://machinebox.io/) 基于Docker的机器学习MLaaS服务

## 中间件
中间件，主要是微服务的中间件，工作中用的Spring Cloud就不列了
- [Trafik](https://traefik.io/) 反向代理，在容器云中比nginx用起来简单方便
- [Kong](https://konghq.com) API-Gateway
- [Pulsar](http://pulsar.apache.org/) 下一代分布式消息队列, Kafka的替代方案之一

## 开发库及框架
代码级的库和框架
### Go
我的Go语言目前还处在比较初级的水平，所以这里列的可能会相对细一些，也会有一些重复表明目前我还没有选出自己的倾向来。
- [go-kit](http://gokit.io/) Go语言的微服务框架
- [go-micro](https://micro.mu/docs/go-micro.html) 另一个Go语言的微服务框架
- [gonum](https://www.gonum.org/) go语言版numpy
### Node.js
Node.js我一般用来做一些快速原型的实现，所以此处涉及的库和框架会偏向与轻量级的项目。
- [apollographql](https://www.apollographql.com/) GrapqhQL库，主要用[apollo-server-koa](https://www.npmjs.com/package/apollo-server-koa)
- [merge-graphql-schemas](https://www.npmjs.com/package/merge-graphql-schemas) 自动合并GraphQL schema的库，方便模块化定义
- [knex](https://www.npmjs.com/package/knex) 关系型数据库migration和query的库。我基本上是用到sqlite上做快速原型
- [lowdb](https://www.npmjs.com/package/lowdb) json文件级数据库

CLI工具
- [json-server](https://www.npmjs.com/package/json-server) json to REST API
- [json-graphql-server](https://www.npmjs.com/package/json-graphql-server) json to GraphQL API

## Contribute

虽然这个repo主要是记录自己的一些发现，不过如果大家觉得有什么的推荐的，也欢迎补充。


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Ming Wan has waived all copyright and
related or neighboring rights to this work.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyODI5NzYyNTksLTE3MDQwMTY2MTBdfQ
==
-->