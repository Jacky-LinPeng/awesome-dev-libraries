# Kotlin · UI、布局与动效

[← Kotlin 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

传统 View 可比较 Epoxy 与 BaseRecyclerViewAdapterHelper；多平台 UI 看 Compose Multiplatform。更多[图片、刷新与事件组件](../java/android.md)可从 Kotlin 调用。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Compose Multiplatform](#compose-multiplatform) | 跨平台声明式 UI | 19,388 | 近期有提交 |
| [Epoxy](#epoxy) | 以模型构建复杂 RecyclerView 列表 | 8,550 | 近期有提交 |
| [BaseRecyclerViewAdapterHelper](#baserecyclerviewadapterhelper) | RecyclerView 适配器与列表交互辅助 | 24,576 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Compose Multiplatform

**适合**：希望共享 Kotlin UI 的多端应用。

**选型提醒**：JetBrains 官方框架；各平台成熟度与系统集成需分别评估。

[源码](https://github.com/JetBrains/compose-multiplatform) · [官方文档](https://github.com/JetBrains/compose-multiplatform#readme) · [安装入口](https://github.com/JetBrains/compose-multiplatform#readme)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/JetBrains/compose-multiplatform/commit/08276ddeab136cd69dc7d05dfb9e3fd2942dbc22) · 版本与许可证见上游仓库。</sub>

## Epoxy

**适合**：传统 Android View 的多类型列表。

**选型提醒**：面向 View 体系；Compose 项目先比较原生 Lazy 组件。

[源码](https://github.com/airbnb/epoxy) · [官方文档](https://github.com/airbnb/epoxy#readme) · [安装入口](https://github.com/airbnb/epoxy#installation)

<sub>默认分支最近提交：2026-01-23 · [近期有提交](https://github.com/airbnb/epoxy/commit/e45bd3a61fe3a1f130e184f5b8dcf172ab99025a) · 版本与许可证见上游仓库。</sub>

## BaseRecyclerViewAdapterHelper

**适合**：传统 View 的多类型列表、分页与拖拽。

**选型提醒**：各大版本 API 不同，按项目 RecyclerView 与 Kotlin 版本选择。

[源码](https://github.com/CymChad/BaseRecyclerViewAdapterHelper) · [官方文档](https://github.com/CymChad/BaseRecyclerViewAdapterHelper#readme) · [安装入口](https://github.com/CymChad/BaseRecyclerViewAdapterHelper#readme)

<sub>默认分支最近提交：2026-06-26 · [近期有提交](https://github.com/CymChad/BaseRecyclerViewAdapterHelper/commit/9948068cd95d5386cdb7f3e03d85fe2aede307cd) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Kotlin](README.md) · [查看调研记录](../research/README.md)
