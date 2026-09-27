# Go · 消息队列客户端

[← Go 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

Kafka、NATS 与消息总线。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Sarama](#sarama) | Kafka Go 客户端 | 12,520 | 近期有提交 |
| [kafka-go](#kafka-go) | Go 风格 Kafka 客户端 | 8,632 | 近期有提交 |
| [NATS Go client](#nats-go-client) | NATS 与 JetStream 客户端 | 6,760 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Sarama

**适合**：生产和消费 Kafka 消息。

**选型提醒**：按 broker 版本配置，并明确消费组、重试和提交语义。

[源码](https://github.com/IBM/sarama) · [官方文档](https://github.com/IBM/sarama#readme) · [安装入口](https://github.com/IBM/sarama#getting-started)

<sub>默认分支最近提交：2026-09-24 · [近期有提交](https://github.com/IBM/sarama/commit/d0755db92482a7035def381a26f3fb93206ee1fa) · 版本与许可证见上游仓库。</sub>

## kafka-go

**适合**：需要较直接 API 的 Kafka 接入。

**选型提醒**：与 Sarama 按功能和运维要求选择。

[源码](https://github.com/segmentio/kafka-go) · [官方文档](https://github.com/segmentio/kafka-go#readme) · [安装入口](https://github.com/segmentio/kafka-go#readme)

<sub>默认分支最近提交：2026-04-23 · [近期有提交](https://github.com/segmentio/kafka-go/commit/2e0b3968aa51b16beb4e221876499a6ff816cd91) · 版本与许可证见上游仓库。</sub>

## NATS Go client

**适合**：消息总线、请求响应和持久消息。

**选型提醒**：客户端需要配套 NATS 服务，持久化与投递语义取决于配置。

[源码](https://github.com/nats-io/nats.go) · [官方文档](https://github.com/nats-io/nats.go#readme) · [安装入口](https://github.com/nats-io/nats.go#installation)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/nats-io/nats.go/commit/5adc9d5d34ce8e3b7b8b002c5bd502a8b7a323d3) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Go](README.md) · [查看调研记录](../research/README.md)
