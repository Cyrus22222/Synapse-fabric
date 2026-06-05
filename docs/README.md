This repository captures a repeatable, enterprise-grade migration from Azure Synapse Analytics to Microsoft Fabric. It includes architecture guidance, governance and compliance controls, migration playbooks, reusable templates, example notebooks, and pipeline code to accelerate and standardize migrations for Australian enterprise environments.

Primary sections
- docs/: Architecture, governance, playbooks, risk and runbooks.
- templates/: Infrastructure-as-Code (Terraform/Bicep) and reusable pipeline templates.
- notebooks/: Executable examples demonstrating metadata-driven, medallion-layer pipelines and schema evolution.
- code/: Pipeline source and helper libraries for ingestion, transformation and orchestration.
- diagrams/: Architecture and operational diagrams (storage for PNG/SVG/Visio export).
- nodes/: Operational procedures and systems support notes.

Audience and intent
- For architects: target design and trade-offs.
- For engineers: reusable templates, code and notebooks to run migrations.
- For governance/compliance: policy artifacts, classification and lineage design.

How to use
- Read docs/Architecture-Design/README.md for strategy and design decisions.
- Use templates/IaC for provisioning base Fabric resources.
- Run notebooks/ examples to validate approach on representative datasets.
- Follow docs/Playbook/README.md for migration runbook and cutover steps.
