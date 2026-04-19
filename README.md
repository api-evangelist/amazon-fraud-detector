# Amazon Fraud Detector (amazon-fraud-detector)

Amazon Fraud Detector is a fully managed service that uses machine learning to identify potentially fraudulent activities and accurately distinguish between legitimate and high-risk transactions. It uses your data and the same technology that Amazon uses to protect its own business from fraud.

**URL:** [https://raw.githubusercontent.com/api-evangelist/amazon-fraud-detector/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amazon-fraud-detector/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Financial Services, Fraud Detection, Machine Learning, Security

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon Fraud Detector API
The Amazon Fraud Detector API provides programmatic access to create and manage detectors, models, event types, entities, labels, outcomes, rules, and variables for automated fraud detection workflows.

**Human URL:** [https://aws.amazon.com/fraud-detector/](https://aws.amazon.com/fraud-detector/)

#### Tags:

 - Fraud Detection, Machine Learning, Security

#### Properties

- [Documentation](https://docs.aws.amazon.com/frauddetector/latest/ug/what-is-frauddetector.html)
- [OpenAPI](openapi/amazon-fraud-detector-openapi.yml)
- [JSONSchema](json-schema/amazon-fraud-detector-detector-schema.json)
- [JSONSchema](json-schema/amazon-fraud-detector-model-schema.json)
- [JSONSchema](json-schema/amazon-fraud-detector-rule-schema.json)
- [JSONSchema](json-schema/amazon-fraud-detector-event-type-schema.json)
- [JSONSchema](json-schema/amazon-fraud-detector-tag-schema.json)
- [JSONStructure](json-structure/amazon-fraud-detector-detector-structure.json)
- [JSONStructure](json-structure/amazon-fraud-detector-model-structure.json)
- [JSONStructure](json-structure/amazon-fraud-detector-rule-structure.json)
- [JSONStructure](json-structure/amazon-fraud-detector-event-type-structure.json)
- [JSONStructure](json-structure/amazon-fraud-detector-tag-structure.json)
- [Example](examples/amazon-fraud-detector-detector-example.json)
- [Example](examples/amazon-fraud-detector-model-example.json)
- [Example](examples/amazon-fraud-detector-rule-example.json)
- [Example](examples/amazon-fraud-detector-event-type-example.json)
- [Example](examples/amazon-fraud-detector-tag-example.json)
- [GettingStarted](https://aws.amazon.com/fraud-detector/getting-started/)
- [Pricing](https://aws.amazon.com/fraud-detector/pricing/)
- [FAQ](https://aws.amazon.com/fraud-detector/faqs/)
- [APIReference](https://docs.aws.amazon.com/frauddetector/latest/api/Welcome.html)

## Common Properties

- [Portal](https://aws.amazon.com/fraud-detector/)
- [Website](https://aws.amazon.com/fraud-detector/)
- [Documentation](https://docs.aws.amazon.com/frauddetector/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/machine-learning/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/frauddetector/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/amazon-fraud-detector)
- [SpectralRules](rules/amazon-fraud-detector-spectral-rules.yml)
- [NaftikoCapability](capabilities/shared/fraud-detector.yaml)
- [NaftikoCapability](capabilities/amazon-fraud-detector-real-time-detection.yaml)
- [Vocabulary](vocabulary/amazon-fraud-detector-vocabulary.yaml)
- [JSON-LD](json-ld/amazon-fraud-detector-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| No ML Expertise Required | Automatically trains and deploys ML models using your historical transaction data without requiring ML expertise. |
| Real-Time Fraud Scoring | Returns fraud scores within milliseconds for integration into transaction approval flows. |
| Pre-Built Models | Online Fraud Insights (OFI), Transaction Fraud Insights (TFI), and Account Takeover Insights (ATI) pre-trained model types. |
| Rule Engine | DETECTORPL rule language allows writing conditional logic using model scores and event variables. |
| Model Explainability | Variable importance scores explain which factors most influenced a fraud prediction. |
| Cold Start Protection | Uses Amazon fraud experience to provide immediate predictions even with limited historical data. |
| Event Ingestion | Ingest historical labeled events to continuously improve model accuracy over time. |

## Use Cases

| Name | Description |
|------|-------------|
| Payment Fraud Detection | Score credit card and payment transactions in real-time to block fraudulent purchases. |
| Account Takeover Prevention | Detect unauthorized login attempts and account compromise using behavioral signals. |
| New Account Fraud | Identify fraudulent new account registrations at signup to prevent synthetic identity fraud. |
| Promotion Abuse Detection | Flag users abusing discount codes, referral bonuses, and promotional offers. |
| Chargeback Prevention | Reduce chargeback rates by blocking high-risk transactions before they complete. |
| Insurance Claims Fraud | Score insurance claims for fraudulent patterns in real-time during claim submission. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Store training datasets and export labeled event data to S3 for model training. |
| AWS IAM | Control access to detectors, models, and predictions using IAM roles and policies. |
| Amazon SageMaker | Combine Fraud Detector with SageMaker for custom ML pipelines and model integration. |
| Amazon CloudWatch | Monitor prediction volumes, model performance, and API error rates. |
| AWS KMS | Encrypt training data and model artifacts with customer-managed KMS keys. |
| Amazon EventBridge | Route fraud detection outcomes to downstream systems for automated response workflows. |
| Amazon SNS | Send real-time fraud alert notifications to operations teams via SNS topics. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-fraud-detector-openapi.yml](openapi/amazon-fraud-detector-openapi.yml)

### JSON Schema

- [amazon-fraud-detector-detector-schema.json](json-schema/amazon-fraud-detector-detector-schema.json)
- [amazon-fraud-detector-event-type-schema.json](json-schema/amazon-fraud-detector-event-type-schema.json)
- [amazon-fraud-detector-model-schema.json](json-schema/amazon-fraud-detector-model-schema.json)
- [amazon-fraud-detector-rule-schema.json](json-schema/amazon-fraud-detector-rule-schema.json)
- [amazon-fraud-detector-tag-schema.json](json-schema/amazon-fraud-detector-tag-schema.json)

### JSON Structure

- [amazon-fraud-detector-detector-structure.json](json-structure/amazon-fraud-detector-detector-structure.json)
- [amazon-fraud-detector-event-type-structure.json](json-structure/amazon-fraud-detector-event-type-structure.json)
- [amazon-fraud-detector-model-structure.json](json-structure/amazon-fraud-detector-model-structure.json)
- [amazon-fraud-detector-rule-structure.json](json-structure/amazon-fraud-detector-rule-structure.json)
- [amazon-fraud-detector-tag-structure.json](json-structure/amazon-fraud-detector-tag-structure.json)

### JSON-LD

- [amazon-fraud-detector-context.jsonld](json-ld/amazon-fraud-detector-context.jsonld)

### Examples

- [amazon-fraud-detector-detector-example.json](examples/amazon-fraud-detector-detector-example.json)
- [amazon-fraud-detector-event-type-example.json](examples/amazon-fraud-detector-event-type-example.json)
- [amazon-fraud-detector-model-example.json](examples/amazon-fraud-detector-model-example.json)
- [amazon-fraud-detector-rule-example.json](examples/amazon-fraud-detector-rule-example.json)
- [amazon-fraud-detector-tag-example.json](examples/amazon-fraud-detector-tag-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [fraud-detector.yaml](capabilities/shared/fraud-detector.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [amazon-fraud-detector-real-time-detection.yaml](capabilities/amazon-fraud-detector-real-time-detection.yaml) | Amazon Fraud Detector API | — | Platform Engineers, DevOps |

## Vocabulary

- [Amazon Fraud Detector Vocabulary](vocabulary/amazon-fraud-detector-vocabulary.yaml)

## Rules

- [amazon-fraud-detector-spectral-rules.yml](rules/amazon-fraud-detector-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
