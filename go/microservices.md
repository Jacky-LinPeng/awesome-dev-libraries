# Go · 微服务与 RPC

[← Go 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

代码生成、服务治理与跨语言调用。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [go-zero](#go-zero) | Web/RPC、代码生成与服务治理 | 33,359 | 近期有提交 |
| [Kratos](#kratos) | 面向微服务的 Go 工程框架 | 25,949 | 近期有提交 |
| [gRPC-Go](#grpc-go) | Go 的 gRPC 实现 | 23,075 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## go-zero

**适合**：采用 go-zero 技术栈的业务服务。

**选型提醒**：优先使用框架已有能力，避免重复接入同类组件。

[源码](https://github.com/zeromicro/go-zero) · [官方文档](https://github.com/zeromicro/go-zero#readme) · [安装入口](https://github.com/zeromicro/go-zero#installation)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/zeromicro/go-zero/commit/0eea741cde72bed2d217c296e2d8e2be874c73ea) · 版本与许可证见上游仓库。</sub>

## Kratos

**适合**：希望统一 HTTP、gRPC 与工程约定的团队。

**选型提醒**：与 go-zero 按已有基础设施和团队习惯选择。

[源码](https://github.com/go-kratos/kratos) · [官方文档](https://go-kratos.dev/docs/getting-started/start) · [安装入口](https://github.com/go-kratos/kratos#installation)

<sub>默认分支最近提交：2026-06-26 · [近期有提交](https://github.com/go-kratos/kratos/commit/668db92c2c001e9552594ba5a8aede8456af6d7e) · 版本与许可证见上游仓库。</sub>

## gRPC-Go

**适合**：与 Java、C# 等服务共享 proto 契约。

**选型提醒**：需要超时、取消、错误码与服务兼容策略。

[源码](https://github.com/grpc/grpc-go) · [官方文档](https://grpc.io/docs/languages/go/quickstart) · [安装入口](https://github.com/grpc/grpc-go#installation)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/grpc/grpc-go/commit/acccf8cd101ae1eb33385f27e12740b3edd730f0) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Go](README.md) · [查看调研记录](../research/README.md)
