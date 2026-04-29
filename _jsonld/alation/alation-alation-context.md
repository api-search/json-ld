---
api_specs:
- filename: alation-data-catalog-openapi.yaml
  format: yaml
  label: Alation Data Catalog API
  slug: data-catalog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alation/refs/heads/main/openapi/alation-data-catalog-openapi.yaml
- filename: alation-lineage-openapi.yaml
  format: yaml
  label: Alation Lineage API
  slug: lineage-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alation/refs/heads/main/openapi/alation-lineage-openapi.yaml
- filename: alation-governance-openapi.yaml
  format: yaml
  label: Alation Governance API
  slug: governance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alation/refs/heads/main/openapi/alation-governance-openapi.yaml
- filename: alation-search-openapi.yaml
  format: yaml
  label: Alation Search API
  slug: search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alation/refs/heads/main/openapi/alation-search-openapi.yaml
class_count: 0
classes: []
context_file: json-ld/alation-alation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/alation/refs/heads/main/json-ld/alation-alation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Alation Alation from Alation.
layout: jsonld
name: Alation Alation Context
namespaces:
- prefix: alation
  uri: https://alation.com/schema/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: DataSource
  type: ''
- container: ''
  name: id
  type: integer
- container: ''
  name: title
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: dbtype
  type: string
- container: ''
  name: host
  type: string
- container: ''
  name: port
  type: integer
- container: ''
  name: is_virtual
  type: boolean
- container: ''
  name: url
  type: anyURI
- container: ''
  name: Schema
  type: ''
- container: ''
  name: name
  type: string
- container: ''
  name: ds_id
  type: integer
- container: ''
  name: Table
  type: ''
- container: ''
  name: schema_id
  type: integer
- container: ''
  name: table_type
  type: string
- container: ''
  name: Column
  type: ''
- container: ''
  name: data_type
  type: string
- container: ''
  name: table_id
  type: integer
- container: ''
  name: is_nullable
  type: boolean
- container: ''
  name: is_primary_key
  type: boolean
- container: ''
  name: CustomFieldValue
  type: ''
- container: ''
  name: field_id
  type: integer
- container: ''
  name: field_name
  type: string
- container: ''
  name: object_type
  type: string
- container: ''
  name: object_id
  type: integer
- container: ''
  name: value
  type: string
- container: ''
  name: Dataflow
  type: ''
- container: ''
  name: external_id
  type: string
- container: ''
  name: sources
  type: string
- container: ''
  name: targets
  type: string
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: LineageGraph
  type: ''
- container: ''
  name: nodes
  type: string
- container: ''
  name: edges
  type: string
- container: ''
  name: GlossaryTerm
  type: ''
- container: ''
  name: abbreviation
  type: string
- container: ''
  name: synonyms
  type: string
- container: ''
  name: stewards
  type: string
- container: ''
  name: Policy
  type: ''
- container: ''
  name: policy_type
  type: string
- container: ''
  name: DataQualityRule
  type: ''
- container: ''
  name: rule_type
  type: string
- container: ''
  name: DataQualityScore
  type: ''
- container: ''
  name: overall_score
  type: decimal
- container: ''
  name: dimensions
  type: string
- container: ''
  name: last_evaluated
  type: dateTime
- container: ''
  name: SearchResult
  type: ''
- container: ''
  name: score
  type: decimal
- container: ''
  name: breadcrumb
  type: string
- container: ''
  name: SearchResults
  type: ''
- container: ''
  name: total
  type: integer
- container: ''
  name: results
  type: string
- container: ''
  name: ContextRequest
  type: ''
- container: ''
  name: query
  type: string
- container: ''
  name: object_types
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: Article
  type: ''
- container: ''
  name: body
  type: string
- container: ''
  name: author
  type: integer
property_count: 60
provider_name: Alation
provider_slug: alation
slug: alation-alation-context
source_filename: alation-alation-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"alation\": \"https://alation.com/schema/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DataSource\": {\n      \"@id\": \"alation:DataSource\"\n    },\n    \"id\": {\n      \"@id\": \"alation:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"title\": {\n      \"@id\": \"alation:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"alation:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dbtype\": {\n      \"@id\": \"alation:dbtype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"host\": {\n      \"@id\": \"alation:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"port\": {\n      \"@id\": \"alation:port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"is_virtual\": {\n      \"@id\": \"alation:is_virtual\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"url\": {\n      \"@id\": \"alation:url\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"Schema\": {\n      \"\
  @id\": \"alation:Schema\"\n    },\n    \"name\": {\n      \"@id\": \"alation:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ds_id\": {\n      \"@id\": \"alation:ds_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Table\": {\n      \"@id\": \"alation:Table\"\n    },\n    \"schema_id\": {\n      \"@id\": \"alation:schema_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"table_type\": {\n      \"@id\": \"alation:table_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Column\": {\n      \"@id\": \"alation:Column\"\n    },\n    \"data_type\": {\n      \"@id\": \"alation:data_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"table_id\": {\n      \"@id\": \"alation:table_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"is_nullable\": {\n      \"@id\": \"alation:is_nullable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"is_primary_key\": {\n      \"@id\": \"alation:is_primary_key\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"CustomFieldValue\":\
  \ {\n      \"@id\": \"alation:CustomFieldValue\"\n    },\n    \"field_id\": {\n      \"@id\": \"alation:field_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"field_name\": {\n      \"@id\": \"alation:field_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"object_type\": {\n      \"@id\": \"alation:object_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"object_id\": {\n      \"@id\": \"alation:object_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"value\": {\n      \"@id\": \"alation:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Dataflow\": {\n      \"@id\": \"alation:Dataflow\"\n    },\n    \"external_id\": {\n      \"@id\": \"alation:external_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sources\": {\n      \"@id\": \"alation:sources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targets\": {\n      \"@id\": \"alation:targets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created_at\": {\n      \"@id\": \"alation:created_at\",\n  \
  \    \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"alation:updated_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LineageGraph\": {\n      \"@id\": \"alation:LineageGraph\"\n    },\n    \"nodes\": {\n      \"@id\": \"alation:nodes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"edges\": {\n      \"@id\": \"alation:edges\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GlossaryTerm\": {\n      \"@id\": \"alation:GlossaryTerm\"\n    },\n    \"abbreviation\": {\n      \"@id\": \"alation:abbreviation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"synonyms\": {\n      \"@id\": \"alation:synonyms\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stewards\": {\n      \"@id\": \"alation:stewards\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Policy\": {\n      \"@id\": \"alation:Policy\"\n    },\n    \"policy_type\": {\n      \"@id\": \"alation:policy_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DataQualityRule\": {\n      \"@id\"\
  : \"alation:DataQualityRule\"\n    },\n    \"rule_type\": {\n      \"@id\": \"alation:rule_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DataQualityScore\": {\n      \"@id\": \"alation:DataQualityScore\"\n    },\n    \"overall_score\": {\n      \"@id\": \"alation:overall_score\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"dimensions\": {\n      \"@id\": \"alation:dimensions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last_evaluated\": {\n      \"@id\": \"alation:last_evaluated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"SearchResult\": {\n      \"@id\": \"alation:SearchResult\"\n    },\n    \"score\": {\n      \"@id\": \"alation:score\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"breadcrumb\": {\n      \"@id\": \"alation:breadcrumb\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SearchResults\": {\n      \"@id\": \"alation:SearchResults\"\n    },\n    \"total\": {\n      \"@id\": \"alation:total\",\n      \"@type\": \"xsd:integer\"\n    },\n   \
  \ \"results\": {\n      \"@id\": \"alation:results\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ContextRequest\": {\n      \"@id\": \"alation:ContextRequest\"\n    },\n    \"query\": {\n      \"@id\": \"alation:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"object_types\": {\n      \"@id\": \"alation:object_types\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"alation:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Article\": {\n      \"@id\": \"alation:Article\"\n    },\n    \"body\": {\n      \"@id\": \"alation:body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"author\": {\n      \"@id\": \"alation:author\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/alation/refs/heads/main/json-ld/alation-alation-context.jsonld
tags:
- Data Catalog
- Data Governance
- Data Intelligence
- Data Lineage
- Data Quality
- Business Glossary
- Metadata Management
- AI
- JSON-LD
- Linked Data
- Semantic Web
---
