# C# · 状态管理与依赖注入

[← C# 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

组织业务状态、事件流和模块依赖。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [VContainer](#vcontainer) | Unity 依赖注入与生命周期作用域 | 3,059 | 近期有提交 |
| [Stateless](#stateless) | C# 状态机定义与转换 | 6,264 | 近期有提交 |
| [.NET Reactive](#net-reactive) | .NET 响应式流与 LINQ 组合 | 7,192 | 近期有提交 |

## 生态补充 · 速查

GitHub Star 低于 3,000，但有包平台使用量或其他框架官方集成依据；具体来源见条目。

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [MessagePipe](#messagepipe) | 进程内发布订阅与消息处理 | 1,997 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## VContainer

**适合**：模块较多、需要独立测试的 Unity 项目。

**选型提醒**：应明确场景作用域与对象生命周期，避免所有对象都走全局容器。

[源码](https://github.com/hadashiA/VContainer) · [官方文档](https://github.com/hadashiA/VContainer#readme) · [安装入口](https://github.com/hadashiA/VContainer#installation)

<sub>默认分支最近提交：2026-09-05 · [近期有提交](https://github.com/hadashiA/VContainer/commit/4fc1ed47dff1314e73fbf2a85ab88f53601414f6) · 版本与许可证见上游仓库。</sub>

## MessagePipe

**适合**：模块间事件解耦。

**选型提醒**：Unity 集成有专门安装方式；并不是可直接替代游戏联网的协议栈。

[源码](https://github.com/Cysharp/MessagePipe) · [官方文档](https://github.com/Cysharp/MessagePipe#readme) · [安装入口](https://github.com/Cysharp/MessagePipe#getting-started)

**补充依据**：VContainer 官方提供 MessagePipe 集成指南，可配合现有 Unity 依赖注入方案。 [核验来源](https://vcontainer.hadashikick.jp/integrations/messagepipe)

<sub>默认分支最近提交：2026-07-08 · [近期有提交](https://github.com/Cysharp/MessagePipe/commit/318838585b53e8e3332949f96be740cc61fcf072) · 版本与许可证见上游仓库。</sub>

## Stateless

**适合**：流程、连接状态和业务状态迁移。

**选型提醒**：它处理状态转换，不会自动提供持久化和 UI 绑定。

[源码](https://github.com/dotnet-state-machine/stateless) · [官方文档](https://github.com/dotnet-state-machine/stateless#readme) · [安装入口](https://github.com/dotnet-state-machine/stateless#readme)

<sub>默认分支最近提交：2026-04-04 · [近期有提交](https://github.com/dotnet-state-machine/stateless/commit/588f1a1a08683b452eb7c05562d9f055693cba5d) · 版本与许可证见上游仓库。</sub>

## .NET Reactive

**适合**：桌面工具和服务的持续事件流。

**选型提醒**：Unity 项目可比较 R3，避免混淆运行时支持范围。

[源码](https://github.com/dotnet/reactive) · [官方文档](https://github.com/dotnet/reactive#readme) · [安装入口](https://github.com/dotnet/reactive#readme)

<sub>默认分支最近提交：2026-09-24 · [近期有提交](https://github.com/dotnet/reactive/commit/89e05b8730107983c3f77af54a52974ae12d37f4) · 版本与许可证见上游仓库。</sub>

---

[← 返回 C#](README.md) · [查看调研记录](../research/README.md)
