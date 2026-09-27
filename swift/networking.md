# Swift · 网络与通信

[← Swift 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

需要完整 HTTP 能力看 Alamofire；接口较多且需要端点建模时，再评估 Moya。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Alamofire](#alamofire) | HTTP 请求、上传下载与请求拦截 | 42,420 | 近期有提交 |
| [Moya](#moya) | 用枚举组织 API，统一请求与测试桩 | 15,356 | 近期有提交 |
| [Starscream](#starscream) | Swift WebSocket 客户端 | 8,641 | 更新较久 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Alamofire

**适合**：需要统一重试、鉴权与上传进度的 iOS 应用。

**选型提醒**：简单请求可先用 URLSession；按项目 Swift 与系统版本选择发行版。

[源码](https://github.com/Alamofire/Alamofire) · [官方文档](https://alamofire.github.io/Alamofire) · [安装入口](https://github.com/Alamofire/Alamofire#installation)

<sub>默认分支最近提交：2026-09-10 · [近期有提交](https://github.com/Alamofire/Alamofire/commit/bda9ed57d72988a3a2ada33d824583541f86eac6) · 版本与许可证见上游仓库。</sub>

## Moya

**适合**：接口较多、需要集中管理端点的团队。

**选型提醒**：基于 Alamofire；已有清晰网络层时不必再叠一层封装。

[源码](https://github.com/Moya/Moya) · [官方文档](https://github.com/Moya/Moya/tree/master/docs/Examples) · [安装入口](https://github.com/Moya/Moya#installation)

<sub>默认分支最近提交：2026-07-14 · [近期有提交](https://github.com/Moya/Moya/commit/24c26671a2f0fc26b53c9fa2410c97987fb0f05a) · 版本与许可证见上游仓库。</sub>

## Starscream

**适合**：聊天、实时推送与双向通信。

**选型提醒**：先比较系统 URLSessionWebSocketTask；需要额外能力时再接入。

[源码](https://github.com/daltoniam/Starscream) · [官方文档](https://github.com/daltoniam/Starscream#readme) · [安装入口](https://github.com/daltoniam/Starscream#installation)

<sub>默认分支最近提交：2024-03-07 · [更新较久](https://github.com/daltoniam/Starscream/commit/c6bfd1af48efcc9a9ad203665db12375ba6b145a) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Swift](README.md) · [查看调研记录](../research/README.md)
