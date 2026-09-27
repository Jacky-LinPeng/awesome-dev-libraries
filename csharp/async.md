# C# · 异步任务与事件流

[← C# 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

UniTask 处理单次异步流程；R3 处理持续事件流。两者可配合，先明确取消与订阅生命周期。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [UniTask](#unitask) | Unity PlayerLoop 集成的 async/await | 11,218 | 近期有提交 |
| [R3](#r3) | 面向 .NET 与 Unity 的响应式事件流 | 4,001 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## UniTask

**适合**：资源加载、场景切换和异步 UI 流程。

**选型提醒**：不是把任务自动搬到后台线程；注意取消与对象销毁生命周期。

[源码](https://github.com/Cysharp/UniTask) · [官方文档](https://github.com/Cysharp/UniTask#readme) · [安装入口](https://github.com/Cysharp/UniTask#getting-started)

<sub>默认分支最近提交：2026-07-08 · [近期有提交](https://github.com/Cysharp/UniTask/commit/ceac8d6946b1125fe782cd171fbcb245b567dbf9) · 版本与许可证见上游仓库。</sub>

## R3

**适合**：事件组合、状态订阅和响应式交互。

**选型提醒**：按文档选择 Unity 集成，并验证订阅释放与异常处理。

[源码](https://github.com/Cysharp/R3) · [官方文档](https://github.com/Cysharp/R3#readme) · [安装入口](https://github.com/Cysharp/R3#readme)

<sub>默认分支最近提交：2026-08-26 · [近期有提交](https://github.com/Cysharp/R3/commit/fdfb36e3d5af90ec06403714492ee85b2d8bf7cd) · 版本与许可证见上游仓库。</sub>

---

[← 返回 C#](README.md) · [查看调研记录](../research/README.md)
