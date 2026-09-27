# Dart · 平台能力与权限

[← Dart 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

系统权限、相机、WebView 等能力。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Flutter 官方平台插件](#flutter-官方平台插件) | 相机、视频、WebView、偏好存储与 URL 唤起 | 5,310 | 近期有提交 |
| [flutter_inappwebview](#flutter_inappwebview) | 增强 WebView 与浏览器交互 | 3,779 | 近期有提交 |

## 生态补充 · 速查

GitHub Star 低于 3,000，但有包平台使用量或其他框架官方集成依据；具体来源见条目。

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Plus Plugins](#plus-plugins) | 设备、网络状态、分享等平台能力插件集合 | 1,875 | 近期有提交 |
| [permission_handler](#permission_handler) | 跨平台权限检查与请求 | 2,174 | 近期有提交 |
| [flutter_local_notifications](#flutter_local_notifications) | 本地通知与定时通知 | 2,666 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Plus Plugins

**适合**：需要跨端系统能力的 Flutter 应用。

**选型提醒**：仓库内插件分别发布；仅安装实际需要的包，Stars 为仓库总值。

[源码](https://github.com/fluttercommunity/plus_plugins) · [官方文档](https://pub.dev/packages/connectivity_plus) · [安装入口](https://pub.dev/packages/connectivity_plus/install)

**补充依据**：pub.dev 的 connectivity_plus 包有 4,095 Likes、近 30 天 3,689,161 次下载，并标注 Flutter Favorite。 [核验来源](https://pub.dev/api/packages/connectivity_plus/metrics)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/fluttercommunity/plus_plugins/commit/27d4e5f3419127b90ba6b279d068e6d58d54421d) · 版本与许可证见上游仓库。</sub>

## permission_handler

**适合**：相机、定位等能力的授权流程。

**选型提醒**：插件不能代替原生声明与用途说明，仍需配置各平台工程。

[源码](https://github.com/Baseflow/flutter-permission-handler) · [官方文档](https://pub.dev/packages/permission_handler) · [安装入口](https://pub.dev/packages/permission_handler/install)

**补充依据**：pub.dev 的 permission_handler 包有 6,014 Likes、近 30 天 3,432,295 次下载。 [核验来源](https://pub.dev/api/packages/permission_handler/metrics)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/Baseflow/flutter-permission-handler/commit/06844691889603bf867ef03e8f3ca24b83f9f1a0) · 版本与许可证见上游仓库。</sub>

## flutter_local_notifications

**适合**：提醒、日程和本地任务反馈。

**选型提醒**：本地通知不同于远程推送；平台权限和调度限制需单独处理。

[源码](https://github.com/MaikuB/flutter_local_notifications) · [官方文档](https://pub.dev/packages/flutter_local_notifications) · [安装入口](https://pub.dev/packages/flutter_local_notifications/install)

**补充依据**：pub.dev 的 flutter_local_notifications 包有 7,349 Likes、近 30 天 2,904,998 次下载，并标注 Flutter Favorite。 [核验来源](https://pub.dev/api/packages/flutter_local_notifications/metrics)

<sub>默认分支最近提交：2026-09-24 · [近期有提交](https://github.com/MaikuB/flutter_local_notifications/commit/884b9ef9d3584dbc647202710d11e1bd80950ad8) · 版本与许可证见上游仓库。</sub>

## Flutter 官方平台插件

**适合**：接入 camera、video_player、webview_flutter 等能力。

**选型提醒**：这是官方插件集合；按包选择并核对平台支持表，Stars 为仓库总值。

[源码](https://github.com/flutter/packages) · [官方文档](https://github.com/flutter/packages/tree/main/packages) · [安装入口](https://github.com/flutter/packages#readme)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/flutter/packages/commit/ba0364a650af47374ffb1412595e3bf789ae5c99) · 版本与许可证见上游仓库。</sub>

## flutter_inappwebview

**适合**：需要较多网页和原生交互能力的应用。

**选型提醒**：按平台配置权限与生命周期，限制暴露给网页的原生桥接能力。

[源码](https://github.com/pichillilorenzo/flutter_inappwebview) · [官方文档](https://github.com/pichillilorenzo/flutter_inappwebview#readme) · [安装入口](https://github.com/pichillilorenzo/flutter_inappwebview#installation)

<sub>默认分支最近提交：2026-02-10 · [近期有提交](https://github.com/pichillilorenzo/flutter_inappwebview/commit/17527cae5a3371c1e87f9c1df4281a7710debf28) · 版本与许可证见上游仓库。</sub>

## 常用官方包直达

| 场景 | 包 |
|---|---|
| 相机预览与拍摄 | [camera](https://pub.dev/packages/camera) |
| 视频播放 | [video_player](https://pub.dev/packages/video_player) |
| 嵌入 WebView | [webview_flutter](https://pub.dev/packages/webview_flutter) |
| 轻量偏好设置 | [shared_preferences](https://pub.dev/packages/shared_preferences) |
| 唤起浏览器或外部链接 | [url_launcher](https://pub.dev/packages/url_launcher) |
| 应用内购买 | [in_app_purchase](https://pub.dev/packages/in_app_purchase) |

这些包共用 Flutter 官方 packages 仓库；请在各自安装页检查系统配置与支持平台。

---

[← 返回 Dart](README.md) · [查看调研记录](../research/README.md)
