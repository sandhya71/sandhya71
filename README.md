[SK.](#hero)

[About](#about) [Experience](#experience) [Projects](#projects) [Stack](#stack) [Contact](#contact)

Data Engineer · Bangalore

# Building data infrastructure that *scales.*

I design and ship **petabyte-scale data pipelines and AI-native platforms** on Azure — from raw ingestion through curated semantic models to agentic AI products. 3.5 years across Microsoft, fintech, and consulting. Currently at Tredence.

[See my work](#projects) [Get in touch](mailto:sandhyakapse17@gmail.com)

0

Professional data\
engineering experience

0

Snowflake query\
runtime reduced

0

AutoFX propensity\
model accuracy

0

ADF connectors owned\
in production

About

I think in systems,\
build for reliability.

I'm a Data Engineer specialising in **Azure-native data infrastructure** — from ingestion through ADF and ADLS Gen2, through transformation in Databricks and Synapse, to curated semantic models powering dashboards and AI agents.

At **Tredence**, I architected the AutoFX intelligent payment platform for a global bank — a six-checkpoint ML pipeline processing live FX payment events, with SHAP-driven explainability surfaced in a real-time advisor dashboard. At **Microsoft**, I owned enterprise data ingestion for global clients and directly influenced ADF platform fixes shipped worldwide.

I care about the last mile as much as the first. The data that reaches an AI agent or an executive dashboard should be as clean and trustworthy as the raw source was messy. **Data governance, lineage, and quality** are engineering decisions, not afterthoughts.

Proficiency

Azure Data Factory & Fabric95%

SQL & Data Modelling92%

PySpark / Databricks88%

Python84%

Snowflake / Delta Lake86%

Azure AI Foundry / Agents74%

Data Governance & Lineage80%

Experience

Where I've built

Jul 2026 — Present

Data Engineer

Tredence · Bangalore

- Architected the **AutoFX AI data platform** — petabyte-scale Medallion pipelines (staging → canonical → curated) processing live multi-currency payment events via Azure Fabric OneLake and ADLS Gen2.
- Built a **six-checkpoint propensity model pipeline** (validation → currency check → feature retrieval → model → decision rules → AutoFX decision) achieving 86% accuracy — enabling straight-through FX conversion.
- Designed **curated semantic and logical data models** across six feature domains, powering NL2SQL / NL2DAX agent queries via Azure AI Foundry and Copilot Studio.
- Delivered a **real-time advisor dashboard** with SHAP explainability — surfacing propensity scores and confidence signals per payment, directly driving executive decision-making and STP rate uplift.
- Enforced data governance via **RBAC, lineage tracking, audit logging, and schema validation** across all pipeline layers.

Mar 2025 — Jun 2026 · 1 yr 4 months

Support Engineer

Microsoft (via Aptly Professionals) · Bangalore

- Owned production reliability for enterprise data ingestion (SAP ERP, REST APIs, SFTP, Fabric Lakehouses via ADF) serving global business-critical Microsoft clients.
- Configured **10+ ADF connectors** — SAP, Snowflake, SQL Server, Fabric, SFTP, ADLS, Blob, Databricks — and resolved high-severity incidents via deep ADF telemetry analysis.
- Identified ADF product bugs and drove **platform fixes shipped globally** to enterprise customers worldwide.

Sep 2024 — Mar 2025 · 7 months

Data Engineer

CoffeeBeans Consulting · Bangalore

- Reduced Snowflake query runtime **35%** by re-architecting REST API ingestion of live eCommerce events via partition pruning, index tuning, and SQL restructuring.
- Delivered **20% executive dashboard performance gain** building PySpark Medallion transforms (Bronze → Silver → Gold) in Databricks on high-volume JSON event streams.

Jan 2022 — Jun 2023 · 1.5 years

Data Engineer

ITC Infotech · Bangalore

- Led cloud database migration from SQL Server and PostgreSQL to Snowflake and Azure Data Lake — designed strategy, resolved schema conflicts, reduced reporting latency.
- Built CI/CD for all data transformation releases via Azure DevOps — zero-regression deployments across dev, UAT, and production.

Engineering work

What I've shipped

[↗ ● Production · Fintech AutoFX — Intelligent Payment Platform Architected an end-to-end AI data platform for a global bank. Designed petabyte-scale Medallion pipelines processing live FX payment events — from raw ingestion through a six-checkpoint ML pipeline to a real-time advisor dashboard with SHAP-driven explainability. The platform enabled straight-through FX conversion, eliminating advisor intervention on qualified payments. Azure Fabric OneLakeADLS Gen2 DatabricksAzure AI Foundry Copilot StudioPySpark Feature StoreSHAP **86%** model accuracy **6** pipeline checkpoints **Real-time** advisor dashboard](https://github.com/sandhya71) [↗ ● Architecture · Azure + AWS Payment Analytics Data Pipeline Idempotent Spark pipeline processing simulated payment transaction data — ingestion, deduplication, schema validation, and aggregated metrics (revenue, conversion, STP rate). Designed for exactly-once delivery and late-arriving data handling. Demonstrates financial data engineering patterns directly applicable to Stripe, Intuit, and PayU-scale systems. PySparkAWS S3 AWS LambdaSnowflake Delta LakePython **Idempotent** design **Exactly-once** delivery **Late data** handled](https://github.com/sandhya71) [↗ ● Open source · Azure Real-Time Sports Analytics Platform REST API ingestion into ADF feeding a Databricks Medallion architecture (Bronze → Silver → Gold) with Delta Lake storage. Demonstrates multi-source ingestion, PySpark transformation patterns, schema evolution handling, and data quality checks on event-driven sports performance data. Azure Data FactoryDatabricks PySparkDelta Lake ADLS Gen2Medallion **3-layer** Medallion **Schema** evolution **Data quality** checks](https://github.com/sandhya71/Olympic_Transformation) [↗ ● Open source · Cross-cloud Cross-Cloud Streaming Pipeline Event-driven streaming architecture spanning Azure and AWS. Twitter Streaming API → AWS Lambda (event trigger) → AWS S3 (data lake) → Elasticsearch (analytics). Demonstrates multi-cloud ingestion, serverless event handling, and near-real-time analytics — patterns applicable to any high-throughput streaming domain. AWS LambdaAWS S3 ElasticsearchPython Event-drivenNear-real-time **Cross-cloud** architecture **Serverless** triggers **Real-time** analytics](https://github.com/sandhya71/Twitter_Data_Pipeline/)

Thinking

How I approach the work

[Data Architecture Why I always start with the Gold layer How working backwards from the business question shapes better Medallion architecture decisions — and why Bronze/Silver aren't just staging areas.](https://medium.com/@sandhyakapse17) [Performance Engineering 35% faster: what actually fixed the Snowflake query The three changes that cut query runtime by a third — partition pruning, index tuning, and a SQL restructure that wasn't obvious until we read the execution plan.](https://medium.com/@sandhyakapse17) [Data Quality Data governance isn't a checklist How RBAC, lineage tracking, audit telemetry, and schema validation became engineering decisions at the design stage — not compliance tasks after launch.](https://medium.com/@sandhyakapse17)

Tech Stack

What I build with

Azure Data FactoryAzure Databricks Microsoft FabricADLS Gen2 Azure SynapseAzure AI Foundry Copilot StudioMCP Endpoints FastAPIPySpark PythonSQL · Spark SQL SnowflakeDelta Lake Medallion Architecturedbt (learning) Airflow (familiar)AWS S3 · Lambda Amazon RedshiftElasticsearch REST API IngestionCDC Feature StoresSHAP Explainability CI/CD · Azure DevOpsData Governance RBAC · Data LineageAudit Telemetry

## Open to the right opportunity.

Looking for senior data engineering roles, data platform architecture, and AI-native data product opportunities. Based in Bangalore — open to hybrid and remote.

[sandhyakapse17@gmail.com](mailto:sandhyakapse17@gmail.com)

[in LinkedIn linkedin.com/in/sandhya-kapse](https://www.linkedin.com/in/sandhya-kapse-086207146/) [gh GitHub github.com/sandhya71](https://github.com/sandhya71) [M Medium @sandhyakapse17](https://medium.com/@sandhyakapse17) [HR HackerRank sandhyakapse17](https://www.hackerrank.com/profile/sandhyakapse17)

© 2026 Sandhya Kapse Data Engineer · Bangalore
