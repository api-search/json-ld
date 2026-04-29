---
class_count: 0
classes: []
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/mastercard/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Mastercard.
layout: jsonld
name: context Context
namespaces:
- prefix: mc
  uri: https://developer.mastercard.com/ns/
- prefix: iso
  uri: https://www.iso.org/standard/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
properties:
- container: ''
  name: Payment
  type: ''
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: Card
  type: ''
- container: ''
  name: Merchant
  type: ''
- container: ''
  name: MerchantAddress
  type: ''
- container: ''
  name: GeoLocation
  type: ''
- container: ''
  name: FraudAlert
  type: ''
- container: ''
  name: AlertOutcome
  type: ''
- container: ''
  name: Cardholder
  type: ''
- container: ''
  name: PaymentParty
  type: ''
property_count: 10
provider_name: Mastercard
provider_slug: mastercard
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"mc\": \"https://developer.mastercard.com/ns/\",\n    \"iso\": \"https://www.iso.org/standard/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"Payment\": {\n      \"@id\": \"schema:PayAction\",\n      \"@context\": {\n        \"paymentId\": \"schema:identifier\",\n        \"paymentType\": \"schema:paymentMethod\",\n        \"amount\": \"schema:price\",\n        \"currency\": \"schema:priceCurrency\",\n        \"status\": \"schema:paymentStatus\",\n        \"timestamp\": \"schema:dateCreated\",\n        \"sender\": \"schema:agent\",\n        \"recipient\": \"schema:recipient\",\n        \"cardNumber\": \"mc:primaryAccountNumber\",\n        \"tokenNumber\": \"mc:paymentToken\",\n        \"merchantId\": \"mc:merchantIdentifier\",\n        \"merchantName\": \"schema:name\",\n        \"merchantCategoryCode\": \"mc:merchantCategoryCode\",\n        \"acquirerId\": \"mc:acquirerIdentifier\"\
  ,\n        \"icaNumber\": \"mc:interbankCardAssociationNumber\",\n        \"authorizationCode\": \"mc:authorizationCode\",\n        \"billingAmount\": \"mc:billingAmount\",\n        \"billingCurrency\": \"mc:billingCurrency\",\n        \"conversionRate\": \"schema:exchangeRate\",\n        \"network\": \"mc:paymentNetwork\",\n        \"channel\": \"mc:paymentChannel\",\n        \"posEntryMode\": \"mc:posEntryMode\",\n        \"terminalId\": \"mc:terminalIdentifier\",\n        \"settlementDate\": \"mc:settlementDate\",\n        \"referenceId\": \"mc:referenceIdentifier\",\n        \"memo\": \"schema:description\"\n      }\n    },\n\n    \"Transaction\": {\n      \"@id\": \"schema:MoneyTransfer\",\n      \"@context\": {\n        \"transactionId\": \"schema:identifier\",\n        \"transactionIdentifiers\": \"mc:transactionIdentifiers\",\n        \"cardNumber\": \"mc:primaryAccountNumber\",\n        \"cardProductCode\": \"mc:cardProductCode\",\n        \"transactionAmount\": \"schema:price\"\
  ,\n        \"transactionCurrencyCode\": \"schema:priceCurrency\",\n        \"billingAmount\": \"mc:billingAmount\",\n        \"billingCurrencyCode\": \"mc:billingCurrency\",\n        \"transactionDate\": \"schema:startDate\",\n        \"transactionTime\": \"schema:startTime\",\n        \"settlementDate\": \"mc:settlementDate\",\n        \"timestamp\": \"schema:dateCreated\",\n        \"icaNumber\": \"mc:interbankCardAssociationNumber\",\n        \"acquirerId\": \"mc:acquirerIdentifier\",\n        \"merchantId\": \"mc:merchantIdentifier\",\n        \"merchantName\": \"schema:name\",\n        \"merchantCity\": \"schema:addressLocality\",\n        \"merchantStateProvinceCode\": \"schema:addressRegion\",\n        \"merchantCountryCode\": \"schema:addressCountry\",\n        \"merchantPostalCode\": \"schema:postalCode\",\n        \"merchantCategoryCode\": \"mc:merchantCategoryCode\",\n        \"terminalId\": \"mc:terminalIdentifier\",\n        \"terminalAttendanceIndicator\": \"mc:terminalAttendanceIndicator\"\
  ,\n        \"terminalOperatingEnvironment\": \"mc:terminalOperatingEnvironment\",\n        \"terminalCapabilityIndicator\": \"mc:terminalCapabilityIndicator\",\n        \"posEntryMode\": \"mc:posEntryMode\",\n        \"accountDeviceType\": \"mc:accountDeviceType\",\n        \"cardholderPresenceIndicator\": \"mc:cardholderPresenceIndicator\",\n        \"cardPresenceIndicator\": \"mc:cardPresenceIndicator\",\n        \"catLevelIndicator\": \"mc:catLevelIndicator\",\n        \"cvcInvalidIndicator\": \"mc:cvcInvalidIndicator\",\n        \"avsResponseCode\": \"mc:avsResponseCode\",\n        \"authResponseCode\": \"mc:authorizationResponseCode\",\n        \"network\": \"mc:paymentNetwork\",\n        \"refId\": \"mc:referenceIdentifier\",\n        \"memo\": \"schema:description\"\n      }\n    },\n\n    \"Card\": {\n      \"@id\": \"schema:PaymentCard\",\n      \"@context\": {\n        \"cardNumber\": \"mc:primaryAccountNumber\",\n        \"cardId\": \"schema:identifier\",\n        \"cardPackId\"\
  : \"mc:cardPackIdentifier\",\n        \"cardType\": \"mc:cardType\",\n        \"cardProductCode\": \"mc:cardProductCode\",\n        \"planCode\": \"mc:planCode\",\n        \"programCode\": \"mc:programCode\",\n        \"brand\": \"schema:brand\",\n        \"tier\": \"mc:cardTier\",\n        \"status\": \"mc:cardStatus\",\n        \"issuedDate\": \"schema:dateCreated\",\n        \"expirationDate\": \"mc:expirationDate\",\n        \"embossedName\": \"schema:name\",\n        \"numberless\": \"mc:numberless\",\n        \"instant\": \"mc:instantCard\",\n        \"virtual\": \"mc:virtualCard\",\n        \"contactless\": \"schema:contactlessPayment\",\n        \"photoIndicator\": \"mc:photoIndicator\",\n        \"deliveryMode\": \"mc:deliveryMode\",\n        \"deliveryDate\": \"mc:deliveryDate\",\n        \"tokenNumber\": \"mc:paymentToken\",\n        \"binNumber\": \"mc:bankIdentificationNumber\",\n        \"issuerId\": \"mc:issuerIdentifier\",\n        \"issuerName\": \"mc:issuerName\",\n \
  \       \"issuerCountryCode\": \"mc:issuerCountry\",\n        \"cardholder\": \"schema:holder\",\n        \"limits\": \"mc:cardLimits\",\n        \"applicationType\": \"mc:applicationType\",\n        \"corporateCode\": \"mc:corporateCode\"\n      }\n    },\n\n    \"Merchant\": {\n      \"@id\": \"schema:LocalBusiness\",\n      \"@context\": {\n        \"merchantId\": \"schema:identifier\",\n        \"id\": \"mc:numericMerchantId\",\n        \"merchantName\": \"schema:legalName\",\n        \"dbaName\": \"schema:alternateName\",\n        \"merchantCategoryCode\": \"mc:merchantCategoryCode\",\n        \"category\": \"schema:category\",\n        \"categoryId\": \"mc:categoryIdentifier\",\n        \"merchantType\": \"mc:merchantType\",\n        \"address\": \"schema:address\",\n        \"location\": \"schema:geo\",\n        \"distance\": \"schema:distance\",\n        \"distanceUnit\": \"mc:distanceUnit\",\n        \"geocodingResult\": \"mc:geocodingResult\",\n        \"terminalCapabilities\"\
  : \"mc:terminalCapabilities\",\n        \"cashbackMaximumAmount\": \"mc:cashbackMaximumAmount\",\n        \"dpa\": \"mc:digitalPaymentApplication\",\n        \"acquirerId\": \"mc:acquirerIdentifier\",\n        \"acquirerMerchantId\": \"mc:acquirerMerchantIdentifier\",\n        \"websiteUrl\": \"schema:url\",\n        \"logoUrl\": \"schema:logo\",\n        \"offerMerchantId\": \"mc:offerMerchantIdentifier\"\n      }\n    },\n\n    \"MerchantAddress\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"addressLine1\": \"schema:streetAddress\",\n        \"addressLine2\": \"mc:addressLine2\",\n        \"city\": \"schema:addressLocality\",\n        \"stateProvinceCode\": \"schema:addressRegion\",\n        \"stateProvinceName\": \"mc:stateProvinceName\",\n        \"postalCode\": \"schema:postalCode\",\n        \"countryCode\": \"schema:addressCountry\",\n        \"countryName\": \"mc:countryName\"\n      }\n    },\n\n    \"GeoLocation\": {\n      \"@id\": \"schema:GeoCoordinates\"\
  ,\n      \"@context\": {\n        \"latitude\": \"schema:latitude\",\n        \"longitude\": \"schema:longitude\"\n      }\n    },\n\n    \"FraudAlert\": {\n      \"@id\": \"mc:FraudAlert\",\n      \"@context\": {\n        \"alertId\": \"schema:identifier\",\n        \"alertType\": \"mc:alertType\",\n        \"alertSource\": \"mc:alertSource\",\n        \"refId\": \"mc:referenceIdentifier\",\n        \"timestamp\": \"schema:dateCreated\",\n        \"icaNumber\": \"mc:interbankCardAssociationNumber\",\n        \"acquirerId\": \"mc:acquirerIdentifier\",\n        \"cardNumber\": \"mc:primaryAccountNumber\",\n        \"cardProductCode\": \"mc:cardProductCode\",\n        \"transactionDate\": \"schema:startDate\",\n        \"transactionAmount\": \"schema:price\",\n        \"transactionCurrencyCode\": \"schema:priceCurrency\",\n        \"billingAmount\": \"mc:billingAmount\",\n        \"billingCurrencyCode\": \"mc:billingCurrency\",\n        \"settlementDate\": \"mc:settlementDate\",\n      \
  \  \"fraudTypeCode\": \"mc:fraudTypeCode\",\n        \"fraudSubTypeCode\": \"mc:fraudSubTypeCode\",\n        \"fraudPostedDate\": \"mc:fraudPostedDate\",\n        \"cardholderReportedDate\": \"mc:cardholderReportedDate\",\n        \"accountDeviceType\": \"mc:accountDeviceType\",\n        \"cardInPossession\": \"mc:cardInPossession\",\n        \"issuerSCAExemption\": \"mc:issuerSCAExemption\",\n        \"transactionIdentifiers\": \"mc:transactionIdentifiers\",\n        \"merchant\": \"schema:seller\",\n        \"terminal\": \"mc:terminal\",\n        \"outcome\": \"schema:result\",\n        \"avsResponseCode\": \"mc:avsResponseCode\",\n        \"authResponseCode\": \"mc:authorizationResponseCode\",\n        \"cvcInvalidIndicator\": \"mc:cvcInvalidIndicator\",\n        \"memo\": \"schema:description\",\n        \"providerId\": \"mc:providerIdentifier\"\n      }\n    },\n\n    \"AlertOutcome\": {\n      \"@id\": \"mc:AlertOutcome\",\n      \"@context\": {\n        \"outcome\": \"mc:outcomeType\"\
  ,\n        \"refundStatus\": \"mc:refundStatus\",\n        \"refundAmount\": \"mc:refundAmount\",\n        \"amountStopped\": \"mc:amountStopped\",\n        \"comments\": \"schema:comment\",\n        \"actionTimestamp\": \"schema:dateModified\",\n        \"status\": \"mc:processingStatus\"\n      }\n    },\n\n    \"Cardholder\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\",\n        \"clientType\": \"mc:clientType\",\n        \"vip\": \"mc:vipStatus\",\n        \"address\": \"schema:address\"\n      }\n    },\n\n    \"PaymentParty\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"accountNumber\": \"mc:accountNumber\",\n        \"institutionId\": \"mc:institutionIdentifier\",\n        \"address\": \"schema:address\"\
  \n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/mastercard/refs/heads/main/json-ld/context.jsonld
tags:
- Credit Cards
- Digital Identity
- Financial Services
- Fraud Detection
- Open Banking
- Payments
- JSON-LD
- Linked Data
- Semantic Web
---
