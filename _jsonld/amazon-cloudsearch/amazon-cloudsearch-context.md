---
api_specs:
- filename: amazon-cloudsearch-openapi.yml
  format: yaml
  label: Amazon CloudSearch API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudsearch/refs/heads/main/openapi/amazon-cloudsearch-openapi.yml
class_count: 9
classes:
- CreateDomainRequest
- CreateDomainResponse
- DescribeDomainsResponse
- DeleteDomainResponse
- DomainStatus
- DefineIndexFieldRequest
- DefineIndexFieldResponse
- DescribeIndexFieldsResponse
- IndexDocumentsResponse
context_file: json-ld/amazon-cloudsearch-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudsearch/refs/heads/main/json-ld/amazon-cloudsearch-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Cloudsearch from Amazon CloudSearch.
layout: jsonld
name: Amazon Cloudsearch Context
namespaces:
- prefix: cloudsearch
  uri: https://aws.amazon.com/cloudsearch/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: domainName
  type: string
- container: ''
  name: domainStatus
  type: string
- container: set
  name: domainStatusList
  type: string
- container: ''
  name: domainId
  type: string
- container: ''
  name: aRN
  type: string
- container: ''
  name: created
  type: boolean
- container: ''
  name: deleted
  type: boolean
- container: ''
  name: processing
  type: boolean
- container: ''
  name: requiresIndexDocuments
  type: boolean
- container: ''
  name: searchInstanceCount
  type: integer
- container: ''
  name: searchInstanceType
  type: string
- container: ''
  name: docService
  type: string
- container: ''
  name: searchService
  type: string
- container: ''
  name: indexField
  type: string
- container: set
  name: indexFields
  type: string
- container: set
  name: fieldNames
  type: string
property_count: 16
provider_name: Amazon CloudSearch
provider_slug: amazon-cloudsearch
slug: amazon-cloudsearch-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cloudsearch\": \"https://aws.amazon.com/cloudsearch/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateDomainRequest\": \"cloudsearch:CreateDomainRequest\",\n    \"domainName\": {\n      \"@id\": \"cloudsearch:domain_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateDomainResponse\": \"cloudsearch:CreateDomainResponse\",\n    \"domainStatus\": {\n      \"@id\": \"cloudsearch:domain_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeDomainsResponse\": \"cloudsearch:DescribeDomainsResponse\",\n    \"domainStatusList\": {\n      \"@id\": \"cloudsearch:domain_status_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteDomainResponse\": \"cloudsearch:DeleteDomainResponse\",\n    \"DomainStatus\": \"cloudsearch:DomainStatus\",\n    \"domainId\":\
  \ {\n      \"@id\": \"cloudsearch:domain_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aRN\": {\n      \"@id\": \"cloudsearch:a_r_n\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"cloudsearch:created\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"deleted\": {\n      \"@id\": \"cloudsearch:deleted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"processing\": {\n      \"@id\": \"cloudsearch:processing\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"requiresIndexDocuments\": {\n      \"@id\": \"cloudsearch:requires_index_documents\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"searchInstanceCount\": {\n      \"@id\": \"cloudsearch:search_instance_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"searchInstanceType\": {\n      \"@id\": \"cloudsearch:search_instance_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"docService\": {\n      \"@id\": \"cloudsearch:doc_service\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"searchService\": {\n      \"@id\": \"cloudsearch:search_service\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefineIndexFieldRequest\": \"cloudsearch:DefineIndexFieldRequest\",\n    \"indexField\": {\n      \"@id\": \"cloudsearch:index_field\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefineIndexFieldResponse\": \"cloudsearch:DefineIndexFieldResponse\",\n    \"DescribeIndexFieldsResponse\": \"cloudsearch:DescribeIndexFieldsResponse\",\n    \"indexFields\": {\n      \"@id\": \"cloudsearch:index_fields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IndexDocumentsResponse\": \"cloudsearch:IndexDocumentsResponse\",\n    \"fieldNames\": {\n      \"@id\": \"cloudsearch:field_names\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudsearch/refs/heads/main/json-ld/amazon-cloudsearch-context.jsonld
tags:
- AWS
- CloudSearch
- Search
- Full-Text Search
- Managed
- JSON-LD
- Linked Data
- Semantic Web
---
