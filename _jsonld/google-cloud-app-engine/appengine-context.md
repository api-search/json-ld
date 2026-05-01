---
api_specs:
- filename: appengine-openapi.yml
  format: yaml
  label: Google Cloud App Engine Admin API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-app-engine/refs/heads/main/openapi/appengine-openapi.yml
class_count: 11
classes:
- Application
- Service
- Version
- Instance
- name
- description
- id
- locationId
- servingStatus
- runtime
- instanceClass
context_file: json-ld/appengine-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-app-engine/refs/heads/main/json-ld/appengine-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Appengine from Google Cloud App Engine.
layout: jsonld
name: Appengine Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: gcp
  uri: https://cloud.google.com/schema#
properties:
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: defaultHostname
  type: string
- container: ''
  name: memoryUsage
  type: string
property_count: 3
provider_name: Google Cloud App Engine
provider_slug: google-cloud-app-engine
slug: appengine-context
source_filename: appengine-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://cloud.google.com/appengine/schema#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"gcp\": \"https://cloud.google.com/schema#\",\n    \"Application\": \"gcp:AppEngineApplication\",\n    \"Service\": \"gcp:AppEngineService\",\n    \"Version\": \"gcp:AppEngineVersion\",\n    \"Instance\": \"gcp:AppEngineInstance\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"id\": \"schema:identifier\",\n    \"locationId\": \"gcp:locationId\",\n    \"servingStatus\": \"gcp:servingStatus\",\n    \"runtime\": \"gcp:runtime\",\n    \"createTime\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"defaultHostname\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceClass\": \"gcp:instanceClass\",\n    \"memoryUsage\": {\n      \"\
  @id\": \"gcp:memoryUsage\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-app-engine/refs/heads/main/json-ld/appengine-context.jsonld
tags:
- App Engine
- Compute
- Google Cloud
- PaaS
- Serverless
- Web Applications
- JSON-LD
- Linked Data
- Semantic Web
---
