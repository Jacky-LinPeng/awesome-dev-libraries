# Java · 文件与文档

[← Java 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

文件选择、Excel、PDF 与导入导出。


## 生态补充 · 速查

GitHub Star 低于 3,000，但有包平台使用量或其他框架官方集成依据；具体来源见条目。

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Apache POI](#apache-poi) | Excel、Word 等 Office 文件处理 | 2,275 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Apache POI

**适合**：文档导入导出与表格处理。

**选型提醒**：大文件需评估流式 API、内存占用和格式兼容。

[源码](https://github.com/apache/poi) · [官方文档](https://github.com/apache/poi#readme) · [安装入口](https://github.com/apache/poi#getting-started)

**补充依据**：Apache Tika 官方格式文档说明 Office 解析器使用 Apache POI。 [核验来源](https://tika.apache.org/docs/4.0.x/formats.html)

<sub>默认分支最近提交：2026-09-24 · [近期有提交](https://github.com/apache/poi/commit/942d95d85b15d0dfdb3bc9ba1b4f273f277757c8) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Java](README.md) · [查看调研记录](../research/README.md)
