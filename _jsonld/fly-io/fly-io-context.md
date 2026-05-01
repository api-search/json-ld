---
api_specs:
- filename: fly-io-machines-api-openapi.yml
  format: yaml
  label: Fly.io Machines API
  slug: machines-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fly-io/refs/heads/main/openapi/fly-io-machines-api-openapi.yml
- filename: fly-io-extensions-api-openapi.yml
  format: yaml
  label: Fly.io Extensions API
  slug: extensions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fly-io/refs/heads/main/openapi/fly-io-extensions-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/fly-io-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/fly-io/refs/heads/main/json-ld/fly-io-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Fly Io from fly-io.
layout: jsonld
name: Fly Io Context
namespaces:
- prefix: flyio
  uri: https://fly.io/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Machine
  type: ''
- container: ''
  name: MachineConfig
  type: ''
- container: ''
  name: MachineGuest
  type: ''
- container: ''
  name: MachineService
  type: ''
- container: ''
  name: MachinePort
  type: ''
- container: ''
  name: Volume
  type: ''
- container: ''
  name: VolumeSnapshot
  type: ''
- container: ''
  name: App
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: ExtensionResource
  type: ''
- container: ''
  name: MachineCheck
  type: ''
property_count: 11
provider_name: fly-io
provider_slug: fly-io
slug: fly-io-context
source_filename: fly-io-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"flyio\": \"https://fly.io/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Machine\": {\n      \"@id\": \"flyio:Machine\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"state\": {\n          \"@id\": \"flyio:machineState\"\n        },\n        \"region\": {\n          \"@id\": \"flyio:region\"\n        },\n        \"instance_id\": {\n          \"@id\": \"flyio:instanceId\"\n        },\n        \"private_ip\": {\n          \"@id\": \"flyio:privateIpAddress\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"config\": {\n \
  \         \"@id\": \"flyio:machineConfig\"\n        }\n      }\n    },\n\n    \"MachineConfig\": {\n      \"@id\": \"flyio:MachineConfig\",\n      \"@context\": {\n        \"image\": {\n          \"@id\": \"flyio:containerImage\"\n        },\n        \"guest\": {\n          \"@id\": \"flyio:guestSpec\"\n        },\n        \"env\": {\n          \"@id\": \"flyio:environmentVariables\"\n        },\n        \"services\": {\n          \"@id\": \"flyio:networkServices\",\n          \"@container\": \"@set\"\n        },\n        \"mounts\": {\n          \"@id\": \"flyio:volumeMounts\",\n          \"@container\": \"@set\"\n        },\n        \"schedule\": {\n          \"@id\": \"schema:schedule\"\n        },\n        \"auto_destroy\": {\n          \"@id\": \"flyio:autoDestroy\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"metadata\": {\n          \"@id\": \"flyio:machineMetadata\"\n        }\n      }\n    },\n\n    \"MachineGuest\": {\n      \"@id\": \"flyio:MachineGuest\",\n\
  \      \"@context\": {\n        \"cpus\": {\n          \"@id\": \"flyio:cpuCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"memory_mb\": {\n          \"@id\": \"flyio:memoryMb\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"cpu_kind\": {\n          \"@id\": \"flyio:cpuKind\"\n        }\n      }\n    },\n\n    \"MachineService\": {\n      \"@id\": \"flyio:MachineService\",\n      \"@context\": {\n        \"protocol\": {\n          \"@id\": \"flyio:networkProtocol\"\n        },\n        \"internal_port\": {\n          \"@id\": \"schema:portNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"ports\": {\n          \"@id\": \"flyio:externalPorts\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"MachinePort\": {\n      \"@id\": \"flyio:MachinePort\",\n      \"@context\": {\n        \"port\": {\n          \"@id\": \"schema:portNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"handlers\": {\n\
  \          \"@id\": \"flyio:protocolHandlers\",\n          \"@container\": \"@set\"\n        },\n        \"force_https\": {\n          \"@id\": \"flyio:forceHttps\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Volume\": {\n      \"@id\": \"flyio:Volume\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"state\": {\n          \"@id\": \"flyio:volumeState\"\n        },\n        \"size_gb\": {\n          \"@id\": \"flyio:sizeGb\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"region\": {\n          \"@id\": \"flyio:region\"\n        },\n        \"zone\": {\n          \"@id\": \"flyio:availabilityZone\"\n        },\n        \"encrypted\": {\n          \"@id\": \"flyio:isEncrypted\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"attached_machine_id\": {\n          \"@id\": \"flyio:attachedMachineId\"\n        },\n        \"filesystem_type\": {\n      \
  \    \"@id\": \"flyio:filesystemType\"\n        },\n        \"snapshot_retention\": {\n          \"@id\": \"flyio:snapshotRetentionDays\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"VolumeSnapshot\": {\n      \"@id\": \"flyio:VolumeSnapshot\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"size\": {\n          \"@id\": \"schema:fileSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"digest\": {\n          \"@id\": \"flyio:contentDigest\"\n        },\n        \"status\": {\n          \"@id\": \"flyio:snapshotStatus\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"App\": {\n      \"@id\": \"flyio:App\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\
  \n        },\n        \"status\": {\n          \"@id\": \"flyio:appStatus\"\n        },\n        \"machine_count\": {\n          \"@id\": \"flyio:machineCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"volume_count\": {\n          \"@id\": \"flyio:volumeCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"network\": {\n          \"@id\": \"flyio:privateNetwork\"\n        },\n        \"organization\": {\n          \"@id\": \"flyio:organization\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"flyio:Organization\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"slug\": {\n          \"@id\": \"flyio:organizationSlug\"\n        }\n      }\n    },\n\n    \"ExtensionResource\": {\n      \"@id\": \"flyio:ExtensionResource\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"status\": {\n          \"\
  @id\": \"flyio:extensionStatus\"\n        },\n        \"config\": {\n          \"@id\": \"flyio:extensionConfig\"\n        },\n        \"organization_id\": {\n          \"@id\": \"flyio:organizationId\"\n        },\n        \"fly_app_name\": {\n          \"@id\": \"flyio:flyAppName\"\n        }\n      }\n    },\n\n    \"MachineCheck\": {\n      \"@id\": \"flyio:MachineCheck\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"flyio:checkType\"\n        },\n        \"port\": {\n          \"@id\": \"schema:portNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"interval\": {\n          \"@id\": \"schema:repeatFrequency\"\n        },\n        \"timeout\": {\n          \"@id\": \"flyio:checkTimeout\"\n        },\n        \"path\": {\n          \"@id\": \"schema:path\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/fly-io/refs/heads/main/json-ld/fly-io-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
