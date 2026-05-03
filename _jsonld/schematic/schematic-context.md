---
api_specs:
- filename: schematic-openapi.yml
  format: yaml
  label: Schematic API
  slug: schematic-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/openapi/schematic-openapi.yml
class_count: 29
classes:
- Company
- User
- Feature
- FeatureFlag
- Plan
- PlanEntitlement
- CompanyOverride
- FlagRule
- UsageEvent
- BillingProduct
- BillingSubscription
- BillingCredit
- Webhook
- name
- description
- url
- identifier
- dateCreated
- dateModified
- flagEnabled
- featureType
- planType
- entitlementValue
- eventName
- externalId
- environmentKey
- Organization
- SoftwareApplication
- WebAPI
context_file: json-ld/schematic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/json-ld/schematic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Schematic from Schematic.
layout: jsonld
name: Schematic Context
namespaces:
- prefix: schematic
  uri: https://schematichq.com/vocab#
- prefix: billing
  uri: https://schematichq.com/billing/vocab#
properties:
- container: ''
  name: hasFeature
  type: reference
- container: ''
  name: hasPlan
  type: reference
- container: ''
  name: hasEntitlement
  type: reference
- container: ''
  name: hasFlag
  type: reference
property_count: 4
provider_name: Schematic
provider_slug: schematic
slug: schematic-context
source_filename: schematic-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"schematic\": \"https://schematichq.com/vocab#\",\n    \"billing\": \"https://schematichq.com/billing/vocab#\",\n\n    \"Company\": \"schematic:Company\",\n    \"User\": \"schematic:User\",\n    \"Feature\": \"schematic:Feature\",\n    \"FeatureFlag\": \"schematic:FeatureFlag\",\n    \"Plan\": \"schematic:Plan\",\n    \"PlanEntitlement\": \"schematic:PlanEntitlement\",\n    \"CompanyOverride\": \"schematic:CompanyOverride\",\n    \"FlagRule\": \"schematic:FlagRule\",\n    \"UsageEvent\": \"schematic:UsageEvent\",\n    \"BillingProduct\": \"billing:BillingProduct\",\n    \"BillingSubscription\": \"billing:Subscription\",\n    \"BillingCredit\": \"billing:Credit\",\n    \"Webhook\": \"schematic:Webhook\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"\
  dateModified\": \"schema:dateModified\",\n\n    \"hasFeature\": {\n      \"@id\": \"schematic:hasFeature\",\n      \"@type\": \"@id\"\n    },\n    \"hasPlan\": {\n      \"@id\": \"schematic:hasPlan\",\n      \"@type\": \"@id\"\n    },\n    \"hasEntitlement\": {\n      \"@id\": \"schematic:hasEntitlement\",\n      \"@type\": \"@id\"\n    },\n    \"hasFlag\": {\n      \"@id\": \"schematic:hasFlag\",\n      \"@type\": \"@id\"\n    },\n    \"flagEnabled\": \"schematic:flagEnabled\",\n    \"featureType\": \"schematic:featureType\",\n    \"planType\": \"schematic:planType\",\n    \"entitlementValue\": \"schematic:entitlementValue\",\n    \"eventName\": \"schematic:eventName\",\n    \"externalId\": \"schematic:externalId\",\n    \"environmentKey\": \"schematic:environmentKey\",\n\n    \"Organization\": \"schema:Organization\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"WebAPI\": \"schema:WebAPI\"\n  },\n  \"@graph\": [\n    {\n      \"@id\": \"https://schematichq.com/\"\
  ,\n      \"@type\": [\"SoftwareApplication\", \"WebAPI\"],\n      \"name\": \"Schematic\",\n      \"description\": \"Feature and entitlement management platform for SaaS companies providing pricing, packaging, and metering.\",\n      \"url\": \"https://schematichq.com/\",\n      \"documentation\": \"https://docs.schematichq.com/\"\n    }\n  ]\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/json-ld/schematic-context.jsonld
tags:
- Billing
- Entitlements
- Feature Flags
- Feature Management
- FinOps
- Metering
- Pricing
- SaaS
- JSON-LD
- Linked Data
- Semantic Web
---
