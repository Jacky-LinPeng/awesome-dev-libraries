# C# · 开源库导航

[← 返回首页](../README.md) · [全部库索引](../INDEX.md) · [筛选与核验](../research/README.md)

以 Unity 为主，.NET 服务与工具单独成页。库的 GitHub 主语言不一定是 C#，例如 HybridCLR 修改运行时，但它服务于 C# 开发。

> Unity / .NET · 30 个选型入口 · 2 个历史条目 · 高 Star 27 / 生态补充 3 · 核验于 2026-09-27

## 按业务模块查找

| 模块 | 我要解决什么问题 | 条目数 |
|---|---|---:|
| [异步任务与事件流](async.md) | Unity 异步流程、取消和事件组合 | 2 |
| [状态管理与依赖注入](architecture.md) | 组织业务状态、事件流和模块依赖 | 4 |
| [数据模型与序列化](serialization.md) | JSON、二进制数据和类型化模型 | 3 |
| [资源管理与更新](assets.md) | 资源构建、加载、分包与下载 | 1 |
| [代码热更新与脚本](hot-update.md) | C# 热更新和 Lua 互操作 | 3 |
| [配置与工具链](configuration.md) | 应用配置、命令行或游戏策划表 | 1 |
| [网络与通信](networking.md) | 调用 API、上传下载、长连接和协议通信 | 2 |
| [UI、布局与动效](ui.md) | 页面布局、图表和界面视觉效果 | 2 |
| [补间动画](animation.md) | UI 动效、数值过渡与动画序列 | 1 |
| [日志、调试与工程质量](tooling.md) | 定位问题、分析性能和统一代码规范 | 1 |
| [.NET 服务与工具](dotnet.md) | C# 服务端和开发工具的基础库 | 4 |
| [Unity 游戏基础框架](frameworks.md) | 统一组织游戏的基础模块与业务结构 | 2 |
| [数据库与本地存储](storage.md) | 离线数据、SQL、事务和结构迁移 | 1 |
| [自动化测试](testing.md) | 测试组织、断言、Mock 和集成验证 | 2 |
| [文件与文档](files.md) | 文件选择、Excel、PDF 与导入导出 | 1 |
| [旧项目维护与迁移](legacy.md) | 已归档、已弃用或需重点评估的历史方案 | 2 |

## 常用路线

- **搭建游戏基础模块**：[异步](async.md) → [依赖注入](architecture.md) → [配置](configuration.md)。
- **构建更新管线**：[资源管理](assets.md) → [代码热更新](hot-update.md)。
- **开发联网与 UI**：[联网](networking.md) → [序列化](serialization.md) → [UI](ui.md)。
- **开发配套 C# 服务**：[.NET 服务与工具](dotnet.md)。

## 官方基础能力

这些是系统或框架入口，单独列出，不计入第三方库数量。

- [Unity 包文档](https://docs.unity3d.com/Manual/PackagesList.html)：Addressables、Input System、Cinemachine、Test Framework 等官方包。

## 阅读说明

Star 是核验时的仓库快照。`近期有提交` 只表示默认分支一年内有提交；`更新较久` 不等于已弃用。具体状态与选型提醒见模块页。
