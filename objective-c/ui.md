# Objective-C · UI、布局与动效

[← Objective-C 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

页面布局、图表和界面视觉效果。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [MJRefresh](#mjrefresh) | 下拉刷新与上拉加载 | 13,802 | 更新较久 |
| [SVProgressHUD](#svprogresshud) | 加载与状态提示 HUD | 12,438 | 近期有提交 |
| [JXCategoryView](#jxcategoryview) | 分类标签与分页容器辅助 | 6,151 | 更新较久 |
| [JXPagingView](#jxpagingview) | 嵌套列表与分页联动滚动 | 3,049 | 更新较久 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## MJRefresh

**适合**：UIKit 列表的刷新交互。

**选型提醒**：分页状态、请求取消和无更多数据状态仍由业务管理。

[源码](https://github.com/CoderMJLee/MJRefresh) · [官方文档](https://github.com/CoderMJLee/MJRefresh#readme) · [安装入口](https://github.com/CoderMJLee/MJRefresh#readme)

<sub>默认分支最近提交：2024-11-28 · [更新较久](https://github.com/CoderMJLee/MJRefresh/commit/5647d82cd7e0de8c59980c6cb2afff173978f481) · 版本与许可证见上游仓库。</sub>

## SVProgressHUD

**适合**：已有 UIKit 界面的短时操作反馈。

**选型提醒**：不适合长流程的唯一进度反馈，避免过度阻塞交互。

[源码](https://github.com/SVProgressHUD/SVProgressHUD) · [官方文档](https://github.com/SVProgressHUD/SVProgressHUD#readme) · [安装入口](https://github.com/SVProgressHUD/SVProgressHUD#installation)

<sub>默认分支最近提交：2026-02-27 · [近期有提交](https://github.com/SVProgressHUD/SVProgressHUD/commit/ece669b5010693024572bcf7bfd5ebede904859f) · 版本与许可证见上游仓库。</sub>

## JXCategoryView

**适合**：频道页、分段内容与标签导航。

**选型提醒**：与分页容器的滚动协调需要按页面组合验证。

[源码](https://github.com/pujiaxin33/JXCategoryView) · [官方文档](https://github.com/pujiaxin33/JXCategoryView#readme) · [安装入口](https://github.com/pujiaxin33/JXCategoryView#安装)

<sub>默认分支最近提交：2024-07-10 · [更新较久](https://github.com/pujiaxin33/JXCategoryView/commit/d2bcedd9f12a4241666b87ad6d85a45395a34a6a) · 版本与许可证见上游仓库。</sub>

## JXPagingView

**适合**：个人主页、吸顶标签与多列表页面。

**选型提醒**：复杂嵌套滚动容易与手势冲突，需要真机验证。

[源码](https://github.com/pujiaxin33/JXPagingView) · [官方文档](https://github.com/pujiaxin33/JXPagingView#readme) · [安装入口](https://github.com/pujiaxin33/JXPagingView#安装)

<sub>默认分支最近提交：2025-04-14 · [更新较久](https://github.com/pujiaxin33/JXPagingView/commit/8aa5663720ebfab0c4df41cfca04b113f832c5b2) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Objective-C](README.md) · [查看调研记录](../research/README.md)
