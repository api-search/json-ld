---
class_count: 0
classes: []
context_file: json-ld/department-of-homeland-security-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/department-of-homeland-security/refs/heads/main/json-ld/department-of-homeland-security-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Department Of Homeland Security from Department of Homeland Security.
layout: jsonld
name: Department Of Homeland Security Context
namespaces:
- prefix: dhs
  uri: https://www.dhs.gov/
properties:
- container: ''
  name: DisasterDeclaration
  type: ''
- container: ''
  name: PublicAssistance
  type: ''
- container: ''
  name: ImmigrationCase
  type: ''
- container: ''
  name: FOIARequest
  type: ''
- container: ''
  name: Vulnerability
  type: ''
- container: ''
  name: NTASAlert
  type: ''
property_count: 6
provider_name: Department of Homeland Security
provider_slug: department-of-homeland-security
slug: department-of-homeland-security-context
source_filename: department-of-homeland-security-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"dhs\": \"https://www.dhs.gov/\",\n    \"DisasterDeclaration\": {\n      \"@id\": \"https://schema.org/Event\",\n      \"@context\": {\n        \"disasterNumber\": \"https://schema.org/identifier\",\n        \"state\": \"https://schema.org/addressRegion\",\n        \"incidentType\": \"https://schema.org/category\",\n        \"declarationDate\": \"https://schema.org/startDate\",\n        \"title\": \"https://schema.org/name\"\n      }\n    },\n    \"PublicAssistance\": {\n      \"@id\": \"dhs:fema/public-assistance\",\n      \"@context\": {\n        \"applicantId\": \"https://schema.org/identifier\",\n        \"disasterNumber\": \"https://schema.org/about\",\n        \"obligatedAmount\": \"https://schema.org/amount\",\n        \"category\": \"https://schema.org/category\"\n      }\n    },\n    \"ImmigrationCase\": {\n      \"@id\": \"dhs:uscis/case\",\n      \"@context\": {\n        \"receiptNumber\": \"https://schema.org/identifier\"\
  ,\n        \"formType\": \"https://schema.org/category\",\n        \"status\": \"https://schema.org/actionStatus\",\n        \"lastUpdated\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"FOIARequest\": {\n      \"@id\": \"dhs:uscis/foia\",\n      \"@context\": {\n        \"requestNumber\": \"https://schema.org/identifier\",\n        \"subject\": \"https://schema.org/about\",\n        \"status\": \"https://schema.org/actionStatus\",\n        \"submittedDate\": \"https://schema.org/dateSubmitted\"\n      }\n    },\n    \"Vulnerability\": {\n      \"@id\": \"dhs:cisa/kev\",\n      \"@context\": {\n        \"cveID\": \"https://schema.org/identifier\",\n        \"vendorProject\": \"https://schema.org/manufacturer\",\n        \"product\": \"https://schema.org/Product\",\n        \"vulnerabilityName\": \"https://schema.org/name\",\n        \"dateAdded\": \"https://schema.org/dateCreated\",\n        \"shortDescription\": \"https://schema.org/description\",\n        \"requiredAction\"\
  : \"https://schema.org/action\",\n        \"dueDate\": \"https://schema.org/expires\",\n        \"knownRansomwareCampaignUse\": \"https://schema.org/keywords\"\n      }\n    },\n    \"NTASAlert\": {\n      \"@id\": \"dhs:ntas\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"summary\": \"https://schema.org/description\",\n        \"issuedAt\": \"https://schema.org/dateIssued\",\n        \"expiresAt\": \"https://schema.org/expires\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/department-of-homeland-security/refs/heads/main/json-ld/department-of-homeland-security-context.jsonld
tags:
- CISA
- Cybersecurity
- Disaster
- Federal Government
- FEMA
- Homeland Security
- Immigration
- NTAS
- Open Data
- USCIS
- JSON-LD
- Linked Data
- Semantic Web
---
