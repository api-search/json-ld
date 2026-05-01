---
class_count: 4
classes:
- policyId
- name
- phone
- email
context_file: json-ld/duck-creek-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/duck-creek/refs/heads/main/json-ld/duck-creek-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Duck Creek from duck-creek.
layout: jsonld
name: Duck Creek Context
namespaces:
- prefix: dc
  uri: https://api.duckcreek.com/v1/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Policy
  type: schema:InsurancePolicy
- container: ''
  name: Claim
  type: schema:Claim
- container: ''
  name: BillingAccount
  type: schema:Invoice
- container: ''
  name: Insured
  type: schema:Person
- container: ''
  name: Coverage
  type: ''
- container: ''
  name: policyNumber
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: productCode
  type: ''
- container: ''
  name: lineOfBusiness
  type: ''
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: expirationDate
  type: date
- container: ''
  name: insured
  type: ''
- container: set
  name: coverages
  type: ''
- container: ''
  name: totalPremium
  type: decimal
- container: ''
  name: writingCompany
  type: schema:Organization
- container: ''
  name: agentCode
  type: ''
- container: ''
  name: dateOfBirth
  type: date
- container: ''
  name: address
  type: schema:PostalAddress
- container: ''
  name: lossDate
  type: date
- container: ''
  name: claimNumber
  type: ''
- container: ''
  name: coverageCode
  type: ''
- container: ''
  name: limit
  type: decimal
- container: ''
  name: deductible
  type: decimal
- container: ''
  name: premium
  type: decimal
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 26
provider_name: duck-creek
provider_slug: duck-creek
slug: duck-creek-context
source_filename: duck-creek-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dc\": \"https://api.duckcreek.com/v1/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Policy\": {\n      \"@id\": \"dc:Policy\",\n      \"@type\": \"schema:InsurancePolicy\"\n    },\n    \"Claim\": {\n      \"@id\": \"dc:Claim\",\n      \"@type\": \"schema:Claim\"\n    },\n    \"BillingAccount\": {\n      \"@id\": \"dc:BillingAccount\",\n      \"@type\": \"schema:Invoice\"\n    },\n    \"Insured\": {\n      \"@id\": \"dc:Insured\",\n      \"@type\": \"schema:Person\"\n    },\n    \"Coverage\": {\n      \"@id\": \"dc:Coverage\"\n    },\n\n    \"policyId\": \"@id\",\n    \"policyNumber\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"status\": {\n      \"@id\": \"schema:eventStatus\"\n    },\n    \"productCode\": {\n      \"@id\": \"schema:productID\"\n    },\n    \"lineOfBusiness\": {\n     \
  \ \"@id\": \"schema:category\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"schema:validFrom\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"schema:validThrough\",\n      \"@type\": \"xsd:date\"\n    },\n    \"insured\": {\n      \"@id\": \"schema:insuredParty\"\n    },\n    \"coverages\": {\n      \"@id\": \"dc:hasCoverage\",\n      \"@container\": \"@set\"\n    },\n    \"totalPremium\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"writingCompany\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"agentCode\": {\n      \"@id\": \"schema:agent\"\n    },\n    \"name\": \"schema:name\",\n    \"dateOfBirth\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"address\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n    \"phone\": \"schema:telephone\",\n    \"email\": \"schema:email\"\
  ,\n    \"lossDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"claimNumber\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"coverageCode\": {\n      \"@id\": \"schema:productID\"\n    },\n    \"limit\": {\n      \"@id\": \"schema:maxValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"deductible\": {\n      \"@id\": \"dc:deductibleAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"premium\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/duck-creek/refs/heads/main/json-ld/duck-creek-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
