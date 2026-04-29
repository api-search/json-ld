---
class_count: 29
classes:
- DeliveryRequest
- MarketingHistory
- OrgUnit
- PrivacyRequest
- PrivacyRequestResponse
- Profile
- ProfileCreate
- ProfileUpdate
- PushEventRequest
- PushEventResponse
- PushEventsRequest
- QueryDefinition
- QueryResult
- SOAPFault
- Service
- ServiceCreate
- ServiceUpdate
- SessionLogonRequest
- SessionLogonResponse
- SubscriptionRequest
- TransactionalEvent
- TransactionalEventResponse
- TransactionalEventStatus
- WorkflowCommand
- WorkflowPostEventRequest
- WorkflowRequest
- WriteCollectionRequest
- WriteRequest
- WriteResponse
context_file: json-ld/adobe-campaign-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-campaign/refs/heads/main/json-ld/adobe-campaign-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Campaign from Adobe Campaign.
layout: jsonld
name: Adobe Campaign Context
namespaces:
- prefix: ac
  uri: https://developer.adobe.com/campaign/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: PKey
  type: string
- container: ''
  name: activity
  type: string
- container: ''
  name: birthDate
  type: string
- container: ''
  name: blackList
  type: boolean
- container: ''
  name: blackListEmail
  type: boolean
- container: ''
  name: blackListMobile
  type: boolean
- container: ''
  name: collection
  type: reference
- container: ''
  name: create
  type: boolean
- container: ''
  name: created
  type: dateTime
- container: ''
  name: ctx
  type: reference
- container: ''
  name: deliveryId
  type: integer
- container: ''
  name: deliveryName
  type: string
- container: ''
  name: detail
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: end
  type: dateTime
- container: ''
  name: entity
  type: reference
- container: ''
  name: eventId
  type: integer
- container: set
  name: events
  type: string
- container: ''
  name: expiration
  type: dateTime
- container: ''
  name: faultcode
  type: string
- container: ''
  name: faultstring
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: gender
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: lastModified
  type: dateTime
- container: ''
  name: lastName
  type: string
- container: ''
  name: messageType
  type: string
- container: ''
  name: method
  type: string
- container: ''
  name: mobilePhone
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: namespaceName
  type: string
- container: ''
  name: parentTitle
  type: string
- container: ''
  name: phone
  type: string
- container: ''
  name: preferredLanguage
  type: string
- container: ''
  name: primaryKey
  type: string
- container: ''
  name: pushPlatform
  type: string
- container: ''
  name: queryDef
  type: reference
- container: ''
  name: reason
  type: string
- container: ''
  name: recipient
  type: reference
- container: ''
  name: reconciliationValue
  type: string
- container: ''
  name: regulation
  type: string
- container: ''
  name: resultSet
  type: reference
- container: ''
  name: rtEvent
  type: reference
- container: ''
  name: scheduled
  type: dateTime
- container: ''
  name: securityToken
  type: string
- container: ''
  name: service
  type: reference
- container: ''
  name: serviceName
  type: string
- container: ''
  name: sessionInfo
  type: reference
- container: ''
  name: sessionToken
  type: string
- container: ''
  name: start
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: strLogin
  type: string
- container: ''
  name: strPassword
  type: string
- container: ''
  name: subscriptions
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: variables
  type: reference
- container: ''
  name: workflowId
  type: integer
property_count: 57
provider_name: Adobe Campaign
provider_slug: adobe-campaign
slug: adobe-campaign-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ac\": \"https://developer.adobe.com/campaign/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DeliveryRequest\": \"ac:DeliveryRequest\",\n    \"MarketingHistory\": \"ac:MarketingHistory\",\n    \"OrgUnit\": \"ac:OrgUnit\",\n    \"PrivacyRequest\": \"ac:PrivacyRequest\",\n    \"PrivacyRequestResponse\": \"ac:PrivacyRequestResponse\",\n    \"Profile\": \"ac:Profile\",\n    \"ProfileCreate\": \"ac:ProfileCreate\",\n    \"ProfileUpdate\": \"ac:ProfileUpdate\",\n    \"PushEventRequest\": \"ac:PushEventRequest\",\n    \"PushEventResponse\": \"ac:PushEventResponse\",\n    \"PushEventsRequest\": \"ac:PushEventsRequest\",\n    \"QueryDefinition\": \"ac:QueryDefinition\",\n    \"QueryResult\": \"ac:QueryResult\",\n    \"SOAPFault\": \"ac:SOAPFault\",\n    \"Service\": \"ac:Service\",\n    \"ServiceCreate\": \"ac:ServiceCreate\",\n    \"ServiceUpdate\": \"ac:ServiceUpdate\"\
  ,\n    \"SessionLogonRequest\": \"ac:SessionLogonRequest\",\n    \"SessionLogonResponse\": \"ac:SessionLogonResponse\",\n    \"SubscriptionRequest\": \"ac:SubscriptionRequest\",\n    \"TransactionalEvent\": \"ac:TransactionalEvent\",\n    \"TransactionalEventResponse\": \"ac:TransactionalEventResponse\",\n    \"TransactionalEventStatus\": \"ac:TransactionalEventStatus\",\n    \"WorkflowCommand\": \"ac:WorkflowCommand\",\n    \"WorkflowPostEventRequest\": \"ac:WorkflowPostEventRequest\",\n    \"WorkflowRequest\": \"ac:WorkflowRequest\",\n    \"WriteCollectionRequest\": \"ac:WriteCollectionRequest\",\n    \"WriteRequest\": \"ac:WriteRequest\",\n    \"WriteResponse\": \"ac:WriteResponse\",\n    \"PKey\": {\n      \"@id\": \"ac:PKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activity\": {\n      \"@id\": \"ac:activity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"birthDate\": {\n      \"@id\": \"ac:birthDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blackList\": {\n \
  \     \"@id\": \"ac:blackList\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"blackListEmail\": {\n      \"@id\": \"ac:blackListEmail\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"blackListMobile\": {\n      \"@id\": \"ac:blackListMobile\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"collection\": {\n      \"@id\": \"ac:collection\",\n      \"@type\": \"@id\"\n    },\n    \"create\": {\n      \"@id\": \"ac:create\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"created\": {\n      \"@id\": \"ac:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ctx\": {\n      \"@id\": \"ac:ctx\",\n      \"@type\": \"@id\"\n    },\n    \"deliveryId\": {\n      \"@id\": \"ac:deliveryId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deliveryName\": {\n      \"@id\": \"ac:deliveryName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"ac:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"ac:email\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"end\": {\n      \"@id\": \"ac:end\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"entity\": {\n      \"@id\": \"ac:entity\",\n      \"@type\": \"@id\"\n    },\n    \"eventId\": {\n      \"@id\": \"ac:eventId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"events\": {\n      \"@id\": \"ac:events\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiration\": {\n      \"@id\": \"ac:expiration\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"faultcode\": {\n      \"@id\": \"ac:faultcode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"faultstring\": {\n      \"@id\": \"ac:faultstring\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"ac:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gender\": {\n      \"@id\": \"ac:gender\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"ac:label\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"lastModified\": {\n      \"@id\": \"ac:lastModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastName\": {\n      \"@id\": \"ac:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageType\": {\n      \"@id\": \"ac:messageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"method\": {\n      \"@id\": \"ac:method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mobilePhone\": {\n      \"@id\": \"ac:mobilePhone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"ac:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespaceName\": {\n      \"@id\": \"ac:namespaceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentTitle\": {\n      \"@id\": \"ac:parentTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phone\": {\n      \"@id\": \"ac:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preferredLanguage\": {\n      \"@id\": \"ac:preferredLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primaryKey\"\
  : {\n      \"@id\": \"ac:primaryKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pushPlatform\": {\n      \"@id\": \"ac:pushPlatform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queryDef\": {\n      \"@id\": \"ac:queryDef\",\n      \"@type\": \"@id\"\n    },\n    \"reason\": {\n      \"@id\": \"ac:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recipient\": {\n      \"@id\": \"ac:recipient\",\n      \"@type\": \"@id\"\n    },\n    \"reconciliationValue\": {\n      \"@id\": \"ac:reconciliationValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regulation\": {\n      \"@id\": \"ac:regulation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultSet\": {\n      \"@id\": \"ac:resultSet\",\n      \"@type\": \"@id\"\n    },\n    \"rtEvent\": {\n      \"@id\": \"ac:rtEvent\",\n      \"@type\": \"@id\"\n    },\n    \"scheduled\": {\n      \"@id\": \"ac:scheduled\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"securityToken\": {\n      \"@id\": \"ac:securityToken\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"ac:service\",\n      \"@type\": \"@id\"\n    },\n    \"serviceName\": {\n      \"@id\": \"ac:serviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo\": {\n      \"@id\": \"ac:sessionInfo\",\n      \"@type\": \"@id\"\n    },\n    \"sessionToken\": {\n      \"@id\": \"ac:sessionToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start\": {\n      \"@id\": \"ac:start\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"ac:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strLogin\": {\n      \"@id\": \"ac:strLogin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strPassword\": {\n      \"@id\": \"ac:strPassword\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriptions\": {\n      \"@id\": \"ac:subscriptions\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"ac:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variables\"\
  : {\n      \"@id\": \"ac:variables\",\n      \"@type\": \"@id\"\n    },\n    \"workflowId\": {\n      \"@id\": \"ac:workflowId\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-campaign/refs/heads/main/json-ld/adobe-campaign-context.jsonld
tags:
- Campaign Management
- Customer Experience
- Email Marketing
- Marketing Automation
- Multi-Channel Marketing
- JSON-LD
- Linked Data
- Semantic Web
---
