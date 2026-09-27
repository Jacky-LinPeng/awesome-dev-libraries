# Go · 旧项目维护与迁移

[← Go 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

> 本页用于识别旧依赖和安排迁移。已归档、已弃用与长期低频更新分别标注；这些条目不进入新项目速查路线。


## 历史维护 · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [旧 GoMock](#旧-gomock) | 历史 Go Mock 代码生成工具 | 9,330 | 已归档 |
| [Wire](#wire) | Go 编译期依赖注入生成 | 14,397 | 已归档 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## 旧 GoMock

**适合**：迁移已有 github.com/golang/mock 依赖。

**选型提醒**：官方已停止维护，按 README 指向的维护分支迁移。

[源码](https://github.com/golang/mock) · [官方文档](https://github.com/golang/mock#readme) · [安装入口](https://github.com/golang/mock#installation)

<sub>默认分支最近提交：2023-06-27 · [已归档](https://github.com/golang/mock/commit/674a1c4a938e7b453416052327872571656801b7) · 版本与许可证见上游仓库。</sub>

## Wire

**适合**：维护已有 Wire 注入代码。

**选型提醒**：需要核对上游归档与维护公告，新项目谨慎选用。

[源码](https://github.com/google/wire) · [官方文档](https://github.com/google/wire#readme) · [安装入口](https://github.com/google/wire#installing)

<sub>默认分支最近提交：2025-08-22 · [已归档](https://github.com/google/wire/commit/9c25c9016f6825302537c4efdd5e897976f9c826) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Go](README.md) · [查看调研记录](../research/README.md)
