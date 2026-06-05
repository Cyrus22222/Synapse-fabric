Purpose
Codebase and templates for building and deploying Synapse→Fabric data pipelines.

Contents
- pipeline-templates/ — JSON/ARM or pipeline templates that demonstrate parameterized ingestion and transform tasks.
- helpers/ — library code for standardized logging, error handling and retry strategies.
- tests/ — unit and integration tests for pipeline components.
- ci/ — GitHub Actions templates for linting, unit tests and deployment.

Deployment guidance
- Use parameterization for environment-specific values (storage paths, secrets).
- Validate with smoke tests after each deployment to staging before promoting to prod.
- Keep pipeline code minimal and push business logic into notebooks or versioned libraries.
