---
class_count: 40
classes:
- AdditionalBankIdentification
- Address-2
- AmountAdjustment
- Amount
- AULocalAccountIdentification
- BalanceMutation
- BalancePlatformNotificationResponse
- BankAccountV3
- BRLocalAccountIdentification
- CALocalAccountIdentification
- CounterpartyV3
- CZLocalAccountIdentification
- DKLocalAccountIdentification
- HULocalAccountIdentification
- IbanAccountIdentification
- MerchantData
- NameLocation
- NOLocalAccountIdentification
- NumberAndBicAccountIdentification
- PartyIdentification-2
- PaymentInstrument
- PLLocalAccountIdentification
- RelayedAuthorisationData-2
- ResourceReference
- Resource
- SELocalAccountIdentification
- SGLocalAccountIdentification
- TransactionEventViolation
- TransactionRuleReference
- TransactionRuleSource
- TransactionRulesResult
- TransferEvent
- TransferNotificationData
- TransferNotificationRequest
- TransferNotificationTransferTracking
- TransferNotificationValidationFact
- UKLocalAccountIdentification
- USLocalAccountIdentification
- name
- description
context_file: json-ld/adyen-accounting-notifications-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounting-notifications-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounting Notifications from Adyen.
layout: jsonld
name: Adyen Accounting Notifications Context
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
  name: code
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: line1
  type: string
- container: ''
  name: line2
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: stateOrProvince
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: amountAdjustmentType
  type: string
- container: ''
  name: basepoints
  type: integer
- container: ''
  name: currency
  type: string
- container: ''
  name: value
  type: integer
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: bsbCode
  type: string
- container: ''
  name: balance
  type: integer
- container: ''
  name: received
  type: integer
- container: ''
  name: reserved
  type: integer
- container: ''
  name: notificationResponse
  type: string
- container: ''
  name: accountHolder
  type: string
- container: ''
  name: accountIdentification
  type: string
- container: ''
  name: bankCode
  type: string
- container: ''
  name: branchNumber
  type: string
- container: ''
  name: institutionNumber
  type: string
- container: ''
  name: transitNumber
  type: string
- container: ''
  name: balanceAccountId
  type: string
- container: ''
  name: bankAccount
  type: string
- container: ''
  name: merchant
  type: string
- container: ''
  name: transferInstrumentId
  type: string
- container: ''
  name: iban
  type: string
- container: ''
  name: mcc
  type: string
- container: ''
  name: merchantId
  type: string
- container: ''
  name: nameLocation
  type: string
- container: ''
  name: countryOfOrigin
  type: string
- container: ''
  name: rawData
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: additionalBankIdentification
  type: string
- container: ''
  name: bic
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: fullName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: tokenType
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: balancePlatform
  type: string
- container: ''
  name: creationDate
  type: dateTime
- container: ''
  name: clearingNumber
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: transactionRule
  type: string
- container: ''
  name: transactionRuleSource
  type: string
- container: ''
  name: advice
  type: string
- container: ''
  name: allRulesPassed
  type: boolean
- container: set
  name: failedTransactionRules
  type: string
- container: ''
  name: score
  type: integer
- container: set
  name: amountAdjustments
  type: string
- container: ''
  name: bookingDate
  type: dateTime
- container: set
  name: mutations
  type: string
- container: ''
  name: originalAmount
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: transactionId
  type: string
- container: ''
  name: updateDate
  type: dateTime
- container: ''
  name: valueDate
  type: dateTime
- container: ''
  name: balanceAccount
  type: string
- container: set
  name: balances
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: counterparty
  type: string
- container: ''
  name: direction
  type: string
- container: set
  name: events
  type: string
- container: ''
  name: modificationMerchantReference
  type: string
- container: ''
  name: modificationPspReference
  type: string
- container: ''
  name: panEntryMode
  type: string
- container: ''
  name: paymentInstrument
  type: string
- container: ''
  name: paymentInstrumentId
  type: string
- container: ''
  name: paymentMerchantReference
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: processingType
  type: string
- container: ''
  name: pspPaymentReference
  type: string
- container: ''
  name: referenceForBeneficiary
  type: string
- container: ''
  name: relayedAuthorisationData
  type: string
- container: ''
  name: sequenceNumber
  type: integer
- container: ''
  name: tracking
  type: string
- container: ''
  name: transactionRulesResult
  type: string
- container: set
  name: validationFacts
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: environment
  type: string
- container: ''
  name: result
  type: string
- container: ''
  name: sortCode
  type: string
- container: ''
  name: accountType
  type: string
- container: ''
  name: routingNumber
  type: string
property_count: 91
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounting-notifications-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AdditionalBankIdentification\": \"adyen:AdditionalBankIdentification\",\n    \"Address-2\": \"adyen:Address-2\",\n    \"AmountAdjustment\": \"adyen:AmountAdjustment\",\n    \"Amount\": \"adyen:Amount\",\n    \"AULocalAccountIdentification\": \"adyen:AULocalAccountIdentification\",\n    \"BalanceMutation\": \"adyen:BalanceMutation\",\n    \"BalancePlatformNotificationResponse\": \"adyen:BalancePlatformNotificationResponse\",\n    \"BankAccountV3\": \"adyen:BankAccountV3\",\n    \"BRLocalAccountIdentification\": \"adyen:BRLocalAccountIdentification\",\n    \"CALocalAccountIdentification\": \"adyen:CALocalAccountIdentification\",\n    \"CounterpartyV3\": \"adyen:CounterpartyV3\",\n    \"CZLocalAccountIdentification\": \"adyen:CZLocalAccountIdentification\"\
  ,\n    \"DKLocalAccountIdentification\": \"adyen:DKLocalAccountIdentification\",\n    \"HULocalAccountIdentification\": \"adyen:HULocalAccountIdentification\",\n    \"IbanAccountIdentification\": \"adyen:IbanAccountIdentification\",\n    \"MerchantData\": \"adyen:MerchantData\",\n    \"NameLocation\": \"adyen:NameLocation\",\n    \"NOLocalAccountIdentification\": \"adyen:NOLocalAccountIdentification\",\n    \"NumberAndBicAccountIdentification\": \"adyen:NumberAndBicAccountIdentification\",\n    \"PartyIdentification-2\": \"adyen:PartyIdentification-2\",\n    \"PaymentInstrument\": \"adyen:PaymentInstrument\",\n    \"PLLocalAccountIdentification\": \"adyen:PLLocalAccountIdentification\",\n    \"RelayedAuthorisationData-2\": \"adyen:RelayedAuthorisationData-2\",\n    \"ResourceReference\": \"adyen:ResourceReference\",\n    \"Resource\": \"adyen:Resource\",\n    \"SELocalAccountIdentification\": \"adyen:SELocalAccountIdentification\",\n    \"SGLocalAccountIdentification\": \"adyen:SGLocalAccountIdentification\"\
  ,\n    \"TransactionEventViolation\": \"adyen:TransactionEventViolation\",\n    \"TransactionRuleReference\": \"adyen:TransactionRuleReference\",\n    \"TransactionRuleSource\": \"adyen:TransactionRuleSource\",\n    \"TransactionRulesResult\": \"adyen:TransactionRulesResult\",\n    \"TransferEvent\": \"adyen:TransferEvent\",\n    \"TransferNotificationData\": \"adyen:TransferNotificationData\",\n    \"TransferNotificationRequest\": \"adyen:TransferNotificationRequest\",\n    \"TransferNotificationTransferTracking\": \"adyen:TransferNotificationTransferTracking\",\n    \"TransferNotificationValidationFact\": \"adyen:TransferNotificationValidationFact\",\n    \"UKLocalAccountIdentification\": \"adyen:UKLocalAccountIdentification\",\n    \"USLocalAccountIdentification\": \"adyen:USLocalAccountIdentification\",\n    \"code\": {\n      \"@id\": \"adyen:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"city\": {\n      \"@id\": \"adyen:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"adyen:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"line1\": {\n      \"@id\": \"adyen:line1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"line2\": {\n      \"@id\": \"adyen:line2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"adyen:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateOrProvince\": {\n      \"@id\": \"adyen:stateOrProvince\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amountAdjustmentType\": {\n      \"@id\": \"adyen:amountAdjustmentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"basepoints\": {\n      \"@id\": \"adyen:basepoints\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currency\": {\n      \"@id\": \"adyen:currency\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"value\": {\n      \"@id\": \"adyen:value\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"accountNumber\": {\n      \"@id\": \"adyen:accountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bsbCode\": {\n      \"@id\": \"adyen:bsbCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balance\": {\n      \"@id\": \"adyen:balance\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"received\": {\n      \"@id\": \"adyen:received\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"reserved\": {\n      \"@id\": \"adyen:reserved\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"notificationResponse\": {\n      \"@id\": \"adyen:notificationResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountHolder\": {\n      \"@id\": \"adyen:accountHolder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountIdentification\": {\n      \"@id\": \"adyen:accountIdentification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankCode\": {\n      \"@id\": \"adyen:bankCode\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"branchNumber\": {\n      \"@id\": \"adyen:branchNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"institutionNumber\": {\n      \"@id\": \"adyen:institutionNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transitNumber\": {\n      \"@id\": \"adyen:transitNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balanceAccountId\": {\n      \"@id\": \"adyen:balanceAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccount\": {\n      \"@id\": \"adyen:bankAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchant\": {\n      \"@id\": \"adyen:merchant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transferInstrumentId\": {\n      \"@id\": \"adyen:transferInstrumentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iban\": {\n      \"@id\": \"adyen:iban\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mcc\": {\n      \"@id\": \"adyen:mcc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantId\"\
  : {\n      \"@id\": \"adyen:merchantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nameLocation\": {\n      \"@id\": \"adyen:nameLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryOfOrigin\": {\n      \"@id\": \"adyen:countryOfOrigin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"rawData\": {\n      \"@id\": \"adyen:rawData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"adyen:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additionalBankIdentification\": {\n      \"@id\": \"adyen:additionalBankIdentification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bic\": {\n      \"@id\": \"adyen:bic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"adyen:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"adyen:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fullName\": {\n      \"@id\": \"adyen:fullName\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"adyen:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenType\": {\n      \"@id\": \"adyen:tokenType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"adyen:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"balancePlatform\": {\n      \"@id\": \"adyen:balancePlatform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"adyen:creationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"clearingNumber\": {\n      \"@id\": \"adyen:clearingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"adyen:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionRule\"\
  : {\n      \"@id\": \"adyen:transactionRule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionRuleSource\": {\n      \"@id\": \"adyen:transactionRuleSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"advice\": {\n      \"@id\": \"adyen:advice\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allRulesPassed\": {\n      \"@id\": \"adyen:allRulesPassed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"failedTransactionRules\": {\n      \"@id\": \"adyen:failedTransactionRules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"score\": {\n      \"@id\": \"adyen:score\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"amountAdjustments\": {\n      \"@id\": \"adyen:amountAdjustments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bookingDate\": {\n      \"@id\": \"adyen:bookingDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"mutations\": {\n      \"@id\": \"adyen:mutations\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originalAmount\": {\n      \"@id\": \"adyen:originalAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionId\": {\n      \"@id\": \"adyen:transactionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updateDate\": {\n      \"@id\": \"adyen:updateDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"valueDate\": {\n      \"@id\": \"adyen:valueDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"balanceAccount\": {\n      \"@id\": \"adyen:balanceAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balances\": {\n      \"@id\": \"adyen:balances\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"adyen:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"counterparty\": {\n      \"@id\": \"adyen:counterparty\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"direction\": {\n      \"@id\": \"adyen:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"events\": {\n      \"@id\": \"adyen:events\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modificationMerchantReference\": {\n      \"@id\": \"adyen:modificationMerchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modificationPspReference\": {\n      \"@id\": \"adyen:modificationPspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"panEntryMode\": {\n      \"@id\": \"adyen:panEntryMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentInstrument\": {\n      \"@id\": \"adyen:paymentInstrument\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentInstrumentId\": {\n      \"@id\": \"adyen:paymentInstrumentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMerchantReference\": {\n      \"@id\": \"adyen:paymentMerchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n\
  \      \"@id\": \"adyen:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processingType\": {\n      \"@id\": \"adyen:processingType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspPaymentReference\": {\n      \"@id\": \"adyen:pspPaymentReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"referenceForBeneficiary\": {\n      \"@id\": \"adyen:referenceForBeneficiary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relayedAuthorisationData\": {\n      \"@id\": \"adyen:relayedAuthorisationData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sequenceNumber\": {\n      \"@id\": \"adyen:sequenceNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tracking\": {\n      \"@id\": \"adyen:tracking\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionRulesResult\": {\n      \"@id\": \"adyen:transactionRulesResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validationFacts\": {\n      \"@id\": \"adyen:validationFacts\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"adyen:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environment\": {\n      \"@id\": \"adyen:environment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"adyen:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sortCode\": {\n      \"@id\": \"adyen:sortCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountType\": {\n      \"@id\": \"adyen:accountType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routingNumber\": {\n      \"@id\": \"adyen:routingNumber\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounting-notifications-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
