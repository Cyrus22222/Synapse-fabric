Purpose
Document the current-state Synapse architecture, the target Microsoft Fabric architecture, and mapping patterns to migrate workloads with minimal business impact.

Contents
- Current-State-Architecture.md — inventory and components in existing Synapse (data sources, compute, storage, security).
- Target-Design.md — recommended Microsoft Fabric architecture, tenant and workspace layout, networking, identity and data plane patterns.
- Migration-Mapping.md — pattern-by-pattern mapping (notebook → Lakehouse/Power BI, Spark jobs → Notebooks/Workflows, dedicated SQL pools → SQL Endpoints).
- Non-functional requirements — scalability, availability, recovery, performance SLAs, and cost constraints.
- Compliance & residency — region selection, data residency and controls for Australian regulated data.

Key recommendations (summary)
- Adopt medallion (bronze/silver/gold) storage topology on Fabric lakehouses.
- Centralize metadata and classification with Purview-style catalog and lineage.
- Use IaC to provision consistent environments across dev/test/prod.
- Preserve separation of duties: infra, platform, data engineering, analytics.
