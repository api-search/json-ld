---
api_specs:
- filename: sap-api-management-portal-openapi.yml
  format: yaml
  label: SAP API Management API Portal API
  slug: sap-api-management-api-portal
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-api-management/refs/heads/main/openapi/sap-api-management-portal-openapi.yml
class_count: 0
classes: []
context_file: json-ld/sap-api-management-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sap-api-management/refs/heads/main/json-ld/sap-api-management-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sap Api Management from SAP API Management.
layout: jsonld
name: Sap Api Management Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sap
  uri: https://api-evangelist.github.io/sap-api-management/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: APIProxy
  type: schema:WebAPI
- container: ''
  name: APIProduct
  type: schema:Product
- container: ''
  name: APIProvider
  type: schema:Service
- container: ''
  name: Application
  type: schema:SoftwareApplication
- container: ''
  name: KeyValueMap
  type: schema:PropertyValue
- container: ''
  name: Policy
  type: schema:Action
- container: ''
  name: name
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: basepath
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: version
  type: string
property_count: 12
provider_name: SAP API Management
provider_slug: sap-api-management
slug: sap-api-management-context
source_filename: sap-api-management-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sap\": \"https://api-evangelist.github.io/sap-api-management/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"APIProxy\": {\n      \"@id\": \"sap:APIProxy\",\n      \"@type\": \"schema:WebAPI\",\n      \"schema:description\": \"A managed API proxy in SAP API Management that fronts a backend service\"\n    },\n\n    \"APIProduct\": {\n      \"@id\": \"sap:APIProduct\",\n      \"@type\": \"schema:Product\",\n      \"schema:description\": \"A bundle of API proxies published for developer consumption\"\n    },\n\n    \"APIProvider\": {\n      \"@id\": \"sap:APIProvider\",\n      \"@type\": \"schema:Service\",\n      \"schema:description\": \"A backend system registered as a data/service source in SAP API Management\"\n    },\n\n    \"Application\": {\n      \"@id\": \"sap:DeveloperApplication\",\n      \"@type\": \"schema:SoftwareApplication\",\n      \"schema:description\"\
  : \"A developer-registered application consuming SAP API products\"\n    },\n\n    \"KeyValueMap\": {\n      \"@id\": \"sap:KeyValueMap\",\n      \"@type\": \"schema:PropertyValue\",\n      \"schema:description\": \"A runtime configuration store for SAP API Management policies\"\n    },\n\n    \"Policy\": {\n      \"@id\": \"sap:Policy\",\n      \"@type\": \"schema:Action\",\n      \"schema:description\": \"A policy applied to an API proxy for security, transformation, or throttling\"\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"title\": {\n      \"@id\": \"schema:headline\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"basepath\": {\n      \"@id\": \"sap:basepath\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"\
  version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sap-api-management/refs/heads/main/json-ld/sap-api-management-context.jsonld
tags:
- API Management
- Developer Portal
- Enterprise
- SAP
- JSON-LD
- Linked Data
- Semantic Web
---
