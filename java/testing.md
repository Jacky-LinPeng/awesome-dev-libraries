# Java · 自动化测试

[← Java 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

测试组织、断言、Mock 和集成验证。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [JUnit](#junit) | Java 自动化测试平台与测试编程模型 | 7,059 | 近期有提交 |
| [Mockito](#mockito) | Mock、Stub 与交互验证 | 15,457 | 近期有提交 |
| [Testcontainers](#testcontainers) | 启动真实数据库等容器做集成测试 | 8,742 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## JUnit

**适合**：Java 工程的单元与集成测试。

**选型提醒**：按发行版核对 JDK 和构建插件兼容性。

[源码](https://github.com/junit-team/junit-framework) · [官方文档](https://docs.junit.org) · [安装入口](https://github.com/junit-team/junit-framework#readme)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/junit-team/junit-framework/commit/6c8ca116941611df2d4e2e8319ab8cb3e520afe7) · 版本与许可证见上游仓库。</sub>

## Mockito

**适合**：隔离服务依赖的 Java 单元测试。

**选型提醒**：优先断言结果，避免把测试写成实现细节的副本。

[源码](https://github.com/mockito/mockito) · [官方文档](https://javadoc.io/doc/org.mockito/mockito-core/latest/org.mockito/org/mockito/Mockito.html) · [安装入口](https://github.com/mockito/mockito#readme)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/mockito/mockito/commit/116a4d6231dc35f90543060af41dcde00fe4e2ae) · 版本与许可证见上游仓库。</sub>

## Testcontainers

**适合**：验证 SQL、缓存与外部服务交互。

**选型提醒**：测试环境需要受支持的容器运行时，启动成本高于纯单元测试。

[源码](https://github.com/testcontainers/testcontainers-java) · [官方文档](https://java.testcontainers.org) · [安装入口](https://github.com/testcontainers/testcontainers-java#readme)

<sub>默认分支最近提交：2026-09-09 · [近期有提交](https://github.com/testcontainers/testcontainers-java/commit/8e549514e3f01c57d70546fbb8599d138f3903e5) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Java](README.md) · [查看调研记录](../research/README.md)
