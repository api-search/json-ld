---
class_count: 0
classes: []
context_file: json-ld/chemius-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/chemius/refs/heads/main/json-ld/chemius-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Chemius from Chemius.
layout: jsonld
name: Chemius Context
namespaces:
- prefix: chemius
  uri: https://www.chemius.net/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: SafetyDataSheet
  type: ''
- container: ''
  name: TechnicalDataSheet
  type: ''
- container: ''
  name: HazardLabel
  type: ''
- container: ''
  name: ChemicalProduct
  type: ''
property_count: 4
provider_name: Chemius
provider_slug: chemius
slug: chemius-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"chemius\": \"https://www.chemius.net/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"SafetyDataSheet\": {\n      \"@id\": \"chemius:SafetyDataSheet\",\n      \"@context\": {\n        \"sdsId\": \"chemius:sdsId\",\n        \"productName\": \"schema:name\",\n        \"language\": \"chemius:language\",\n        \"version\": \"schema:version\",\n        \"issueDate\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:date\"\n        },\n        \"regulatoryFramework\": \"chemius:regulatoryFramework\",\n        \"hazardClass\": \"chemius:hazardClass\"\n      }\n    },\n\n    \"TechnicalDataSheet\": {\n      \"@id\": \"chemius:TechnicalDataSheet\",\n      \"@context\": {\n        \"tdsId\": \"chemius:tdsId\",\n        \"productName\": \"schema:name\",\n        \"language\": \"chemius:language\"\
  ,\n        \"version\": \"schema:version\"\n      }\n    },\n\n    \"HazardLabel\": {\n      \"@id\": \"chemius:HazardLabel\",\n      \"@context\": {\n        \"labelId\": \"chemius:labelId\",\n        \"ufi\": \"chemius:ufi\",\n        \"qrCode\": \"chemius:qrCode\",\n        \"pictograms\": \"chemius:pictograms\",\n        \"signalWord\": \"chemius:signalWord\",\n        \"hazardStatements\": \"chemius:hazardStatements\",\n        \"precautionaryStatements\": \"chemius:precautionaryStatements\"\n      }\n    },\n\n    \"ChemicalProduct\": {\n      \"@id\": \"chemius:ChemicalProduct\",\n      \"@context\": {\n        \"productId\": \"schema:productID\",\n        \"name\": \"schema:name\",\n        \"casNumber\": \"chemius:casNumber\",\n        \"ecNumber\": \"chemius:ecNumber\",\n        \"manufacturer\": \"schema:manufacturer\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/chemius/refs/heads/main/json-ld/chemius-context.jsonld
tags:
- ADR
- AI
- Chemicals
- Chemists
- Compliance
- GHS
- Hazard Communication
- Labels
- REACH
- Regulatory
- Research
- Safety Data Sheets
- SaaS
- SDS
- TDS
- JSON-LD
- Linked Data
- Semantic Web
---
