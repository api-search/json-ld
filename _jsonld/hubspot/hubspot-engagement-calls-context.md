---
class_count: 0
classes: []
context_file: json-ld/hubspot-engagement-calls-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-engagement-calls-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Engagement Calls from HubSpot.
layout: jsonld
name: Hubspot Engagement Calls Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Call
  type: ''
- container: ''
  name: PropertyHistory
  type: ''
- container: ''
  name: CallCollectionResponse
  type: ''
- container: ''
  name: CallSearchResponse
  type: ''
- container: ''
  name: BatchCallsResponse
  type: ''
- container: ''
  name: BatchError
  type: ''
- container: ''
  name: CallCreateRequest
  type: ''
- container: ''
  name: CallUpdateRequest
  type: ''
- container: ''
  name: BatchCreateCallsRequest
  type: ''
- container: ''
  name: BatchReadCallsRequest
  type: ''
- container: ''
  name: BatchReadInput
  type: ''
- container: ''
  name: BatchUpdateCallsRequest
  type: ''
- container: ''
  name: BatchUpdateInput
  type: ''
- container: ''
  name: BatchArchiveCallsRequest
  type: ''
- container: ''
  name: CallSearchRequest
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
  name: GdprDeleteRequest
  type: ''
- container: ''
  name: Paging
  type: ''
- container: ''
  name: NextPage
  type: ''
- container: ''
  name: Error
  type: ''
- container: ''
  name: ErrorDetail
  type: ''
property_count: 25
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-engagement-calls-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"Call\": {\n      \"@id\": \"ns:Call\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"properties\": \"ns:properties\",\n        \"propertiesWithHistory\": \"ns:propertiesWithHistory\",\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"ns:updatedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"archived\": {\n          \"@id\": \"ns:archived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"archivedAt\": {\n          \"@id\": \"ns:archivedAt\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"PropertyHistory\": {\n      \"@id\": \"ns:PropertyHistory\",\n      \"@context\": {\n        \"\
  value\": {\n          \"@id\": \"ns:value\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timestamp\": {\n          \"@id\": \"ns:timestamp\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sourceType\": {\n          \"@id\": \"ns:sourceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sourceId\": {\n          \"@id\": \"ns:sourceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sourceLabel\": {\n          \"@id\": \"ns:sourceLabel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedByUserId\": {\n          \"@id\": \"ns:updatedByUserId\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"CallCollectionResponse\": {\n      \"@id\": \"ns:CallCollectionResponse\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"CallSearchResponse\": {\n      \"@id\"\
  : \"ns:CallSearchResponse\",\n      \"@context\": {\n        \"total\": {\n          \"@id\": \"ns:total\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BatchCallsResponse\": {\n      \"@id\": \"ns:BatchCallsResponse\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"results\": \"ns:results\",\n        \"requestedAt\": {\n          \"@id\": \"ns:requestedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startedAt\": {\n          \"@id\": \"ns:startedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"completedAt\": {\n          \"@id\": \"ns:completedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"errors\": \"ns:errors\",\n        \"links\": \"ns:links\"\n      }\n    },\n    \"\
  BatchError\": {\n      \"@id\": \"ns:BatchError\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\",\n        \"errors\": \"ns:errors\"\n      }\n    },\n    \"CallCreateRequest\": {\n      \"@id\": \"ns:CallCreateRequest\",\n      \"@context\": {\n        \"properties\": \"ns:properties\",\n        \"associations\": \"ns:associations\"\n      }\n    },\n    \"CallUpdateRequest\": {\n      \"@id\": \"ns:CallUpdateRequest\",\n      \"@context\": {\n        \"properties\": \"ns:properties\"\n      }\n    },\n    \"BatchCreateCallsRequest\": {\n      \"@id\": \"ns:BatchCreateCallsRequest\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n\
  \    },\n    \"BatchReadCallsRequest\": {\n      \"@id\": \"ns:BatchReadCallsRequest\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\",\n        \"properties\": \"ns:properties\",\n        \"propertiesWithHistory\": \"ns:propertiesWithHistory\",\n        \"idProperty\": {\n          \"@id\": \"ns:idProperty\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BatchReadInput\": {\n      \"@id\": \"ns:BatchReadInput\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BatchUpdateCallsRequest\": {\n      \"@id\": \"ns:BatchUpdateCallsRequest\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchUpdateInput\": {\n      \"@id\": \"ns:BatchUpdateInput\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"properties\": \"ns:properties\"\n      }\n   \
  \ },\n    \"BatchArchiveCallsRequest\": {\n      \"@id\": \"ns:BatchArchiveCallsRequest\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"CallSearchRequest\": {\n      \"@id\": \"ns:CallSearchRequest\",\n      \"@context\": {\n        \"filterGroups\": \"ns:filterGroups\",\n        \"sorts\": \"ns:sorts\",\n        \"query\": {\n          \"@id\": \"ns:query\",\n          \"@type\": \"xsd:string\"\n        },\n        \"properties\": \"ns:properties\",\n        \"limit\": {\n          \"@id\": \"ns:limit\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"after\": {\n          \"@id\": \"ns:after\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"FilterGroup\": {\n      \"@id\": \"ns:FilterGroup\",\n      \"@context\": {\n        \"filters\": \"ns:filters\"\n      }\n    },\n    \"Filter\": {\n      \"@id\": \"ns:Filter\",\n      \"@context\": {\n        \"propertyName\": {\n          \"@id\": \"ns:propertyName\",\n\
  \          \"@type\": \"xsd:string\"\n        },\n        \"operator\": {\n          \"@id\": \"ns:operator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"value\": {\n          \"@id\": \"ns:value\",\n          \"@type\": \"xsd:string\"\n        },\n        \"values\": \"ns:values\",\n        \"highValue\": {\n          \"@id\": \"ns:highValue\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"SortOption\": {\n      \"@id\": \"ns:SortOption\",\n      \"@context\": {\n        \"propertyName\": {\n          \"@id\": \"ns:propertyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"direction\": {\n          \"@id\": \"ns:direction\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"AssociationInput\": {\n      \"@id\": \"ns:AssociationInput\",\n      \"@context\": {\n        \"to\": \"ns:to\",\n        \"types\": \"ns:types\"\n      }\n    },\n    \"AssociationType\": {\n      \"@id\": \"ns:AssociationType\",\n\
  \      \"@context\": {\n        \"associationCategory\": {\n          \"@id\": \"ns:associationCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"associationTypeId\": {\n          \"@id\": \"ns:associationTypeId\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"GdprDeleteRequest\": {\n      \"@id\": \"ns:GdprDeleteRequest\",\n      \"@context\": {\n        \"objectId\": {\n          \"@id\": \"ns:objectId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"idProperty\": {\n          \"@id\": \"ns:idProperty\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Paging\": {\n      \"@id\": \"ns:Paging\",\n      \"@context\": {\n        \"next\": {\n          \"@id\": \"ns:next\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"NextPage\": {\n      \"@id\": \"ns:NextPage\",\n      \"@context\": {\n        \"after\": {\n          \"@id\": \"ns:after\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"link\": {\n          \"@id\": \"ns:link\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\",\n        \"errors\": \"ns:errors\"\n      }\n    },\n    \"ErrorDetail\": {\n      \"@id\": \"ns:ErrorDetail\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n\
  \          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"in\": {\n          \"@id\": \"ns:in\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-engagement-calls-context.jsonld
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
