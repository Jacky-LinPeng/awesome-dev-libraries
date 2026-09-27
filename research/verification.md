# 扩充版检查记录

[← 调研说明](README.md) · [导航首页](../README.md)

检查日期：**2026-09-27**。

| 检查项 | 结果 |
|---|---|
| 分类与计数 | 7 种语言；241 个独立仓库、242 个导航条目 |
| 分区 | 198 个高 Star 入口、26 个生态补充、18 个历史条目 |
| 热度条件 | 高 Star 区均至少 3,000 Star；补充区至少 1,000 Star 且逐项附依据 |
| 维护状态 | 全部条目有默认分支提交日期；已归档项目均在历史页；维护公告另行标注 |
| 补充证据 | 20 项 pub.dev 代表包指标、6 项其他框架官方依赖或集成文档 |
| 数值来源 | 每项记录 Star 来源、核验时间；多包仓库明确计数范围 |
| 内部导航 | Markdown 文件路径与章节锚点检查通过 |
| 安装章节 | 从上游 README 提取的 122 个安装锚点均在对应页面找到 |
| 文档与包链接 | 检查 158 个独立文档、包、SDK 与指标 URL；156 个 HTTP 200，2 个访问限制见下方 |
| 阅读排版 | 渲染检查扩充版首页和 Dart 状态管理页；修正相邻速查表之间的空行，确认分区标题正常 |
| 变更检查 | git diff --check 通过 |

## 两个访问限制

以下官方文档入口的命令行访问返回 HTTP 403；网页检索可确认入口存在，但正文需要 JavaScript 渲染。这两项不计作命令行连通检查通过。

- [Kingfisher 官方文档](https://swiftpackageindex.com/onevcat/kingfisher/master/documentation/kingfisher)
- [TCA 官方入门文档](https://swiftpackageindex.com/pointfreeco/swift-composable-architecture/main/documentation/composablearchitecture/gettingstarted)

相关条目同时保留源码与 README 安装入口。开发分支文档可能变化，接入时应切换到选定发行版。

## 检查边界

检查对象是导航内容、公开来源、链接和阅读排版；没有逐一安装、编译或测试这些库，也没有把 Star、下载量和提交频率当成代码质量结论。外部页面可能变化，GitHub 原生页面的最终排版以发布后的实际效果为准。
