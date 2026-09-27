# Objective-C · 旧项目维护与迁移

[← Objective-C 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

> 本页用于识别旧依赖和安排迁移。已归档、已弃用与长期低频更新分别标注；这些条目不进入新项目速查路线。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Masonry](#masonry) | Objective-C Auto Layout 链式约束 | 18,125 | 更新较久 |
| [MBProgressHUD](#mbprogresshud) | 加载提示与轻量 HUD | 15,914 | 更新较久 |
| [AFNetworking](#afnetworking) | 历史主流 Objective-C 网络封装 | 33,371 | 已归档 |
| [YYKit](#yykit) | 图片、文本、缓存与模型等工具集合 | 13,965 | 更新较久 |
| [YYModel](#yymodel) | JSON 与 Objective-C 模型互转 | 4,345 | 更新较久 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Masonry

**适合**：维护已有 Masonry 的 UIKit 页面。

**选型提醒**：上游长期低频更新；新模块可评估原生 NSLayoutAnchor。

[源码](https://github.com/SnapKit/Masonry) · [官方文档](https://github.com/SnapKit/Masonry#readme) · [安装入口](https://github.com/SnapKit/Masonry#installation)

<sub>默认分支最近提交：2017-09-28 · [更新较久](https://github.com/SnapKit/Masonry/commit/8bd77ea92bbe995e14c454f821200b222e5a8804) · 版本与许可证见上游仓库。</sub>

## MBProgressHUD

**适合**：维护已有 HUD 交互的应用。

**选型提醒**：上游更新较久；避免用阻塞式加载提示覆盖所有业务操作。

[源码](https://github.com/jdg/MBProgressHUD) · [官方文档](https://github.com/jdg/MBProgressHUD#readme) · [安装入口](https://github.com/jdg/MBProgressHUD#readme)

<sub>默认分支最近提交：2024-05-10 · [更新较久](https://github.com/jdg/MBProgressHUD/commit/4a7c5f3e53cdea77c5dcb8578c2ee5acacdf6781) · 版本与许可证见上游仓库。</sub>

## AFNetworking

**适合**：理解和维护既有 AFNetworking 代码。

**选型提醒**：官方已弃用并归档；新项目使用 NSURLSession 或 Swift 的 Alamofire。

[源码](https://github.com/AFNetworking/AFNetworking) · [官方文档](https://github.com/AFNetworking/AFNetworking#readme) · [安装入口](https://github.com/AFNetworking/AFNetworking#installation)

<sub>默认分支最近提交：2023-01-17 · [已归档](https://github.com/AFNetworking/AFNetworking/commit/d9f589cc2c1fe9d55eb5eea00558010afea7a41e) · 版本与许可证见上游仓库。</sub>

## YYKit

**适合**：维护使用 YY 系列组件的旧工程。

**选型提醒**：长期低频更新；不要为单个工具引入整套组件。

[源码](https://github.com/ibireme/YYKit) · [官方文档](https://github.com/ibireme/YYKit#readme) · [安装入口](https://github.com/ibireme/YYKit#installation)

<sub>默认分支最近提交：2017-08-06 · [更新较久](https://github.com/ibireme/YYKit/commit/4e1bd1cfcdb3331244b219cbd37cc9b1ccb62b7a) · 版本与许可证见上游仓库。</sub>

## YYModel

**适合**：维护已有模型映射代码。

**选型提醒**：上游长期未更新；必须自行验证现代工具链和边界数据。

[源码](https://github.com/ibireme/YYModel) · [官方文档](https://github.com/ibireme/YYModel#readme) · [安装入口](https://github.com/ibireme/YYModel#installation)

<sub>默认分支最近提交：2017-08-06 · [更新较久](https://github.com/ibireme/YYModel/commit/1230e605c1abdcd34bf0adb371d89783ff39a856) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Objective-C](README.md) · [查看调研记录](../research/README.md)
