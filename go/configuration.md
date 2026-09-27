# Go · 配置与工具链

[← Go 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

应用配置、命令行或游戏策划表。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Viper](#viper) | 统一读取配置文件、环境变量等配置源 | 30,469 | 近期有提交 |
| [Cobra](#cobra) | 构建子命令、参数与帮助信息 | 44,659 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Viper

**适合**：多部署环境下的服务配置。

**选型提醒**：明确配置优先级，敏感值不要提交到仓库。

[源码](https://github.com/spf13/viper) · [官方文档](https://github.com/spf13/viper#readme) · [安装入口](https://github.com/spf13/viper#install)

<sub>默认分支最近提交：2025-10-15 · [近期有提交](https://github.com/spf13/viper/commit/528f7416c4b56a4948673984b190bf8713f0c3c4) · 版本与许可证见上游仓库。</sub>

## Cobra

**适合**：项目脚手架、运维工具和开发 CLI。

**选型提醒**：简单单命令工具可先使用标准库 flag。

[源码](https://github.com/spf13/cobra) · [官方文档](https://cobra.dev) · [安装入口](https://github.com/spf13/cobra#installing)

<sub>默认分支最近提交：2026-07-11 · [近期有提交](https://github.com/spf13/cobra/commit/adbc8813901bba65827259daa8e22ff94ec1f30e) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Go](README.md) · [查看调研记录](../research/README.md)
