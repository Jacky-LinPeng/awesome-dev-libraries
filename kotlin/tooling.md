# Kotlin · 日志、调试与工程质量

[← Kotlin 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

定位问题、分析性能和统一代码规范。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Chucker](#chucker) | 在应用内查看 HTTP 请求与响应 | 4,569 | 近期有提交 |
| [LeakCanary](#leakcanary) | 检测 Android 对象与组件的内存泄漏 | 29,999 | 近期有提交 |
| [detekt](#detekt) | Kotlin 静态分析与复杂度检查 | 7,071 | 近期有提交 |
| [ktlint](#ktlint) | Kotlin 格式检查与自动修正 | 6,747 | 近期有提交 |
| [Timber](#timber) | Android 日志入口与输出树 | 10,852 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Chucker

**适合**：调试 Android 网络接口。

**选型提醒**：按官方方式配置 debug 与 no-op 依赖，避免生产环境泄漏请求数据。

[源码](https://github.com/ChuckerTeam/chucker) · [官方文档](https://github.com/ChuckerTeam/chucker#readme) · [安装入口](https://github.com/ChuckerTeam/chucker#getting-started-)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/ChuckerTeam/chucker/commit/0f6727941ea1fb3921a22a1d18d311c5266b5b02) · 版本与许可证见上游仓库。</sub>

## LeakCanary

**适合**：开发阶段定位 Activity、Fragment 等泄漏。

**选型提醒**：通常配置为 debug 依赖；报告仍需结合引用链分析。

[源码](https://github.com/square/leakcanary) · [官方文档](https://github.com/square/leakcanary#readme) · [安装入口](https://github.com/square/leakcanary#readme)

<sub>默认分支最近提交：2026-08-31 · [近期有提交](https://github.com/square/leakcanary/commit/66aab8d2ab695c4e1c013ed1bd5c3884939c1e2f) · 版本与许可证见上游仓库。</sub>

## detekt

**适合**：CI 代码质量规则。

**选型提醒**：先建立团队基线，再逐步收紧规则。

[源码](https://github.com/detekt/detekt) · [官方文档](https://detekt.dev/) · [安装入口](https://github.com/detekt/detekt#quick-start-)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/detekt/detekt/commit/d8424fc71161aec85d8667f6cbc22671d9e3a4d6) · 版本与许可证见上游仓库。</sub>

## ktlint

**适合**：统一 Kotlin 代码排版。

**选型提醒**：项目已迁移组织；本导航使用实际跳转后的官方地址。

[源码](https://github.com/ktlint/ktlint) · [官方文档](https://ktlint.github.io/ktlint/) · [安装入口](https://github.com/ktlint/ktlint#quick-start)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/ktlint/ktlint/commit/9dbe17d9e1b3b18f07d76bdd34bee0020ab05d02) · 版本与许可证见上游仓库。</sub>

## Timber

**适合**：统一应用日志调用与不同环境输出。

**选型提醒**：只是日志基础库，上传、检索和脱敏需要另行设计。

[源码](https://github.com/JakeWharton/timber) · [官方文档](https://github.com/JakeWharton/timber#readme) · [安装入口](https://github.com/JakeWharton/timber#readme)

<sub>默认分支最近提交：2026-09-18 · [近期有提交](https://github.com/JakeWharton/timber/commit/55b54775e7ecc003efb75116de7721048483a56f) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Kotlin](README.md) · [查看调研记录](../research/README.md)
