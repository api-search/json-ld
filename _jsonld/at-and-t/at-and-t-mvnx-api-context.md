---
api_specs:
- filename: at-and-t-sms-api.yaml
  format: yaml
  label: AT&T SMS API
  slug: att-sms-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/openapi/at-and-t-sms-api.yaml
- filename: at-and-t-in-app-messaging-api.yaml
  format: yaml
  label: AT&T In-App Messaging API
  slug: att-in-app-messaging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/openapi/at-and-t-in-app-messaging-api.yaml
- filename: at-and-t-mvnx-api.yaml
  format: yaml
  label: AT&T MVNX API
  slug: att-mvnx-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/openapi/at-and-t-mvnx-api.yaml
class_count: 18
classes:
- GeographicSite
- ProductOrderCreate
- ProductOrder
- ResourceReservationCreate
- ResourceReservation
- ResourceReservationUpdate
- PortabilityOrderCreate
- PortabilityOrder
- PortabilityOrderUpdate
- CancelPortabilityOrder
- PortabilityOrderCancellation
- Resource
- ResourceUpdate
- Product
- Service
- TopupBalanceCreate
- TopupBalance
- name
context_file: json-ld/at-and-t-mvnx-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/json-ld/at-and-t-mvnx-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for At And T Mvnx Api from AT&T.
layout: jsonld
name: At And T Mvnx Api Context
namespaces:
- prefix: pan
  uri: https://att.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: href
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: externalId
  type: string
- container: set
  name: orderItem
  type: reference
- container: ''
  name: action
  type: string
- container: ''
  name: product
  type: reference
- container: ''
  name: productOffering
  type: reference
- container: ''
  name: state
  type: string
- container: set
  name: resourceCapacity
  type: reference
- container: ''
  name: resourcePool
  type: reference
- container: ''
  name: capacityAmount
  type: integer
- container: ''
  name: reservationState
  type: string
- container: set
  name: reservedResource
  type: reference
- container: ''
  name: value
  type: string
- container: set
  name: portabilityOrderItem
  type: reference
- container: ''
  name: msisdn
  type: string
- container: ''
  name: portingType
  type: string
- container: ''
  name: currentCarrier
  type: string
- container: ''
  name: requestedCompletionDate
  type: dateTime
- container: ''
  name: portabilityOrder
  type: reference
- container: ''
  name: cancellationReason
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: serialNumber
  type: string
- container: set
  name: resourceCharacteristic
  type: reference
- container: ''
  name: serviceType
  type: string
- container: ''
  name: channel
  type: reference
- container: ''
  name: amount
  type: reference
- container: ''
  name: units
  type: decimal
- container: ''
  name: currency
  type: string
property_count: 30
provider_name: AT&T
provider_slug: at-and-t
slug: at-and-t-mvnx-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://att.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GeographicSite\": \"pan:GeographicSite\",\n    \"ProductOrderCreate\": \"pan:ProductOrderCreate\",\n    \"ProductOrder\": \"pan:ProductOrder\",\n    \"ResourceReservationCreate\": \"pan:ResourceReservationCreate\",\n    \"ResourceReservation\": \"pan:ResourceReservation\",\n    \"ResourceReservationUpdate\": \"pan:ResourceReservationUpdate\",\n    \"PortabilityOrderCreate\": \"pan:PortabilityOrderCreate\",\n    \"PortabilityOrder\": \"pan:PortabilityOrder\",\n    \"PortabilityOrderUpdate\": \"pan:PortabilityOrderUpdate\",\n    \"CancelPortabilityOrder\": \"pan:CancelPortabilityOrder\",\n    \"PortabilityOrderCancellation\": \"pan:PortabilityOrderCancellation\",\n    \"Resource\": \"pan:Resource\",\n    \"ResourceUpdate\": \"pan:ResourceUpdate\"\
  ,\n    \"Product\": \"pan:Product\",\n    \"Service\": \"pan:Service\",\n    \"TopupBalanceCreate\": \"pan:TopupBalanceCreate\",\n    \"TopupBalance\": \"pan:TopupBalance\",\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"href\": {\n      \"@id\": \"pan:href\",\n      \"@type\": \"@id\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalId\": {\n      \"@id\": \"pan:externalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderItem\": {\n      \"@id\": \"pan:orderItem\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"action\": {\n      \"@id\": \"pan:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"product\": {\n      \"@id\": \"pan:product\",\n      \"@type\": \"@id\"\n    },\n    \"productOffering\": {\n      \"@id\": \"pan:productOffering\",\n      \"@type\": \"@id\"\n    },\n    \"state\": {\n      \"@id\"\
  : \"pan:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceCapacity\": {\n      \"@id\": \"pan:resourceCapacity\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"resourcePool\": {\n      \"@id\": \"pan:resourcePool\",\n      \"@type\": \"@id\"\n    },\n    \"capacityAmount\": {\n      \"@id\": \"pan:capacityAmount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"reservationState\": {\n      \"@id\": \"pan:reservationState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reservedResource\": {\n      \"@id\": \"pan:reservedResource\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portabilityOrderItem\": {\n      \"@id\": \"pan:portabilityOrderItem\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"msisdn\": {\n      \"@id\": \"pan:msisdn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portingType\"\
  : {\n      \"@id\": \"pan:portingType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentCarrier\": {\n      \"@id\": \"pan:currentCarrier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedCompletionDate\": {\n      \"@id\": \"pan:requestedCompletionDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"portabilityOrder\": {\n      \"@id\": \"pan:portabilityOrder\",\n      \"@type\": \"@id\"\n    },\n    \"cancellationReason\": {\n      \"@id\": \"pan:cancellationReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"pan:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serialNumber\": {\n      \"@id\": \"pan:serialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceCharacteristic\": {\n      \"@id\": \"pan:resourceCharacteristic\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"serviceType\": {\n      \"@id\": \"pan:serviceType\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"channel\": {\n      \"@id\": \"pan:channel\",\n      \"@type\": \"@id\"\n    },\n    \"amount\": {\n      \"@id\": \"pan:amount\",\n      \"@type\": \"@id\"\n    },\n    \"units\": {\n      \"@id\": \"pan:units\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"pan:currency\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/json-ld/at-and-t-mvnx-api-context.jsonld
tags:
- Telecommunications
- Wireless
- Wireline
- Messaging
- Speech
- Mobile
- Broadband
- Enterprise
- JSON-LD
- Linked Data
- Semantic Web
---
