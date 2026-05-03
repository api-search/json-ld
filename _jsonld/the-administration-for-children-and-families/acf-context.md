---
class_count: 7
classes:
- GovernmentOrganization
- name
- description
- url
- Program
- Child
- Dataset
context_file: json-ld/acf-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/the-administration-for-children-and-families/refs/heads/main/json-ld/acf-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Acf from The Administration for Children and Families.
layout: jsonld
name: Acf Context
namespaces:
- prefix: schema
  uri: http://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: hl7
  uri: http://hl7.org/fhir/
- prefix: gov
  uri: https://www.w3.org/ns/gov#
properties:
- container: ''
  name: ACF
  type: schema:GovernmentOrganization
- container: ''
  name: TANF
  type: schema:GovernmentService
- container: ''
  name: CCDF
  type: schema:GovernmentService
- container: ''
  name: HeadStart
  type: schema:GovernmentService
- container: ''
  name: LIHEAP
  type: schema:GovernmentService
- container: ''
  name: age
  type: integer
- container: ''
  name: sex
  type: string
- container: ''
  name: FosterCareCase
  type: schema:LegalCase
- container: ''
  name: placementType
  type: string
- container: ''
  name: removalDate
  type: date
- container: ''
  name: dischargeDate
  type: date
- container: ''
  name: ChildAbuseReport
  type: schema:Report
- container: ''
  name: disposition
  type: string
- container: ''
  name: TANFCase
  type: schema:GovernmentPermit
- container: ''
  name: benefitAmount
  type: decimal
- container: ''
  name: reportMonth
  type: string
- container: ''
  name: AFCARS
  type: schema:Dataset
- container: ''
  name: NCANDS
  type: schema:Dataset
- container: ''
  name: NYTD
  type: schema:Dataset
- container: ''
  name: created
  type: date
- container: ''
  name: modified
  type: date
property_count: 21
provider_name: The Administration for Children and Families
provider_slug: the-administration-for-children-and-families
slug: acf-context
source_filename: acf-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.acf.hhs.gov/v1/\",\n    \"schema\": \"http://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"hl7\": \"http://hl7.org/fhir/\",\n    \"gov\": \"https://www.w3.org/ns/gov#\",\n\n    \"GovernmentOrganization\": \"schema:GovernmentOrganization\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n\n    \"ACF\": {\n      \"@id\": \"https://schema.acf.hhs.gov/v1/ACF\",\n      \"@type\": \"schema:GovernmentOrganization\"\n    },\n\n    \"Program\": \"schema:GovernmentService\",\n    \"TANF\": {\n      \"@id\": \"https://schema.acf.hhs.gov/v1/TANF\",\n      \"@type\": \"schema:GovernmentService\"\n    },\n    \"CCDF\": {\n      \"@id\": \"https://schema.acf.hhs.gov/v1/CCDF\",\n      \"@type\": \"schema:GovernmentService\"\n    },\n    \"HeadStart\": {\n      \"@id\": \"https://schema.acf.hhs.gov/v1/HeadStart\",\n      \"@type\": \"schema:GovernmentService\"\
  \n    },\n    \"LIHEAP\": {\n      \"@id\": \"https://schema.acf.hhs.gov/v1/LIHEAP\",\n      \"@type\": \"schema:GovernmentService\"\n    },\n\n    \"Child\": \"schema:Person\",\n    \"age\": {\n      \"@id\": \"schema:age\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sex\": {\n      \"@id\": \"schema:gender\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"FosterCareCase\": {\n      \"@id\": \"https://schema.acf.hhs.gov/v1/FosterCareCase\",\n      \"@type\": \"schema:LegalCase\"\n    },\n    \"placementType\": {\n      \"@id\": \"https://schema.acf.hhs.gov/v1/placementType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"removalDate\": {\n      \"@id\": \"https://schema.acf.hhs.gov/v1/removalDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"dischargeDate\": {\n      \"@id\": \"https://schema.acf.hhs.gov/v1/dischargeDate\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"ChildAbuseReport\": {\n      \"@id\": \"https://schema.acf.hhs.gov/v1/ChildAbuseReport\",\n      \"@type\"\
  : \"schema:Report\"\n    },\n    \"disposition\": {\n      \"@id\": \"https://schema.acf.hhs.gov/v1/disposition\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"TANFCase\": {\n      \"@id\": \"https://schema.acf.hhs.gov/v1/TANFCase\",\n      \"@type\": \"schema:GovernmentPermit\"\n    },\n    \"benefitAmount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"reportMonth\": {\n      \"@id\": \"schema:temporalCoverage\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"Dataset\": \"schema:Dataset\",\n    \"AFCARS\": {\n      \"@id\": \"https://schema.acf.hhs.gov/v1/AFCARS\",\n      \"@type\": \"schema:Dataset\"\n    },\n    \"NCANDS\": {\n      \"@id\": \"https://schema.acf.hhs.gov/v1/NCANDS\",\n      \"@type\": \"schema:Dataset\"\n    },\n    \"NYTD\": {\n      \"@id\": \"https://schema.acf.hhs.gov/v1/NYTD\",\n      \"@type\": \"schema:Dataset\"\n    },\n\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n\
  \    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/the-administration-for-children-and-families/refs/heads/main/json-ld/acf-context.jsonld
tags:
- Children
- Families
- Federal Government
- Health And Human Services
- Human Services
- Social Safety Net
- JSON-LD
- Linked Data
- Semantic Web
---
