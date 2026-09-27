# Dart · UI、布局与动效

[← Dart 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

页面布局、图表和界面视觉效果。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [flutter_staggered_grid_view](#flutter_staggered_grid_view) | 瀑布流与多种网格布局 | 3,217 | 更新较久 |
| [fl_chart](#fl_chart) | 折线、柱状、饼图等交互图表 | 7,579 | 近期有提交 |
| [flutter_screenutil](#flutter_screenutil) | 设计稿尺寸与字体适配辅助 | 4,020 | 更新较久 |

## 生态补充 · 速查

GitHub Star 低于 3,000，但有包平台使用量或其他框架官方集成依据；具体来源见条目。

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [flutter_slidable](#flutter_slidable) | 列表项滑动操作 | 2,853 | 近期有提交 |
| [Flutter Form Builder](#flutter-form-builder) | 表单字段、状态与验证组织 | 1,605 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## flutter_staggered_grid_view

**适合**：图片墙、卡片瀑布流和拼贴式列表。

**选型提醒**：结合懒加载和图片尺寸策略控制长列表开销。

[源码](https://github.com/letsar/flutter_staggered_grid_view) · [官方文档](https://github.com/letsar/flutter_staggered_grid_view#readme) · [安装入口](https://pub.dev/packages/flutter_staggered_grid_view/install)

<sub>默认分支最近提交：2023-07-30 · [更新较久](https://github.com/letsar/flutter_staggered_grid_view/commit/0bfd05f285a6ecf390a8927e6ad4e67f7a39979b) · 版本与许可证见上游仓库。</sub>

## fl_chart

**适合**：数据看板和业务统计。

**选型提醒**：先用真实数据量验证交互与绘制性能。

[源码](https://github.com/imaNNeo/fl_chart) · [官方文档](https://github.com/imaNNeo/fl_chart#readme) · [安装入口](https://pub.dev/packages/fl_chart/install)

<sub>默认分支最近提交：2026-09-17 · [近期有提交](https://github.com/imaNNeo/fl_chart/commit/0c4d2efc83b60a8a31d0508af34f0fe9f684cc5a) · 版本与许可证见上游仓库。</sub>

## flutter_screenutil

**适合**：以设计稿为基准的移动端界面。

**选型提醒**：不能代替响应式布局和系统字体缩放测试。

[源码](https://github.com/OpenFlutter/flutter_screenutil) · [官方文档](https://github.com/OpenFlutter/flutter_screenutil#readme) · [安装入口](https://github.com/OpenFlutter/flutter_screenutil#readme)

<sub>默认分支最近提交：2025-06-23 · [更新较久](https://github.com/OpenFlutter/flutter_screenutil/commit/65a9f0c031f8ecc11d2f5d6649f5030c676c1be8) · 版本与许可证见上游仓库。</sub>

## flutter_slidable

**适合**：消息、任务和邮件式列表。

**选型提醒**：滑动操作应同时提供可访问的替代入口。

[源码](https://github.com/letsar/flutter_slidable) · [官方文档](https://pub.dev/packages/flutter_slidable) · [安装入口](https://pub.dev/packages/flutter_slidable/install)

**补充依据**：pub.dev 的 flutter_slidable 包有 6,141 Likes、近 30 天 771,208 次下载，并标注 Flutter Favorite。 [核验来源](https://pub.dev/api/packages/flutter_slidable/metrics)

<sub>默认分支最近提交：2025-09-27 · [近期有提交](https://github.com/letsar/flutter_slidable/commit/0563760f9dcf22f5498a3126deec611af5604072) · 版本与许可证见上游仓库。</sub>

## Flutter Form Builder

**适合**：字段较多的录入与设置页面。

**选型提醒**：官方正在招募维护者；接入前检查维护响应。复杂校验和后端错误映射仍需自行设计。

[源码](https://github.com/flutter-form-builder-ecosystem/flutter_form_builder) · [官方文档](https://pub.dev/packages/flutter_form_builder) · [安装入口](https://pub.dev/packages/flutter_form_builder/install)

**补充依据**：pub.dev 的 flutter_form_builder 包有 2,804 Likes、近 30 天 73,028 次下载。 [核验来源](https://pub.dev/api/packages/flutter_form_builder/metrics)

<sub>默认分支最近提交：2026-08-15 · [近期有提交](https://github.com/flutter-form-builder-ecosystem/flutter_form_builder/commit/f8706f7c3877215d7927a9d43cbb6babc125fd70) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Dart](README.md) · [查看调研记录](../research/README.md)
