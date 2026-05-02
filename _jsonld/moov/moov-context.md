---
api_specs:
- filename: moov-api-openapi.yml
  format: yaml
  label: Moov API
  slug: moov-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/moov/refs/heads/main/openapi/moov-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/moov-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/moov/refs/heads/main/json-ld/moov-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Moov from Moov.
layout: jsonld
name: Moov Context
namespaces:
- prefix: moov
  uri: https://api.moov.io/schemas/moov/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: fibo-fnd-acc-cur
  uri: https://spec.edmcouncil.org/fibo/ontology/FND/Accounting/CurrencyAmount/
properties:
- container: ''
  name: Account
  type: ''
- container: ''
  name: IndividualProfile
  type: ''
- container: ''
  name: BusinessProfile
  type: ''
- container: ''
  name: Address
  type: ''
- container: ''
  name: Transfer
  type: ''
- container: ''
  name: Amount
  type: ''
- container: ''
  name: BankAccount
  type: ''
- container: ''
  name: Card
  type: ''
- container: ''
  name: Wallet
  type: ''
- container: ''
  name: PaymentMethod
  type: ''
- container: ''
  name: Capability
  type: ''
- container: ''
  name: Representative
  type: ''
- container: ''
  name: Dispute
  type: ''
- container: ''
  name: SweepConfig
  type: ''
- container: ''
  name: PaymentLink
  type: ''
- container: ''
  name: WebhookEvent
  type: ''
property_count: 16
provider_name: Moov
provider_slug: moov
slug: moov-context
source_filename: moov-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"moov\": \"https://api.moov.io/schemas/moov/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fibo-fnd-acc-cur\": \"https://spec.edmcouncil.org/fibo/ontology/FND/Accounting/CurrencyAmount/\",\n\n    \"Account\": {\n      \"@id\": \"moov:Account\",\n      \"@context\": {\n        \"accountID\": {\n          \"@id\": \"moov:accountID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountType\": {\n          \"@id\": \"moov:accountType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\"\n        },\n        \"profile\": {\n          \"@id\": \"moov:profile\"\n        },\n        \"capabilities\": {\n          \"@id\": \"moov:capabilities\",\n          \"@container\": \"@set\"\n        },\n        \"verification\": {\n          \"@id\": \"moov:verification\"\
  \n        },\n        \"metadata\": {\n          \"@id\": \"moov:metadata\"\n        },\n        \"foreignID\": {\n          \"@id\": \"dcterms:identifier\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"IndividualProfile\": {\n      \"@id\": \"moov:IndividualProfile\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\"\n        },\n        \"phone\": {\n          \"@id\": \"schema:telephone\"\n        },\n        \"address\": {\n          \"@id\": \"schema:address\"\n        },\n        \"birthDate\": {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"governmentID\": {\n          \"@id\": \"moov:governmentID\"\n \
  \       }\n      }\n    },\n\n    \"BusinessProfile\": {\n      \"@id\": \"moov:BusinessProfile\",\n      \"@context\": {\n        \"legalBusinessName\": {\n          \"@id\": \"schema:legalName\"\n        },\n        \"businessType\": {\n          \"@id\": \"moov:businessType\"\n        },\n        \"address\": {\n          \"@id\": \"schema:address\"\n        },\n        \"phone\": {\n          \"@id\": \"schema:telephone\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\"\n        },\n        \"website\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"taxID\": {\n          \"@id\": \"moov:taxID\"\n        },\n        \"industryCodes\": {\n          \"@id\": \"moov:industryCodes\"\n        }\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"addressLine1\": {\n          \"@id\"\
  : \"schema:streetAddress\"\n        },\n        \"addressLine2\": {\n          \"@id\": \"moov:addressLine2\"\n        },\n        \"city\": {\n          \"@id\": \"schema:addressLocality\"\n        },\n        \"stateOrProvince\": {\n          \"@id\": \"schema:addressRegion\"\n        },\n        \"postalCode\": {\n          \"@id\": \"schema:postalCode\"\n        },\n        \"country\": {\n          \"@id\": \"schema:addressCountry\"\n        }\n      }\n    },\n\n    \"Transfer\": {\n      \"@id\": \"moov:Transfer\",\n      \"@context\": {\n        \"transferID\": {\n          \"@id\": \"moov:transferID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"moov:status\"\n        },\n        \"source\": {\n          \"@id\": \"moov:source\"\n        },\n        \"destination\": {\n          \"@id\": \"moov:destination\"\n        },\n        \"amount\": {\n          \"@id\": \"moov:amount\"\n        },\n        \"description\": {\n        \
  \  \"@id\": \"schema:description\"\n        },\n        \"metadata\": {\n          \"@id\": \"moov:metadata\"\n        },\n        \"facilitatorFee\": {\n          \"@id\": \"moov:facilitatorFee\"\n        },\n        \"moovFee\": {\n          \"@id\": \"moov:moovFee\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedOn\": {\n          \"@id\": \"moov:completedOn\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Amount\": {\n      \"@id\": \"moov:Amount\",\n      \"@context\": {\n        \"currency\": {\n          \"@id\": \"fibo-fnd-acc-cur:hasMonetaryAmount\"\n        },\n        \"value\": {\n          \"@id\": \"schema:value\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n  \
  \  \"BankAccount\": {\n      \"@id\": \"moov:BankAccount\",\n      \"@context\": {\n        \"bankAccountID\": {\n          \"@id\": \"moov:bankAccountID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"bankName\": {\n          \"@id\": \"schema:name\"\n        },\n        \"bankAccountType\": {\n          \"@id\": \"moov:bankAccountType\"\n        },\n        \"routingNumber\": {\n          \"@id\": \"moov:routingNumber\"\n        },\n        \"lastFourAccountNumber\": {\n          \"@id\": \"moov:lastFourAccountNumber\"\n        },\n        \"status\": {\n          \"@id\": \"moov:status\"\n        },\n        \"verificationStatus\": {\n          \"@id\": \"moov:verificationStatus\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Card\": {\n      \"\
  @id\": \"moov:Card\",\n      \"@context\": {\n        \"cardID\": {\n          \"@id\": \"moov:cardID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"brand\": {\n          \"@id\": \"moov:brand\"\n        },\n        \"cardType\": {\n          \"@id\": \"moov:cardType\"\n        },\n        \"lastFourCardNumber\": {\n          \"@id\": \"moov:lastFourCardNumber\"\n        },\n        \"holderName\": {\n          \"@id\": \"schema:name\"\n        },\n        \"billingAddress\": {\n          \"@id\": \"schema:address\"\n        },\n        \"issuer\": {\n          \"@id\": \"moov:issuer\"\n        },\n        \"issuerCountry\": {\n          \"@id\": \"moov:issuerCountry\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Wallet\": {\n      \"@id\": \"moov:Wallet\"\
  ,\n      \"@context\": {\n        \"walletID\": {\n          \"@id\": \"moov:walletID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"availableBalance\": {\n          \"@id\": \"moov:availableBalance\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PaymentMethod\": {\n      \"@id\": \"moov:PaymentMethod\",\n      \"@context\": {\n        \"paymentMethodID\": {\n          \"@id\": \"moov:paymentMethodID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"paymentMethodType\": {\n          \"@id\": \"moov:paymentMethodType\"\n        },\n        \"wallet\": {\n          \"@id\": \"moov:wallet\"\n        },\n        \"bankAccount\": {\n          \"@id\": \"moov:bankAccount\"\n        },\n        \"card\": {\n          \"@id\": \"moov:card\"\n\
  \        }\n      }\n    },\n\n    \"Capability\": {\n      \"@id\": \"moov:Capability\",\n      \"@context\": {\n        \"capability\": {\n          \"@id\": \"moov:capabilityType\"\n        },\n        \"accountID\": {\n          \"@id\": \"moov:accountID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"moov:status\"\n        },\n        \"requirements\": {\n          \"@id\": \"moov:requirements\",\n          \"@container\": \"@set\"\n        },\n        \"disabledReason\": {\n          \"@id\": \"moov:disabledReason\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Representative\": {\n      \"@id\": \"moov:Representative\",\n      \"@context\": {\n        \"representativeID\": {\n          \"@id\": \"moov:representativeID\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"phone\": {\n          \"@id\": \"schema:telephone\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\"\n        },\n        \"address\": {\n          \"@id\": \"schema:address\"\n        },\n        \"birthDate\": {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"responsibilities\": {\n          \"@id\": \"moov:responsibilities\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"disabledOn\": {\n          \"@id\": \"moov:disabledOn\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Dispute\": {\n      \"@id\": \"moov:Dispute\",\n      \"@context\": {\n\
  \        \"disputeID\": {\n          \"@id\": \"moov:disputeID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"transferID\": {\n          \"@id\": \"moov:transferID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"phase\": {\n          \"@id\": \"moov:phase\"\n        },\n        \"status\": {\n          \"@id\": \"moov:status\"\n        },\n        \"amount\": {\n          \"@id\": \"moov:amount\"\n        },\n        \"reason\": {\n          \"@id\": \"moov:reason\"\n        },\n        \"respondBy\": {\n          \"@id\": \"moov:respondBy\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"SweepConfig\": {\n      \"@id\": \"moov:SweepConfig\",\n      \"@context\": {\n        \"sweepConfigID\": {\n\
  \          \"@id\": \"moov:sweepConfigID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"walletID\": {\n          \"@id\": \"moov:walletID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"paymentMethodID\": {\n          \"@id\": \"moov:paymentMethodID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"moov:status\"\n        },\n        \"statementDescriptor\": {\n          \"@id\": \"moov:statementDescriptor\"\n        },\n        \"minimumBalance\": {\n          \"@id\": \"moov:minimumBalance\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PaymentLink\": {\n      \"@id\": \"moov:PaymentLink\",\n      \"@context\": {\n        \"paymentLinkCode\": {\n          \"@id\": \"moov:paymentLinkCode\"\
  \n        },\n        \"accountID\": {\n          \"@id\": \"moov:accountID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"moov:status\"\n        },\n        \"amount\": {\n          \"@id\": \"moov:amount\"\n        },\n        \"currency\": {\n          \"@id\": \"moov:currency\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"expiresOn\": {\n          \"@id\": \"moov:expiresOn\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"WebhookEvent\": {\n      \"@id\": \"moov:WebhookEvent\",\n      \"@context\": {\n        \"eventID\"\
  : {\n          \"@id\": \"moov:eventID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"moov:eventType\"\n        },\n        \"data\": {\n          \"@id\": \"moov:eventData\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/moov/refs/heads/main/json-ld/moov-context.jsonld
tags:
- Banking
- Embedded Finance
- Financial Infrastructure
- Money Movement
- Payments
- Transfers
- JSON-LD
- Linked Data
- Semantic Web
---
