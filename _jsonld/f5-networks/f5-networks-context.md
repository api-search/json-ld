---
class_count: 0
classes: []
context_file: json-ld/f5-networks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/f5-networks/refs/heads/main/json-ld/f5-networks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for F5 Networks from F5 Networks.
layout: jsonld
name: F5 Networks Context
namespaces:
- prefix: f5
  uri: https://schemas.f5.com/bigip/ltm/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: network
  uri: https://schemas.f5.com/bigip/network/
properties:
- container: ''
  name: VirtualServer
  type: ''
- container: ''
  name: Pool
  type: ''
- container: ''
  name: PoolMember
  type: ''
- container: ''
  name: Node
  type: ''
- container: ''
  name: Profile
  type: ''
- container: ''
  name: NodeFqdn
  type: ''
property_count: 6
provider_name: F5 Networks
provider_slug: f5-networks
slug: f5-networks-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"f5\": \"https://schemas.f5.com/bigip/ltm/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"network\": \"https://schemas.f5.com/bigip/network/\",\n\n    \"VirtualServer\": {\n      \"@id\": \"f5:VirtualServer\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fullPath\": {\n          \"@id\": \"f5:fullPath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"destination\": {\n          \"@id\": \"f5:destination\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ipProtocol\": {\n          \"@id\": \"f5:ipProtocol\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"mask\": {\n          \"@id\": \"f5:networkMask\",\n          \"@type\": \"xsd:string\"\n        },\n        \"source\": {\n          \"@id\": \"f5:sourceFilter\",\n          \"@type\": \"xsd:string\"\n        },\n        \"partition\": {\n          \"@id\": \"f5:partition\",\n          \"@type\": \"xsd:string\"\n        },\n        \"pool\": {\n          \"@id\": \"f5:assignedPool\",\n          \"@type\": \"@id\"\n        },\n        \"enabled\": {\n          \"@id\": \"f5:enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"disabled\": {\n          \"@id\": \"f5:disabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"connectionLimit\": {\n          \"@id\": \"f5:connectionLimit\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"translateAddress\": {\n          \"@id\": \"f5:translateAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"translatePort\": {\n          \"@id\": \"f5:translatePort\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"sourcePort\": {\n          \"@id\": \"f5:sourcePort\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mirror\": {\n          \"@id\": \"f5:mirrorEnabled\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rateLimit\": {\n          \"@id\": \"f5:rateLimit\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rateLimitMode\": {\n          \"@id\": \"f5:rateLimitMode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"addressStatus\": {\n          \"@id\": \"f5:addressStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"autoLasthop\": {\n          \"@id\": \"f5:autoLasthop\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cmpEnabled\": {\n          \"@id\": \"f5:cmpEnabled\",\n          \"@type\": \"xsd:string\"\n        },\n        \"nat64\": {\n          \"@id\": \"f5:nat64\",\n          \"@type\": \"xsd:string\"\n        },\n        \"gtmScore\": {\n \
  \         \"@id\": \"f5:gtmScore\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"fallbackPersistence\": {\n          \"@id\": \"f5:fallbackPersistence\",\n          \"@type\": \"xsd:string\"\n        },\n        \"profiles\": {\n          \"@id\": \"f5:hasProfile\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"persist\": {\n          \"@id\": \"f5:hasPersistence\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"rules\": {\n          \"@id\": \"f5:hasRule\",\n          \"@container\": \"@set\"\n        },\n        \"vlans\": {\n          \"@id\": \"f5:onVlan\",\n          \"@container\": \"@set\"\n        },\n        \"vlansEnabled\": {\n          \"@id\": \"f5:vlansEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"vlansDisabled\": {\n          \"@id\": \"f5:vlansDisabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"selfLink\": {\n          \"\
  @id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"kind\": {\n          \"@id\": \"f5:resourceKind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"generation\": {\n          \"@id\": \"f5:generation\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Pool\": {\n      \"@id\": \"f5:Pool\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fullPath\": {\n          \"@id\": \"f5:fullPath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"partition\": {\n          \"@id\": \"f5:partition\",\n          \"@type\": \"xsd:string\"\n        },\n        \"loadBalancingMode\": {\n          \"@id\": \"f5:loadBalancingMode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"monitor\": {\n          \"@id\"\
  : \"f5:healthMonitor\",\n          \"@type\": \"xsd:string\"\n        },\n        \"allowNat\": {\n          \"@id\": \"f5:allowNat\",\n          \"@type\": \"xsd:string\"\n        },\n        \"allowSnat\": {\n          \"@id\": \"f5:allowSnat\",\n          \"@type\": \"xsd:string\"\n        },\n        \"minActiveMembers\": {\n          \"@id\": \"f5:minActiveMembers\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"minUpMembers\": {\n          \"@id\": \"f5:minUpMembers\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"minUpMembersAction\": {\n          \"@id\": \"f5:minUpMembersAction\",\n          \"@type\": \"xsd:string\"\n        },\n        \"minUpMembersChecking\": {\n          \"@id\": \"f5:minUpMembersChecking\",\n          \"@type\": \"xsd:string\"\n        },\n        \"slowRampTime\": {\n          \"@id\": \"f5:slowRampTime\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"reselectTries\": {\n          \"@id\": \"f5:reselectTries\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"serviceDownAction\": {\n          \"@id\": \"f5:serviceDownAction\",\n          \"@type\": \"xsd:string\"\n        },\n        \"queueDepthLimit\": {\n          \"@id\": \"f5:queueDepthLimit\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"queueOnConnectionLimit\": {\n          \"@id\": \"f5:queueOnConnectionLimit\",\n          \"@type\": \"xsd:string\"\n        },\n        \"queueTimeLimit\": {\n          \"@id\": \"f5:queueTimeLimit\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"members\": {\n          \"@id\": \"f5:hasMember\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"selfLink\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"kind\": {\n          \"@id\": \"f5:resourceKind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"generation\": {\n          \"@id\": \"f5:generation\",\n       \
  \   \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"PoolMember\": {\n      \"@id\": \"f5:PoolMember\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fullPath\": {\n          \"@id\": \"f5:fullPath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address\": {\n          \"@id\": \"network:ipAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"partition\": {\n          \"@id\": \"f5:partition\",\n          \"@type\": \"xsd:string\"\n        },\n        \"connectionLimit\": {\n          \"@id\": \"f5:connectionLimit\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"dynamicRatio\": {\n          \"@id\": \"f5:dynamicRatio\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"monitor\": {\n          \"@id\":\
  \ \"f5:healthMonitor\",\n          \"@type\": \"xsd:string\"\n        },\n        \"priorityGroup\": {\n          \"@id\": \"f5:priorityGroup\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"rateLimit\": {\n          \"@id\": \"f5:rateLimit\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ratio\": {\n          \"@id\": \"f5:ratio\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"session\": {\n          \"@id\": \"f5:sessionState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"f5:operationalState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"inheritProfile\": {\n          \"@id\": \"f5:inheritProfile\",\n          \"@type\": \"xsd:string\"\n        },\n        \"logging\": {\n          \"@id\": \"f5:loggingEnabled\",\n          \"@type\": \"xsd:string\"\n        },\n        \"selfLink\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"kind\"\
  : {\n          \"@id\": \"f5:resourceKind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"generation\": {\n          \"@id\": \"f5:generation\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Node\": {\n      \"@id\": \"f5:Node\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fullPath\": {\n          \"@id\": \"f5:fullPath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address\": {\n          \"@id\": \"network:ipAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"partition\": {\n          \"@id\": \"f5:partition\",\n          \"@type\": \"xsd:string\"\n        },\n        \"connectionLimit\": {\n          \"@id\": \"f5:connectionLimit\",\n          \"@type\": \"xsd:integer\"\n        },\n       \
  \ \"dynamicRatio\": {\n          \"@id\": \"f5:dynamicRatio\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"monitor\": {\n          \"@id\": \"f5:healthMonitor\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rateLimit\": {\n          \"@id\": \"f5:rateLimit\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ratio\": {\n          \"@id\": \"f5:ratio\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"session\": {\n          \"@id\": \"f5:sessionState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"f5:operationalState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"logging\": {\n          \"@id\": \"f5:loggingEnabled\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fqdn\": {\n          \"@id\": \"f5:fqdnConfig\",\n          \"@type\": \"@id\"\n        },\n        \"selfLink\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n\
  \        \"kind\": {\n          \"@id\": \"f5:resourceKind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"generation\": {\n          \"@id\": \"f5:generation\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Profile\": {\n      \"@id\": \"f5:Profile\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fullPath\": {\n          \"@id\": \"f5:fullPath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": {\n          \"@id\": \"f5:profileContext\",\n          \"@type\": \"xsd:string\"\n        },\n        \"defaultsFrom\": {\n          \"@id\": \"f5:inheritsFrom\",\n          \"@type\": \"@id\"\n        },\n        \"partition\": {\n          \"@id\": \"f5:partition\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"selfLink\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"kind\": {\n          \"@id\": \"f5:resourceKind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"generation\": {\n          \"@id\": \"f5:generation\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"NodeFqdn\": {\n      \"@id\": \"f5:NodeFqdn\",\n      \"@context\": {\n        \"addressFamily\": {\n          \"@id\": \"f5:addressFamily\",\n          \"@type\": \"xsd:string\"\n        },\n        \"autopopulate\": {\n          \"@id\": \"f5:autopopulate\",\n          \"@type\": \"xsd:string\"\n        },\n        \"downInterval\": {\n          \"@id\": \"f5:downInterval\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"interval\": {\n          \"@id\": \"f5:queryInterval\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tmName\": {\n          \"@id\": \"f5:fqdnName\",\n          \"@type\": \"xsd:string\"\n\
  \        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/f5-networks/refs/heads/main/json-ld/f5-networks-context.jsonld
tags:
- API Gateway
- Application Delivery
- Automation
- Edge Computing
- Kubernetes
- Load Balancing
- Multi-Cloud
- NGINX
- Security
- WAF
- JSON-LD
- Linked Data
- Semantic Web
---
