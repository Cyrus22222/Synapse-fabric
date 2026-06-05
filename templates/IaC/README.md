Purpose
Guidance and examples to provision Microsoft Fabric and supporting infrastructure using IaC.

Included samples
- terraform/fabric-base.tf — create managed resource groups, storage accounts, log analytics, and Fabric workspaces.
- bicep/fabric-deploy.bicep — Bicep module examples for workspace and networking.
- examples/variables.example.tfvars — recommended variables for Australian region, subscription IDs, and naming conventions.

Notes
- Use service principals and Managed Identities for automation.
- Encrypt secrets with Key Vault and reference them in templates.
- Validate network dependencies (private endpoints) and route table requirements before provisioning.
