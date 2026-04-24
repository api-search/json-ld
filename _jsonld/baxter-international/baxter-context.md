---
class_count: 0
classes: []
context_file: json-ld/baxter-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/baxter-international/refs/heads/main/json-ld/baxter-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Baxter from Baxter International.
layout: jsonld
name: Baxter Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fhir
  uri: http://hl7.org/fhir/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: MedicalDevice
  type: reference
- container: ''
  name: DeviceObservation
  type: reference
- container: ''
  name: deviceId
  type: string
- container: ''
  name: deviceType
  type: string
- container: ''
  name: manufacturer
  type: reference
- container: ''
  name: modelNumber
  type: string
- container: ''
  name: serialNumber
  type: string
- container: ''
  name: patientId
  type: string
- container: ''
  name: observationTime
  type: dateTime
- container: ''
  name: value
  type: decimal
- container: ''
  name: unit
  type: string
- container: ''
  name: status
  type: string
property_count: 12
provider_name: Baxter International
provider_slug: baxter-international
slug: baxter-context
tags:
- Healthcare
- Medical Devices
- Infusion Pumps
- Patient Monitoring
- Connected Health
- JSON-LD
- Linked Data
- Semantic Web
---
