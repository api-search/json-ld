---
api_specs:
- filename: amazon-firewall-manager-openapi.yml
  format: yaml
  label: AWS Firewall Manager API
  slug: aws-firewall-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-firewall-manager/refs/heads/main/openapi/amazon-firewall-manager-openapi.yml
class_count: 5
classes:
- Policy
- ComplianceViolator
- ResourceSet
- SecurityServicePolicyData
- Tag
context_file: json-ld/amazon-firewall-manager-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-firewall-manager/refs/heads/main/json-ld/amazon-firewall-manager-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Firewall Manager from Amazon Firewall Manager.
layout: jsonld
name: Amazon Firewall Manager Context
namespaces:
- prefix: fms
  uri: https://aws.amazon.com/firewall-manager/vocabulary/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: PolicyId
  type: string
- container: ''
  name: PolicyName
  type: string
- container: ''
  name: PolicyArn
  type: string
- container: ''
  name: RemediationEnabled
  type: boolean
- container: ''
  name: ExcludeResourceTags
  type: boolean
- container: ''
  name: ResourceType
  type: string
- container: ''
  name: ResourceId
  type: string
- container: ''
  name: ViolationReason
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: LastUpdateTime
  type: dateTime
- container: ''
  name: Key
  type: string
- container: ''
  name: Value
  type: string
property_count: 14
provider_name: Amazon Firewall Manager
provider_slug: amazon-firewall-manager
slug: amazon-firewall-manager-context
source_filename: amazon-firewall-manager-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fms\": \"https://aws.amazon.com/firewall-manager/vocabulary/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Policy\": \"fms:Policy\",\n    \"ComplianceViolator\": \"fms:ComplianceViolator\",\n    \"ResourceSet\": \"fms:ResourceSet\",\n    \"SecurityServicePolicyData\": \"fms:SecurityServicePolicyData\",\n    \"Tag\": \"schema:PropertyValue\",\n    \"PolicyId\": {\n      \"@id\": \"fms:policyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PolicyName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PolicyArn\": {\n      \"@id\": \"fms:policyArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RemediationEnabled\": {\n      \"@id\": \"fms:remediationEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ExcludeResourceTags\": {\n      \"@id\": \"fms:excludeResourceTags\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"\
  ResourceType\": {\n      \"@id\": \"fms:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceId\": {\n      \"@id\": \"fms:resourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ViolationReason\": {\n      \"@id\": \"fms:violationReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastUpdateTime\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Key\": {\n      \"@id\": \"schema:propertyID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"schema:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-firewall-manager/refs/heads/main/json-ld/amazon-firewall-manager-context.jsonld
tags:
- Compliance
- Firewall
- Network Security
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
