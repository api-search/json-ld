---
api_specs:
- filename: consul-connect-openapi.yml
  format: yaml
  label: Consul Connect HTTP API
  slug: consul-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/consul-connect/refs/heads/main/openapi/consul-connect-openapi.yml
class_count: 0
classes: []
context_file: json-ld/consul-connect-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/consul-connect/refs/heads/main/json-ld/consul-connect-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Consul Connect from Consul Connect.
layout: jsonld
name: Consul Connect Context
namespaces:
- prefix: consul
  uri: https://developer.hashicorp.com/consul/vocabulary#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Intention
  type: ''
- container: ''
  name: Service
  type: ''
- container: ''
  name: CaRoot
  type: ''
- container: ''
  name: CaConfiguration
  type: ''
property_count: 4
provider_name: Consul Connect
provider_slug: consul-connect
slug: consul-connect-context
source_filename: consul-connect-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"consul\": \"https://developer.hashicorp.com/consul/vocabulary#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Intention\": {\n      \"@id\": \"consul:Intention\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"sourceName\": \"consul:sourceServiceName\",\n        \"destinationName\": \"consul:destinationServiceName\",\n        \"sourceNamespace\": \"consul:sourceNamespace\",\n        \"destinationNamespace\": \"consul:destinationNamespace\",\n        \"action\": \"consul:authorizationAction\",\n        \"description\": \"schema:description\",\n        \"precedence\": {\n          \"@id\": \"consul:precedence\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"meta\": \"consul:metadata\",\n        \"createIndex\": {\n          \"@id\": \"consul:createIndex\",\n          \"@type\"\
  : \"xsd:integer\"\n        },\n        \"modifyIndex\": {\n          \"@id\": \"consul:modifyIndex\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Service\": {\n      \"@id\": \"consul:Service\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"consul:namespace\",\n        \"partition\": \"consul:partition\",\n        \"tags\": {\n          \"@id\": \"consul:tags\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"CaRoot\": {\n      \"@id\": \"consul:CaRoot\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"trustDomain\": \"consul:trustDomain\",\n        \"rootCert\": \"consul:rootCertificate\",\n        \"active\": \"consul:isActive\",\n        \"notBefore\": {\n          \"@id\": \"consul:notBefore\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"notAfter\": {\n          \"@id\": \"consul:notAfter\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CaConfiguration\": {\n      \"@id\": \"consul:CaConfiguration\",\n      \"@context\": {\n        \"provider\": \"consul:caProvider\",\n        \"config\": \"consul:providerConfig\",\n        \"state\": \"consul:providerState\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/consul-connect/refs/heads/main/json-ld/consul-connect-context.jsonld
tags:
- Consul
- Envoy
- HashiCorp
- Intentions
- Kubernetes
- mTLS
- Service Mesh
- Sidecar
- Zero Trust
- JSON-LD
- Linked Data
- Semantic Web
---
