---
api_specs:
- filename: etcd-http-gateway-openapi.yml
  format: yaml
  label: etcd HTTP Gateway API
  slug: etcd-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/etcd/refs/heads/main/openapi/etcd-http-gateway-openapi.yml
class_count: 0
classes: []
context_file: json-ld/etcd-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/etcd/refs/heads/main/json-ld/etcd-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Etcd from Etcd.
layout: jsonld
name: Etcd Context
namespaces:
- prefix: etcd
  uri: https://etcd.io/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: KeyValue
  type: ''
- container: ''
  name: Lease
  type: ''
- container: ''
  name: Member
  type: ''
- container: ''
  name: WatchEvent
  type: ''
- container: ''
  name: Permission
  type: ''
- container: ''
  name: Role
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Alarm
  type: ''
- container: ''
  name: ResponseHeader
  type: ''
property_count: 9
provider_name: Etcd
provider_slug: etcd
slug: etcd-context
source_filename: etcd-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"etcd\": \"https://etcd.io/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"KeyValue\": {\n      \"@id\": \"etcd:KeyValue\",\n      \"@context\": {\n        \"key\": {\n          \"@id\": \"etcd:key\",\n          \"@type\": \"xsd:base64Binary\"\n        },\n        \"value\": {\n          \"@id\": \"etcd:value\",\n          \"@type\": \"xsd:base64Binary\"\n        },\n        \"version\": {\n          \"@id\": \"etcd:version\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"create_revision\": {\n          \"@id\": \"etcd:createRevision\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"mod_revision\": {\n          \"@id\": \"etcd:modRevision\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"lease\": {\n          \"\
  @id\": \"etcd:lease\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Lease\": {\n      \"@id\": \"etcd:Lease\",\n      \"@context\": {\n        \"ID\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"TTL\": {\n          \"@id\": \"etcd:timeToLive\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"grantedTTL\": {\n          \"@id\": \"etcd:grantedTTL\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"keys\": {\n          \"@id\": \"etcd:attachedKeys\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Member\": {\n      \"@id\": \"etcd:Member\",\n      \"@context\": {\n        \"ID\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"peerURLs\": {\n          \"@id\": \"etcd:peerURL\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"clientURLs\": {\n          \"@id\": \"etcd:clientURL\"\
  ,\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"isLearner\": {\n          \"@id\": \"etcd:isLearner\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"WatchEvent\": {\n      \"@id\": \"etcd:WatchEvent\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"etcd:eventType\"\n        },\n        \"kv\": {\n          \"@id\": \"etcd:keyValue\",\n          \"@type\": \"@id\"\n        },\n        \"prev_kv\": {\n          \"@id\": \"etcd:previousKeyValue\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Permission\": {\n      \"@id\": \"etcd:Permission\",\n      \"@context\": {\n        \"permType\": {\n          \"@id\": \"etcd:permissionType\"\n        },\n        \"key\": {\n          \"@id\": \"etcd:key\",\n          \"@type\": \"xsd:base64Binary\"\n        },\n        \"range_end\": {\n          \"@id\": \"etcd:rangeEnd\",\n          \"@type\": \"xsd:base64Binary\"\n        }\n     \
  \ }\n    },\n\n    \"Role\": {\n      \"@id\": \"etcd:Role\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"keyPermission\": {\n          \"@id\": \"etcd:keyPermission\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"etcd:User\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"roles\": {\n          \"@id\": \"etcd:role\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Alarm\": {\n      \"@id\": \"etcd:Alarm\",\n      \"@context\": {\n        \"memberID\": {\n          \"@id\": \"etcd:memberID\"\n        },\n        \"alarm\": {\n          \"@id\": \"etcd:alarmType\"\n        }\n      }\n    },\n\n    \"ResponseHeader\": {\n      \"@id\": \"etcd:ResponseHeader\",\n      \"@context\": {\n        \"cluster_id\": {\n          \"@id\": \"etcd:clusterID\"\n        },\n        \"member_id\": {\n       \
  \   \"@id\": \"etcd:memberID\"\n        },\n        \"revision\": {\n          \"@id\": \"etcd:revision\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"raft_term\": {\n          \"@id\": \"etcd:raftTerm\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/etcd/refs/heads/main/json-ld/etcd-context.jsonld
tags:
- Cloud Native
- Consensus
- Distributed Systems
- Graduated
- Key-Value Store
- Kubernetes
- JSON-LD
- Linked Data
- Semantic Web
---
