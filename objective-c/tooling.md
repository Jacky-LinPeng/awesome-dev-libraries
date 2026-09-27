# Objective-C · 日志、调试与工程质量

[← Objective-C 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

定位问题、分析性能和统一代码规范。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [CocoaLumberjack](#cocoalumberjack) | 分级日志、异步记录与多输出目标 | 13,320 | 近期有提交 |
| [FLEX](#flex) | 运行时查看视图、对象与网络信息 | 14,640 | 近期有提交 |
| [PLCrashReporter](#plcrashreporter) | 生成原生崩溃报告 | 3,070 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## CocoaLumberjack

**适合**：iOS 混编工程的日志体系。

**选型提醒**：生产日志应控制体积并避免记录凭据和隐私数据。

[源码](https://github.com/CocoaLumberjack/CocoaLumberjack) · [官方文档](https://github.com/CocoaLumberjack/CocoaLumberjack/blob/master/Documentation/GettingStarted.md) · [安装入口](https://github.com/CocoaLumberjack/CocoaLumberjack#install-manually)

<sub>默认分支最近提交：2026-09-21 · [近期有提交](https://github.com/CocoaLumberjack/CocoaLumberjack/commit/b75d3c3198a2930b4491b04fd47cb504b359c750) · 版本与许可证见上游仓库。</sub>

## FLEX

**适合**：开发阶段排查 UI 和状态问题。

**选型提醒**：仅在调试构建中启用，不要随正式包开放调试入口。

[源码](https://github.com/FLEXTool/FLEX) · [官方文档](https://github.com/FLEXTool/FLEX#readme) · [安装入口](https://github.com/FLEXTool/FLEX#installation)

<sub>默认分支最近提交：2026-06-11 · [近期有提交](https://github.com/FLEXTool/FLEX/commit/63a6f588841e94e4c3adaa045ff16eb8163f0bb4) · 版本与许可证见上游仓库。</sub>

## PLCrashReporter

**适合**：需要自建或集成崩溃采集能力。

**选型提醒**：完整崩溃平台仍需上报、符号化和报告管理。

[源码](https://github.com/microsoft/plcrashreporter) · [官方文档](https://github.com/microsoft/plcrashreporter#readme) · [安装入口](https://github.com/microsoft/plcrashreporter#readme)

<sub>默认分支最近提交：2025-11-12 · [近期有提交](https://github.com/microsoft/plcrashreporter/commit/0254f941c646b1ed17b243654723d0f071e990d0) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Objective-C](README.md) · [查看调研记录](../research/README.md)
