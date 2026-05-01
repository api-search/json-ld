---
api_specs:
- filename: apollo-open-api.yml
  format: yaml
  label: Apollo Config
  slug: apollo-config
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apollo-config/refs/heads/main/openapi/apollo-open-api.yml
class_count: 6
classes:
- App
- Namespace
- Item
- Cluster
- Release
- name
context_file: json-ld/apollo-config-open-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apollo-config/refs/heads/main/json-ld/apollo-config-open-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apollo Config Open Api from Apollo Config.
layout: jsonld
name: Apollo Config Open Api Context
namespaces:
- prefix: apollo
  uri: https://apolloconfig.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: appId
  type: string
- container: ''
  name: orgId
  type: string
- container: ''
  name: orgName
  type: string
- container: ''
  name: ownerName
  type: string
- container: ''
  name: ownerEmail
  type: string
- container: ''
  name: dataChangeCreatedBy
  type: string
- container: ''
  name: dataChangeLastModifiedBy
  type: string
- container: ''
  name: dataChangeCreatedTime
  type: dateTime
- container: ''
  name: dataChangeLastModifiedTime
  type: dateTime
- container: ''
  name: clusterName
  type: string
- container: ''
  name: namespaceName
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: isPublic
  type: boolean
- container: set
  name: items
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: namespaceId
  type: integer
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: lineNum
  type: integer
- container: ''
  name: isAbandoned
  type: boolean
- container: ''
  name: configurations
  type: reference
property_count: 22
provider_name: Apollo Config
provider_slug: apollo-config
slug: apollo-config-open-api-context
source_filename: apollo-config-open-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"apollo\": \"https://apolloconfig.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"App\": \"apollo:App\",\n    \"Namespace\": \"apollo:Namespace\",\n    \"Item\": \"apollo:Item\",\n    \"Cluster\": \"apollo:Cluster\",\n    \"Release\": \"apollo:Release\",\n    \"name\": \"schema:name\",\n    \"appId\": {\n      \"@id\": \"apollo:appId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orgId\": {\n      \"@id\": \"apollo:orgId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orgName\": {\n      \"@id\": \"apollo:orgName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerName\": {\n      \"@id\": \"apollo:ownerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerEmail\": {\n      \"@id\": \"apollo:ownerEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataChangeCreatedBy\": {\n      \"@id\"\
  : \"apollo:dataChangeCreatedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataChangeLastModifiedBy\": {\n      \"@id\": \"apollo:dataChangeLastModifiedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataChangeCreatedTime\": {\n      \"@id\": \"apollo:dataChangeCreatedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dataChangeLastModifiedTime\": {\n      \"@id\": \"apollo:dataChangeLastModifiedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"clusterName\": {\n      \"@id\": \"apollo:clusterName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespaceName\": {\n      \"@id\": \"apollo:namespaceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"apollo:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"apollo:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isPublic\": {\n      \"@id\": \"apollo:isPublic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"items\": {\n    \
  \  \"@id\": \"apollo:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"apollo:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"namespaceId\": {\n      \"@id\": \"apollo:namespaceId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"key\": {\n      \"@id\": \"apollo:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"apollo:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lineNum\": {\n      \"@id\": \"apollo:lineNum\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isAbandoned\": {\n      \"@id\": \"apollo:isAbandoned\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"configurations\": {\n      \"@id\": \"apollo:configurations\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apollo-config/refs/heads/main/json-ld/apollo-config-open-api-context.jsonld
tags:
- Apache 2.0
- Configuration Management
- Ctrip
- Distributed Systems
- Java
- Microservices
- Open Source
- Real-Time Configuration
- JSON-LD
- Linked Data
- Semantic Web
---
