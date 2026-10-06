# Awesome-Serverless-Interactive-Query-Service

# Top Serverless Interactive Query Service Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Federated SQL Queries, Data Lake Analytics & Self-Hosted Query Engines*  
**Last updated: October 2026**

This repository tracks notable **commercial interactive query platforms** and **open-source projects** that let analysts run SQL across data lakes, warehouses, and databases without managing infrastructure. These tools range from serverless query engines like Athena to full data warehouse platforms.

**Examples** include Amazon Athena, Snowflake, Google Cloud BigQuery, Databricks SQL, Starburst Galaxy, Dremio Cloud, Ahana Cloud for Presto, PrestoDB Cloud, Trino Cloud, and ClickHouse Cloud (the category leaders).

**Open-source emphasis**: Interactive query is one of the strongest open-source domains. **Trino** leads as the de facto federated SQL engine, **Apache Spark** powers large-scale analytics, **DuckDB** brings in-process OLAP, and **ClickHouse** dominates real-time analytical queries. **Apache Doris** and **StarRocks** offer real-time analytics, while **DataFusion** and **Polars** provide Rust-based query foundations. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Amazon Athena](https://aws.amazon.com/athena/)**  
  **AWS's serverless interactive query service** — run SQL on S3 data lake without infrastructure . **Pay per query** — $5 per TB scanned . **Best for ad-hoc S3 analytics** .

- **[Snowflake](https://www.snowflake.com/)**  
  **The leading cloud data warehouse** — separate compute and storage, multi-cluster warehouses, and data sharing . **The reference for cloud data warehousing** . **Best for enterprise analytics** .

- **[Google Cloud BigQuery](https://cloud.google.com/bigquery)**  
  **Google's serverless data warehouse** — petabyte-scale SQL analytics with built-in ML . **Best for GCP-native analytics** .

- **[Databricks SQL](https://www.databricks.com/)**  
  **Lakehouse SQL analytics** — query Delta Lake, Parquet, and Iceberg with Photon engine . **Best for lakehouse analytics** .

- **[Starburst Galaxy](https://www.starburst.io/)**  
  **Managed Trino platform** — federated queries across data sources . **Best for data mesh and federation** .

- **[Dremio Cloud](https://www.dremio.com/)**  
  **Lakehouse query engine** — Apache Arrow-based with semantic layer . **Best for lakehouse analytics** .

- **[Ahana Cloud for Presto](https://ahana.io/)**  
  **Managed Presto** (acquired by IBM) — SQL analytics on data lakes . **Best for Presto users** .

- **[ClickHouse Cloud](https://clickhouse.com/)**  
  **The leading analytical database** — columnar storage, real-time ingestion, and sub-second queries . **Best for real-time analytics** .

## Open-Source GitHub Projects

### Federated Query Engines

- **[Trino](https://github.com/trinodb/trino)**  
  **The de facto open-source federated SQL engine**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Query across 50+ data sources** — Hive, Iceberg, Delta Lake, PostgreSQL, MySQL, Kafka, and more . **Massively parallel processing** — scales to thousands of nodes . **The reference for interactive analytics on data lakes** . **Best for federated queries across heterogeneous sources** .

- **[PrestoDB](https://github.com/prestodb/presto)**  
  **The original Presto SQL engine**, Apache-2.0 licensed with **16,000+ GitHub stars** . **The predecessor to Trino** — created at Facebook . **Best for existing Presto deployments** .

- **[Apache Hive](https://github.com/apache/hive)**  
  **Data warehouse software for Hadoop**, Apache-2.0 licensed . **SQL-like query language for large datasets** . **The original big data SQL engine** . **Best for Hadoop ecosystems** .

- **[Apache Impala](https://github.com/apache/impala)**  
  **MPP SQL query engine for Hadoop**, Apache-2.0 licensed . **Low-latency queries on HDFS and Kudu** . **Best for Hadoop-native analytics** .

- **[Apache Drill](https://github.com/apache/drill)**  
  **Schema-free SQL query engine**, Apache-2.0 licensed . **Query JSON, Parquet, and NoSQL without schemas** . **Best for schema-less data exploration** .

### Analytical Databases

- **[ClickHouse](https://github.com/ClickHouse/ClickHouse)**  
  **The leading columnar analytical database**, Apache-2.0 licensed with **35,000+ GitHub stars** . **Real-time ingestion and sub-second queries** . **The best open-source alternative to data warehouses** . **Best for large-scale analytics and observability** .

- **[Apache Doris](https://github.com/apache/doris)**  
  **Real-time analytical database**, Apache-2.0 licensed with **12,000+ GitHub stars** . **High-performance SQL analytics** . **Best for real-time analytics** .

- **[StarRocks](https://github.com/StarRocks/starrocks)**  
  **High-performance analytical database**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Real-time analytics with lakehouse integration** . **Best for modern analytics** .

- **[Apache Druid](https://github.com/apache/druid)**  
  **Real-time analytics database**, Apache-2.0 licensed with **13,000+ GitHub stars** . **Sub-second queries on streaming data** . **Best for real-time analytics** .

- **[Apache Pinot](https://github.com/apache/pinot)**  
  **Real-time distributed OLAP datastore**, Apache-2.0 licensed with **5,000+ GitHub stars** . **User-facing analytics** . **Best for real-time analytics at scale** .

### In-Process & Embedded

- **[DuckDB](https://github.com/duckdb/duckdb)**  
  **In-process analytical database**, MIT licensed with **20,000+ GitHub stars** . **"SQLite for analytics"** — columnar storage with vectorized execution . **Runs inside your application** — no server . **The most exciting open-source analytical database** . **Best for embedded analytics and local data processing** .

- **[Apache DataFusion](https://github.com/apache/datafusion)**  
  **Extensible query engine in Rust**, Apache-2.0 licensed with **6,000+ GitHub stars** . **Arrow-native with SQL support** . **The foundation for many modern query engines** . **Best for building custom query engines** .

- **[Polars](https://github.com/pola-rs/polars)**  
  **Fast DataFrame library in Rust**, MIT licensed with **30,000+ GitHub stars** . **Multi-threaded, vectorized execution** . **The fastest DataFrame library** . **Best for data manipulation and analysis** .

### Lakehouse & Table Formats

- **[Apache Iceberg](https://github.com/apache/iceberg)**  
  **Open table format for huge analytic datasets**, Apache-2.0 licensed with **6,000+ GitHub stars** . **Schema evolution, time travel, and hidden partitioning** . **The de facto standard for data lakes** . **Best for lakehouse architectures** .

- **[Delta Lake](https://github.com/delta-io/delta)**  
  **Open table format with ACID transactions**, Apache-2.0 licensed . **Reliable data lakes with schema enforcement** . **Best for Databricks and Spark** .

- **[Apache Hudi](https://github.com/apache/hudi)**  
  **Transactional data lake platform**, Apache-2.0 licensed . **Upserts, deletes, and incremental processing** . **Best for streaming data lakes** .

- **[Project Nessie](https://github.com/projectnessie/nessie)**  
  **Git-like version control for data lakes**, Apache-2.0 licensed . **Branch, merge, and version data** . **Best for data lake versioning** .

### Additional Strong Open-Source Options

- **Apache Calcite** — SQL parser and optimization framework .
- **Apache Arrow** — Columnar in-memory format .
- **Substrait** — Cross-platform query plan format .
- **Apache Kyuubi** — Distributed SQL gateway .
- **Apache Livy** — REST interface for Spark .
- **Apache Zeppelin** — Notebook for data analytics .
- **Jupyter** — Interactive computing .
- **Metabase** — Open-source BI tool .
- **Apache Superset** — Open-source BI and visualization .

**Frameworks for building custom interactive query solutions**: Combine **Trino** for federated SQL across data sources . Use **ClickHouse** or **Apache Doris** for real-time analytical queries . Deploy **DuckDB** for embedded, in-process analytics . Choose **Apache Iceberg** for open table formats . Integrate **DataFusion** or **Polars** for custom query engines . Note that true serverless query services with managed infrastructure, automatic scaling, and vendor-supported SLAs (Athena, Snowflake, BigQuery, Databricks SQL) remain primarily commercial territory; open-source stacks provide strong federated query, analytical storage, and lakehouse foundations that require integration for complete analytics.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Interactive query services handle sensitive business data. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.
- **License considerations**: Trino uses Apache-2.0, ClickHouse uses Apache-2.0, DuckDB uses MIT, and Polars uses MIT. All permissive for commercial use. Verify licensing against your use case before committing .
- **Query performance depends on data layout** — columnar formats (Parquet, ORC, Arrow) and partition pruning are critical for performance. Design data storage accordingly .
- **Federated queries introduce latency** — Trino and Presto query across multiple sources, which can be slower than native queries. Materialize frequently accessed data for performance .
- The open-source ecosystem provides strong federated query, analytical storage, and lakehouse foundations, but **managed infrastructure, automatic scaling, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for data engineers, analysts, and organizations seeking interactive query sovereignty.**  
Let's make serverless interactive query services more open, transparent, and performant.
