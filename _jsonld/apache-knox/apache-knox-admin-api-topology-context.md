---
api_specs:
- filename: apache-knox-admin-api.yaml
  format: yaml
  label: Apache Knox Admin REST API
  slug: admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-knox/refs/heads/main/openapi/apache-knox-admin-api.yaml
class_count: 3
classes:
- Topology
- TopologyList
- name
context_file: json-ld/apache-knox-admin-api-topology-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-knox/refs/heads/main/json-ld/apache-knox-admin-api-topology-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Knox Admin Api Topology from Apache Knox.
layout: jsonld
name: Apache Knox Admin Api Topology Context
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
- container: ''
  name: uri
  type: string
- container: ''
  name: timestamp
  type: integer
- container: ''
  name: topologies
  type: reference
- container: set
  name: topology
  type: string
property_count: 4
provider_name: Apache Knox
provider_slug: apache-knox
slug: apache-knox-admin-api-topology-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"knox\": \"https://apache-knox.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Topology\": \"knox:Topology\",\n    \"TopologyList\": \"knox:TopologyList\",\n    \"name\": \"schema:name\",\n    \"uri\": {\n      \"@id\": \"knox:uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"knox:timestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"topologies\": {\n      \"@id\": \"knox:topologies\",\n      \"@type\": \"@id\"\n    },\n    \"topology\": {\n      \"@id\": \"knox:topology\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-knox/refs/heads/main/json-ld/apache-knox-admin-api-topology-context.jsonld
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
