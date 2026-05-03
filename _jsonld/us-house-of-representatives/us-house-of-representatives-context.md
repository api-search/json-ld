---
api_specs:
- filename: congress-gov-api-openapi.yml
  format: yaml
  label: Congress.gov API
  slug: congress-gov-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-house-of-representatives/refs/heads/main/openapi/congress-gov-api-openapi.yml
class_count: 26
classes:
- congress
- Legislation
- LegislativeBill
- MemberOfCongress
- CongressionalCommittee
- CongressionalChamber
- LegislativeAction
- id
- type
- number
- title
- originChamber
- latestAction
- sponsors
- cosponsors
- subjects
- bioguideId
- name
- firstName
- lastName
- state
- party
- district
- chamber
- officeAddress
- phoneNumber
context_file: json-ld/us-house-of-representatives-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-house-of-representatives/refs/heads/main/json-ld/us-house-of-representatives-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us House Of Representatives from US House of Representatives.
layout: jsonld
name: Us House Of Representatives Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: introducedDate
  type: date
- container: ''
  name: updateDate
  type: dateTime
- container: ''
  name: officialWebsiteUrl
  type: reference
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Congress
  type: ''
property_count: 5
provider_name: US House of Representatives
provider_slug: us-house-of-representatives
slug: us-house-of-representatives-context
source_filename: us-house-of-representatives-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"congress\": \"https://api.congress.gov/ns/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Legislation\": \"schema:Legislation\",\n    \"LegislativeBill\": \"schema:LegislativeBill\",\n    \"MemberOfCongress\": \"schema:Person\",\n    \"CongressionalCommittee\": \"schema:GovernmentOrganization\",\n    \"CongressionalChamber\": \"schema:GovernmentOrganization\",\n    \"LegislativeAction\": \"schema:Action\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"congress\": \"congress:congressNumber\",\n    \"number\": \"congress:billNumber\",\n    \"title\": \"schema:name\",\n    \"introducedDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"updateDate\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"originChamber\": \"congress:originatingChamber\"\
  ,\n    \"latestAction\": \"schema:potentialAction\",\n    \"sponsors\": \"schema:author\",\n    \"cosponsors\": \"congress:cosponsors\",\n    \"subjects\": \"schema:about\",\n\n    \"bioguideId\": \"congress:bioguideId\",\n    \"name\": \"schema:name\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"state\": \"schema:addressRegion\",\n    \"party\": \"schema:memberOf\",\n    \"district\": \"congress:congressionalDistrict\",\n    \"chamber\": \"congress:chamber\",\n    \"officeAddress\": \"schema:address\",\n    \"phoneNumber\": \"schema:telephone\",\n    \"officialWebsiteUrl\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n\n    \"Organization\": {\n      \"@id\": \"schema:LegislativeBuilding\",\n      \"name\": \"US House of Representatives\",\n      \"url\": \"https://www.house.gov\",\n      \"sameAs\": [\n        \"https://www.wikidata.org/wiki/Q11701\",\n        \"https://dbpedia.org/resource/United_States_House_of_Representatives\"\
  \n      ]\n    },\n\n    \"Congress\": {\n      \"@id\": \"schema:GovernmentOrganization\",\n      \"name\": \"United States Congress\",\n      \"url\": \"https://www.congress.gov\",\n      \"sameAs\": \"https://www.wikidata.org/wiki/Q11268\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-house-of-representatives/refs/heads/main/json-ld/us-house-of-representatives-context.jsonld
tags:
- Federal Government
- Legislation
- Congress
- Legislative Data
- Bills
- Members
- Committees
- JSON-LD
- Linked Data
- Semantic Web
---
