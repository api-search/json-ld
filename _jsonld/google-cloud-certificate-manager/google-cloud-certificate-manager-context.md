---
api_specs:
- filename: certificate-manager-api-openapi.yml
  format: yaml
  label: Certificate Manager API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-certificate-manager/refs/heads/main/openapi/certificate-manager-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-cloud-certificate-manager-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-certificate-manager/refs/heads/main/json-ld/google-cloud-certificate-manager-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Certificate Manager from Google Cloud Certificate Manager.
layout: jsonld
name: Google Cloud Certificate Manager Context
namespaces:
- prefix: cm
  uri: https://cloud.google.com/certificate-manager/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Certificate
  type: ''
- container: ''
  name: CertificateMap
  type: ''
- container: ''
  name: DnsAuthorization
  type: ''
property_count: 3
provider_name: Google Cloud Certificate Manager
provider_slug: google-cloud-certificate-manager
slug: google-cloud-certificate-manager-context
source_filename: google-cloud-certificate-manager-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cm\": \"https://cloud.google.com/certificate-manager/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Certificate\": {\n      \"@id\": \"cm:Certificate\",\n      \"@context\": {\n        \"name\": \"cm:certificateName\",\n        \"description\": \"schema:description\",\n        \"sanDnsnames\": \"cm:sanDnsnames\",\n        \"pemCertificate\": \"cm:pemCertificate\",\n        \"scope\": \"cm:scope\",\n        \"managed\": \"cm:managedConfig\",\n        \"selfManaged\": \"cm:selfManagedConfig\",\n        \"expireTime\": {\n          \"@id\": \"cm:expireTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        },\n        \"labels\": \"cm:labels\"\n      }\n    },\n\n    \"CertificateMap\": {\n      \"@id\": \"cm:CertificateMap\",\n      \"@context\": {\n        \"name\": \"cm:mapName\",\n        \"description\": \"schema:description\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"labels\": \"cm:labels\"\n      }\n    },\n\n    \"DnsAuthorization\": {\n      \"@id\": \"cm:DnsAuthorization\",\n      \"@context\": {\n        \"name\": \"cm:authorizationName\",\n        \"description\": \"schema:description\",\n        \"domain\": \"cm:domain\",\n        \"dnsResourceRecord\": \"cm:dnsResourceRecord\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-certificate-manager/refs/heads/main/json-ld/google-cloud-certificate-manager-context.jsonld
tags:
- Certificate Management
- Certificates
- Load Balancing
- Security
- SSL
- TLS
- JSON-LD
- Linked Data
- Semantic Web
---
