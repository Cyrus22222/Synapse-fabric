Purpose
Define governance framework, roles, policies and technical controls required for secure, compliant operations on Microsoft Fabric.

Sections
- Governance-Overview.md — governance model, responsibilities (platform, security, data owners).
- Data-Classifications.md — classification taxonomy, handling rules, retention and masking guidance.
- Access-Control.md — principle of least privilege, role mapping to Fabric workspace roles, Azure AD groups.
- Lineage-and-Discovery.md — cataloging approach and lineage capture for audits.
- Monitoring-and-Audit.md — recommended telemetry (activity logs, diagnostic settings, workspace usage) and retention policy to satisfy Australian compliance.
- Purview-Integration.md — how to integrate Purview (or equivalent) for catalog and classification.

Operational controls
- Enforce workspace-level network controls and private endpoints for sensitive systems.
- Automate policy and baseline via IaC and policy-as-code scans.
- Periodic compliance reviews and automated alerts for drift.
