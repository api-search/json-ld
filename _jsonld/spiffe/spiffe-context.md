---
api_specs:
- filename: spiffe-workload-asyncapi.yml
  format: yaml
  label: SPIFFE Workload API
  slug: spiffe-workload-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/spiffe/refs/heads/main/asyncapi/spiffe-workload-asyncapi.yml
- filename: spiffe-federation-openapi.yml
  format: yaml
  label: SPIFFE Federation API
  slug: spiffe-federation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spiffe/refs/heads/main/openapi/spiffe-federation-openapi.yml
class_count: 0
classes: []
context_file: json-ld/spiffe-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spiffe/refs/heads/main/json-ld/spiffe-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spiffe from SPIFFE.
layout: jsonld
name: Spiffe Context
namespaces:
- prefix: spiffe
  uri: https://spiffe.io/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: security
  uri: https://w3id.org/security#
- prefix: cert
  uri: http://www.w3.org/ns/auth/cert#
properties:
- container: ''
  name: SpiffeID
  type: ''
- container: ''
  name: TrustDomain
  type: ''
- container: ''
  name: X509SVID
  type: ''
- container: ''
  name: JWTSVID
  type: ''
- container: ''
  name: JWTSVIDClaims
  type: ''
- container: ''
  name: TrustBundle
  type: ''
- container: ''
  name: JWK
  type: ''
property_count: 7
provider_name: SPIFFE
provider_slug: spiffe
slug: spiffe-context
source_filename: spiffe-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"spiffe\": \"https://spiffe.io/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"security\": \"https://w3id.org/security#\",\n    \"cert\": \"http://www.w3.org/ns/auth/cert#\",\n\n    \"SpiffeID\": {\n      \"@id\": \"spiffe:SpiffeID\",\n      \"@context\": {\n        \"trustDomain\": {\n          \"@id\": \"spiffe:trustDomain\"\n        },\n        \"path\": {\n          \"@id\": \"spiffe:path\"\n        }\n      }\n    },\n\n    \"TrustDomain\": {\n      \"@id\": \"spiffe:TrustDomain\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"bundleEndpoint\": {\n          \"@id\": \"spiffe:bundleEndpoint\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"X509SVID\": {\n      \"@id\": \"spiffe:X509SVID\",\n      \"@context\": {\n        \"spiffe_id\"\
  : {\n          \"@id\": \"spiffe:spiffeID\",\n          \"@type\": \"@id\"\n        },\n        \"x509_svid\": {\n          \"@id\": \"cert:certificate\"\n        },\n        \"bundle\": {\n          \"@id\": \"spiffe:trustBundle\"\n        },\n        \"hint\": {\n          \"@id\": \"spiffe:hint\"\n        }\n      }\n    },\n\n    \"JWTSVID\": {\n      \"@id\": \"spiffe:JWTSVID\",\n      \"@context\": {\n        \"token\": {\n          \"@id\": \"security:jws\"\n        },\n        \"spiffe_id\": {\n          \"@id\": \"spiffe:spiffeID\",\n          \"@type\": \"@id\"\n        },\n        \"expiry_time\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"JWTSVIDClaims\": {\n      \"@id\": \"spiffe:JWTSVIDClaims\",\n      \"@context\": {\n        \"sub\": {\n          \"@id\": \"spiffe:spiffeID\",\n          \"@type\": \"@id\"\n        },\n        \"aud\": {\n          \"@id\": \"spiffe:audience\",\n          \"@container\"\
  : \"@set\"\n        },\n        \"exp\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"iat\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"jti\": {\n          \"@id\": \"schema:identifier\"\n        }\n      }\n    },\n\n    \"TrustBundle\": {\n      \"@id\": \"spiffe:TrustBundle\",\n      \"@context\": {\n        \"keys\": {\n          \"@id\": \"security:publicKeyJwk\",\n          \"@container\": \"@set\"\n        },\n        \"spiffe_refresh_hint\": {\n          \"@id\": \"spiffe:refreshHint\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"spiffe_sequence\": {\n          \"@id\": \"spiffe:sequence\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"JWK\": {\n      \"@id\": \"security:JsonWebKey\",\n      \"@context\": {\n        \"kty\": {\n          \"@id\": \"security:keyType\"\n        },\n        \"use\": {\n          \"@id\"\
  : \"security:usage\"\n        },\n        \"kid\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"crv\": {\n          \"@id\": \"security:curve\"\n        },\n        \"x5c\": {\n          \"@id\": \"security:x509Certificate\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spiffe/refs/heads/main/json-ld/spiffe-context.jsonld
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
