---
class_count: 19
classes:
- TestResponse
- ArchiveSearchRequest
- ArchiveScene
- Bundle
- ArchiveOrderRequest
- BatchArchiveOrderRequest
- TaskingSearchRequest
- TaskingOpportunity
- TaskingOrderRequest
- BatchTaskingOrderRequest
- OrderResponse
- CancelResponse
- OrdersListResponse
- Order
- Campaign
- CampaignsListResponse
- Dataset
- DatasetsListResponse
- Resource
context_file: json-ld/arlula-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/arlula/refs/heads/main/json-ld/arlula-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Arlula Api from Arlula.
layout: jsonld
name: Arlula Api Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: arlula
  uri: https://arlula.com/vocab#
properties:
- container: ''
  name: orderId
  type: string
- container: ''
  name: sceneId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: provider
  type: string
- container: ''
  name: resolution
  type: decimal
- container: ''
  name: cloudCover
  type: decimal
- container: ''
  name: captureDate
  type: date
- container: ''
  name: price
  type: decimal
- container: set
  name: bundles
  type: ''
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: campaignId
  type: string
- container: ''
  name: datasetId
  type: string
- container: ''
  name: resourceId
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: filename
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: opportunityId
  type: string
- container: ''
  name: satellite
  type: string
- container: ''
  name: windowStart
  type: dateTime
- container: ''
  name: windowEnd
  type: dateTime
- container: ''
  name: cancelled
  type: boolean
- container: set
  name: datasets
  type: ''
- container: set
  name: resources
  type: ''
- container: set
  name: orders
  type: ''
- container: set
  name: campaigns
  type: ''
property_count: 26
provider_name: Arlula
provider_slug: arlula
slug: arlula-api-context
tags:
- Earth Observation
- Geospatial
- Imagery
- Remote Sensing
- Satellites
- JSON-LD
- Linked Data
- Semantic Web
---
