---
class_count: 27
classes:
- EPCISEvent
- ObjectEvent
- AggregationEvent
- TransactionEvent
- TransformationEvent
- AssociationEvent
- eventTimeZoneOffset
- epcList
- action
- bizStep
- disposition
- readPoint
- bizLocation
- bizTransactionList
- sensorElementList
- epc
- epcUrn
- rssi
- antennaId
- readerSerial
- timestamp
- tagType
- EPC
- SGTIN
- SSCC
- SGLN
- GLN
context_file: json-ld/rfid-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rfid/refs/heads/main/json-ld/rfid-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rfid from RFID.
layout: jsonld
name: Rfid Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: epcis
  uri: https://ref.gs1.org/standards/epcis/
- prefix: cbv
  uri: https://ref.gs1.org/cbv/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rfid
  uri: https://www.rfidjournal.com/vocab/
properties:
- container: ''
  name: eventTime
  type: dateTime
property_count: 1
provider_name: RFID
provider_slug: rfid
slug: rfid-context
source_filename: rfid-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"epcis\": \"https://ref.gs1.org/standards/epcis/\",\n    \"cbv\": \"https://ref.gs1.org/cbv/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rfid\": \"https://www.rfidjournal.com/vocab/\",\n\n    \"EPCISEvent\": \"epcis:EPCISEvent\",\n    \"ObjectEvent\": \"epcis:ObjectEvent\",\n    \"AggregationEvent\": \"epcis:AggregationEvent\",\n    \"TransactionEvent\": \"epcis:TransactionEvent\",\n    \"TransformationEvent\": \"epcis:TransformationEvent\",\n    \"AssociationEvent\": \"epcis:AssociationEvent\",\n\n    \"eventTime\": {\n      \"@id\": \"epcis:eventTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"eventTimeZoneOffset\": \"epcis:eventTimeZoneOffset\",\n    \"epcList\": \"epcis:epcList\",\n    \"action\": \"epcis:action\",\n    \"bizStep\": \"epcis:bizStep\",\n    \"disposition\": \"epcis:disposition\",\n    \"readPoint\": \"epcis:readPoint\",\n    \"bizLocation\"\
  : \"epcis:bizLocation\",\n    \"bizTransactionList\": \"epcis:bizTransactionList\",\n    \"sensorElementList\": \"epcis:sensorElementList\",\n\n    \"epc\": \"rfid:epc\",\n    \"epcUrn\": \"rfid:epcUrn\",\n    \"rssi\": \"rfid:rssi\",\n    \"antennaId\": \"rfid:antennaId\",\n    \"readerSerial\": \"rfid:readerSerial\",\n    \"timestamp\": \"schema:dateCreated\",\n    \"tagType\": \"rfid:tagType\",\n\n    \"EPC\": \"rfid:EPC\",\n    \"SGTIN\": \"rfid:SGTIN\",\n    \"SSCC\": \"rfid:SSCC\",\n    \"SGLN\": \"rfid:SGLN\",\n    \"GLN\": \"rfid:GLN\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rfid/refs/heads/main/json-ld/rfid-context.jsonld
tags:
- RFID
- IoT
- Supply Chain
- Inventory Management
- Asset Tracking
- GS1
- EPCIS
- JSON-LD
- Linked Data
- Semantic Web
---
