---
api_specs:
- filename: webmethods-api-gateway-openapi.yml
  format: yaml
  label: webMethods API Gateway Service Management API
  slug: webmethods-api-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/openapi/webmethods-api-gateway-openapi.yml
class_count: 0
classes: []
context_file: json-ld/software-ag-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/json-ld/software-ag-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Software Ag from Software AG.
layout: jsonld
name: Software Ag Context
namespaces:
- prefix: webmethods
  uri: https://www.softwareag.com/webmethods/ns#
- prefix: api
  uri: https://api-evangelist.github.io/software-ag/ns#
properties:
- container: ''
  name: API
  type: reference
- container: ''
  name: apiName
  type: ''
- container: ''
  name: apiVersion
  type: ''
- container: ''
  name: apiDescription
  type: ''
- container: ''
  name: type
  type: ''
- container: ''
  name: isActive
  type: boolean
- container: ''
  name: tags
  type: ''
- container: ''
  name: maturityState
  type: ''
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
- container: ''
  name: Application
  type: reference
- container: ''
  name: GatewayEndpoint
  type: reference
- container: ''
  name: Policy
  type: reference
- container: ''
  name: owner
  type: ''
- container: ''
  name: APIGateway
  type: reference
- container: ''
  name: DeveloperPortal
  type: reference
- container: ''
  name: IntegrationServer
  type: reference
- container: ''
  name: SoftwareAG
  type: reference
property_count: 18
provider_name: Software AG
provider_slug: software-ag
slug: software-ag-context
source_filename: software-ag-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"webmethods\": \"https://www.softwareag.com/webmethods/ns#\",\n    \"api\": \"https://api-evangelist.github.io/software-ag/ns#\",\n    \"API\": {\n      \"@id\": \"webmethods:API\",\n      \"@type\": \"@id\"\n    },\n    \"apiName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"apiVersion\": {\n      \"@id\": \"schema:version\"\n    },\n    \"apiDescription\": {\n      \"@id\": \"schema:description\"\n    },\n    \"type\": {\n      \"@id\": \"schema:additionalType\"\n    },\n    \"isActive\": {\n      \"@id\": \"webmethods:isActive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\"\n    },\n    \"maturityState\": {\n      \"@id\": \"webmethods:maturityState\"\n    },\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"Application\": {\n      \"@id\": \"webmethods:Application\",\n      \"@type\": \"@id\"\n    },\n    \"GatewayEndpoint\": {\n      \"@id\": \"webmethods:GatewayEndpoint\",\n      \"@type\": \"@id\"\n    },\n    \"Policy\": {\n      \"@id\": \"webmethods:Policy\",\n      \"@type\": \"@id\"\n    },\n    \"owner\": {\n      \"@id\": \"schema:author\"\n    },\n    \"APIGateway\": {\n      \"@id\": \"webmethods:APIGateway\",\n      \"@type\": \"@id\"\n    },\n    \"DeveloperPortal\": {\n      \"@id\": \"webmethods:DeveloperPortal\",\n      \"@type\": \"@id\"\n    },\n    \"IntegrationServer\": {\n      \"@id\": \"webmethods:IntegrationServer\",\n      \"@type\": \"@id\"\n    },\n    \"SoftwareAG\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/json-ld/software-ag-context.jsonld
tags:
- API Management
- Enterprise Integration
- iPaaS
- webMethods
- Integration Platform
- API Gateway
- JSON-LD
- Linked Data
- Semantic Web
---
