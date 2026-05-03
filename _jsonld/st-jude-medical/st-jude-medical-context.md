---
class_count: 27
classes:
- MedicalDevice
- ImplantableDevice
- CardiacDevice
- ICD
- CRTDevice
- Pacemaker
- Patient
- Clinic
- Observation
- deviceId
- serialNumber
- model
- remoteMonitoring
- transmitterModel
- connectionType
- batteryStatus
- batteryVoltage
- leadMeasurements
- leadLocation
- impedance
- threshold
- sensing
- CardiacAlert
- alertType
- severity
- MerlinNet
- MerlinAtHome
context_file: json-ld/st-jude-medical-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/st-jude-medical/refs/heads/main/json-ld/st-jude-medical-context.jsonld
description: JSON-LD context defining the semantic vocabulary for St Jude Medical from St. Jude Medical.
layout: jsonld
name: St Jude Medical Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fhir
  uri: http://hl7.org/fhir/
- prefix: med
  uri: https://github.com/api-evangelist/st-jude-medical#
properties:
- container: ''
  name: manufacturer
  type: reference
- container: ''
  name: implantDate
  type: schema:Date
- container: ''
  name: patientId
  type: reference
- container: ''
  name: lastTransmissionDate
  type: schema:DateTime
- container: ''
  name: estimatedReplacementDate
  type: schema:Date
- container: ''
  name: detectedDate
  type: schema:DateTime
property_count: 6
provider_name: St. Jude Medical
provider_slug: st-jude-medical
slug: st-jude-medical-context
source_filename: st-jude-medical-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fhir\": \"http://hl7.org/fhir/\",\n    \"med\": \"https://github.com/api-evangelist/st-jude-medical#\",\n\n    \"MedicalDevice\": \"schema:MedicalDevice\",\n    \"ImplantableDevice\": \"med:ImplantableDevice\",\n    \"CardiacDevice\": \"med:CardiacDevice\",\n    \"ICD\": \"med:ImplantableCardioverterDefibrillator\",\n    \"CRTDevice\": \"med:CardiacResynchronizationTherapyDevice\",\n    \"Pacemaker\": \"med:Pacemaker\",\n\n    \"Patient\": \"fhir:Patient\",\n    \"Clinic\": \"schema:MedicalClinic\",\n    \"Observation\": \"fhir:Observation\",\n\n    \"deviceId\": \"schema:identifier\",\n    \"serialNumber\": \"schema:serialNumber\",\n    \"model\": \"schema:model\",\n    \"manufacturer\": {\n      \"@id\": \"schema:manufacturer\",\n      \"@type\": \"@id\"\n    },\n    \"implantDate\": {\n      \"@id\": \"med:implantDate\",\n      \"@type\": \"schema:Date\"\n    },\n    \"patientId\"\
  : {\n      \"@id\": \"fhir:subject\",\n      \"@type\": \"@id\"\n    },\n\n    \"remoteMonitoring\": \"med:remoteMonitoring\",\n    \"transmitterModel\": \"med:transmitterModel\",\n    \"lastTransmissionDate\": {\n      \"@id\": \"med:lastTransmission\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"connectionType\": \"med:connectionType\",\n\n    \"batteryStatus\": \"med:batteryStatus\",\n    \"batteryVoltage\": \"med:batteryVoltage\",\n    \"estimatedReplacementDate\": {\n      \"@id\": \"med:estimatedReplacementDate\",\n      \"@type\": \"schema:Date\"\n    },\n\n    \"leadMeasurements\": \"med:leadMeasurements\",\n    \"leadLocation\": \"med:leadLocation\",\n    \"impedance\": \"med:impedance\",\n    \"threshold\": \"med:pacingThreshold\",\n    \"sensing\": \"med:sensingAmplitude\",\n\n    \"CardiacAlert\": \"med:CardiacAlert\",\n    \"alertType\": \"med:alertType\",\n    \"severity\": \"med:alertSeverity\",\n    \"detectedDate\": {\n      \"@id\": \"med:detectedDate\",\n  \
  \    \"@type\": \"schema:DateTime\"\n    },\n\n    \"MerlinNet\": \"med:MerlinPatientCareNetwork\",\n    \"MerlinAtHome\": \"med:MerlinAtHomeTransmitter\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/st-jude-medical/refs/heads/main/json-ld/st-jude-medical-context.jsonld
tags:
- Cardiac
- Cardiovascular
- Healthcare
- Medical Devices
- Patient Monitoring
- Remote Care
- JSON-LD
- Linked Data
- Semantic Web
---
