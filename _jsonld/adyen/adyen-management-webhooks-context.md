---
class_count: 17
classes:
- AccountCapabilityData
- AccountCreateNotificationData
- AccountNotificationResponse
- AccountUpdateNotificationData
- CapabilityProblemEntity-recursive
- CapabilityProblemEntity
- CapabilityProblem
- MerchantCreatedNotificationRequest
- MerchantUpdatedNotificationRequest
- MidServiceNotificationData
- PaymentMethodCreatedNotificationRequest
- PaymentMethodNotificationResponse
- PaymentMethodRequestRemovedNotificationRequest
- PaymentMethodScheduledForRemovalNotificationRequest
- RemediatingAction
- VerificationError-recursive
- VerificationError
context_file: json-ld/adyen-management-webhooks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-webhooks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Webhooks from Adyen.
layout: jsonld
name: Adyen Management Webhooks Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: allowed
  type: boolean
- container: ''
  name: allowedLevel
  type: string
- container: ''
  name: capability
  type: string
- container: set
  name: problems
  type: string
- container: ''
  name: requested
  type: boolean
- container: ''
  name: requestedLevel
  type: string
- container: ''
  name: verificationDeadline
  type: dateTime
- container: ''
  name: verificationStatus
  type: string
- container: ''
  name: capabilities
  type: reference
- container: ''
  name: companyId
  type: string
- container: ''
  name: legalEntityId
  type: string
- container: ''
  name: merchantId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: notificationResponse
  type: string
- container: set
  name: documents
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: entity
  type: string
- container: set
  name: verificationErrors
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: data
  type: string
- container: ''
  name: environment
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: reference
  type: string
- container: ''
  name: storeId
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: message
  type: string
- container: set
  name: remediatingActions
  type: string
- container: set
  name: subErrors
  type: string
property_count: 30
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-webhooks-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccountCapabilityData\": \"adyen:AccountCapabilityData\",\n    \"AccountCreateNotificationData\": \"adyen:AccountCreateNotificationData\",\n    \"AccountNotificationResponse\": \"adyen:AccountNotificationResponse\",\n    \"AccountUpdateNotificationData\": \"adyen:AccountUpdateNotificationData\",\n    \"CapabilityProblemEntity-recursive\": \"adyen:CapabilityProblemEntity-recursive\",\n    \"CapabilityProblemEntity\": \"adyen:CapabilityProblemEntity\",\n    \"CapabilityProblem\": \"adyen:CapabilityProblem\",\n    \"MerchantCreatedNotificationRequest\": \"adyen:MerchantCreatedNotificationRequest\",\n    \"MerchantUpdatedNotificationRequest\": \"adyen:MerchantUpdatedNotificationRequest\",\n    \"MidServiceNotificationData\": \"adyen:MidServiceNotificationData\"\
  ,\n    \"PaymentMethodCreatedNotificationRequest\": \"adyen:PaymentMethodCreatedNotificationRequest\",\n    \"PaymentMethodNotificationResponse\": \"adyen:PaymentMethodNotificationResponse\",\n    \"PaymentMethodRequestRemovedNotificationRequest\": \"adyen:PaymentMethodRequestRemovedNotificationRequest\",\n    \"PaymentMethodScheduledForRemovalNotificationRequest\": \"adyen:PaymentMethodScheduledForRemovalNotificationRequest\",\n    \"RemediatingAction\": \"adyen:RemediatingAction\",\n    \"VerificationError-recursive\": \"adyen:VerificationError-recursive\",\n    \"VerificationError\": \"adyen:VerificationError\",\n    \"allowed\": {\n      \"@id\": \"adyen:allowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"allowedLevel\": {\n      \"@id\": \"adyen:allowedLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capability\": {\n      \"@id\": \"adyen:capability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"problems\": {\n      \"@id\": \"adyen:problems\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requested\": {\n      \"@id\": \"adyen:requested\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"requestedLevel\": {\n      \"@id\": \"adyen:requestedLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verificationDeadline\": {\n      \"@id\": \"adyen:verificationDeadline\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"verificationStatus\": {\n      \"@id\": \"adyen:verificationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capabilities\": {\n      \"@id\": \"adyen:capabilities\",\n      \"@type\": \"@id\"\n    },\n    \"companyId\": {\n      \"@id\": \"adyen:companyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalEntityId\": {\n      \"@id\": \"adyen:legalEntityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantId\": {\n      \"@id\": \"adyen:merchantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"notificationResponse\": {\n      \"@id\": \"adyen:notificationResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documents\": {\n      \"@id\": \"adyen:documents\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"adyen:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entity\": {\n      \"@id\": \"adyen:entity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verificationErrors\": {\n      \"@id\": \"adyen:verificationErrors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"adyen:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"data\": {\n      \"@id\": \"adyen:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environment\": {\n     \
  \ \"@id\": \"adyen:environment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"adyen:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storeId\": {\n      \"@id\": \"adyen:storeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"adyen:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"adyen:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remediatingActions\": {\n      \"@id\": \"adyen:remediatingActions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subErrors\": {\n      \"@id\": \"adyen:subErrors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-webhooks-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
