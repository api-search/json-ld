---
api_specs:
- filename: api-explorer
  format: yaml
  label: Junos Space API
  slug: ''
  spec_type: OpenAPI
  url: https://[space-server]/api/space/api-explorer
- filename: juniper-apstra-openapi.yml
  format: yaml
  label: Juniper Apstra API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper/refs/heads/main/openapi/juniper-apstra-openapi.yml
- filename: juniper-junos-rest-api-openapi.yml
  format: yaml
  label: Junos REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper/refs/heads/main/openapi/juniper-junos-rest-api-openapi.yml
- filename: juniper-mist-openapi.yml
  format: yaml
  label: Juniper Mist API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper/refs/heads/main/openapi/juniper-mist-openapi.yml
- filename: juniper-contrail-openapi.yml
  format: yaml
  label: Contrail Networking API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper/refs/heads/main/openapi/juniper-contrail-openapi.yml
- filename: juniper-atp-cloud-openapi.yml
  format: yaml
  label: Juniper ATP Cloud API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper/refs/heads/main/openapi/juniper-atp-cloud-openapi.yml
class_count: 0
classes: []
context_file: json-ld/juniper-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/juniper/refs/heads/main/json-ld/juniper-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Juniper from Juniper Networks.
layout: jsonld
name: Juniper Context
namespaces:
- prefix: juniper
  uri: https://www.juniper.net/ns/api#
- prefix: network
  uri: https://www.juniper.net/ns/network#
- prefix: security
  uri: https://www.juniper.net/ns/security#
- prefix: name
  uri: https://schema.org/name
- prefix: description
  uri: https://schema.org/description
- prefix: url
  uri: https://schema.org/url
- prefix: email
  uri: https://schema.org/email
- prefix: dateCreated
  uri: https://schema.org/dateCreated
- prefix: dateModified
  uri: https://schema.org/dateModified
- prefix: identifier
  uri: https://schema.org/identifier
properties:
- container: ''
  name: NetworkDevice
  type: ''
- container: ''
  name: Site
  type: ''
- container: ''
  name: VirtualNetwork
  type: ''
- container: ''
  name: Blueprint
  type: ''
- container: ''
  name: SecurityThreat
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Interface
  type: ''
- container: ''
  name: WLAN
  type: ''
property_count: 8
provider_name: Juniper Networks
provider_slug: juniper
slug: juniper-context
source_filename: juniper-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"juniper\": \"https://www.juniper.net/ns/api#\",\n    \"network\": \"https://www.juniper.net/ns/network#\",\n    \"security\": \"https://www.juniper.net/ns/security#\",\n\n    \"NetworkDevice\": {\n      \"@id\": \"juniper:NetworkDevice\",\n      \"@context\": {\n        \"deviceId\": \"juniper:deviceId\",\n        \"serialNumber\": \"juniper:serialNumber\",\n        \"macAddress\": \"juniper:macAddress\",\n        \"model\": \"juniper:model\",\n        \"deviceFamily\": {\n          \"@id\": \"juniper:deviceFamily\",\n          \"@type\": \"@vocab\"\n        },\n        \"deviceType\": {\n          \"@id\": \"juniper:deviceType\",\n          \"@type\": \"@vocab\"\n        },\n        \"osVersion\": \"juniper:osVersion\",\n        \"managementIp\": \"juniper:managementIp\",\n        \"status\": {\n          \"@id\": \"juniper:status\",\n          \"@type\": \"@vocab\"\n        },\n        \"uptime\": {\n \
  \         \"@id\": \"juniper:uptime\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#integer\"\n        },\n        \"hostname\": \"juniper:hostname\",\n        \"location\": \"https://schema.org/location\",\n        \"interfaces\": \"network:interfaces\"\n      }\n    },\n\n    \"Site\": {\n      \"@id\": \"juniper:Site\",\n      \"@context\": {\n        \"siteId\": \"juniper:siteId\",\n        \"orgId\": \"juniper:orgId\",\n        \"address\": \"https://schema.org/address\",\n        \"latitude\": \"https://schema.org/latitude\",\n        \"longitude\": \"https://schema.org/longitude\",\n        \"timezone\": \"juniper:timezone\",\n        \"countryCode\": \"https://schema.org/addressCountry\",\n        \"siteGroups\": \"juniper:siteGroups\",\n        \"deviceCounts\": \"juniper:deviceCounts\"\n      }\n    },\n\n    \"VirtualNetwork\": {\n      \"@id\": \"network:VirtualNetwork\",\n      \"@context\": {\n        \"vnType\": {\n          \"@id\": \"network:vnType\",\n   \
  \       \"@type\": \"@vocab\"\n        },\n        \"vlanId\": {\n          \"@id\": \"network:vlanId\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#integer\"\n        },\n        \"vni\": {\n          \"@id\": \"network:vni\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#integer\"\n        },\n        \"subnets\": \"network:subnets\",\n        \"routingZone\": \"network:routingZone\",\n        \"forwardingMode\": {\n          \"@id\": \"network:forwardingMode\",\n          \"@type\": \"@vocab\"\n        },\n        \"routeTargets\": \"network:routeTargets\",\n        \"boundDevices\": \"network:boundDevices\"\n      }\n    },\n\n    \"Blueprint\": {\n      \"@id\": \"juniper:Blueprint\",\n      \"@context\": {\n        \"blueprintId\": \"juniper:blueprintId\",\n        \"label\": \"https://schema.org/name\",\n        \"design\": {\n          \"@id\": \"juniper:design\",\n          \"@type\": \"@vocab\"\n        },\n        \"version\": {\n          \"@id\": \"\
  juniper:version\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#integer\"\n        },\n        \"anomalyCount\": {\n          \"@id\": \"juniper:anomalyCount\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#integer\"\n        },\n        \"topology\": \"juniper:topology\",\n        \"virtualNetworks\": \"network:virtualNetworks\",\n        \"securityZones\": \"network:securityZones\"\n      }\n    },\n\n    \"SecurityThreat\": {\n      \"@id\": \"security:SecurityThreat\",\n      \"@context\": {\n        \"indicatorType\": {\n          \"@id\": \"security:indicatorType\",\n          \"@type\": \"@vocab\"\n        },\n        \"indicatorValue\": \"security:indicatorValue\",\n        \"threatScore\": {\n          \"@id\": \"security:threatScore\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#integer\"\n        },\n        \"verdict\": {\n          \"@id\": \"security:verdict\",\n          \"@type\": \"@vocab\"\n        },\n        \"confidence\": {\n  \
  \        \"@id\": \"security:confidence\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#decimal\"\n        },\n        \"malwareInfo\": \"security:malwareInfo\",\n        \"fileDetails\": \"security:fileDetails\",\n        \"categories\": \"security:categories\",\n        \"firstSeen\": {\n          \"@id\": \"security:firstSeen\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\n        },\n        \"lastSeen\": {\n          \"@id\": \"security:lastSeen\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"juniper:Organization\",\n      \"@context\": {\n        \"orgId\": \"juniper:orgId\",\n        \"name\": \"https://schema.org/name\",\n        \"sessionExpiry\": \"juniper:sessionExpiry\"\n      }\n    },\n\n    \"Interface\": {\n      \"@id\": \"network:Interface\",\n      \"@context\": {\n        \"interfaceName\": \"network:interfaceName\",\n        \"adminStatus\"\
  : {\n          \"@id\": \"network:adminStatus\",\n          \"@type\": \"@vocab\"\n        },\n        \"operStatus\": {\n          \"@id\": \"network:operStatus\",\n          \"@type\": \"@vocab\"\n        },\n        \"speed\": \"network:speed\",\n        \"mtu\": {\n          \"@id\": \"network:mtu\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#integer\"\n        },\n        \"ipAddresses\": \"network:ipAddresses\"\n      }\n    },\n\n    \"WLAN\": {\n      \"@id\": \"network:WLAN\",\n      \"@context\": {\n        \"ssid\": \"network:ssid\",\n        \"enabled\": \"juniper:enabled\",\n        \"hideSsid\": \"network:hideSsid\",\n        \"band\": \"network:band\",\n        \"authType\": {\n          \"@id\": \"network:authType\",\n          \"@type\": \"@vocab\"\n        }\n      }\n    },\n\n    \"name\": \"https://schema.org/name\",\n    \"description\": \"https://schema.org/description\",\n    \"url\": \"https://schema.org/url\",\n    \"email\": \"https://schema.org/email\"\
  ,\n    \"dateCreated\": \"https://schema.org/dateCreated\",\n    \"dateModified\": \"https://schema.org/dateModified\",\n    \"identifier\": \"https://schema.org/identifier\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/juniper/refs/heads/main/json-ld/juniper-context.jsonld
tags:
- AI
- Automation
- Cloud
- Enterprise
- Networking
- SDN
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
