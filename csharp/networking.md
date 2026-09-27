# C# · 网络与通信

[← C# 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

希望使用高层对象同步看 Mirror；需要自行控制 UDP 消息协议看 LiteNetLib。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Mirror](#mirror) | Unity 高层多人联网框架 | 6,344 | 近期有提交 |
| [LiteNetLib](#litenetlib) | 轻量 UDP 网络库 | 3,625 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Mirror

**适合**：同步对象、玩家与场景状态的多人游戏。

**选型提醒**：需结合权威服务器、同步频率与传输方案设计。

[源码](https://github.com/MirrorNetworking/Mirror) · [官方文档](https://mirror-networking.gitbook.io/) · [安装入口](https://github.com/MirrorNetworking/Mirror#getting-started)

<sub>默认分支最近提交：2026-09-19 · [近期有提交](https://github.com/MirrorNetworking/Mirror/commit/c4f3739966e151f405be1762d33502794fd034ff) · 版本与许可证见上游仓库。</sub>

## LiteNetLib

**适合**：需要自己控制消息协议的游戏网络层。

**选型提醒**：比 Mirror 更底层，不提供完整状态同步；上游提示主分支可能不稳定，请选择适合的发行版。

[源码](https://github.com/RevenantX/LiteNetLib) · [官方文档](https://revenantx.github.io/LiteNetLib/index.html) · [安装入口](https://github.com/RevenantX/LiteNetLib#readme)

<sub>默认分支最近提交：2026-09-22 · [近期有提交](https://github.com/RevenantX/LiteNetLib/commit/caaf395942be6db401a2c58a377aa5b8720157ab) · 版本与许可证见上游仓库。</sub>

---

[← 返回 C#](README.md) · [查看调研记录](../research/README.md)
