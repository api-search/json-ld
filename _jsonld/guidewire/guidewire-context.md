---
api_specs:
- filename: guidewire-policycenter-openapi.yml
  format: yaml
  label: Guidewire PolicyCenter API
  slug: guidewire-policycenter-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/guidewire/refs/heads/main/openapi/guidewire-policycenter-openapi.yml
- filename: guidewire-claimcenter-openapi.yml
  format: yaml
  label: Guidewire ClaimCenter API
  slug: guidewire-claimcenter-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/guidewire/refs/heads/main/openapi/guidewire-claimcenter-openapi.yml
- filename: guidewire-integration-gateway-asyncapi.yml
  format: yaml
  label: Guidewire Integration Gateway API
  slug: guidewire-integration-gateway-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/guidewire/refs/heads/main/asyncapi/guidewire-integration-gateway-asyncapi.yml
class_count: 11
classes:
- id
- policyNumber
- claimNumber
- accountNumber
- status
- product
- currency
- lossType
- lossDescription
- displayName
- name
context_file: json-ld/guidewire-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/guidewire/refs/heads/main/json-ld/guidewire-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Guidewire from Guidewire.
layout: jsonld
name: Guidewire Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dct
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Policy
  type: reference
- container: ''
  name: Claim
  type: reference
- container: ''
  name: Account
  type: reference
- container: ''
  name: Coverage
  type: reference
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: expirationDate
  type: date
- container: ''
  name: issuedDate
  type: date
- container: ''
  name: totalPremium
  type: decimal
- container: ''
  name: createdDate
  type: dateTime
- container: ''
  name: updatedDate
  type: dateTime
- container: ''
  name: insured
  type: reference
- container: ''
  name: account
  type: reference
- container: set
  name: coverages
  type: reference
- container: ''
  name: lossDate
  type: date
- container: ''
  name: reportedDate
  type: dateTime
- container: ''
  name: totalIncurred
  type: decimal
- container: ''
  name: totalPaid
  type: decimal
property_count: 17
provider_name: Guidewire
provider_slug: guidewire
slug: guidewire-context
source_filename: guidewire-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n\n    \"Policy\": {\n      \"@id\": \"schema:Service\",\n      \"@type\": \"@id\"\n    },\n    \"Claim\": {\n      \"@id\": \"schema:ReportedDoseSchedule\",\n      \"@type\": \"@id\"\n    },\n    \"Account\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"@id\"\n    },\n    \"Coverage\": {\n      \"@id\": \"schema:InsuranceAgency\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": \"schema:identifier\",\n    \"policyNumber\": \"schema:identifier\",\n    \"claimNumber\": \"schema:identifier\",\n    \"accountNumber\": \"schema:identifier\",\n    \"status\": \"schema:itemCondition\",\n    \"product\": \"schema:serviceType\",\n    \"effectiveDate\": {\n      \"@id\": \"schema:validFrom\",\n      \"@type\": \"xsd:date\"\
  \n    },\n    \"expirationDate\": {\n      \"@id\": \"schema:validThrough\",\n      \"@type\": \"xsd:date\"\n    },\n    \"issuedDate\": {\n      \"@id\": \"schema:dateIssued\",\n      \"@type\": \"xsd:date\"\n    },\n    \"totalPremium\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": \"schema:priceCurrency\",\n    \"createdDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedDate\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"insured\": {\n      \"@id\": \"schema:customer\",\n      \"@type\": \"@id\"\n    },\n    \"account\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"@id\"\n    },\n    \"coverages\": {\n      \"@id\": \"schema:offers\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n\n    \"lossDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"lossType\"\
  : \"schema:additionalType\",\n    \"lossDescription\": \"schema:description\",\n    \"reportedDate\": {\n      \"@id\": \"schema:datePosted\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"totalIncurred\": {\n      \"@id\": \"schema:totalPaymentDue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalPaid\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"displayName\": \"schema:name\",\n    \"name\": \"schema:name\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/guidewire/refs/heads/main/json-ld/guidewire-context.jsonld
tags:
- Insurance
- Policy
- Claims
- Billing
- P&C
- JSON-LD
- Linked Data
- Semantic Web
---
