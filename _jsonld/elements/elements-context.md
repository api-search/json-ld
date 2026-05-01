---
api_specs:
- filename: elements-elements-openapi.yml
  format: yaml
  label: Stoplight Elements
  slug: elements
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elements/refs/heads/main/openapi/elements-elements-openapi.yml
class_count: 0
classes: []
context_file: json-ld/elements-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/elements/refs/heads/main/json-ld/elements-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Elements from Stoplight Elements.
layout: jsonld
name: Elements Context
namespaces:
- prefix: elements
  uri: https://stoplight.io/elements/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: APIDocumentationComponent
  type: ''
- container: ''
  name: OpenAPISpecification
  type: ''
- container: ''
  name: OperationNode
  type: ''
- container: ''
  name: SchemaNode
  type: ''
- container: ''
  name: ServerNode
  type: ''
- container: ''
  name: TryItRequest
  type: ''
- container: ''
  name: LayoutConfiguration
  type: ''
property_count: 7
provider_name: Stoplight Elements
provider_slug: elements
slug: elements-context
source_filename: elements-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"elements\": \"https://stoplight.io/elements/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"APIDocumentationComponent\": {\n      \"@id\": \"elements:APIDocumentationComponent\",\n      \"@context\": {\n        \"apiDescriptionUrl\": {\n          \"@id\": \"elements:apiDescriptionUrl\",\n          \"@type\": \"@id\"\n        },\n        \"apiDescriptionDocument\": {\n          \"@id\": \"elements:apiDescriptionDocument\"\n        },\n        \"layout\": {\n          \"@id\": \"elements:layout\"\n        },\n        \"router\": {\n          \"@id\": \"elements:router\"\n        },\n        \"basePath\": {\n          \"@id\": \"elements:basePath\"\n        },\n        \"staticRouterPath\": {\n          \"@id\": \"elements:staticRouterPath\"\n        },\n        \"logo\": {\n          \"@id\": \"schema:logo\",\n\
  \          \"@type\": \"@id\"\n        },\n        \"hideTryIt\": {\n          \"@id\": \"elements:hideTryIt\"\n        },\n        \"hideTryItPanel\": {\n          \"@id\": \"elements:hideTryItPanel\"\n        },\n        \"hideSamples\": {\n          \"@id\": \"elements:hideSamples\"\n        },\n        \"hideSchemas\": {\n          \"@id\": \"elements:hideSchemas\"\n        },\n        \"hideInternal\": {\n          \"@id\": \"elements:hideInternal\"\n        },\n        \"hideExport\": {\n          \"@id\": \"elements:hideExport\"\n        },\n        \"hideServerInfo\": {\n          \"@id\": \"elements:hideServerInfo\"\n        },\n        \"hideSecurityInfo\": {\n          \"@id\": \"elements:hideSecurityInfo\"\n        },\n        \"tryItCredentialsPolicy\": {\n          \"@id\": \"elements:tryItCredentialsPolicy\"\n        },\n        \"tryItCorsProxy\": {\n          \"@id\": \"elements:tryItCorsProxy\",\n          \"@type\": \"@id\"\n        },\n        \"maxRefDepth\": {\n \
  \         \"@id\": \"elements:maxRefDepth\"\n        },\n        \"outerRouter\": {\n          \"@id\": \"elements:outerRouter\"\n        }\n      }\n    },\n\n    \"OpenAPISpecification\": {\n      \"@id\": \"elements:OpenAPISpecification\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"title\": {\n          \"@id\": \"dcterms:title\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"version\": {\n          \"@id\": \"schema:version\"\n        },\n        \"specVersion\": {\n          \"@id\": \"elements:specVersion\"\n        },\n        \"servers\": {\n          \"@id\": \"elements:servers\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"elements:tags\",\n          \"@container\": \"@set\"\n        },\n        \"paths\": {\n          \"@id\": \"elements:paths\",\n          \"@container\": \"@set\"\n\
  \        },\n        \"components\": {\n          \"@id\": \"elements:components\"\n        }\n      }\n    },\n\n    \"OperationNode\": {\n      \"@id\": \"elements:OperationNode\",\n      \"@context\": {\n        \"operationId\": {\n          \"@id\": \"elements:operationId\"\n        },\n        \"summary\": {\n          \"@id\": \"dcterms:title\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"method\": {\n          \"@id\": \"elements:httpMethod\"\n        },\n        \"path\": {\n          \"@id\": \"elements:httpPath\"\n        },\n        \"tags\": {\n          \"@id\": \"elements:tags\",\n          \"@container\": \"@set\"\n        },\n        \"internal\": {\n          \"@id\": \"elements:internal\"\n        },\n        \"deprecated\": {\n          \"@id\": \"schema:supersededBy\"\n        }\n      }\n    },\n\n    \"SchemaNode\": {\n      \"@id\": \"elements:SchemaNode\",\n      \"@context\": {\n        \"name\": {\n\
  \          \"@id\": \"schema:name\"\n        },\n        \"title\": {\n          \"@id\": \"dcterms:title\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"type\": {\n          \"@id\": \"elements:schemaType\"\n        },\n        \"properties\": {\n          \"@id\": \"elements:properties\",\n          \"@container\": \"@set\"\n        },\n        \"required\": {\n          \"@id\": \"elements:requiredProperties\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ServerNode\": {\n      \"@id\": \"elements:ServerNode\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"variables\": {\n          \"@id\": \"elements:serverVariables\"\n        }\n      }\n    },\n\n    \"TryItRequest\": {\n      \"@id\": \"elements:TryItRequest\",\n      \"@context\"\
  : {\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"method\": {\n          \"@id\": \"elements:httpMethod\"\n        },\n        \"headers\": {\n          \"@id\": \"elements:headers\",\n          \"@container\": \"@set\"\n        },\n        \"body\": {\n          \"@id\": \"elements:requestBody\"\n        },\n        \"credentialsPolicy\": {\n          \"@id\": \"elements:tryItCredentialsPolicy\"\n        },\n        \"corsProxy\": {\n          \"@id\": \"elements:tryItCorsProxy\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"LayoutConfiguration\": {\n      \"@id\": \"elements:LayoutConfiguration\",\n      \"@context\": {\n        \"layout\": {\n          \"@id\": \"elements:layout\"\n        },\n        \"router\": {\n          \"@id\": \"elements:router\"\n        },\n        \"basePath\": {\n          \"@id\": \"elements:basePath\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/elements/refs/heads/main/json-ld/elements-context.jsonld
tags:
- API Documentation
- Developer Tools
- Documentation
- Interactive Docs
- OpenAPI
- React
- Web Components
- JSON-LD
- Linked Data
- Semantic Web
---
