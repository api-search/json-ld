---
class_count: 0
classes: []
context_file: json-ld/citrix-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/citrix/refs/heads/main/json-ld/citrix-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Citrix from Citrix.
layout: jsonld
name: Citrix Context
namespaces:
- prefix: citrix
  uri: https://developer.citrix.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: MachineCatalog
  type: ''
- container: ''
  name: DeliveryGroup
  type: ''
- container: ''
  name: Machine
  type: ''
- container: ''
  name: Session
  type: ''
- container: ''
  name: Application
  type: ''
- container: ''
  name: ServicePrincipal
  type: ''
- container: ''
  name: ResourceLocation
  type: ''
- container: ''
  name: Device
  type: ''
property_count: 8
provider_name: Citrix
provider_slug: citrix
slug: citrix-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"citrix\": \"https://developer.citrix.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"MachineCatalog\": {\n      \"@id\": \"citrix:MachineCatalog\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"allocationType\": \"citrix:allocationType\",\n        \"provisioningType\": \"citrix:provisioningType\",\n        \"sessionSupport\": \"citrix:sessionSupport\",\n        \"machineCount\": {\n          \"@id\": \"citrix:machineCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"DeliveryGroup\": {\n      \"@id\": \"citrix:DeliveryGroup\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"enabled\": \"citrix:enabled\",\n        \"deliveryType\"\
  : \"citrix:deliveryType\",\n        \"totalMachines\": {\n          \"@id\": \"citrix:totalMachines\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Machine\": {\n      \"@id\": \"citrix:Machine\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"dnsName\": \"citrix:dnsName\",\n        \"registrationState\": \"citrix:registrationState\",\n        \"powerState\": \"citrix:powerState\",\n        \"inMaintenanceMode\": {\n          \"@id\": \"citrix:inMaintenanceMode\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Session\": {\n      \"@id\": \"citrix:Session\",\n      \"@context\": {\n        \"userName\": \"schema:name\",\n        \"state\": \"citrix:sessionState\",\n        \"startTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"machineName\": \"citrix:machineName\",\n        \"clientName\": \"citrix:clientName\"\n      }\n    },\n\n    \"Application\"\
  : {\n      \"@id\": \"citrix:Application\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"publishedName\": \"citrix:publishedName\",\n        \"description\": \"schema:description\",\n        \"enabled\": \"citrix:enabled\",\n        \"commandLineExecutable\": \"citrix:commandLineExecutable\"\n      }\n    },\n\n    \"ServicePrincipal\": {\n      \"@id\": \"citrix:ServicePrincipal\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"clientId\": \"citrix:clientId\",\n        \"customerId\": \"citrix:customerId\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ResourceLocation\": {\n      \"@id\": \"citrix:ResourceLocation\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"internalOnly\": {\n          \"@id\": \"citrix:internalOnly\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"timeZone\": \"citrix:timeZone\"\
  \n      }\n    },\n\n    \"Device\": {\n      \"@id\": \"citrix:Device\",\n      \"@context\": {\n        \"serialNumber\": \"citrix:serialNumber\",\n        \"deviceModel\": \"citrix:deviceModel\",\n        \"platform\": \"citrix:platform\",\n        \"osVersion\": \"citrix:osVersion\",\n        \"userName\": \"schema:name\",\n        \"managed\": {\n          \"@id\": \"citrix:managed\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"compliant\": {\n          \"@id\": \"citrix:compliant\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"lastAccess\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/citrix/refs/heads/main/json-ld/citrix-context.jsonld
tags:
- Application Delivery
- Desktop-As-A-Service
- Networking
- Virtualization
- Workspace
- JSON-LD
- Linked Data
- Semantic Web
---
