# Dart · 后台任务与并发

[← Dart 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

队列、定时调度和并发控制。


## 生态补充 · 速查

GitHub Star 低于 3,000，但有包平台使用量或其他框架官方集成依据；具体来源见条目。

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Workmanager](#workmanager) | Android/iOS 后台任务调度 | 1,027 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Workmanager

**适合**：可延后执行的数据同步与维护任务。

**选型提醒**：执行时机受系统调度限制，不是精确计时或常驻后台服务。

[源码](https://github.com/fluttercommunity/flutter_workmanager) · [官方文档](https://pub.dev/packages/workmanager) · [安装入口](https://pub.dev/packages/workmanager/install)

**补充依据**：pub.dev 的 workmanager 包有 2,420 Likes、近 30 天 271,685 次下载。 [核验来源](https://pub.dev/api/packages/workmanager/metrics)

<sub>默认分支最近提交：2026-09-07 · [近期有提交](https://github.com/fluttercommunity/flutter_workmanager/commit/896c4c1122f5e267ed472b044219c884305246d3) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Dart](README.md) · [查看调研记录](../research/README.md)
