---
class_count: 8
classes:
- AssetFileMetadata
- FileUploadRequest
- FileExtractRequest
- TaskLocator
- ActionResponse
- ValidationResult
- ValidationError
- ValidationWarning
context_file: json-ld/hubspot-source-code-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-source-code-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Source Code Api from HubSpot.
layout: jsonld
name: Hubspot Source Code Api Context
namespaces:
- prefix: hubspot
  uri: https://developers.hubspot.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: folder
  type: boolean
- container: set
  name: children
  type: string
- container: ''
  name: hash
  type: string
- container: ''
  name: createdAt
  type: string
- container: ''
  name: updatedAt
  type: string
- container: ''
  name: archivedAt
  type: string
- container: ''
  name: file
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: links
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: requestedAt
  type: dateTime
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: valid
  type: boolean
- container: set
  name: errors
  type: reference
- container: set
  name: warnings
  type: reference
- container: ''
  name: message
  type: string
- container: ''
  name: line
  type: integer
- container: ''
  name: column
  type: integer
- container: ''
  name: category
  type: string
- container: ''
  name: suggestion
  type: string
property_count: 23
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-source-code-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AssetFileMetadata\": \"hubspot:AssetFileMetadata\",\n    \"id\": {\n      \"@id\": \"hubspot:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"folder\": {\n      \"@id\": \"hubspot:folder\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"children\": {\n      \"@id\": \"hubspot:children\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hash\": {\n      \"@id\": \"hubspot:hash\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"hubspot:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"hubspot:updatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  archivedAt\": {\n      \"@id\": \"hubspot:archivedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FileUploadRequest\": \"hubspot:FileUploadRequest\",\n    \"file\": {\n      \"@id\": \"hubspot:file\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FileExtractRequest\": \"hubspot:FileExtractRequest\",\n    \"path\": {\n      \"@id\": \"hubspot:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TaskLocator\": \"hubspot:TaskLocator\",\n    \"links\": {\n      \"@id\": \"hubspot:links\",\n      \"@type\": \"@id\"\n    },\n    \"ActionResponse\": \"hubspot:ActionResponse\",\n    \"status\": {\n      \"@id\": \"hubspot:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedAt\": {\n      \"@id\": \"hubspot:requestedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startedAt\": {\n      \"@id\": \"hubspot:startedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"hubspot:completedAt\",\n      \"@type\": \"xsd:dateTime\"\n  \
  \  },\n    \"ValidationResult\": \"hubspot:ValidationResult\",\n    \"valid\": {\n      \"@id\": \"hubspot:valid\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"errors\": {\n      \"@id\": \"hubspot:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"warnings\": {\n      \"@id\": \"hubspot:warnings\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"ValidationError\": \"hubspot:ValidationError\",\n    \"message\": {\n      \"@id\": \"hubspot:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"line\": {\n      \"@id\": \"hubspot:line\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"column\": {\n      \"@id\": \"hubspot:column\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"category\": {\n      \"@id\": \"hubspot:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ValidationWarning\": \"hubspot:ValidationWarning\",\n    \"suggestion\": {\n      \"@id\": \"hubspot:suggestion\",\n      \"@type\": \"xsd:string\"\
  \n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-source-code-api-context.jsonld
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
