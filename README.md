# AI-Powered Automated Code Intelligence Platform — POC

A proof of concept exploring whether Claude AI can autonomously audit, document, and surface actionable intelligence from enterprise Java microservice codebases — with zero manual engineering effort.

The pipeline clones a target repository, strips all sensitive content locally, and sends only a structural skeleton to Claude. Three outputs are generated automatically: an architecture document, a security findings report, and a developer onboarding guide.

Built on Java Spring Boot, AWS EKS, DynamoDB, Amazon MQ, and Solace messaging. Local simulation via LocalStack ensures zero AWS spend during development. One environment variable separates local POC from full enterprise deployment.
