# Swift · 状态管理与依赖注入

[← Swift 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

TCA 组织业务状态，RxSwift 组合事件流，Swinject 管理依赖；三者解决的问题不同。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [RxSwift](#rxswift) | 组合异步事件与响应式数据流 | 24,640 | 近期有提交 |
| [TCA](#tca) | 统一状态、事件、副作用与可测试的功能组合 | 14,937 | 近期有提交 |
| [Swinject](#swinject) | 依赖注入与对象生命周期管理 | 6,708 | 更新较久 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## RxSwift

**适合**：已有 Rx 架构，或需要复杂事件组合。

**选型提醒**：团队需掌握订阅生命周期；新项目也可评估原生并发能力。

[源码](https://github.com/ReactiveX/RxSwift) · [官方文档](https://github.com/ReactiveX/RxSwift/blob/main/Documentation/GettingStarted.md) · [安装入口](https://github.com/ReactiveX/RxSwift#-install)

<sub>默认分支最近提交：2026-09-04 · [近期有提交](https://github.com/ReactiveX/RxSwift/commit/3e33f90c1bcd3cdea25bdb49bd4a594a50c3ab84) · 版本与许可证见上游仓库。</sub>

## TCA

**适合**：状态复杂、强调模块组合和测试的应用。

**选型提醒**：架构约束较强，应先用一个业务模块验证团队适应成本。

[源码](https://github.com/pointfreeco/swift-composable-architecture) · [官方文档](https://swiftpackageindex.com/pointfreeco/swift-composable-architecture/main/documentation/composablearchitecture/gettingstarted) · [安装入口](https://github.com/pointfreeco/swift-composable-architecture#installation)

<sub>默认分支最近提交：2026-08-28 · [近期有提交](https://github.com/pointfreeco/swift-composable-architecture/commit/377da4061db10d26337a71bb279c506bb951f50f) · 版本与许可证见上游仓库。</sub>

## Swinject

**适合**：模块较多，需要替换服务实现和测试依赖。

**选型提醒**：小项目可先用构造函数注入；关注当前 Swift 工具链兼容性。

[源码](https://github.com/Swinject/Swinject) · [官方文档](https://github.com/Swinject/Swinject#readme) · [安装入口](https://github.com/Swinject/Swinject#installation)

<sub>默认分支最近提交：2025-09-01 · [更新较久](https://github.com/Swinject/Swinject/commit/b685b549fe4d8ae265fc7a2f27d0789720425d69) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Swift](README.md) · [查看调研记录](../research/README.md)
