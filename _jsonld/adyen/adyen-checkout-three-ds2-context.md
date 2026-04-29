---
class_count: 4
classes:
- ThreeDS2RequestData
- ThreeDS2RequestFields
- ThreeDS2ResponseData
- ThreeDS2Result
context_file: json-ld/adyen-checkout-three-ds2-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-three-ds2-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Three Ds2 from Adyen.
layout: jsonld
name: Adyen Checkout Three Ds2 Context
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
  name: acctInfo
  type: string
- container: ''
  name: acctType
  type: string
- container: ''
  name: acquirerBIN
  type: string
- container: ''
  name: acquirerMerchantID
  type: string
- container: ''
  name: addrMatch
  type: string
- container: ''
  name: authenticationOnly
  type: boolean
- container: ''
  name: challengeIndicator
  type: string
- container: ''
  name: deviceChannel
  type: string
- container: ''
  name: deviceRenderOptions
  type: string
- container: ''
  name: homePhone
  type: string
- container: ''
  name: mcc
  type: string
- container: ''
  name: merchantName
  type: string
- container: ''
  name: messageVersion
  type: string
- container: ''
  name: mobilePhone
  type: string
- container: ''
  name: notificationURL
  type: string
- container: ''
  name: payTokenInd
  type: boolean
- container: ''
  name: paymentAuthenticationUseCase
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: purchaseInstalData
  type: string
- container: ''
  name: recurringExpiry
  type: string
- container: ''
  name: recurringFrequency
  type: string
- container: ''
  name: sdkAppID
  type: string
- container: ''
  name: sdkEncData
  type: string
- container: ''
  name: sdkEphemPubKey
  type: string
- container: ''
  name: sdkMaxTimeout
  type: integer
- container: ''
  name: sdkReferenceNumber
  type: string
- container: ''
  name: sdkTransID
  type: string
- container: ''
  name: sdkVersion
  type: string
- container: ''
  name: threeDSCompInd
  type: string
- container: ''
  name: threeDSRequestorAuthenticationInd
  type: string
- container: ''
  name: threeDSRequestorAuthenticationInfo
  type: string
- container: ''
  name: threeDSRequestorChallengeInd
  type: string
- container: ''
  name: threeDSRequestorID
  type: string
- container: ''
  name: threeDSRequestorName
  type: string
- container: ''
  name: threeDSRequestorPriorAuthenticationInfo
  type: string
- container: ''
  name: threeDSRequestorURL
  type: string
- container: ''
  name: transType
  type: string
- container: ''
  name: transactionType
  type: string
- container: ''
  name: whiteListStatus
  type: string
- container: ''
  name: workPhone
  type: string
- container: ''
  name: acsChallengeMandated
  type: string
- container: ''
  name: acsOperatorID
  type: string
- container: ''
  name: acsReferenceNumber
  type: string
- container: ''
  name: acsSignedContent
  type: string
- container: ''
  name: acsTransID
  type: string
- container: ''
  name: acsURL
  type: string
- container: ''
  name: authenticationType
  type: string
- container: ''
  name: cardHolderInfo
  type: string
- container: ''
  name: cavvAlgorithm
  type: string
- container: ''
  name: dsReferenceNumber
  type: string
- container: ''
  name: dsTransID
  type: string
- container: ''
  name: exemptionIndicator
  type: string
- container: ''
  name: riskScore
  type: string
- container: ''
  name: threeDSServerTransID
  type: string
- container: ''
  name: transStatus
  type: string
- container: ''
  name: transStatusReason
  type: string
- container: ''
  name: authenticationValue
  type: string
- container: ''
  name: challengeCancel
  type: string
- container: ''
  name: eci
  type: string
- container: ''
  name: timestamp
  type: string
property_count: 60
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-three-ds2-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ThreeDS2RequestData\": \"adyen:ThreeDS2RequestData\",\n    \"ThreeDS2RequestFields\": \"adyen:ThreeDS2RequestFields\",\n    \"ThreeDS2ResponseData\": \"adyen:ThreeDS2ResponseData\",\n    \"ThreeDS2Result\": \"adyen:ThreeDS2Result\",\n    \"acctInfo\": {\n      \"@id\": \"adyen:acctInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"acctType\": {\n      \"@id\": \"adyen:acctType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"acquirerBIN\": {\n      \"@id\": \"adyen:acquirerBIN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"acquirerMerchantID\": {\n      \"@id\": \"adyen:acquirerMerchantID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addrMatch\": {\n      \"@id\": \"adyen:addrMatch\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"authenticationOnly\": {\n      \"@id\": \"adyen:authenticationOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"challengeIndicator\": {\n      \"@id\": \"adyen:challengeIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceChannel\": {\n      \"@id\": \"adyen:deviceChannel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceRenderOptions\": {\n      \"@id\": \"adyen:deviceRenderOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"homePhone\": {\n      \"@id\": \"adyen:homePhone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mcc\": {\n      \"@id\": \"adyen:mcc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantName\": {\n      \"@id\": \"adyen:merchantName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageVersion\": {\n      \"@id\": \"adyen:messageVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mobilePhone\": {\n      \"@id\": \"adyen:mobilePhone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notificationURL\"\
  : {\n      \"@id\": \"adyen:notificationURL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payTokenInd\": {\n      \"@id\": \"adyen:payTokenInd\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"paymentAuthenticationUseCase\": {\n      \"@id\": \"adyen:paymentAuthenticationUseCase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"adyen:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purchaseInstalData\": {\n      \"@id\": \"adyen:purchaseInstalData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringExpiry\": {\n      \"@id\": \"adyen:recurringExpiry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringFrequency\": {\n      \"@id\": \"adyen:recurringFrequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sdkAppID\": {\n      \"@id\": \"adyen:sdkAppID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sdkEncData\": {\n      \"@id\": \"adyen:sdkEncData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sdkEphemPubKey\"\
  : {\n      \"@id\": \"adyen:sdkEphemPubKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sdkMaxTimeout\": {\n      \"@id\": \"adyen:sdkMaxTimeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sdkReferenceNumber\": {\n      \"@id\": \"adyen:sdkReferenceNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sdkTransID\": {\n      \"@id\": \"adyen:sdkTransID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sdkVersion\": {\n      \"@id\": \"adyen:sdkVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSCompInd\": {\n      \"@id\": \"adyen:threeDSCompInd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSRequestorAuthenticationInd\": {\n      \"@id\": \"adyen:threeDSRequestorAuthenticationInd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSRequestorAuthenticationInfo\": {\n      \"@id\": \"adyen:threeDSRequestorAuthenticationInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSRequestorChallengeInd\": {\n      \"@id\": \"adyen:threeDSRequestorChallengeInd\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSRequestorID\": {\n      \"@id\": \"adyen:threeDSRequestorID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSRequestorName\": {\n      \"@id\": \"adyen:threeDSRequestorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSRequestorPriorAuthenticationInfo\": {\n      \"@id\": \"adyen:threeDSRequestorPriorAuthenticationInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSRequestorURL\": {\n      \"@id\": \"adyen:threeDSRequestorURL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transType\": {\n      \"@id\": \"adyen:transType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionType\": {\n      \"@id\": \"adyen:transactionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"whiteListStatus\": {\n      \"@id\": \"adyen:whiteListStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workPhone\": {\n      \"@id\": \"adyen:workPhone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"acsChallengeMandated\"\
  : {\n      \"@id\": \"adyen:acsChallengeMandated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"acsOperatorID\": {\n      \"@id\": \"adyen:acsOperatorID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"acsReferenceNumber\": {\n      \"@id\": \"adyen:acsReferenceNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"acsSignedContent\": {\n      \"@id\": \"adyen:acsSignedContent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"acsTransID\": {\n      \"@id\": \"adyen:acsTransID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"acsURL\": {\n      \"@id\": \"adyen:acsURL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authenticationType\": {\n      \"@id\": \"adyen:authenticationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardHolderInfo\": {\n      \"@id\": \"adyen:cardHolderInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cavvAlgorithm\": {\n      \"@id\": \"adyen:cavvAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dsReferenceNumber\": {\n   \
  \   \"@id\": \"adyen:dsReferenceNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dsTransID\": {\n      \"@id\": \"adyen:dsTransID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exemptionIndicator\": {\n      \"@id\": \"adyen:exemptionIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskScore\": {\n      \"@id\": \"adyen:riskScore\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSServerTransID\": {\n      \"@id\": \"adyen:threeDSServerTransID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transStatus\": {\n      \"@id\": \"adyen:transStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transStatusReason\": {\n      \"@id\": \"adyen:transStatusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authenticationValue\": {\n      \"@id\": \"adyen:authenticationValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"challengeCancel\": {\n      \"@id\": \"adyen:challengeCancel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eci\": {\n      \"\
  @id\": \"adyen:eci\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"adyen:timestamp\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-three-ds2-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
