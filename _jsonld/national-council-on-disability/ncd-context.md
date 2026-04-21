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
