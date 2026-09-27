# Java · Android 客户端

[← Java 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

传统 View 图片展示和 Rx 事件处理。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Glide](#glide) | Android 图片加载、缓存与解码 | 35,022 | 近期有提交 |
| [RxJava](#rxjava) | 响应式流与异步操作组合 | 48,192 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Glide

**适合**：Java 或传统 View 技术栈的图片展示。

**选型提醒**：Kotlin Compose 项目可对比 Coil；统一应用图片缓存策略。

[源码](https://github.com/bumptech/glide) · [官方文档](https://bumptech.github.io/glide/) · [安装入口](https://github.com/bumptech/glide#readme)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/bumptech/glide/commit/dd2e7ed6a5bad52b94d50001075ec2b94e43f388) · 版本与许可证见上游仓库。</sub>

## RxJava

**适合**：已有 RxJava 架构或 JVM 事件流处理。

**选型提醒**：Android 主线程调度等集成需配套模块；注意背压与订阅释放。

[源码](https://github.com/ReactiveX/RxJava) · [官方文档](https://github.com/ReactiveX/RxJava/wiki/Getting-Started) · [安装入口](https://github.com/ReactiveX/RxJava#getting-started)

<sub>默认分支最近提交：2026-09-21 · [近期有提交](https://github.com/ReactiveX/RxJava/commit/ec9f38c33595dfd81168832c60cb960a69f8492a) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Java](README.md) · [查看调研记录](../research/README.md)
