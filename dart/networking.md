# Dart · 网络与通信

[← Dart 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

调用 API、上传下载、长连接和协议通信。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Dio](#dio) | HTTP 请求、拦截器、上传下载与取消 | 12,842 | 近期有提交 |

## 生态补充 · 速查

GitHub Star 低于 3,000，但有包平台使用量或其他框架官方集成依据；具体来源见条目。

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [http](#http) | Dart HTTP 请求与响应 | 1,110 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Dio

**适合**：Flutter 应用的集中式网络层。

**选型提醒**：Token 刷新和重试需处理并发，避免重复请求。

[源码](https://github.com/cfug/dio) · [官方文档](https://pub.dev/packages/dio) · [安装入口](https://pub.dev/packages/dio/install)

<sub>默认分支最近提交：2026-09-04 · [近期有提交](https://github.com/cfug/dio/commit/4684e29dabaa2655606f1620a4ed316ee3f8c963) · 版本与许可证见上游仓库。</sub>

## http

**适合**：轻量接口调用或通用 Dart 网络代码。

**选型提醒**：属于 Dart 官方生态包；拦截器等更完整需求可比较 Dio。

[源码](https://github.com/dart-lang/http) · [官方文档](https://pub.dev/packages/http) · [安装入口](https://pub.dev/packages/http/install)

**补充依据**：pub.dev 的 http 包有 8,473 Likes、近 30 天 12,147,753 次下载。 [核验来源](https://pub.dev/api/packages/http/metrics)

<sub>默认分支最近提交：2026-09-21 · [近期有提交](https://github.com/dart-lang/http/commit/d8e8e9cd1ae6ed0f0339cfa0f47f92e837a786f5) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Dart](README.md) · [查看调研记录](../research/README.md)
