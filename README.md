# Amazon Data Lifecycle Manager

Amazon Data Lifecycle Manager provides an automated way to manage the lifecycle of your AWS resources. Using lifecycle policies, you can automate the creation, retention, and deletion of Amazon EBS snapshots and EBS-backed AMIs, reducing storage costs and simplifying backup management. Policies target EBS volumes and EC2 instances using tags, execute on configurable schedules, and apply flexible retention rules based on count or age.

## APIs

### Amazon Data Lifecycle Manager API

The Amazon Data Lifecycle Manager API enables programmatic management of lifecycle policies for automating the creation, retention, and deletion of EBS snapshots and AMIs to meet backup and compliance requirements.

- **Base URL:** https://dlm.amazonaws.com
- **Documentation:** https://docs.aws.amazon.com/dlm/latest/APIReference/Welcome.html
- **OpenAPI:** [openapi/amazon-data-lifecycle-manager-openapi.yml](openapi/amazon-data-lifecycle-manager-openapi.yml)

**Tags:** Automation, EBS Snapshots, Lifecycle Management, Backup, AMI Management

## Artifacts

| Type | Count | Location |
|------|-------|----------|
| OpenAPI Specs | 1 | [openapi/](openapi/) |
| JSON Schemas | 15 | [json-schema/](json-schema/) |
| JSON Structures | 15 | [json-structure/](json-structure/) |
| Examples | 15 | [examples/](examples/) |
| JSON-LD Contexts | 1 | [json-ld/](json-ld/) |
| Spectral Rules | 1 | [rules/](rules/) |
| Vocabulary | 1 | [vocabulary/](vocabulary/) |
| Naftiko Capabilities | 2 | [capabilities/](capabilities/) |

## Features

- **EBS Snapshot Automation** — Automatically create, copy, and delete EBS snapshots on configurable schedules using tag-based targeting of volumes across AWS accounts.
- **AMI Lifecycle Management** — Automate the creation and deregistration of Amazon Machine Images from EC2 instances on schedules to maintain a library of AMIs.
- **Flexible Retention Rules** — Retain snapshots by count (keep the last N) or by age (keep for N days/weeks/months/years), automatically deleting older snapshots.
- **Tag-Based Targeting** — Target EBS volumes or EC2 instances using resource tags for policy scope, enabling granular backup control without managing resource lists.
- **Cross-Region Copy** — Configure schedules to copy snapshots to other AWS regions for disaster recovery and geographic redundancy automatically.
- **Fast Snapshot Restore** — Enable fast snapshot restore on snapshots created by DLM policies to dramatically reduce EBS volume initialization time.
- **Event-Based Policies** — Trigger snapshot sharing and copying workflows in response to CloudWatch Events for cross-account snapshot automation.

## Use Cases

- **Automated Daily Backups** — Schedule daily EBS volume snapshots with automated retention of the last 7 or 30 days of backups without manual intervention.
- **Compliance and Audit Retention** — Meet regulatory backup retention requirements by defining long-term retention policies (monthly/yearly) for compliance snapshots.
- **Disaster Recovery** — Automatically copy EBS snapshots to secondary AWS regions to enable cross-region disaster recovery with minimal RTO and RPO.
- **Golden AMI Pipeline** — Automate the creation of hardened EC2 AMI images from approved instances and manage their lifecycle for deployment fleets.
- **Storage Cost Optimization** — Reduce EBS snapshot storage costs by automatically deleting outdated snapshots based on configurable age or count retention rules.

## Integrations

- **Amazon EBS** — Native integration with Amazon EBS for snapshot creation, retention, and deletion of volumes across the AWS account.
- **Amazon EC2** — Target EC2 instances with IMAGE_MANAGEMENT policies to automate AMI creation from running or stopped instances.
- **Amazon CloudWatch** — Event-based DLM policies are triggered by Amazon CloudWatch Events for cross-account snapshot sharing scenarios.
- **AWS Backup** — Complementary to DLM, AWS Backup provides centralized backup management across multiple AWS services including EBS, RDS, and DynamoDB.
- **AWS IAM** — DLM uses IAM execution roles to assume permissions for creating and deleting snapshots on behalf of the lifecycle policy.
- **AWS Organizations** — Cross-account snapshot sharing policies use AWS Organizations to share EBS snapshots with member accounts automatically.

## Resources

- [Portal](https://aws.amazon.com/ebs/data-lifecycle-manager/)
- [Documentation](https://docs.aws.amazon.com/dlm/)
- [Getting Started](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/snapshot-lifecycle.html)
- [GitHub Organization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/ec2/v2/home#Lifecycle)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Terms of Service](https://aws.amazon.com/service-terms/)
- [Privacy Policy](https://aws.amazon.com/privacy/)

## Maintainers

- **Kin Lane** — kin@apievangelist.com
