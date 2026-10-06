# Awesome-Unified-Cloud-Resource-Management-API

# Top Unified Cloud Resource Management API Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Infrastructure-as-Code, Cloud Provisioning APIs & Multi-Cloud Control Planes*  
**Last updated: October 2026**

This repository tracks notable **commercial cloud resource management platforms** and **open-source projects** that provide unified APIs for provisioning, managing, and governing cloud infrastructure. These tools abstract across AWS, Azure, GCP, and other providers — enabling Infrastructure as Code, policy enforcement, and self-service provisioning.

**Examples** include AWS CloudControl, Azure Resource Manager, Google Cloud Resource Manager, Terraform Cloud, Pulumi, Crossplane, Spacelift, Scalr, env0, and CloudFormation (the category leaders).

**Open-source emphasis**: Cloud resource management is a strong open-source domain. **Terraform** and **OpenTofu** lead as the IaC standards. **Pulumi** brings IaC with real programming languages. **Crossplane** extends Kubernetes to manage cloud resources. **AWS Controllers for Kubernetes (ACK)** and **Azure Service Operator** bring provider-native control planes to Kubernetes. **Terragrunt** adds orchestration to Terraform. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[AWS Cloud Control API](https://aws.amazon.com/cloudcontrolapi/)**  
  **AWS's unified API for cloud resource management** — consistent CRUD operations across hundreds of AWS services. **The standard for AWS-native resource provisioning** .

- **[Azure Resource Manager](https://azure.microsoft.com/en-us/features/resource-manager/)**  
  **Azure's management layer** — deploy, manage, and organize Azure resources via declarative templates. **The foundation for all Azure provisioning** .

- **[Google Cloud Resource Manager](https://cloud.google.com/resource-manager)**  
  GCP's resource hierarchy API — manage projects, folders, and organizations programmatically.

- **[Terraform Cloud](https://www.terraform.io/cloud)**  
  **HashiCorp's managed IaC platform** — remote state, collaboration, policy enforcement, and CI/CD integration. **The most widely used commercial IaC platform** .

- **[Pulumi Cloud](https://www.pulumi.com/)**  
  **Managed IaC with real programming languages** — TypeScript, Python, Go, .NET. **Best for developers wanting IaC in code** .

- **[Spacelift](https://spacelift.io/)**  
  **IaC orchestration platform** — Terraform, OpenTofu, Pulumi, CloudFormation, and Kubernetes. **Best for complex multi-IaC workflows** .

- **[Scalr](https://scalr.com/)**  
  **Terraform automation and collaboration platform** — policy enforcement and cost management. **Best for enterprise Terraform governance** .

- **[env0](https://www.env0.com/)**  
  **IaC automation platform** — self-service environments with guardrails. **Best for developer self-service** .

- **[AWS CloudFormation](https://aws.amazon.com/cloudformation/)**  
  **AWS's native IaC service** — declarative templates for AWS resource provisioning. **The reference for AWS-native IaC** .

## Open-Source GitHub Projects

### Infrastructure as Code

- **[Terraform](https://github.com/hashicorp/terraform)**  
  **The de facto IaC standard**, MPL-2.0 licensed with **43,000+ GitHub stars** . **Declarative configuration for any cloud** — AWS, Azure, GCP, and 3,000+ providers . **The reference for infrastructure provisioning** . **Best for multi-cloud infrastructure as code** .

- **[OpenTofu](https://github.com/opentofu/opentofu)**  
  **Open-source Terraform fork**, MPL-2.0 licensed with **25,000+ GitHub stars** . **Community-driven under Linux Foundation** — no BSL licensing concerns . **Drop-in replacement for Terraform** . **Best for organizations wanting open governance** .

- **[Pulumi](https://github.com/pulumi/pulumi)**  
  **IaC with real programming languages**, Apache-2.0 licensed with **22,000+ GitHub stars** . **TypeScript, Python, Go, .NET, Java** . **Full programming language power** — loops, functions, classes, and testing . **Best for developers wanting IaC in code** .

- **[Crossplane](https://github.com/crossplane/crossplane)**  
  **Kubernetes-native cloud resource management**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Extends Kubernetes API to manage cloud resources** — provision AWS, Azure, GCP from Kubernetes . **The standard for Kubernetes-native infrastructure** . **Best for platform teams building internal developer platforms** .

- **[AWS Controllers for Kubernetes (ACK)](https://github.com/aws-controllers-kustomize/ack)**  
  **AWS-native Kubernetes controllers**, Apache-2.0 licensed . **Manage AWS resources from Kubernetes** — S3, RDS, EKS, and more . **Best for AWS-centric Kubernetes deployments** .

- **[Azure Service Operator](https://github.com/Azure/azure-service-operator)**  
  **Azure-native Kubernetes controllers**, MIT licensed . **Manage Azure resources from Kubernetes** . **Best for Azure-centric Kubernetes deployments** .

- **[GCP Config Connector](https://github.com/GoogleCloudPlatform/k8s-config-connector)**  
  **GCP-native Kubernetes controllers**, Apache-2.0 licensed . **Manage GCP resources from Kubernetes** . **Best for GCP-centric Kubernetes deployments** .

- **[Terragrunt](https://github.com/gruntwork-io/terragrunt)**  
  **Terraform wrapper for DRY configurations**, MIT licensed with **8,000+ GitHub stars** . **Orchestrates Terraform across environments** — keeps configurations DRY . **Best for complex multi-environment deployments** .

- **[Terramate](https://github.com/terramate-io/terramate)**  
  **Orchestration and code generation for Terraform**, MPL-2.0 licensed . **Adds stacks, orchestration, and GitOps to Terraform** . **Best for scaling Terraform deployments** .

- **[Atlantis](https://github.com/runatlantis/atlantis)**  
  **Terraform pull request automation**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Collaborative IaC via pull requests** — plan and apply from PR comments . **Best for Terraform collaboration** .

- **[Digger](https://github.com/diggerhq/digger)**  
  **Open-source Terraform Cloud alternative**, MIT licensed . **CI/CD-native IaC orchestration** — runs in your existing CI . **Best for Terraform in CI/CD** .

### Cloud Resource APIs

- **[AWS SDK](https://github.com/aws/aws-sdk)** — Official AWS SDKs for all languages .
- **[Azure SDK](https://github.com/Azure/azure-sdk)** — Official Azure SDKs .
- **[Google Cloud SDK](https://github.com/googleapis/google-cloud-go)** — Official GCP SDKs .
- **[CloudQuery](https://github.com/cloudquery/cloudquery)**  
  **Open-source cloud asset inventory**, MPL-2.0 licensed with **6,000+ GitHub stars** . **Extracts, transforms, and loads cloud configuration** — SQL-queryable inventory . **Best for cloud asset visibility and compliance** .
- **[Steampipe](https://github.com/turbot/steampipe)**  
  **Zero-ETL cloud API querying with SQL**, AGPL-3.0 licensed with **7,000+ GitHub stars** . **Query cloud resources with SQL** — no database required . **Best for cloud resource exploration** .
- **[Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)**  
  **Rules engine for cloud security and cost management**, Apache-2.0 licensed . **Policy-as-code for AWS, Azure, GCP** . **Best for cloud governance** .

### Policy & Governance

- **[Open Policy Agent (OPA)](https://github.com/open-policy-agent/opa)**  
  **General-purpose policy engine**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Unified policy enforcement across cloud, Kubernetes, and CI/CD** . **The standard for policy-as-code** .
- **[Kyverno](https://github.com/kyverno/kyverno)**  
  **Kubernetes-native policy management**, Apache-2.0 licensed with **6,000+ GitHub stars** . **Policy as Kubernetes resources** . **Best for Kubernetes policy** .
- **[Gatekeeper](https://github.com/open-policy-agent/gatekeeper)**  
  **OPA-based Kubernetes policy controller**, Apache-2.0 licensed . **Policy enforcement for Kubernetes** . **Best for Kubernetes admission control** .

### Additional Strong Open-Source Options

- **AWS CloudFormation** — AWS-native IaC (not open-source but free) .
- **Troposphere** — Python library for CloudFormation templates .
- **AWS CDK** — IaC with programming languages (open-source) .
- **SST** — Serverless stack for AWS (open-source) .
- **Serverless Framework** — Serverless deployment (open-source) .
- **LocalStack** — Local AWS cloud stack (open-source) .
- **Moto** — Mock AWS services for testing (open-source) .
- **Checkov** — IaC security scanning (open-source) .
- **tfsec** — Terraform security scanning (open-source) .
- **Infracost** — Cloud cost estimation for IaC (open-source) .

**Frameworks for building custom cloud resource management solutions**: Combine **Terraform** or **OpenTofu** for multi-cloud IaC . Use **Pulumi** for IaC with real programming languages . Deploy **Crossplane** for Kubernetes-native cloud resource management . Choose **Terragrunt** or **Terramate** for orchestration at scale . Integrate **Atlantis** for PR-based Terraform workflows . Use **Open Policy Agent** for policy-as-code . Note that true enterprise cloud management with managed state, policy enforcement, and cost optimization (Terraform Cloud, Spacelift, Scalr) remains primarily commercial territory; open-source stacks provide strong IaC, orchestration, and policy foundations that require integration for complete cloud governance.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Cloud resource management APIs control infrastructure and credentials. **Secure state files and secrets** — state contains sensitive data . Self-hosted solutions require proper security hardening.
- **Terraform's BSL license** prompted the creation of **OpenTofu** under Linux Foundation governance . Evaluate licensing against your use case.
- **State management is critical** — remote state backends (S3, GCS, Azure Blob) with locking are essential for team collaboration . Never commit state files to Git.
- **IaC security scanning is essential** — use Checkov, tfsec, or similar tools to catch misconfigurations before deployment .
- The open-source ecosystem provides strong IaC, orchestration, and policy foundations, but **managed state, policy enforcement, and cost optimization** remain primarily commercial offerings.

---

**Made for platform engineers, cloud architects, and organizations seeking cloud management sovereignty.**  
Let's make unified cloud resource management more open, transparent, and programmable.
