# Swift · 图片加载与缓存

[← Swift 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

常规图片加载先比较 Kingfisher；需要定制图片处理管线时再深入看 Nuke。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Kingfisher](#kingfisher) | 远程图片加载、处理与内存/磁盘缓存 | 24,406 | 近期有提交 |
| [Nuke](#nuke) | 可定制图片管线、预取与 SwiftUI 图片组件 | 8,671 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Kingfisher

**适合**：头像、商品列表、信息流等常规图片场景。

**选型提醒**：按场景设置缓存上限，并使用降采样处理大图。

[源码](https://github.com/onevcat/Kingfisher) · [官方文档](https://swiftpackageindex.com/onevcat/kingfisher/master/documentation/kingfisher) · [安装入口](https://github.com/onevcat/Kingfisher#installation)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/onevcat/Kingfisher/commit/a821446e559d74f67d93dfcab86bcd370e177bf0) · 版本与许可证见上游仓库。</sub>

## Nuke

**适合**：需要控制图片处理流程和加载优先级。

**选型提醒**：与 Kingfisher 按需求择一，避免重复维护两套图片缓存。

[源码](https://github.com/kean/Nuke) · [官方文档](https://kean-docs.github.io/nuke/documentation/nuke/getting-started/) · [安装入口](https://github.com/kean/Nuke#installation)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/kean/Nuke/commit/61f8aebad96bd27508cb92f9e9fd83520c37a1f3) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Swift](README.md) · [查看调研记录](../research/README.md)
