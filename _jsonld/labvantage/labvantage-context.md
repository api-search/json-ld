---
api_specs:
- filename: labvantage-lims-openapi.yml
  format: yaml
  label: LabVantage LIMS API
  slug: labvantage-lims-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/labvantage/refs/heads/main/openapi/labvantage-lims-openapi.yml
class_count: 26
classes:
- sampleId
- sampleNumber
- sampleType
- sampleDescription
- status
- loginUser
- storageLocation
- quantityUnit
- testId
- testMethod
- testMethodDescription
- priority
- assignedAnalyst
- overallResult
- resultId
- parameterName
- resultValue
- unit
- enteredBy
- approvedBy
- instrumentId
- name
- instrumentType
- manufacturer
- model
- serialNumber
context_file: json-ld/labvantage-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/labvantage/refs/heads/main/json-ld/labvantage-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Labvantage from LabVantage Solutions.
layout: jsonld
name: Labvantage Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: sio
  uri: http://semanticscience.org/resource/
- prefix: obo
  uri: http://purl.obolibrary.org/obo/
properties:
- container: ''
  name: Sample
  type: reference
- container: ''
  name: Test
  type: reference
- container: ''
  name: Result
  type: reference
- container: ''
  name: Instrument
  type: reference
- container: ''
  name: lotNumber
  type: string
- container: ''
  name: projectId
  type: reference
- container: ''
  name: productId
  type: string
- container: ''
  name: loginDate
  type: dateTime
- container: ''
  name: dueDate
  type: dateTime
- container: ''
  name: quantity
  type: decimal
- container: ''
  name: requestedDate
  type: dateTime
- container: ''
  name: completedDate
  type: dateTime
- container: ''
  name: resultNumeric
  type: decimal
- container: ''
  name: specMin
  type: decimal
- container: ''
  name: specMax
  type: decimal
- container: ''
  name: enteredDate
  type: dateTime
- container: ''
  name: approvedDate
  type: dateTime
- container: ''
  name: lastCalibrationDate
  type: date
- container: ''
  name: nextCalibrationDate
  type: date
property_count: 19
provider_name: LabVantage Solutions
provider_slug: labvantage
slug: labvantage-context
source_filename: labvantage-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"sio\": \"http://semanticscience.org/resource/\",\n    \"obo\": \"http://purl.obolibrary.org/obo/\",\n\n    \"Sample\": {\n      \"@id\": \"sio:SIO_000744\",\n      \"@type\": \"@id\",\n      \"@comment\": \"SIO:000744 = sample\"\n    },\n    \"Test\": {\n      \"@id\": \"sio:SIO_000654\",\n      \"@type\": \"@id\",\n      \"@comment\": \"SIO:000654 = assay\"\n    },\n    \"Result\": {\n      \"@id\": \"sio:SIO_000414\",\n      \"@type\": \"@id\",\n      \"@comment\": \"SIO:000414 = laboratory test result\"\n    },\n    \"Instrument\": {\n      \"@id\": \"sio:SIO_000956\",\n      \"@type\": \"@id\",\n      \"@comment\": \"SIO:000956 = laboratory instrument\"\n    },\n\n    \"sampleId\": \"schema:identifier\",\n    \"sampleNumber\": \"schema:identifier\",\n    \"sampleType\": \"schema:additionalType\"\
  ,\n    \"sampleDescription\": \"schema:description\",\n    \"status\": \"schema:actionStatus\",\n    \"lotNumber\": {\n      \"@id\": \"schema:serialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectId\": {\n      \"@id\": \"schema:isPartOf\",\n      \"@type\": \"@id\"\n    },\n    \"productId\": {\n      \"@id\": \"schema:productID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loginDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"loginUser\": \"schema:creator\",\n    \"dueDate\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"storageLocation\": \"schema:location\",\n    \"quantity\": {\n      \"@id\": \"schema:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"quantityUnit\": \"schema:unitCode\",\n\n    \"testId\": \"schema:identifier\",\n    \"testMethod\": \"schema:additionalType\",\n    \"testMethodDescription\": \"schema:description\",\n    \"priority\": \"schema:priority\"\
  ,\n    \"requestedDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedDate\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"assignedAnalyst\": \"schema:agent\",\n    \"overallResult\": \"schema:result\",\n\n    \"resultId\": \"schema:identifier\",\n    \"parameterName\": \"schema:name\",\n    \"resultValue\": \"schema:value\",\n    \"resultNumeric\": {\n      \"@id\": \"schema:value\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"unit\": \"schema:unitCode\",\n    \"specMin\": {\n      \"@id\": \"schema:minValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"specMax\": {\n      \"@id\": \"schema:maxValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"enteredBy\": \"schema:creator\",\n    \"enteredDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"approvedBy\": \"schema:accountablePerson\",\n    \"approvedDate\": {\n      \"@id\"\
  : \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"instrumentId\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"instrumentType\": \"schema:additionalType\",\n    \"manufacturer\": \"schema:manufacturer\",\n    \"model\": \"schema:model\",\n    \"serialNumber\": \"schema:serialNumber\",\n    \"lastCalibrationDate\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:date\"\n    },\n    \"nextCalibrationDate\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/labvantage/refs/heads/main/json-ld/labvantage-context.jsonld
tags:
- Pharma
- Laboratory
- LIMS
- Quality
- GxP
- JSON-LD
- Linked Data
- Semantic Web
---
