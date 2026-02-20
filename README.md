# zoomcamp_bruin_project
This hands-on tutorial guides you through building a complete NYC Taxi data pipeline from scratch using Bruin - a unified CLI tool for data ingestion, transformation, orchestration, and governance.

We will create a pipeline with 3 layers:
1. Ingestion (Python + seed): fetch monthly NYC TLC parquet files + load a small lookup CSV
2. Staging (SQL): clean + deduplicate + enrich (join lookup)
3. Reports (SQL): aggregate metrics + run quality checks
Bruin runs assets in dependency order and supports validation (dry-run style) before executing.

We use GitHub Codespaces to do the project.
Step 1 — we Create a new repository named as "nyc-taxi-bruin"
