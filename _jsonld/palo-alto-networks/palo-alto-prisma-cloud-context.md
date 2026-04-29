---
class_count: 3
classes:
- Prisma Cloud Policy
- remediation
- rule
context_file: json-ld/palo-alto-prisma-cloud-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-cloud-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Prisma Cloud from Palo Alto Networks.
layout: jsonld
name: Palo Alto Prisma Cloud Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: cliScriptTemplate
  type: string
- container: ''
  name: cloudType
  type: string
- container: set
  name: complianceMetadata
  type: ''
- container: ''
  name: createdBy
  type: string
- container: ''
  name: createdOn
  type: integer
- container: ''
  name: criteria
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: enabled
  type: boolean
- container: set
  name: labels
  type: string
- container: ''
  name: lastModifiedBy
  type: string
- container: ''
  name: lastModifiedOn
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: parameters
  type: reference
- container: ''
  name: policyId
  type: string
- container: ''
  name: policyType
  type: string
- container: ''
  name: recommendation
  type: string
- container: ''
  name: remediable
  type: boolean
- container: ''
  name: requirementId
  type: string
- container: ''
  name: requirementName
  type: string
- container: ''
  name: rollbackCLIScriptTemplate
  type: string
- container: ''
  name: savedSearch
  type: boolean
- container: ''
  name: sectionDescription
  type: string
- container: ''
  name: sectionId
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: standardName
  type: string
- container: ''
  name: systemDefault
  type: boolean
- container: ''
  name: type
  type: string
- container: ''
  name: withIac
  type: boolean
property_count: 28
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-prisma-cloud-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Prisma Cloud Policy\": \"pan:Prisma Cloud Policy\",\n    \"cliScriptTemplate\": {\n      \"@id\": \"pan:cliScriptTemplate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudType\": {\n      \"@id\": \"pan:cloudType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"complianceMetadata\": {\n      \"@id\": \"pan:complianceMetadata\",\n      \"@container\": \"@set\"\n    },\n    \"createdBy\": {\n      \"@id\": \"pan:createdBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdOn\": {\n      \"@id\": \"pan:createdOn\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"criteria\": {\n      \"@id\": \"pan:criteria\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"labels\": {\n      \"@id\": \"pan:labels\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModifiedBy\": {\n      \"@id\": \"pan:lastModifiedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModifiedOn\": {\n      \"@id\": \"pan:lastModifiedOn\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"pan:parameters\",\n      \"@type\": \"@id\"\n    },\n    \"policyId\": {\n      \"@id\": \"pan:policyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyType\": {\n      \"@id\": \"pan:policyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendation\": {\n      \"@id\": \"pan:recommendation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remediable\": {\n      \"@id\": \"pan:remediable\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"remediation\": \"pan:remediation\",\n    \"requirementId\": {\n      \"@id\": \"pan:requirementId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requirementName\": {\n      \"@id\": \"pan:requirementName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rollbackCLIScriptTemplate\": {\n      \"@id\": \"pan:rollbackCLIScriptTemplate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rule\": \"pan:rule\",\n    \"savedSearch\": {\n      \"@id\": \"pan:savedSearch\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"sectionDescription\": {\n      \"@id\": \"pan:sectionDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sectionId\": {\n      \"@id\": \"pan:sectionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"standardName\": {\n      \"@id\": \"pan:standardName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"systemDefault\"\
  : {\n      \"@id\": \"pan:systemDefault\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"withIac\": {\n      \"@id\": \"pan:withIac\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-cloud-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
