---
api_specs:
- filename: fastdol-openapi.yml
  format: yaml
  label: FastDOL API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastdol/main/openapi/fastdol-openapi.yml
class_count: 21
classes:
- Employer
- ParentCompany
- Establishment
- Inspection
- Violation
- WhdCase
- SevereInjury
- OshaAccident
- SecEnforcement
- IndustryCode
- Address
- name
- description
- employer_id
- duns
- state
- zip
- parent_name
- risk_level
- activity_nr
- agency
context_file: json-ld/fastdol-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/fastdol/refs/heads/main/json-ld/fastdol-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Fastdol from FastDOL.
layout: jsonld
name: Fastdol Context
namespaces:
- prefix: fastdol
  uri: https://raw.githubusercontent.com/api-evangelist/fastdol/refs/heads/main/json-ld/fastdol-context.jsonld#
- prefix: schema
  uri: https://schema.org/
- prefix: dcat
  uri: http://www.w3.org/ns/dcat#
- prefix: org
  uri: http://www.w3.org/ns/org#
- prefix: gleif
  uri: https://www.gleif.org/ontology/Base/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ein
  type: string
- container: ''
  name: address
  type: reference
- container: ''
  name: naics
  type: string
- container: ''
  name: naics4
  type: string
- container: ''
  name: risk_score
  type: decimal
- container: ''
  name: inspection_date
  type: date
- container: ''
  name: penalty
  type: decimal
- container: ''
  name: back_wages
  type: decimal
- container: ''
  name: employees_affected
  type: integer
- container: set
  name: inspections
  type: ''
- container: set
  name: violations
  type: ''
- container: set
  name: whd_cases
  type: ''
- container: set
  name: severe_injuries
  type: ''
- container: set
  name: osha_accidents
  type: ''
- container: set
  name: sec_enforcement
  type: ''
- container: set
  name: peers
  type: ''
- container: ''
  name: related_locations_count
  type: integer
property_count: 17
provider_name: FastDOL
provider_slug: fastdol
slug: fastdol-context
source_filename: fastdol-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fastdol\": \"https://raw.githubusercontent.com/api-evangelist/fastdol/refs/heads/main/json-ld/fastdol-context.jsonld#\",\n    \"schema\": \"https://schema.org/\",\n    \"dcat\": \"http://www.w3.org/ns/dcat#\",\n    \"org\": \"http://www.w3.org/ns/org#\",\n    \"gleif\": \"https://www.gleif.org/ontology/Base/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Employer\": \"schema:Organization\",\n    \"ParentCompany\": \"schema:Corporation\",\n    \"Establishment\": \"schema:LocalBusiness\",\n    \"Inspection\": \"fastdol:Inspection\",\n    \"Violation\": \"fastdol:Violation\",\n    \"WhdCase\": \"fastdol:WhdCase\",\n    \"SevereInjury\": \"fastdol:SevereInjury\",\n    \"OshaAccident\": \"fastdol:OshaAccident\",\n    \"SecEnforcement\": \"fastdol:SecEnforcement\",\n    \"IndustryCode\": \"fastdol:IndustryCode\",\n    \"Address\": \"schema:PostalAddress\",\n    \"name\": \"schema:name\",\n    \"description\": \"\
  schema:description\",\n    \"employer_id\": \"fastdol:employerId\",\n    \"ein\": {\n      \"@id\": \"fastdol:ein\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duns\": \"fastdol:duns\",\n    \"address\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"@id\"\n    },\n    \"state\": \"schema:addressRegion\",\n    \"zip\": \"schema:postalCode\",\n    \"naics\": {\n      \"@id\": \"fastdol:naicsCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"naics4\": {\n      \"@id\": \"fastdol:naics4Code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parent_name\": \"schema:parentOrganization\",\n    \"risk_score\": {\n      \"@id\": \"fastdol:riskScore\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"risk_level\": \"fastdol:riskLevel\",\n    \"activity_nr\": \"fastdol:activityNumber\",\n    \"inspection_date\": {\n      \"@id\": \"fastdol:inspectionDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"penalty\": {\n      \"@id\": \"fastdol:penaltyAmount\",\n      \"@type\"\
  : \"xsd:decimal\"\n    },\n    \"back_wages\": {\n      \"@id\": \"fastdol:backWages\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"employees_affected\": {\n      \"@id\": \"fastdol:employeesAffected\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"agency\": \"fastdol:agency\",\n    \"inspections\": {\n      \"@id\": \"fastdol:hasInspection\",\n      \"@container\": \"@set\"\n    },\n    \"violations\": {\n      \"@id\": \"fastdol:hasViolation\",\n      \"@container\": \"@set\"\n    },\n    \"whd_cases\": {\n      \"@id\": \"fastdol:hasWhdCase\",\n      \"@container\": \"@set\"\n    },\n    \"severe_injuries\": {\n      \"@id\": \"fastdol:hasSevereInjury\",\n      \"@container\": \"@set\"\n    },\n    \"osha_accidents\": {\n      \"@id\": \"fastdol:hasOshaAccident\",\n      \"@container\": \"@set\"\n    },\n    \"sec_enforcement\": {\n      \"@id\": \"fastdol:hasSecEnforcement\",\n      \"@container\": \"@set\"\n    },\n    \"peers\": {\n      \"@id\": \"fastdol:peer\",\n     \
  \ \"@container\": \"@set\"\n    },\n    \"related_locations_count\": {\n      \"@id\": \"fastdol:relatedLocationsCount\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/fastdol/refs/heads/main/json-ld/fastdol-context.jsonld
tags:
- OSHA
- Compliance
- Workplace Safety
- Public Records
- Federal Enforcement
- Labor
- JSON-LD
- Linked Data
- Semantic Web
---
