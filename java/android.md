# Java · Android 客户端

[← Java 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

Java/Kotlin 混编项目也可查看 [Kotlin 网络](../kotlin/networking.md)、[MMKV 存储](../kotlin/storage.md)、[列表组件](../kotlin/ui.md)与[图表](../kotlin/charts.md)。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Glide](#glide) | Android 图片加载、缓存与解码 | 35,022 | 近期有提交 |
| [RxJava](#rxjava) | 响应式流与异步操作组合 | 48,192 | 近期有提交 |
| [EventBus](#eventbus) | 发布订阅式事件总线 | 24,706 | 更新较久 |
| [SmartRefreshLayout](#smartrefreshlayout) | Android 下拉刷新与加载更多 | 25,115 | 更新较久 |
| [Fresco](#fresco) | Android 图片管线与展示组件 | 17,155 | 近期有提交 |

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

## EventBus

**适合**：维护使用事件总线解耦的 Android 工程。

**选型提醒**：控制事件范围和订阅生命周期，避免形成难追踪的全局通信。

[源码](https://github.com/greenrobot/EventBus) · [官方文档](https://github.com/greenrobot/EventBus#readme) · [安装入口](https://github.com/greenrobot/EventBus#readme)

<sub>默认分支最近提交：2022-07-11 · [更新较久](https://github.com/greenrobot/EventBus/commit/0194926b3bcf70cc0d7bfd3c5da16708dd5ab876) · 版本与许可证见上游仓库。</sub>

## SmartRefreshLayout

**适合**：传统 View 列表的刷新动画与状态。

**选型提醒**：需要业务自行处理分页、失败和重复请求。

[源码](https://github.com/scwang90/SmartRefreshLayout) · [官方文档](https://github.com/scwang90/SmartRefreshLayout#readme) · [安装入口](https://github.com/scwang90/SmartRefreshLayout#readme)

<sub>默认分支最近提交：2024-11-26 · [更新较久](https://github.com/scwang90/SmartRefreshLayout/commit/224db48f8af897a930b810a6b6fc55af8cef0d57) · 版本与许可证见上游仓库。</sub>

## Fresco

**适合**：需要可定制图片处理管线的 Android 应用。

**选型提醒**：与 Glide、Coil 按图片管线和界面体系选型，避免重复缓存。

[源码](https://github.com/facebook/fresco) · [官方文档](https://github.com/facebook/fresco#readme) · [安装入口](https://github.com/facebook/fresco#readme)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/facebook/fresco/commit/6c366a53cecac0fe955173dc2d53edf9a2d043b0) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Java](README.md) · [查看调研记录](../research/README.md)
