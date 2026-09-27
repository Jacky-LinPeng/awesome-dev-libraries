# Java · 网络与通信

[← Java 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

调用 API、上传下载、长连接和协议通信。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Netty](#netty) | 异步网络框架与协议编解码 | 35,067 | 近期有提交 |
| [gRPC Java](#grpc-java) | 基于 Protocol Buffers 的 RPC | 12,072 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Netty

**适合**：自定义协议、长连接与高并发网络服务。

**选型提醒**：比业务 HTTP 框架更底层；需要理解线程模型与缓冲区生命周期。

[源码](https://github.com/netty/netty) · [官方文档](https://netty.io/wiki/) · [安装入口](https://github.com/netty/netty#readme)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/netty/netty/commit/901d1c5ef8f921c7a4dfd873a873a7b1cdf477bb) · 版本与许可证见上游仓库。</sub>

## gRPC Java

**适合**：Java 与 Go 等服务之间的类型化通信。

**选型提醒**：需维护 proto 契约，并设计超时、错误与版本兼容。

[源码](https://github.com/grpc/grpc-java) · [官方文档](https://grpc.io/docs/languages/java/quickstart) · [安装入口](https://github.com/grpc/grpc-java#getting-started)

<sub>默认分支最近提交：2026-09-24 · [近期有提交](https://github.com/grpc/grpc-java/commit/4d0d548ea050d002c66573a30785f14bdfd41bea) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Java](README.md) · [查看调研记录](../research/README.md)
