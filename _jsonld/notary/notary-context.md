---
class_count: 7
classes:
- Signature
- TrustPolicy
- TrustPolicyStatement
- TrustStore
- Plugin
- Artifact
- CertificateChain
context_file: json-ld/notary-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/notary/refs/heads/main/json-ld/notary-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Notary from Notary Project.
layout: jsonld
name: Notary Context
namespaces:
- prefix: notary
  uri: https://notaryproject.dev/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: sec
  uri: https://w3id.org/security#
- prefix: oci
  uri: https://opencontainers.org/schema#
- prefix: spdx
  uri: https://spdx.org/rdf/terms#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: url
  type: reference
- container: set
  name: trustPolicies
  type: ''
- container: set
  name: registryScopes
  type: ''
- container: ''
  name: signatureVerification
  type: ''
- container: set
  name: trustStores
  type: ''
- container: set
  name: trustedIdentities
  type: ''
- container: ''
  name: level
  type: string
- container: ''
  name: override
  type: ''
- container: ''
  name: keyId
  type: string
- container: ''
  name: keySpec
  type: string
- container: ''
  name: hashAlgorithm
  type: string
- container: ''
  name: signingAlgorithm
  type: string
- container: list
  name: certificateChain
  type: ''
- container: ''
  name: signature
  type: base64Binary
- container: ''
  name: payload
  type: base64Binary
- container: set
  name: capabilities
  type: ''
- container: set
  name: supportedContractVersions
  type: ''
- container: ''
  name: contractVersion
  type: string
- container: ''
  name: mediaType
  type: string
- container: ''
  name: digest
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: annotations
  type: ''
- container: ''
  name: artifactReference
  type: reference
- container: ''
  name: success
  type: boolean
- container: ''
  name: reason
  type: string
- container: ''
  name: errorCode
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: created
  type: date
- container: ''
  name: modified
  type: date
property_count: 32
provider_name: Notary Project
provider_slug: notary
slug: notary-context
source_filename: notary-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"notary\": \"https://notaryproject.dev/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"oci\": \"https://opencontainers.org/schema#\",\n    \"spdx\": \"https://spdx.org/rdf/terms#\",\n\n    \"Signature\": \"notary:Signature\",\n    \"TrustPolicy\": \"notary:TrustPolicy\",\n    \"TrustPolicyStatement\": \"notary:TrustPolicyStatement\",\n    \"TrustStore\": \"notary:TrustStore\",\n    \"Plugin\": \"notary:Plugin\",\n    \"Artifact\": \"notary:Artifact\",\n    \"CertificateChain\": \"sec:CertificateChain\",\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:softwareVersion\",\n     \
  \ \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n\n    \"trustPolicies\": {\n      \"@id\": \"notary:trustPolicies\",\n      \"@container\": \"@set\"\n    },\n    \"registryScopes\": {\n      \"@id\": \"notary:registryScopes\",\n      \"@container\": \"@set\"\n    },\n    \"signatureVerification\": {\n      \"@id\": \"notary:signatureVerification\"\n    },\n    \"trustStores\": {\n      \"@id\": \"notary:trustStores\",\n      \"@container\": \"@set\"\n    },\n    \"trustedIdentities\": {\n      \"@id\": \"notary:trustedIdentities\",\n      \"@container\": \"@set\"\n    },\n    \"level\": {\n      \"@id\": \"notary:verificationLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"override\": {\n      \"@id\": \"notary:verificationOverride\"\n    },\n\n    \"keyId\": {\n      \"@id\": \"notary:keyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keySpec\": {\n      \"@id\": \"notary:keySpec\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"hashAlgorithm\": {\n      \"@id\": \"sec:digestAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signingAlgorithm\": {\n      \"@id\": \"sec:signatureAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateChain\": {\n      \"@id\": \"sec:x509Certificate\",\n      \"@container\": \"@list\"\n    },\n    \"signature\": {\n      \"@id\": \"sec:signatureValue\",\n      \"@type\": \"xsd:base64Binary\"\n    },\n    \"payload\": {\n      \"@id\": \"notary:payload\",\n      \"@type\": \"xsd:base64Binary\"\n    },\n\n    \"capabilities\": {\n      \"@id\": \"notary:capabilities\",\n      \"@container\": \"@set\"\n    },\n    \"supportedContractVersions\": {\n      \"@id\": \"notary:supportedContractVersions\",\n      \"@container\": \"@set\"\n    },\n    \"contractVersion\": {\n      \"@id\": \"notary:contractVersion\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"mediaType\": {\n      \"@id\": \"dcterms:format\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"digest\": {\n      \"@id\": \"oci:digest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"schema:contentSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"annotations\": {\n      \"@id\": \"notary:annotations\"\n    },\n    \"artifactReference\": {\n      \"@id\": \"notary:artifactReference\",\n      \"@type\": \"@id\"\n    },\n\n    \"success\": {\n      \"@id\": \"notary:verificationSuccess\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reason\": {\n      \"@id\": \"notary:verificationReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorCode\": {\n      \"@id\": \"notary:errorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"schema:error\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"created\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:date\"\n    },\n    \"modified\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:date\"\
  \n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/notary/refs/heads/main/json-ld/notary-context.jsonld
tags:
- Cloud Native
- Container Security
- Image Signing
- Incubating
- OCI
- Verification
- JSON-LD
- Linked Data
- Semantic Web
---
