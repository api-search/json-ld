---
api_specs:
- filename: stigg-openapi.yml
  format: yaml
  label: Stigg GraphQL API
  slug: stigg-graphql
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stigg/refs/heads/main/openapi/stigg-openapi.yml
class_count: 19
classes:
- customerId
- featureId
- planId
- subscriptionId
- isGranted
- usageLimit
- currentUsage
- resetPeriod
- Customer
- Subscription
- Plan
- Entitlement
- Feature
- name
- email
- createdAt
- updatedAt
- status
- description
context_file: json-ld/stigg-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stigg/refs/heads/main/json-ld/stigg-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stigg from Stigg.
layout: jsonld
name: Stigg Context
namespaces:
- prefix: stigg
  uri: https://api.stigg.io/vocab#
properties: []
property_count: 0
provider_name: Stigg
provider_slug: stigg
slug: stigg-context
source_filename: stigg-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"stigg\": \"https://api.stigg.io/vocab#\",\n\n    \"customerId\": \"stigg:customerId\",\n    \"featureId\": \"stigg:featureId\",\n    \"planId\": \"stigg:planId\",\n    \"subscriptionId\": \"stigg:subscriptionId\",\n    \"isGranted\": \"stigg:isGranted\",\n    \"usageLimit\": \"stigg:usageLimit\",\n    \"currentUsage\": \"stigg:currentUsage\",\n    \"resetPeriod\": \"stigg:resetPeriod\",\n\n    \"Customer\": \"stigg:Customer\",\n    \"Subscription\": \"stigg:Subscription\",\n    \"Plan\": \"stigg:Plan\",\n    \"Entitlement\": \"stigg:Entitlement\",\n    \"Feature\": \"stigg:Feature\",\n\n    \"name\": \"name\",\n    \"email\": \"email\",\n    \"createdAt\": \"dateCreated\",\n    \"updatedAt\": \"dateModified\",\n    \"status\": \"stigg:status\",\n    \"description\": \"description\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stigg/refs/heads/main/json-ld/stigg-context.jsonld
tags:
- FinOps
- Pricing
- Billing
- Entitlements
- Usage-Based Billing
- SaaS
- JSON-LD
- Linked Data
- Semantic Web
---
