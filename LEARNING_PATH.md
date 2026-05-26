# 学习路径｜Learning Path

DataForge Academy 的学习路径按照“基础能力 → 数据开发 → 数仓建模 → 大数据实时链路 → OLAP 优化 → 数据产品与求职表达”逐层展开。

## 总体能力地图

```text
Level 0：学习方法与工程习惯
Level 1：Python / SQL / 数据库 / Linux / Docker 基础
Level 2：ETL、数据清洗、数据质量、任务调度
Level 3：数据仓库建模、指标体系、ODS/DWD/DWS/ADS
Level 4：Kafka、Flink、CDC、实时计算
Level 5：StarRocks / Doris / ClickHouse 等 OLAP 引擎
Level 6：查询优化、物化视图、分区分桶、Profile 分析
Level 7：数据看板、AI 自动报告、数据产品化
Level 8：简历、面试、作品集、课程化输出
```

## 路径 1：Data Foundation｜数据基础

适合：零基础、基础不扎实、想补齐基本功的人。

### 核心知识点

- Python 基础语法
- 函数、异常处理、日志
- pandas 数据处理
- CSV / Excel / JSON 文件处理
- SQL 基础查询
- JOIN、GROUP BY、窗口函数
- MySQL / PostgreSQL 基础
- Linux 常用命令
- Docker 和 Docker Compose
- Git 与 GitHub 工作流

### 输出目标

- Python 数据生成器
- Excel / CSV 清洗脚本
- 30–50 条业务 SQL
- MySQL 业务库 demo
- Linux + Docker 部署记录

## 路径 2：ETL Engineer｜ETL 工程师

适合：准备做 ETL、数据开发、数据同步方向的人。

### 核心知识点

- Extract / Transform / Load
- 批处理数据同步
- 增量同步
- 数据清洗
- 字段映射
- 数据质量校验
- 异常数据处理
- 日志记录
- 任务调度
- DataX / Airflow / DolphinScheduler，可后续扩展

### 输出目标

- CSV / Excel → MySQL ETL 项目
- MySQL → StarRocks 批量同步项目
- 数据质量校验脚本
- ETL 运行日志和错误报告

## 路径 3：Data Warehouse｜数据仓库

适合：想做数据仓库、BI、指标体系、数据产品的人。

### 核心知识点

- OLTP vs OLAP
- 事实表和维度表
- 星型模型和雪花模型
- ODS / DWD / DWS / ADS 分层
- 明细表、宽表、汇总表
- 指标口径设计
- 数据血缘
- 数据质量
- 维度建模

### 输出目标

- 电商数仓分层设计
- 指标口径文档
- DWD 订单明细宽表
- DWS 商品/渠道/用户汇总表
- ADS 看板应用表

## 路径 4：Big Data Engineer｜大数据工程师

适合：想进入大数据平台、实时计算、湖仓方向的人。

### 核心知识点

- Kafka 基础
- Flink 基础
- Flink SQL
- Flink CDC
- Spark 基础，后续扩展
- Hive / Iceberg / Hudi / Delta，后续扩展
- 分布式系统基础
- 集群部署与监控

### 输出目标

- Kafka 行为日志链路
- Flink Streaming 实时处理
- Flink CDC 同步 MySQL binlog
- 实时 PV / UV / 漏斗指标

## 路径 5：Realtime Warehouse｜实时数仓

适合：实时数仓工程师、数据平台工程师、OLAP 分析方向。

### 核心知识点

- 实时数仓架构
- Lambda / Kappa 架构
- CDC 实时同步
- Kafka 实时日志
- Flink 实时计算
- StarRocks / Doris 实时 OLAP
- 主键模型与 Upsert
- 实时指标口径
- 延迟、乱序、重复数据处理

### 输出目标

- MySQL → Flink CDC → StarRocks 链路
- Kafka → Flink → StarRocks 链路
- 实时订单状态更新
- 实时 GMV、PV、UV、转化漏斗

## 路径 6：OLAP Engineer｜OLAP 优化

适合：想深入 StarRocks / Doris / ClickHouse 等分析数据库的人。

### 核心知识点

- MPP 架构
- 列式存储
- FE / BE 架构
- 分区与分桶
- Duplicate Key / Aggregate Key / Primary Key
- 物化视图
- Bloom Filter / Bitmap / HLL
- EXPLAIN
- Query Profile
- Join 优化
- 数据倾斜
- 慢查询排查

### 输出目标

- 5 个以上查询优化案例
- 优化前后耗时对比
- Profile 分析文档
- 表模型选型文档

## 路径 7：AI Data Product｜AI 数据产品

适合：数据产品经理、AI 产品经理、想做 AI 数据工具的人。

### 核心知识点

- 数据看板设计
- 指标解释
- 自动报告生成
- LLM API 调用
- 结构化输出
- 数据问答
- AI 经营日报
- 数据 Agent 雏形

### 输出目标

- Streamlit 数据看板
- AI 自动经营日报
- SQL 结果自动解释
- 面向业务方的数据分析报告

## 路径 8：Career Interview｜职业与面试

适合：准备求职、转行、实习、跳槽的人。

### 核心知识点

- 简历项目包装
- 项目讲解方法
- 数据工程面试题
- SQL 面试题
- 数仓建模题
- StarRocks / Doris 面试题
- Flink / Kafka 场景题
- 项目复盘与技术表达

### 输出目标

- 简历项目描述
- 5 分钟项目介绍
- 15 分钟项目深讲
- 面试问答库
- GitHub 作品集说明

## 建议学习顺序

### 入门版

```text
Data Foundation → ETL Engineer → Data Warehouse → Career Interview
```

### 数据工程求职版

```text
Data Foundation → ETL Engineer → Data Warehouse → Big Data Engineer → Career Interview
```

### 实时数仓版

```text
Data Foundation → Data Warehouse → Big Data Engineer → Realtime Warehouse → OLAP Engineer → Career Interview
```

### AI 数据产品版

```text
Data Foundation → Data Warehouse → AI Data Product → Career Interview
```

### 全栈数据工程版

```text
Data Foundation → ETL Engineer → Data Warehouse → Big Data Engineer → Realtime Warehouse → OLAP Engineer → AI Data Product → Career Interview
```
