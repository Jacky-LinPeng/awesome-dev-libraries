# Swift · UI、布局与动效

[← Swift 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

页面布局、图表和界面视觉效果。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [SnapKit](#snapkit) | 用 Swift DSL 编写 Auto Layout 约束 | 20,349 | 近期有提交 |
| [Lottie iOS](#lottie-ios) | 播放设计师导出的矢量动画 | 26,887 | 近期有提交 |
| [IQKeyboardManager](#iqkeyboardmanager) | 处理输入框被键盘遮挡与输入辅助条 | 16,629 | 近期有提交 |
| [Hero](#hero) | 视图控制器与元素转场动画 | 22,490 | 更新较久 |
| [SkeletonView](#skeletonview) | 为加载中的内容显示骨架屏 | 12,890 | 更新较久 |
| [SwiftMessages](#swiftmessages) | 消息条与自定义提示视图 | 7,548 | 更新较久 |
| [SwiftEntryKit](#swiftentrykit) | 弹窗、横幅和提示内容展示 | 6,750 | 更新较久 |
| [SwipeCellKit](#swipecellkit) | 列表单元格的滑动操作 | 6,281 | 更新较久 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## SnapKit

**适合**：以 UIKit 为主的页面布局。

**选型提醒**：适用于 Auto Layout；SwiftUI 页面通常不需要它。

[源码](https://github.com/SnapKit/SnapKit) · [官方文档](https://snapkit.github.io/SnapKit/docs/) · [安装入口](https://github.com/SnapKit/SnapKit#installation)

<sub>默认分支最近提交：2026-07-13 · [近期有提交](https://github.com/SnapKit/SnapKit/commit/250529bec615066185ff328984855101820fcbee) · 版本与许可证见上游仓库。</sub>

## Lottie iOS

**适合**：引导页、加载态、反馈动效。

**选型提醒**：先验证素材使用的 After Effects 特性是否受支持。

[源码](https://github.com/airbnb/lottie-ios) · [官方文档](https://github.com/airbnb/lottie-ios#readme) · [安装入口](https://github.com/airbnb/lottie-ios#installing-lottie)

<sub>默认分支最近提交：2026-09-19 · [近期有提交](https://github.com/airbnb/lottie-ios/commit/2c8608c6b5d6e3fc62168e321fe0a7c89aaa8693) · 版本与许可证见上游仓库。</sub>

## IQKeyboardManager

**适合**：表单密集的 UIKit 应用。

**选型提醒**：全局自动行为可能影响自定义页面，建议按页面验证。

[源码](https://github.com/hackiftekhar/IQKeyboardManager) · [官方文档](https://github.com/hackiftekhar/IQKeyboardManager#readme) · [安装入口](https://github.com/hackiftekhar/IQKeyboardManager#installation)

<sub>默认分支最近提交：2026-05-25 · [近期有提交](https://github.com/hackiftekhar/IQKeyboardManager/commit/0972dd6eded87c930fb6ad36b3c5ecd620f06894) · 版本与许可证见上游仓库。</sub>

## Hero

**适合**：复杂页面转场和共享元素动画。

**选型提醒**：需要配合视图层级与转场生命周期，先验证手势取消行为。

[源码](https://github.com/HeroTransitions/Hero) · [官方文档](https://github.com/HeroTransitions/Hero#readme) · [安装入口](https://github.com/HeroTransitions/Hero#installation)

<sub>默认分支最近提交：2025-01-23 · [更新较久](https://github.com/HeroTransitions/Hero/commit/d7a72e13b034599ff694e6907f770e6bcb83f59d) · 版本与许可证见上游仓库。</sub>

## SkeletonView

**适合**：列表、详情等异步内容页。

**选型提醒**：骨架屏不代替错误态与空状态；注意复用单元格状态恢复。

[源码](https://github.com/Juanpe/SkeletonView) · [官方文档](https://github.com/Juanpe/SkeletonView#readme) · [安装入口](https://github.com/Juanpe/SkeletonView#-installation)

<sub>默认分支最近提交：2024-04-18 · [更新较久](https://github.com/Juanpe/SkeletonView/commit/30c92f0992888e7b249e788405ac31e2103f5c69) · 版本与许可证见上游仓库。</sub>

## SwiftMessages

**适合**：顶部通知、表单反馈和轻提示。

**选型提醒**：统一业务提示层级，避免多个提示组件相互覆盖。

[源码](https://github.com/SwiftKickMobile/SwiftMessages) · [官方文档](https://github.com/SwiftKickMobile/SwiftMessages#readme) · [安装入口](https://github.com/SwiftKickMobile/SwiftMessages#installation)

<sub>默认分支最近提交：2025-09-03 · [更新较久](https://github.com/SwiftKickMobile/SwiftMessages/commit/c0ff6c65bfc00e6a707957cb7069988c5cde2a30) · 版本与许可证见上游仓库。</sub>

## SwiftEntryKit

**适合**：需要定制展示位置与交互的 UIKit 页面。

**选型提醒**：检查当前工具链兼容性；不要同时引入多个弹窗框架。

[源码](https://github.com/huri000/SwiftEntryKit) · [官方文档](https://github.com/huri000/SwiftEntryKit#readme) · [安装入口](https://github.com/huri000/SwiftEntryKit#example-project-installation)

<sub>默认分支最近提交：2021-10-17 · [更新较久](https://github.com/huri000/SwiftEntryKit/commit/5ad36cccf0c4b9fea32f4e9b17a8e38f07563ef0) · 版本与许可证见上游仓库。</sub>

## SwipeCellKit

**适合**：邮件式列表、删除和快捷动作。

**选型提醒**：先评估系统侧滑操作能否满足需求。

[源码](https://github.com/SwipeCellKit/SwipeCellKit) · [官方文档](https://github.com/SwipeCellKit/SwipeCellKit#readme) · [安装入口](https://github.com/SwipeCellKit/SwipeCellKit#installation)

<sub>默认分支最近提交：2019-12-13 · [更新较久](https://github.com/SwipeCellKit/SwipeCellKit/commit/6d632bdf1b7309505566b0248a00f61b67415a37) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Swift](README.md) · [查看调研记录](../research/README.md)
