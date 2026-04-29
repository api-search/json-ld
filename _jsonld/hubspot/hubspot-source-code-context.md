---
class_count: 0
classes: []
context_file: json-ld/hubspot-source-code-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-source-code-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Source Code from HubSpot.
layout: jsonld
name: Hubspot Source Code Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: AssetFileMetadata
  type: ''
- container: ''
  name: FileUploadRequest
  type: ''
- container: ''
  name: FileExtractRequest
  type: ''
- container: ''
  name: TaskLocator
  type: ''
- container: ''
  name: ActionResponse
  type: ''
- container: ''
  name: ValidationResult
  type: ''
- container: ''
  name: ValidationError
  type: ''
- container: ''
  name: ValidationWarning
  type: ''
- container: ''
  name: Error
  type: ''
- container: ''
  name: ErrorDetail
  type: ''
property_count: 10
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-source-code-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"AssetFileMetadata\": {\n      \"@id\": \"ns:AssetFileMetadata\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"folder\": {\n          \"@id\": \"ns:folder\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"children\": \"ns:children\",\n        \"hash\": {\n          \"@id\": \"ns:hash\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"ns:updatedAt\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"archivedAt\": {\n          \"@id\": \"ns:archivedAt\",\n    \
  \      \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"FileUploadRequest\": {\n      \"@id\": \"ns:FileUploadRequest\",\n      \"@context\": {\n        \"file\": {\n          \"@id\": \"ns:file\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"FileExtractRequest\": {\n      \"@id\": \"ns:FileExtractRequest\",\n      \"@context\": {\n        \"path\": {\n          \"@id\": \"ns:path\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"TaskLocator\": {\n      \"@id\": \"ns:TaskLocator\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"links\": \"ns:links\"\n      }\n    },\n    \"ActionResponse\": {\n      \"@id\": \"ns:ActionResponse\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"requestedAt\": {\n          \"@id\": \"ns:requestedAt\",\n          \"\
  @type\": \"xsd:string\"\n        },\n        \"startedAt\": {\n          \"@id\": \"ns:startedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"completedAt\": {\n          \"@id\": \"ns:completedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"links\": \"ns:links\"\n      }\n    },\n    \"ValidationResult\": {\n      \"@id\": \"ns:ValidationResult\",\n      \"@context\": {\n        \"valid\": {\n          \"@id\": \"ns:valid\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"errors\": \"ns:errors\",\n        \"warnings\": \"ns:warnings\"\n      }\n    },\n    \"ValidationError\": {\n      \"@id\": \"ns:ValidationError\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"line\": {\n          \"@id\": \"ns:line\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"column\": {\n          \"@id\": \"ns:column\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ValidationWarning\": {\n      \"@id\": \"ns:ValidationWarning\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"line\": {\n          \"@id\": \"ns:line\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"suggestion\": {\n          \"@id\": \"ns:suggestion\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n       \
  \ \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\",\n        \"errors\": \"ns:errors\"\n      }\n    },\n    \"ErrorDetail\": {\n      \"@id\": \"ns:ErrorDetail\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"in\": {\n          \"@id\": \"ns:in\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-source-code-context.jsonld
tags:
- Analytics
- Commerce
- Content
- CRM
- Customer Service
- Email Marketing
- Marketing
- Marketing Automation
- Operations
- Sales
- JSON-LD
- Linked Data
- Semantic Web
---
