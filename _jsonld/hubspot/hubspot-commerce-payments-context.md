---
class_count: 0
classes: []
context_file: json-ld/hubspot-commerce-payments-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-commerce-payments-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Commerce Payments from HubSpot.
layout: jsonld
name: Hubspot Commerce Payments Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: CommercePayment
  type: ''
- container: ''
  name: CommercePaymentInput
  type: ''
- container: ''
  name: CommercePaymentPatch
  type: ''
- container: ''
  name: CommercePaymentCollection
  type: ''
- container: ''
  name: BatchReadRequest
  type: ''
- container: ''
  name: BatchReadInputItem
  type: ''
- container: ''
  name: BatchReadResponse
  type: ''
- container: ''
  name: BatchArchiveRequest
  type: ''
- container: ''
  name: BatchCreateRequest
  type: ''
- container: ''
  name: BatchCreateResponse
  type: ''
- container: ''
  name: BatchUpdateRequest
  type: ''
- container: ''
  name: BatchUpdateInputItem
  type: ''
- container: ''
  name: BatchUpdateResponse
  type: ''
- container: ''
  name: SearchRequest
  type: ''
- container: ''
  name: SearchResponse
  type: ''
- container: ''
  name: FilterGroup
  type: ''
- container: ''
  name: Filter
  type: ''
- container: ''
  name: SortOption
  type: ''
- container: ''
  name: AssociationInput
  type: ''
- container: ''
  name: AssociationType
  type: ''
- container: ''
  name: AssociationResult
  type: ''
- container: ''
  name: PropertyHistory
  type: ''
- container: ''
  name: Paging
  type: ''
- container: ''
  name: BatchError
  type: ''
- container: ''
  name: Error
  type: ''
- container: ''
  name: ErrorDetail
  type: ''
property_count: 26
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-commerce-payments-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"CommercePayment\": {\n      \"@id\": \"ns:CommercePayment\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"properties\": \"ns:properties\",\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"ns:updatedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"archived\": {\n          \"@id\": \"ns:archived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"archivedAt\": {\n          \"@id\": \"ns:archivedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"associations\": \"ns:associations\",\n        \"propertiesWithHistory\": \"ns:propertiesWithHistory\"\n      }\n    },\n    \"CommercePaymentInput\":\
  \ {\n      \"@id\": \"ns:CommercePaymentInput\",\n      \"@context\": {\n        \"properties\": \"ns:properties\",\n        \"associations\": \"ns:associations\"\n      }\n    },\n    \"CommercePaymentPatch\": {\n      \"@id\": \"ns:CommercePaymentPatch\",\n      \"@context\": {\n        \"properties\": \"ns:properties\"\n      }\n    },\n    \"CommercePaymentCollection\": {\n      \"@id\": \"ns:CommercePaymentCollection\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BatchReadRequest\": {\n      \"@id\": \"ns:BatchReadRequest\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\",\n        \"properties\": \"ns:properties\",\n        \"propertiesWithHistory\": \"ns:propertiesWithHistory\",\n        \"idProperty\": {\n          \"@id\": \"ns:idProperty\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BatchReadInputItem\"\
  : {\n      \"@id\": \"ns:BatchReadInputItem\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BatchReadResponse\": {\n      \"@id\": \"ns:BatchReadResponse\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"results\": \"ns:results\",\n        \"requestedAt\": {\n          \"@id\": \"ns:requestedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startedAt\": {\n          \"@id\": \"ns:startedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"completedAt\": {\n          \"@id\": \"ns:completedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"numErrors\": {\n          \"@id\": \"ns:numErrors\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"errors\": \"ns:errors\",\n        \"links\": \"ns:links\"\n      }\n    },\n    \"BatchArchiveRequest\"\
  : {\n      \"@id\": \"ns:BatchArchiveRequest\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchCreateRequest\": {\n      \"@id\": \"ns:BatchCreateRequest\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchCreateResponse\": {\n      \"@id\": \"ns:BatchCreateResponse\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"results\": \"ns:results\",\n        \"requestedAt\": {\n          \"@id\": \"ns:requestedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startedAt\": {\n          \"@id\": \"ns:startedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"completedAt\": {\n          \"@id\": \"ns:completedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"numErrors\": {\n          \"@id\": \"ns:numErrors\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"errors\": \"\
  ns:errors\",\n        \"links\": \"ns:links\"\n      }\n    },\n    \"BatchUpdateRequest\": {\n      \"@id\": \"ns:BatchUpdateRequest\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchUpdateInputItem\": {\n      \"@id\": \"ns:BatchUpdateInputItem\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"properties\": \"ns:properties\",\n        \"idProperty\": {\n          \"@id\": \"ns:idProperty\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BatchUpdateResponse\": {\n      \"@id\": \"ns:BatchUpdateResponse\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"results\": \"ns:results\",\n        \"requestedAt\": {\n          \"@id\": \"ns:requestedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startedAt\": {\n          \"@id\": \"ns:startedAt\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"completedAt\": {\n          \"@id\": \"ns:completedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"numErrors\": {\n          \"@id\": \"ns:numErrors\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"errors\": \"ns:errors\",\n        \"links\": \"ns:links\"\n      }\n    },\n    \"SearchRequest\": {\n      \"@id\": \"ns:SearchRequest\",\n      \"@context\": {\n        \"query\": {\n          \"@id\": \"ns:query\",\n          \"@type\": \"xsd:string\"\n        },\n        \"limit\": {\n          \"@id\": \"ns:limit\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"after\": {\n          \"@id\": \"ns:after\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sorts\": \"ns:sorts\",\n        \"properties\": \"ns:properties\",\n        \"filterGroups\": \"ns:filterGroups\"\n      }\n    },\n    \"SearchResponse\": {\n      \"@id\": \"ns:SearchResponse\",\n      \"@context\":\
  \ {\n        \"total\": {\n          \"@id\": \"ns:total\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"FilterGroup\": {\n      \"@id\": \"ns:FilterGroup\",\n      \"@context\": {\n        \"filters\": \"ns:filters\"\n      }\n    },\n    \"Filter\": {\n      \"@id\": \"ns:Filter\",\n      \"@context\": {\n        \"propertyName\": {\n          \"@id\": \"ns:propertyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"operator\": {\n          \"@id\": \"ns:operator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"value\": {\n          \"@id\": \"ns:value\",\n          \"@type\": \"xsd:string\"\n        },\n        \"values\": \"ns:values\",\n        \"highValue\": {\n          \"@id\": \"ns:highValue\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"SortOption\"\
  : {\n      \"@id\": \"ns:SortOption\",\n      \"@context\": {\n        \"propertyName\": {\n          \"@id\": \"ns:propertyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"direction\": {\n          \"@id\": \"ns:direction\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"AssociationInput\": {\n      \"@id\": \"ns:AssociationInput\",\n      \"@context\": {\n        \"to\": \"ns:to\",\n        \"types\": \"ns:types\"\n      }\n    },\n    \"AssociationType\": {\n      \"@id\": \"ns:AssociationType\",\n      \"@context\": {\n        \"associationCategory\": {\n          \"@id\": \"ns:associationCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"associationTypeId\": {\n          \"@id\": \"ns:associationTypeId\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"AssociationResult\": {\n      \"@id\": \"ns:AssociationResult\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\"\
  : {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"PropertyHistory\": {\n      \"@id\": \"ns:PropertyHistory\",\n      \"@context\": {\n        \"value\": {\n          \"@id\": \"ns:value\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timestamp\": {\n          \"@id\": \"ns:timestamp\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sourceType\": {\n          \"@id\": \"ns:sourceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sourceId\": {\n          \"@id\": \"ns:sourceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sourceLabel\": {\n          \"@id\": \"ns:sourceLabel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedByUserId\": {\n          \"@id\": \"ns:updatedByUserId\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"Paging\": {\n      \"@id\": \"ns:Paging\",\n      \"@context\": {\n        \"next\": \"ns:next\"\
  ,\n        \"prev\": \"ns:prev\"\n      }\n    },\n    \"BatchError\": {\n      \"@id\": \"ns:BatchError\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"errors\": \"ns:errors\",\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\",\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\"\
  : {\n          \"@id\": \"ns:correlationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"errors\": \"ns:errors\",\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\"\n      }\n    },\n    \"ErrorDetail\": {\n      \"@id\": \"ns:ErrorDetail\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"in\": {\n          \"@id\": \"ns:in\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\"\n     \
  \ }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-commerce-payments-context.jsonld
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
