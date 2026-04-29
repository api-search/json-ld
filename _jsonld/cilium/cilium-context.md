---
api_specs:
- filename: cilium-api-openapi.yml
  format: yaml
  label: Cilium API
  slug: cilium-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cilium/refs/heads/main/openapi/cilium-api-openapi.yml
- filename: cilium-hubble-asyncapi.yml
  format: yaml
  label: Hubble API
  slug: hubble-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/cilium/refs/heads/main/asyncapi/cilium-hubble-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/cilium-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cilium/refs/heads/main/json-ld/cilium-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cilium from Cilium.
layout: jsonld
name: Cilium Context
namespaces:
- prefix: cilium
  uri: https://cilium.io/ontology/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: k8s
  uri: https://kubernetes.io/ontology/
properties:
- container: ''
  name: Endpoint
  type: ''
- container: ''
  name: Identity
  type: ''
- container: ''
  name: NetworkPolicy
  type: ''
- container: ''
  name: PolicyRule
  type: ''
- container: ''
  name: Service
  type: ''
- container: ''
  name: FrontendAddress
  type: ''
- container: ''
  name: BackendAddress
  type: ''
- container: ''
  name: NetworkFlow
  type: ''
- container: ''
  name: ClusterNode
  type: ''
- container: ''
  name: BgpPeer
  type: ''
- container: ''
  name: DNSLookup
  type: ''
property_count: 11
provider_name: Cilium
provider_slug: cilium
slug: cilium-context
source_filename: cilium-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cilium\": \"https://cilium.io/ontology/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"k8s\": \"https://kubernetes.io/ontology/\",\n\n    \"Endpoint\": {\n      \"@id\": \"cilium:Endpoint\",\n      \"@context\": {\n        \"id\": \"cilium:endpointId\",\n        \"containerID\": \"cilium:containerID\",\n        \"containerName\": \"schema:name\",\n        \"k8sNamespace\": \"k8s:namespace\",\n        \"k8sPodName\": \"k8s:podName\",\n        \"k8sUID\": \"k8s:uid\",\n        \"state\": \"cilium:endpointState\",\n        \"labels\": {\n          \"@id\": \"cilium:label\",\n          \"@container\": \"@set\"\n        },\n        \"identity\": {\n          \"@id\": \"cilium:hasIdentity\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"\
  xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Identity\": {\n      \"@id\": \"cilium:Identity\",\n      \"@context\": {\n        \"id\": \"cilium:identityId\",\n        \"labels\": {\n          \"@id\": \"cilium:label\",\n          \"@container\": \"@set\"\n        },\n        \"labelsSHA256\": \"cilium:labelsSHA256\"\n      }\n    },\n\n    \"NetworkPolicy\": {\n      \"@id\": \"cilium:NetworkPolicy\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"revision\": \"cilium:policyRevision\",\n        \"rules\": {\n          \"@id\": \"cilium:hasRule\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"PolicyRule\": {\n      \"@id\": \"cilium:PolicyRule\",\n      \"@context\": {\n        \"labels\": {\n          \"@id\": \"cilium:label\",\n          \"@container\": \"@set\"\n        },\n        \"endpointSelector\": \"cilium:endpointSelector\",\n        \"ingress\": {\n          \"@id\": \"cilium:ingressRule\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"egress\": {\n          \"@id\": \"cilium:egressRule\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Service\": {\n      \"@id\": \"cilium:Service\",\n      \"@context\": {\n        \"id\": \"cilium:serviceId\",\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"frontendAddress\": {\n          \"@id\": \"cilium:frontendAddress\",\n          \"@type\": \"@id\"\n        },\n        \"backendAddresses\": {\n          \"@id\": \"cilium:backendAddress\",\n          \"@container\": \"@set\"\n        },\n        \"type\": \"cilium:serviceType\",\n        \"trafficPolicy\": \"cilium:trafficPolicy\"\n      }\n    },\n\n    \"FrontendAddress\": {\n      \"@id\": \"cilium:FrontendAddress\",\n      \"@context\": {\n        \"ip\": \"schema:ipAddressOrRange\",\n        \"port\": \"schema:portNumber\",\n        \"protocol\": \"cilium:protocol\",\n        \"scope\": \"cilium:addressScope\"\
  \n      }\n    },\n\n    \"BackendAddress\": {\n      \"@id\": \"cilium:BackendAddress\",\n      \"@context\": {\n        \"ip\": \"schema:ipAddressOrRange\",\n        \"port\": \"schema:portNumber\",\n        \"nodeName\": \"k8s:nodeName\",\n        \"state\": \"cilium:backendState\",\n        \"weight\": \"cilium:loadBalancerWeight\"\n      }\n    },\n\n    \"NetworkFlow\": {\n      \"@id\": \"cilium:NetworkFlow\",\n      \"@context\": {\n        \"time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"verdict\": \"cilium:policyVerdict\",\n        \"source\": {\n          \"@id\": \"cilium:sourceEndpoint\",\n          \"@type\": \"@id\"\n        },\n        \"destination\": {\n          \"@id\": \"cilium:destinationEndpoint\",\n          \"@type\": \"@id\"\n        },\n        \"nodeName\": \"k8s:nodeName\",\n        \"trafficDirection\": \"cilium:trafficDirection\",\n        \"sourceService\": {\n          \"@id\": \"cilium:sourceService\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"destinationService\": {\n          \"@id\": \"cilium:destinationService\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ClusterNode\": {\n      \"@id\": \"cilium:ClusterNode\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"primaryAddress\": {\n          \"@id\": \"cilium:primaryAddress\",\n          \"@type\": \"@id\"\n        },\n        \"allocationCIDR\": \"cilium:allocationCIDR\",\n        \"encryptionKey\": \"cilium:encryptionKey\"\n      }\n    },\n\n    \"BgpPeer\": {\n      \"@id\": \"cilium:BgpPeer\",\n      \"@context\": {\n        \"peerAddress\": {\n          \"@id\": \"schema:ipAddressOrRange\"\n        },\n        \"peerASN\": \"cilium:peerASN\",\n        \"localASN\": \"cilium:localASN\",\n        \"sessionState\": \"cilium:bgpSessionState\"\n      }\n    },\n\n    \"DNSLookup\": {\n      \"@id\": \"cilium:DNSLookup\",\n      \"@context\": {\n        \"fqdn\": \"cilium:fullyQualifiedDomainName\"\
  ,\n        \"ips\": {\n          \"@id\": \"cilium:resolvedIP\",\n          \"@container\": \"@set\"\n        },\n        \"lookupTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expirationTime\": {\n          \"@id\": \"dcterms:valid\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"ttl\": \"cilium:dnsTTL\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cilium/refs/heads/main/json-ld/cilium-context.jsonld
tags:
- Cloud Native
- eBPF
- Kubernetes
- Networking
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
