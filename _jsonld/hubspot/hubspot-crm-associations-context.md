---
class_count: 0
classes: []
context_file: json-ld/hubspot-crm-associations-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-associations-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Crm Associations from HubSpot.
layout: jsonld
name: Hubspot Crm Associations Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Association
  type: ''
- container: ''
  name: AssociationType
  type: ''
- container: ''
  name: AssociationDefinition
  type: ''
- container: ''
  name: AssociationLabel
  type: ''
- container: ''
  name: CreateAssociationInput
  type: ''
- container: ''
  name: ObjectReference
  type: ''
- container: ''
  name: AssociationTypeInput
  type: ''
- container: ''
  name: BatchAssociationReadInput
  type: ''
- container: ''
  name: BatchAssociationCreateInput
  type: ''
- container: ''
  name: BatchAssociationCreateItem
  type: ''
- container: ''
  name: BatchAssociationArchiveInput
  type: ''
- container: ''
  name: BatchAssociationArchiveItem
  type: ''
- container: ''
  name: CreateLabelInput
  type: ''
- container: ''
  name: AssociationResult
  type: ''
- container: ''
  name: BatchAssociationResponse
  type: ''
- container: ''
  name: PagingNext
  type: ''
- container: ''
  name: Paging
  type: ''
- container: ''
  name: AssociationDefinitionCollection
  type: ''
- container: ''
  name: AssociationLabelCollection
  type: ''
- container: ''
  name: StandardError
  type: ''
- container: ''
  name: ErrorDetail
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 22
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-crm-associations-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"Association\": {\n      \"@id\": \"ns:Association\",\n      \"@context\": {\n        \"toObjectId\": {\n          \"@id\": \"ns:toObjectId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"associationTypes\": \"ns:associationTypes\"\n      }\n    },\n    \"AssociationType\": {\n      \"@id\": \"ns:AssociationType\",\n      \"@context\": {\n        \"associationCategory\": {\n          \"@id\": \"ns:associationCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"associationTypeId\": {\n          \"@id\": \"ns:associationTypeId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"AssociationDefinition\": {\n      \"@id\": \"ns:AssociationDefinition\",\n      \"@context\": {\n\
  \        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fromObjectTypeId\": {\n          \"@id\": \"ns:fromObjectTypeId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"toObjectTypeId\": {\n          \"@id\": \"ns:toObjectTypeId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"inverseLabel\": {\n          \"@id\": \"ns:inverseLabel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"AssociationLabel\": {\n      \"@id\": \"ns:AssociationLabel\",\n      \"@context\": {\n        \"typeId\": {\n          \"@id\": \"ns:typeId\",\n          \"@type\": \"xsd:integer\"\n      \
  \  },\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"CreateAssociationInput\": {\n      \"@id\": \"ns:CreateAssociationInput\",\n      \"@context\": {\n        \"to\": {\n          \"@id\": \"ns:to\",\n          \"@type\": \"xsd:string\"\n        },\n        \"types\": \"ns:types\"\n      }\n    },\n    \"ObjectReference\": {\n      \"@id\": \"ns:ObjectReference\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"AssociationTypeInput\": {\n      \"@id\": \"ns:AssociationTypeInput\",\n      \"@context\": {\n        \"associationCategory\": {\n          \"@id\": \"ns:associationCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"associationTypeId\": {\n          \"@id\": \"ns:associationTypeId\"\
  ,\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"BatchAssociationReadInput\": {\n      \"@id\": \"ns:BatchAssociationReadInput\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchAssociationCreateInput\": {\n      \"@id\": \"ns:BatchAssociationCreateInput\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchAssociationCreateItem\": {\n      \"@id\": \"ns:BatchAssociationCreateItem\",\n      \"@context\": {\n        \"from\": {\n          \"@id\": \"ns:from\",\n          \"@type\": \"xsd:string\"\n        },\n        \"to\": {\n          \"@id\": \"ns:to\",\n          \"@type\": \"xsd:string\"\n        },\n        \"types\": \"ns:types\"\n      }\n    },\n    \"BatchAssociationArchiveInput\": {\n      \"@id\": \"ns:BatchAssociationArchiveInput\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchAssociationArchiveItem\": {\n      \"@id\": \"ns:BatchAssociationArchiveItem\"\
  ,\n      \"@context\": {\n        \"from\": {\n          \"@id\": \"ns:from\",\n          \"@type\": \"xsd:string\"\n        },\n        \"to\": {\n          \"@id\": \"ns:to\",\n          \"@type\": \"xsd:string\"\n        },\n        \"types\": \"ns:types\"\n      }\n    },\n    \"CreateLabelInput\": {\n      \"@id\": \"ns:CreateLabelInput\",\n      \"@context\": {\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"inverseLabel\": {\n          \"@id\": \"ns:inverseLabel\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"AssociationResult\": {\n      \"@id\": \"ns:AssociationResult\",\n      \"@context\": {\n        \"from\": {\n          \"@id\": \"ns:from\",\n          \"@type\": \"xsd:string\"\n        },\n        \"to\": \"ns:to\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n \
  \         \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BatchAssociationResponse\": {\n      \"@id\": \"ns:BatchAssociationResponse\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"results\": \"ns:results\",\n        \"requestedAt\": {\n          \"@id\": \"ns:requestedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startedAt\": {\n          \"@id\": \"ns:startedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"completedAt\": {\n          \"@id\": \"ns:completedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"numErrors\": {\n          \"@id\": \"ns:numErrors\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"errors\": \"ns:errors\",\n        \"links\": \"ns:links\"\n      }\n    },\n    \"PagingNext\": {\n      \"@id\": \"ns:PagingNext\",\n      \"@context\": {\n        \"after\": {\n          \"@id\": \"ns:after\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"link\": {\n          \"@id\": \"ns:link\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Paging\": {\n      \"@id\": \"ns:Paging\",\n      \"@context\": {\n        \"next\": {\n          \"@id\": \"ns:next\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"AssociationDefinitionCollection\": {\n      \"@id\": \"ns:AssociationDefinitionCollection\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"AssociationLabelCollection\": {\n      \"@id\": \"ns:AssociationLabelCollection\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"StandardError\": {\n      \"@id\": \"ns:StandardError\",\n      \"@context\"\
  : {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"errors\": \"ns:errors\",\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\"\n      }\n    },\n    \"ErrorDetail\": {\n      \"@id\": \"ns:ErrorDetail\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"in\": {\n          \"@id\"\
  : \"ns:in\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\"\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\",\n        \"errors\": \"ns:errors\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-associations-context.jsonld
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
