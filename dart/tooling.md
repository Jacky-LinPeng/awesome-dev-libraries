# Dart · 日志、调试与工程质量

[← Dart 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

定位问题、分析性能和统一代码规范。


## 生态补充 · 速查

GitHub Star 低于 3,000，但有包平台使用量或其他框架官方集成依据；具体来源见条目。

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [flutter_native_splash](#flutter_native_splash) | 生成原生启动屏资源与配置 | 1,474 | 近期有提交 |
| [flutter_launcher_icons](#flutter_launcher_icons) | 生成应用图标资源 | 2,121 | 更新较久 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## flutter_native_splash

**适合**：统一 iOS/Android 启动屏。

**选型提醒**：属于构建工具，应用内加载页面仍需单独实现。

[源码](https://github.com/jonbhanson/flutter_native_splash) · [官方文档](https://pub.dev/packages/flutter_native_splash) · [安装入口](https://pub.dev/packages/flutter_native_splash/install)

**补充依据**：pub.dev 的 flutter_native_splash 包有 9,801 Likes、近 30 天 1,733,307 次下载，并标注 Flutter Favorite。 [核验来源](https://pub.dev/api/packages/flutter_native_splash/metrics)

<sub>默认分支最近提交：2026-05-29 · [近期有提交](https://github.com/jonbhanson/flutter_native_splash/commit/3de495d6cc4d4a2bce0e2e12286e1ffee15f1a35) · 版本与许可证见上游仓库。</sub>

## flutter_launcher_icons

**适合**：多平台图标与品牌资源更新。

**选型提醒**：生成后检查各平台遮罩、尺寸和构建配置。

[源码](https://github.com/fluttercommunity/flutter_launcher_icons) · [官方文档](https://pub.dev/packages/flutter_launcher_icons) · [安装入口](https://pub.dev/packages/flutter_launcher_icons/install)

**补充依据**：pub.dev 的 flutter_launcher_icons 包有 8,031 Likes、近 30 天 3,498,362 次下载。 [核验来源](https://pub.dev/api/packages/flutter_launcher_icons/metrics)

<sub>默认分支最近提交：2025-06-10 · [更新较久](https://github.com/fluttercommunity/flutter_launcher_icons/commit/10b86b10a5adef1368860aa22c8473d1881c47da) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Dart](README.md) · [查看调研记录](../research/README.md)
