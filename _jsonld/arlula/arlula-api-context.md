---
api_specs:
- filename: arlula-openapi.yaml
  format: yaml
  label: Arlula API
  slug: arlula-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/arlula/refs/heads/main/openapi/arlula-openapi.yaml
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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"arlula\": \"https://arlula.com/vocab#\",\n    \"TestResponse\": \"arlula:TestResponse\",\n    \"ArchiveSearchRequest\": \"arlula:ArchiveSearchRequest\",\n    \"ArchiveScene\": \"arlula:ArchiveScene\",\n    \"Bundle\": \"arlula:Bundle\",\n    \"ArchiveOrderRequest\": \"arlula:ArchiveOrderRequest\",\n    \"BatchArchiveOrderRequest\": \"arlula:BatchArchiveOrderRequest\",\n    \"TaskingSearchRequest\": \"arlula:TaskingSearchRequest\",\n    \"TaskingOpportunity\": \"arlula:TaskingOpportunity\",\n    \"TaskingOrderRequest\": \"arlula:TaskingOrderRequest\",\n    \"BatchTaskingOrderRequest\": \"arlula:BatchTaskingOrderRequest\",\n    \"OrderResponse\": \"arlula:OrderResponse\",\n    \"CancelResponse\": \"arlula:CancelResponse\",\n    \"OrdersListResponse\": \"arlula:OrdersListResponse\",\n\
  \    \"Order\": \"arlula:Order\",\n    \"Campaign\": \"arlula:Campaign\",\n    \"CampaignsListResponse\": \"arlula:CampaignsListResponse\",\n    \"Dataset\": \"arlula:Dataset\",\n    \"DatasetsListResponse\": \"arlula:DatasetsListResponse\",\n    \"Resource\": \"arlula:Resource\",\n    \"orderId\": {\"@id\": \"arlula:orderId\", \"@type\": \"xsd:string\"},\n    \"sceneId\": {\"@id\": \"arlula:sceneId\", \"@type\": \"xsd:string\"},\n    \"status\": {\"@id\": \"arlula:status\", \"@type\": \"xsd:string\"},\n    \"provider\": {\"@id\": \"schema:provider\", \"@type\": \"xsd:string\"},\n    \"resolution\": {\"@id\": \"arlula:resolution\", \"@type\": \"xsd:decimal\"},\n    \"cloudCover\": {\"@id\": \"arlula:cloudCover\", \"@type\": \"xsd:decimal\"},\n    \"captureDate\": {\"@id\": \"dcterms:date\", \"@type\": \"xsd:date\"},\n    \"price\": {\"@id\": \"schema:price\", \"@type\": \"xsd:decimal\"},\n    \"bundles\": {\"@id\": \"arlula:bundles\", \"@container\": \"@set\"},\n    \"name\": {\"@id\"\
  : \"schema:name\", \"@type\": \"xsd:string\"},\n    \"description\": {\"@id\": \"dcterms:description\", \"@type\": \"xsd:string\"},\n    \"campaignId\": {\"@id\": \"arlula:campaignId\", \"@type\": \"xsd:string\"},\n    \"datasetId\": {\"@id\": \"arlula:datasetId\", \"@type\": \"xsd:string\"},\n    \"resourceId\": {\"@id\": \"arlula:resourceId\", \"@type\": \"xsd:string\"},\n    \"type\": {\"@id\": \"dcterms:type\", \"@type\": \"xsd:string\"},\n    \"filename\": {\"@id\": \"arlula:filename\", \"@type\": \"xsd:string\"},\n    \"message\": {\"@id\": \"arlula:message\", \"@type\": \"xsd:string\"},\n    \"opportunityId\": {\"@id\": \"arlula:opportunityId\", \"@type\": \"xsd:string\"},\n    \"satellite\": {\"@id\": \"arlula:satellite\", \"@type\": \"xsd:string\"},\n    \"windowStart\": {\"@id\": \"arlula:windowStart\", \"@type\": \"xsd:dateTime\"},\n    \"windowEnd\": {\"@id\": \"arlula:windowEnd\", \"@type\": \"xsd:dateTime\"},\n    \"cancelled\": {\"@id\": \"arlula:cancelled\", \"@type\":\
  \ \"xsd:boolean\"},\n    \"datasets\": {\"@id\": \"arlula:datasets\", \"@container\": \"@set\"},\n    \"resources\": {\"@id\": \"arlula:resources\", \"@container\": \"@set\"},\n    \"orders\": {\"@id\": \"arlula:orders\", \"@container\": \"@set\"},\n    \"campaigns\": {\"@id\": \"arlula:campaigns\", \"@container\": \"@set\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/arlula/refs/heads/main/json-ld/arlula-api-context.jsonld
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
