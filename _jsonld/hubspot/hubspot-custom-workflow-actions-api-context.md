---
class_count: 22
classes:
- CallbackCompletionRequest
- BatchCallbackCompletionRequest
- BatchCallbackInput
- BatchCallbackResponse
- BatchCallbackError
- ActionDefinition
- ActionDefinitionInput
- ActionDefinitionPatch
- ActionLabels
- InputField
- OutputField
- FieldTypeDefinition
- FieldOption
- ObjectRequestOptions
- ActionFunctionReference
- ActionDefinitionCollection
- ActionFunction
- ActionFunctionInput
- ActionFunctionCollection
- ActionDefinitionRevision
- ActionDefinitionRevisionCollection
- Paging
context_file: json-ld/hubspot-custom-workflow-actions-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-custom-workflow-actions-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Custom Workflow Actions Api from HubSpot.
layout: jsonld
name: Hubspot Custom Workflow Actions Api Context
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
  name: outputFields
  type: reference
- container: set
  name: inputs
  type: reference
- container: ''
  name: callbackId
  type: string
- container: ''
  name: status
  type: string
- container: set
  name: errors
  type: reference
- container: ''
  name: message
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: revisionId
  type: string
- container: ''
  name: actionUrl
  type: reference
- container: ''
  name: labels
  type: reference
- container: set
  name: inputFields
  type: reference
- container: set
  name: objectTypes
  type: string
- container: ''
  name: objectRequestOptions
  type: reference
- container: ''
  name: published
  type: boolean
- container: set
  name: functions
  type: reference
- container: ''
  name: actionName
  type: string
- container: ''
  name: actionDescription
  type: string
- container: ''
  name: appDisplayName
  type: string
- container: ''
  name: actionCardContent
  type: string
- container: ''
  name: typeDefinition
  type: reference
- container: set
  name: supportedValueTypes
  type: string
- container: ''
  name: isRequired
  type: boolean
- container: ''
  name: name
  type: ''
- container: ''
  name: type
  type: string
- container: ''
  name: fieldType
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: description
  type: ''
- container: set
  name: options
  type: reference
- container: ''
  name: value
  type: string
- container: ''
  name: displayOrder
  type: integer
- container: set
  name: properties
  type: string
- container: ''
  name: functionType
  type: string
- container: set
  name: results
  type: reference
- container: ''
  name: paging
  type: reference
- container: ''
  name: functionSource
  type: string
- container: ''
  name: definition
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: next
  type: reference
property_count: 39
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-custom-workflow-actions-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CallbackCompletionRequest\": \"hubspot:CallbackCompletionRequest\",\n    \"outputFields\": {\n      \"@id\": \"hubspot:outputFields\",\n      \"@type\": \"@id\"\n    },\n    \"BatchCallbackCompletionRequest\": \"hubspot:BatchCallbackCompletionRequest\",\n    \"inputs\": {\n      \"@id\": \"hubspot:inputs\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"BatchCallbackInput\": \"hubspot:BatchCallbackInput\",\n    \"callbackId\": {\n      \"@id\": \"hubspot:callbackId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BatchCallbackResponse\": \"hubspot:BatchCallbackResponse\",\n    \"status\": {\n      \"@id\": \"hubspot:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n     \
  \ \"@id\": \"hubspot:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"BatchCallbackError\": \"hubspot:BatchCallbackError\",\n    \"message\": {\n      \"@id\": \"hubspot:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"hubspot:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ActionDefinition\": \"hubspot:ActionDefinition\",\n    \"id\": {\n      \"@id\": \"hubspot:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revisionId\": {\n      \"@id\": \"hubspot:revisionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionUrl\": {\n      \"@id\": \"hubspot:actionUrl\",\n      \"@type\": \"@id\"\n    },\n    \"labels\": {\n      \"@id\": \"hubspot:labels\",\n      \"@type\": \"@id\"\n    },\n    \"inputFields\": {\n      \"@id\": \"hubspot:inputFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"objectTypes\": {\n      \"@id\": \"hubspot:objectTypes\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objectRequestOptions\": {\n      \"@id\": \"hubspot:objectRequestOptions\",\n      \"@type\": \"@id\"\n    },\n    \"published\": {\n      \"@id\": \"hubspot:published\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"functions\": {\n      \"@id\": \"hubspot:functions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"ActionDefinitionInput\": \"hubspot:ActionDefinitionInput\",\n    \"ActionDefinitionPatch\": \"hubspot:ActionDefinitionPatch\",\n    \"ActionLabels\": \"hubspot:ActionLabels\",\n    \"actionName\": {\n      \"@id\": \"hubspot:actionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionDescription\": {\n      \"@id\": \"hubspot:actionDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appDisplayName\": {\n      \"@id\": \"hubspot:appDisplayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionCardContent\": {\n      \"@id\": \"hubspot:actionCardContent\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"InputField\": \"hubspot:InputField\",\n    \"typeDefinition\": {\n      \"@id\": \"hubspot:typeDefinition\",\n      \"@type\": \"@id\"\n    },\n    \"supportedValueTypes\": {\n      \"@id\": \"hubspot:supportedValueTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isRequired\": {\n      \"@id\": \"hubspot:isRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"OutputField\": \"hubspot:OutputField\",\n    \"FieldTypeDefinition\": \"hubspot:FieldTypeDefinition\",\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"type\": {\n      \"@id\": \"hubspot:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldType\": {\n      \"@id\": \"hubspot:fieldType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"hubspot:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"options\": {\n    \
  \  \"@id\": \"hubspot:options\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"FieldOption\": \"hubspot:FieldOption\",\n    \"value\": {\n      \"@id\": \"hubspot:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayOrder\": {\n      \"@id\": \"hubspot:displayOrder\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ObjectRequestOptions\": \"hubspot:ObjectRequestOptions\",\n    \"properties\": {\n      \"@id\": \"hubspot:properties\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ActionFunctionReference\": \"hubspot:ActionFunctionReference\",\n    \"functionType\": {\n      \"@id\": \"hubspot:functionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ActionDefinitionCollection\": \"hubspot:ActionDefinitionCollection\",\n    \"results\": {\n      \"@id\": \"hubspot:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"paging\": {\n      \"@id\": \"hubspot:paging\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"ActionFunction\": \"hubspot:ActionFunction\",\n    \"functionSource\": {\n      \"@id\": \"hubspot:functionSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ActionFunctionInput\": \"hubspot:ActionFunctionInput\",\n    \"ActionFunctionCollection\": \"hubspot:ActionFunctionCollection\",\n    \"ActionDefinitionRevision\": \"hubspot:ActionDefinitionRevision\",\n    \"definition\": {\n      \"@id\": \"hubspot:definition\",\n      \"@type\": \"@id\"\n    },\n    \"createdAt\": {\n      \"@id\": \"hubspot:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ActionDefinitionRevisionCollection\": \"hubspot:ActionDefinitionRevisionCollection\",\n    \"Paging\": \"hubspot:Paging\",\n    \"next\": {\n      \"@id\": \"hubspot:next\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-custom-workflow-actions-api-context.jsonld
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
