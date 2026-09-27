# C# · .NET 服务与工具

[← C# 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

本页用于 C# 后端和工具开发，不承诺这些包可直接用于 Unity/IL2CPP。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Serilog](#serilog) | .NET 结构化日志 | 8,042 | 近期有提交 |
| [Polly](#polly) | .NET 重试、超时和熔断策略 | 14,235 | 近期有提交 |
| [Dapper](#dapper) | 轻量 SQL 对象映射 | 18,398 | 近期有提交 |
| [Entity Framework Core](#entity-framework-core) | .NET 实体映射与数据库访问 | 14,791 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Serilog

**适合**：C# 工具和服务端的日志记录。

**选型提醒**：主要按 .NET 场景收录；Unity 目标需单独验证 sink 和运行时兼容性。

[源码](https://github.com/serilog/serilog) · [官方文档](https://github.com/serilog/serilog/wiki/) · [安装入口](https://github.com/serilog/serilog#getting-started)

<sub>默认分支最近提交：2026-09-13 · [近期有提交](https://github.com/serilog/serilog/commit/bebc7719004f76187ae72e64ce138ec2540f2070) · 版本与许可证见上游仓库。</sub>

## Polly

**适合**：C# 服务或工具调用外部依赖。

**选型提醒**：主要按 .NET 场景收录；上游另有商业维护政策公告，商业接入前阅读官方 README。

[源码](https://github.com/App-vNext/Polly) · [官方文档](https://github.com/App-vNext/Polly#readme) · [安装入口](https://github.com/App-vNext/Polly#quick-start)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/App-vNext/Polly/commit/dc933fd172cbfae51b4ebc419014f4fed695cbb6) · 版本与许可证见上游仓库。</sub>

## Dapper

**适合**：C# 服务端与工具的数据访问。

**选型提醒**：主要用于 .NET 数据库访问，不能据此直接在移动游戏客户端连接生产数据库。

[源码](https://github.com/DapperLib/Dapper) · [官方文档](https://github.com/DapperLib/Dapper#readme) · [安装入口](https://github.com/DapperLib/Dapper#readme)

<sub>默认分支最近提交：2026-09-23 · [近期有提交](https://github.com/DapperLib/Dapper/commit/eb47546a408bbf6c178bda4f04dc205bc51ffbfe) · 版本与许可证见上游仓库。</sub>

## Entity Framework Core

**适合**：采用 ORM 的 C# 服务和工具。

**选型提醒**：属于微软官方生态组件；不作为 Unity 客户端默认数据库方案。

[源码](https://github.com/dotnet/efcore) · [官方文档](https://learn.microsoft.com/ef/core/) · [安装入口](https://github.com/dotnet/efcore#installation)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/dotnet/efcore/commit/7ae0f8f72996c83b9311d0e168eebb41bc160264) · 版本与许可证见上游仓库。</sub>

---

[← 返回 C#](README.md) · [查看调研记录](../research/README.md)
