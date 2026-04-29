---
class_count: 0
classes: []
context_file: json-ld/salesforce-bulk-2-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/json-ld/salesforce-bulk-2-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Salesforce Bulk 2 from Salesforce.
layout: jsonld
name: Salesforce Bulk 2 Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: IngestJobRequest
  type: ''
- container: ''
  name: IngestJobInfo
  type: ''
- container: ''
  name: QueryJobRequest
  type: ''
- container: ''
  name: QueryJobInfo
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 5
provider_name: Salesforce
provider_slug: salesforce
slug: salesforce-bulk-2-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"IngestJobRequest\": {\n      \"@id\": \"ns:IngestJobRequest\",\n      \"@context\": {\n        \"operation\": {\n          \"@id\": \"ns:operation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"object\": {\n          \"@id\": \"ns:object\",\n          \"@type\": \"xsd:string\"\n        },\n        \"externalIdFieldName\": {\n          \"@id\": \"ns:externalIdFieldName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contentType\": {\n          \"@id\": \"ns:contentType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lineEnding\": {\n          \"@id\": \"ns:lineEnding\",\n          \"@type\": \"xsd:string\"\n        },\n        \"columnDelimiter\": {\n          \"@id\": \"ns:columnDelimiter\",\n          \"@type\": \"xsd:string\"\n        },\n        \"assignmentRuleId\": {\n          \"\
  @id\": \"ns:assignmentRuleId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"IngestJobInfo\": {\n      \"@id\": \"ns:IngestJobInfo\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"operation\": {\n          \"@id\": \"ns:operation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"object\": {\n          \"@id\": \"ns:object\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"ns:state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDate\": {\n          \"@id\": \"ns:createdDate\",\n          \"@type\": \"xsd:string\"\n        },\n        \"systemModstamp\": {\n          \"@id\": \"ns:systemModstamp\",\n          \"@type\": \"xsd:string\"\n        },\n        \"numberRecordsProcessed\": {\n          \"@id\": \"ns:numberRecordsProcessed\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"\
  numberRecordsFailed\": {\n          \"@id\": \"ns:numberRecordsFailed\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalProcessingTime\": {\n          \"@id\": \"ns:totalProcessingTime\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"errorMessage\": {\n          \"@id\": \"ns:errorMessage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contentType\": {\n          \"@id\": \"ns:contentType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lineEnding\": {\n          \"@id\": \"ns:lineEnding\",\n          \"@type\": \"xsd:string\"\n        },\n        \"columnDelimiter\": {\n          \"@id\": \"ns:columnDelimiter\",\n          \"@type\": \"xsd:string\"\n        },\n        \"externalIdFieldName\": {\n          \"@id\": \"ns:externalIdFieldName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"jobType\": {\n          \"@id\": \"ns:jobType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdById\"\
  : {\n          \"@id\": \"ns:createdById\",\n          \"@type\": \"xsd:string\"\n        },\n        \"apiVersion\": {\n          \"@id\": \"ns:apiVersion\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n    \"QueryJobRequest\": {\n      \"@id\": \"ns:QueryJobRequest\",\n      \"@context\": {\n        \"operation\": {\n          \"@id\": \"ns:operation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"query\": {\n          \"@id\": \"ns:query\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contentType\": {\n          \"@id\": \"ns:contentType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"columnDelimiter\": {\n          \"@id\": \"ns:columnDelimiter\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lineEnding\": {\n          \"@id\": \"ns:lineEnding\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"QueryJobInfo\": {\n      \"@id\": \"ns:QueryJobInfo\",\n      \"@context\": {\n      \
  \  \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"operation\": {\n          \"@id\": \"ns:operation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"object\": {\n          \"@id\": \"ns:object\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"ns:state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDate\": {\n          \"@id\": \"ns:createdDate\",\n          \"@type\": \"xsd:string\"\n        },\n        \"systemModstamp\": {\n          \"@id\": \"ns:systemModstamp\",\n          \"@type\": \"xsd:string\"\n        },\n        \"numberRecordsProcessed\": {\n          \"@id\": \"ns:numberRecordsProcessed\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalProcessingTime\": {\n          \"@id\": \"ns:totalProcessingTime\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"errorMessage\": {\n          \"@id\": \"ns:errorMessage\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"contentType\": {\n          \"@id\": \"ns:contentType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"columnDelimiter\": {\n          \"@id\": \"ns:columnDelimiter\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lineEnding\": {\n          \"@id\": \"ns:lineEnding\",\n          \"@type\": \"xsd:string\"\n        },\n        \"jobType\": {\n          \"@id\": \"ns:jobType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdById\": {\n          \"@id\": \"ns:createdById\",\n          \"@type\": \"xsd:string\"\n        },\n        \"apiVersion\": {\n          \"@id\": \"ns:apiVersion\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"errorCode\": {\n          \"@id\": \"ns:errorCode\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"fields\": \"ns:fields\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/json-ld/salesforce-bulk-2-context.jsonld
tags:
- AI
- Analytics
- Cloud
- Commerce
- CRM
- Customer Service
- Enterprise
- Marketing
- Platform
- Sales
- JSON-LD
- Linked Data
- Semantic Web
---
