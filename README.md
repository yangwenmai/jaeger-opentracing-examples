# 分布式全链路跟踪系统实战 #
[![Build Status](https://travis-ci.org/yangwenmai/jaeger-opentracing-examples.svg?branch=master)](https://travis-ci.org/yangwenmai/jaeger-opentracing-examples) [![Go Report Card](https://goreportcard.com/badge/github.com/yangwenmai/jaeger-opentracing-examples)](https://goreportcard.com/report/github.com/yangwenmai/jaeger-opentracing-examples)  [![Documentation](https://godoc.org/github.com/yangwenmai/jaeger-opentracing-examples?status.svg)](http://godoc.org/github.com/yangwenmai/jaeger-opentracing-examples) [![Coverage Status](https://coveralls.io/repos/github/yangwenmai/jaeger-opentracing-examples/badge.svg?branch=master)](https://coveralls.io/github/yangwenmai/jaeger-opentracing-examples?branch=master) [![GitHub issues](https://img.shields.io/github/issues/yangwenmai/jaeger-opentracing-examples.svg)](https://github.com/yangwenmai/jaeger-opentracing-examples/issues) [![license](https://img.shields.io/github/license/yangwenmai/jaeger-opentracing-examples.svg?maxAge=2592000)](https://github.com/yangwenmai/jaeger-opentracing-examples/LICENSE) [![Release](https://img.shields.io/github/release/yangwenmai/jaeger-opentracing-examples.svg?label=Release)](https://github.com/yangwenmai/jaeger-opentracing-examples/releases)

## Stargazers over time

[![Stargazers over time](https://starcharts.herokuapp.com/yangwenmai/jaeger-opentracing-examples.svg)](https://starcharts.herokuapp.com/yangwenmai/jaeger-opentracing-examples)

## 分布式全链路跟踪系统是什么？

分布式链路跟踪的核心基本都是 Google Dapper 论文所述，使用全局 TraceID 表示一条调用链，连接各个服务调用（用 SPAN 表示），通过分析 SPAN 之间的父子关系形成跟踪树。
另外通过中间件的埋点和业务自定义的 Annotation ，记录日志并采用收集器进行离线和在线分析，从而实现调用链跟踪、优化决策等信息。

## Dapper 是什么？

[Dapper](https://github.com/bigbully/Dapper-translation) 是 Google 发表的分布式链路跟踪的论文。

## Jaeger 是什么？

[Jaeger](https://github.com/jaegertracing/jaeger) 是 Uber 基于 Google Dapper 开发的分布式链路跟踪系统的实现。

## 其他

- Ziplin

----

# 坑

1. Docker 运行要特别注意网络互通。
2. 实际运行中可能存在较大的延时。

# 参考资料

1. http://ginobefunny.com/post/learning_distributed_systems_tracing/
2. https://bigbully.github.io/Dapper-translation/
3. https://tech.meituan.com/mt-mtrace.html
4. https://github.com/jaegertracing/jaeger

# 赞助我

![微信支付](./docs/wxpay.jpg)
