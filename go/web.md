# Go · Web 与 API 服务

[← Go 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

保留 net/http 接口看 chi；完整 API 框架比较 Gin 与 Echo；Fiber 需额外验证 fasthttp 的接口差异。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Gin](#gin) | HTTP 路由、中间件与接口绑定 | 89,264 | 近期有提交 |
| [Echo](#echo) | HTTP 路由、请求上下文与中间件 | 32,730 | 近期有提交 |
| [Fiber](#fiber) | 基于 fasthttp 的 Web 框架 | 40,184 | 近期有提交 |
| [chi](#chi) | 兼容 net/http 的轻量路由与中间件 | 22,893 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Gin

**适合**：通用 Go HTTP API 服务。

**选型提醒**：已有 net/http 能覆盖需求时，不必为简单路由增加框架。

[源码](https://github.com/gin-gonic/gin) · [官方文档](https://pkg.go.dev/github.com/gin-gonic/gin) · [安装入口](https://github.com/gin-gonic/gin#getting-started)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/gin-gonic/gin/commit/1bd0ecf2d3e08da37efa270bb7be20c1eddb0d68) · 版本与许可证见上游仓库。</sub>

## Echo

**适合**：偏好完整 Web 框架体验的 API 项目。

**选型提醒**：与 Gin 按团队习惯择一，避免同服务混用框架。

[源码](https://github.com/labstack/echo) · [官方文档](https://echo.labstack.com/docs/quick-start) · [安装入口](https://github.com/labstack/echo#installation)

<sub>默认分支最近提交：2026-09-21 · [近期有提交](https://github.com/labstack/echo/commit/3d084be9022432c5a5257924c7d74bfc3444b456) · 版本与许可证见上游仓库。</sub>

## Fiber

**适合**：偏好 Express 风格 API 的 Go 服务。

**选型提醒**：与 net/http 生态存在接口差异，先验证中间件和上下文使用方式。

[源码](https://github.com/gofiber/fiber) · [官方文档](https://docs.gofiber.io) · [安装入口](https://github.com/gofiber/fiber#️-installation)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/gofiber/fiber/commit/e10bca7375d87511d8c764642689db7809a4e1c8) · 版本与许可证见上游仓库。</sub>

## chi

**适合**：希望保留标准库接口的服务。

**选型提醒**：适合渐进组合；认证、存储等能力需要自行选择。

[源码](https://github.com/go-chi/chi) · [官方文档](https://github.com/go-chi/chi#readme) · [安装入口](https://github.com/go-chi/chi#install)

<sub>默认分支最近提交：2026-09-18 · [近期有提交](https://github.com/go-chi/chi/commit/3d1777a1ef8881f7d1da0b02c76ca8f0a29cd2bc) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Go](README.md) · [查看调研记录](../research/README.md)
