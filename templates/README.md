Purpose
Collection of reusable templates to provision and configure Microsoft Fabric environments and pipeline scaffolds.

Structure
- IaC/ — Terraform and Bicep templates for core resources: tenants, workspaces, storage accounts, private endpoints, Key Vault, monitoring.
- Pipelines/ — sample pipeline templates (parameterized) for ingestion and transformation.
- CI-CD/ — sample GitHub Actions workflows to validate and deploy templates and notebooks.
- Config/ — example configuration files and secrets handling patterns (Key Vault references, managed identities).

Usage
- Copy and parameterize templates/IaC for your tenant and subscription.
- Use CI-CD templates to run static checks and automated deployments.
- Apply least-privilege and test deployments in non-prod first.
