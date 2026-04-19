# Amazon CodePipeline

AWS CodePipeline is a fully managed continuous delivery service that helps you automate your release pipelines for fast and reliable application and infrastructure updates. CodePipeline automates the build, test, and deploy phases of your release process every time there is a code change, based on the release model you define.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/amazon-codepipeline/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Amazon, AWS, CI/CD, Continuous Delivery, DevOps, Pipeline, Release Automation

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon CodePipeline API

The Amazon CodePipeline REST API.

**Human URL:** [https://docs.aws.amazon.com/codepipeline/latest/APIReference/Welcome.html](https://docs.aws.amazon.com/codepipeline/latest/APIReference/Welcome.html)

#### Tags:

 - Amazon, AWS, CI/CD, Continuous Delivery, DevOps

#### Properties

- [Documentation](https://docs.aws.amazon.com/codepipeline/)
- [APIReference](https://docs.aws.amazon.com/codepipeline/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-codepipeline-openapi-original.yaml)

## Common Properties

- [GettingStarted](https://docs.aws.amazon.com/codepipeline)
- [Pricing](https://aws.amazon.com/codepipeline/pricing/)
- [Console](https://console.aws.amazon.com/codepipeline/)
- [Portal](https://aws.amazon.com/codepipeline/)
- [Documentation](https://docs.aws.amazon.com/codepipeline/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Blog](https://aws.amazon.com/blogs/devops/)
- [SignUp](https://portal.aws.amazon.com/gp/aws/developer/registration/index.html)
- [GitHubOrganization](https://github.com/aws)

## Features

| Name | Description |
|------|-------------|
| Pipeline Automation | Automate the entire release process from source code to production with customizable pipeline stages and actions. |
| Parallel Execution | Run multiple actions in parallel within a pipeline stage to speed up your delivery workflows. |
| Manual Approval Actions | Add manual approval gates to pipelines for human review before promoting changes to production environments. |
| Pipeline Conditions | Define conditions that must be met for a pipeline to proceed, including CloudWatch alarms and custom conditions. |
| Cross-Account Deployments | Deploy to multiple AWS accounts and regions from a single pipeline using cross-account roles and artifact stores. |
| Custom Actions | Create custom pipeline actions using Lambda functions or CodeBuild projects for specialized workflow steps. |
| Execution History | Track the full execution history of each pipeline run including status, timing, and artifact details for each action. |

## Use Cases

| Name | Description |
|------|-------------|
| Continuous Delivery Pipeline | Automate the entire software delivery lifecycle from source commit through build, test, staging, and production deployme |
| Multi-Environment Promotion | Automatically promote changes through development, staging, and production environments with approval gates between stag |
| Infrastructure as Code Deployment | Deploy CloudFormation stacks and Terraform configurations as pipeline stages for automated infrastructure provisioning. |
| Microservices Delivery | Orchestrate independent delivery pipelines for multiple microservices, each triggered by its own source repository. |
| Blue/Green Deployments | Use CodeDeploy actions in pipelines to implement zero-downtime blue/green deployments automatically. |

## Integrations

| Name | Description |
|------|-------------|
| AWS CodeBuild | Use CodeBuild as the build and test stage in pipelines. |
| AWS CodeDeploy | Use CodeDeploy as the deployment stage for EC2, Lambda, and ECS targets. |
| AWS CodeCommit | Trigger pipelines automatically on CodeCommit repository changes. |
| GitHub | Connect GitHub repositories as pipeline source stages with webhook triggers. |
| Amazon S3 | Use S3 as a source stage or for storing pipeline artifacts between stages. |
| AWS CloudFormation | Deploy infrastructure as code using CloudFormation actions in pipeline stages. |
| AWS Elastic Beanstalk | Deploy application updates to Elastic Beanstalk environments from pipelines. |
| Amazon ECS | Deploy container updates to ECS services as a pipeline deployment stage. |
| Amazon EventBridge | Trigger pipelines from EventBridge events for event-driven delivery workflows. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-codepipeline-openapi-original](openapi/amazon-codepipeline-openapi-original.yaml)
- [amazon-codepipeline-openapi](openapi/amazon-codepipeline-openapi.yml)

### JSON Schema

314 JSON Schema files generated from the OpenAPI specification.

- [amazon-codepipeline-access-key-id-schema](json-schema/amazon-codepipeline-access-key-id-schema.json)
- [amazon-codepipeline-account-id-schema](json-schema/amazon-codepipeline-account-id-schema.json)
- [amazon-codepipeline-acknowledge-job-input-schema](json-schema/amazon-codepipeline-acknowledge-job-input-schema.json)
- [amazon-codepipeline-acknowledge-job-output-schema](json-schema/amazon-codepipeline-acknowledge-job-output-schema.json)
- [amazon-codepipeline-acknowledge-third-party-job-input-schema](json-schema/amazon-codepipeline-acknowledge-third-party-job-input-schema.json)
- ...and 309 more in [json-schema/](json-schema/)

### JSON Structure

314 JSON Structure files in [json-structure/](json-structure/).

### JSON-LD

- [amazon-codepipeline-context](json-ld/amazon-codepipeline-context.jsonld)

### Examples

314 example JSON files in [examples/](examples/).

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [codepipeline](capabilities/shared/codepipeline.yaml) — 39 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon CodePipeline Release Pipeline Automation](capabilities/amazon-codepipeline-release-pipeline.yaml) | codepipeline | 14 | DevOps Engineer |

## Vocabulary

- [amazon-codepipeline-vocabulary](vocabulary/amazon-codepipeline-vocabulary.yaml) — Unified taxonomy mapping 1 resources, 5 actions, 1 workflows, and 3 personas

## Rules

- [amazon-codepipeline-spectral-rules](rules/amazon-codepipeline-spectral-rules.yml) — 10 rules enforcing Amazon CodePipeline API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
