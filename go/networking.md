# Go · 网络与通信

[← Go 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

调用 API、上传下载、长连接和协议通信。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Gorilla WebSocket](#gorilla-websocket) | WebSocket 客户端与服务端 | 24,878 | 更新较久 |
| [Resty](#resty) | HTTP 客户端封装与请求链式配置 | 11,810 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Gorilla WebSocket

**适合**：聊天、实时通知与状态推送。

**选型提醒**：按文档控制并发读写，并处理心跳和断线恢复。

[源码](https://github.com/gorilla/websocket) · [官方文档](https://pkg.go.dev/github.com/gorilla/websocket) · [安装入口](https://github.com/gorilla/websocket#installation)

<sub>默认分支最近提交：2025-03-19 · [更新较久](https://github.com/gorilla/websocket/commit/e064f32e3674d9d79a8fd417b5bc06fa5c6cad8f) · 版本与许可证见上游仓库。</sub>

## Resty

**适合**：调用外部 API，统一重试与请求处理。

**选型提醒**：普通请求可先用 net/http；重试写操作需考虑幂等性。

[源码](https://github.com/go-resty/resty) · [官方文档](https://github.com/go-resty/resty#readme) · [安装入口](https://github.com/go-resty/resty#readme)

<sub>默认分支最近提交：2026-09-21 · [近期有提交](https://github.com/go-resty/resty/commit/3da7d0987ff4ba931fe55ce8a7f71cb4193fd971) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Go](README.md) · [查看调研记录](../research/README.md)
