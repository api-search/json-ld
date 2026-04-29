---
api_specs:
- filename: amazon-datazone-openapi.yml
  format: yaml
  label: Amazon DataZone API
  slug: amazon-datazone-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-datazone/refs/heads/main/openapi/amazon-datazone-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-datazone-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-datazone/refs/heads/main/json-ld/amazon-datazone-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Datazone from Amazon DataZone.
layout: jsonld
name: Amazon Datazone Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/datazone/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Domain
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: Asset
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: SubscriptionRequest
  type: ''
- container: ''
  name: id
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: portalUrl
  type: string
- container: ''
  name: domainId
  type: string
- container: ''
  name: domainExecutionRole
  type: string
- container: ''
  name: projectId
  type: string
- container: ''
  name: owningProjectId
  type: string
- container: ''
  name: typeIdentifier
  type: string
- container: ''
  name: requestReason
  type: string
- container: ''
  name: nextToken
  type: string
- container: set
  name: items
  type: ''
- container: set
  name: subscribedListings
  type: ''
- container: set
  name: subscribedPrincipals
  type: ''
- container: ''
  name: tags
  type: ''
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: message
  type: string
- container: ''
  name: code
  type: string
property_count: 26
provider_name: Amazon DataZone
provider_slug: amazon-datazone
slug: amazon-datazone-context
source_filename: amazon-datazone-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/datazone/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Domain\": {\"@id\": \"aws:Domain\"},\n    \"Project\": {\"@id\": \"aws:Project\"},\n    \"Asset\": {\"@id\": \"aws:DataAsset\"},\n    \"Environment\": {\"@id\": \"aws:Environment\"},\n    \"SubscriptionRequest\": {\"@id\": \"aws:SubscriptionRequest\"},\n\n    \"id\": {\"@id\": \"aws:resourceId\", \"@type\": \"xsd:string\"},\n    \"arn\": {\"@id\": \"aws:arn\", \"@type\": \"xsd:string\"},\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"description\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"status\": {\"@id\": \"aws:status\", \"@type\": \"xsd:string\"},\n    \"portalUrl\": {\"@id\": \"schema:url\", \"@type\": \"xsd:string\"},\n    \"domainId\": {\"@id\": \"aws:domainId\", \"@type\": \"xsd:string\"},\n    \"domainExecutionRole\"\
  : {\"@id\": \"aws:domainExecutionRole\", \"@type\": \"xsd:string\"},\n    \"projectId\": {\"@id\": \"aws:projectId\", \"@type\": \"xsd:string\"},\n    \"owningProjectId\": {\"@id\": \"aws:owningProjectId\", \"@type\": \"xsd:string\"},\n    \"typeIdentifier\": {\"@id\": \"aws:assetType\", \"@type\": \"xsd:string\"},\n    \"requestReason\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"nextToken\": {\"@id\": \"aws:nextToken\", \"@type\": \"xsd:string\"},\n\n    \"items\": {\"@id\": \"aws:items\", \"@container\": \"@set\"},\n    \"subscribedListings\": {\"@id\": \"aws:subscribedListings\", \"@container\": \"@set\"},\n    \"subscribedPrincipals\": {\"@id\": \"aws:subscribedPrincipals\", \"@container\": \"@set\"},\n    \"tags\": {\"@id\": \"aws:tags\"},\n\n    \"createdAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"updatedAt\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n\n    \"message\": {\"@id\": \"schema:description\"\
  , \"@type\": \"xsd:string\"},\n    \"code\": {\"@id\": \"aws:errorCode\", \"@type\": \"xsd:string\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-datazone/refs/heads/main/json-ld/amazon-datazone-context.jsonld
tags:
- AWS
- Data Catalog
- Data Governance
- Data Management
- Data Sharing
- Analytics
- JSON-LD
- Linked Data
- Semantic Web
---
