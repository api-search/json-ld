---
api_specs:
- filename: spot-by-netapp-openapi.yml
  format: yaml
  label: Spot by NetApp API
  slug: spot-by-netapp
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spot-by-netapp/refs/heads/main/openapi/spot-by-netapp-openapi.yml
class_count: 39
classes:
- ElastigroupAWS
- id
- name
- description
- region
- Capacity
- minimum
- maximum
- target
- unit
- Strategy
- risk
- onDemandCount
- availabilityVsCost
- fallbackToOnDemand
- utilizeReservedInstances
- OceanCluster
- cloudProvider
- autoScaler
- CostSavings
- actualCost
- potentialCost
- savings
- savingsPercentage
- currency
- RightsizingRecommendation
- resourceId
- resourceType
- currentSize
- recommendedSize
- estimatedMonthlySavings
- justification
- AuditEvent
- eventType
- accountId
- userId
- data
- StatefulNode
- state
context_file: json-ld/spot-by-netapp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spot-by-netapp/refs/heads/main/json-ld/spot-by-netapp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spot By Netapp from Spot by NetApp.
layout: jsonld
name: Spot By Netapp Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: finops
  uri: https://www.finops.org/ontology/
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: timestamp
  type: dateTime
property_count: 3
provider_name: Spot by NetApp
provider_slug: spot-by-netapp
slug: spot-by-netapp-context
source_filename: spot-by-netapp-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://spot.io/ontology/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"finops\": \"https://www.finops.org/ontology/\",\n\n    \"ElastigroupAWS\": \"spot:Elastigroup\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"region\": \"spot:cloudRegion\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"Capacity\": \"spot:CapacityConfiguration\",\n    \"minimum\": \"spot:minimumCapacity\",\n    \"maximum\": \"spot:maximumCapacity\",\n    \"target\": \"spot:targetCapacity\",\n    \"unit\": \"spot:capacityUnit\",\n\n    \"Strategy\": \"spot:SpotStrategy\",\n    \"risk\": \"spot:spotRiskPercentage\",\n    \"onDemandCount\": \"spot:onDemandCount\",\n    \"availabilityVsCost\"\
  : \"spot:optimizationMode\",\n    \"fallbackToOnDemand\": \"spot:onDemandFallback\",\n    \"utilizeReservedInstances\": \"spot:useReservedInstances\",\n\n    \"OceanCluster\": \"spot:OceanCluster\",\n    \"cloudProvider\": \"spot:cloudProvider\",\n    \"autoScaler\": \"spot:autoScalerConfig\",\n\n    \"CostSavings\": \"finops:CostSavingsReport\",\n    \"actualCost\": \"finops:actualCost\",\n    \"potentialCost\": \"finops:potentialCost\",\n    \"savings\": \"finops:costSavings\",\n    \"savingsPercentage\": \"finops:savingsPercentage\",\n    \"currency\": \"schema:priceCurrency\",\n\n    \"RightsizingRecommendation\": \"finops:RightsizingRecommendation\",\n    \"resourceId\": \"spot:resourceId\",\n    \"resourceType\": \"spot:resourceType\",\n    \"currentSize\": \"spot:currentSize\",\n    \"recommendedSize\": \"spot:recommendedSize\",\n    \"estimatedMonthlySavings\": \"finops:estimatedSavings\",\n    \"justification\": \"schema:description\",\n\n    \"AuditEvent\": \"schema:Event\",\n\
  \    \"eventType\": \"schema:eventType\",\n    \"accountId\": \"spot:accountId\",\n    \"userId\": \"spot:userId\",\n    \"timestamp\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"data\": \"spot:eventData\",\n\n    \"StatefulNode\": \"spot:StatefulNode\",\n    \"state\": \"spot:nodeState\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spot-by-netapp/refs/heads/main/json-ld/spot-by-netapp-context.jsonld
tags:
- Cloud Optimization
- FinOps
- Kubernetes
- Azure
- GCP
- Cost Optimization
- Auto Scaling
- JSON-LD
- Linked Data
- Semantic Web
---
