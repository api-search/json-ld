---
class_count: 5
classes:
- AllocationEntry
- AllocationRequest
- Entitlement
- Subscription
- SubscriptionEntitlements
context_file: json-ld/palo-alto-sase-subscription-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-subscription-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Sase Subscription Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Sase Subscription Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: allocatedQuantity
  type: integer
- container: set
  name: allocations
  type: reference
- container: ''
  name: availableQuantity
  type: integer
- container: ''
  name: endDate
  type: date
- container: set
  name: entitlements
  type: reference
- container: ''
  name: feature
  type: string
- container: ''
  name: licensedQuantity
  type: integer
- container: ''
  name: licensedUnit
  type: string
- container: ''
  name: productName
  type: string
- container: ''
  name: quantity
  type: integer
- container: ''
  name: sku
  type: string
- container: ''
  name: startDate
  type: date
- container: ''
  name: status
  type: string
- container: ''
  name: subscriptionId
  type: string
- container: ''
  name: supportLevel
  type: string
- container: ''
  name: tsgId
  type: string
- container: ''
  name: tsgName
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: utilizedQuantity
  type: integer
property_count: 19
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-sase-subscription-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AllocationEntry\": \"pan:AllocationEntry\",\n    \"AllocationRequest\": \"pan:AllocationRequest\",\n    \"Entitlement\": \"pan:Entitlement\",\n    \"Subscription\": \"pan:Subscription\",\n    \"SubscriptionEntitlements\": \"pan:SubscriptionEntitlements\",\n    \"allocatedQuantity\": {\n      \"@id\": \"pan:allocated_quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"allocations\": {\n      \"@id\": \"pan:allocations\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"availableQuantity\": {\n      \"@id\": \"pan:available_quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endDate\": {\n      \"@id\": \"pan:end_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"entitlements\": {\n      \"@id\"\
  : \"pan:entitlements\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"feature\": {\n      \"@id\": \"pan:feature\",\n      \"@type\": \"xsd:string\"\n    },\n    \"licensedQuantity\": {\n      \"@id\": \"pan:licensed_quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"licensedUnit\": {\n      \"@id\": \"pan:licensed_unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productName\": {\n      \"@id\": \"pan:product_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"pan:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sku\": {\n      \"@id\": \"pan:sku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"pan:start_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriptionId\": {\n      \"@id\": \"pan:subscription_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supportLevel\"\
  : {\n      \"@id\": \"pan:support_level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tsgId\": {\n      \"@id\": \"pan:tsg_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tsgName\": {\n      \"@id\": \"pan:tsg_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"pan:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"utilizedQuantity\": {\n      \"@id\": \"pan:utilized_quantity\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-subscription-api-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
