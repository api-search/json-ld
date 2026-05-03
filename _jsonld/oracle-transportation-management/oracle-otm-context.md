---
api_specs:
- filename: oracle-otm-business-objects-openapi.yml
  format: yaml
  label: Oracle Transportation Management Business Object Resources REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-transportation-management/refs/heads/main/openapi/oracle-otm-business-objects-openapi.yml
class_count: 0
classes: []
context_file: json-ld/oracle-otm-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-transportation-management/refs/heads/main/json-ld/oracle-otm-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Otm from Oracle Transportation Management.
layout: jsonld
name: Oracle Otm Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: otm
  uri: https://docs.oracle.com/en/cloud/saas/transportation/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ShipmentOrder
  type: reference
- container: ''
  name: shipmentOrderGid
  type: ''
- container: ''
  name: shipmentOrderXid
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: sourceLocationGid
  type: ''
- container: ''
  name: destLocationGid
  type: ''
- container: ''
  name: earlyPickupDate
  type: dateTime
- container: ''
  name: lateDeliveryDate
  type: dateTime
- container: ''
  name: transportationMode
  type: ''
- container: ''
  name: totalWeight
  type: decimal
- container: ''
  name: Carrier
  type: reference
- container: ''
  name: servprovGid
  type: ''
- container: ''
  name: scacCode
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: Location
  type: reference
- container: ''
  name: locationGid
  type: ''
- container: ''
  name: locationName
  type: ''
- container: ''
  name: address1
  type: ''
- container: ''
  name: city
  type: ''
- container: ''
  name: province
  type: ''
- container: ''
  name: postalCode
  type: ''
- container: ''
  name: country
  type: ''
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
property_count: 24
provider_name: Oracle Transportation Management
provider_slug: oracle-transportation-management
slug: oracle-otm-context
source_filename: oracle-otm-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"otm\": \"https://docs.oracle.com/en/cloud/saas/transportation/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ShipmentOrder\": {\n      \"@id\": \"schema:DeliveryEvent\",\n      \"@type\": \"@id\"\n    },\n    \"shipmentOrderGid\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"shipmentOrderXid\": {\n      \"@id\": \"schema:orderNumber\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\"\n    },\n    \"sourceLocationGid\": {\n      \"@id\": \"schema:originAddress\"\n    },\n    \"destLocationGid\": {\n      \"@id\": \"schema:destinationAddress\"\n    },\n    \"earlyPickupDate\": {\n      \"@id\": \"schema:expectedArrivalFrom\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lateDeliveryDate\": {\n      \"@id\": \"schema:expectedArrivalUntil\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"transportationMode\": {\n      \"@id\": \"schema:deliveryMethod\"\
  \n    },\n    \"totalWeight\": {\n      \"@id\": \"schema:weight\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"Carrier\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"@id\"\n    },\n    \"servprovGid\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"scacCode\": {\n      \"@id\": \"otm:scacCode\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n\n    \"Location\": {\n      \"@id\": \"schema:Place\",\n      \"@type\": \"@id\"\n    },\n    \"locationGid\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"locationName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"address1\": {\n      \"@id\": \"schema:streetAddress\"\n    },\n    \"city\": {\n      \"@id\": \"schema:addressLocality\"\n    },\n    \"province\": {\n      \"@id\": \"schema:addressRegion\"\n    },\n    \"postalCode\": {\n      \"@id\": \"schema:postalCode\"\n    },\n    \"country\": {\n      \"@id\": \"schema:addressCountry\"\n    },\n    \"latitude\": {\n      \"\
  @id\": \"schema:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"schema:longitude\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-transportation-management/refs/heads/main/json-ld/oracle-otm-context.jsonld
tags:
- Logistics
- Transportation
- Freight
- Supply Chain
- Shipping
- Global Trade
- Oracle
- JSON-LD
- Linked Data
- Semantic Web
---
