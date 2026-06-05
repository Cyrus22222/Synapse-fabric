Purpose
Executable notebooks illustrating patterns used during migration and post-migration validation.

Categories
- Metadata-driven dynamic pipelines — notebooks that generate pipeline runs from a metadata catalog.
- Medallion architecture examples — Bronze ingestion, Silver transforms, Gold publishing patterns.
- Incremental loads & CDC — techniques for efficient incremental ingestion (sources: database, event streams).
- Schema evolution — handling column additions, type changes and backfills.
- Validation & reconciliation notebooks — checksum and row-count comparisons for migration verification.

How to run
- Configure a credentials cell to point at your dev Fabric workspace.
- Parameterize dataset paths and run on a small sample first.
- Convert validated notebooks into pipeline tasks as part of CI-CD.
