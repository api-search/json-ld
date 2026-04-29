---
api_specs:
- filename: adobe-analytics-api-openapi.yml
  format: yaml
  label: Adobe Analytics 2.0 API
  slug: analytics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/openapi/adobe-analytics-api-openapi.yml
- filename: adobe-experience-platform-api-openapi.yml
  format: yaml
  label: Adobe Experience Platform API
  slug: experience-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/openapi/adobe-experience-platform-api-openapi.yml
- filename: adobe-target-api-openapi.yml
  format: yaml
  label: Adobe Target API
  slug: target-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/openapi/adobe-target-api-openapi.yml
- filename: adobe-journey-optimizer-api-openapi.yml
  format: yaml
  label: Adobe Journey Optimizer API
  slug: journey-optimizer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/openapi/adobe-journey-optimizer-api-openapi.yml
- filename: adobe-campaign-api-openapi.yml
  format: yaml
  label: Adobe Campaign API
  slug: campaign-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/openapi/adobe-campaign-api-openapi.yml
- filename: adobe-io-events-asyncapi.yml
  format: yaml
  label: Adobe I/O Events
  slug: io-events
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/asyncapi/adobe-io-events-asyncapi.yml
class_count: 20
classes:
- DatasetInput
- SandboxList
- Batch
- QueryList
- SchemaInput
- Sandbox
- IdentityNamespace
- ClassList
- Schema
- SegmentDefinitionList
- IdentityNamespaceInput
- Dataset
- SchemaList
- SegmentDefinition
- SegmentDefinitionInput
- Query
- ProfileEntity
- name
- description
- version
context_file: json-ld/adobe-experience-cloud-experience-platform-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/json-ld/adobe-experience-cloud-experience-platform-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Experience Cloud Experience Platform Api from Adobe Experience Cloud.
layout: jsonld
name: Adobe Experience Cloud Experience Platform Api Context
namespaces:
- prefix: aec
  uri: https://developer.adobe.com/schema/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: schema
  type: reference
- container: ''
  name: schemaRef
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: contentType
  type: string
- container: set
  name: sandboxes
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: completed
  type: dateTime
- container: set
  name: queries
  type: string
- container: ''
  name: dbName
  type: string
- container: ''
  name: sql
  type: string
- container: ''
  name: updated
  type: dateTime
- container: ''
  name: rowCount
  type: integer
- container: ''
  name: Page
  type: reference
- container: ''
  name: totalCount
  type: integer
- container: set
  name: allOf
  type: string
- container: ''
  name: $ref
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: idType
  type: string
- container: ''
  name: standard
  type: boolean
- container: set
  name: results
  type: string
- container: ''
  name: meta:altId
  type: string
- container: set
  name: segments
  type: string
- container: ''
  name: expression
  type: reference
- container: ''
  name: value
  type: string
- container: ''
  name: mergePolicyId
  type: string
- container: ''
  name: evaluationInfo
  type: reference
- container: ''
  name: page
  type: reference
- container: ''
  name: fileDescription
  type: reference
- container: ''
  name: format
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: entity
  type: reference
- container: ''
  name: lastModifiedAt
  type: dateTime
property_count: 37
provider_name: Adobe Experience Cloud
provider_slug: adobe-experience-cloud
slug: adobe-experience-cloud-experience-platform-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aec\": \"https://developer.adobe.com/schema/\",\n    \"schema\": {\n      \"@id\": \"aec:schema\",\n      \"@type\": \"@id\"\n    },\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DatasetInput\": \"aec:DatasetInput\",\n    \"SandboxList\": \"aec:SandboxList\",\n    \"Batch\": \"aec:Batch\",\n    \"QueryList\": \"aec:QueryList\",\n    \"SchemaInput\": \"aec:SchemaInput\",\n    \"Sandbox\": \"aec:Sandbox\",\n    \"IdentityNamespace\": \"aec:IdentityNamespace\",\n    \"ClassList\": \"aec:ClassList\",\n    \"Schema\": \"aec:Schema\",\n    \"SegmentDefinitionList\": \"aec:SegmentDefinitionList\",\n    \"IdentityNamespaceInput\": \"aec:IdentityNamespaceInput\",\n    \"Dataset\": \"aec:Dataset\",\n    \"SchemaList\": \"aec:SchemaList\",\n    \"SegmentDefinition\": \"aec:SegmentDefinition\",\n    \"SegmentDefinitionInput\": \"aec:SegmentDefinitionInput\",\n    \"Query\"\
  : \"aec:Query\",\n    \"ProfileEntity\": \"aec:ProfileEntity\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"schemaRef\": {\n      \"@id\": \"aec:schemaRef\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"aec:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"aec:contentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sandboxes\": {\n      \"@id\": \"aec:sandboxes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"aec:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"aec:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"aec:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"aec:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aec:status\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"created\": {\n      \"@id\": \"aec:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completed\": {\n      \"@id\": \"aec:completed\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"queries\": {\n      \"@id\": \"aec:queries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dbName\": {\n      \"@id\": \"aec:dbName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sql\": {\n      \"@id\": \"aec:sql\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updated\": {\n      \"@id\": \"aec:updated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"rowCount\": {\n      \"@id\": \"aec:rowCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Page\": {\n      \"@id\": \"aec:_page\",\n      \"@type\": \"@id\"\n    },\n    \"totalCount\": {\n      \"@id\": \"aec:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"allOf\": {\n      \"@id\": \"aec:allOf\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"$ref\": {\n      \"@id\": \"aec:$ref\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"aec:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idType\": {\n      \"@id\": \"aec:idType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"standard\": {\n      \"@id\": \"aec:standard\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"results\": {\n      \"@id\": \"aec:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meta:altId\": {\n      \"@id\": \"aec:meta:altId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"segments\": {\n      \"@id\": \"aec:segments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expression\": {\n      \"@id\": \"aec:expression\",\n      \"@type\": \"@id\"\n    },\n    \"value\": {\n      \"@id\": \"aec:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mergePolicyId\": {\n      \"@id\": \"aec:mergePolicyId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"evaluationInfo\": {\n      \"@id\": \"aec:evaluationInfo\",\n      \"@type\": \"@id\"\n    },\n    \"page\": {\n      \"@id\": \"aec:page\",\n      \"@type\": \"@id\"\n    },\n    \"fileDescription\": {\n      \"@id\": \"aec:fileDescription\",\n      \"@type\": \"@id\"\n    },\n    \"format\": {\n      \"@id\": \"aec:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"aec:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entity\": {\n      \"@id\": \"aec:entity\",\n      \"@type\": \"@id\"\n    },\n    \"lastModifiedAt\": {\n      \"@id\": \"aec:lastModifiedAt\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/json-ld/adobe-experience-cloud-experience-platform-api-context.jsonld
tags:
- Analytics
- Customer Experience
- Digital Marketing
- Personalization
- Campaign Management
- Journey Orchestration
- JSON-LD
- Linked Data
- Semantic Web
---
