---
api_specs:
- filename: binary-authorization-api-openapi.yml
  format: yaml
  label: Binary Authorization API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-binary-authorization/refs/heads/main/openapi/binary-authorization-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-cloud-binary-authorization-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-binary-authorization/refs/heads/main/json-ld/google-cloud-binary-authorization-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Binary Authorization from Google Cloud Binary Authorization.
layout: jsonld
name: Google Cloud Binary Authorization Context
namespaces:
- prefix: binauth
  uri: https://cloud.google.com/binary-authorization/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Policy
  type: ''
- container: ''
  name: Attestor
  type: ''
- container: ''
  name: AdmissionRule
  type: ''
property_count: 3
provider_name: Google Cloud Binary Authorization
provider_slug: google-cloud-binary-authorization
slug: google-cloud-binary-authorization-context
source_filename: google-cloud-binary-authorization-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"binauth\": \"https://cloud.google.com/binary-authorization/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Policy\": {\n      \"@id\": \"binauth:Policy\",\n      \"@context\": {\n        \"name\": \"binauth:policyName\",\n        \"globalPolicyEvaluationMode\": \"binauth:globalPolicyEvaluationMode\",\n        \"defaultAdmissionRule\": \"binauth:defaultAdmissionRule\",\n        \"clusterAdmissionRules\": \"binauth:clusterAdmissionRules\",\n        \"admissionWhitelistPatterns\": \"binauth:admissionWhitelistPatterns\",\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Attestor\": {\n      \"@id\": \"binauth:Attestor\",\n      \"@context\": {\n        \"name\": \"binauth:attestorName\",\n        \"description\": \"schema:description\"\
  ,\n        \"userOwnedGrafeasNote\": \"binauth:userOwnedGrafeasNote\",\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AdmissionRule\": {\n      \"@id\": \"binauth:AdmissionRule\",\n      \"@context\": {\n        \"evaluationMode\": \"binauth:evaluationMode\",\n        \"requireAttestationsBy\": \"binauth:requireAttestationsBy\",\n        \"enforcementMode\": \"binauth:enforcementMode\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-binary-authorization/refs/heads/main/json-ld/google-cloud-binary-authorization-context.jsonld
tags:
- Attestation
- Container Security
- DevSecOps
- Kubernetes
- Policy Enforcement
- Supply Chain Security
- JSON-LD
- Linked Data
- Semantic Web
---
