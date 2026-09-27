# Go · 认证、权限与凭据

[← Go 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

登录凭据、Token 和服务访问控制。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [golang-jwt](#golang-jwt) | JWT 签发、解析与校验 | 9,228 | 近期有提交 |
| [Casbin](#casbin) | RBAC、ABAC 等访问控制模型 | 20,406 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## golang-jwt

**适合**：服务端处理 JWT 凭据。

**选型提醒**：必须限制算法并校验签发者、受众与有效期。

[源码](https://github.com/golang-jwt/jwt) · [官方文档](https://golang-jwt.github.io/jwt/usage/create/) · [安装入口](https://github.com/golang-jwt/jwt#installation-guidelines)

<sub>默认分支最近提交：2026-09-14 · [近期有提交](https://github.com/golang-jwt/jwt/commit/73c870b18e68b6e654b2b03f485aa3c9fab32cea) · 版本与许可证见上游仓库。</sub>

## Casbin

**适合**：角色权限、资源权限与策略管理。

**选型提醒**：它处理授权；身份认证和业务数据过滤仍需单独设计。

[源码](https://github.com/apache/casbin) · [官方文档](https://github.com/apache/casbin#readme) · [安装入口](https://github.com/apache/casbin#installation)

<sub>默认分支最近提交：2026-09-11 · [近期有提交](https://github.com/apache/casbin/commit/524f3f2dc9baef696d748db491d49b3055d359d1) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Go](README.md) · [查看调研记录](../research/README.md)
