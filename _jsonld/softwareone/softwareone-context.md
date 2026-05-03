---
class_count: 30
classes:
- Order
- Subscription
- Product
- Organization
- Agreement
- License
- id
- type
- name
- description
- status
- client
- vendor
- agreement
- lines
- quantity
- product
- unitPrice
- currency
- notes
- billingTerm
- autoRenew
- licensePosition
- entitlements
- deployments
- complianceStatus
- cloudProvider
- monthlySpend
- savingsOpportunity
- rightsizingRecommendations
context_file: json-ld/softwareone-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/softwareone/refs/heads/main/json-ld/softwareone-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Softwareone from SoftwareOne.
layout: jsonld
name: Softwareone Context
namespaces:
- prefix: swo
  uri: https://api-evangelist.com/vocab/softwareone#
- prefix: schema
  uri: https://schema.org/
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: startDate
  type: date
- container: ''
  name: endDate
  type: date
property_count: 5
provider_name: SoftwareOne
provider_slug: softwareone
slug: softwareone-context
source_filename: softwareone-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"swo\": \"https://api-evangelist.com/vocab/softwareone#\",\n    \"schema\": \"https://schema.org/\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Order\": \"schema:Order\",\n    \"Subscription\": \"swo:Subscription\",\n    \"Product\": \"gr:ProductOrService\",\n    \"Organization\": \"schema:Organization\",\n    \"Agreement\": \"swo:Agreement\",\n    \"License\": \"swo:License\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"schema:orderStatus\",\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"client\": \"schema:customer\",\n    \"vendor\": \"schema:seller\",\n    \"agreement\": \"swo:agreement\"\
  ,\n    \"lines\": \"schema:orderedItem\",\n    \"quantity\": \"schema:orderQuantity\",\n    \"product\": \"gr:includes\",\n    \"unitPrice\": \"gr:hasCurrencyValue\",\n    \"currency\": \"gr:hasCurrency\",\n    \"notes\": \"schema:description\",\n    \"completedAt\": {\n      \"@id\": \"schema:orderDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"billingTerm\": \"swo:billingTerm\",\n    \"startDate\": {\n      \"@id\": \"schema:validFrom\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"schema:validThrough\",\n      \"@type\": \"xsd:date\"\n    },\n    \"autoRenew\": \"swo:autoRenew\",\n\n    \"licensePosition\": \"swo:licensePosition\",\n    \"entitlements\": \"swo:entitlements\",\n    \"deployments\": \"swo:deployments\",\n    \"complianceStatus\": \"swo:complianceStatus\",\n\n    \"cloudProvider\": \"swo:cloudProvider\",\n    \"monthlySpend\": \"swo:monthlySpend\",\n    \"savingsOpportunity\": \"swo:savingsOpportunity\",\n    \"rightsizingRecommendations\"\
  : \"swo:rightsizingRecommendations\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/softwareone/refs/heads/main/json-ld/softwareone-context.jsonld
tags:
- Marketplace
- Software Procurement
- Cloud Management
- License Management
- SaaS
- JSON-LD
- Linked Data
- Semantic Web
---
