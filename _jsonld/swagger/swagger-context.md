---
class_count: 0
classes: []
context_file: json-ld/swagger-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/swagger/refs/heads/main/json-ld/swagger-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Swagger from Swagger.
layout: jsonld
name: Swagger Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: swagger
  uri: https://api-evangelist.github.io/swagger/vocab#
- prefix: oas
  uri: https://spec.openapis.org/oas/v3.1.0#
properties:
- container: ''
  name: OpenApiSpecification
  type: reference
- container: ''
  name: ApiOperation
  type: reference
- container: ''
  name: ApiPath
  type: reference
- container: ''
  name: ApiSchema
  type: reference
- container: ''
  name: SecurityScheme
  type: reference
- container: ''
  name: SwaggerUi
  type: reference
- container: ''
  name: SwaggerEditor
  type: reference
- container: ''
  name: SwaggerCodegen
  type: reference
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: url
  type: reference
- container: ''
  name: version
  type: ''
- container: ''
  name: softwareVersion
  type: ''
- container: ''
  name: license
  type: reference
- container: ''
  name: codeRepository
  type: reference
- container: ''
  name: programmingLanguage
  type: ''
- container: ''
  name: featureList
  type: ''
- container: ''
  name: specVersion
  type: ''
- container: ''
  name: operationId
  type: ''
- container: ''
  name: httpMethod
  type: ''
- container: ''
  name: pathTemplate
  type: ''
- container: ''
  name: securityType
  type: ''
- container: ''
  name: requestBodyRequired
  type: ''
- container: ''
  name: deprecated
  type: ''
- container: list
  name: tags
  type: ''
property_count: 25
provider_name: Swagger
provider_slug: swagger
slug: swagger-context
source_filename: swagger-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"swagger\": \"https://api-evangelist.github.io/swagger/vocab#\",\n    \"oas\": \"https://spec.openapis.org/oas/v3.1.0#\",\n\n    \"OpenApiSpecification\": {\n      \"@id\": \"swagger:OpenApiSpecification\",\n      \"@type\": \"@id\"\n    },\n    \"ApiOperation\": {\n      \"@id\": \"swagger:ApiOperation\",\n      \"@type\": \"@id\"\n    },\n    \"ApiPath\": {\n      \"@id\": \"swagger:ApiPath\",\n      \"@type\": \"@id\"\n    },\n    \"ApiSchema\": {\n      \"@id\": \"swagger:ApiSchema\",\n      \"@type\": \"@id\"\n    },\n    \"SecurityScheme\": {\n      \"@id\": \"swagger:SecurityScheme\",\n      \"@type\": \"@id\"\n    },\n    \"SwaggerUi\": {\n      \"@id\": \"swagger:SwaggerUi\",\n      \"@type\": \"@id\"\n    },\n    \"SwaggerEditor\": {\n      \"@id\": \"swagger:SwaggerEditor\",\n      \"@type\": \"@id\"\n    },\n    \"SwaggerCodegen\": {\n      \"@id\": \"swagger:SwaggerCodegen\"\
  ,\n      \"@type\": \"@id\"\n    },\n\n    \"name\": { \"@id\": \"schema:name\" },\n    \"description\": { \"@id\": \"schema:description\" },\n    \"url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"version\": { \"@id\": \"schema:version\" },\n    \"softwareVersion\": { \"@id\": \"schema:softwareVersion\" },\n    \"license\": { \"@id\": \"schema:license\", \"@type\": \"@id\" },\n    \"codeRepository\": { \"@id\": \"schema:codeRepository\", \"@type\": \"@id\" },\n    \"programmingLanguage\": { \"@id\": \"schema:programmingLanguage\" },\n    \"featureList\": { \"@id\": \"schema:featureList\" },\n\n    \"specVersion\": { \"@id\": \"swagger:specVersion\" },\n    \"operationId\": { \"@id\": \"swagger:operationId\" },\n    \"httpMethod\": { \"@id\": \"swagger:httpMethod\" },\n    \"pathTemplate\": { \"@id\": \"swagger:pathTemplate\" },\n    \"securityType\": { \"@id\": \"swagger:securityType\" },\n    \"requestBodyRequired\": { \"@id\": \"swagger:requestBodyRequired\" },\n    \"\
  deprecated\": { \"@id\": \"swagger:deprecated\" },\n    \"tags\": { \"@id\": \"swagger:tags\", \"@container\": \"@list\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/swagger/refs/heads/main/json-ld/swagger-context.jsonld
tags:
- API Design
- Documentation
- Open Source
- OpenAPI
- REST
- Standard
- Swagger
- JSON-LD
- Linked Data
- Semantic Web
---
