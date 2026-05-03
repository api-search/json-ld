---
api_specs:
- filename: vineyard-python-client-openapi.yml
  format: yaml
  label: Vineyard Python Client API
  slug: vineyard-python-client
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vineyard/refs/heads/main/openapi/vineyard-python-client-openapi.yml
class_count: 0
classes: []
context_file: json-ld/vineyard-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vineyard/refs/heads/main/json-ld/vineyard-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vineyard from Vineyard.
layout: jsonld
name: Vineyard Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: k8s
  uri: https://kubernetes.io/
properties:
- container: ''
  name: VineyardObject
  type: reference
- container: ''
  name: VineyardMetadata
  type: reference
- container: ''
  name: VineyardInstance
  type: reference
- container: ''
  name: GlobalObject
  type: reference
- container: ''
  name: LocalObject
  type: reference
- container: ''
  name: Blob
  type: reference
- container: ''
  name: id
  type: ''
- container: ''
  name: typename
  type: ''
- container: ''
  name: nbytes
  type: ''
- container: ''
  name: isglobal
  type: http://www.w3.org/2001/XMLSchema#boolean
- container: ''
  name: islocal
  type: http://www.w3.org/2001/XMLSchema#boolean
- container: ''
  name: instance_id
  type: ''
- container: ''
  name: hostname
  type: ''
- container: ''
  name: signature
  type: ''
- container: list
  name: members
  type: ''
- container: ''
  name: socket
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: version
  type: ''
- container: ''
  name: Vineyardd
  type: reference
- container: ''
  name: Sidecar
  type: reference
- container: ''
  name: Operation
  type: reference
- container: ''
  name: Backup
  type: reference
- container: ''
  name: Recover
  type: reference
property_count: 24
provider_name: Vineyard
provider_slug: vineyard
slug: vineyard-context
source_filename: vineyard-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://v6d.io/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"k8s\": \"https://kubernetes.io/\",\n\n    \"VineyardObject\": {\n      \"@id\": \"https://v6d.io/vocab/VineyardObject\",\n      \"@type\": \"@id\"\n    },\n    \"VineyardMetadata\": {\n      \"@id\": \"https://v6d.io/vocab/VineyardMetadata\",\n      \"@type\": \"@id\"\n    },\n    \"VineyardInstance\": {\n      \"@id\": \"https://v6d.io/vocab/VineyardInstance\",\n      \"@type\": \"@id\"\n    },\n    \"GlobalObject\": {\n      \"@id\": \"https://v6d.io/vocab/GlobalObject\",\n      \"@type\": \"@id\"\n    },\n    \"LocalObject\": {\n      \"@id\": \"https://v6d.io/vocab/LocalObject\",\n      \"@type\": \"@id\"\n    },\n    \"Blob\": {\n      \"@id\": \"https://v6d.io/vocab/Blob\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"typename\": {\n      \"@id\": \"https://v6d.io/vocab/typename\"\n    },\n    \"nbytes\"\
  : {\n      \"@id\": \"schema:fileSize\"\n    },\n    \"isglobal\": {\n      \"@id\": \"https://v6d.io/vocab/isglobal\",\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#boolean\"\n    },\n    \"islocal\": {\n      \"@id\": \"https://v6d.io/vocab/islocal\",\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#boolean\"\n    },\n    \"instance_id\": {\n      \"@id\": \"https://v6d.io/vocab/instanceId\"\n    },\n    \"hostname\": {\n      \"@id\": \"schema:serverName\"\n    },\n    \"signature\": {\n      \"@id\": \"https://v6d.io/vocab/signature\"\n    },\n    \"members\": {\n      \"@id\": \"https://v6d.io/vocab/members\",\n      \"@container\": \"@list\"\n    },\n    \"socket\": {\n      \"@id\": \"https://v6d.io/vocab/ipcSocket\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\"\n    },\n\n    \"Vineyardd\": {\n      \"@id\": \"https://v6d.io/vocab/Vineyardd\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"Sidecar\": {\n      \"@id\": \"https://v6d.io/vocab/Sidecar\",\n      \"@type\": \"@id\"\n    },\n    \"Operation\": {\n      \"@id\": \"https://v6d.io/vocab/Operation\",\n      \"@type\": \"@id\"\n    },\n    \"Backup\": {\n      \"@id\": \"https://v6d.io/vocab/Backup\",\n      \"@type\": \"@id\"\n    },\n    \"Recover\": {\n      \"@id\": \"https://v6d.io/vocab/Recover\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vineyard/refs/heads/main/json-ld/vineyard-context.jsonld
tags:
- Big Data
- CNCF
- Cloud Native
- Data Engineering
- Distributed Systems
- In-Memory Storage
- Kubernetes
- Machine Learning
- Metadata Management
- Python
- Zero-Copy
- JSON-LD
- Linked Data
- Semantic Web
---
