---
api_specs:
- filename: spire-workload-asyncapi.yml
  format: yaml
  label: SPIRE Workload API
  slug: spire-workload-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/spire/refs/heads/main/asyncapi/spire-workload-asyncapi.yml
- filename: spire-health-openapi.yml
  format: yaml
  label: SPIRE Agent API
  slug: spire-agent-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spire/refs/heads/main/openapi/spire-health-openapi.yml
- filename: spire-oidc-discovery-openapi.yml
  format: yaml
  label: SPIRE OIDC Discovery API
  slug: spire-oidc-discovery-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spire/refs/heads/main/openapi/spire-oidc-discovery-openapi.yml
class_count: 0
classes: []
context_file: json-ld/spire-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spire/refs/heads/main/json-ld/spire-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spire from SPIRE.
layout: jsonld
name: Spire Context
namespaces:
- prefix: spire
  uri: https://spiffe.io/schemas/spire/
- prefix: spiffe
  uri: https://spiffe.io/schemas/spiffe/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: sec
  uri: https://w3id.org/security#
properties:
- container: ''
  name: SVID
  type: ''
- container: ''
  name: X509SVID
  type: ''
- container: ''
  name: JWTSVID
  type: ''
- container: ''
  name: RegistrationEntry
  type: ''
- container: ''
  name: Selector
  type: ''
- container: ''
  name: Bundle
  type: ''
- container: ''
  name: Agent
  type: ''
- container: ''
  name: SPIFFEID
  type: ''
- container: ''
  name: OpenIDConfiguration
  type: ''
property_count: 9
provider_name: SPIRE
provider_slug: spire
slug: spire-context
source_filename: spire-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"spire\": \"https://spiffe.io/schemas/spire/\",\n    \"spiffe\": \"https://spiffe.io/schemas/spiffe/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"sec\": \"https://w3id.org/security#\",\n\n    \"SVID\": {\n      \"@id\": \"spire:SVID\",\n      \"@context\": {\n        \"type\": \"spire:svidType\",\n        \"spiffe_id\": {\n          \"@id\": \"spiffe:id\",\n          \"@type\": \"@id\"\n        },\n        \"hint\": \"spire:hint\",\n        \"x509_svid\": \"spire:x509SVID\",\n        \"jwt_svid\": \"spire:jwtSVID\"\n      }\n    },\n\n    \"X509SVID\": {\n      \"@id\": \"spire:X509SVID\",\n      \"@context\": {\n        \"cert_chain\": \"sec:certificate\",\n        \"private_key\": \"sec:privateKey\",\n        \"expiry_time\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:integer\"\n        }\n\
  \      }\n    },\n\n    \"JWTSVID\": {\n      \"@id\": \"spire:JWTSVID\",\n      \"@context\": {\n        \"token\": \"sec:token\",\n        \"expiry_time\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"issued_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"RegistrationEntry\": {\n      \"@id\": \"spire:RegistrationEntry\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"spiffe_id\": {\n          \"@id\": \"spiffe:id\",\n          \"@type\": \"@id\"\n        },\n        \"parent_id\": {\n          \"@id\": \"spire:parentId\",\n          \"@type\": \"@id\"\n        },\n        \"selectors\": {\n          \"@id\": \"spire:selectors\",\n          \"@container\": \"@set\"\n        },\n        \"ttl\": \"spire:ttl\",\n        \"dns_names\": {\n          \"@id\": \"schema:name\",\n          \"@container\": \"@set\"\n        },\n        \"downstream\"\
  : \"spire:downstream\",\n        \"expires_at\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"federation_with\": {\n          \"@id\": \"spire:federatesWith\",\n          \"@container\": \"@set\"\n        },\n        \"admin\": \"spire:admin\",\n        \"store_svid\": \"spire:storeSvid\",\n        \"hint\": \"spire:hint\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"revision_number\": \"spire:revisionNumber\"\n      }\n    },\n\n    \"Selector\": {\n      \"@id\": \"spire:Selector\",\n      \"@context\": {\n        \"type\": \"spire:selectorType\",\n        \"value\": \"schema:value\"\n      }\n    },\n\n    \"Bundle\": {\n      \"@id\": \"spire:Bundle\",\n      \"@context\": {\n        \"trust_domain\": \"spire:trustDomain\",\n        \"x509_authorities\": {\n          \"@id\": \"sec:x509Certificate\",\n          \"@container\": \"@set\"\n   \
  \     },\n        \"jwt_authorities\": {\n          \"@id\": \"sec:publicKey\",\n          \"@container\": \"@set\"\n        },\n        \"refresh_hint\": \"spire:refreshHint\",\n        \"sequence_number\": \"spire:sequenceNumber\"\n      }\n    },\n\n    \"Agent\": {\n      \"@id\": \"spire:Agent\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"spiffe:id\",\n          \"@type\": \"@id\"\n        },\n        \"attestation_type\": \"spire:attestationType\",\n        \"x509svid_expires_at\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"x509svid_serial_number\": \"schema:serialNumber\",\n        \"banned\": \"spire:banned\",\n        \"selectors\": {\n          \"@id\": \"spire:selectors\",\n          \"@container\": \"@set\"\n        },\n        \"can_reattest\": \"spire:canReattest\"\n      }\n    },\n\n    \"SPIFFEID\": {\n      \"@id\": \"spiffe:ID\",\n      \"@context\": {\n        \"trust_domain\": \"spiffe:trustDomain\"\
  ,\n        \"path\": \"spiffe:path\"\n      }\n    },\n\n    \"OpenIDConfiguration\": {\n      \"@id\": \"spire:OIDCConfiguration\",\n      \"@context\": {\n        \"issuer\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"jwks_uri\": {\n          \"@id\": \"spire:jwksUri\",\n          \"@type\": \"@id\"\n        },\n        \"authorization_endpoint\": {\n          \"@id\": \"spire:authorizationEndpoint\",\n          \"@type\": \"@id\"\n        },\n        \"response_types_supported\": {\n          \"@id\": \"spire:responseTypesSupported\",\n          \"@container\": \"@set\"\n        },\n        \"subject_types_supported\": {\n          \"@id\": \"spire:subjectTypesSupported\",\n          \"@container\": \"@set\"\n        },\n        \"id_token_signing_alg_values_supported\": {\n          \"@id\": \"spire:idTokenSigningAlgValuesSupported\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spire/refs/heads/main/json-ld/spire-context.jsonld
tags:
- Authentication
- Cloud Native
- Graduated
- Identity
- Security
- Zero Trust
- JSON-LD
- Linked Data
- Semantic Web
---
