---
class_count: 3
classes:
- DescriptorList
- Descriptor
- name
context_file: json-ld/apache-knox-admin-api-descriptor-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-knox/refs/heads/main/json-ld/apache-knox-admin-api-descriptor-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Knox Admin Api Descriptor from Apache Knox.
layout: jsonld
name: Apache Knox Admin Api Descriptor Context
namespaces:
- prefix: knox
  uri: https://apache-knox.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: descriptors
  type: string
- container: ''
  name: discoveryType
  type: string
- container: ''
  name: discoveryAddress
  type: string
- container: ''
  name: cluster
  type: string
- container: ''
  name: providerConfig
  type: string
- container: set
  name: services
  type: reference
property_count: 6
provider_name: Apache Knox
provider_slug: apache-knox
slug: apache-knox-admin-api-descriptor-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"knox\": \"https://apache-knox.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DescriptorList\": \"knox:DescriptorList\",\n    \"Descriptor\": \"knox:Descriptor\",\n    \"descriptors\": {\n      \"@id\": \"knox:descriptors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"discoveryType\": {\n      \"@id\": \"knox:discoveryType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"discoveryAddress\": {\n      \"@id\": \"knox:discoveryAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cluster\": {\n      \"@id\": \"knox:cluster\",\n      \"@type\": \"xsd:string\"\n    },\n    \"providerConfig\": {\n      \"@id\": \"knox:providerConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"services\": {\n      \"@id\": \"knox:services\",\n\
  \      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-knox/refs/heads/main/json-ld/apache-knox-admin-api-descriptor-context.jsonld
tags:
- API Gateway
- Authentication
- Hadoop
- Open Source
- Security
- SSO
- JSON-LD
- Linked Data
- Semantic Web
---
