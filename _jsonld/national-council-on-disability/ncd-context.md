---
class_count: 3
classes:
- title
- summary
- format
context_file: json-ld/ncd-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/national-council-on-disability/refs/heads/main/json-ld/ncd-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ncd from National Council on Disability.
layout: jsonld
name: Ncd Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: gov
  uri: https://www.w3.org/ns/gov#
- prefix: policyArea
  uri: https://www.ncd.gov/vocab/policyArea
- prefix: recommendations
  uri: https://www.ncd.gov/vocab/recommendation
- prefix: fiscalYear
  uri: https://www.ncd.gov/vocab/fiscalYear
- prefix: recordType
  uri: https://www.ncd.gov/vocab/recordType
- prefix: reportType
  uri: https://www.ncd.gov/vocab/reportType
- prefix: committee
  uri: https://www.ncd.gov/vocab/committee
- prefix: chamber
  uri: https://www.ncd.gov/vocab/chamber
- prefix: recipient
  uri: https://www.ncd.gov/vocab/recipient
- prefix: recipientAgency
  uri: https://www.ncd.gov/vocab/recipientAgency
properties:
- container: ''
  name: publicationDate
  type: date
- container: ''
  name: documentURL
  type: reference
- container: ''
  name: agencyBudget
  type: decimal
- container: ''
  name: publishedDate
  type: date
- container: ''
  name: date
  type: date
- container: ''
  name: year
  type: integer
property_count: 6
provider_name: National Council on Disability
provider_slug: national-council-on-disability
slug: ncd-context
source_filename: ncd-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://www.ncd.gov/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"gov\": \"https://www.w3.org/ns/gov#\",\n    \"title\": \"schema:name\",\n    \"publicationDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"policyArea\": \"https://www.ncd.gov/vocab/policyArea\",\n    \"summary\": \"schema:abstract\",\n    \"recommendations\": \"https://www.ncd.gov/vocab/recommendation\",\n    \"documentURL\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"fiscalYear\": \"https://www.ncd.gov/vocab/fiscalYear\",\n    \"recordType\": \"https://www.ncd.gov/vocab/recordType\",\n    \"reportType\": \"https://www.ncd.gov/vocab/reportType\",\n    \"committee\": \"https://www.ncd.gov/vocab/committee\",\n    \"chamber\": \"https://www.ncd.gov/vocab/chamber\",\n    \"recipient\": \"https://www.ncd.gov/vocab/recipient\"\
  ,\n    \"recipientAgency\": \"https://www.ncd.gov/vocab/recipientAgency\",\n    \"agencyBudget\": {\n      \"@id\": \"https://www.ncd.gov/vocab/agencyBudget\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"publishedDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"date\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"format\": \"schema:encodingFormat\",\n    \"year\": {\n      \"@id\": \"schema:copyrightYear\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/national-council-on-disability/refs/heads/main/json-ld/ncd-context.jsonld
tags:
- Disability
- Federal Government
- Policy
- Civil Rights
- Healthcare
- Independent Agency
- JSON-LD
- Linked Data
- Semantic Web
---
