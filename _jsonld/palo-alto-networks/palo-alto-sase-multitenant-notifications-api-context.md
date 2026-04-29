---
class_count: 14
classes:
- EmailChannelDetails
- EmailDetails
- MtNotifAggKey
- MtNotification
- NotifCategoryDetail
- NotifChannel
- NotifFilter
- NotifListApiReqBody
- NotifProfile
- NotifStateChangeApiBody
- NotifSubCategoryDetail
- NotifTypeDetail
- SortBy
- WebhookChannelDetails
context_file: json-ld/palo-alto-sase-multitenant-notifications-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-multitenant-notifications-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Sase Multitenant Notifications Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Sase Multitenant Notifications Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: action
  type: string
- container: ''
  name: aggKey
  type: reference
- container: ''
  name: authType
  type: string
- container: ''
  name: bestPractice
  type: boolean
- container: ''
  name: body
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: createdTime
  type: decimal
- container: ''
  name: description
  type: string
- container: ''
  name: emailChannelDetails
  type: reference
- container: ''
  name: emailId
  type: string
- container: set
  name: emails
  type: reference
- container: set
  name: excludeTenantList
  type: string
- container: set
  name: failureTenant
  type: string
- container: ''
  name: field
  type: string
- container: set
  name: filters
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: impactedTenantCount
  type: decimal
- container: set
  name: impactedTenants
  type: string
- container: ''
  name: inAppFlag
  type: boolean
- container: ''
  name: name
  type: string
- container: ''
  name: needLicense
  type: boolean
- container: set
  name: notifCategoryList
  type: reference
- container: set
  name: notifChannels
  type: reference
- container: set
  name: notifIds
  type: string
- container: ''
  name: notifReadState
  type: string
- container: ''
  name: notifType
  type: string
- container: set
  name: notifTypeDetails
  type: reference
- container: ''
  name: num
  type: integer
- container: ''
  name: opState
  type: string
- container: ''
  name: page
  type: reference
- container: ''
  name: profileName
  type: string
- container: ''
  name: readState
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: sortBy
  type: string
- container: set
  name: sortByList
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: subCategory
  type: string
- container: set
  name: subCategoryList
  type: reference
- container: set
  name: successTenant
  type: string
- container: ''
  name: tag
  type: reference
- container: ''
  name: template
  type: reference
- container: ''
  name: templateJson
  type: string
- container: set
  name: tenantList
  type: string
- container: ''
  name: token
  type: string
- container: ''
  name: tsgId
  type: string
- container: ''
  name: type
  type: string
- container: set
  name: urls
  type: string
- container: set
  name: values
  type: string
- container: ''
  name: webhookChannelDetails
  type: reference
property_count: 49
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-sase-multitenant-notifications-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EmailChannelDetails\": \"pan:EmailChannelDetails\",\n    \"EmailDetails\": \"pan:EmailDetails\",\n    \"MtNotifAggKey\": \"pan:MtNotifAggKey\",\n    \"MtNotification\": \"pan:MtNotification\",\n    \"NotifCategoryDetail\": \"pan:NotifCategoryDetail\",\n    \"NotifChannel\": \"pan:NotifChannel\",\n    \"NotifFilter\": \"pan:NotifFilter\",\n    \"NotifListApiReqBody\": \"pan:NotifListApiReqBody\",\n    \"NotifProfile\": \"pan:NotifProfile\",\n    \"NotifStateChangeApiBody\": \"pan:NotifStateChangeApiBody\",\n    \"NotifSubCategoryDetail\": \"pan:NotifSubCategoryDetail\",\n    \"NotifTypeDetail\": \"pan:NotifTypeDetail\",\n    \"SortBy\": \"pan:SortBy\",\n    \"WebhookChannelDetails\": \"pan:WebhookChannelDetails\",\n    \"action\": {\n     \
  \ \"@id\": \"pan:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aggKey\": {\n      \"@id\": \"pan:aggKey\",\n      \"@type\": \"@id\"\n    },\n    \"authType\": {\n      \"@id\": \"pan:authType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bestPractice\": {\n      \"@id\": \"pan:bestPractice\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"body\": {\n      \"@id\": \"pan:body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdTime\": {\n      \"@id\": \"pan:createdTime\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"emailChannelDetails\": {\n      \"@id\": \"pan:emailChannelDetails\",\n      \"@type\": \"@id\"\n    },\n    \"emailId\": {\n      \"@id\": \"pan:emailId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"emails\": {\n      \"@id\": \"pan:emails\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"excludeTenantList\": {\n      \"@id\": \"pan:excludeTenantList\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureTenant\": {\n      \"@id\": \"pan:failureTenant\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"field\": {\n      \"@id\": \"pan:field\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filters\": {\n      \"@id\": \"pan:filters\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"impactedTenantCount\": {\n      \"@id\": \"pan:impactedTenantCount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"impactedTenants\": {\n      \"@id\": \"pan:impactedTenants\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inAppFlag\": {\n      \"@id\": \"pan:inAppFlag\",\n      \"@type\": \"xsd:boolean\"\
  \n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"needLicense\": {\n      \"@id\": \"pan:needLicense\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"notifCategoryList\": {\n      \"@id\": \"pan:notifCategoryList\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"notifChannels\": {\n      \"@id\": \"pan:notifChannels\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"notifIds\": {\n      \"@id\": \"pan:notifIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notifReadState\": {\n      \"@id\": \"pan:notifReadState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notifType\": {\n      \"@id\": \"pan:notifType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notifTypeDetails\": {\n      \"@id\": \"pan:notifTypeDetails\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"num\": {\n      \"@id\": \"pan:num\",\n     \
  \ \"@type\": \"xsd:integer\"\n    },\n    \"opState\": {\n      \"@id\": \"pan:opState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"page\": {\n      \"@id\": \"pan:page\",\n      \"@type\": \"@id\"\n    },\n    \"profileName\": {\n      \"@id\": \"pan:profileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"readState\": {\n      \"@id\": \"pan:readState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"pan:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sortBy\": {\n      \"@id\": \"pan:sortBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sortByList\": {\n      \"@id\": \"pan:sortByList\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subCategory\": {\n      \"@id\": \"pan:subCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subCategoryList\": {\n      \"@id\": \"pan:subCategoryList\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"successTenant\": {\n      \"@id\": \"pan:successTenant\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tag\": {\n      \"@id\": \"pan:tag\",\n      \"@type\": \"@id\"\n    },\n    \"template\": {\n      \"@id\": \"pan:template\",\n      \"@type\": \"@id\"\n    },\n    \"templateJson\": {\n      \"@id\": \"pan:templateJson\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenantList\": {\n      \"@id\": \"pan:tenantList\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token\": {\n      \"@id\": \"pan:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tsgId\": {\n      \"@id\": \"pan:tsgId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"urls\": {\n      \"@id\": \"pan:urls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n\
  \      \"@id\": \"pan:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webhookChannelDetails\": {\n      \"@id\": \"pan:webhookChannelDetails\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-multitenant-notifications-api-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
