# C# · 状态管理与依赖注入

[← C# 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

组织业务状态、事件流和模块依赖。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [VContainer](#vcontainer) | Unity 依赖注入与生命周期作用域 | 3,059 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## VContainer

**适合**：模块较多、需要独立测试的 Unity 项目。

**选型提醒**：应明确场景作用域与对象生命周期，避免所有对象都走全局容器。

[源码](https://github.com/hadashiA/VContainer) · [官方文档](https://github.com/hadashiA/VContainer#readme) · [安装入口](https://github.com/hadashiA/VContainer#installation)

<sub>默认分支最近提交：2026-09-05 · [近期有提交](https://github.com/hadashiA/VContainer/commit/4fc1ed47dff1314e73fbf2a85ab88f53601414f6) · 版本与许可证见上游仓库。</sub>

---

[← 返回 C#](README.md) · [查看调研记录](../research/README.md)
