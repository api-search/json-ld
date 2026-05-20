---
api_specs:
- filename: eu-open-data-portal-search-openapi.yml
  format: yaml
  label: EU Open Data Portal Search API
  slug: eu-open-data-portal-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/eu-open-data-portal/refs/heads/main/openapi/eu-open-data-portal-search-openapi.yml
class_count: 6
classes:
- id
- title
- description
- fn
- hasEmail
- name
context_file: json-ld/eu-open-data-portal-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/eu-open-data-portal/refs/heads/main/json-ld/eu-open-data-portal-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Eu Open Data Portal from EU Open Data Portal.
layout: jsonld
name: Eu Open Data Portal Context
namespaces:
- prefix: dcat
  uri: http://www.w3.org/ns/dcat#
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: schema
  uri: https://schema.org/
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: adms
  uri: http://www.w3.org/ns/adms#
properties:
- container: ''
  name: Dataset
  type: reference
- container: ''
  name: Distribution
  type: reference
- container: ''
  name: Catalog
  type: reference
- container: ''
  name: DataService
  type: reference
- container: ''
  name: issued
  type: dateTime
- container: ''
  name: modified
  type: dateTime
- container: ''
  name: publisher
  type: reference
- container: ''
  name: contactPoint
  type: vcard:Kind
- container: set
  name: theme
  type: reference
- container: set
  name: keyword
  type: ''
- container: set
  name: language
  type: reference
- container: set
  name: spatial
  type: reference
- container: ''
  name: temporal
  type: dct:PeriodOfTime
- container: ''
  name: startDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: accrualPeriodicity
  type: reference
- container: ''
  name: license
  type: reference
- container: ''
  name: accessRights
  type: reference
- container: set
  name: conformsTo
  type: reference
- container: set
  name: distributions
  type: reference
- container: ''
  name: accessURL
  type: reference
- container: ''
  name: downloadURL
  type: reference
- container: ''
  name: format
  type: reference
- container: ''
  name: mediaType
  type: reference
- container: ''
  name: byteSize
  type: nonNegativeInteger
- container: ''
  name: hasURL
  type: reference
- container: ''
  name: homepage
  type: reference
property_count: 27
provider_name: EU Open Data Portal
provider_slug: eu-open-data-portal
slug: eu-open-data-portal-context
source_filename: eu-open-data-portal-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dcat\": \"http://www.w3.org/ns/dcat#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"schema\": \"https://schema.org/\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"adms\": \"http://www.w3.org/ns/adms#\",\n\n    \"Dataset\": {\n      \"@id\": \"dcat:Dataset\",\n      \"@type\": \"@id\"\n    },\n    \"Distribution\": {\n      \"@id\": \"dcat:Distribution\",\n      \"@type\": \"@id\"\n    },\n    \"Catalog\": {\n      \"@id\": \"dcat:Catalog\",\n      \"@type\": \"@id\"\n    },\n    \"DataService\": {\n      \"@id\": \"dcat:DataService\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": \"@id\",\n    \"title\": \"dct:title\",\n    \"description\": \"dct:description\",\n    \"issued\": {\n      \"@id\": \"dct:issued\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"modified\": {\n      \"@id\": \"dct:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"publisher\": {\n      \"@id\": \"dct:publisher\",\n      \"@type\": \"@id\"\n    },\n    \"contactPoint\": {\n      \"@id\": \"dcat:contactPoint\",\n      \"@type\": \"vcard:Kind\"\n    },\n    \"theme\": {\n      \"@id\": \"dcat:theme\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"keyword\": {\n      \"@id\": \"dcat:keyword\",\n      \"@container\": \"@set\"\n    },\n    \"language\": {\n      \"@id\": \"dct:language\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"spatial\": {\n      \"@id\": \"dct:spatial\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"temporal\": {\n      \"@id\": \"dct:temporal\",\n      \"@type\": \"dct:PeriodOfTime\"\n    },\n    \"startDate\": {\n      \"@id\": \"dcat:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"dcat:endDate\"\
  ,\n      \"@type\": \"xsd:date\"\n    },\n    \"accrualPeriodicity\": {\n      \"@id\": \"dct:accrualPeriodicity\",\n      \"@type\": \"@id\"\n    },\n    \"license\": {\n      \"@id\": \"dct:license\",\n      \"@type\": \"@id\"\n    },\n    \"accessRights\": {\n      \"@id\": \"dct:accessRights\",\n      \"@type\": \"@id\"\n    },\n    \"conformsTo\": {\n      \"@id\": \"dct:conformsTo\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"distributions\": {\n      \"@id\": \"dcat:distribution\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n\n    \"accessURL\": {\n      \"@id\": \"dcat:accessURL\",\n      \"@type\": \"@id\"\n    },\n    \"downloadURL\": {\n      \"@id\": \"dcat:downloadURL\",\n      \"@type\": \"@id\"\n    },\n    \"format\": {\n      \"@id\": \"dct:format\",\n      \"@type\": \"@id\"\n    },\n    \"mediaType\": {\n      \"@id\": \"dcat:mediaType\",\n      \"@type\": \"@id\"\n    },\n    \"byteSize\": {\n      \"@id\": \"dcat:byteSize\"\
  ,\n      \"@type\": \"xsd:nonNegativeInteger\"\n    },\n\n    \"fn\": \"vcard:fn\",\n    \"hasEmail\": \"vcard:hasEmail\",\n    \"hasURL\": {\n      \"@id\": \"vcard:hasURL\",\n      \"@type\": \"@id\"\n    },\n\n    \"name\": \"foaf:name\",\n    \"homepage\": {\n      \"@id\": \"foaf:homepage\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/eu-open-data-portal/refs/heads/main/json-ld/eu-open-data-portal-context.jsonld
tags:
- Government
- Open Data
- SPARQL
- EU
- Regulatory
- Linked Data
- JSON-LD
- Linked Data
- Semantic Web
---
