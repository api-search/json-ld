---
api_specs:
- filename: ssl-tls-certificate-management-openapi.yml
  format: yaml
  label: Let's Encrypt ACME API
  slug: lets-encrypt-acme
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/openapi/ssl-tls-certificate-management-openapi.yml
class_count: 20
classes:
- Certificate
- CertificateOrder
- Challenge
- Domain
- id
- commonName
- subjectAlternativeNames
- serialNumber
- issuer
- subject
- status
- certType
- keyAlgorithm
- pem
- chain
- fingerprint
- revocationReason
- token
- type
- domain
context_file: json-ld/ssl-tls-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/json-ld/ssl-tls-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ssl Tls from SSL/TLS.
layout: jsonld
name: Ssl Tls Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: cert
  uri: http://www.w3.org/ns/auth/cert#
- prefix: sec
  uri: https://w3id.org/security#
- prefix: tls
  uri: https://www.w3.org/ns/tls-cert/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: notBefore
  type: dateTime
- container: ''
  name: notAfter
  type: dateTime
- container: ''
  name: sha256
  type: hexBinary
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: revokedAt
  type: dateTime
- container: list
  name: domains
  type: ''
- container: list
  name: challenges
  type: ''
property_count: 7
provider_name: SSL/TLS
provider_slug: ssl-tls
slug: ssl-tls-context
source_filename: ssl-tls-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"cert\": \"http://www.w3.org/ns/auth/cert#\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"tls\": \"https://www.w3.org/ns/tls-cert/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Certificate\": \"cert:Certificate\",\n    \"CertificateOrder\": \"tls:CertificateOrder\",\n    \"Challenge\": \"tls:DomainChallenge\",\n    \"Domain\": \"schema:WebSite\",\n\n    \"id\": \"schema:identifier\",\n    \"commonName\": \"cert:subject\",\n    \"subjectAlternativeNames\": \"cert:subjectAlternativeName\",\n    \"serialNumber\": \"cert:serialNumber\",\n    \"issuer\": \"cert:issuer\",\n    \"subject\": \"cert:subject\",\n    \"notBefore\": {\n      \"@id\": \"schema:validFrom\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"notAfter\": {\n      \"@id\": \"schema:validThrough\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": \"schema:status\",\n    \"certType\"\
  : \"tls:certificateType\",\n    \"keyAlgorithm\": \"tls:keyAlgorithm\",\n    \"pem\": \"cert:pemEncoded\",\n    \"chain\": \"tls:certificateChain\",\n    \"fingerprint\": \"cert:fingerprint\",\n    \"sha256\": {\n      \"@id\": \"cert:sha256\",\n      \"@type\": \"xsd:hexBinary\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"revokedAt\": {\n      \"@id\": \"tls:revokedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"revocationReason\": \"tls:revocationReason\",\n\n    \"domains\": {\n      \"@id\": \"tls:coveredDomains\",\n      \"@container\": \"@list\"\n    },\n    \"challenges\": {\n      \"@id\": \"tls:hasChallenge\",\n      \"@container\": \"@list\"\n    },\n    \"token\": \"tls:challengeToken\",\n    \"type\": \"tls:challengeType\",\n    \"domain\": \"schema:domainIncludes\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/json-ld/ssl-tls-context.jsonld
tags:
- SSL/TLS
- TLS
- Certificates
- PKI
- Cryptography
- Certificate Authority
- HTTPS
- JSON-LD
- Linked Data
- Semantic Web
---
