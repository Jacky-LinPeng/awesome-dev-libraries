# 首版检查记录

[← 调研说明](README.md) · [导航首页](../README.md)

检查日期：**2026-09-27**。

| 检查项 | 结果 |
|---|---|
| 分类 | 覆盖 7 种语言；语言内按业务模块拆分 |
| 热度门槛 | 131 个入口对应 130 个仓库，最低 3,003 Star |
| 选型与历史区分 | 118 个选型入口、13 个历史条目；已归档仓库均在历史页 |
| 数值来源 | 每个仓库均记录 Star 来源、核验时间和默认分支提交记录 |
| 内部导航 | Markdown 文件路径与章节锚点检查通过 |
| 安装章节 | 从上游 README 提取的 72 个安装锚点均在对应页面找到 |
| 文档与包链接 | 额外检查 93 个独立文档、包和 SDK 页面，91 个 HTTP 200；另 2 个见下方说明 |
| 阅读排版 | 本地渲染检查首页和 Go 数据库模块页，表格、标题和链接入口显示正常 |

## 两个访问限制

以下链接来自项目自己的 README，命令行访问返回 HTTP 403。通过网页检索可确认文档入口存在，但正文需要 JavaScript 渲染；这两项不计为命令行连通检查通过。

- [Kingfisher 官方文档](https://swiftpackageindex.com/onevcat/kingfisher/master/documentation/kingfisher)
- [TCA 官方入门文档](https://swiftpackageindex.com/pointfreeco/swift-composable-architecture/main/documentation/composablearchitecture/gettingstarted)

相应条目同时保留源码与 README 安装入口。上述文档来自开发分支，接入时应切换到所选发行版的文档。

## 检查边界

本次检查对象是导航内容、公开来源、链接和阅读排版，没有逐一安装、编译或测试这些库，也没有以提交频率代替代码质量评审。GitHub 原生页面的最终呈现以发布后的实际效果为准。
