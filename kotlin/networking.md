# Kotlin · 网络与通信

[← Kotlin 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

Android REST 常见组合是 Retrofit + OkHttp；跨平台 Kotlin 网络层再评估 Ktor Client。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Retrofit](#retrofit) | 将 HTTP API 定义为类型化接口 | 43,944 | 近期有提交 |
| [OkHttp](#okhttp) | HTTP 连接、缓存、拦截器与 WebSocket | 47,077 | 近期有提交 |
| [Ktor](#ktor) | Kotlin HTTP 客户端与服务端框架 | 14,531 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Retrofit

**适合**：Android 常规 REST 接口接入。

**选型提醒**：通常配合 OkHttp；JSON 转换器按项目选择。

[源码](https://github.com/lysine-dev/retrofit) · [官方文档](https://lysine.dev/retrofit/) · [安装入口](https://github.com/lysine-dev/retrofit#readme)

<sub>默认分支最近提交：2026-09-03 · [近期有提交](https://github.com/lysine-dev/retrofit/commit/e27d855b7b029e7f907dfc52205fdb3e9c603c16) · 版本与许可证见上游仓库。</sub>

## OkHttp

**适合**：Android/JVM 的底层网络通信。

**选型提醒**：与 Retrofit 是上下层关系，常常一起使用。

[源码](https://github.com/lysine-dev/okhttp) · [官方文档](https://lysine.dev/okhttp/) · [安装入口](https://github.com/lysine-dev/okhttp#readme)

<sub>默认分支最近提交：2026-09-17 · [近期有提交](https://github.com/lysine-dev/okhttp/commit/40a3b8749deaacf60a04c890aed052cb14ad36ee) · 版本与许可证见上游仓库。</sub>

## Ktor

**适合**：共享 Kotlin 网络层或编写 Kotlin 服务。

**选型提醒**：客户端按目标平台选择 engine，不要误装服务端模块。

[源码](https://github.com/ktorio/ktor) · [官方文档](https://github.com/ktorio/ktor#readme) · [安装入口](https://github.com/ktorio/ktor#readme)

<sub>默认分支最近提交：2026-09-21 · [近期有提交](https://github.com/ktorio/ktor/commit/d08fd0382b2acf314b2beb430b66ba148845a892) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Kotlin](README.md) · [查看调研记录](../research/README.md)
