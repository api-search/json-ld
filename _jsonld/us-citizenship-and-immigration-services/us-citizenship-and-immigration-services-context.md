---
api_specs:
- filename: uscis-case-status-api-openapi.yml
  format: yaml
  label: USCIS Case Status API
  slug: uscis-case-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-citizenship-and-immigration-services/refs/heads/main/openapi/uscis-case-status-api-openapi.yml
- filename: uscis-foia-api-openapi.yml
  format: yaml
  label: USCIS FOIA Request and Status API
  slug: uscis-foia-request-and-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-citizenship-and-immigration-services/refs/heads/main/openapi/uscis-foia-api-openapi.yml
class_count: 1
classes:
- GovernmentOrganization
context_file: json-ld/us-citizenship-and-immigration-services-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-citizenship-and-immigration-services/refs/heads/main/json-ld/us-citizenship-and-immigration-services-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Citizenship And Immigration Services from US Citizenship and Immigration Services.
layout: jsonld
name: Us Citizenship And Immigration Services Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: dcat
  uri: https://www.w3.org/ns/dcat#
- prefix: uscis
  uri: https://developer.uscis.gov/
properties:
- container: ''
  name: ImmigrationCase
  type: reference
- container: ''
  name: CaseStatus
  type: reference
- container: ''
  name: FoiaRequest
  type: reference
- container: ''
  name: ImmigrationApplication
  type: reference
- container: ''
  name: AlienFile
  type: reference
- container: ''
  name: receiptNumber
  type: string
- container: ''
  name: formType
  type: string
- container: ''
  name: submittedDate
  type: date
- container: ''
  name: modifiedDate
  type: date
- container: ''
  name: status
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: statusEsDesc
  type: string
- container: set
  name: historicalCaseStatuses
  type: ''
- container: ''
  name: requestNumber
  type: string
- container: ''
  name: requestType
  type: string
- container: ''
  name: subjectFirstName
  type: string
- container: ''
  name: subjectLastName
  type: string
- container: ''
  name: subjectDateOfBirth
  type: date
- container: ''
  name: subjectAlienNumber
  type: string
- container: ''
  name: requesterName
  type: string
- container: ''
  name: requesterEmail
  type: string
- container: ''
  name: requesterType
  type: string
- container: ''
  name: alienNumber
  type: string
- container: ''
  name: publisher
  type: reference
- container: ''
  name: title
  type: string
property_count: 25
provider_name: US Citizenship and Immigration Services
provider_slug: us-citizenship-and-immigration-services
slug: us-citizenship-and-immigration-services-context
source_filename: us-citizenship-and-immigration-services-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"dcat\": \"https://www.w3.org/ns/dcat#\",\n    \"uscis\": \"https://developer.uscis.gov/\",\n\n    \"ImmigrationCase\": {\n      \"@id\": \"schema:GovernmentPermit\",\n      \"@type\": \"@id\"\n    },\n    \"CaseStatus\": {\n      \"@id\": \"schema:Status\",\n      \"@type\": \"@id\"\n    },\n    \"FoiaRequest\": {\n      \"@id\": \"schema:Action\",\n      \"@type\": \"@id\"\n    },\n    \"ImmigrationApplication\": {\n      \"@id\": \"schema:GovernmentPermit\",\n      \"@type\": \"@id\"\n    },\n    \"AlienFile\": {\n      \"@id\": \"uscis:AlienFile\",\n      \"@type\": \"@id\"\n    },\n\n    \"receiptNumber\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"formType\": {\n      \"@id\": \"schema:additionalType\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"submittedDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"modifiedDate\": {\n      \"@id\": \"dct:modified\",\n      \"@type\": \"xsd:date\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"dct:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusEsDesc\": {\n      \"@id\": \"uscis:statusEsDesc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"historicalCaseStatuses\": {\n      \"@id\": \"uscis:historicalStatuses\",\n      \"@container\": \"@set\"\n    },\n    \"requestNumber\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestType\": {\n      \"@id\": \"schema:additionalType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subjectFirstName\": {\n      \"@id\": \"schema:givenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subjectLastName\": {\n      \"@id\"\
  : \"schema:familyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subjectDateOfBirth\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"subjectAlienNumber\": {\n      \"@id\": \"uscis:alienNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requesterName\": {\n      \"@id\": \"schema:agent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requesterEmail\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requesterType\": {\n      \"@id\": \"uscis:requesterType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alienNumber\": {\n      \"@id\": \"uscis:alienNumber\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"GovernmentOrganization\": \"schema:GovernmentOrganization\",\n    \"publisher\": {\n      \"@id\": \"dct:publisher\",\n      \"@type\": \"@id\"\n    },\n    \"title\": {\n      \"@id\": \"dct:title\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-citizenship-and-immigration-services/refs/heads/main/json-ld/us-citizenship-and-immigration-services-context.jsonld
tags:
- Federal Government
- Immigration
- Citizenship
- Case Status
- FOIA
- JSON-LD
- Linked Data
- Semantic Web
---
