---
class_count: 11
classes:
- uuid
- rssi
- txPowerLevel
- serviceUUIDs
- manufacturerData
- companyId
- connectable
- addressType
- characteristics
- localName
- address
context_file: json-ld/ble-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ble/refs/heads/main/json-ld/ble-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ble from BLE.
layout: jsonld
name: Ble Context
namespaces:
- prefix: bluetooth
  uri: https://www.bluetooth.com/ontology/
properties: []
property_count: 0
provider_name: BLE
provider_slug: ble
slug: ble-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"bluetooth\": \"https://www.bluetooth.com/ontology/\",\n    \"uuid\": \"bluetooth:uuid\",\n    \"rssi\": \"bluetooth:rssi\",\n    \"txPowerLevel\": \"bluetooth:txPowerLevel\",\n    \"serviceUUIDs\": \"bluetooth:serviceUUIDs\",\n    \"manufacturerData\": \"bluetooth:manufacturerData\",\n    \"companyId\": \"bluetooth:companyId\",\n    \"connectable\": \"bluetooth:connectable\",\n    \"addressType\": \"bluetooth:addressType\",\n    \"characteristics\": \"bluetooth:characteristics\",\n    \"localName\": \"name\",\n    \"address\": \"bluetooth:deviceAddress\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ble/refs/heads/main/json-ld/ble-context.jsonld
tags:
- BLE
- Bluetooth
- Embedded
- IoT
- Protocols
- Standards
- Wireless
- JSON-LD
- Linked Data
- Semantic Web
---
