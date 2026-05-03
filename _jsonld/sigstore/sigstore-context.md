---
api_specs:
- filename: rekor-openapi.yaml
  format: yaml
  label: Rekor Transparency Log API
  slug: rekor
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sigstore/refs/heads/main/openapi/rekor-openapi.yaml
- filename: fulcio-openapi.json
  format: json
  label: Fulcio Certificate Authority API
  slug: fulcio
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sigstore/refs/heads/main/openapi/fulcio-openapi.json
class_count: 30
classes:
- LogEntry
- TrustBundle
- Certificate
- PublicKey
- InclusionProof
- SignedEntryTimestamp
- TransparencyLog
- CertificateAuthority
- uuid
- body
- logID
- logIndex
- verification
- inclusionProof
- signedEntryTimestamp
- checkpoint
- hashes
- rootHash
- treeSize
- certificates
- algorithm
- key
- issuer
- artifactHash
- artifactType
- signature
- publicKey
- oidcIssuer
- subjectAlternativeName
- host
context_file: json-ld/sigstore-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sigstore/refs/heads/main/json-ld/sigstore-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sigstore from Sigstore.
layout: jsonld
name: Sigstore Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sigstore
  uri: https://sigstore.dev/vocab/
- prefix: sec
  uri: https://w3id.org/security#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: integratedTime
  type: integer
- container: ''
  name: timestamp
  type: dateTime
property_count: 2
provider_name: Sigstore
provider_slug: sigstore
slug: sigstore-context
source_filename: sigstore-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sigstore\": \"https://sigstore.dev/vocab/\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"LogEntry\": \"sigstore:LogEntry\",\n    \"TrustBundle\": \"sigstore:TrustBundle\",\n    \"Certificate\": \"sec:Certificate\",\n    \"PublicKey\": \"sec:publicKey\",\n    \"InclusionProof\": \"sigstore:InclusionProof\",\n    \"SignedEntryTimestamp\": \"sigstore:SignedEntryTimestamp\",\n    \"TransparencyLog\": \"sigstore:TransparencyLog\",\n    \"CertificateAuthority\": \"sigstore:CertificateAuthority\",\n\n    \"uuid\": \"@id\",\n    \"body\": \"sigstore:entryBody\",\n    \"integratedTime\": {\n      \"@id\": \"sigstore:integratedTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"logID\": \"sigstore:logID\",\n    \"logIndex\": \"sigstore:logIndex\",\n    \"verification\": \"sigstore:verification\",\n    \"inclusionProof\": \"\
  sigstore:inclusionProof\",\n    \"signedEntryTimestamp\": \"sigstore:signedEntryTimestamp\",\n    \"checkpoint\": \"sigstore:checkpoint\",\n    \"hashes\": \"sigstore:hashes\",\n    \"rootHash\": \"sigstore:rootHash\",\n    \"treeSize\": \"sigstore:treeSize\",\n\n    \"certificates\": \"sec:certificate\",\n    \"algorithm\": \"sec:algorithm\",\n    \"key\": \"sec:key\",\n    \"issuer\": \"schema:issuer\",\n\n    \"artifactHash\": \"sigstore:artifactHash\",\n    \"artifactType\": \"sigstore:artifactType\",\n    \"signature\": \"sec:signature\",\n    \"publicKey\": \"sec:publicKey\",\n\n    \"oidcIssuer\": \"sigstore:oidcIssuer\",\n    \"subjectAlternativeName\": \"sigstore:subjectAlternativeName\",\n\n    \"host\": \"schema:url\",\n    \"timestamp\": {\n      \"@id\": \"schema:DateTime\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sigstore/refs/heads/main/json-ld/sigstore-context.jsonld
tags:
- Certificate Authority
- Code Signing
- Containers
- Cryptography
- Open Source
- PKI
- Security
- Software Supply Chain
- Transparency Log
- JSON-LD
- Linked Data
- Semantic Web
---
