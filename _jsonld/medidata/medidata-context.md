---
api_specs:
- filename: medidata-rave-openapi.yml
  format: yaml
  label: Medidata Rave EDC API
  slug: medidata-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/medidata/refs/heads/main/openapi/medidata-rave-openapi.yml
class_count: 20
classes:
- Study
- studyOID
- studyName
- status
- Subject
- subjectKey
- ClinicalEvent
- eventOID
- eventName
- CRFForm
- formOID
- formName
- CRFField
- fieldOID
- value
- Site
- siteName
- investigator
- city
- country
context_file: json-ld/medidata-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/medidata/refs/heads/main/json-ld/medidata-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Medidata from medidata.
layout: jsonld
name: Medidata Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: medidata
  uri: https://www.medidata.com/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: protocolName
  type: string
- container: ''
  name: environment
  type: string
- container: ''
  name: createdDate
  type: dateTime
- container: ''
  name: modifiedDate
  type: dateTime
- container: ''
  name: siteID
  type: string
- container: ''
  name: enrollmentDate
  type: date
- container: ''
  name: screeningDate
  type: date
- container: ''
  name: initials
  type: string
- container: ''
  name: eventDate
  type: date
- container: ''
  name: dataEntryDateTime
  type: dateTime
property_count: 10
provider_name: medidata
provider_slug: medidata
slug: medidata-context
source_filename: medidata-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"medidata\": \"https://www.medidata.com/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Study\": \"schema:ResearchProject\",\n    \"studyOID\": \"schema:identifier\",\n    \"studyName\": \"schema:name\",\n    \"protocolName\": {\n      \"@id\": \"medidata:protocolName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environment\": {\n      \"@id\": \"medidata:environment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": \"schema:status\",\n    \"createdDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedDate\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Subject\": \"schema:Patient\",\n    \"subjectKey\": \"schema:identifier\",\n    \"siteID\": {\n      \"@id\": \"schema:memberOf\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enrollmentDate\"\
  : {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"screeningDate\": {\n      \"@id\": \"medidata:screeningDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"initials\": {\n      \"@id\": \"schema:additionalName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClinicalEvent\": \"schema:MedicalStudy\",\n    \"eventOID\": \"schema:identifier\",\n    \"eventName\": \"schema:name\",\n    \"eventDate\": {\n      \"@id\": \"schema:eventDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"CRFForm\": \"schema:Observation\",\n    \"formOID\": \"schema:identifier\",\n    \"formName\": \"schema:name\",\n    \"CRFField\": \"schema:PropertyValue\",\n    \"fieldOID\": \"schema:identifier\",\n    \"value\": \"schema:value\",\n    \"dataEntryDateTime\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Site\": \"schema:Hospital\",\n    \"siteName\": \"schema:name\",\n    \"investigator\": \"schema:employee\",\n    \"city\"\
  : \"schema:addressLocality\",\n    \"country\": \"schema:addressCountry\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/medidata/refs/heads/main/json-ld/medidata-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
