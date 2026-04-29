---
api_specs:
- filename: quickbooks-accounting.yml
  format: yaml
  label: QuickBooks Online Accounting API
  slug: quickbooks-accounting
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/intuit/refs/heads/main/openapi/quickbooks-accounting.yml
class_count: 0
classes: []
context_file: json-ld/intuit-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/intuit/refs/heads/main/json-ld/intuit-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Intuit from Intuit.
layout: jsonld
name: Intuit Context
namespaces:
- prefix: intuit
  uri: https://developer.intuit.com/ns/quickbooks#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: qbo
  uri: https://quickbooks.api.intuit.com/v3/company/
properties:
- container: ''
  name: Invoice
  type: ''
- container: ''
  name: Customer
  type: ''
- container: ''
  name: Item
  type: ''
- container: ''
  name: Payment
  type: ''
- container: ''
  name: PhysicalAddress
  type: ''
- container: ''
  name: ReferenceType
  type: ''
- container: ''
  name: MetaData
  type: ''
- container: ''
  name: LinkedTxn
  type: ''
property_count: 8
provider_name: Intuit
provider_slug: intuit
slug: intuit-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/\",\n    \"intuit\": \"https://developer.intuit.com/ns/quickbooks#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"qbo\": \"https://quickbooks.api.intuit.com/v3/company/\",\n\n    \"Invoice\": {\n      \"@id\": \"intuit:Invoice\",\n      \"@context\": {\n        \"Id\": {\n          \"@id\": \"intuit:entityId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SyncToken\": {\n          \"@id\": \"intuit:syncToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DocNumber\": {\n          \"@id\": \"intuit:docNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"TxnDate\": {\n          \"@id\": \"intuit:transactionDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"DueDate\": {\n          \"@id\": \"schema:paymentDueDate\",\n          \"@type\": \"\
  xsd:date\"\n        },\n        \"TotalAmt\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"Balance\": {\n          \"@id\": \"intuit:balance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"CustomerRef\": {\n          \"@id\": \"intuit:customerReference\",\n          \"@type\": \"@id\"\n        },\n        \"Line\": {\n          \"@id\": \"intuit:lineItem\",\n          \"@container\": \"@list\"\n        },\n        \"BillAddr\": {\n          \"@id\": \"schema:billingAddress\",\n          \"@type\": \"schema:PostalAddress\"\n        },\n        \"ShipAddr\": {\n          \"@id\": \"intuit:shippingAddress\",\n          \"@type\": \"schema:PostalAddress\"\n        },\n        \"BillEmail\": {\n          \"@id\": \"intuit:billingEmail\",\n          \"@type\": \"schema:ContactPoint\"\n        },\n        \"PrintStatus\": {\n          \"@id\": \"intuit:printStatus\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"EmailStatus\": {\n          \"@id\": \"intuit:emailStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ShipDate\": {\n          \"@id\": \"intuit:shipDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"TrackingNum\": {\n          \"@id\": \"intuit:trackingNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"PrivateNote\": {\n          \"@id\": \"intuit:privateNote\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ExchangeRate\": {\n          \"@id\": \"schema:currentExchangeRate\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"Deposit\": {\n          \"@id\": \"intuit:deposit\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"AllowOnlinePayment\": {\n          \"@id\": \"intuit:allowOnlinePayment\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"AllowOnlineCreditCardPayment\": {\n          \"@id\": \"intuit:allowOnlineCreditCardPayment\",\n          \"@type\": \"xsd:boolean\"\
  \n        },\n        \"AllowOnlineACHPayment\": {\n          \"@id\": \"intuit:allowOnlineACHPayment\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Customer\": {\n      \"@id\": \"intuit:Customer\",\n      \"@context\": {\n        \"Id\": {\n          \"@id\": \"intuit:entityId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SyncToken\": {\n          \"@id\": \"intuit:syncToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DisplayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"GivenName\": {\n          \"@id\": \"schema:givenName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"MiddleName\": {\n          \"@id\": \"schema:additionalName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"FamilyName\": {\n          \"@id\": \"schema:familyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Title\": {\n          \"@id\": \"schema:honorificPrefix\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"Suffix\": {\n          \"@id\": \"schema:honorificSuffix\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CompanyName\": {\n          \"@id\": \"schema:legalName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"PrimaryEmailAddr\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"schema:ContactPoint\"\n        },\n        \"PrimaryPhone\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"schema:ContactPoint\"\n        },\n        \"Mobile\": {\n          \"@id\": \"intuit:mobilePhone\",\n          \"@type\": \"schema:ContactPoint\"\n        },\n        \"Fax\": {\n          \"@id\": \"schema:faxNumber\",\n          \"@type\": \"schema:ContactPoint\"\n        },\n        \"BillAddr\": {\n          \"@id\": \"schema:billingAddress\",\n          \"@type\": \"schema:PostalAddress\"\n        },\n        \"ShipAddr\": {\n          \"@id\": \"intuit:shippingAddress\",\n \
  \         \"@type\": \"schema:PostalAddress\"\n        },\n        \"WebAddr\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"Active\": {\n          \"@id\": \"intuit:active\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"Taxable\": {\n          \"@id\": \"intuit:taxable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"Balance\": {\n          \"@id\": \"intuit:balance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"BalanceWithJobs\": {\n          \"@id\": \"intuit:balanceWithJobs\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"Job\": {\n          \"@id\": \"intuit:isJob\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"ParentRef\": {\n          \"@id\": \"intuit:parentReference\",\n          \"@type\": \"@id\"\n        },\n        \"Level\": {\n          \"@id\": \"intuit:hierarchyLevel\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"FullyQualifiedName\"\
  : {\n          \"@id\": \"intuit:fullyQualifiedName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"PreferredDeliveryMethod\": {\n          \"@id\": \"intuit:preferredDeliveryMethod\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Notes\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CurrencyRef\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Item\": {\n      \"@id\": \"intuit:Item\",\n      \"@context\": {\n        \"Id\": {\n          \"@id\": \"intuit:entityId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SyncToken\": {\n          \"@id\": \"intuit:syncToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"\
  xsd:string\"\n        },\n        \"Active\": {\n          \"@id\": \"intuit:active\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"UnitPrice\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"PurchaseCost\": {\n          \"@id\": \"intuit:purchaseCost\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"Type\": {\n          \"@id\": \"intuit:itemType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"QtyOnHand\": {\n          \"@id\": \"intuit:quantityOnHand\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"Sku\": {\n          \"@id\": \"schema:sku\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Taxable\": {\n          \"@id\": \"intuit:taxable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"IncomeAccountRef\": {\n          \"@id\": \"intuit:incomeAccountReference\",\n          \"@type\": \"@id\"\n        },\n        \"ExpenseAccountRef\": {\n      \
  \    \"@id\": \"intuit:expenseAccountReference\",\n          \"@type\": \"@id\"\n        },\n        \"AssetAccountRef\": {\n          \"@id\": \"intuit:assetAccountReference\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Payment\": {\n      \"@id\": \"intuit:Payment\",\n      \"@context\": {\n        \"Id\": {\n          \"@id\": \"intuit:entityId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SyncToken\": {\n          \"@id\": \"intuit:syncToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"TxnDate\": {\n          \"@id\": \"intuit:transactionDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"TotalAmt\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"CustomerRef\": {\n          \"@id\": \"intuit:customerReference\",\n          \"@type\": \"@id\"\n        },\n        \"PaymentRefNum\": {\n          \"@id\": \"intuit:paymentReferenceNumber\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"PaymentMethodRef\": {\n          \"@id\": \"schema:paymentMethod\",\n          \"@type\": \"@id\"\n        },\n        \"DepositToAccountRef\": {\n          \"@id\": \"intuit:depositToAccountReference\",\n          \"@type\": \"@id\"\n        },\n        \"UnappliedAmt\": {\n          \"@id\": \"intuit:unappliedAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"Line\": {\n          \"@id\": \"intuit:paymentLine\",\n          \"@container\": \"@list\"\n        },\n        \"CurrencyRef\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"@id\"\n        },\n        \"ExchangeRate\": {\n          \"@id\": \"schema:currentExchangeRate\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"PrivateNote\": {\n          \"@id\": \"intuit:privateNote\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"PhysicalAddress\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\"\
  : {\n        \"Line1\": {\n          \"@id\": \"schema:streetAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"City\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CountrySubDivisionCode\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"PostalCode\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Lat\": {\n          \"@id\": \"schema:latitude\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Long\": {\n          \"@id\": \"schema:longitude\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ReferenceType\": {\n      \"@id\": \"intuit:ReferenceType\",\n      \"@context\": {\n        \"value\": {\n          \"@id\": \"intuit:referenceId\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"intuit:referenceName\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"MetaData\": {\n      \"@id\": \"intuit:MetaData\",\n      \"@context\": {\n        \"CreateTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"LastUpdatedTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"LinkedTxn\": {\n      \"@id\": \"intuit:LinkedTransaction\",\n      \"@context\": {\n        \"TxnId\": {\n          \"@id\": \"intuit:transactionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"TxnType\": {\n          \"@id\": \"intuit:transactionType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/intuit/refs/heads/main/json-ld/intuit-context.jsonld
tags:
- Accounting
- Custom Fields
- Financial
- Financial Services
- Invoicing
- Payments
- Payroll
- Project Management
- Sales Tax
- Small Business
- Tax
- Tax Preparation
- Taxes
- Time Tracking
- JSON-LD
- Linked Data
- Semantic Web
---
