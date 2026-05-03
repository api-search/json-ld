---
api_specs:
- filename: ngrok-api-openapi.yml
  format: yaml
  label: ngrok API
  slug: ngrok
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ngrok/refs/heads/main/openapi/ngrok-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/ngrok-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ngrok/refs/heads/main/json-ld/ngrok-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ngrok from ngrok.
layout: jsonld
name: Ngrok Context
namespaces:
- prefix: ngrok
  uri: https://ngrok.com/docs/api/resources/
properties:
- container: ''
  name: Tunnel
  type: ''
- container: ''
  name: Endpoint
  type: ''
- container: ''
  name: HttpsEdge
  type: ''
- container: ''
  name: TcpEdge
  type: ''
- container: ''
  name: TlsEdge
  type: ''
- container: ''
  name: ReservedDomain
  type: ''
- container: ''
  name: ReservedAddr
  type: ''
- container: ''
  name: ApiKey
  type: ''
- container: ''
  name: IpPolicy
  type: ''
- container: ''
  name: TlsCertificate
  type: ''
- container: ''
  name: EventSubscription
  type: ''
- container: ''
  name: TunnelSession
  type: ''
property_count: 12
provider_name: ngrok
provider_slug: ngrok
slug: ngrok-context
source_filename: ngrok-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"ngrok\": \"https://ngrok.com/docs/api/resources/\",\n    \"Tunnel\": {\n      \"@id\": \"ngrok:tunnels\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"public_url\": \"https://schema.org/url\",\n        \"started_at\": \"https://schema.org/dateCreated\",\n        \"metadata\": \"https://schema.org/additionalProperty\",\n        \"proto\": \"https://schema.org/encodingFormat\",\n        \"region\": \"https://schema.org/locationCreated\",\n        \"tunnel_session\": {\n          \"@id\": \"ngrok:tunnel-sessions\",\n          \"@type\": \"@id\"\n        },\n        \"endpoint\": {\n          \"@id\": \"ngrok:endpoints\",\n          \"@type\": \"@id\"\n        },\n        \"labels\": \"https://schema.org/keywords\",\n        \"forwards_to\": \"https://schema.org/url\"\n      }\n    },\n    \"Endpoint\": {\n      \"@id\": \"ngrok:endpoints\",\n      \"@context\": {\n  \
  \      \"id\": \"https://schema.org/identifier\",\n        \"public_url\": \"https://schema.org/url\",\n        \"proto\": \"https://schema.org/encodingFormat\",\n        \"type\": \"https://schema.org/category\",\n        \"description\": \"https://schema.org/description\",\n        \"metadata\": \"https://schema.org/additionalProperty\",\n        \"region\": \"https://schema.org/locationCreated\",\n        \"domain\": {\n          \"@id\": \"ngrok:reserved-domains\",\n          \"@type\": \"@id\"\n        },\n        \"tcp_addr\": {\n          \"@id\": \"ngrok:reserved-addrs\",\n          \"@type\": \"@id\"\n        },\n        \"tunnel\": {\n          \"@id\": \"ngrok:tunnels\",\n          \"@type\": \"@id\"\n        },\n        \"edge\": {\n          \"@id\": \"ngrok:edges-https\",\n          \"@type\": \"@id\"\n        },\n        \"traffic_policy\": \"https://schema.org/conditionsOfAccess\"\n      }\n    },\n    \"HttpsEdge\": {\n      \"@id\": \"ngrok:edges-https\",\n      \"@context\"\
  : {\n        \"id\": \"https://schema.org/identifier\",\n        \"description\": \"https://schema.org/description\",\n        \"metadata\": \"https://schema.org/additionalProperty\",\n        \"created_at\": \"https://schema.org/dateCreated\",\n        \"hostports\": \"https://schema.org/url\",\n        \"routes\": \"https://schema.org/hasPart\"\n      }\n    },\n    \"TcpEdge\": {\n      \"@id\": \"ngrok:edges-tcp\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"description\": \"https://schema.org/description\",\n        \"metadata\": \"https://schema.org/additionalProperty\",\n        \"created_at\": \"https://schema.org/dateCreated\",\n        \"hostports\": \"https://schema.org/url\",\n        \"backend\": \"https://schema.org/hasPart\",\n        \"ip_restriction\": \"https://schema.org/conditionsOfAccess\"\n      }\n    },\n    \"TlsEdge\": {\n      \"@id\": \"ngrok:edges-tls\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\"\
  ,\n        \"description\": \"https://schema.org/description\",\n        \"metadata\": \"https://schema.org/additionalProperty\",\n        \"created_at\": \"https://schema.org/dateCreated\",\n        \"hostports\": \"https://schema.org/url\",\n        \"backend\": \"https://schema.org/hasPart\",\n        \"ip_restriction\": \"https://schema.org/conditionsOfAccess\",\n        \"mutual_tls\": \"https://schema.org/conditionsOfAccess\",\n        \"tls_termination\": \"https://schema.org/actionOption\"\n      }\n    },\n    \"ReservedDomain\": {\n      \"@id\": \"ngrok:reserved-domains\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"domain\": \"https://schema.org/url\",\n        \"description\": \"https://schema.org/description\",\n        \"metadata\": \"https://schema.org/additionalProperty\",\n        \"region\": \"https://schema.org/locationCreated\",\n        \"cname_target\": \"https://schema.org/url\",\n        \"certificate\": {\n          \"\
  @id\": \"ngrok:tls-certificates\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"ReservedAddr\": {\n      \"@id\": \"ngrok:reserved-addrs\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"addr\": \"https://schema.org/url\",\n        \"description\": \"https://schema.org/description\",\n        \"metadata\": \"https://schema.org/additionalProperty\",\n        \"region\": \"https://schema.org/locationCreated\"\n      }\n    },\n    \"ApiKey\": {\n      \"@id\": \"ngrok:api-keys\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"description\": \"https://schema.org/description\",\n        \"metadata\": \"https://schema.org/additionalProperty\",\n        \"token\": \"https://schema.org/accessCode\",\n        \"owner_id\": \"https://schema.org/identifier\"\n      }\n    },\n    \"IpPolicy\": {\n      \"@id\": \"ngrok:ip-policies\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\"\
  ,\n        \"description\": \"https://schema.org/description\",\n        \"metadata\": \"https://schema.org/additionalProperty\"\n      }\n    },\n    \"TlsCertificate\": {\n      \"@id\": \"ngrok:tls-certificates\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"description\": \"https://schema.org/description\",\n        \"metadata\": \"https://schema.org/additionalProperty\",\n        \"certificate_pem\": \"https://schema.org/text\",\n        \"subject_common_name\": \"https://schema.org/name\",\n        \"not_before\": \"https://schema.org/validFrom\",\n        \"not_after\": \"https://schema.org/validThrough\",\n        \"private_key_type\": \"https://schema.org/category\"\n      }\n    },\n    \"EventSubscription\": {\n      \"@id\": \"ngrok:event-subscriptions\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"description\": \"https://schema.org/description\",\n        \"metadata\": \"https://schema.org/additionalProperty\"\
  ,\n        \"sources\": \"https://schema.org/hasPart\",\n        \"destinations\": {\n          \"@id\": \"ngrok:event-destinations\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"TunnelSession\": {\n      \"@id\": \"ngrok:tunnel-sessions\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"agent_version\": \"https://schema.org/softwareVersion\",\n        \"ip\": \"https://schema.org/identifier\",\n        \"metadata\": \"https://schema.org/additionalProperty\",\n        \"os\": \"https://schema.org/operatingSystem\",\n        \"region\": \"https://schema.org/locationCreated\",\n        \"started_at\": \"https://schema.org/dateCreated\",\n        \"transport\": \"https://schema.org/encodingFormat\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ngrok/refs/heads/main/json-ld/ngrok-context.jsonld
tags:
- AI Gateway
- API Gateway
- Compute
- Developer Tools
- Gateways
- Ingress
- Platform
- Proxies
- Servers
- Tunnels
- JSON-LD
- Linked Data
- Semantic Web
---
