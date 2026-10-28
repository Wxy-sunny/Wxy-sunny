<!-- README.md · github.com/Wxy-sunny -->

# Hi there 👋, I'm Wxy-sunny

🧑‍💻 3 年+ .NET 全栈开发｜制造业 MES / IOT × 医疗信息化双赛道  
🛠️ 主栈：C# · ASP.NET Core · SQL Server / Oracle · Vue 3 · TypeScript  
🚀 当前主线：从零构建并上线 Asset Management System（资产管理系统）  
📫 wxy200307@outlook.com

---

## 🧠 About Me

3 年+ .NET 后端开发经验，覆盖制造业 MES/IOT 及医疗信息化双领域，具备 AI 编码实践能力，
主导完成从 0 到 1 的资产管理系统开发，并实现基于 Docker 的云服务器网站部署。
能全栈开发，技术栈涵盖 C#、ASP.NET Core、SQL Server、Oracle 及 Vue3、Redis，
具备独立承担模块开发与上线交付能力。

---

## 🏗️ Current Project · Asset Management System

一个覆盖资产全生命周期的 .NET 10 + Vue 3 全栈管理平台：台账建档、折旧核算、
分类体系、权限控制、资料归档、消息通知，同一套代码跨库部署。

🔗 **github.com/Wxy-sunny/AssetManagement**

```
Backend  : ASP.NET Core Web API · .NET 10 · SqlSugar (CodeFirst)
Frontend : Vue 3 · TypeScript · Vite · Pinia · Element Plus
Data     : SQLite（内置）/ SQL Server（可选），一套代码跨库兼容
Infra    : Docker Compose 一键编排 · nginx 反代 · Redis 热点缓存（异常自动降级内存）
Security : BCrypt 密码哈希 · JWT 鉴权 · 登录防爆破 · 速率限制 · 安全响应头
```

**✅ 已交付**
- 资产台账：登记 / 批量维护 / 多条件检索 / 状态流转
- 折旧统计：按年限与残值自动计算，一键重算 + 净值分布图表
- 分类体系：多级分类树，分类与资产双向绑定、按类归集统计
- 权限管理：用户 / 角色 / 部门三级，21 项功能权限，无权限入口前端隐藏
- 资料管理：合同、发票、说明书附件上传 / 在线预览 / 批量清理
- 消息通知：站内公告与个人消息，发布撤回 + 已读状态跟踪
- 部署交付：Docker Compose 一键起站，登录框布局与四套主题（含暗黑）可切换

**🚧 进行中**
领用 / 归还 / 维修 / 报废全流程闭环 · 盘点与报表导出 · ECharts 仪表盘

---

## 🏥 Featured · HealthVcan 康复信息平台　2022.07 – 2025.08

公司核心产品，落地医院、高校及科研场景，依托 ICF 功能地形图实现康复评估、
治疗、质控一体化管理。

- **HIS / EMR 对接：** 主导 WebService 接口开发，患者主索引与诊疗数据实时同步，支撑临床业务闭环。
- **业务开发：** 负责页面与后端功能迭代，覆盖医院、教学科研等多场景模块。
- **生产运维：** .NET Framework 4.5 / ASP.NET MVC + SQL Server，IIS 部署、监控与维护，保障区域三级康复网络稳定运行。

🔗 公司介绍：海司唯尔官网 · 关于我们

---

## 🏭 Manufacturing · 立讯精密热传科技 MES / IOT

- **看板与接口：** 12 个生产看板接口按时交付，支撑车间实时数据展示。
- **设备接入：** 16 台采集设备接入 Kafka 链路，消费者幂等设计，设备数据零重复落库。
- **性能调优：** PDA 扫码并发场景 SQL + 索引重构，慢查询从秒级降到毫秒级。
- **调度治理：** 13 类业务定时任务（Quartz 18 Job）稳定运行，异常重试 + 告警闭环。
- **交付节奏：** 20+ 需求按期上线，Oracle 大表批量 Upsert 用 MERGE 落地。

---

## 🛠️ Tech Stack

| 领域 | 技术 |
| --- | --- |
| Backend | C# · .NET Framework 4.5 · ASP.NET MVC · .NET 8/10 · ASP.NET Core Web API · SqlSugar · EF Core |
| 前端 | Vue 3 · TypeScript · Vite · Pinia · Element Plus · Axios · ECharts |
| 数据 | SQL Server · Oracle · SQLite · Redis（缓存 / 分布式锁 / 降级） |
| 集成与运维 | Kafka · WebService / HIS 对接 · Docker · Docker Compose · nginx · IIS · Quartz |
| 工程化 | Git · AI 编码（方案生成 + 单测 / 边界补全，人工 Code Review 兜底） |

---

## 💡 Fun Fact

写 LINQ 的心情 ≈ 给资产编号的心情：都要优雅、不能重复、查得快。

⭐️ From Wxy-sunny
