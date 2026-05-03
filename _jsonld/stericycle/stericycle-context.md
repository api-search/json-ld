---
class_count: 22
classes:
- id
- accountId
- locationId
- serviceDate
- wasteType
- status
- containerCount
- weight
- manifestNumber
- treatmentFacility
- complianceDocumentUrl
- driverName
- createdAt
- employeeId
- employeeName
- courseId
- courseName
- courseType
- completionDate
- expirationDate
- score
- certificateUrl
context_file: json-ld/stericycle-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stericycle/refs/heads/main/json-ld/stericycle-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stericycle from Stericycle.
layout: jsonld
name: Stericycle Context
namespaces:
- prefix: srcl
  uri: https://www.stericycle.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: env
  uri: https://schema.org/environmentalImpact
properties:
- container: ''
  name: WastePickup
  type: reference
- container: ''
  name: ComplianceTraining
  type: reference
- container: ''
  name: ServiceAccount
  type: reference
property_count: 3
provider_name: Stericycle
provider_slug: stericycle
slug: stericycle-context
source_filename: stericycle-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"srcl\": \"https://www.stericycle.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"env\": \"https://schema.org/environmentalImpact\",\n    \"WastePickup\": {\n      \"@id\": \"srcl:WastePickup\",\n      \"@type\": \"@id\"\n    },\n    \"ComplianceTraining\": {\n      \"@id\": \"srcl:ComplianceTraining\",\n      \"@type\": \"@id\"\n    },\n    \"ServiceAccount\": {\n      \"@id\": \"srcl:ServiceAccount\",\n      \"@type\": \"@id\"\n    },\n    \"id\": \"@id\",\n    \"accountId\": \"srcl:accountId\",\n    \"locationId\": \"srcl:locationId\",\n    \"serviceDate\": \"schema:startDate\",\n    \"wasteType\": \"srcl:wasteType\",\n    \"status\": \"srcl:serviceStatus\",\n    \"containerCount\": \"srcl:containerCount\",\n    \"weight\": \"schema:weight\",\n    \"manifestNumber\": \"srcl:manifestNumber\",\n    \"treatmentFacility\": \"srcl:treatmentFacility\",\n    \"complianceDocumentUrl\": \"schema:url\",\n    \"driverName\"\
  : \"srcl:serviceProvider\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"employeeId\": \"srcl:employeeId\",\n    \"employeeName\": \"schema:name\",\n    \"courseId\": \"srcl:courseId\",\n    \"courseName\": \"schema:name\",\n    \"courseType\": \"srcl:courseType\",\n    \"completionDate\": \"schema:endDate\",\n    \"expirationDate\": \"srcl:expirationDate\",\n    \"score\": \"schema:value\",\n    \"certificateUrl\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stericycle/refs/heads/main/json-ld/stericycle-context.jsonld
tags:
- Healthcare
- Medical Waste
- Compliance
- Waste Management
- Environmental Services
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
