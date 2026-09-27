# Kotlin · 旧项目维护与迁移

[← Kotlin 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

> 本页用于识别旧依赖和安排迁移。已归档、已弃用与长期低频更新分别标注；这些条目不进入新项目速查路线。


## 历史维护 · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [旧 ExoPlayer](#旧-exoplayer) | 旧版 Android 媒体播放库 | 21,938 | 已弃用 |
| [Accompanist](#accompanist) | Compose 的补充工具集合 | 7,837 | 部分已弃用 |
| [Material Components Views](#material-components-views) | 基于 Android Views 的 Material UI 组件 | 17,399 | 维护模式 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## 旧 ExoPlayer

**适合**：迁移已有 com.google.android.exoplayer2 代码。

**选型提醒**：上游说明已迁移 AndroidX Media3；新项目使用 Media3。

[源码](https://github.com/google/ExoPlayer) · [官方文档](https://github.com/google/ExoPlayer#readme) · [安装入口](https://github.com/google/ExoPlayer#readme)

<sub>默认分支最近提交：2024-07-25 · [已弃用](https://github.com/google/ExoPlayer/commit/dd430f7053a1a3958deea3ead6a0565150c06bfc) · 版本与许可证见上游仓库。</sub>

## Accompanist

**适合**：维护已有 Accompanist 模块。

**选型提醒**：多个组件已弃用或迁入官方 Compose；逐模块核对迁移指引。

[源码](https://github.com/google/accompanist) · [官方文档](https://github.com/google/accompanist#readme) · [安装入口](https://github.com/google/accompanist#readme)

<sub>默认分支最近提交：2025-08-18 · [部分已弃用](https://github.com/google/accompanist/commit/12ec3408fc101e0006e38dc62f7acff7a822e20b) · 版本与许可证见上游仓库。</sub>

## Material Components Views

**适合**：维护现有 XML/View 界面。

**选型提醒**：官方已进入维护模式，新的 Material 特性优先看 Compose Material 3。

[源码](https://github.com/material-components/material-components-android) · [官方文档](https://github.com/material-components/material-components-android#readme) · [安装入口](https://github.com/material-components/material-components-android#getting-started)

<sub>默认分支最近提交：2026-09-14 · [维护模式](https://github.com/material-components/material-components-android/commit/60ff09436d5d477a4b9d02940f31eb01e1250620) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Kotlin](README.md) · [查看调研记录](../research/README.md)
