---
class_count: 12
classes:
- AutoScalingConfiguration
- ConnectionSummary
- OperationSummary
- Service
- CreateServiceRequest
- UpdateServiceRequest
- Tag
- CustomDomain
- Connection
- VpcConnector
- VpcDNSTarget
- ServiceSummary
context_file: json-ld/aws-app-runner-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-runner/refs/heads/main/json-ld/aws-app-runner-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Runner from AWS App Runner.
layout: jsonld
name: Aws App Runner Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: InstanceConfiguration
  type: reference
- container: ''
  name: ObservabilityConfiguration
  type: reference
- container: ''
  name: AutoScalingConfigurationSummary
  type: reference
- container: ''
  name: SourceConfiguration
  type: reference
- container: ''
  name: HealthCheckConfiguration
  type: reference
- container: ''
  name: Cpu
  type: string
- container: ''
  name: Memory
  type: string
- container: ''
  name: InstanceRoleArn
  type: string
- container: ''
  name: VpcIngressConnectionArn
  type: string
- container: ''
  name: VpcId
  type: string
- container: ''
  name: DomainName
  type: string
- container: ''
  name: ConnectionName
  type: string
- container: ''
  name: ConnectionArn
  type: string
- container: ''
  name: ProviderType
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: CreatedAt
  type: dateTime
- container: ''
  name: ServiceName
  type: string
- container: set
  name: Tags
  type: reference
- container: ''
  name: EncryptionConfiguration
  type: reference
- container: ''
  name: AutoScalingConfigurationArn
  type: string
- container: ''
  name: NetworkConfiguration
  type: reference
- container: ''
  name: ServiceId
  type: string
- container: ''
  name: ServiceArn
  type: string
- container: ''
  name: ServiceUrl
  type: string
- container: ''
  name: UpdatedAt
  type: dateTime
- container: ''
  name: DeletedAt
  type: dateTime
- container: ''
  name: AutoScalingConfigurationName
  type: string
- container: ''
  name: AutoScalingConfigurationRevision
  type: integer
- container: ''
  name: HasAssociatedService
  type: boolean
- container: ''
  name: IsDefault
  type: boolean
- container: ''
  name: VpcConnectorName
  type: string
- container: ''
  name: VpcConnectorArn
  type: string
- container: ''
  name: VpcConnectorRevision
  type: integer
- container: set
  name: Subnets
  type: string
- container: set
  name: SecurityGroups
  type: string
- container: ''
  name: ObservabilityConfigurationArn
  type: string
- container: ''
  name: ObservabilityConfigurationName
  type: string
- container: ''
  name: ObservabilityConfigurationRevision
  type: integer
- container: ''
  name: Latest
  type: boolean
- container: ''
  name: TraceConfiguration
  type: reference
- container: ''
  name: Protocol
  type: string
- container: ''
  name: Path
  type: string
- container: ''
  name: Interval
  type: integer
- container: ''
  name: Timeout
  type: integer
- container: ''
  name: HealthyThreshold
  type: integer
- container: ''
  name: UnhealthyThreshold
  type: integer
- container: ''
  name: Key
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: MaxConcurrency
  type: integer
- container: ''
  name: MinSize
  type: integer
- container: ''
  name: MaxSize
  type: integer
- container: ''
  name: Id
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: TargetArn
  type: string
- container: ''
  name: StartedAt
  type: dateTime
- container: ''
  name: EndedAt
  type: dateTime
- container: ''
  name: CodeRepository
  type: reference
- container: ''
  name: ImageRepository
  type: reference
- container: ''
  name: AutoDeploymentsEnabled
  type: boolean
- container: ''
  name: AuthenticationConfiguration
  type: reference
- container: ''
  name: EnableWWWSubdomain
  type: boolean
- container: set
  name: CertificateValidationRecords
  type: reference
property_count: 62
provider_name: AWS App Runner
provider_slug: aws-app-runner
slug: aws-app-runner-context
tags:
- AWS
- CI/CD
- Containers
- Deployment
- Microservices
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
