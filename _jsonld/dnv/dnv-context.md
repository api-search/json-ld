---
api_specs:
- filename: dnv-class-status-openapi.yml
  format: yaml
  label: DNV Class Status API
  slug: dnv-class-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/openapi/dnv-class-status-openapi.yml
class_count: 1
classes:
- vesselName
context_file: json-ld/dnv-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/json-ld/dnv-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dnv from DNV.
layout: jsonld
name: Dnv Context
namespaces:
- prefix: dnv
  uri: https://maritime.dnv.com/api/cs-iacs-customer/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: mar
  uri: https://www.w3.org/ns/maritime#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Vessel
  type: schema:Vehicle
- container: ''
  name: Certificate
  type: schema:Certification
- container: ''
  name: Survey
  type: schema:Observation
- container: ''
  name: imoNumber
  type: ''
- container: ''
  name: callSign
  type: ''
- container: ''
  name: flagState
  type: ''
- container: ''
  name: shipType
  type: ''
- container: ''
  name: classStatus
  type: ''
- container: ''
  name: classNotation
  type: ''
- container: ''
  name: vesselOwner
  type: schema:Organization
- container: ''
  name: technicalManager
  type: schema:Organization
- container: ''
  name: grossTonnage
  type: schema:QuantitativeValue
- container: ''
  name: deadweightTonnage
  type: ''
- container: ''
  name: buildYear
  type: integer
- container: ''
  name: shipyard
  type: schema:Organization
- container: ''
  name: enginePowerKW
  type: schema:QuantitativeValue
- container: set
  name: certificates
  type: ''
- container: ''
  name: issueDate
  type: date
- container: ''
  name: expiryDate
  type: date
- container: ''
  name: surveyDate
  type: date
- container: ''
  name: nextDueDate
  type: date
- container: ''
  name: issuingOffice
  type: schema:Organization
property_count: 22
provider_name: DNV
provider_slug: dnv
slug: dnv-context
source_filename: dnv-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dnv\": \"https://maritime.dnv.com/api/cs-iacs-customer/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"mar\": \"https://www.w3.org/ns/maritime#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Vessel\": {\n      \"@id\": \"dnv:Vessel\",\n      \"@type\": \"schema:Vehicle\"\n    },\n    \"Certificate\": {\n      \"@id\": \"dnv:Certificate\",\n      \"@type\": \"schema:Certification\"\n    },\n    \"Survey\": {\n      \"@id\": \"dnv:Survey\",\n      \"@type\": \"schema:Observation\"\n    },\n\n    \"imoNumber\": {\n      \"@id\": \"dnv:imoNumber\",\n      \"description\": \"IMO vessel identification number\"\n    },\n    \"vesselName\": \"schema:name\",\n    \"callSign\": {\n      \"@id\": \"dnv:callSign\"\n    },\n    \"flagState\": {\n      \"@id\": \"schema:countryOfOrigin\"\n    },\n    \"shipType\": {\n      \"@id\": \"schema:vehicleSpecialUsage\"\
  \n    },\n    \"classStatus\": {\n      \"@id\": \"dnv:classificationStatus\"\n    },\n    \"classNotation\": {\n      \"@id\": \"dnv:classNotation\"\n    },\n    \"vesselOwner\": {\n      \"@id\": \"schema:owner\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"technicalManager\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"grossTonnage\": {\n      \"@id\": \"schema:weight\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"deadweightTonnage\": {\n      \"@id\": \"dnv:deadweightTonnage\"\n    },\n    \"buildYear\": {\n      \"@id\": \"schema:modelDate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"shipyard\": {\n      \"@id\": \"schema:manufacturer\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"enginePowerKW\": {\n      \"@id\": \"schema:enginePower\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"certificates\": {\n      \"@id\": \"dnv:hasCertificate\",\n      \"@container\":\
  \ \"@set\"\n    },\n    \"issueDate\": {\n      \"@id\": \"schema:dateIssued\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expiryDate\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:date\"\n    },\n    \"surveyDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"nextDueDate\": {\n      \"@id\": \"dnv:nextSurveyDue\",\n      \"@type\": \"xsd:date\"\n    },\n    \"issuingOffice\": {\n      \"@id\": \"schema:issuedBy\",\n      \"@type\": \"schema:Organization\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/json-ld/dnv-context.jsonld
tags:
- Maritime
- Energy
- Classification
- Vessel
- Data Platform
- JSON-LD
- Linked Data
- Semantic Web
---
