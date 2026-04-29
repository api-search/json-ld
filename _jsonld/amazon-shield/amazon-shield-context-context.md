---
class_count: 14
classes:
- AttackDetail
- CreateProtectionGroupRequest
- CreateProtectionRequest
- CreateProtectionResponse
- DescribeAttackRequest
- DescribeAttackResponse
- DescribeProtectionRequest
- DescribeProtectionResponse
- ListProtectionsRequest
- ListProtectionsResponse
- Mitigation
- SummarizedCounter
- Tag
- Amazon Shield Protection
context_file: json-ld/amazon-shield-context-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-shield/refs/heads/main/json-ld/amazon-shield-context-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Shield from Amazon Shield.
layout: jsonld
name: Amazon Shield Context
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
  name: Protection
  type: string
- container: ''
  name: AttackId
  type: string
- container: ''
  name: ResourceArn
  type: string
- container: ''
  name: StartTime
  type: dateTime
- container: ''
  name: EndTime
  type: dateTime
- container: set
  name: AttackCounters
  type: string
- container: set
  name: Mitigations
  type: string
- container: ''
  name: ProtectionGroupId
  type: string
- container: ''
  name: Aggregation
  type: string
- container: ''
  name: Pattern
  type: string
- container: ''
  name: ResourceType
  type: string
- container: set
  name: Members
  type: string
- container: ''
  name: Name
  type: string
- container: set
  name: Tags
  type: string
- container: ''
  name: ProtectionId
  type: string
- container: ''
  name: Attack
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: MaxResults
  type: integer
- container: set
  name: Protections
  type: string
- container: ''
  name: MitigationName
  type: string
- container: ''
  name: Id
  type: string
- container: set
  name: HealthCheckIds
  type: string
- container: ''
  name: ProtectionArn
  type: string
- container: ''
  name: Max
  type: decimal
- container: ''
  name: Average
  type: decimal
- container: ''
  name: Sum
  type: decimal
- container: ''
  name: N
  type: integer
- container: ''
  name: Unit
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: ApplicationLayerAutomaticResponseConfiguration
  type: string
property_count: 31
provider_name: Amazon Shield
provider_slug: amazon-shield
slug: amazon-shield-context-context
source_filename: amazon-shield-context-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AttackDetail\": \"aws:AttackDetail\",\n    \"CreateProtectionGroupRequest\": \"aws:CreateProtectionGroupRequest\",\n    \"CreateProtectionRequest\": \"aws:CreateProtectionRequest\",\n    \"CreateProtectionResponse\": \"aws:CreateProtectionResponse\",\n    \"DescribeAttackRequest\": \"aws:DescribeAttackRequest\",\n    \"DescribeAttackResponse\": \"aws:DescribeAttackResponse\",\n    \"DescribeProtectionRequest\": \"aws:DescribeProtectionRequest\",\n    \"DescribeProtectionResponse\": \"aws:DescribeProtectionResponse\",\n    \"ListProtectionsRequest\": \"aws:ListProtectionsRequest\",\n    \"ListProtectionsResponse\": \"aws:ListProtectionsResponse\",\n    \"Mitigation\": \"aws:Mitigation\",\n    \"Protection\": {\n      \"@id\": \"aws:Protection\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"SummarizedCounter\": \"aws:SummarizedCounter\",\n    \"Tag\": \"aws:Tag\",\n    \"Amazon Shield Protection\": \"aws:Amazon Shield Protection\",\n    \"AttackId\": {\n      \"@id\": \"aws:AttackId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceArn\": {\n      \"@id\": \"aws:ResourceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartTime\": {\n      \"@id\": \"aws:StartTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"EndTime\": {\n      \"@id\": \"aws:EndTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"AttackCounters\": {\n      \"@id\": \"aws:AttackCounters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Mitigations\": {\n      \"@id\": \"aws:Mitigations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProtectionGroupId\": {\n      \"@id\": \"aws:ProtectionGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Aggregation\":\
  \ {\n      \"@id\": \"aws:Aggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Pattern\": {\n      \"@id\": \"aws:Pattern\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceType\": {\n      \"@id\": \"aws:ResourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Members\": {\n      \"@id\": \"aws:Members\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"aws:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"aws:Tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProtectionId\": {\n      \"@id\": \"aws:ProtectionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Attack\": {\n      \"@id\": \"aws:Attack\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"aws:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxResults\": {\n      \"@id\": \"aws:MaxResults\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"Protections\": {\n      \"@id\": \"aws:Protections\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MitigationName\": {\n      \"@id\": \"aws:MitigationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"aws:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HealthCheckIds\": {\n      \"@id\": \"aws:HealthCheckIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProtectionArn\": {\n      \"@id\": \"aws:ProtectionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Max\": {\n      \"@id\": \"aws:Max\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"Average\": {\n      \"@id\": \"aws:Average\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"Sum\": {\n      \"@id\": \"aws:Sum\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"N\": {\n      \"@id\": \"aws:N\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Unit\": {\n      \"@id\": \"aws:Unit\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"Key\": {\n      \"@id\": \"aws:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"aws:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApplicationLayerAutomaticResponseConfiguration\": {\n      \"@id\": \"aws:ApplicationLayerAutomaticResponseConfiguration\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-shield/refs/heads/main/json-ld/amazon-shield-context-context.jsonld
tags:
- AWS
- DDoS Protection
- Networking
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
