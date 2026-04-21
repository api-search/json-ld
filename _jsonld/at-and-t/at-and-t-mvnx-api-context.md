---
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
