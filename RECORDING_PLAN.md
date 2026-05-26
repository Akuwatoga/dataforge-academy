# Recording Plan｜录制与内容输出计划

DataForge Academy 的录制目标不是一次性制作完美课程，而是将真实学习、搭建、踩坑、复盘过程持续记录下来，形成可复用、可剪辑、可商业化的内容资产。

## 核心原则

1. 每天录制一个明确问题。
2. 每集只解决一个小目标。
3. 真实记录报错和排查过程。
4. 每天至少有一个 Git commit。
5. 每周做一次复盘视频。
6. 技术学习、项目交付、求职表达同步沉淀。

## 每集视频结构

每集建议 8–20 分钟，结构如下：

```text
1. 今天要解决什么问题？
2. 这个问题在真实数据岗位中为什么重要？
3. 需要掌握哪些知识点？
4. 实操过程。
5. 遇到的问题与排查。
6. 今日产出。
7. 这个内容如何用于面试或项目文档？
8. 下一集要做什么？
```

## 每日输出模板

每天至少输出：

- 一段录屏视频
- 一个 Git commit
- 一份 daily 学习记录
- 一个可运行功能、SQL、配置或文档

每日记录模板：

```markdown
# Day X：标题

## 今日目标

## 今日学习知识点

## 今日实操内容

## 今日代码 / SQL / 文档输出

## 遇到的问题

## 解决方法

## 可以录制成课程的重点

## 面试可讲点

## 明日计划
```

## 每周输出模板

每周至少输出：

- 一篇周总结
- 一个阶段性 demo
- 一个课程模块文档
- 一个 5–15 分钟周总结视频
- 一组小红书 / B 站 / 公众号标题

每周总结模板：

```markdown
# Week X 总结

## 本周主题

## 本周完成内容

## 核心知识点

## 项目进展

## 录制内容列表

## 本周踩坑

## 本周面试沉淀

## 下周计划
```

## 12 周录制主题

### Week 00：项目定位与学习体系设计

- Day 1：为什么要做 DataForge Academy？
- Day 2：如何拆解数据岗位能力？
- Day 3：如何把 gap 期学习变成作品集和课程？
- Day 4：GitHub 仓库结构设计。
- Day 5：主线项目：电商端到端数据平台。

### Week 01：Python 数据工程基础

- Day 1：Python 在数据工程中到底用来做什么？
- Day 2：生成用户和商品模拟数据。
- Day 3：生成订单和支付数据。
- Day 4：pandas 读取和清洗 CSV / Excel。
- Day 5：logging、argparse 和脚本工程化。
- Day 6：Python 写入 MySQL。
- Day 7：周总结：数据生成器 v1。

### Week 02：SQL 与业务指标分析

- Day 1：SQL 为什么是数据岗位核心能力？
- Day 2：GMV、订单数、客单价。
- Day 3：JOIN 用户、商品、订单、支付表。
- Day 4：窗口函数：首单、最近一次下单、排名。
- Day 5：复购率、转化率、支付成功率。
- Day 6：留存、漏斗和渠道分析。
- Day 7：周总结：40 条业务 SQL。

### Week 03：MySQL 业务库建模

- Day 1：电商业务库怎么设计？
- Day 2：用户、商品、类目、供应商表。
- Day 3：订单、订单明细、支付、退款表。
- Day 4：订单状态和支付状态流转。
- Day 5：索引、事务和执行计划。
- Day 6：为什么 MySQL 不适合复杂 OLAP？
- Day 7：周总结：业务库到分析库。

### Week 04：Linux 与 Docker 部署

- Day 1：ECS 初始化和 SSH。
- Day 2：Linux 常用命令和日志排查。
- Day 3：Docker 镜像、容器、网络、卷。
- Day 4：Docker Compose 部署 MySQL。
- Day 5：服务端口和防火墙排查。
- Day 6：数据平台组件目录规划。
- Day 7：周总结：服务器环境搭建。

### Week 05：ETL 与数据质量

- Day 1：ETL 的本质是什么？
- Day 2：CSV / Excel → MySQL。
- Day 3：字段映射和类型转换。
- Day 4：缺失值、重复值、异常值处理。
- Day 5：数据质量校验报告。
- Day 6：ETL 运行日志和错误记录。
- Day 7：周总结：第一个 ETL 项目。

### Week 06：数据仓库建模

- Day 1：ODS/DWD/DWS/ADS 为什么存在？
- Day 2：事实表和维度表。
- Day 3：订单明细宽表设计。
- Day 4：商品、渠道、用户汇总表。
- Day 5：指标口径文档怎么写？
- Day 6：数据血缘和数据质量。
- Day 7：周总结：电商数仓模型。

### Week 07：Kafka 实时日志

- Day 1：业务库数据和行为日志有什么不同？
- Day 2：Kafka Topic 和 Partition。
- Day 3：Python Kafka Producer。
- Day 4：行为日志格式设计。
- Day 5：实时 PV / UV 计算思路。
- Day 6：用户转化漏斗设计。
- Day 7：周总结：行为日志链路。

### Week 08：Flink CDC 与实时同步

- Day 1：CDC 是什么？
- Day 2：MySQL binlog 配置。
- Day 3：Flink CDC 读取 MySQL。
- Day 4：Flink SQL 基础。
- Day 5：订单状态实时同步。
- Day 6：Checkpoint、延迟和一致性。
- Day 7：周总结：CDC 实时链路。

### Week 09：StarRocks / Doris OLAP 数仓

- Day 1：OLAP 引擎解决什么问题？
- Day 2：StarRocks FE / BE 架构。
- Day 3：部署 StarRocks。
- Day 4：Duplicate Key / Primary Key / Aggregate Key。
- Day 5：分区和分桶设计。
- Day 6：Stream Load 和 Flink Connector。
- Day 7：周总结：实时 OLAP 数仓建模。

### Week 10：OLAP 查询优化

- Day 1：慢查询排查流程。
- Day 2：分区裁剪优化。
- Day 3：物化视图优化。
- Day 4：Join 优化和宽表化。
- Day 5：Bitmap / HLL 去重优化。
- Day 6：TopN 查询优化。
- Day 7：周总结：5 个优化案例。

### Week 11：数据看板与 AI 自动报告

- Day 1：数据工程项目如何产品化？
- Day 2：Streamlit 搭建看板。
- Day 3：实时 GMV、订单数、支付成功率。
- Day 4：商品 TopN 和渠道转化。
- Day 5：用户漏斗和留存展示。
- Day 6：AI 自动经营日报。
- Day 7：周总结：数据产品 demo。

### Week 12：简历、面试与课程化

- Day 1：如何把项目写进简历？
- Day 2：5 分钟项目讲解稿。
- Day 3：SQL / 数仓 / StarRocks 面试题。
- Day 4：项目架构图和数据流图。
- Day 5：课程介绍页和销售文案。
- Day 6：内容切片和平台发布计划。
- Day 7：最终复盘：从 gap 学习到数据教培项目。

## 内容分发建议

### 免费内容

- gap 期如何做数据工程作品集
- SQL 学到什么程度能找数据岗位
- ETL 工程师到底做什么
- 实时数仓岗位 JD 拆解
- StarRocks / Doris 入门路线
- Flink CDC 是什么
- 数据工程项目如何写进简历

### 付费内容

- 完整项目代码和讲解
- 每周作业和答疑
- 简历项目辅导
- SQL / 数仓 / 实时链路专项训练
- 一对一项目陪跑
