---
api_specs:
- filename: cisco-systems-cisco-api-openapi.yml
  format: yaml
  label: Cisco DevNet API Catalog
  slug: devnet-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cisco-systems/refs/heads/main/openapi/cisco-systems-cisco-api-openapi.yml
class_count: 13
classes:
- Organization
- Product
- API
- Domain
- Region
- Customer
- Partner
- name
- description
- category
- version
- createdAt
- updatedAt
context_file: json-ld/cisco-systems-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cisco-systems/refs/heads/main/json-ld/cisco-systems-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cisco Systems from Cisco Systems.
layout: jsonld
name: Cisco Systems Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: cisco
  uri: https://developer.cisco.com/vocab/
properties: []
property_count: 0
provider_name: Cisco Systems
provider_slug: cisco-systems
slug: cisco-systems-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://apievangelist.com/vocab/cisco-systems/\",\n    \"schema\": \"https://schema.org/\",\n    \"cisco\": \"https://developer.cisco.com/vocab/\",\n    \"Organization\": \"schema:Organization\",\n    \"Product\": \"schema:SoftwareApplication\",\n    \"API\": \"schema:WebAPI\",\n    \"Domain\": \"cisco:ProductDomain\",\n    \"Region\": \"schema:Place\",\n    \"Customer\": \"schema:Organization\",\n    \"Partner\": \"schema:Organization\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"category\": \"schema:category\",\n    \"version\": \"schema:softwareVersion\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cisco-systems/refs/heads/main/json-ld/cisco-systems-context.jsonld
tags:
- Collaboration
- Infrastructure
- Networking
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
