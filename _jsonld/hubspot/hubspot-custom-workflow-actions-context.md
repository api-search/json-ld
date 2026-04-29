---
class_count: 0
classes: []
context_file: json-ld/hubspot-custom-workflow-actions-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-custom-workflow-actions-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Custom Workflow Actions from HubSpot.
layout: jsonld
name: Hubspot Custom Workflow Actions Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: CallbackCompletionRequest
  type: ''
- container: ''
  name: BatchCallbackCompletionRequest
  type: ''
- container: ''
  name: BatchCallbackInput
  type: ''
- container: ''
  name: BatchCallbackResponse
  type: ''
- container: ''
  name: BatchCallbackError
  type: ''
- container: ''
  name: ActionDefinition
  type: ''
- container: ''
  name: ActionDefinitionInput
  type: ''
- container: ''
  name: ActionDefinitionPatch
  type: ''
- container: ''
  name: ActionLabels
  type: ''
- container: ''
  name: InputField
  type: ''
- container: ''
  name: OutputField
  type: ''
- container: ''
  name: FieldTypeDefinition
  type: ''
- container: ''
  name: FieldOption
  type: ''
- container: ''
  name: ObjectRequestOptions
  type: ''
- container: ''
  name: ActionFunctionReference
  type: ''
- container: ''
  name: ActionDefinitionCollection
  type: ''
- container: ''
  name: ActionFunction
  type: ''
- container: ''
  name: ActionFunctionInput
  type: ''
- container: ''
  name: ActionFunctionCollection
  type: ''
- container: ''
  name: ActionDefinitionRevision
  type: ''
- container: ''
  name: ActionDefinitionRevisionCollection
  type: ''
- container: ''
  name: Paging
  type: ''
- container: ''
  name: Error
  type: ''
- container: ''
  name: ErrorDetail
  type: ''
property_count: 24
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-custom-workflow-actions-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"CallbackCompletionRequest\": {\n      \"@id\": \"ns:CallbackCompletionRequest\",\n      \"@context\": {\n        \"outputFields\": \"ns:outputFields\"\n      }\n    },\n    \"BatchCallbackCompletionRequest\": {\n      \"@id\": \"ns:BatchCallbackCompletionRequest\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchCallbackInput\": {\n      \"@id\": \"ns:BatchCallbackInput\",\n      \"@context\": {\n        \"callbackId\": {\n          \"@id\": \"ns:callbackId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"outputFields\": \"ns:outputFields\"\n      }\n    },\n    \"BatchCallbackResponse\": {\n      \"@id\": \"ns:BatchCallbackResponse\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"errors\"\
  : \"ns:errors\"\n      }\n    },\n    \"BatchCallbackError\": {\n      \"@id\": \"ns:BatchCallbackError\",\n      \"@context\": {\n        \"callbackId\": {\n          \"@id\": \"ns:callbackId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ActionDefinition\": {\n      \"@id\": \"ns:ActionDefinition\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"revisionId\": {\n          \"@id\": \"ns:revisionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"actionUrl\": {\n          \"@id\": \"ns:actionUrl\",\n          \"@type\": \"xsd:string\"\n        },\n        \"labels\": {\n          \"@id\": \"ns:labels\",\n          \"@type\": \"xsd:string\"\n  \
  \      },\n        \"inputFields\": \"ns:inputFields\",\n        \"outputFields\": \"ns:outputFields\",\n        \"objectTypes\": \"ns:objectTypes\",\n        \"objectRequestOptions\": {\n          \"@id\": \"ns:objectRequestOptions\",\n          \"@type\": \"xsd:string\"\n        },\n        \"published\": {\n          \"@id\": \"ns:published\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"functions\": \"ns:functions\"\n      }\n    },\n    \"ActionDefinitionInput\": {\n      \"@id\": \"ns:ActionDefinitionInput\",\n      \"@context\": {\n        \"actionUrl\": {\n          \"@id\": \"ns:actionUrl\",\n          \"@type\": \"xsd:string\"\n        },\n        \"labels\": {\n          \"@id\": \"ns:labels\",\n          \"@type\": \"xsd:string\"\n        },\n        \"inputFields\": \"ns:inputFields\",\n        \"outputFields\": \"ns:outputFields\",\n        \"objectTypes\": \"ns:objectTypes\",\n        \"objectRequestOptions\": {\n          \"@id\": \"ns:objectRequestOptions\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"published\": {\n          \"@id\": \"ns:published\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"ActionDefinitionPatch\": {\n      \"@id\": \"ns:ActionDefinitionPatch\",\n      \"@context\": {\n        \"actionUrl\": {\n          \"@id\": \"ns:actionUrl\",\n          \"@type\": \"xsd:string\"\n        },\n        \"labels\": {\n          \"@id\": \"ns:labels\",\n          \"@type\": \"xsd:string\"\n        },\n        \"inputFields\": \"ns:inputFields\",\n        \"outputFields\": \"ns:outputFields\",\n        \"objectTypes\": \"ns:objectTypes\",\n        \"objectRequestOptions\": {\n          \"@id\": \"ns:objectRequestOptions\",\n          \"@type\": \"xsd:string\"\n        },\n        \"published\": {\n          \"@id\": \"ns:published\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"ActionLabels\": {\n      \"@id\": \"ns:ActionLabels\",\n      \"@context\": {\n    \
  \    \"actionName\": {\n          \"@id\": \"ns:actionName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"actionDescription\": {\n          \"@id\": \"ns:actionDescription\",\n          \"@type\": \"xsd:string\"\n        },\n        \"appDisplayName\": {\n          \"@id\": \"ns:appDisplayName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"actionCardContent\": {\n          \"@id\": \"ns:actionCardContent\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"InputField\": {\n      \"@id\": \"ns:InputField\",\n      \"@context\": {\n        \"typeDefinition\": {\n          \"@id\": \"ns:typeDefinition\",\n          \"@type\": \"xsd:string\"\n        },\n        \"supportedValueTypes\": \"ns:supportedValueTypes\",\n        \"isRequired\": {\n          \"@id\": \"ns:isRequired\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"OutputField\": {\n      \"@id\": \"ns:OutputField\",\n      \"@context\": {\n        \"\
  typeDefinition\": {\n          \"@id\": \"ns:typeDefinition\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"FieldTypeDefinition\": {\n      \"@id\": \"ns:FieldTypeDefinition\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fieldType\": {\n          \"@id\": \"ns:fieldType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"options\": \"ns:options\"\n      }\n    },\n    \"FieldOption\": {\n      \"@id\": \"ns:FieldOption\",\n      \"@context\": {\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"xsd:string\"\n\
  \        },\n        \"value\": {\n          \"@id\": \"ns:value\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayOrder\": {\n          \"@id\": \"ns:displayOrder\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"ObjectRequestOptions\": {\n      \"@id\": \"ns:ObjectRequestOptions\",\n      \"@context\": {\n        \"properties\": \"ns:properties\"\n      }\n    },\n    \"ActionFunctionReference\": {\n      \"@id\": \"ns:ActionFunctionReference\",\n      \"@context\": {\n        \"functionType\": {\n          \"@id\": \"ns:functionType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ActionDefinitionCollection\": {\n      \"@id\": \"ns:ActionDefinitionCollection\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\
  \n        }\n      }\n    },\n    \"ActionFunction\": {\n      \"@id\": \"ns:ActionFunction\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"functionType\": {\n          \"@id\": \"ns:functionType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"functionSource\": {\n          \"@id\": \"ns:functionSource\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ActionFunctionInput\": {\n      \"@id\": \"ns:ActionFunctionInput\",\n      \"@context\": {\n        \"functionSource\": {\n          \"@id\": \"ns:functionSource\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ActionFunctionCollection\": {\n      \"@id\": \"ns:ActionFunctionCollection\",\n      \"@context\": {\n        \"results\": \"ns:results\"\n      }\n    },\n    \"ActionDefinitionRevision\": {\n      \"@id\": \"ns:ActionDefinitionRevision\",\n      \"@context\": {\n        \"revisionId\"\
  : {\n          \"@id\": \"ns:revisionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"definition\": {\n          \"@id\": \"ns:definition\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ActionDefinitionRevisionCollection\": {\n      \"@id\": \"ns:ActionDefinitionRevisionCollection\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Paging\": {\n      \"@id\": \"ns:Paging\",\n      \"@context\": {\n        \"next\": \"ns:next\"\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"errors\": \"ns:errors\",\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\"\n      }\n    },\n    \"ErrorDetail\": {\n      \"@id\": \"ns:ErrorDetail\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"in\": {\n          \"@id\": \"ns:in\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-custom-workflow-actions-context.jsonld
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
