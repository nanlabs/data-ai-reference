# Data Quality Framework Checklist

A practical checklist for trustworthy data platforms: architecture documentation, schema management, orchestration reliability, data quality, lineage, storage, governance, security, observability, and scalability. Score each item 1–5 (ad-hoc → systematic) and track trends per pipeline.

## 1. Architecture & Contracts

- [ ] Platform architecture documented (sources, ingestion, storage, processing, serving).
- [ ] Schema management: versioned schemas, backward-compatible evolution, registry or contracts.
- [ ] Business-rules documentation: what each dataset means, who owns it, SLAs.

## 2. Orchestration Reliability (Score 5 Target)

- [ ] Every pipeline orchestrated (Airflow, Dagster, Step Functions, Glue Workflows) — no cron-only critical paths.
- [ ] Retries with backoff, dead-letter handling, and idempotent tasks.
- [ ] SLAs + alerts on lateness and failure; on-call rotation defined.

## 3. Data Quality Checks

- [ ] Validation at ingestion: types, ranges, nullability, referential integrity.
- [ ] Freshness, volume, and distribution checks (e.g., Great Expectations, dbt tests, Deequ).
- [ ] Quarantine-or-block policy for failing batches — never silent drops.
- [ ] Data quality dashboard visible to producers and consumers.

## 4. Lineage & Observability

- [ ] Column-to-dashboard lineage for critical datasets (manual docs or OpenLineage/Marquez).
- [ ] Pipeline observability: run history, durations, failure reasons, cost per run.
- [ ] Audit trail: who changed what pipeline, when, and why.

## 5. Storage, Security & Governance

- [ ] Storage optimized: partitioning, compression, lifecycle policies, format choice (Parquet/Delta/Iceberg).
- [ ] Encryption at rest and in transit; secrets in a vault, never in code.
- [ ] Access control per dataset/role (RBAC); PII classified and masked.
- [ ] Retention and deletion policy documented and enforced.

## 6. Scalability & Consumption

- [ ] Pipelines handle 10× current volume without redesign (partitioning, autoscaling, backpressure).
- [ ] Consumption-ready: documented tables/views, SLAs, and contact points for analysts and ML consumers.

## Running the Assessment

1. Scope one pipeline or platform area per pass.
2. Score 1–5 with evidence (dashboards, configs, run history).
3. Convert every gap ≤ 3 into an owned backlog item; re-score quarterly.

## References

- [Great Expectations](https://greatexpectations.io/)
- [dbt Tests & Documentation](https://docs.getdbt.com/docs/build/tests)
- [OpenLineage](https://openlineage.io/)
- [AWS Data Quality Best Practices](https://docs.aws.amazon.com/prescriptive-guidance/latest/strategy-data-modernization/welcome.html)
