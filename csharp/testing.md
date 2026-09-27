# C# · 自动化测试

[← C# 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

测试组织、断言、Mock 和集成验证。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [xUnit.net](#xunitnet) | .NET 测试框架 | 4,608 | 近期有提交 |

## 生态补充 · 速查

GitHub Star 低于 3,000，但有包平台使用量或其他框架官方集成依据；具体来源见条目。

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [NUnit](#nunit) | .NET 单元测试框架 | 2,626 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## NUnit

**适合**：C# 库与工具的单元测试。

**选型提醒**：Unity Test Framework 对 NUnit 有自身集成，不应随意替换内置版本。

[源码](https://github.com/nunit/nunit) · [官方文档](https://github.com/nunit/nunit#readme) · [安装入口](https://github.com/nunit/nunit#readme)

**补充依据**：Unity Test Framework 官方文档说明其集成 NUnit；Unity 工程应使用框架提供的兼容版本。 [核验来源](https://docs.unity3d.com/Packages/com.unity.test-framework@1.4/manual/index.html)

<sub>默认分支最近提交：2026-09-20 · [近期有提交](https://github.com/nunit/nunit/commit/8d82f854dcdc939aceae80dccb1fdaaf681e5430) · 版本与许可证见上游仓库。</sub>

## xUnit.net

**适合**：C# 服务与开发工具测试。

**选型提醒**：按 .NET 工程收录，不作为 Unity Test Runner 的直接替代。

[源码](https://github.com/xunit/xunit) · [官方文档](https://github.com/xunit/xunit#readme) · [安装入口](https://github.com/xunit/xunit#readme)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/xunit/xunit/commit/3c5976ff1a2e311e1a03d38c56393bce2e4eb3ce) · 版本与许可证见上游仓库。</sub>

---

[← 返回 C#](README.md) · [查看调研记录](../research/README.md)
