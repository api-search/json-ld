---
class_count: 0
classes: []
context_file: json-ld/cartography-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cartography/refs/heads/main/json-ld/cartography-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cartography from Cartography.
layout: jsonld
name: Cartography Context
namespaces:
- prefix: cartography
  uri: https://lyft.github.io/cartography/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Asset
  type: ''
- container: ''
  name: Identity
  type: ''
- container: ''
  name: CloudAccount
  type: ''
- container: ''
  name: ComputeInstance
  type: ''
- container: ''
  name: Datastore
  type: ''
- container: ''
  name: Permission
  type: ''
- container: ''
  name: Repository
  type: ''
- container: ''
  name: Detection
  type: ''
- container: ''
  name: Relationship
  type: ''
property_count: 9
provider_name: Cartography
provider_slug: cartography
slug: cartography-context
source_filename: cartography-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cartography\": \"https://lyft.github.io/cartography/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Asset\": {\n      \"@id\": \"cartography:Asset\",\n      \"@context\": {\n        \"assetId\": \"schema:identifier\",\n        \"assetType\": \"cartography:assetType\",\n        \"provider\": \"schema:provider\",\n        \"firstSeen\": {\n          \"@id\": \"cartography:firstSeen\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastUpdated\": {\n          \"@id\": \"cartography:lastUpdated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Identity\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"principalId\": \"schema:identifier\",\n        \"principalType\": \"cartography:principalType\",\n        \"email\": \"schema:email\",\n        \"provider\": \"schema:provider\"\n      }\n    },\n\n\
  \    \"CloudAccount\": {\n      \"@id\": \"cartography:CloudAccount\",\n      \"@context\": {\n        \"accountId\": \"schema:identifier\",\n        \"provider\": \"schema:provider\",\n        \"tenant\": \"cartography:tenant\"\n      }\n    },\n\n    \"ComputeInstance\": {\n      \"@id\": \"cartography:ComputeInstance\",\n      \"@context\": {\n        \"instanceId\": \"schema:identifier\",\n        \"region\": \"schema:addressRegion\",\n        \"publicIp\": \"cartography:publicIp\",\n        \"privateIp\": \"cartography:privateIp\",\n        \"exposedToInternet\": {\n          \"@id\": \"cartography:exposedToInternet\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Datastore\": {\n      \"@id\": \"cartography:Datastore\",\n      \"@context\": {\n        \"datastoreId\": \"schema:identifier\",\n        \"datastoreType\": \"cartography:datastoreType\",\n        \"encrypted\": {\n          \"@id\": \"cartography:encrypted\",\n          \"@type\": \"xsd:boolean\"\
  \n        },\n        \"public\": {\n          \"@id\": \"cartography:public\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Permission\": {\n      \"@id\": \"cartography:Permission\",\n      \"@context\": {\n        \"principal\": {\n          \"@id\": \"cartography:principal\",\n          \"@type\": \"@id\"\n        },\n        \"resource\": {\n          \"@id\": \"cartography:resource\",\n          \"@type\": \"@id\"\n        },\n        \"action\": \"cartography:action\",\n        \"effect\": \"cartography:effect\"\n      }\n    },\n\n    \"Repository\": {\n      \"@id\": \"schema:SoftwareSourceCode\",\n      \"@context\": {\n        \"repoId\": \"schema:identifier\",\n        \"url\": \"schema:codeRepository\",\n        \"private\": {\n          \"@id\": \"cartography:private\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Detection\": {\n      \"@id\": \"cartography:Detection\",\n      \"@context\": {\n        \"detectionId\"\
  : \"schema:identifier\",\n        \"severity\": \"cartography:severity\",\n        \"raisedAt\": {\n          \"@id\": \"cartography:raisedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"source\": \"schema:provider\"\n      }\n    },\n\n    \"Relationship\": {\n      \"@id\": \"cartography:Relationship\",\n      \"@context\": {\n        \"edgeType\": \"cartography:edgeType\",\n        \"from\": {\n          \"@id\": \"cartography:from\",\n          \"@type\": \"@id\"\n        },\n        \"to\": {\n          \"@id\": \"cartography:to\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cartography/refs/heads/main/json-ld/cartography-context.jsonld
tags:
- Security
- Cloud Security
- Graph
- CSPM
- Neo4j
- Open Source
- Lyft
- Asset Inventory
- Identity
- JSON-LD
- Linked Data
- Semantic Web
---
