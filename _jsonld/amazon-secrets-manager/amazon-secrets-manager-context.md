---
api_specs:
- filename: amazon-secrets-manager-openapi.yml
  format: yaml
  label: Amazon Secrets Manager API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-secrets-manager/refs/heads/main/openapi/amazon-secrets-manager-openapi.yml
class_count: 6
classes:
- Secret
- RotationRules
- SecretValue
- Tag
- ListSecretsResponse
- GetRandomPasswordResponse
context_file: json-ld/amazon-secrets-manager-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-secrets-manager/refs/heads/main/json-ld/amazon-secrets-manager-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Secrets Manager from Amazon Secrets Manager.
layout: jsonld
name: Amazon Secrets Manager Context
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
  name: ARN
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: KmsKeyId
  type: string
- container: ''
  name: RotationEnabled
  type: boolean
- container: ''
  name: RotationLambdaARN
  type: string
- container: ''
  name: LastRotatedDate
  type: dateTime
- container: ''
  name: LastChangedDate
  type: dateTime
- container: ''
  name: LastAccessedDate
  type: dateTime
- container: ''
  name: DeletedDate
  type: dateTime
- container: set
  name: Tags
  type: string
- container: ''
  name: SecretVersionsToStages
  type: string
- container: ''
  name: OwningService
  type: string
- container: ''
  name: CreatedDate
  type: dateTime
- container: ''
  name: PrimaryRegion
  type: string
- container: ''
  name: VersionId
  type: string
- container: ''
  name: SecretBinary
  type: string
- container: ''
  name: SecretString
  type: string
- container: set
  name: VersionStages
  type: string
- container: ''
  name: AutomaticallyAfterDays
  type: integer
- container: ''
  name: Duration
  type: string
- container: ''
  name: ScheduleExpression
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: Value
  type: string
- container: set
  name: SecretList
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: RandomPassword
  type: string
property_count: 27
provider_name: Amazon Secrets Manager
provider_slug: amazon-secrets-manager
slug: amazon-secrets-manager-context
source_filename: amazon-secrets-manager-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Secret\": \"aws:Secret\",\n    \"ARN\": {\n      \"@id\": \"aws:ARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"aws:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"aws:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KmsKeyId\": {\n      \"@id\": \"aws:KmsKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RotationEnabled\": {\n      \"@id\": \"aws:RotationEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"RotationLambdaARN\": {\n      \"@id\": \"aws:RotationLambdaARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RotationRules\": \"aws:RotationRules\",\n    \"LastRotatedDate\": {\n      \"@id\": \"aws:LastRotatedDate\",\n \
  \     \"@type\": \"xsd:dateTime\"\n    },\n    \"LastChangedDate\": {\n      \"@id\": \"aws:LastChangedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LastAccessedDate\": {\n      \"@id\": \"aws:LastAccessedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"DeletedDate\": {\n      \"@id\": \"aws:DeletedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Tags\": {\n      \"@id\": \"aws:Tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SecretVersionsToStages\": {\n      \"@id\": \"aws:SecretVersionsToStages\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OwningService\": {\n      \"@id\": \"aws:OwningService\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedDate\": {\n      \"@id\": \"aws:CreatedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"PrimaryRegion\": {\n      \"@id\": \"aws:PrimaryRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SecretValue\": \"aws:SecretValue\",\n    \"VersionId\": {\n\
  \      \"@id\": \"aws:VersionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SecretBinary\": {\n      \"@id\": \"aws:SecretBinary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SecretString\": {\n      \"@id\": \"aws:SecretString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VersionStages\": {\n      \"@id\": \"aws:VersionStages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AutomaticallyAfterDays\": {\n      \"@id\": \"aws:AutomaticallyAfterDays\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Duration\": {\n      \"@id\": \"aws:Duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ScheduleExpression\": {\n      \"@id\": \"aws:ScheduleExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tag\": \"aws:Tag\",\n    \"Key\": {\n      \"@id\": \"aws:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"aws:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListSecretsResponse\": \"aws:ListSecretsResponse\"\
  ,\n    \"SecretList\": {\n      \"@id\": \"aws:SecretList\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"aws:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetRandomPasswordResponse\": \"aws:GetRandomPasswordResponse\",\n    \"RandomPassword\": {\n      \"@id\": \"aws:RandomPassword\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-secrets-manager/refs/heads/main/json-ld/amazon-secrets-manager-context.jsonld
tags:
- Configuration
- Credentials
- Rotation
- Secrets
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
