---
class_count: 6
classes:
- GetStoresUnderAccountRequest
- GetStoresUnderAccountResponse
- GetTerminalDetailsRequest
- GetTerminalDetailsResponse
- GetTerminalsUnderAccountRequest
- GetTerminalsUnderAccountResponse
context_file: json-ld/adyen-pos-terminal-get-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-pos-terminal-get-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Pos Terminal Get from Adyen.
layout: jsonld
name: Adyen Pos Terminal Get Context
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
  name: companyAccount
  type: string
- container: ''
  name: merchantAccount
  type: string
- container: set
  name: stores
  type: string
- container: ''
  name: terminal
  type: string
- container: ''
  name: bluetoothIp
  type: string
- container: ''
  name: bluetoothMac
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: deviceModel
  type: string
- container: ''
  name: dhcpEnabled
  type: boolean
- container: ''
  name: displayLabel
  type: string
- container: ''
  name: ethernetIp
  type: string
- container: ''
  name: ethernetMac
  type: string
- container: ''
  name: firmwareVersion
  type: string
- container: ''
  name: iccid
  type: string
- container: ''
  name: lastActivityDateTime
  type: dateTime
- container: ''
  name: lastTransactionDateTime
  type: dateTime
- container: ''
  name: linkNegotiation
  type: string
- container: ''
  name: merchantInventory
  type: boolean
- container: ''
  name: permanentTerminalId
  type: string
- container: ''
  name: serialNumber
  type: string
- container: ''
  name: simStatus
  type: string
- container: ''
  name: store
  type: string
- container: ''
  name: storeDetails
  type: string
- container: ''
  name: terminalStatus
  type: string
- container: ''
  name: wifiIp
  type: string
- container: ''
  name: wifiMac
  type: string
- container: set
  name: inventoryTerminals
  type: string
- container: set
  name: merchantAccounts
  type: string
property_count: 28
provider_name: Adyen
provider_slug: adyen
slug: adyen-pos-terminal-get-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GetStoresUnderAccountRequest\": \"adyen:GetStoresUnderAccountRequest\",\n    \"GetStoresUnderAccountResponse\": \"adyen:GetStoresUnderAccountResponse\",\n    \"GetTerminalDetailsRequest\": \"adyen:GetTerminalDetailsRequest\",\n    \"GetTerminalDetailsResponse\": \"adyen:GetTerminalDetailsResponse\",\n    \"GetTerminalsUnderAccountRequest\": \"adyen:GetTerminalsUnderAccountRequest\",\n    \"GetTerminalsUnderAccountResponse\": \"adyen:GetTerminalsUnderAccountResponse\",\n    \"companyAccount\": {\n      \"@id\": \"adyen:companyAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stores\": {\n      \"@id\": \"adyen:stores\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminal\": {\n      \"@id\": \"adyen:terminal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bluetoothIp\": {\n      \"@id\": \"adyen:bluetoothIp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bluetoothMac\": {\n      \"@id\": \"adyen:bluetoothMac\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"adyen:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceModel\": {\n      \"@id\": \"adyen:deviceModel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dhcpEnabled\": {\n      \"@id\": \"adyen:dhcpEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"displayLabel\": {\n      \"@id\": \"adyen:displayLabel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ethernetIp\": {\n      \"@id\": \"adyen:ethernetIp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ethernetMac\": {\n      \"@id\": \"adyen:ethernetMac\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"firmwareVersion\": {\n      \"@id\": \"adyen:firmwareVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iccid\": {\n      \"@id\": \"adyen:iccid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastActivityDateTime\": {\n      \"@id\": \"adyen:lastActivityDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastTransactionDateTime\": {\n      \"@id\": \"adyen:lastTransactionDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"linkNegotiation\": {\n      \"@id\": \"adyen:linkNegotiation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantInventory\": {\n      \"@id\": \"adyen:merchantInventory\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"permanentTerminalId\": {\n      \"@id\": \"adyen:permanentTerminalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serialNumber\": {\n      \"@id\": \"adyen:serialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"simStatus\": {\n      \"@id\": \"adyen:simStatus\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"store\": {\n      \"@id\": \"adyen:store\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storeDetails\": {\n      \"@id\": \"adyen:storeDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminalStatus\": {\n      \"@id\": \"adyen:terminalStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wifiIp\": {\n      \"@id\": \"adyen:wifiIp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wifiMac\": {\n      \"@id\": \"adyen:wifiMac\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inventoryTerminals\": {\n      \"@id\": \"adyen:inventoryTerminals\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccounts\": {\n      \"@id\": \"adyen:merchantAccounts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-pos-terminal-get-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
