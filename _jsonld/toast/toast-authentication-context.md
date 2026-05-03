---
api_specs:
- filename: toast-orders-openapi.yaml
  format: yaml
  label: Toast Orders API
  slug: toast-orders
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-orders-openapi.yaml
- filename: toast-menus-openapi.yaml
  format: yaml
  label: Toast Menus API
  slug: toast-menus
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-menus-openapi.yaml
- filename: toast-labor-openapi.yaml
  format: yaml
  label: Toast Labor API
  slug: toast-labor
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-labor-openapi.yaml
- filename: toast-restaurants-openapi.yaml
  format: yaml
  label: Toast Restaurants API
  slug: toast-restaurants
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-restaurants-openapi.yaml
- filename: toast-stock-openapi.yaml
  format: yaml
  label: Toast Stock API
  slug: toast-stock
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-stock-openapi.yaml
- filename: toast-partners-openapi.yaml
  format: yaml
  label: Toast Partners API
  slug: toast-partners
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-partners-openapi.yaml
- filename: toast-authentication-openapi.yaml
  format: yaml
  label: Toast Authentication API
  slug: toast-authentication
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-authentication-openapi.yaml
class_count: 3
classes:
- AuthenticationRequest
- AuthenticationResponse
- AuthenticationToken
context_file: json-ld/toast-authentication-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/json-ld/toast-authentication-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Toast Authentication from Toast.
layout: jsonld
name: Toast Authentication Context
namespaces:
- prefix: toast
  uri: https://developer.toasttab.com/schema/
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
- container: ''
  name: clientId
  type: string
- container: ''
  name: clientSecret
  type: string
- container: ''
  name: expiresIn
  type: integer
- container: ''
  name: idToken
  type: string
- container: ''
  name: refreshToken
  type: string
- container: ''
  name: scope
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: token
  type: reference
- container: ''
  name: tokenType
  type: string
- container: ''
  name: userAccessType
  type: string
property_count: 11
provider_name: Toast
provider_slug: toast
slug: toast-authentication-context
source_filename: toast-authentication-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"toast\": \"https://developer.toasttab.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AuthenticationRequest\": \"toast:AuthenticationRequest\",\n    \"AuthenticationResponse\": \"toast:AuthenticationResponse\",\n    \"AuthenticationToken\": \"toast:AuthenticationToken\",\n    \"accessToken\": {\n      \"@id\": \"toast:accessToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientId\": {\n      \"@id\": \"toast:clientId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientSecret\": {\n      \"@id\": \"toast:clientSecret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresIn\": {\n      \"@id\": \"toast:expiresIn\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"idToken\": {\n      \"@id\": \"toast:idToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refreshToken\": {\n      \"@id\":\
  \ \"toast:refreshToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scope\": {\n      \"@id\": \"toast:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"toast:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token\": {\n      \"@id\": \"toast:token\",\n      \"@type\": \"@id\"\n    },\n    \"tokenType\": {\n      \"@id\": \"toast:tokenType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userAccessType\": {\n      \"@id\": \"toast:userAccessType\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/json-ld/toast-authentication-context.jsonld
tags:
- Food Service
- Point of Sale
- Restaurants
- Hospitality
- JSON-LD
- Linked Data
- Semantic Web
---
