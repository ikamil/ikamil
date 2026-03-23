# Kamil Islamov

**Senior / Staff Data Engineer / Analyst | Database Architect | 22+ Years Experience | PhD**

[linkedin.com/in/ikamil](https://linkedin.com/in/ikamil) | [github.com/ikamil](https://github.com/ikamil)

---

## Profile

Results-driven Senior Data Engineer with 22+ years delivering enterprise-grade data systems across telecom, FMCG, adtech, and fintech. Proven record of building and owning complex cloud-native pipelines (Snowflake, Databricks, Airflow, dbt) that run at global scale. At PepsiCo, personally engineered an inventory optimization engine saving tens of thousands of dollars monthly across multi-manufacturer supply chains. At OXIO, led a full Snowflake to Databricks platform migration (~1,000 models). Deep roots in Oracle billing systems give unique insight into mission-critical, high-volume transactional workloads. PhD, published speaker at PgConf, and active hackathon competitor.

---

## Core Skills

| Domain | Technologies | Years |
|--------|-------------|-------|
| **SQL & Databases** | SQL, Oracle PL/SQL, PostgreSQL, PL/pgSQL | 22 |
| **Data Warehousing** | Snowflake, Data Vault 2.0 | 7 |
| **Orchestration** | Apache Airflow (MWAA), Luigi, Jenkins | 5 |
| **Transformation** | dbt, Great Expectations, pandas, Dask | 5 |
| **Cloud Platforms** | AWS (S3, MWAA, SQS, ECR), Azure (Blob, Data Lake) | 7 |
| **Big Data** | Databricks, Delta Lake, Spark, Hive, Kafka | 1-7 |
| **Programming** | Python, Django, Java Spring, Groovy, Delphi, Node.js | 12 |
| **ML / CV** | YOLO, PaddleOCR, ONNX, Scikit-Learn, Prophet | 2 |
| **DevOps** | Docker, Kubernetes, CI/CD (GitLab CI, Argo), Flyway | 5 |

---

## Experience

### Senior Data Engineer -- OXIO (Telecom-as-a-Service)
**January 2026 -- March 2026**

- Migration of ~1,000 BI/ML models from Snowflake + CloudDBT + ElasticCube to Databricks Delta tables + dbt -- driven by cost efficiency goals
- Orchestrated ~500 Airflow (AWS MWAA) DAGs covering Kafka ingestion, dbt transformations, and Sisense BI delivery for a TaaS telecom platform
- Conducted Data Quality research and remediation as part of the broader Snowflake to Databricks infrastructure transformation
- **Stack:** AWS MWAA, Databricks, Delta Lake, dbt, Kafka, Sisense, CI/CD

### Senior Data Engineer -- PepsiCo (via Provectus)
**January 2021 -- December 2025**

- Owned and maintained an inventory optimization engine solving a multi-manufacturer, multi-warehouse fill-rate problem -- saving tens of thousands of dollars monthly in shipping costs
- Contributed to a cross-functional DE platform spanning dozens of teams, with hundreds of Airflow pipelines processing everything from raw web-scraped pages to relational DB sources
- Led migration of Azure/Snowflake/Prophet forecasting system to Databricks; implemented Data Vault patterns and Great Expectations data quality checks
- Enforced cross-team code reuse, data governance standards, and CI/CD pipelines across AWS and Azure
- **Stack:** Airflow, Snowflake, dbt, Databricks, Azure, AWS, pandas, Scikit-Learn, Prophet, Great Expectations

### Senior Data Engineer -- NinthDecimal / InMarket (via Provectus)
**August 2017 -- December 2020**

- Built dozens of commercially deployed datasets powering US-wide mobile device movement analytics -- processing terabytes of geo and transactional data
- Developed fully automated Luigi / Airflow / Jenkins container pipelines and self-serve Jupyter Notebook tools for non-technical product managers
- Delivered ad-hoc big data services and automated licensing reports; Snowflake + Hive for cloud analytics
- **Stack:** Luigi, Airflow, Jenkins, Snowflake, Hive, Jupyter, Python

### CTO & Co-Founder -- Stickeroid AI (FinTech Startup)
**2016 -- April 2020**

- Architected and built a high-load PostgreSQL/Django backend from scratch; designed all PL/pgSQL business logic
- Ran big data analytics across Snowflake, ParAccel, and Hive; built mobile location data automation pipelines
- Full-stack ownership (excluding design): backend, data engineering, front-end JS

### Senior Database Developer -- Tronic SmartCity PTE Ltd
**November 2014 -- February 2018**

- Led database architecture and data analysis for a Smart City Wi-Fi analytics platform integrated into urban IoT environments
- Developed distributed mobile device monitoring and authentication infrastructure; authored patents and grant applications

### Senior Oracle Developer / Team Lead -- MTS (Mobile TeleSystems)
**October 2003 -- August 2017**

- Key developer and later team lead on a national-scale OSS/BSS billing system serving hundreds of millions of telecom customers (internet, TV, mobile, VOIP)
- Built billing core, tariffing, service request, NOC, and financial modules within a 1M+ LOC mission-critical codebase spanning Oracle PL/SQL, Java Spring, Groovy, Cassandra, Tarantool, RabbitMQ, and Kafka
- Led migration of regional customers to single unified national infrastructure; performance-tuned high-load Oracle systems
- **Stack:** Oracle PL/SQL, Delphi, Java Spring, MyBatis, Groovy, Cassandra, Tarantool, RabbitMQ, Kafka

---

## Open-Source Portfolio

### AWS + Databricks Data Platform
[github.com/ikamil/aws-databricks-demo](https://github.com/ikamil/aws-databricks-demo)

Production-grade medallion architecture (Bronze/Silver/Gold) on Databricks + Delta Lake with AWS MWAA orchestration. YAML-driven DAG factory generating 19+ DAGs, Kafka Protobuf/JSON streaming, watermark-based deduplication, dbt transformations, Flyway schema migrations, GeoPandas spatial joins, and multi-tenant brand isolation.

**Stack:** Databricks, Delta Lake, AWS MWAA, dbt, Kafka, Flyway, GeoPandas, GitLab CI, CloudWatch

### Azure + Snowflake Pipeline Platform
[github.com/ikamil/azure-snowflake-demo](https://github.com/ikamil/azure-snowflake-demo)

Enterprise Airflow platform with 12 pipeline patterns: SFTP/REST API/S3/SharePoint ingestion, K8s web scrapers, email-triggered pipelines, SQS-driven dbt re-runs, cross-cloud S3-to-Azure transfer via DuckDB. Data Vault 2.0 loading (Hub/Link/Satellite), Great Expectations validation, custom fiscal calendar timetable.

**Stack:** Airflow 2.10, Snowflake, dbt, DuckDB, Great Expectations, Kubernetes, Datadog, Sentry

### Analytics ETL Pipeline (pandas)
[github.com/ikamil/pandas-cloud-demo](https://github.com/ikamil/pandas-cloud-demo)

Multi-source ETL into Snowflake with Data Vault 2.0 methodology. S3 Select server-side filtering, chunked CSV processing, multi-sheet Excel extraction, two-phase Great Expectations validation (source + warehouse), Argo Workflows CI/CD with Kaniko builds.

**Stack:** Airflow 1.10, pandas, Snowflake, Great Expectations, Dask, Argo Workflows, Data Vault 2.0

### Snowflake & Hadoop ETL Patterns
[github.com/ikamil/snowflake-jupyter-demo](https://github.com/ikamil/snowflake-jupyter-demo)

Reference patterns for Hive-to-Snowflake ingestion, Snowflake-to-S3/HDFS export, Luigi + PySpark orchestration. Advanced SQL: Haversine UDFs, JavaScript stored procedures, address normalization, geospatial grid math.

**Stack:** Snowflake, Hive/Hadoop, PySpark, Luigi, Docker

### VisionGate -- License Plate Recognition
[github.com/ikamil/visiongate](https://github.com/ikamil/visiongate)

YOLO-based license plate detection with PaddleOCR text recognition and Django admin panel for access control. RTSP video stream processing, event logging, allowed-list management, CSV export. Multiple ONNX model versions for detection accuracy.

**Stack:** Django, YOLO, PaddleOCR, ONNX Runtime, OpenCV, PostgreSQL, Nginx, Docker

### IQCity -- Smart City Monitoring
[github.com/ikamil/iqcity](https://github.com/ikamil/iqcity)

Automated IQ index data collection and analysis system for Smart City territorial units. Airflow DAGs for BIM Excel processing and 2GIS API import, Django admin for data management, PostgreSQL stored procedures for data loading.

**Stack:** Django, Airflow, PostgreSQL, pandas, Docker

---

## Key Achievements

- **PepsiCo Optimization Engine:** Personally built and owned system saving $10K+/month in shipping costs, increasing supply chain fill rates across competing manufacturers
- **OXIO Platform Migration:** Took part in ~1,000-model transition from Snowflake to Databricks Delta Lake, improving cost efficiency for a TaaS telecom platform
- **PgConf Speaker (2017--2020):** Published sessions on PostgreSQL sequences, CTE queries, MQTT IoT data, and Django ORM integration at Russia's top DB conference
- **Hackathons:** Top 20 in Tsifrovoy Proryv 2020--2021 ML championships (MFC/Federal Tax Service/Rosstat track). Participant in Guinness World Record hackathon (2019)
- **Patents:** Authored patents for IoT/Smart Home integration systems and Wi-Fi analytics infrastructure

---

## Education & Certifications

- **PhD (Candidate of Technical Sciences at Civil Engineering), Associate Professor** -- Kazan (Volga Region) Federal University, 1998--2007
- **ML & Data Analysis Certificate** -- Innopolis University, 2024
- **ML Advanced Certificate** -- Otus, 2025

---

## Publications

- PgConf 2017, Moscow -- "The use of stored procedures Postgres and ORM on the example of Django"
- PgConf 2016, Moscow -- "Optimization of data processing of analytical reports"
- Journal "Fundamental Research" (HAC) -- Articles on information modeling, load-carrying capacity of structures (2015--2016)
- Published research on MQTT as IoT data exchange interface integrated with PostgreSQL
- Published research on advanced CTE chain patterns for business logic in databases

---

*Open to Senior / Staff Data Engineer roles. Remote-only.*
