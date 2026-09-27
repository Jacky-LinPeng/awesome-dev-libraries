# C# · 代码热更新与脚本

[← C# 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

HybridCLR 面向 C# 代码热更新；xLua 面向 Lua 与 C# 互操作。先决定业务语言和构建管线。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [HybridCLR](#hybridclr) | 扩展 Unity IL2CPP 的 C# 热更新能力 | 7,982 | 近期有提交 |
| [xLua](#xlua) | Unity/C# 与 Lua 的互操作 | 10,199 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## HybridCLR

**适合**：采用 C# 代码热更新管线的 Unity 工程。

**选型提醒**：与 Unity、IL2CPP、构建工具链强相关，先验证目标平台和发布要求。

[源码](https://github.com/focus-creative-games/hybridclr) · [官方文档](https://www.hybridclr.cn/docs/intro) · [安装入口](https://github.com/focus-creative-games/hybridclr#readme)

<sub>默认分支最近提交：2026-08-20 · [近期有提交](https://github.com/focus-creative-games/hybridclr/commit/210cbe0ecc878a6ab7e392b1ce191a46d509ba25) · 版本与许可证见上游仓库。</sub>

## xLua

**适合**：已有 Lua 业务逻辑或脚本热更新方案。

**选型提醒**：引入 Lua 需要配套绑定、调试、资源和发布管线。

[源码](https://github.com/Tencent/xLua) · [官方文档](https://github.com/Tencent/xLua#readme) · [安装入口](https://github.com/Tencent/xLua#安装)

<sub>默认分支最近提交：2025-11-21 · [近期有提交](https://github.com/Tencent/xLua/commit/59bf42685dbe36fe0e1678a6ba8597f859ef7ca3) · 版本与许可证见上游仓库。</sub>

---

[← 返回 C#](README.md) · [查看调研记录](../research/README.md)
