# Yassine Ouzaina

**Data Engineer at [Owkin](https://www.owkin.com)**, Paris

Python data products, production pipelines, and internal data tooling for biomedical and product data.

[youzaina.fr](https://youzaina.fr) | [LinkedIn](https://www.linkedin.com/in/youzaina001/) | [work@youzaina.fr](mailto:work@youzaina.fr)

## Experience

**Owkin**, Data Engineer, Paris, Jul 2025 to present
- Co-designed a shared dimensional model and built or configured scheduled Python and SQL ingestion and transformation pipelines for an internal biomedical data catalog, giving cross-functional teams on-demand self-service analytics with access controls and natural-language exploration to reduce dependence on ad hoc engineering requests.
- Built a typed Python client wrapping an ontology service API and a CI-driven importer that synchronizes published definitions into a shared data-contract package consumed by live validation pipelines.
- Contributing to ongoing cloud pipeline and analytics modernization to simplify external data integration and support recurring data deliveries.
- Operate idempotent Airflow ETL pipelines with automated schema, completeness, and referential-integrity validation, handling upstream format drift with visible quality warnings so valid records keep flowing.
- Manage cloud infrastructure as code with Terraform, contribute to orchestrator upgrades, and support production reliability through observability, targeted fixes, and safe rollbacks.

**re:mind**, Data Engineer, Paris, Sep 2023 to May 2025
- Built PySpark pipelines on Azure Databricks transforming thousands of product manuals and repair guides into structured attributes and searchable datasets.
- Co-developed and deployed an LLM document-extraction workflow with an ML engineer, validating and prefilling fields from invoices, technical sheets, and receipts for operator verification.
- Converted data and ML notebooks into tested Python modules deployed through CI/CD.

**Eviden**, HPC Research Engineer Intern, Bordeaux, Feb to Aug 2023
- Profiled CPU, memory, and I/O bottlenecks in MPI/OpenMP workloads.
- Automated benchmark collection using Python, C, and Bash on Linux.

## Selected open-source work

- **[airflow-dq-agent](https://github.com/youzaina001/airflow-dq-agent)**: Airflow 3 data-quality remediation engine. Deterministic Polars checks, allow-listed actions, HITL approval, and target-fingerprint rechecks in one `SERIALIZABLE` PostgreSQL transaction. The model never writes SQL.
- **[LedgerLens (`invoice-exception-workbench`)](https://github.com/youzaina001/invoice-exception-workbench)**: FastAPI and PostgreSQL 16 invoice triage workbench with 4 least-privilege DB roles, row-level security, transaction-scoped advisory locks, and offline evaluation replay.
- **[geocrawl](https://github.com/youzaina001/geocrawl)** ([live explorer](https://youzaina.fr/projects/geocrawl/)): Python and DuckDB crawl-freshness pipeline comparing archived web snapshots with visible-prose extraction, three-word run deduplication, and SHA-256 manifest provenance.

## Stack

Python, SQL, PySpark, Databricks, Airflow, Polars, DuckDB, PostgreSQL, AWS, Azure, Terraform, Docker, Kubernetes

## Education & Certification

- **ENSEIRB-MATMECA**: Engineering degree in Applied Mathematics (Diplôme d'ingénieur, Master's equivalent), 2023
- **Astronomer**: DAG Authoring for Apache Airflow 3, Nov 2025
