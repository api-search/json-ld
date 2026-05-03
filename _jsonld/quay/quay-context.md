---
api_specs:
- filename: quay-openapi.yml
  format: yaml
  label: Quay
  slug: quay
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/quay/refs/heads/main/openapi/quay-openapi.yml
class_count: 5
classes:
- name
- description
- url
- provider
- category
context_file: json-ld/quay-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/quay/refs/heads/main/json-ld/quay-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Quay from Quay.
layout: jsonld
name: Quay Context
namespaces: []
properties:
- container: ''
  name: documentation
  type: reference
- container: ''
  name: termsOfService
  type: reference
property_count: 2
provider_name: Quay
provider_slug: quay
slug: quay-context
source_filename: quay-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"url\": \"url\",\n    \"provider\": \"provider\",\n    \"category\": \"category\",\n    \"documentation\": {\n      \"@id\": \"https://schema.org/documentation\",\n      \"@type\": \"@id\"\n    },\n    \"termsOfService\": {\n      \"@id\": \"https://schema.org/termsOfService\",\n      \"@type\": \"@id\"\n    }\n  },\n  \"@type\": \"WebAPI\",\n  \"name\": \"Quay Container Registry API\",\n  \"description\": \"Quay is a container image registry that enables you to build, store, distribute, and deploy container images with built-in security scanning, access controls, and automated build triggers.\",\n  \"url\": \"https://quay.io/api/v1\",\n  \"documentation\": \"https://docs.quay.io/api/\",\n  \"termsOfService\": \"https://quay.io/tos\",\n  \"provider\": {\n    \"@type\": \"Organization\",\n    \"name\": \"Red Hat\",\n    \"url\": \"https://www.redhat.com/\"\
  \n  },\n  \"category\": [\n    \"Container Images\",\n    \"Container Registry\",\n    \"Security Scanning\",\n    \"DevOps\"\n  ],\n  \"audience\": {\n    \"@type\": \"Audience\",\n    \"audienceType\": \"Developers, DevOps Engineers, Platform Engineers\"\n  },\n  \"potentialAction\": [\n    {\n      \"@type\": \"ConsumeAction\",\n      \"name\": \"List Repositories\",\n      \"target\": \"https://quay.io/api/v1/repository\"\n    },\n    {\n      \"@type\": \"ConsumeAction\",\n      \"name\": \"Get Manifest Security\",\n      \"target\": \"https://quay.io/api/v1/repository/{repository}/manifest/{manifestref}/security\"\n    }\n  ]\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/quay/refs/heads/main/json-ld/quay-context.jsonld
tags:
- Container Images
- Containers
- Red Hat
- Registry
- Security Scanning
- JSON-LD
- Linked Data
- Semantic Web
---
