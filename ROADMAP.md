# Roadmap｜项目路线图

DataForge Academy 是一个长期建设项目，路线图分为四个阶段：项目初始化、基础能力建设、端到端数据平台实战、课程化与职业化。

## Phase 0：项目初始化

目标：完成仓库结构、课程定位、学习路径和输出机制设计。

### 任务

- [x] 创建 GitHub 仓库
- [x] 初始化 README
- [x] 编写课程介绍
- [x] 编写学习路径
- [ ] 编写录制计划
- [ ] 创建 tracks 目录
- [ ] 创建 projects 目录
- [ ] 创建 docs 目录
- [ ] 创建 daily 目录
- [ ] 创建 interview 目录

### 交付物

- README.md
- COURSE_INTRO.md
- LEARNING_PATH.md
- ROADMAP.md
- RECORDING_PLAN.md

## Phase 1：数据基础能力

目标：补齐 Python、SQL、数据库、Linux、Docker、Git 等基础能力。

### 任务

- [ ] Python 数据生成器
- [ ] pandas 数据清洗脚本
- [ ] MySQL 业务库设计
- [ ] 30–50 条电商业务 SQL
- [ ] Linux 常用命令记录
- [ ] Docker Compose 部署 MySQL
- [ ] GitHub 每日 commit 流程

### 交付物

- scripts/generate_users.py
- scripts/generate_products.py
- scripts/generate_orders.py
- scripts/generate_payments.py
- sql/mysql/*.sql
- docker/docker-compose.mysql.yml
- daily/week_01.md
- daily/week_02.md

## Phase 2：ETL 与数据仓库

目标：掌握批处理 ETL、数据质量、数仓分层、指标体系。

### 任务

- [ ] CSV / Excel → MySQL ETL
- [ ] MySQL → 分析库批量同步
- [ ] 数据质量校验
- [ ] ODS / DWD / DWS / ADS 分层设计
- [ ] 事实表和维度表设计
- [ ] 指标口径文档

### 交付物

- projects/project-01-python-sql-etl/
- projects/project-02-ecommerce-data-warehouse/
- docs/warehouse-modeling.md
- docs/metric-definition.md

## Phase 3：实时数据链路

目标：掌握 Kafka、Flink、CDC、实时数据处理。

### 任务

- [ ] Kafka 行为日志 topic 设计
- [ ] Python Kafka Producer
- [ ] Flink CDC 读取 MySQL binlog
- [ ] Flink Streaming 消费 Kafka 日志
- [ ] 实时 PV / UV / 转化漏斗
- [ ] 实时订单状态同步

### 交付物

- projects/project-03-flink-cdc-starrocks/
- projects/project-04-kafka-realtime-analytics/
- sql/flink/*.sql
- scripts/generate_behavior_logs.py

## Phase 4：OLAP 数仓与查询优化

目标：掌握 StarRocks / Doris 的建模、导入、查询和优化。

### 任务

- [ ] 部署 StarRocks / Doris
- [ ] 创建 ODS/DWD/DWS/ADS 表
- [ ] 设计 Duplicate Key / Primary Key / Aggregate Key 表
- [ ] Stream Load / Flink Connector 数据导入
- [ ] 物化视图优化
- [ ] 分区分桶优化
- [ ] Bitmap / HLL 去重优化
- [ ] Profile 慢查询分析

### 交付物

- sql/starrocks/*.sql
- benchmark/case_01_partition_pruning.md
- benchmark/case_02_materialized_view.md
- benchmark/case_03_join_optimization.md
- benchmark/case_04_bitmap_hll.md
- benchmark/case_05_topn_optimization.md

## Phase 5：数据产品与 AI 数据应用

目标：将数据平台结果产品化，形成可演示的数据看板和 AI 报告。

### 任务

- [ ] Streamlit 数据看板
- [ ] 实时 GMV 指标卡
- [ ] 商品 TopN
- [ ] 用户转化漏斗
- [ ] 渠道分析
- [ ] AI 自动经营日报
- [ ] SQL 结果解释助手

### 交付物

- dashboard/streamlit_app.py
- dashboard/pages/*.py
- projects/project-06-ai-data-report/

## Phase 6：职业化与课程化

目标：将学习过程转化为课程、作品集、简历和面试材料。

### 任务

- [ ] 每日录制计划
- [ ] 每周复盘文档
- [ ] 项目 README 优化
- [ ] 简历项目描述
- [ ] 面试问答库
- [ ] 项目讲解稿
- [ ] 课程销售页
- [ ] 内容分发计划

### 交付物

- RECORDING_PLAN.md
- interview/resume_project_description.md
- interview/project_pitch.md
- interview/sql_interview_questions.md
- interview/data_warehouse_interview_questions.md
- interview/starrocks_interview_questions.md

## 长期扩展方向

- Spark / Hive 离线数仓路径
- Iceberg / Hudi / Delta Lake 湖仓路径
- Airflow / DolphinScheduler 调度路径
- DataX / SeaTunnel 数据同步路径
- ClickHouse / Doris / StarRocks 横向对比
- dbt 数据建模路径
- 数据治理与数据质量平台
- AI 数据分析 Agent
- 企业级数据平台架构案例
