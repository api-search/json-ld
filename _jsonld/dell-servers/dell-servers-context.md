---
api_specs:
- filename: dell-servers-idrac-redfish-openapi.yml
  format: yaml
  label: Dell iDRAC Redfish REST API
  slug: dell-servers-idrac-redfish
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dell-servers/refs/heads/main/openapi/dell-servers-idrac-redfish-openapi.yml
- filename: dell-servers-openmanage-enterprise-openapi.yml
  format: yaml
  label: Dell OpenManage Enterprise API
  slug: dell-servers-openmanage-enterprise
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dell-servers/refs/heads/main/openapi/dell-servers-openmanage-enterprise-openapi.yml
class_count: 10
classes:
- ComputerSystem
- Chassis
- Manager
- Device
- Group
- Job
- Alert
- FirmwareInventory
- MetricReport
- EventSubscription
context_file: json-ld/dell-servers-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dell-servers/refs/heads/main/json-ld/dell-servers-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dell Servers from Dell Servers.
layout: jsonld
name: Dell Servers Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dell
  uri: https://schema.dell.com/servers/
properties:
- container: ''
  name: id
  type: schema:Text
- container: ''
  name: name
  type: schema:Text
- container: ''
  name: Model
  type: schema:Text
- container: ''
  name: Manufacturer
  type: schema:Text
- container: ''
  name: SerialNumber
  type: schema:Text
- container: ''
  name: PartNumber
  type: schema:Text
- container: ''
  name: Status
  type: schema:Text
- container: ''
  name: PowerState
  type: schema:Text
- container: ''
  name: BiosVersion
  type: schema:Text
- container: ''
  name: FirmwareVersion
  type: schema:Text
- container: ''
  name: MACAddress
  type: schema:Text
- container: ''
  name: IPv4Addresses
  type: schema:Text
property_count: 12
provider_name: Dell Servers
provider_slug: dell-servers
slug: dell-servers-context
source_filename: dell-servers-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.dell.com/servers/\",\n    \"schema\": \"https://schema.org/\",\n    \"dell\": \"https://schema.dell.com/servers/\",\n    \"ComputerSystem\": \"dell:ComputerSystem\",\n    \"Chassis\": \"dell:Chassis\",\n    \"Manager\": \"dell:Manager\",\n    \"Device\": \"dell:Device\",\n    \"Group\": \"dell:Group\",\n    \"Job\": \"dell:Job\",\n    \"Alert\": \"dell:Alert\",\n    \"FirmwareInventory\": \"dell:FirmwareInventory\",\n    \"MetricReport\": \"dell:MetricReport\",\n    \"EventSubscription\": \"dell:EventSubscription\",\n    \"id\": {\"@id\": \"schema:identifier\", \"@type\": \"schema:Text\"},\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"schema:Text\"},\n    \"Model\": {\"@id\": \"dell:model\", \"@type\": \"schema:Text\"},\n    \"Manufacturer\": {\"@id\": \"schema:manufacturer\", \"@type\": \"schema:Text\"},\n    \"SerialNumber\": {\"@id\": \"schema:serialNumber\", \"@type\": \"schema:Text\"\
  },\n    \"PartNumber\": {\"@id\": \"dell:partNumber\", \"@type\": \"schema:Text\"},\n    \"Status\": {\"@id\": \"dell:status\", \"@type\": \"schema:Text\"},\n    \"PowerState\": {\"@id\": \"dell:powerState\", \"@type\": \"schema:Text\"},\n    \"BiosVersion\": {\"@id\": \"dell:biosVersion\", \"@type\": \"schema:Text\"},\n    \"FirmwareVersion\": {\"@id\": \"dell:firmwareVersion\", \"@type\": \"schema:Text\"},\n    \"MACAddress\": {\"@id\": \"dell:macAddress\", \"@type\": \"schema:Text\"},\n    \"IPv4Addresses\": {\"@id\": \"dell:ipv4Addresses\", \"@type\": \"schema:Text\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dell-servers/refs/heads/main/json-ld/dell-servers-context.jsonld
tags:
- Hardware
- Infrastructure
- Management
- Monitoring
- Servers
- JSON-LD
- Linked Data
- Semantic Web
---
