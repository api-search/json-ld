---
api_specs:
- filename: taxi-language-openapi.yml
  format: yaml
  label: Taxi Language
  slug: taxi-language
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/taxi-describe-how-your-apis-and-data-relate/refs/heads/main/openapi/taxi-language-openapi.yml
class_count: 24
classes:
- TaxiSchema
- TaxiType
- TaxiModel
- TaxiService
- TaxiOperation
- namespace
- inherits
- qualifiedName
- baseUri
- returnType
- parameter
- contract
- annotation
- TaxiQL
- query
- facts
- executionPlan
- SoftwareSourceCode
- programmingLanguage
- codeRepository
- license
- APIReference
- name
- description
context_file: json-ld/taxi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/taxi-describe-how-your-apis-and-data-relate/refs/heads/main/json-ld/taxi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Taxi from Taxi - Describe How Your APIs and Data Relate.
layout: jsonld
name: Taxi Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: rdf
  uri: http://www.w3.org/1999/02/22-rdf-syntax-ns#
properties: []
property_count: 0
provider_name: Taxi - Describe How Your APIs and Data Relate
provider_slug: taxi-describe-how-your-apis-and-data-relate
slug: taxi-context
source_filename: taxi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://taxilang.org/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"rdf\": \"http://www.w3.org/1999/02/22-rdf-syntax-ns#\",\n    \"TaxiSchema\": \"taxi:Schema\",\n    \"TaxiType\": \"taxi:Type\",\n    \"TaxiModel\": \"taxi:Model\",\n    \"TaxiService\": \"taxi:Service\",\n    \"TaxiOperation\": \"taxi:Operation\",\n    \"namespace\": \"taxi:namespace\",\n    \"inherits\": \"taxi:inherits\",\n    \"qualifiedName\": \"taxi:qualifiedName\",\n    \"baseUri\": \"taxi:baseUri\",\n    \"returnType\": \"taxi:returnType\",\n    \"parameter\": \"taxi:parameter\",\n    \"contract\": \"taxi:contract\",\n    \"annotation\": \"taxi:annotation\",\n    \"TaxiQL\": \"taxi:QueryLanguage\",\n    \"query\": \"taxi:query\",\n    \"facts\": \"taxi:facts\",\n    \"executionPlan\": \"taxi:executionPlan\",\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n    \"programmingLanguage\": \"\
  schema:programmingLanguage\",\n    \"codeRepository\": \"schema:codeRepository\",\n    \"license\": \"schema:license\",\n    \"APIReference\": \"schema:APIReference\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/taxi-describe-how-your-apis-and-data-relate/refs/heads/main/json-ld/taxi-context.jsonld
tags:
- API Description
- Data Integration
- Open Source
- Query Language
- Schema
- Semantic
- JSON-LD
- Linked Data
- Semantic Web
---
