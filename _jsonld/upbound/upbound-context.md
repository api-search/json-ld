---
api_specs:
- filename: upbound-openapi.yml
  format: yaml
  label: Upbound API
  slug: upbound
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/upbound/refs/heads/main/openapi/upbound-openapi.yml
class_count: 5
classes:
- Organization
- Team
- ControlPlane
- Repository
- Robot
context_file: json-ld/upbound-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/upbound/refs/heads/main/json-ld/upbound-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Upbound from Upbound.
layout: jsonld
name: Upbound Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: upbound
  uri: https://api.upbound.io/v1/
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
  name: displayName
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: tier
  type: string
- container: ''
  name: organizationName
  type: string
- container: ''
  name: memberCount
  type: integer
- container: ''
  name: configuration
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: crossplaneVersion
  type: string
- container: ''
  name: public
  type: boolean
- container: ''
  name: packageCount
  type: integer
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 15
provider_name: Upbound
provider_slug: upbound
slug: upbound-context
source_filename: upbound-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"upbound\": \"https://api.upbound.io/v1/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Organization\": \"schema:Organization\",\n    \"id\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"displayName\": { \"@id\": \"schema:alternateName\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"tier\": { \"@id\": \"upbound:tier\", \"@type\": \"xsd:string\" },\n\n    \"Team\": \"schema:Organization\",\n    \"organizationName\": { \"@id\": \"upbound:organizationName\", \"@type\": \"xsd:string\" },\n    \"memberCount\": { \"@id\": \"schema:numberOfEmployees\", \"@type\": \"xsd:integer\" },\n\n    \"ControlPlane\": \"schema:SoftwareApplication\",\n    \"configuration\": { \"@id\": \"upbound:configuration\", \"\
  @type\": \"xsd:string\" },\n    \"status\": { \"@id\": \"upbound:status\", \"@type\": \"xsd:string\" },\n    \"region\": { \"@id\": \"upbound:region\", \"@type\": \"xsd:string\" },\n    \"crossplaneVersion\": { \"@id\": \"schema:softwareVersion\", \"@type\": \"xsd:string\" },\n\n    \"Repository\": \"schema:SoftwareSourceCode\",\n    \"public\": { \"@id\": \"schema:isAccessibleForFree\", \"@type\": \"xsd:boolean\" },\n    \"packageCount\": { \"@id\": \"upbound:packageCount\", \"@type\": \"xsd:integer\" },\n\n    \"Robot\": \"schema:Person\",\n\n    \"createdAt\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"updatedAt\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/upbound/refs/heads/main/json-ld/upbound-context.jsonld
tags:
- Cloud Infrastructure
- Crossplane
- Developer Experience
- Internal Developer Platform
- Platform Engineering
- JSON-LD
- Linked Data
- Semantic Web
---
