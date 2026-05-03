---
class_count: 10
classes:
- name
- description
- url
- category
- dateCreated
- dateModified
- Organization
- SoftwareApplication
- price
- currency
context_file: json-ld/spendflo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spendflo/refs/heads/main/json-ld/spendflo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spendflo from Spendflo.
layout: jsonld
name: Spendflo Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spendflo
  uri: https://spendflo.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
properties:
- container: ''
  name: Vendor
  type: reference
- container: ''
  name: PurchaseRequest
  type: reference
- container: ''
  name: Contract
  type: reference
- container: ''
  name: LicenseAllocation
  type: reference
- container: ''
  name: SpendReport
  type: reference
- container: ''
  name: annualSpend
  type: decimal
- container: ''
  name: licenseCount
  type: integer
- container: ''
  name: activeUsers
  type: integer
- container: ''
  name: utilizationPercent
  type: decimal
- container: ''
  name: renewalDate
  type: date
- container: ''
  name: contractStartDate
  type: date
- container: ''
  name: paymentCycle
  type: '@vocab'
- container: ''
  name: vendorStatus
  type: '@vocab'
property_count: 13
provider_name: Spendflo
provider_slug: spendflo
slug: spendflo-context
source_filename: spendflo-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spendflo\": \"https://spendflo.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n\n    \"Vendor\": {\n      \"@id\": \"spendflo:Vendor\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"A software vendor tracked in the Spendflo procurement platform.\"\n    },\n    \"PurchaseRequest\": {\n      \"@id\": \"spendflo:PurchaseRequest\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"A formal request to acquire a new software tool or license.\"\n    },\n    \"Contract\": {\n      \"@id\": \"spendflo:Contract\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"A vendor agreement with terms, pricing, and renewal dates.\"\n    },\n    \"LicenseAllocation\": {\n      \"@id\": \"spendflo:LicenseAllocation\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"An assignment of software\
  \ license seats to users.\"\n    },\n    \"SpendReport\": {\n      \"@id\": \"spendflo:SpendReport\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"An aggregated view of SaaS spending across vendors.\"\n    },\n\n    \"annualSpend\": {\n      \"@id\": \"spendflo:annualSpend\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"licenseCount\": {\n      \"@id\": \"spendflo:licenseCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"activeUsers\": {\n      \"@id\": \"spendflo:activeUsers\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"utilizationPercent\": {\n      \"@id\": \"spendflo:utilizationPercent\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"renewalDate\": {\n      \"@id\": \"spendflo:renewalDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"contractStartDate\": {\n      \"@id\": \"spendflo:contractStartDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"paymentCycle\": {\n      \"@id\": \"spendflo:paymentCycle\",\n      \"@type\": \"@vocab\"\n    },\n\
  \    \"vendorStatus\": {\n      \"@id\": \"spendflo:vendorStatus\",\n      \"@type\": \"@vocab\"\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"category\": \"schema:category\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"Organization\": \"schema:Organization\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"price\": \"gr:hasCurrencyValue\",\n    \"currency\": \"gr:hasCurrency\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spendflo/refs/heads/main/json-ld/spendflo-context.jsonld
tags:
- License Management
- Procurement
- SaaS Management
- Spend Management
- Usage Analytics
- Vendor Management
- JSON-LD
- Linked Data
- Semantic Web
---
