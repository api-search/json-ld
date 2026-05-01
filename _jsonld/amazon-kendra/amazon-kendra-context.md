---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Amazon Kendra API
  slug: ''
  spec_type: OpenAPI
  url: https://api.apis.guru/v2/specs/amazonaws.com/kendra/2019-02-03/openapi.yaml
class_count: 4
classes:
- Index
- DataSource
- QueryResult
- Faq
context_file: json-ld/amazon-kendra-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-kendra/refs/heads/main/json-ld/amazon-kendra-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Kendra from Amazon Kendra.
layout: jsonld
name: Amazon Kendra Context
namespaces:
- prefix: kendra
  uri: https://kendra.amazonaws.com/schema/
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
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: edition
  type: string
- container: ''
  name: roleArn
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: schedule
  type: string
- container: ''
  name: indexId
  type: string
- container: ''
  name: queryId
  type: string
- container: set
  name: resultItems
  type: ''
- container: ''
  name: totalNumberOfResults
  type: integer
- container: set
  name: facetResults
  type: ''
- container: ''
  name: fileFormat
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 16
provider_name: Amazon Kendra
provider_slug: amazon-kendra
slug: amazon-kendra-context
source_filename: amazon-kendra-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"kendra\": \"https://kendra.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Index\": \"kendra:Index\",\n    \"DataSource\": \"kendra:DataSource\",\n    \"QueryResult\": \"kendra:QueryResult\",\n    \"Faq\": \"kendra:Faq\",\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"kendra:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"edition\": {\n      \"@id\": \"kendra:edition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleArn\": {\n      \"@id\": \"kendra:roleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  type\": {\n      \"@id\": \"kendra:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schedule\": {\n      \"@id\": \"kendra:schedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"indexId\": {\n      \"@id\": \"kendra:indexId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queryId\": {\n      \"@id\": \"kendra:queryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultItems\": {\n      \"@id\": \"kendra:resultItems\",\n      \"@container\": \"@set\"\n    },\n    \"totalNumberOfResults\": {\n      \"@id\": \"kendra:totalNumberOfResults\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"facetResults\": {\n      \"@id\": \"kendra:facetResults\",\n      \"@container\": \"@set\"\n    },\n    \"fileFormat\": {\n      \"@id\": \"kendra:fileFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\":\
  \ \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-kendra/refs/heads/main/json-ld/amazon-kendra-context.jsonld
tags:
- AI
- Enterprise Search
- Knowledge Management
- Machine Learning
- Natural Language
- JSON-LD
- Linked Data
- Semantic Web
---
