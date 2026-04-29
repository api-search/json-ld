---
api_specs:
- filename: teradata-querygrid-manager-api.yaml
  format: yaml
  label: Teradata QueryGrid Manager API
  slug: querygrid-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/teradata/refs/heads/main/openapi/teradata-querygrid-manager-api.yaml
- filename: teradata-query-service-api.yaml
  format: yaml
  label: Teradata Query Service API
  slug: query-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/teradata/refs/heads/main/openapi/teradata-query-service-api.yaml
class_count: 15
classes:
- ApiInfo
- Issue
- Manager
- Node
- QuerySummary
- Software
- User
- DataCenter
- System
- Bridge
- Connector
- Link
- Fabric
- Network
- CommPolicy
context_file: json-ld/teradata-querygrid-manager-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/teradata/refs/heads/main/json-ld/teradata-querygrid-manager-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Teradata Querygrid Manager Api from Teradata.
layout: jsonld
name: Teradata Querygrid Manager Api Context
namespaces:
- prefix: td
  uri: https://developer.teradata.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: version
  type: string
- container: ''
  name: build
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: name
  type: string
- container: ''
  name: hostname
  type: string
- container: ''
  name: systemId
  type: string
- container: ''
  name: softwareVersion
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: dataCenterId
  type: string
- container: ''
  name: sourceSystemId
  type: string
- container: ''
  name: targetSystemId
  type: string
- container: ''
  name: subnet
  type: string
- container: ''
  name: encryption
  type: boolean
- container: ''
  name: compression
  type: boolean
- container: ''
  name: maxBandwidth
  type: integer
- container: ''
  name: fabricId
  type: string
- container: set
  name: roles
  type: ''
- container: ''
  name: username
  type: string
property_count: 23
provider_name: Teradata
provider_slug: teradata
slug: teradata-querygrid-manager-api-context
source_filename: teradata-querygrid-manager-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"td\": \"https://developer.teradata.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ApiInfo\": \"td:ApiInfo\",\n    \"Issue\": \"td:Issue\",\n    \"Manager\": \"td:Manager\",\n    \"Node\": \"td:Node\",\n    \"QuerySummary\": \"td:QuerySummary\",\n    \"Software\": \"td:Software\",\n    \"User\": \"td:User\",\n    \"DataCenter\": \"td:DataCenter\",\n    \"System\": \"td:System\",\n    \"Bridge\": \"td:Bridge\",\n    \"Connector\": \"td:Connector\",\n    \"Link\": \"td:Link\",\n    \"Fabric\": \"td:Fabric\",\n    \"Network\": \"td:Network\",\n    \"CommPolicy\": \"td:CommPolicy\",\n    \"version\": { \"@id\": \"schema:version\", \"@type\": \"xsd:string\" },\n    \"build\": { \"@id\": \"td:build\", \"@type\": \"xsd:string\" },\n    \"status\": { \"@id\": \"td:status\", \"@type\": \"xsd:string\" },\n    \"severity\"\
  : { \"@id\": \"td:severity\", \"@type\": \"xsd:string\" },\n    \"message\": { \"@id\": \"td:message\", \"@type\": \"xsd:string\" },\n    \"source\": { \"@id\": \"td:source\", \"@type\": \"xsd:string\" },\n    \"timestamp\": { \"@id\": \"td:timestamp\", \"@type\": \"xsd:dateTime\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"hostname\": { \"@id\": \"td:hostname\", \"@type\": \"xsd:string\" },\n    \"systemId\": { \"@id\": \"td:systemId\", \"@type\": \"xsd:string\" },\n    \"softwareVersion\": { \"@id\": \"schema:softwareVersion\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"location\": { \"@id\": \"td:location\", \"@type\": \"xsd:string\" },\n    \"dataCenterId\": { \"@id\": \"td:dataCenterId\", \"@type\": \"xsd:string\" },\n    \"sourceSystemId\": { \"@id\": \"td:sourceSystemId\", \"@type\": \"xsd:string\" },\n    \"targetSystemId\": { \"@id\": \"td:targetSystemId\", \"@type\"\
  : \"xsd:string\" },\n    \"subnet\": { \"@id\": \"td:subnet\", \"@type\": \"xsd:string\" },\n    \"encryption\": { \"@id\": \"td:encryption\", \"@type\": \"xsd:boolean\" },\n    \"compression\": { \"@id\": \"td:compression\", \"@type\": \"xsd:boolean\" },\n    \"maxBandwidth\": { \"@id\": \"td:maxBandwidth\", \"@type\": \"xsd:integer\" },\n    \"fabricId\": { \"@id\": \"td:fabricId\", \"@type\": \"xsd:string\" },\n    \"roles\": { \"@id\": \"td:roles\", \"@container\": \"@set\" },\n    \"username\": { \"@id\": \"td:username\", \"@type\": \"xsd:string\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/teradata/refs/heads/main/json-ld/teradata-querygrid-manager-api-context.jsonld
tags:
- Analytics
- Cloud
- Data Management
- Data Warehousing
- Database
- Enterprise
- Machine Learning
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
