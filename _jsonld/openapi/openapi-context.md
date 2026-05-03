---
class_count: 0
classes: []
context_file: json-ld/openapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/openapi/refs/heads/main/json-ld/openapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Openapi from OpenAPI.
layout: jsonld
name: Openapi Context
namespaces:
- prefix: oas
  uri: https://spec.openapis.org/oas/3.1/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: hydra
  uri: http://www.w3.org/ns/hydra/core#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: vann
  uri: http://purl.org/vocab/vann/
properties:
- container: ''
  name: OpenAPIDocument
  type: reference
- container: ''
  name: openapi
  type: string
- container: ''
  name: info
  type: reference
- container: ''
  name: InfoObject
  type: reference
- container: ''
  name: title
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: termsOfService
  type: reference
- container: ''
  name: contact
  type: reference
- container: ''
  name: ContactObject
  type: reference
- container: ''
  name: name
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: email
  type: string
- container: ''
  name: license
  type: reference
- container: ''
  name: LicenseObject
  type: reference
- container: ''
  name: version
  type: string
- container: ''
  name: ServerObject
  type: reference
- container: set
  name: servers
  type: reference
- container: ''
  name: variables
  type: reference
- container: ''
  name: paths
  type: reference
- container: ''
  name: PathItemObject
  type: reference
- container: ''
  name: OperationObject
  type: reference
- container: ''
  name: get
  type: reference
- container: ''
  name: put
  type: reference
- container: ''
  name: post
  type: reference
- container: ''
  name: delete
  type: reference
- container: ''
  name: patch
  type: reference
- container: ''
  name: operationId
  type: string
- container: set
  name: parameters
  type: reference
- container: ''
  name: ParameterObject
  type: reference
- container: ''
  name: requestBody
  type: reference
- container: ''
  name: responses
  type: reference
- container: ''
  name: ResponseObject
  type: reference
- container: set
  name: tags
  type: string
- container: ''
  name: TagObject
  type: reference
- container: ''
  name: externalDocs
  type: reference
- container: ''
  name: deprecated
  type: boolean
- container: set
  name: security
  type: reference
- container: ''
  name: SecuritySchemeObject
  type: reference
- container: ''
  name: components
  type: reference
- container: ''
  name: ComponentsObject
  type: reference
- container: ''
  name: webhooks
  type: reference
- container: ''
  name: schema_def
  type: reference
- container: ''
  name: content
  type: reference
- container: ''
  name: MediaTypeObject
  type: reference
- container: ''
  name: example
  type: reference
- container: set
  name: examples
  type: reference
- container: ''
  name: encoding
  type: reference
- container: ''
  name: LinkObject
  type: reference
- container: ''
  name: callbacks
  type: reference
property_count: 50
provider_name: OpenAPI
provider_slug: openapi
slug: openapi-context
source_filename: openapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oas\": \"https://spec.openapis.org/oas/3.1/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"vann\": \"http://purl.org/vocab/vann/\",\n\n    \"OpenAPIDocument\": {\n      \"@id\": \"oas:OpenAPIDocument\",\n      \"@type\": \"@id\"\n    },\n    \"openapi\": {\n      \"@id\": \"oas:specificationVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"info\": {\n      \"@id\": \"oas:info\",\n      \"@type\": \"@id\"\n    },\n    \"InfoObject\": {\n      \"@id\": \"oas:InfoObject\",\n      \"@type\": \"@id\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"schema:abstract\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"termsOfService\": {\n      \"@id\": \"schema:termsOfService\",\n      \"@type\": \"@id\"\n    },\n    \"contact\": {\n      \"@id\": \"schema:contactPoint\",\n      \"@type\": \"@id\"\n    },\n    \"ContactObject\": {\n      \"@id\": \"schema:ContactPoint\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"license\": {\n      \"@id\": \"schema:license\",\n      \"@type\": \"@id\"\n    },\n    \"LicenseObject\": {\n      \"@id\": \"schema:CreativeWork\",\n      \"@type\": \"@id\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServerObject\": {\n      \"@id\": \"oas:ServerObject\",\n      \"@type\": \"@id\"\n    },\n    \"\
  servers\": {\n      \"@id\": \"oas:servers\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"variables\": {\n      \"@id\": \"oas:serverVariables\",\n      \"@type\": \"@id\"\n    },\n    \"paths\": {\n      \"@id\": \"oas:paths\",\n      \"@type\": \"@id\"\n    },\n    \"PathItemObject\": {\n      \"@id\": \"hydra:Class\",\n      \"@type\": \"@id\"\n    },\n    \"OperationObject\": {\n      \"@id\": \"hydra:Operation\",\n      \"@type\": \"@id\"\n    },\n    \"get\": {\n      \"@id\": \"hydra:method\",\n      \"@type\": \"@id\"\n    },\n    \"put\": {\n      \"@id\": \"hydra:method\",\n      \"@type\": \"@id\"\n    },\n    \"post\": {\n      \"@id\": \"hydra:method\",\n      \"@type\": \"@id\"\n    },\n    \"delete\": {\n      \"@id\": \"hydra:method\",\n      \"@type\": \"@id\"\n    },\n    \"patch\": {\n      \"@id\": \"hydra:method\",\n      \"@type\": \"@id\"\n    },\n    \"operationId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"parameters\": {\n      \"@id\": \"hydra:expects\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"ParameterObject\": {\n      \"@id\": \"oas:ParameterObject\",\n      \"@type\": \"@id\"\n    },\n    \"requestBody\": {\n      \"@id\": \"hydra:expects\",\n      \"@type\": \"@id\"\n    },\n    \"responses\": {\n      \"@id\": \"hydra:returns\",\n      \"@type\": \"@id\"\n    },\n    \"ResponseObject\": {\n      \"@id\": \"oas:ResponseObject\",\n      \"@type\": \"@id\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@type\": \"xsd:string\",\n      \"@container\": \"@set\"\n    },\n    \"TagObject\": {\n      \"@id\": \"oas:TagObject\",\n      \"@type\": \"@id\"\n    },\n    \"externalDocs\": {\n      \"@id\": \"rdfs:seeAlso\",\n      \"@type\": \"@id\"\n    },\n    \"deprecated\": {\n      \"@id\": \"oas:deprecated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"security\": {\n      \"@id\": \"oas:security\",\n      \"\
  @type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"SecuritySchemeObject\": {\n      \"@id\": \"oas:SecuritySchemeObject\",\n      \"@type\": \"@id\"\n    },\n    \"components\": {\n      \"@id\": \"oas:components\",\n      \"@type\": \"@id\"\n    },\n    \"ComponentsObject\": {\n      \"@id\": \"oas:ComponentsObject\",\n      \"@type\": \"@id\"\n    },\n    \"webhooks\": {\n      \"@id\": \"oas:webhooks\",\n      \"@type\": \"@id\"\n    },\n    \"schema_def\": {\n      \"@id\": \"oas:schema\",\n      \"@type\": \"@id\"\n    },\n    \"content\": {\n      \"@id\": \"oas:content\",\n      \"@type\": \"@id\"\n    },\n    \"MediaTypeObject\": {\n      \"@id\": \"schema:MediaObject\",\n      \"@type\": \"@id\"\n    },\n    \"example\": {\n      \"@id\": \"schema:workExample\",\n      \"@type\": \"@id\"\n    },\n    \"examples\": {\n      \"@id\": \"schema:workExample\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"encoding\": {\n      \"@id\": \"schema:encodingFormat\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"LinkObject\": {\n      \"@id\": \"hydra:Link\",\n      \"@type\": \"@id\"\n    },\n    \"callbacks\": {\n      \"@id\": \"oas:callbacks\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/openapi/refs/heads/main/json-ld/openapi-context.jsonld
tags:
- Documentation
- REST
- Specification
- JSON-LD
- Linked Data
- Semantic Web
---
