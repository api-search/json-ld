---
api_specs:
- filename: fiscalnote-policynote-openapi.yml
  format: yaml
  label: FiscalNote PolicyNote API
  slug: policynote-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiscalnote/refs/heads/main/openapi/fiscalnote-policynote-openapi.yml
- filename: fiscalnote-appdata-openapi.yml
  format: yaml
  label: FiscalNote AppData API
  slug: appdata-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiscalnote/refs/heads/main/openapi/fiscalnote-appdata-openapi.yml
- filename: fiscalnote-people-openapi.yml
  format: yaml
  label: FiscalNote People API
  slug: people-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiscalnote/refs/heads/main/openapi/fiscalnote-people-openapi.yml
- filename: fiscalnote-organization-openapi.yml
  format: yaml
  label: FiscalNote Organization API
  slug: organization-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiscalnote/refs/heads/main/openapi/fiscalnote-organization-openapi.yml
class_count: 0
classes: []
context_file: json-ld/fiscalnote-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/fiscalnote/refs/heads/main/json-ld/fiscalnote-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Fiscalnote from FiscalNote.
layout: jsonld
name: Fiscalnote Context
namespaces:
- prefix: fn
  uri: https://fiscalnote.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Legislation
  type: ''
- container: ''
  name: Regulation
  type: ''
- container: ''
  name: GovernmentOfficial
  type: ''
- container: ''
  name: GovernmentOrganization
  type: ''
- container: ''
  name: PresidentialTranscript
  type: ''
property_count: 5
provider_name: FiscalNote
provider_slug: fiscalnote
slug: fiscalnote-context
source_filename: fiscalnote-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fn\": \"https://fiscalnote.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Legislation\": {\n      \"@id\": \"fn:Legislation\",\n      \"@context\": {\n        \"title\": \"dcterms:title\",\n        \"shortTitle\": \"fn:shortTitle\",\n        \"number\": \"fn:billNumber\",\n        \"type\": \"fn:legislationType\",\n        \"jurisdiction\": \"fn:jurisdiction\",\n        \"session\": \"fn:legislativeSession\",\n        \"status\": \"fn:legislationStatus\",\n        \"introducedDate\": {\n          \"@id\": \"fn:introducedDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"lastActionDate\": {\n          \"@id\": \"fn:lastActionDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"lastAction\": \"fn:lastAction\",\n        \"sponsors\": {\n          \"@id\": \"fn:sponsors\",\n         \
  \ \"@container\": \"@set\"\n        },\n        \"committees\": {\n          \"@id\": \"fn:committees\",\n          \"@container\": \"@set\"\n        },\n        \"subjects\": {\n          \"@id\": \"fn:subjects\",\n          \"@container\": \"@set\"\n        },\n        \"summary\": \"dcterms:abstract\",\n        \"fullTextUrl\": {\n          \"@id\": \"fn:fullTextUrl\",\n          \"@type\": \"@id\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Regulation\": {\n      \"@id\": \"fn:Regulation\",\n      \"@context\": {\n        \"title\": \"dcterms:title\",\n        \"agency\": \"fn:issuingAgency\",\n        \"type\": \"fn:regulationType\",\n        \"status\": \"fn:regulationStatus\"\
  ,\n        \"jurisdiction\": \"fn:jurisdiction\",\n        \"publishedDate\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:date\"\n        },\n        \"effectiveDate\": {\n          \"@id\": \"fn:effectiveDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"commentPeriodEnd\": {\n          \"@id\": \"fn:commentPeriodEnd\",\n          \"@type\": \"xsd:date\"\n        },\n        \"summary\": \"dcterms:abstract\",\n        \"fullTextUrl\": {\n          \"@id\": \"fn:fullTextUrl\",\n          \"@type\": \"@id\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"GovernmentOfficial\": {\n      \"@id\": \"fn:GovernmentOfficial\",\n      \"\
  @context\": {\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"fullName\": \"schema:name\",\n        \"title\": \"schema:jobTitle\",\n        \"party\": \"fn:politicalParty\",\n        \"jurisdiction\": \"fn:jurisdiction\",\n        \"state\": \"fn:state\",\n        \"chamber\": \"fn:chamber\",\n        \"district\": \"fn:district\",\n        \"active\": \"fn:isActive\",\n        \"biography\": \"schema:description\",\n        \"photoUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\",\n        \"website\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n\
  \      }\n    },\n\n    \"GovernmentOrganization\": {\n      \"@id\": \"fn:GovernmentOrganization\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"abbreviation\": \"fn:abbreviation\",\n        \"type\": \"fn:organizationType\",\n        \"jurisdiction\": \"fn:jurisdiction\",\n        \"description\": \"schema:description\",\n        \"website\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"leadership\": {\n          \"@id\": \"fn:leadership\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PresidentialTranscript\": {\n      \"@id\": \"fn:PresidentialTranscript\",\n      \"@context\": {\n        \"title\": \"dcterms:title\",\n        \"type\": \"fn:communicationType\"\
  ,\n        \"date\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"location\": \"schema:location\",\n        \"duration\": \"schema:duration\",\n        \"wordCount\": \"schema:wordCount\",\n        \"fullText\": \"schema:text\",\n        \"summary\": \"dcterms:abstract\",\n        \"videoUrl\": {\n          \"@id\": \"schema:video\",\n          \"@type\": \"@id\"\n        },\n        \"sourceUrl\": {\n          \"@id\": \"dcterms:source\",\n          \"@type\": \"@id\"\n        },\n        \"verified\": \"fn:isVerified\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/fiscalnote/refs/heads/main/json-ld/fiscalnote-context.jsonld
tags:
- Government
- Legislation
- Policy
- Political Intelligence
- Regulation
- JSON-LD
- Linked Data
- Semantic Web
---
