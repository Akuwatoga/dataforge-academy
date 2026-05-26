# DataForge Academy｜数据工坊学院

> 从数据基础到实时数仓，从项目实战到职业成长。

DataForge Academy 是一个面向 **数据工程、ETL、大数据、实时数仓、OLAP 分析、数据产品与 AI 数据应用** 的开源项目制学习体系。

本项目不是单点技术教程，而是一个长期建设的数据能力训练场：学习者可以按自己的职业方向选择不同路径，从 Python、SQL、数据库、Linux、Docker 基础出发，逐步进入 ETL、数据仓库、Kafka、Flink、StarRocks/Doris、实时指标、可视化看板、AI 自动报告与面试项目包装。

## 项目适合谁

- 想入门数据岗位的学生或转行者
- 想补齐 Python、SQL、数据库基础的学习者
- 准备做 ETL 工程师、数据工程师、大数据工程师的人
- 想学习实时数仓、Flink CDC、Kafka、StarRocks/Doris 的人
- 想用项目制方式准备简历和面试的人
- 想把数据工程能力和 AI 数据应用结合的人

## 学习路径总览

| 路径 | 适合人群 | 核心内容 |
|---|---|---|
| Data Foundation | 零基础/基础不扎实 | Python、SQL、MySQL、Linux、Docker |
| ETL Engineer | ETL/数据开发入门 | 数据抽取、清洗、同步、调度、数据质量 |
| Data Warehouse | 数仓方向 | ODS/DWD/DWS/ADS、事实表、维度表、指标体系 |
| Big Data Engineer | 大数据工程 | Kafka、Flink、Spark、Hive、湖仓、集群基础 |
| Realtime Warehouse | 实时数仓 | Flink CDC、Kafka、StarRocks/Doris、实时指标 |
| OLAP Engineer | OLAP 优化 | 表模型、分区分桶、物化视图、Profile、查询优化 |
| AI Data Product | AI 数据产品 | 自动报表、数据问答、AI 经营日报、数据 Agent |
| Career Interview | 求职面试 | 简历项目、面试题、项目讲解、场景题 |

## 项目核心主线

主线项目暂定为：**面向电商业务的端到端数据平台项目**。

覆盖链路：

```text
Python 造数 / MySQL 业务库 / Kafka 行为日志
        ↓
ETL / Flink CDC / Flink Streaming
        ↓
StarRocks / Doris OLAP 数仓
        ↓
ODS / DWD / DWS / ADS 分层建模
        ↓
SQL 指标分析 / 查询优化 / 物化视图
        ↓
数据看板 / AI 自动经营日报 / 面试项目包装
```

## 仓库结构

```text
dataforge-academy/
├── COURSE_INTRO.md          # 课程与项目介绍
├── LEARNING_PATH.md         # 完整学习路径
├── ROADMAP.md               # 长期路线图
├── RECORDING_PLAN.md        # 每日录制与内容输出计划
├── tracks/                  # 分方向学习路径
├── projects/                # 项目制实战模块
├── docs/                    # 技术文档与讲义
├── daily/                   # 每日/每周学习记录
├── scripts/                 # Python 脚本
├── sql/                     # MySQL / StarRocks / Flink SQL
├── docker/                  # Docker Compose 与部署文件
├── dashboard/               # 看板与 AI 报表
├── benchmark/               # 性能优化案例
├── interview/               # 简历与面试材料
└── assets/                  # 架构图、截图、课程素材
```

## 当前阶段目标

第一阶段先完成：

1. 明确课程定位与学习路径。
2. 初始化 GitHub 仓库结构。
3. 设计数据工程能力地图。
4. 确定第一个主线项目：电商实时数据平台。
5. 开始每日录制与 Git commit。

## 输出原则

每天至少保留四类输出：

1. 一个可运行的小功能、SQL 或配置。
2. 一个 Git commit。
3. 一份学习记录。
4. 一段可剪辑成课程的视频素材。

## Slogan

**从数据基础到实时数仓，从项目实战到职业成长。**
