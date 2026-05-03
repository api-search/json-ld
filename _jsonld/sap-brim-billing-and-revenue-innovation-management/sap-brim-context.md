---
api_specs:
- filename: overview
  format: yaml
  label: SAP Convergent Charging API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/convergent_charging/overview
- filename: overview
  format: yaml
  label: SAP Convergent Invoicing API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/convergent_invoicing/overview
- filename: overview
  format: yaml
  label: SAP Subscription Billing API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/subscription_billing/overview
- filename: overview
  format: yaml
  label: SAP Contract Accounts Receivable and Payable API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/fica/overview
- filename: overview
  format: yaml
  label: SAP BRIM Usage Data Intake API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/usage_data_intake/overview
- filename: overview
  format: yaml
  label: SAP Revenue Accounting and Reporting API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/revenue_accounting/overview
class_count: 0
classes: []
context_file: json-ld/sap-brim-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sap-brim-billing-and-revenue-innovation-management/refs/heads/main/json-ld/sap-brim-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sap Brim from SAP BRIM (Billing and Revenue Innovation Management).
layout: jsonld
name: Sap Brim Context
namespaces:
- prefix: sap-brim
  uri: https://api.sap.com/brim/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dc
  uri: http://purl.org/dc/terms/
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
properties:
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: SubscriptionItem
  type: ''
- container: ''
  name: SubscriptionPlan
  type: ''
- container: ''
  name: PricingPlan
  type: ''
- container: ''
  name: RateCard
  type: ''
- container: ''
  name: PricingTier
  type: ''
- container: ''
  name: ChargingEvent
  type: ''
- container: ''
  name: UsageEvent
  type: ''
- container: ''
  name: RatingResult
  type: ''
- container: ''
  name: BillingRecord
  type: ''
- container: ''
  name: MonetaryAmount
  type: ''
- container: ''
  name: Customer
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: customer
  type: reference
- container: ''
  name: plan
  type: reference
- container: set
  name: items
  type: ''
- container: ''
  name: account
  type: reference
- container: ''
  name: recurringCharge
  type: reference
- container: ''
  name: price
  type: reference
- container: ''
  name: unitPrice
  type: reference
- container: ''
  name: totalPrice
  type: reference
- container: ''
  name: amount
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
property_count: 26
provider_name: SAP BRIM (Billing and Revenue Innovation Management)
provider_slug: sap-brim-billing-and-revenue-innovation-management
slug: sap-brim-context
source_filename: sap-brim-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sap-brim\": \"https://api.sap.com/brim/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dc\": \"http://purl.org/dc/terms/\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n\n    \"Subscription\": {\n      \"@id\": \"sap-brim:Subscription\",\n      \"@context\": {\n        \"subscriptionId\": {\n          \"@id\": \"sap-brim:subscriptionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"sap-brim:subscriptionStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startDate\": {\n          \"@id\": \"schema:validFrom\",\n          \"@type\": \"xsd:date\"\n        },\n        \"endDate\": {\n          \"@id\": \"schema:validThrough\",\n          \"@type\": \"xsd:date\"\n        },\n        \"billingFrequency\": {\n          \"@id\": \"sap-brim:billingFrequency\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"autoRenew\": {\n          \"@id\": \"sap-brim:autoRenew\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"renewalCount\": {\n          \"@id\": \"sap-brim:renewalCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"cancellationDate\": {\n          \"@id\": \"sap-brim:cancellationDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"cancellationReason\": {\n          \"@id\": \"sap-brim:cancellationReason\",\n          \"@type\": \"xsd:string\"\n        },\n        \"trialEndDate\": {\n          \"@id\": \"sap-brim:trialEndDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"SubscriptionItem\": {\n      \"@id\": \"sap-brim:SubscriptionItem\",\n      \"@context\": {\n        \"itemId\": {\n          \"@id\": \"sap-brim:itemId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"quantity\": {\n          \"@id\": \"schema:amount\",\n          \"@type\": \"xsd:integer\"\n        },\n    \
  \    \"billingType\": {\n          \"@id\": \"sap-brim:billingType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"includedUnits\": {\n          \"@id\": \"sap-brim:includedUnits\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"overageRate\": {\n          \"@id\": \"sap-brim:overageRate\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"SubscriptionPlan\": {\n      \"@id\": \"sap-brim:SubscriptionPlan\",\n      \"@context\": {\n        \"planId\": {\n          \"@id\": \"sap-brim:planId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contractTermMonths\": {\n          \"@id\": \"sap-brim:contractTermMonths\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"trialPeriodDays\": {\n          \"@id\": \"sap-brim:trialPeriodDays\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"features\": {\n          \"@id\": \"sap-brim:features\",\n          \"@container\": \"@list\"\n        }\n      }\n   \
  \ },\n\n    \"PricingPlan\": {\n      \"@id\": \"sap-brim:PricingPlan\",\n      \"@context\": {\n        \"pricingModel\": {\n          \"@id\": \"sap-brim:pricingModel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"effectiveFrom\": {\n          \"@id\": \"schema:validFrom\",\n          \"@type\": \"xsd:date\"\n        },\n        \"effectiveTo\": {\n          \"@id\": \"schema:validThrough\",\n          \"@type\": \"xsd:date\"\n        },\n        \"rateCards\": {\n          \"@id\": \"sap-brim:hasRateCard\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"RateCard\": {\n      \"@id\": \"sap-brim:RateCard\",\n      \"@context\": {\n        \"rateCardId\": {\n          \"@id\": \"sap-brim:rateCardId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"unit\": {\n          \"@id\": \"schema:unitCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"baseRate\": {\n          \"@id\": \"sap-brim:baseRate\",\n          \"@type\"\
  : \"xsd:double\"\n        },\n        \"tiers\": {\n          \"@id\": \"sap-brim:hasPricingTier\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"PricingTier\": {\n      \"@id\": \"sap-brim:PricingTier\",\n      \"@context\": {\n        \"tierName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fromQuantity\": {\n          \"@id\": \"sap-brim:fromQuantity\",\n          \"@type\": \"xsd:double\"\n        },\n        \"toQuantity\": {\n          \"@id\": \"sap-brim:toQuantity\",\n          \"@type\": \"xsd:double\"\n        },\n        \"ratePerUnit\": {\n          \"@id\": \"gr:hasCurrencyValue\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"ChargingEvent\": {\n      \"@id\": \"sap-brim:ChargingEvent\",\n      \"@context\": {\n        \"chargeId\": {\n          \"@id\": \"sap-brim:chargeId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"chargeType\": {\n        \
  \  \"@id\": \"sap-brim:chargeType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"chargedAt\": {\n          \"@id\": \"sap-brim:chargedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"UsageEvent\": {\n      \"@id\": \"sap-brim:UsageEvent\",\n      \"@context\": {\n        \"eventId\": {\n          \"@id\": \"sap-brim:eventId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"serviceType\": {\n          \"@id\": \"sap-brim:serviceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"usageTimestamp\": {\n          \"@id\": \"sap-brim:usageTimestamp\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"RatingResult\": {\n      \"@id\": \"sap-brim:RatingResult\",\n      \"@context\": {\n        \"ratingId\": {\n          \"@id\": \"sap-brim:ratingId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rateApplied\": {\n          \"@id\": \"sap-brim:rateApplied\",\n          \"@type\"\
  : \"xsd:double\"\n        },\n        \"tierApplied\": {\n          \"@id\": \"sap-brim:tierApplied\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ratedAt\": {\n          \"@id\": \"sap-brim:ratedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"BillingRecord\": {\n      \"@id\": \"sap-brim:BillingRecord\",\n      \"@context\": {\n        \"billingRecordId\": {\n          \"@id\": \"sap-brim:billingRecordId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"invoiceNumber\": {\n          \"@id\": \"sap-brim:invoiceNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"billingPeriodStart\": {\n          \"@id\": \"sap-brim:billingPeriodStart\",\n          \"@type\": \"xsd:date\"\n        },\n        \"billingPeriodEnd\": {\n          \"@id\": \"sap-brim:billingPeriodEnd\",\n          \"@type\": \"xsd:date\"\n        },\n        \"issuedAt\": {\n          \"@id\": \"sap-brim:issuedAt\",\n          \"@type\": \"xsd:dateTime\"\
  \n        },\n        \"dueDate\": {\n          \"@id\": \"sap-brim:dueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"paidAt\": {\n          \"@id\": \"sap-brim:paidAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"MonetaryAmount\": {\n      \"@id\": \"schema:MonetaryAmount\",\n      \"@context\": {\n        \"value\": {\n          \"@id\": \"schema:value\",\n          \"@type\": \"xsd:double\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:currency\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Customer\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"customerId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Account\": {\n      \"@id\": \"sap-brim:Account\",\n      \"@context\": {\n        \"accountId\": {\n          \"@id\": \"sap-brim:accountId\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"accountType\": {\n          \"@id\": \"sap-brim:accountType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customer\": {\n      \"@id\": \"sap-brim:hasCustomer\",\n      \"@type\": \"@id\"\n    },\n    \"plan\": {\n      \"@id\": \"sap-brim:hasPlan\",\n      \"@type\": \"@id\"\n    },\n    \"items\": {\n      \"@id\": \"sap-brim:hasItem\",\n      \"@container\": \"@set\"\n    },\n    \"account\": {\n      \"@id\": \"sap-brim:hasAccount\",\n      \"@type\": \"@id\"\n    },\n    \"recurringCharge\": {\n      \"@id\": \"sap-brim:recurringCharge\",\n      \"@type\": \"@id\"\n    },\n    \"price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"@id\"\n    },\n    \"unitPrice\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"@id\"\
  \n    },\n    \"totalPrice\": {\n      \"@id\": \"sap-brim:totalPrice\",\n      \"@type\": \"@id\"\n    },\n    \"amount\": {\n      \"@id\": \"sap-brim:amount\",\n      \"@type\": \"@id\"\n    },\n    \"createdAt\": {\n      \"@id\": \"dc:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedAt\": {\n      \"@id\": \"dc:modified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sap-brim-billing-and-revenue-innovation-management/refs/heads/main/json-ld/sap-brim-context.jsonld
tags:
- Billing
- Enterprise
- Order to Cash
- Revenue Management
- SAP
- Subscription Management
- Usage-Based Pricing
- JSON-LD
- Linked Data
- Semantic Web
---
