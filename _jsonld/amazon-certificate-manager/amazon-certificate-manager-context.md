---
api_specs:
- filename: amazon-certificate-manager-openapi.yml
  format: yaml
  label: Amazon Certificate Manager API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-certificate-manager/refs/heads/main/openapi/amazon-certificate-manager-openapi.yml
class_count: 4
classes:
- RequestCertificateRequest
- RequestCertificateResponse
- ListCertificatesResponse
- DescribeCertificateResponse
context_file: json-ld/amazon-certificate-manager-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-certificate-manager/refs/heads/main/json-ld/amazon-certificate-manager-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Certificate Manager from Amazon Certificate Manager.
layout: jsonld
name: Amazon Certificate Manager Context
namespaces:
- prefix: acm
  uri: https://aws.amazon.com/certificate-manager/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: domainName
  type: string
- container: set
  name: subjectAlternativeNames
  type: string
- container: ''
  name: validationMethod
  type: string
- container: ''
  name: idempotencyToken
  type: string
- container: ''
  name: certificateArn
  type: string
- container: set
  name: certificateSummaryList
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: certificate
  type: string
property_count: 8
provider_name: Amazon Certificate Manager
provider_slug: amazon-certificate-manager
slug: amazon-certificate-manager-context
source_filename: amazon-certificate-manager-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"acm\": \"https://aws.amazon.com/certificate-manager/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"RequestCertificateRequest\": \"acm:RequestCertificateRequest\",\n    \"domainName\": {\n      \"@id\": \"acm:domain_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subjectAlternativeNames\": {\n      \"@id\": \"acm:subject_alternative_names\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validationMethod\": {\n      \"@id\": \"acm:validation_method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idempotencyToken\": {\n      \"@id\": \"acm:idempotency_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RequestCertificateResponse\": \"acm:RequestCertificateResponse\",\n    \"certificateArn\": {\n      \"@id\": \"acm:certificate_arn\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"ListCertificatesResponse\": \"acm:ListCertificatesResponse\",\n    \"certificateSummaryList\": {\n      \"@id\": \"acm:certificate_summary_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"acm:next_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeCertificateResponse\": \"acm:DescribeCertificateResponse\",\n    \"certificate\": {\n      \"@id\": \"acm:certificate\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-certificate-manager/refs/heads/main/json-ld/amazon-certificate-manager-context.jsonld
tags:
- Certificates
- Encryption
- Security
- SSL
- TLS
- JSON-LD
- Linked Data
- Semantic Web
---
