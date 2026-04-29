---
class_count: 1
classes:
- DeviceInfo
context_file: json-ld/adyen-configuration-device-info-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-device-info-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Device Info from Adyen.
layout: jsonld
name: Adyen Configuration Device Info Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: cardCaptureTechnology
  type: string
- container: ''
  name: deviceName
  type: string
- container: ''
  name: formFactor
  type: string
- container: ''
  name: imei
  type: string
- container: ''
  name: isoDeviceType
  type: string
- container: ''
  name: msisdn
  type: string
- container: ''
  name: osName
  type: string
- container: ''
  name: osVersion
  type: string
- container: set
  name: paymentTypes
  type: string
- container: ''
  name: serialNumber
  type: string
- container: ''
  name: storageTechnology
  type: string
property_count: 11
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-device-info-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DeviceInfo\": \"adyen:DeviceInfo\",\n    \"cardCaptureTechnology\": {\n      \"@id\": \"adyen:cardCaptureTechnology\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceName\": {\n      \"@id\": \"adyen:deviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"formFactor\": {\n      \"@id\": \"adyen:formFactor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imei\": {\n      \"@id\": \"adyen:imei\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isoDeviceType\": {\n      \"@id\": \"adyen:isoDeviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"msisdn\": {\n      \"@id\": \"adyen:msisdn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"osName\": {\n      \"@id\": \"adyen:osName\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"osVersion\": {\n      \"@id\": \"adyen:osVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentTypes\": {\n      \"@id\": \"adyen:paymentTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serialNumber\": {\n      \"@id\": \"adyen:serialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storageTechnology\": {\n      \"@id\": \"adyen:storageTechnology\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-device-info-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
