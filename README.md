# kfappfoundry
This is an Open Source project that standardizes, automates and accelerates the end to end lifecycle of modern cloud native applications based on the Java Micro-services ecosystem

The main goals of the Project are :

Domain Driven Development

- A Common Registry that holds Domain Models as OpenApi3.0 Schemas
- Complete  GitOps style Workfows for managing Schemas, including a RBAC based workflow 
- Inline Schema Editor that validates against OpenApi3.0 Schema specifications
  Ablity to create Multi-resolutional knowledge models  using prototypes and properties
  - https://ieeexplore.ieee.org/abstract/document/1245089
  - ( https://pdfs.semanticscholar.org/971a/66a2ff85c5dc14475cf8535df04de8e5c9e0.pdf)

API First Development

- Ablity to import Common API Schemas to Compose OPenApi 3.0 COmpliant Schemas
- Autogenerate  Validation code as well as package the Validation Code into Reusable microservices

Composable Integration Workflows

- Ablity to assemble API Implemenation as composable workflows that work on standard patterns like the VETRO (Validation, Enrichment, Transform, Route, Operate) pattern.
- Generate code to relasise the workflow - Initial support for Apache Camel based runtimes(WSO2 and Mulesof in later versions)
- Autogenerate Test Stubs to validate APIs
- Gits Style Workflows 

Common Components for :

- Audit Logging( GDPR Compliance coming later)
- Error Handling and Resubmition portal
- Application Level Monitoring(including constituent microservices and APIs)
- Common Discovery Service 
- Common Cloud Config Service with Vault Integration 
- CEP engine to treat Logs as Streams that can diseccted for Buisness, Performance and Security events

AutoOps for Cloud Native DevSecOps

- PreConfigured pipelines that can deploy a Microservice or API/Integration workflow on Kubernetes or Cloudfoundry
- Gits Ops Style Auditable and Repeatable Code

DataOps 

Integrate with DataOps tools for end to end DataOps fetaures like 
- Migration 
- Snapshots (as an application)
- Automatically obfuscate production data so as to enable parity in test enviroments 


