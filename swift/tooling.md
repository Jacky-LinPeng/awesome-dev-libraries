# Swift · 日志、调试与工程质量

[← Swift 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

定位问题、分析性能和统一代码规范。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [SwiftLint](#swiftlint) | 检查 Swift 风格与部分易错写法 | 19,745 | 近期有提交 |
| [SwiftFormat](#swiftformat) | 自动格式化 Swift 代码 | 8,928 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## SwiftLint

**适合**：团队规范、提交检查和 CI。

**选型提醒**：是开发工具，不应作为业务运行时依赖。

[源码](https://github.com/realm/SwiftLint) · [官方文档](https://github.com/realm/SwiftLint#readme) · [安装入口](https://github.com/realm/SwiftLint#installation)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/realm/SwiftLint/commit/ec569260b2015e6a84a0f21eda3564482a6b4346) · 版本与许可证见上游仓库。</sub>

## SwiftFormat

**适合**：统一团队代码格式，减少格式争议。

**选型提醒**：与 SwiftLint 职责有交集，需统一规则避免相互改写。

[源码](https://github.com/nicklockwood/SwiftFormat) · [官方文档](https://github.com/nicklockwood/SwiftFormat#readme) · [安装入口](https://github.com/nicklockwood/SwiftFormat#how-do-i-install-it)

<sub>默认分支最近提交：2026-09-16 · [近期有提交](https://github.com/nicklockwood/SwiftFormat/commit/173d2cb252474cd8e8baeaf13636f5d565408ec9) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Swift](README.md) · [查看调研记录](../research/README.md)
