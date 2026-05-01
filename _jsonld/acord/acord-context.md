---
api_specs:
- filename: acord-ngds-openapi.yml
  format: yaml
  label: ACORD Next-Generation Digital Standards (NGDS) API
  slug: acord-ngds-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/openapi/acord-ngds-openapi.yml
class_count: 0
classes: []
context_file: json-ld/acord-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-ld/acord-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Acord from ACORD.
layout: jsonld
name: Acord Context
namespaces:
- prefix: acord
  uri: https://www.acord.org/standards-architecture/acord-data-standards/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Policy
  type: ''
- container: ''
  name: Claim
  type: ''
- container: ''
  name: Party
  type: ''
- container: ''
  name: Coverage
  type: ''
- container: ''
  name: Address
  type: ''
property_count: 5
provider_name: ACORD
provider_slug: acord
slug: acord-context
source_filename: acord-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"acord\": \"https://www.acord.org/standards-architecture/acord-data-standards/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Policy\": {\n      \"@id\": \"acord:Policy\",\n      \"@context\": {\n        \"policyId\": {\"@id\": \"acord:policyId\", \"@type\": \"xsd:string\"},\n        \"policyNumber\": {\"@id\": \"acord:policyNumber\", \"@type\": \"xsd:string\"},\n        \"lineOfBusiness\": {\"@id\": \"acord:lineOfBusiness\"},\n        \"status\": {\"@id\": \"acord:policyStatus\"},\n        \"effectiveDate\": {\"@id\": \"schema:validFrom\", \"@type\": \"xsd:date\"},\n        \"expirationDate\": {\"@id\": \"schema:validThrough\", \"@type\": \"xsd:date\"},\n        \"premiumAmount\": {\"@id\": \"acord:premiumAmount\", \"@type\": \"xsd:decimal\"},\n        \"currency\": {\"@id\": \"schema:currency\"},\n        \"insuredParty\": {\"@id\": \"acord:insuredParty\"},\n   \
  \     \"coverages\": {\"@id\": \"acord:coverage\", \"@container\": \"@set\"},\n        \"endorsements\": {\"@id\": \"acord:endorsement\", \"@container\": \"@set\"}\n      }\n    },\n\n    \"Claim\": {\n      \"@id\": \"acord:Claim\",\n      \"@context\": {\n        \"claimId\": {\"@id\": \"acord:claimId\", \"@type\": \"xsd:string\"},\n        \"claimNumber\": {\"@id\": \"acord:claimNumber\", \"@type\": \"xsd:string\"},\n        \"policyId\": {\"@id\": \"acord:policyId\"},\n        \"status\": {\"@id\": \"acord:claimStatus\"},\n        \"lossDate\": {\"@id\": \"acord:lossDate\", \"@type\": \"xsd:date\"},\n        \"reportedDate\": {\"@id\": \"acord:reportedDate\", \"@type\": \"xsd:date\"},\n        \"lossDescription\": {\"@id\": \"acord:lossDescription\", \"@type\": \"xsd:string\"},\n        \"lossType\": {\"@id\": \"acord:lossType\"},\n        \"lossLocation\": {\"@id\": \"schema:location\"},\n        \"claimant\": {\"@id\": \"acord:claimant\"},\n        \"reserveAmount\": {\"@id\": \"\
  acord:reserveAmount\", \"@type\": \"xsd:decimal\"},\n        \"paidAmount\": {\"@id\": \"acord:paidAmount\", \"@type\": \"xsd:decimal\"}\n      }\n    },\n\n    \"Party\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"partyId\": {\"@id\": \"acord:partyId\", \"@type\": \"xsd:string\"},\n        \"partyType\": {\"@id\": \"acord:partyRole\"},\n        \"firstName\": {\"@id\": \"schema:givenName\"},\n        \"lastName\": {\"@id\": \"schema:familyName\"},\n        \"organizationName\": {\"@id\": \"schema:legalName\"},\n        \"taxId\": {\"@id\": \"acord:taxIdentifier\"},\n        \"address\": {\"@id\": \"schema:address\"},\n        \"contacts\": {\"@id\": \"schema:contactPoint\", \"@container\": \"@set\"}\n      }\n    },\n\n    \"Coverage\": {\n      \"@id\": \"acord:Coverage\",\n      \"@context\": {\n        \"coverageId\": {\"@id\": \"acord:coverageId\"},\n        \"coverageType\": {\"@id\": \"acord:coverageType\"},\n        \"limit\": {\"@id\": \"acord:coverageLimit\"\
  , \"@type\": \"xsd:decimal\"},\n        \"deductible\": {\"@id\": \"acord:deductible\", \"@type\": \"xsd:decimal\"},\n        \"premium\": {\"@id\": \"acord:premium\", \"@type\": \"xsd:decimal\"}\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"street1\": {\"@id\": \"schema:streetAddress\"},\n        \"city\": {\"@id\": \"schema:addressLocality\"},\n        \"state\": {\"@id\": \"schema:addressRegion\"},\n        \"postalCode\": {\"@id\": \"schema:postalCode\"},\n        \"country\": {\"@id\": \"schema:addressCountry\"}\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-ld/acord-context.jsonld
tags:
- Claims
- Insurance
- Policy
- Standards
- Underwriting
- JSON-LD
- Linked Data
- Semantic Web
---
