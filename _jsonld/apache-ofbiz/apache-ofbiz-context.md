---
class_count: 9
classes:
- RefreshRequest
- ServiceEntry
- ServiceLink
- ServiceListResponse
- ServiceResponse
- TokenData
- TokenResponse
- description
- name
context_file: json-ld/apache-ofbiz-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/json-ld/apache-ofbiz-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Ofbiz from Apache OFBiz.
layout: jsonld
name: Apache Ofbiz Context
namespaces:
- prefix: ofbiz
  uri: https://ofbiz.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accessToken
  type: string
- container: set
  name: data
  type: string
- container: ''
  name: expiresIn
  type: string
- container: ''
  name: href
  type: reference
- container: ''
  name: link
  type: reference
- container: ''
  name: refreshToken
  type: string
- container: ''
  name: rel
  type: string
- container: ''
  name: statusCode
  type: integer
- container: ''
  name: statusDescription
  type: string
- container: ''
  name: successMessage
  type: string
- container: ''
  name: tokenType
  type: string
- container: ''
  name: type
  type: string
property_count: 12
provider_name: Apache OFBiz
provider_slug: apache-ofbiz
slug: apache-ofbiz-context
source_filename: apache-ofbiz-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ofbiz\": \"https://ofbiz.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"RefreshRequest\": \"ofbiz:RefreshRequest\",\n    \"ServiceEntry\": \"ofbiz:ServiceEntry\",\n    \"ServiceLink\": \"ofbiz:ServiceLink\",\n    \"ServiceListResponse\": \"ofbiz:ServiceListResponse\",\n    \"ServiceResponse\": \"ofbiz:ServiceResponse\",\n    \"TokenData\": \"ofbiz:TokenData\",\n    \"TokenResponse\": \"ofbiz:TokenResponse\",\n    \"accessToken\": {\n      \"@id\": \"ofbiz:access_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"ofbiz:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"expiresIn\": {\n      \"@id\": \"ofbiz:expires_in\",\n      \"@type\": \"xsd:string\"\n    },\n    \"href\": {\n    \
  \  \"@id\": \"ofbiz:href\",\n      \"@type\": \"@id\"\n    },\n    \"link\": {\n      \"@id\": \"ofbiz:link\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"refreshToken\": {\n      \"@id\": \"ofbiz:refresh_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rel\": {\n      \"@id\": \"ofbiz:rel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusCode\": {\n      \"@id\": \"ofbiz:statusCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"statusDescription\": {\n      \"@id\": \"ofbiz:statusDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"successMessage\": {\n      \"@id\": \"ofbiz:successMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenType\": {\n      \"@id\": \"ofbiz:token_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"ofbiz:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/json-ld/apache-ofbiz-context.jsonld
tags:
- ERP
- CRM
- E-Commerce
- Business Applications
- Apache
- Java
- Open Source
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
