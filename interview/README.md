# Interview｜简历与面试材料

本目录用于沉淀 DataForge Academy 项目相关的求职材料。

## 内容规划

| 文件 | 内容 |
|---|---|
| resume_project_description.md | 简历项目描述 |
| project_pitch.md | 5 分钟 / 15 分钟项目讲解稿 |
| sql_interview_questions.md | SQL 面试题 |
| data_warehouse_interview_questions.md | 数仓建模面试题 |
| etl_interview_questions.md | ETL 场景题 |
| big_data_interview_questions.md | Kafka / Flink / Spark 面试题 |
| olap_interview_questions.md | StarRocks / Doris / ClickHouse 面试题 |
| behavioral_questions.md | 行为面试与项目复盘问题 |

## 项目讲解原则

项目讲解不能只说“我用了什么技术”，而要说清楚：

1. 业务背景是什么。
2. 数据从哪里来。
3. 数据链路怎么设计。
4. 为什么这样建模。
5. 遇到了什么问题。
6. 如何优化。
7. 最终结果是什么。
8. 如果数据量扩大 10 倍，如何改进。

## 面试表达模板

```text
我做的是一个面向电商业务的端到端数据平台项目。
数据源包括 MySQL 业务库和 Kafka 行为日志。
离线和实时链路分别覆盖 ETL、Flink CDC、Flink Streaming。
分析层使用 StarRocks / Doris 进行 OLAP 查询。
数仓模型按照 ODS、DWD、DWS、ADS 分层设计。
项目实现了 GMV、订单数、支付成功率、商品 TopN、渠道转化、用户漏斗等指标。
同时针对慢查询做了分区裁剪、物化视图、宽表化、Bitmap/HLL 去重等优化。
```
