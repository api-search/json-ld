---
api_specs:
- filename: salesforce-openapi.yml
  format: yaml
  label: Salesforce REST API
  slug: salesforce-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/openapi/salesforce-openapi.yml
- filename: salesforce-bulk-api-2-openapi.yml
  format: yaml
  label: Salesforce Bulk API 2.0
  slug: salesforce-bulk-api-2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/openapi/salesforce-bulk-api-2-openapi.yml
- filename: salesforce-streaming-asyncapi.yml
  format: yaml
  label: Salesforce Streaming API
  slug: salesforce-streaming-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/asyncapi/salesforce-streaming-asyncapi.yml
- filename: salesforce-platform-events-asyncapi.yml
  format: yaml
  label: Salesforce Platform Events API
  slug: salesforce-platform-events-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/asyncapi/salesforce-platform-events-asyncapi.yml
- filename: salesforce-change-data-capture-asyncapi.yml
  format: yaml
  label: Salesforce Change Data Capture API
  slug: salesforce-change-data-capture-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/asyncapi/salesforce-change-data-capture-asyncapi.yml
- filename: salesforce-ui-api-openapi.yml
  format: yaml
  label: Salesforce UI API
  slug: salesforce-ui-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/openapi/salesforce-ui-api-openapi.yml
- filename: salesforce-marketing-cloud-rest-openapi.yml
  format: yaml
  label: Salesforce Marketing Cloud REST API
  slug: salesforce-marketing-cloud-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/openapi/salesforce-marketing-cloud-rest-openapi.yml
- filename: salesforce-openapi.yml
  format: yaml
  label: Salesforce
  slug: salesforce-salesforce
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/openapi/salesforce-openapi.yml
class_count: 0
classes: []
context_file: json-ld/salesforce-rest-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/json-ld/salesforce-rest-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Salesforce Rest from Salesforce.
layout: jsonld
name: Salesforce Rest Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: ApiVersion
  type: ''
- container: ''
  name: SObjectRecord
  type: ''
- container: ''
  name: SObjectDescribe
  type: ''
- container: ''
  name: QueryResult
  type: ''
- container: ''
  name: SearchResult
  type: ''
- container: ''
  name: CompositeRequest
  type: ''
- container: ''
  name: CompositeResponse
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 8
provider_name: Salesforce
provider_slug: salesforce
slug: salesforce-rest-context
source_filename: salesforce-rest-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"ApiVersion\": {\n      \"@id\": \"ns:ApiVersion\",\n      \"@context\": {\n        \"version\": {\n          \"@id\": \"ns:version\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"url\": {\n          \"@id\": \"ns:url\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"SObjectRecord\": {\n      \"@id\": \"ns:SObjectRecord\",\n      \"@context\": {\n        \"attributes\": \"ns:attributes\",\n        \"Id\": {\n          \"@id\": \"ns:Id\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"SObjectDescribe\": {\n      \"@id\": \"ns:SObjectDescribe\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n      \
  \  },\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"labelPlural\": {\n          \"@id\": \"ns:labelPlural\",\n          \"@type\": \"xsd:string\"\n        },\n        \"keyPrefix\": {\n          \"@id\": \"ns:keyPrefix\",\n          \"@type\": \"xsd:string\"\n        },\n        \"queryable\": {\n          \"@id\": \"ns:queryable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"searchable\": {\n          \"@id\": \"ns:searchable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createable\": {\n          \"@id\": \"ns:createable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"updateable\": {\n          \"@id\": \"ns:updateable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"deletable\": {\n          \"@id\": \"ns:deletable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"fields\": \"ns:fields\",\n        \"urls\": \"ns:urls\"\n      }\n    },\n\
  \    \"QueryResult\": {\n      \"@id\": \"ns:QueryResult\",\n      \"@context\": {\n        \"totalSize\": {\n          \"@id\": \"ns:totalSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"done\": {\n          \"@id\": \"ns:done\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"nextRecordsUrl\": {\n          \"@id\": \"ns:nextRecordsUrl\",\n          \"@type\": \"xsd:string\"\n        },\n        \"records\": \"ns:records\"\n      }\n    },\n    \"SearchResult\": {\n      \"@id\": \"ns:SearchResult\",\n      \"@context\": {\n        \"searchRecords\": \"ns:searchRecords\"\n      }\n    },\n    \"CompositeRequest\": {\n      \"@id\": \"ns:CompositeRequest\",\n      \"@context\": {\n        \"allOrNone\": {\n          \"@id\": \"ns:allOrNone\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"collateSubrequests\": {\n          \"@id\": \"ns:collateSubrequests\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"compositeRequest\": \"\
  ns:compositeRequest\"\n      }\n    },\n    \"CompositeResponse\": {\n      \"@id\": \"ns:CompositeResponse\",\n      \"@context\": {\n        \"compositeResponse\": \"ns:compositeResponse\"\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"errorCode\": {\n          \"@id\": \"ns:errorCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fields\": \"ns:fields\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/json-ld/salesforce-rest-context.jsonld
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
