# Dart · 状态管理与依赖注入

[← Dart 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

Provider 适合组件树内的依赖共享；Riverpod 便于异步状态组织；Bloc 强调明确的状态转换。先选一种主要约定。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Bloc / flutter_bloc](#bloc--flutter_bloc) | 事件驱动状态管理与配套测试工具 | 12,482 | 近期有提交 |
| [Riverpod](#riverpod) | 状态管理、依赖组织与异步数据处理 | 7,393 | 近期有提交 |
| [Provider](#provider) | 基于组件树提供和订阅依赖 | 5,251 | 近期有提交 |
| [GetX](#getx) | 状态、依赖与路由的一体化工具 | 11,195 | 近期有提交 |

## 生态补充 · 速查

GitHub Star 低于 3,000，但有包平台使用量或其他框架官方集成依据；具体来源见条目。

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [GetIt](#getit) | 服务定位与依赖获取 | 1,471 | 近期有提交 |

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

## GetIt

**适合**：跨组件访问服务对象。

**选型提醒**：它本身不是完整 UI 状态管理方案；避免隐藏依赖和全局滥用。

[源码](https://github.com/flutter-it/get_it) · [官方文档](https://pub.dev/packages/get_it) · [安装入口](https://pub.dev/packages/get_it/install)

**补充依据**：pub.dev 的 get_it 包有 4,725 Likes、近 30 天 2,124,078 次下载。 [核验来源](https://pub.dev/api/packages/get_it/metrics)

<sub>默认分支最近提交：2026-09-19 · [近期有提交](https://github.com/flutter-it/get_it/commit/5f20b031315e092ce4ecd278cb6d293f5fcf78c9) · 版本与许可证见上游仓库。</sub>

## GetX

**适合**：团队已选择 GetX 约定的 Flutter 工程。

**选型提醒**：涵盖职责较多，需约定使用边界；并非所有团队都偏好这种架构。

[源码](https://github.com/jonataslaw/getx) · [官方文档](https://github.com/jonataslaw/getx#readme) · [安装入口](https://github.com/jonataslaw/getx#installing)

<sub>默认分支最近提交：2026-06-12 · [近期有提交](https://github.com/jonataslaw/getx/commit/e3c8fa04ae65ebf7ff0128dbeb2dc91d4dafa429) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Dart](README.md) · [查看调研记录](../research/README.md)
