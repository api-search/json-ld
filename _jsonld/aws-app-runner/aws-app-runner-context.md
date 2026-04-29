---
api_specs:
- filename: aws-app-runner-openapi.yml
  format: yaml
  label: AWS App Runner
  slug: aws-app-runner
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-app-runner/refs/heads/main/openapi/aws-app-runner-openapi.yml
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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AutoScalingConfiguration\": \"aws:AutoScalingConfiguration\",\n    \"ConnectionSummary\": \"aws:ConnectionSummary\",\n    \"InstanceConfiguration\": {\n      \"@id\": \"aws:InstanceConfiguration\",\n      \"@type\": \"@id\"\n    },\n    \"ObservabilityConfiguration\": {\n      \"@id\": \"aws:ObservabilityConfiguration\",\n      \"@type\": \"@id\"\n    },\n    \"OperationSummary\": \"aws:OperationSummary\",\n    \"Service\": \"aws:Service\",\n    \"CreateServiceRequest\": \"aws:CreateServiceRequest\",\n    \"AutoScalingConfigurationSummary\": {\n      \"@id\": \"aws:AutoScalingConfigurationSummary\",\n      \"@type\": \"@id\"\n    },\n    \"SourceConfiguration\": {\n      \"@id\": \"aws:SourceConfiguration\",\n      \"@type\": \"@id\"\
  \n    },\n    \"UpdateServiceRequest\": \"aws:UpdateServiceRequest\",\n    \"Tag\": \"aws:Tag\",\n    \"CustomDomain\": \"aws:CustomDomain\",\n    \"Connection\": \"aws:Connection\",\n    \"VpcConnector\": \"aws:VpcConnector\",\n    \"VpcDNSTarget\": \"aws:VpcDNSTarget\",\n    \"HealthCheckConfiguration\": {\n      \"@id\": \"aws:HealthCheckConfiguration\",\n      \"@type\": \"@id\"\n    },\n    \"ServiceSummary\": \"aws:ServiceSummary\",\n    \"Cpu\": {\n      \"@id\": \"aws:Cpu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Memory\": {\n      \"@id\": \"aws:Memory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceRoleArn\": {\n      \"@id\": \"aws:InstanceRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcIngressConnectionArn\": {\n      \"@id\": \"aws:VpcIngressConnectionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcId\": {\n      \"@id\": \"aws:VpcId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DomainName\": {\n      \"@id\": \"aws:DomainName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectionName\": {\n      \"@id\": \"aws:ConnectionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectionArn\": {\n      \"@id\": \"aws:ConnectionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProviderType\": {\n      \"@id\": \"aws:ProviderType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"aws:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedAt\": {\n      \"@id\": \"aws:CreatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ServiceName\": {\n      \"@id\": \"aws:ServiceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"aws:Tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"EncryptionConfiguration\": {\n      \"@id\": \"aws:EncryptionConfiguration\",\n      \"@type\": \"@id\"\n    },\n    \"AutoScalingConfigurationArn\": {\n      \"@id\": \"aws:AutoScalingConfigurationArn\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"NetworkConfiguration\": {\n      \"@id\": \"aws:NetworkConfiguration\",\n      \"@type\": \"@id\"\n    },\n    \"ServiceId\": {\n      \"@id\": \"aws:ServiceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceArn\": {\n      \"@id\": \"aws:ServiceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceUrl\": {\n      \"@id\": \"aws:ServiceUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdatedAt\": {\n      \"@id\": \"aws:UpdatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"DeletedAt\": {\n      \"@id\": \"aws:DeletedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"AutoScalingConfigurationName\": {\n      \"@id\": \"aws:AutoScalingConfigurationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AutoScalingConfigurationRevision\": {\n      \"@id\": \"aws:AutoScalingConfigurationRevision\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"HasAssociatedService\": {\n      \"@id\": \"aws:HasAssociatedService\",\n      \"\
  @type\": \"xsd:boolean\"\n    },\n    \"IsDefault\": {\n      \"@id\": \"aws:IsDefault\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"VpcConnectorName\": {\n      \"@id\": \"aws:VpcConnectorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcConnectorArn\": {\n      \"@id\": \"aws:VpcConnectorArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcConnectorRevision\": {\n      \"@id\": \"aws:VpcConnectorRevision\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Subnets\": {\n      \"@id\": \"aws:Subnets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SecurityGroups\": {\n      \"@id\": \"aws:SecurityGroups\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ObservabilityConfigurationArn\": {\n      \"@id\": \"aws:ObservabilityConfigurationArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ObservabilityConfigurationName\": {\n      \"@id\": \"aws:ObservabilityConfigurationName\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"ObservabilityConfigurationRevision\": {\n      \"@id\": \"aws:ObservabilityConfigurationRevision\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Latest\": {\n      \"@id\": \"aws:Latest\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"TraceConfiguration\": {\n      \"@id\": \"aws:TraceConfiguration\",\n      \"@type\": \"@id\"\n    },\n    \"Protocol\": {\n      \"@id\": \"aws:Protocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Path\": {\n      \"@id\": \"aws:Path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Interval\": {\n      \"@id\": \"aws:Interval\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Timeout\": {\n      \"@id\": \"aws:Timeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"HealthyThreshold\": {\n      \"@id\": \"aws:HealthyThreshold\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"UnhealthyThreshold\": {\n      \"@id\": \"aws:UnhealthyThreshold\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Key\": {\n    \
  \  \"@id\": \"aws:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"aws:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxConcurrency\": {\n      \"@id\": \"aws:MaxConcurrency\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"MinSize\": {\n      \"@id\": \"aws:MinSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"MaxSize\": {\n      \"@id\": \"aws:MaxSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Id\": {\n      \"@id\": \"aws:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"aws:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TargetArn\": {\n      \"@id\": \"aws:TargetArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartedAt\": {\n      \"@id\": \"aws:StartedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"EndedAt\": {\n      \"@id\": \"aws:EndedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"CodeRepository\": {\n      \"@id\": \"aws:CodeRepository\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"ImageRepository\": {\n      \"@id\": \"aws:ImageRepository\",\n      \"@type\": \"@id\"\n    },\n    \"AutoDeploymentsEnabled\": {\n      \"@id\": \"aws:AutoDeploymentsEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"AuthenticationConfiguration\": {\n      \"@id\": \"aws:AuthenticationConfiguration\",\n      \"@type\": \"@id\"\n    },\n    \"EnableWWWSubdomain\": {\n      \"@id\": \"aws:EnableWWWSubdomain\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"CertificateValidationRecords\": {\n      \"@id\": \"aws:CertificateValidationRecords\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-runner/refs/heads/main/json-ld/aws-app-runner-context.jsonld
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
