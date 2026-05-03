---
api_specs:
- filename: supermicro-redfish-openapi.yml
  format: yaml
  label: Supermicro Redfish API
  slug: redfish-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/openapi/supermicro-redfish-openapi.yml
class_count: 11
classes:
- ComputerSystem
- Chassis
- Manager
- Session
- Account
- Storage
- EventSubscription
- SoftwareInventory
- Status
- Health
- PowerState
context_file: json-ld/super-micro-computer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/json-ld/super-micro-computer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Super Micro Computer from Super Micro Computer.
layout: jsonld
name: Super Micro Computer Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dmtf
  uri: https://redfish.dmtf.org/schemas/v1/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Id
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: Manufacturer
  type: string
- container: ''
  name: Model
  type: string
- container: ''
  name: SerialNumber
  type: string
- container: ''
  name: BIOSVersion
  type: string
- container: ''
  name: FirmwareVersion
  type: string
- container: ''
  name: PowerConsumedWatts
  type: decimal
- container: ''
  name: ReadingCelsius
  type: decimal
- container: ''
  name: UserName
  type: string
- container: ''
  name: RoleId
  type: string
- container: ''
  name: Destination
  type: anyURI
- container: ''
  name: RedfishVersion
  type: string
property_count: 14
provider_name: Super Micro Computer
provider_slug: super-micro-computer
slug: super-micro-computer-context
source_filename: super-micro-computer-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://www.supermicro.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"dmtf\": \"https://redfish.dmtf.org/schemas/v1/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ComputerSystem\": \"dmtf:ComputerSystem\",\n    \"Chassis\": \"dmtf:Chassis\",\n    \"Manager\": \"dmtf:Manager\",\n    \"Session\": \"dmtf:Session\",\n    \"Account\": \"dmtf:ManagerAccount\",\n    \"Storage\": \"dmtf:Storage\",\n    \"EventSubscription\": \"dmtf:EventSubscription\",\n    \"SoftwareInventory\": \"dmtf:SoftwareInventory\",\n    \"Id\": {\n      \"@id\": \"dmtf:Resource.Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"dmtf:Resource.Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"dmtf:Resource.Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": \"dmtf:Resource.Status\",\n    \"Health\": \"dmtf:Resource.Health\",\n    \"PowerState\"\
  : \"dmtf:ComputerSystem.PowerState\",\n    \"Manufacturer\": {\n      \"@id\": \"schema:manufacturer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Model\": {\n      \"@id\": \"schema:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SerialNumber\": {\n      \"@id\": \"schema:serialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BIOSVersion\": {\n      \"@id\": \"dmtf:ComputerSystem.BiosVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FirmwareVersion\": {\n      \"@id\": \"dmtf:SoftwareInventory.Version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PowerConsumedWatts\": {\n      \"@id\": \"dmtf:Power.PowerConsumedWatts\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ReadingCelsius\": {\n      \"@id\": \"dmtf:Thermal.ReadingCelsius\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"UserName\": {\n      \"@id\": \"dmtf:ManagerAccount.UserName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleId\": {\n      \"@id\": \"dmtf:ManagerAccount.RoleId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"Destination\": {\n      \"@id\": \"dmtf:EventDestination.Destination\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"RedfishVersion\": {\n      \"@id\": \"dmtf:ServiceRoot.RedfishVersion\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/json-ld/super-micro-computer-context.jsonld
tags:
- Servers
- Data Center
- Hardware
- Server Management
- Redfish
- BMC
- IPMI
- Fortune 500
- Infrastructure
- Cloud
- JSON-LD
- Linked Data
- Semantic Web
---
