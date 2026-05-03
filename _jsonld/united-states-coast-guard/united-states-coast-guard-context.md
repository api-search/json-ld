---
api_specs:
- filename: cgmix-maritime-information-exchange-openapi.yml
  format: yaml
  label: CGMIX Maritime Information Exchange API
  slug: cgmix-maritime-information-exchange
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-coast-guard/refs/heads/main/openapi/cgmix-maritime-information-exchange-openapi.yml
class_count: 5
classes:
- Vessel
- VesselCase
- EquipmentCertification
- IncidentReport
- GovernmentOrganization
context_file: json-ld/united-states-coast-guard-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/united-states-coast-guard/refs/heads/main/json-ld/united-states-coast-guard-context.jsonld
description: JSON-LD context defining the semantic vocabulary for United States Coast Guard from United States Coast Guard.
layout: jsonld
name: United States Coast Guard Context
namespaces:
- prefix: uscg
  uri: https://cgmix.uscg.mil/ontology/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: gov
  uri: https://www.w3.org/ns/org#
properties:
- container: ''
  name: vesselId
  type: reference
- container: ''
  name: vesselName
  type: ''
- container: ''
  name: flag
  type: ''
- container: ''
  name: hullIdentificationNumber
  type: ''
- container: ''
  name: vesselType
  type: ''
- container: ''
  name: grossTons
  type: schema:Number
- container: ''
  name: netTons
  type: schema:Number
- container: ''
  name: length
  type: schema:Distance
- container: ''
  name: ownerName
  type: ''
- container: ''
  name: homePort
  type: ''
- container: ''
  name: inspectionDate
  type: schema:Date
- container: ''
  name: port
  type: ''
- container: ''
  name: examType
  type: ''
- container: ''
  name: result
  type: ''
- container: ''
  name: deficiencyCount
  type: schema:Integer
- container: ''
  name: equipmentId
  type: ''
- container: ''
  name: manufacturer
  type: ''
- container: ''
  name: approvalStatus
  type: ''
- container: ''
  name: description
  type: ''
property_count: 19
provider_name: United States Coast Guard
provider_slug: united-states-coast-guard
slug: united-states-coast-guard-context
source_filename: united-states-coast-guard-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"uscg\": \"https://cgmix.uscg.mil/ontology/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"gov\": \"https://www.w3.org/ns/org#\",\n\n    \"Vessel\": \"uscg:Vessel\",\n    \"VesselCase\": \"uscg:VesselCase\",\n    \"EquipmentCertification\": \"uscg:EquipmentCertification\",\n    \"IncidentReport\": \"uscg:IncidentReport\",\n    \"GovernmentOrganization\": \"GovernmentOrganization\",\n\n    \"vesselId\": {\n      \"@id\": \"uscg:officialNumber\",\n      \"@type\": \"@id\"\n    },\n    \"vesselName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"flag\": {\n      \"@id\": \"uscg:flagState\"\n    },\n    \"hullIdentificationNumber\": {\n      \"@id\": \"uscg:hin\"\n    },\n    \"vesselType\": {\n      \"@id\": \"uscg:vesselType\"\n    },\n    \"grossTons\": {\n      \"@id\": \"uscg:grossTonnage\",\n      \"@type\": \"schema:Number\"\n    },\n    \"netTons\": {\n      \"@id\": \"uscg:netTonnage\"\
  ,\n      \"@type\": \"schema:Number\"\n    },\n    \"length\": {\n      \"@id\": \"schema:depth\",\n      \"@type\": \"schema:Distance\"\n    },\n    \"ownerName\": {\n      \"@id\": \"schema:ownershipFundingInfo\"\n    },\n    \"homePort\": {\n      \"@id\": \"uscg:homePort\"\n    },\n    \"inspectionDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"schema:Date\"\n    },\n    \"port\": {\n      \"@id\": \"schema:location\"\n    },\n    \"examType\": {\n      \"@id\": \"uscg:examinationType\"\n    },\n    \"result\": {\n      \"@id\": \"schema:result\"\n    },\n    \"deficiencyCount\": {\n      \"@id\": \"uscg:deficiencyCount\",\n      \"@type\": \"schema:Integer\"\n    },\n    \"equipmentId\": {\n      \"@id\": \"uscg:equipmentApprovalNumber\"\n    },\n    \"manufacturer\": {\n      \"@id\": \"schema:manufacturer\"\n    },\n    \"approvalStatus\": {\n      \"@id\": \"schema:validFrom\"\n    },\n    \"description\": {\n      \"@id\": \"dcterms:description\"\n    }\n\
  \  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/united-states-coast-guard/refs/heads/main/json-ld/united-states-coast-guard-context.jsonld
tags:
- Federal Government
- Maritime Safety
- Vessel Documentation
- Emergency Response
- Law Enforcement
- JSON-LD
- Linked Data
- Semantic Web
---
