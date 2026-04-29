---
class_count: 0
classes: []
context_file: json-ld/hubspot-crm-feature-flags-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-feature-flags-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Crm Feature Flags from HubSpot.
layout: jsonld
name: Hubspot Crm Feature Flags Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: FeatureFlag
  type: ''
- container: ''
  name: FeatureFlagInput
  type: ''
- container: ''
  name: PortalFlagState
  type: ''
- container: ''
  name: PortalFlagStateInput
  type: ''
- container: ''
  name: PortalFlagStateCollection
  type: ''
- container: ''
  name: BatchPortalFlagStateInput
  type: ''
- container: ''
  name: BatchPortalFlagStateInputItem
  type: ''
- container: ''
  name: BatchDeleteInput
  type: ''
- container: ''
  name: BatchDeleteInputItem
  type: ''
- container: ''
  name: BatchPortalFlagStateResponse
  type: ''
- container: ''
  name: BatchPortalFlagStateResponseWithErrors
  type: ''
- container: ''
  name: BatchError
  type: ''
- container: ''
  name: Paging
  type: ''
- container: ''
  name: PagingNext
  type: ''
- container: ''
  name: Error
  type: ''
- container: ''
  name: ErrorDetail
  type: ''
property_count: 16
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-crm-feature-flags-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"FeatureFlag\": {\n      \"@id\": \"ns:FeatureFlag\",\n      \"@context\": {\n        \"appId\": {\n          \"@id\": \"ns:appId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"flagName\": {\n          \"@id\": \"ns:flagName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"defaultState\": {\n          \"@id\": \"ns:defaultState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"overrideState\": {\n          \"@id\": \"ns:overrideState\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"FeatureFlagInput\": {\n      \"@id\": \"ns:FeatureFlagInput\",\n      \"@context\": {\n        \"defaultState\": {\n          \"@id\": \"ns:defaultState\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"PortalFlagState\": {\n      \"@id\": \"ns:PortalFlagState\"\
  ,\n      \"@context\": {\n        \"appId\": {\n          \"@id\": \"ns:appId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"flagName\": {\n          \"@id\": \"ns:flagName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"portalId\": {\n          \"@id\": \"ns:portalId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"flagState\": {\n          \"@id\": \"ns:flagState\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"PortalFlagStateInput\": {\n      \"@id\": \"ns:PortalFlagStateInput\",\n      \"@context\": {\n        \"flagState\": {\n          \"@id\": \"ns:flagState\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"PortalFlagStateCollection\": {\n      \"@id\": \"ns:PortalFlagStateCollection\",\n      \"@context\": {\n        \"portalFlagStates\": \"ns:portalFlagStates\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n   \
  \ },\n    \"BatchPortalFlagStateInput\": {\n      \"@id\": \"ns:BatchPortalFlagStateInput\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchPortalFlagStateInputItem\": {\n      \"@id\": \"ns:BatchPortalFlagStateInputItem\",\n      \"@context\": {\n        \"portalId\": {\n          \"@id\": \"ns:portalId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"flagState\": {\n          \"@id\": \"ns:flagState\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BatchDeleteInput\": {\n      \"@id\": \"ns:BatchDeleteInput\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchDeleteInputItem\": {\n      \"@id\": \"ns:BatchDeleteInputItem\",\n      \"@context\": {\n        \"portalId\": {\n          \"@id\": \"ns:portalId\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"BatchPortalFlagStateResponse\": {\n      \"@id\": \"ns:BatchPortalFlagStateResponse\",\n  \
  \    \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"results\": \"ns:results\",\n        \"startedAt\": {\n          \"@id\": \"ns:startedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"completedAt\": {\n          \"@id\": \"ns:completedAt\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BatchPortalFlagStateResponseWithErrors\": {\n      \"@id\": \"ns:BatchPortalFlagStateResponseWithErrors\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"results\": \"ns:results\",\n        \"errors\": \"ns:errors\",\n        \"startedAt\": {\n          \"@id\": \"ns:startedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"completedAt\": {\n          \"@id\": \"ns:completedAt\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BatchError\": {\n\
  \      \"@id\": \"ns:BatchError\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\"\n      }\n    },\n    \"Paging\": {\n      \"@id\": \"ns:Paging\",\n      \"@context\": {\n        \"next\": {\n          \"@id\": \"ns:next\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"PagingNext\": {\n      \"@id\": \"ns:PagingNext\",\n      \"@context\": {\n        \"after\": {\n          \"@id\": \"ns:after\",\n          \"@type\": \"xsd:string\"\n        },\n        \"link\": {\n          \"@id\": \"ns:link\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\"\
  : {\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\",\n        \"errors\": \"ns:errors\"\n      }\n    },\n    \"ErrorDetail\": {\n      \"@id\": \"ns:ErrorDetail\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"in\": {\n          \"@id\": \"ns:in\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-feature-flags-context.jsonld
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
