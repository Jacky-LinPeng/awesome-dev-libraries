# Kotlin · 状态管理与依赖注入

[← Kotlin 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

协程负责异步；Koin 与 Dagger/Hilt 负责依赖组织，后两者按团队约定择一。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [kotlinx.coroutines](#kotlinxcoroutines) | 协程、结构化并发与 Flow | 13,815 | 近期有提交 |
| [Koin](#koin) | 面向 Kotlin 的依赖注入 | 10,022 | 近期有提交 |
| [Dagger / Hilt](#dagger--hilt) | 编译期依赖注入与 Android 生命周期集成 | 17,701 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## kotlinx.coroutines

**适合**：异步任务、取消与事件流。

**选型提醒**：属于 Kotlin 官方生态组件；关注作用域与生命周期。

[源码](https://github.com/Kotlin/kotlinx.coroutines) · [官方文档](https://kotlinlang.org/api/kotlinx.coroutines/) · [安装入口](https://github.com/Kotlin/kotlinx.coroutines#readme)

<sub>默认分支最近提交：2026-09-16 · [近期有提交](https://github.com/Kotlin/kotlinx.coroutines/commit/bd2e9a1b90400fb7b2fa4f8731e7d8148799ab73) · 版本与许可证见上游仓库。</sub>

## Koin

**适合**：偏好 DSL 配置与较轻接入方式。

**选型提醒**：作用域和依赖图需测试；与 Dagger/Hilt 选择一条主线。

[源码](https://github.com/InsertKoinIO/koin) · [官方文档](https://github.com/InsertKoinIO/koin#readme) · [安装入口](https://github.com/InsertKoinIO/koin#readme)

<sub>默认分支最近提交：2026-06-12 · [近期有提交](https://github.com/InsertKoinIO/koin/commit/dc86ef8dd8fbe8564fb7453c03f5b738da3450bb) · 版本与许可证见上游仓库。</sub>

## Dagger / Hilt

**适合**：大型 Android 项目的依赖管理。

**选型提醒**：Hilt 是该仓库中的 Android 方案；Stars 属于整个 Dagger 仓库。

[源码](https://github.com/google/dagger) · [官方文档](https://dagger.dev) · [安装入口](https://github.com/google/dagger#installation)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/google/dagger/commit/cf791f362d4d0379b8a6ecee7f80770aba25bec1) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Kotlin](README.md) · [查看调研记录](../research/README.md)
