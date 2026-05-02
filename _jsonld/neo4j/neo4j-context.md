---
api_specs:
- filename: neo4j-http-api-openapi.yml
  format: yaml
  label: Neo4j HTTP API
  slug: http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/neo4j/refs/heads/main/openapi/neo4j-http-api-openapi.yml
- filename: neo4j-query-api-openapi.yml
  format: yaml
  label: Neo4j Query API
  slug: query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/neo4j/refs/heads/main/openapi/neo4j-query-api-openapi.yml
- filename: neo4j-aura-api-openapi.yml
  format: yaml
  label: Neo4j Aura API
  slug: aura-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/neo4j/refs/heads/main/openapi/neo4j-aura-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/neo4j-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/neo4j/refs/heads/main/json-ld/neo4j-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Neo4J from Neo4j.
layout: jsonld
name: Neo4J Context
namespaces:
- prefix: neo4j
  uri: https://neo4j.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: GraphDatabase
  type: ''
- container: ''
  name: Node
  type: ''
- container: ''
  name: Relationship
  type: ''
- container: ''
  name: CypherQuery
  type: ''
- container: ''
  name: AuraInstance
  type: ''
- container: ''
  name: Tenant
  type: ''
- container: ''
  name: Snapshot
  type: ''
property_count: 7
provider_name: Neo4j
provider_slug: neo4j
slug: neo4j-context
source_filename: neo4j-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"neo4j\": \"https://neo4j.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"GraphDatabase\": {\n      \"@id\": \"neo4j:GraphDatabase\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"version\": \"schema:softwareVersion\",\n        \"edition\": \"neo4j:edition\",\n        \"connectionUrl\": {\n          \"@id\": \"neo4j:connectionUrl\",\n          \"@type\": \"@id\"\n        },\n        \"boltUrl\": {\n          \"@id\": \"neo4j:boltUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Node\": {\n      \"@id\": \"neo4j:Node\",\n      \"@context\": {\n        \"elementId\": \"neo4j:elementId\",\n        \"labels\": {\n          \"@id\": \"neo4j:labels\",\n          \"@container\": \"@set\"\n        },\n        \"properties\"\
  : \"neo4j:properties\"\n      }\n    },\n\n    \"Relationship\": {\n      \"@id\": \"neo4j:Relationship\",\n      \"@context\": {\n        \"elementId\": \"neo4j:elementId\",\n        \"relationshipType\": \"neo4j:relationshipType\",\n        \"startNode\": {\n          \"@id\": \"neo4j:startNode\",\n          \"@type\": \"@id\"\n        },\n        \"endNode\": {\n          \"@id\": \"neo4j:endNode\",\n          \"@type\": \"@id\"\n        },\n        \"properties\": \"neo4j:properties\"\n      }\n    },\n\n    \"CypherQuery\": {\n      \"@id\": \"neo4j:CypherQuery\",\n      \"@context\": {\n        \"statement\": \"neo4j:statement\",\n        \"parameters\": \"neo4j:parameters\",\n        \"database\": \"neo4j:database\"\n      }\n    },\n\n    \"AuraInstance\": {\n      \"@id\": \"neo4j:AuraInstance\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"identifier\": \"schema:identifier\",\n        \"status\": \"neo4j:instanceStatus\",\n        \"cloudProvider\": \"\
  neo4j:cloudProvider\",\n        \"region\": \"neo4j:region\",\n        \"instanceType\": \"neo4j:instanceType\",\n        \"memory\": \"neo4j:memory\",\n        \"storage\": \"neo4j:storage\",\n        \"connectionUrl\": {\n          \"@id\": \"neo4j:connectionUrl\",\n          \"@type\": \"@id\"\n        },\n        \"metricsUrl\": {\n          \"@id\": \"neo4j:metricsUrl\",\n          \"@type\": \"@id\"\n        },\n        \"neo4jVersion\": \"schema:softwareVersion\",\n        \"tenant\": {\n          \"@id\": \"neo4j:tenant\",\n          \"@type\": \"@id\"\n        },\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Tenant\": {\n      \"@id\": \"neo4j:Tenant\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"identifier\": \"schema:identifier\",\n        \"instances\": {\n          \"@id\": \"neo4j:instances\",\n          \"@container\": \"@set\"\n        }\n      }\n\
  \    },\n\n    \"Snapshot\": {\n      \"@id\": \"neo4j:Snapshot\",\n      \"@context\": {\n        \"identifier\": \"schema:identifier\",\n        \"status\": \"neo4j:snapshotStatus\",\n        \"instance\": {\n          \"@id\": \"neo4j:instance\",\n          \"@type\": \"@id\"\n        },\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"exportable\": {\n          \"@id\": \"neo4j:exportable\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/neo4j/refs/heads/main/json-ld/neo4j-context.jsonld
tags:
- Graph Database
- Cypher
- Cloud
- GraphQL
- Drivers
- APIs
- JSON-LD
- Linked Data
- Semantic Web
---
