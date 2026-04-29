---
api_specs:
- filename: aruba-central-api.yml
  format: yaml
  label: Aruba Central API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aruba/refs/heads/main/openapi/aruba-central-api.yml
class_count: 0
classes: []
context_file: json-ld/aruba-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aruba/refs/heads/main/json-ld/aruba-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aruba from Aruba.
layout: jsonld
name: Aruba Context
namespaces:
- prefix: aruba
  uri: https://developer.arubanetworks.com/schemas/
- prefix: network
  uri: https://developer.arubanetworks.com/schemas/network#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Device
  type: ''
- container: ''
  name: AccessPoint
  type: ''
- container: ''
  name: Radio
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: Site
  type: ''
- container: ''
  name: Client
  type: ''
- container: ''
  name: Gateway
  type: ''
- container: ''
  name: Network
  type: ''
property_count: 8
provider_name: Aruba
provider_slug: aruba
slug: aruba-context
source_filename: aruba-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"aruba\": \"https://developer.arubanetworks.com/schemas/\",\n    \"network\": \"https://developer.arubanetworks.com/schemas/network#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Device\": {\n      \"@id\": \"aruba:Device\",\n      \"@context\": {\n        \"serial\": {\n          \"@id\": \"aruba:serial\",\n          \"@type\": \"xsd:string\"\n        },\n        \"macaddr\": {\n          \"@id\": \"aruba:macaddr\",\n          \"@type\": \"xsd:string\"\n        },\n        \"device_type\": {\n          \"@id\": \"aruba:deviceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"model\": {\n          \"@id\": \"aruba:model\",\n          \"@type\": \"xsd:string\"\n        },\n        \"firmware_version\": {\n          \"@id\": \"aruba:firmwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"aruba:operationalStatus\",\n\
  \          \"@type\": \"xsd:string\"\n        },\n        \"ip_address\": {\n          \"@id\": \"aruba:ipAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"group_name\": {\n          \"@id\": \"aruba:groupName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"site\": {\n          \"@id\": \"aruba:site\",\n          \"@type\": \"xsd:string\"\n        },\n        \"labels\": {\n          \"@id\": \"aruba:labels\",\n          \"@container\": \"@set\"\n        },\n        \"customer_id\": {\n          \"@id\": \"aruba:customerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"customer_name\": {\n          \"@id\": \"aruba:customerName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"client_count\": {\n          \"@id\": \"aruba:clientCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"uptime\": {\n      \
  \    \"@id\": \"aruba:uptimeSeconds\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"cpu_utilization\": {\n          \"@id\": \"aruba:cpuUtilization\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"mem_total\": {\n          \"@id\": \"aruba:memoryTotal\",\n          \"@type\": \"xsd:long\"\n        },\n        \"mem_free\": {\n          \"@id\": \"aruba:memoryFree\",\n          \"@type\": \"xsd:long\"\n        },\n        \"last_modified\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AccessPoint\": {\n      \"@id\": \"aruba:AccessPoint\",\n      \"@context\": {\n        \"serial\": {\n          \"@id\": \"aruba:serial\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"macaddr\": {\n          \"@id\": \"aruba:macaddr\",\n          \"@type\": \"xsd:string\"\n    \
  \    },\n        \"model\": {\n          \"@id\": \"aruba:model\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"aruba:operationalStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ap_deployment_mode\": {\n          \"@id\": \"aruba:deploymentMode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"swarm_id\": {\n          \"@id\": \"aruba:swarmId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"swarm_name\": {\n          \"@id\": \"aruba:swarmName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mesh_role\": {\n          \"@id\": \"aruba:meshRole\",\n          \"@type\": \"xsd:string\"\n        },\n        \"radios\": {\n          \"@id\": \"aruba:hasRadio\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Radio\": {\n      \"@id\": \"aruba:Radio\",\n      \"@context\": {\n        \"index\": {\n          \"@id\": \"aruba:radioIndex\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"band\": {\n          \"@id\": \"aruba:frequencyBand\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"channel\": {\n          \"@id\": \"aruba:channel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"power\": {\n          \"@id\": \"aruba:transmitPower\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"utilization\": {\n          \"@id\": \"aruba:channelUtilization\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"noise_floor\": {\n          \"@id\": \"aruba:noiseFloor\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"status\": {\n          \"@id\": \"aruba:operationalStatus\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"aruba:ConfigurationGroup\",\n      \"@context\": {\n        \"group\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"group_properties\"\
  : {\n          \"@id\": \"aruba:groupProperties\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Site\": {\n      \"@id\": \"aruba:Site\",\n      \"@context\": {\n        \"site_id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"site_name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address\": {\n          \"@id\": \"schema:streetAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"zipcode\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"longitude\": {\n          \"@id\": \"schema:longitude\",\n          \"@type\": \"xsd:double\"\n        },\n        \"latitude\": {\n          \"@id\": \"schema:latitude\",\n          \"@type\": \"xsd:double\"\n        },\n        \"tags\": {\n          \"@id\": \"aruba:tags\",\n          \"@container\": \"@set\"\n        },\n        \"associated_device_count\": {\n          \"@id\": \"aruba:associatedDeviceCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Client\": {\n      \"@id\": \"aruba:NetworkClient\",\n      \"@context\": {\n        \"macaddr\": {\n          \"@id\": \"aruba:macaddr\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ip_address\": {\n          \"@id\": \"aruba:ipAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"os_type\": {\n          \"@id\": \"aruba:operatingSystem\",\n          \"\
  @type\": \"xsd:string\"\n        },\n        \"connection\": {\n          \"@id\": \"aruba:connectionType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"network\": {\n          \"@id\": \"aruba:networkName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"signal_strength\": {\n          \"@id\": \"aruba:signalStrength\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"associated_device\": {\n          \"@id\": \"aruba:associatedDevice\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Gateway\": {\n      \"@id\": \"aruba:Gateway\",\n      \"@context\": {\n        \"serial\": {\n          \"@id\": \"aruba:serial\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"model\": {\n          \"@id\": \"aruba:model\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"aruba:operationalStatus\"\
  ,\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Network\": {\n      \"@id\": \"aruba:WirelessNetwork\",\n      \"@context\": {\n        \"essid\": {\n          \"@id\": \"aruba:essid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"aruba:networkType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"client_count\": {\n          \"@id\": \"aruba:clientCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aruba/refs/heads/main/json-ld/aruba-context.jsonld
tags:
- Cloud
- Infrastructure
- Network Management
- Networking
- SD-WAN
- Security
- Switches
- Wireless
- JSON-LD
- Linked Data
- Semantic Web
---
