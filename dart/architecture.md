# Dart · 状态管理与依赖注入

[← Dart 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

Provider 适合组件树内的依赖共享；Riverpod 便于异步状态组织；Bloc 强调明确的状态转换。先选一种主要约定。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Bloc / flutter_bloc](#bloc--flutter_bloc) | 事件驱动状态管理与配套测试工具 | 12,482 | 近期有提交 |
| [Riverpod](#riverpod) | 状态管理、依赖组织与异步数据处理 | 7,393 | 近期有提交 |
| [Provider](#provider) | 基于组件树提供和订阅依赖 | 5,251 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Bloc / flutter_bloc

**适合**：需要明确状态转换与团队规范的业务应用。

**选型提醒**：Bloc 与 Cubit 可按复杂度选择；无需所有页面都上复杂事件模型。

[源码](https://github.com/felangel/bloc) · [官方文档](https://bloclibrary.dev) · [安装入口](https://pub.dev/packages/flutter_bloc/install)

<sub>默认分支最近提交：2026-09-24 · [近期有提交](https://github.com/felangel/bloc/commit/b9be1e252ee24ffbe9f2fb629edc7624b2cfbf05) · 版本与许可证见上游仓库。</sub>

## Riverpod

**适合**：Flutter 多页面共享状态和异步业务。

**选型提醒**：若使用代码生成，需同时维护生成器与构建流程。

[源码](https://github.com/rrousselGit/riverpod) · [官方文档](https://riverpod.dev) · [安装入口](https://pub.dev/packages/flutter_riverpod/install)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/rrousselGit/riverpod/commit/f7e0110a8dba42c4125dc8976505c6d996f8df49) · 版本与许可证见上游仓库。</sub>

## Provider

**适合**：中小规模状态共享或已有 ChangeNotifier 架构。

**选型提醒**：复杂状态和生命周期需要团队自行约定。

[源码](https://github.com/rrousselGit/provider) · [官方文档](https://pub.dev/packages/provider) · [安装入口](https://pub.dev/packages/provider/install)

<sub>默认分支最近提交：2026-03-10 · [近期有提交](https://github.com/rrousselGit/provider/commit/6cfb56aec9f405dae0030d78f43bf4817265c5eb) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Dart](README.md) · [查看调研记录](../research/README.md)
