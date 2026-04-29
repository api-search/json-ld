---
class_count: 14
classes:
- FeatureFlag
- FeatureFlagInput
- PortalFlagState
- PortalFlagStateInput
- PortalFlagStateCollection
- BatchPortalFlagStateInput
- BatchPortalFlagStateInputItem
- BatchDeleteInput
- BatchDeleteInputItem
- BatchPortalFlagStateResponse
- BatchPortalFlagStateResponseWithErrors
- BatchError
- Paging
- PagingNext
context_file: json-ld/hubspot-crm-feature-flags-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-feature-flags-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Crm Feature Flags Api from HubSpot.
layout: jsonld
name: Hubspot Crm Feature Flags Api Context
namespaces:
- prefix: hubspot
  uri: https://developers.hubspot.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: appId
  type: string
- container: ''
  name: flagName
  type: string
- container: ''
  name: defaultState
  type: string
- container: ''
  name: overrideState
  type: string
- container: ''
  name: portalId
  type: string
- container: ''
  name: flagState
  type: string
- container: set
  name: portalFlagStates
  type: reference
- container: ''
  name: paging
  type: reference
- container: set
  name: inputs
  type: reference
- container: ''
  name: status
  type: string
- container: set
  name: results
  type: reference
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: set
  name: errors
  type: reference
- container: ''
  name: category
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: context
  type: reference
- container: ''
  name: next
  type: reference
- container: ''
  name: after
  type: string
- container: ''
  name: link
  type: string
property_count: 20
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-crm-feature-flags-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"FeatureFlag\": \"hubspot:FeatureFlag\",\n    \"appId\": {\n      \"@id\": \"hubspot:appId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flagName\": {\n      \"@id\": \"hubspot:flagName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultState\": {\n      \"@id\": \"hubspot:defaultState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overrideState\": {\n      \"@id\": \"hubspot:overrideState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FeatureFlagInput\": \"hubspot:FeatureFlagInput\",\n    \"PortalFlagState\": \"hubspot:PortalFlagState\",\n    \"portalId\": {\n      \"@id\": \"hubspot:portalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flagState\": {\n      \"@id\": \"hubspot:flagState\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"PortalFlagStateInput\": \"hubspot:PortalFlagStateInput\",\n    \"PortalFlagStateCollection\": \"hubspot:PortalFlagStateCollection\",\n    \"portalFlagStates\": {\n      \"@id\": \"hubspot:portalFlagStates\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"paging\": {\n      \"@id\": \"hubspot:paging\",\n      \"@type\": \"@id\"\n    },\n    \"BatchPortalFlagStateInput\": \"hubspot:BatchPortalFlagStateInput\",\n    \"inputs\": {\n      \"@id\": \"hubspot:inputs\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"BatchPortalFlagStateInputItem\": \"hubspot:BatchPortalFlagStateInputItem\",\n    \"BatchDeleteInput\": \"hubspot:BatchDeleteInput\",\n    \"BatchDeleteInputItem\": \"hubspot:BatchDeleteInputItem\",\n    \"BatchPortalFlagStateResponse\": \"hubspot:BatchPortalFlagStateResponse\",\n    \"status\": {\n      \"@id\": \"hubspot:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"results\"\
  : {\n      \"@id\": \"hubspot:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"startedAt\": {\n      \"@id\": \"hubspot:startedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"hubspot:completedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"BatchPortalFlagStateResponseWithErrors\": \"hubspot:BatchPortalFlagStateResponseWithErrors\",\n    \"errors\": {\n      \"@id\": \"hubspot:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"BatchError\": \"hubspot:BatchError\",\n    \"category\": {\n      \"@id\": \"hubspot:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"hubspot:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"context\": {\n      \"@id\": \"hubspot:context\",\n      \"@type\": \"@id\"\n    },\n    \"Paging\": \"hubspot:Paging\",\n    \"next\": {\n      \"@id\": \"hubspot:next\",\n      \"@type\": \"@id\"\n    },\n\
  \    \"PagingNext\": \"hubspot:PagingNext\",\n    \"after\": {\n      \"@id\": \"hubspot:after\",\n      \"@type\": \"xsd:string\"\n    },\n    \"link\": {\n      \"@id\": \"hubspot:link\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-feature-flags-api-context.jsonld
tags:
- Analytics
- Commerce
- Content
- CRM
- Customer Service
- Email Marketing
- Marketing
- Marketing Automation
- Operations
- Sales
- JSON-LD
- Linked Data
- Semantic Web
---
