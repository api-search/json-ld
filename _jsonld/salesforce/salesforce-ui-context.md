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
context_file: json-ld/salesforce-ui-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/json-ld/salesforce-ui-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Salesforce Ui from Salesforce.
layout: jsonld
name: Salesforce Ui Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: RecordRepresentation
  type: ''
- container: ''
  name: FieldValueRepresentation
  type: ''
- container: ''
  name: RecordInput
  type: ''
- container: ''
  name: ObjectInfoRepresentation
  type: ''
- container: ''
  name: FieldRepresentation
  type: ''
- container: ''
  name: PicklistValuesCollection
  type: ''
- container: ''
  name: PicklistValue
  type: ''
- container: ''
  name: ListViewCollection
  type: ''
- container: ''
  name: ListViewSummary
  type: ''
- container: ''
  name: ListViewResult
  type: ''
- container: ''
  name: LookupRecordsCollection
  type: ''
- container: ''
  name: ErrorResponse
  type: ''
property_count: 12
provider_name: Salesforce
provider_slug: salesforce
slug: salesforce-ui-context
source_filename: salesforce-ui-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"RecordRepresentation\": {\n      \"@id\": \"ns:RecordRepresentation\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"apiName\": {\n          \"@id\": \"ns:apiName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"childRelationships\": \"ns:childRelationships\",\n        \"eTag\": {\n          \"@id\": \"ns:eTag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fields\": \"ns:fields\",\n        \"recordTypeId\": {\n          \"@id\": \"ns:recordTypeId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"recordTypeInfo\": \"ns:recordTypeInfo\",\n        \"systemModstamp\": {\n          \"@id\": \"ns:systemModstamp\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastModifiedById\": {\n          \"\
  @id\": \"ns:lastModifiedById\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastModifiedDate\": {\n          \"@id\": \"ns:lastModifiedDate\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdById\": {\n          \"@id\": \"ns:createdById\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDate\": {\n          \"@id\": \"ns:createdDate\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"FieldValueRepresentation\": {\n      \"@id\": \"ns:FieldValueRepresentation\",\n      \"@context\": {\n        \"displayValue\": {\n          \"@id\": \"ns:displayValue\",\n          \"@type\": \"xsd:string\"\n        },\n        \"value\": {\n          \"@id\": \"ns:value\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"RecordInput\": {\n      \"@id\": \"ns:RecordInput\",\n      \"@context\": {\n        \"apiName\": {\n          \"@id\": \"ns:apiName\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"fields\": \"ns:fields\"\n      }\n    },\n    \"ObjectInfoRepresentation\": {\n      \"@id\": \"ns:ObjectInfoRepresentation\",\n      \"@context\": {\n        \"apiName\": {\n          \"@id\": \"ns:apiName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"labelPlural\": {\n          \"@id\": \"ns:labelPlural\",\n          \"@type\": \"xsd:string\"\n        },\n        \"keyPrefix\": {\n          \"@id\": \"ns:keyPrefix\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createable\": {\n          \"@id\": \"ns:createable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"updateable\": {\n          \"@id\": \"ns:updateable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"deleteable\": {\n          \"@id\": \"ns:deleteable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"queryable\": {\n          \"@id\": \"\
  ns:queryable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"fields\": \"ns:fields\",\n        \"recordTypeInfos\": \"ns:recordTypeInfos\",\n        \"themeInfo\": \"ns:themeInfo\"\n      }\n    },\n    \"FieldRepresentation\": {\n      \"@id\": \"ns:FieldRepresentation\",\n      \"@context\": {\n        \"apiName\": {\n          \"@id\": \"ns:apiName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dataType\": {\n          \"@id\": \"ns:dataType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"required\": {\n          \"@id\": \"ns:required\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"updateable\": {\n          \"@id\": \"ns:updateable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createable\": {\n          \"@id\": \"ns:createable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"nillable\"\
  : {\n          \"@id\": \"ns:nillable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"referenceToInfos\": \"ns:referenceToInfos\"\n      }\n    },\n    \"PicklistValuesCollection\": {\n      \"@id\": \"ns:PicklistValuesCollection\",\n      \"@context\": {\n        \"picklistFieldValues\": \"ns:picklistFieldValues\"\n      }\n    },\n    \"PicklistValue\": {\n      \"@id\": \"ns:PicklistValue\",\n      \"@context\": {\n        \"attributes\": {\n          \"@id\": \"ns:attributes\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"validFor\": \"ns:validFor\",\n        \"value\": {\n          \"@id\": \"ns:value\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ListViewCollection\": {\n      \"@id\": \"ns:ListViewCollection\",\n      \"@context\": {\n        \"count\": {\n          \"@id\": \"ns:count\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"currentPageToken\": {\n          \"@id\": \"ns:currentPageToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"nextPageToken\": {\n          \"@id\": \"ns:nextPageToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"previousPageToken\": {\n          \"@id\": \"ns:previousPageToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"results\": \"ns:results\"\n      }\n    },\n    \"ListViewSummary\": {\n      \"@id\": \"ns:ListViewSummary\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"apiName\": {\n          \"@id\": \"ns:apiName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"url\": {\n          \"@id\": \"ns:url\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ListViewResult\": {\n      \"\
  @id\": \"ns:ListViewResult\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"records\": \"ns:records\",\n        \"sortBy\": {\n          \"@id\": \"ns:sortBy\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"LookupRecordsCollection\": {\n      \"@id\": \"ns:LookupRecordsCollection\",\n      \"@context\": {\n        \"count\": {\n          \"@id\": \"ns:count\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"lookupResults\": \"ns:lookupResults\"\n      }\n    },\n    \"ErrorResponse\": {\n      \"@id\": \"ns:ErrorResponse\",\n      \"@context\": {\n        \"errorCode\": {\n          \"@id\": \"ns:errorCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n    \
  \    }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/json-ld/salesforce-ui-context.jsonld
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
