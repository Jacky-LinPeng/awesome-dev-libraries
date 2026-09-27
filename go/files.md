# Go · 文件与文档

[← Go 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

文件选择、Excel、PDF 与导入导出。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Excelize](#excelize) | Excel 文件读写、图表与流式处理 | 20,941 | 近期有提交 |
| [fsnotify](#fsnotify) | 跨平台文件系统变更通知 | 10,783 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Excelize

**适合**：后台导入导出和报表生成。

**选型提醒**：大表格使用流式方案并设置输入规模限制。

[源码](https://github.com/qax-os/excelize) · [官方文档](https://github.com/qax-os/excelize#readme) · [安装入口](https://github.com/qax-os/excelize#installation)

<sub>默认分支最近提交：2026-09-27 · [近期有提交](https://github.com/qax-os/excelize/commit/e81f05008b33232151a58f06474fad5f70c4d060) · 版本与许可证见上游仓库。</sub>

## fsnotify

**适合**：配置重载、文件监视与开发工具。

**选型提醒**：不同系统的事件细节不同，需要防抖和重新扫描策略。

[源码](https://github.com/fsnotify/fsnotify) · [官方文档](https://github.com/fsnotify/fsnotify#readme) · [安装入口](https://github.com/fsnotify/fsnotify#readme)

<sub>默认分支最近提交：2026-05-11 · [近期有提交](https://github.com/fsnotify/fsnotify/commit/20b1e15ef3c70caeb37ea2bd184f48ef8382669e) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Go](README.md) · [查看调研记录](../research/README.md)
