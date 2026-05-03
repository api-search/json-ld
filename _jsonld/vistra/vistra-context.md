---
api_specs:
- filename: vistra-incorporations-openapi.yml
  format: yaml
  label: Vistra Incorporations API
  slug: incorporations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vistra/refs/heads/main/openapi/vistra-incorporations-openapi.yml
class_count: 32
classes:
- IncorporationRequest
- IndividualStakeholder
- CorporateStakeholder
- ShareStructure
- RegisteredAgent
- Document
- companyName
- jurisdiction
- entityType
- status
- referenceNumber
- submittedAt
- estimatedCompletionDate
- firstName
- lastName
- dateOfBirth
- nationality
- role
- shares
- authorizedShares
- parValue
- currency
- documentId
- uploadUrl
- expiresAt
- filename
- size
- name
- address
- notes
- registrationNumber
- id
context_file: json-ld/vistra-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vistra/refs/heads/main/json-ld/vistra-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vistra from Vistra.
layout: jsonld
name: Vistra Context
namespaces:
- prefix: vistra
  uri: https://www.vistra.com/ontology/
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: documentIds
  type: reference
- container: ''
  name: individuals
  type: schema:Person
- container: ''
  name: corporates
  type: schema:Organization
- container: ''
  name: shareStructure
  type: ''
- container: ''
  name: registeredAgent
  type: ''
property_count: 5
provider_name: Vistra
provider_slug: vistra
slug: vistra-context
source_filename: vistra-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"vistra\": \"https://www.vistra.com/ontology/\",\n    \"schema\": \"https://schema.org/\",\n\n    \"IncorporationRequest\": \"vistra:IncorporationRequest\",\n    \"IndividualStakeholder\": \"schema:Person\",\n    \"CorporateStakeholder\": \"schema:Organization\",\n    \"ShareStructure\": \"vistra:ShareStructure\",\n    \"RegisteredAgent\": \"vistra:RegisteredAgent\",\n    \"Document\": \"schema:DigitalDocument\",\n\n    \"companyName\": \"schema:legalName\",\n    \"jurisdiction\": \"vistra:jurisdiction\",\n    \"entityType\": \"vistra:entityType\",\n    \"status\": \"schema:status\",\n    \"referenceNumber\": \"schema:identifier\",\n    \"submittedAt\": \"schema:dateCreated\",\n    \"estimatedCompletionDate\": \"vistra:estimatedCompletionDate\",\n\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"dateOfBirth\": \"schema:birthDate\",\n    \"nationality\": \"schema:nationality\"\
  ,\n    \"role\": \"vistra:stakeholderRole\",\n    \"shares\": \"vistra:shares\",\n\n    \"authorizedShares\": \"vistra:authorizedShares\",\n    \"parValue\": \"vistra:parValue\",\n    \"currency\": \"schema:currency\",\n\n    \"documentId\": \"@id\",\n    \"documentIds\": {\n      \"@id\": \"vistra:documentIds\",\n      \"@type\": \"@id\"\n    },\n\n    \"uploadUrl\": \"schema:url\",\n    \"expiresAt\": \"schema:expires\",\n    \"filename\": \"schema:name\",\n    \"size\": \"schema:contentSize\",\n\n    \"individuals\": {\n      \"@id\": \"vistra:individuals\",\n      \"@type\": \"schema:Person\"\n    },\n    \"corporates\": {\n      \"@id\": \"vistra:corporates\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"shareStructure\": {\n      \"@id\": \"vistra:shareStructure\"\n    },\n    \"registeredAgent\": {\n      \"@id\": \"vistra:registeredAgent\"\n    },\n\n    \"name\": \"schema:name\",\n    \"address\": \"schema:address\",\n    \"notes\": \"schema:description\",\n\n    \"\
  registrationNumber\": \"schema:taxID\",\n    \"id\": \"@id\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vistra/refs/heads/main/json-ld/vistra-context.jsonld
tags:
- Compliance
- Corporate Services
- Entity Management
- Finance
- Fortune 500
- Legal
- JSON-LD
- Linked Data
- Semantic Web
---
