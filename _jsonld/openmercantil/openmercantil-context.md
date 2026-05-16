---
api_specs:
- filename: openmercantil-openapi.yml
  format: yaml
  label: OpenMercantil Public API
  slug: openmercantil-public-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openmercantil/refs/heads/main/openapi/openmercantil-openapi.yml
class_count: 31
classes:
- Company
- Person
- Event
- Officer
- slug
- name
- cif
- registered_address
- province
- registry
- legal_form
- status
- cnae
- founding_date
- last_event
- events_count
- aliases
- id
- date
- type
- text
- source_url
- person_slug
- role
- appointed
- ceased
- lat
- lng
- address
- score
- trust_score
context_file: json-ld/openmercantil-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/openmercantil/refs/heads/main/json-ld/openmercantil-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Openmercantil from OpenMercantil.
layout: jsonld
name: Openmercantil Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: om
  uri: https://openmercantil.es/vocab/
properties:
- container: set
  name: components
  type: ''
- container: set
  name: items
  type: ''
property_count: 2
provider_name: OpenMercantil
provider_slug: openmercantil
slug: openmercantil-context
source_filename: openmercantil-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"om\": \"https://openmercantil.es/vocab/\",\n    \"Company\": \"schema:Organization\",\n    \"Person\": \"schema:Person\",\n    \"Event\": \"om:RegistryEvent\",\n    \"Officer\": \"om:Officer\",\n    \"slug\": \"om:slug\",\n    \"name\": \"schema:name\",\n    \"cif\": \"schema:taxID\",\n    \"registered_address\": \"schema:address\",\n    \"province\": \"schema:addressRegion\",\n    \"registry\": \"om:registry\",\n    \"legal_form\": \"om:legalForm\",\n    \"status\": \"om:registryStatus\",\n    \"cnae\": \"om:cnae\",\n    \"founding_date\": \"schema:foundingDate\",\n    \"last_event\": \"om:lastEventDate\",\n    \"events_count\": \"om:eventsCount\",\n    \"aliases\": \"schema:alternateName\",\n    \"id\": \"@id\",\n    \"date\": \"schema:datePublished\",\n    \"type\": \"om:actType\",\n    \"text\": \"schema:text\",\n    \"source_url\"\
  : \"schema:isBasedOn\",\n    \"person_slug\": \"om:personSlug\",\n    \"role\": \"schema:roleName\",\n    \"appointed\": \"om:appointedOn\",\n    \"ceased\": \"om:ceasedOn\",\n    \"lat\": \"schema:latitude\",\n    \"lng\": \"schema:longitude\",\n    \"address\": \"schema:address\",\n    \"score\": \"om:companyScore\",\n    \"trust_score\": \"om:trustScore\",\n    \"components\": {\n      \"@id\": \"om:scoreComponents\",\n      \"@container\": \"@set\"\n    },\n    \"items\": {\n      \"@id\": \"om:items\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/openmercantil/refs/heads/main/json-ld/openmercantil-context.jsonld
tags:
- Open Data
- Spain
- Company Data
- Business Registry
- BORME
- Public Records
- Spanish Companies
- CIF
- CNAE
- Public Procurement
- PLACSP
- CNMV
- OEPM
- BDNS
- OpenSanctions
- Public-Interest Data
- Spanish Open Data
- REST API
- JSON
- CSV
- Geocoding
- Trust Score
- Registry Timeline
- Daily Summary
- JSON-LD
- Linked Data
- Semantic Web
---
