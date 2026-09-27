# Java · 自动化测试

[← Java 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

测试组织、断言、Mock 和集成验证。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [JUnit](#junit) | Java 自动化测试平台与测试编程模型 | 7,059 | 近期有提交 |
| [Mockito](#mockito) | Mock、Stub 与交互验证 | 15,457 | 近期有提交 |
| [Testcontainers](#testcontainers) | 启动真实数据库等容器做集成测试 | 8,742 | 近期有提交 |
| [Awaitility](#awaitility) | 等待异步条件的测试 DSL | 4,027 | 近期有提交 |
| [WireMock](#wiremock) | 模拟 HTTP 服务与故障响应 | 7,382 | 近期有提交 |

## 生态补充 · 速查

GitHub Star 低于 3,000，但有包平台使用量或其他框架官方集成依据；具体来源见条目。

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [AssertJ](#assertj) | 链式 Java 断言 | 2,847 | 近期有提交 |

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

## AssertJ

**适合**：需要清晰表达集合和对象断言的测试。

**选型提醒**：可与 JUnit 配合，无需替换测试运行器。

[源码](https://github.com/assertj/assertj) · [官方文档](https://github.com/assertj/assertj#readme) · [安装入口](https://github.com/assertj/assertj#readme)

**补充依据**：Spring Boot 官方测试文档说明 spring-boot-starter-test 包含 AssertJ。 [核验来源](https://docs.spring.io/spring-boot/reference/testing/)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/assertj/assertj/commit/7ca27151d9bc4ba86b7e789a327e2e6e96ae5ada) · 版本与许可证见上游仓库。</sub>

## Awaitility

**适合**：验证最终一致性和异步任务完成。

**选型提醒**：设置合理超时，避免用轮询掩盖真实竞态问题。

[源码](https://github.com/awaitility/awaitility) · [官方文档](https://github.com/awaitility/awaitility#readme) · [安装入口](https://github.com/awaitility/awaitility#readme)

<sub>默认分支最近提交：2026-04-17 · [近期有提交](https://github.com/awaitility/awaitility/commit/4fc23ccbd610ec16d14c2e7728e0593bffa6ac64) · 版本与许可证见上游仓库。</sub>

## WireMock

**适合**：接口集成测试、超时和异常场景验证。

**选型提醒**：维护契约与真实服务一致；不要仅靠 Mock 证明端到端正确。

[源码](https://github.com/wiremock/wiremock) · [官方文档](https://github.com/wiremock/wiremock#readme) · [安装入口](https://github.com/wiremock/wiremock#readme)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/wiremock/wiremock/commit/d44aabbd754d95351fb58245ba95ad8325905efa) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Java](README.md) · [查看调研记录](../research/README.md)
