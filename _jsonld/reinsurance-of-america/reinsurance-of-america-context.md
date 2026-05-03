---
class_count: 0
classes: []
context_file: json-ld/reinsurance-of-america-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/reinsurance-of-america/refs/heads/main/json-ld/reinsurance-of-america-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Reinsurance Of America from Reinsurance Group of America.
layout: jsonld
name: Reinsurance Of America Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: finserv
  uri: http://schema.org/
- prefix: rga
  uri: https://rgare.com/vocab/
properties:
- container: ''
  name: RGAInsuranceProduct
  type: reference
- container: ''
  name: Reinsurer
  type: reference
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: riskScore
  type: decimal
- container: ''
  name: underwritingCategory
  type: ''
- container: ''
  name: claimsData
  type: ''
- container: ''
  name: medicalRecords
  type: ''
- container: ''
  name: carrierSystem
  type: ''
- container: ''
  name: policyType
  type: ''
- container: ''
  name: coverageAmount
  type: decimal
- container: ''
  name: issuedDate
  type: dateTime
- container: ''
  name: clientId
  type: ''
property_count: 13
provider_name: Reinsurance Group of America
provider_slug: reinsurance-of-america
slug: reinsurance-of-america-context
source_filename: reinsurance-of-america-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"finserv\": \"http://schema.org/\",\n    \"rga\": \"https://rgare.com/vocab/\",\n    \"RGAInsuranceProduct\": {\n      \"@id\": \"rga:InsuranceProduct\",\n      \"@type\": \"@id\"\n    },\n    \"Reinsurer\": {\n      \"@id\": \"schema:FinancialService\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"riskScore\": {\n      \"@id\": \"rga:riskScore\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"underwritingCategory\": {\n      \"@id\": \"rga:underwritingCategory\"\n    },\n    \"claimsData\": {\n      \"@id\": \"rga:claimsData\"\n    },\n    \"medicalRecords\": {\n      \"@id\": \"rga:medicalRecords\"\n    },\n    \"carrierSystem\": {\n      \"@id\": \"rga:carrierSystem\"\n    },\n    \"policyType\": {\n   \
  \   \"@id\": \"rga:policyType\"\n    },\n    \"coverageAmount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"issuedDate\": {\n      \"@id\": \"schema:dateIssued\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"clientId\": {\n      \"@id\": \"schema:identifier\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/reinsurance-of-america/refs/heads/main/json-ld/reinsurance-of-america-context.jsonld
tags:
- Reinsurance
- Life Insurance
- Health Insurance
- Underwriting
- Financial Services
- Risk Assessment
- Digital Health
- JSON-LD
- Linked Data
- Semantic Web
---
