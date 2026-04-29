---
api_specs:
- filename: oracle-integration-developer-api.yaml
  format: yaml
  label: Oracle Integration Developer API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-integration/refs/heads/main/openapi/oracle-integration-developer-api.yaml
- filename: oracle-integration-process-automation-api.yaml
  format: yaml
  label: Oracle Integration Process Automation API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-integration/refs/heads/main/openapi/oracle-integration-process-automation-api.yaml
class_count: 7
classes:
- Connection
- Integration
- MonitoringInstance
- Package
- TradingPartner
- B2BDocument
- Certificate
context_file: json-ld/oracle-integration-developer-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-integration/refs/heads/main/json-ld/oracle-integration-developer-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Integration Developer Api from Oracle Integration.
layout: jsonld
name: Oracle Integration Developer Api Context
namespaces:
- prefix: oracle
  uri: https://docs.oracle.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: adapterType
  type: string
- container: ''
  name: percentageComplete
  type: integer
- container: ''
  name: lockedFlag
  type: boolean
- container: ''
  name: testStatus
  type: string
- container: ''
  name: lastUpdatedBy
  type: string
- container: ''
  name: lastUpdated
  type: dateTime
- container: ''
  name: code
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: pattern
  type: string
- container: ''
  name: style
  type: string
- container: ''
  name: packageName
  type: string
- container: ''
  name: integrationId
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: businessIdentifier
  type: string
- container: ''
  name: contactName
  type: string
- container: ''
  name: contactEmail
  type: string
- container: ''
  name: standard
  type: string
- container: ''
  name: transactionType
  type: string
- container: ''
  name: direction
  type: string
- container: ''
  name: alias
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: expiry
  type: dateTime
property_count: 27
provider_name: Oracle Integration
provider_slug: oracle-integration
slug: oracle-integration-developer-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oracle\": \"https://docs.oracle.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Connection\": \"oracle:Connection\",\n    \"Integration\": \"oracle:Integration\",\n    \"MonitoringInstance\": \"oracle:MonitoringInstance\",\n    \"Package\": \"oracle:Package\",\n    \"TradingPartner\": \"oracle:TradingPartner\",\n    \"B2BDocument\": \"oracle:B2BDocument\",\n    \"Certificate\": \"oracle:Certificate\",\n    \"id\": {\"@id\": \"dcterms:identifier\", \"@type\": \"xsd:string\"},\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"description\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"status\": {\"@id\": \"oracle:status\", \"@type\": \"xsd:string\"},\n    \"adapterType\": {\"@id\": \"oracle:adapterType\", \"@type\": \"xsd:string\"},\n    \"percentageComplete\"\
  : {\"@id\": \"oracle:percentageComplete\", \"@type\": \"xsd:integer\"},\n    \"lockedFlag\": {\"@id\": \"oracle:lockedFlag\", \"@type\": \"xsd:boolean\"},\n    \"testStatus\": {\"@id\": \"oracle:testStatus\", \"@type\": \"xsd:string\"},\n    \"lastUpdatedBy\": {\"@id\": \"oracle:lastUpdatedBy\", \"@type\": \"xsd:string\"},\n    \"lastUpdated\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n    \"code\": {\"@id\": \"oracle:code\", \"@type\": \"xsd:string\"},\n    \"version\": {\"@id\": \"schema:version\", \"@type\": \"xsd:string\"},\n    \"pattern\": {\"@id\": \"oracle:pattern\", \"@type\": \"xsd:string\"},\n    \"style\": {\"@id\": \"oracle:style\", \"@type\": \"xsd:string\"},\n    \"packageName\": {\"@id\": \"oracle:packageName\", \"@type\": \"xsd:string\"},\n    \"integrationId\": {\"@id\": \"oracle:integrationId\", \"@type\": \"xsd:string\"},\n    \"startTime\": {\"@id\": \"oracle:startTime\", \"@type\": \"xsd:dateTime\"},\n    \"endTime\": {\"@id\": \"oracle:endTime\"\
  , \"@type\": \"xsd:dateTime\"},\n    \"businessIdentifier\": {\"@id\": \"oracle:businessIdentifier\", \"@type\": \"xsd:string\"},\n    \"contactName\": {\"@id\": \"oracle:contactName\", \"@type\": \"xsd:string\"},\n    \"contactEmail\": {\"@id\": \"schema:email\", \"@type\": \"xsd:string\"},\n    \"standard\": {\"@id\": \"oracle:standard\", \"@type\": \"xsd:string\"},\n    \"transactionType\": {\"@id\": \"oracle:transactionType\", \"@type\": \"xsd:string\"},\n    \"direction\": {\"@id\": \"oracle:direction\", \"@type\": \"xsd:string\"},\n    \"alias\": {\"@id\": \"oracle:alias\", \"@type\": \"xsd:string\"},\n    \"subject\": {\"@id\": \"oracle:subject\", \"@type\": \"xsd:string\"},\n    \"expiry\": {\"@id\": \"oracle:expiry\", \"@type\": \"xsd:dateTime\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-integration/refs/heads/main/json-ld/oracle-integration-developer-api-context.jsonld
tags:
- API Management
- Automation
- B2B Integration
- Cloud Integration
- Enterprise Integration
- Integration
- iPaaS
- Process Automation
- JSON-LD
- Linked Data
- Semantic Web
---
