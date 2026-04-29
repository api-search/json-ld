---
class_count: 9
classes:
- Alert
- AlertFilter
- CloudAccount
- ComplianceStandard
- Policy
- PolicyInput
- Report
- SearchResult
- TimeRange
context_file: json-ld/palo-alto-prisma-cloud-cspm-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-cloud-cspm-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Prisma Cloud Cspm Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Prisma Cloud Cspm Api Context
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
  name: accountId
  type: string
- container: ''
  name: accountName
  type: string
- container: ''
  name: alertTime
  type: integer
- container: ''
  name: amount
  type: integer
- container: ''
  name: cloudType
  type: string
- container: set
  name: complianceMetadata
  type: reference
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
  name: data
  type: reference
- container: ''
  name: description
  type: string
- container: ''
  name: downloadUrl
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: firstSeen
  type: integer
- container: ''
  name: id
  type: string
- container: set
  name: items
  type: reference
- container: ''
  name: lastModifiedOn
  type: integer
- container: ''
  name: lastModifiedTs
  type: integer
- container: ''
  name: lastSeen
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: numberOfPolicies
  type: integer
- container: ''
  name: operator
  type: string
- container: ''
  name: overallPassed
  type: boolean
- container: ''
  name: policiesAssigned
  type: integer
- container: ''
  name: policy
  type: reference
- container: ''
  name: policyId
  type: string
- container: ''
  name: policyType
  type: string
- container: ''
  name: query
  type: string
- container: ''
  name: rating
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: recommendation
  type: string
- container: ''
  name: regionId
  type: string
- container: ''
  name: requirementId
  type: string
- container: ''
  name: requirementName
  type: string
- container: ''
  name: resource
  type: reference
- container: ''
  name: resourceType
  type: string
- container: ''
  name: riskDetail
  type: reference
- container: ''
  name: rrn
  type: string
- container: ''
  name: rule
  type: reference
- container: ''
  name: score
  type: integer
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
  name: status
  type: string
- container: ''
  name: systemDefault
  type: boolean
- container: ''
  name: totalRows
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: value
  type: string
property_count: 49
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-prisma-cloud-cspm-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Alert\": \"pan:Alert\",\n    \"AlertFilter\": \"pan:AlertFilter\",\n    \"CloudAccount\": \"pan:CloudAccount\",\n    \"ComplianceStandard\": \"pan:ComplianceStandard\",\n    \"Policy\": \"pan:Policy\",\n    \"PolicyInput\": \"pan:PolicyInput\",\n    \"Report\": \"pan:Report\",\n    \"SearchResult\": \"pan:SearchResult\",\n    \"TimeRange\": \"pan:TimeRange\",\n    \"accountId\": {\n      \"@id\": \"pan:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountName\": {\n      \"@id\": \"pan:accountName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertTime\": {\n      \"@id\": \"pan:alertTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"amount\": {\n      \"@id\": \"pan:amount\",\n      \"@type\": \"xsd:integer\"\n \
  \   },\n    \"cloudType\": {\n      \"@id\": \"pan:cloudType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"complianceMetadata\": {\n      \"@id\": \"pan:complianceMetadata\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"createdBy\": {\n      \"@id\": \"pan:createdBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdOn\": {\n      \"@id\": \"pan:createdOn\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"criteria\": {\n      \"@id\": \"pan:criteria\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"pan:data\",\n      \"@type\": \"@id\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"pan:downloadUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"firstSeen\": {\n      \"@id\": \"pan:firstSeen\",\n      \"@type\": \"\
  xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"pan:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"lastModifiedOn\": {\n      \"@id\": \"pan:lastModifiedOn\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"lastModifiedTs\": {\n      \"@id\": \"pan:lastModifiedTs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"lastSeen\": {\n      \"@id\": \"pan:lastSeen\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfPolicies\": {\n      \"@id\": \"pan:numberOfPolicies\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"operator\": {\n      \"@id\": \"pan:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overallPassed\": {\n      \"@id\": \"pan:overallPassed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"policiesAssigned\": {\n      \"@id\": \"pan:policiesAssigned\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"policy\": {\n      \"@id\": \"pan:policy\",\n      \"@type\": \"@id\"\n    },\n    \"policyId\": {\n      \"@id\": \"pan:policyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyType\": {\n      \"@id\": \"pan:policyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"query\": {\n      \"@id\": \"pan:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rating\": {\n      \"@id\": \"pan:rating\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"pan:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendation\": {\n      \"@id\": \"pan:recommendation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regionId\": {\n      \"@id\": \"pan:regionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requirementId\": {\n      \"@id\": \"pan:requirementId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requirementName\": {\n      \"@id\": \"pan:requirementName\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"resource\": {\n      \"@id\": \"pan:resource\",\n      \"@type\": \"@id\"\n    },\n    \"resourceType\": {\n      \"@id\": \"pan:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskDetail\": {\n      \"@id\": \"pan:riskDetail\",\n      \"@type\": \"@id\"\n    },\n    \"rrn\": {\n      \"@id\": \"pan:rrn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rule\": {\n      \"@id\": \"pan:rule\",\n      \"@type\": \"@id\"\n    },\n    \"score\": {\n      \"@id\": \"pan:score\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sectionId\": {\n      \"@id\": \"pan:sectionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"standardName\": {\n      \"@id\": \"pan:standardName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"systemDefault\": {\n      \"@id\": \"pan:systemDefault\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"totalRows\": {\n      \"@id\": \"pan:totalRows\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"pan:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-cloud-cspm-api-context.jsonld
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
