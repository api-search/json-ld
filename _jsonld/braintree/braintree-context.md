---
api_specs:
- filename: braintree-payments-openapi.yml
  format: yaml
  label: Braintree Payments API
  slug: payments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/braintree/refs/heads/main/openapi/braintree-payments-openapi.yml
- filename: braintree-webhooks-asyncapi.yml
  format: yaml
  label: Braintree Webhooks
  slug: webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/braintree/refs/heads/main/asyncapi/braintree-webhooks-asyncapi.yml
- filename: braintree-payments-openapi.yml
  format: yaml
  label: Braintree Vault API
  slug: vault-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/braintree/refs/heads/main/openapi/braintree-payments-openapi.yml
- filename: braintree-subscriptions-openapi.yml
  format: yaml
  label: Braintree Subscriptions API
  slug: subscriptions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/braintree/refs/heads/main/openapi/braintree-subscriptions-openapi.yml
class_count: 0
classes: []
context_file: json-ld/braintree-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/braintree/refs/heads/main/json-ld/braintree-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Braintree from braintree.
layout: jsonld
name: Braintree Context
namespaces:
- prefix: braintree
  uri: https://api-evangelist.github.io/braintree/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
properties:
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: Customer
  type: ''
- container: ''
  name: PaymentMethod
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: Plan
  type: ''
- container: ''
  name: Dispute
  type: ''
- container: ''
  name: Address
  type: ''
- container: ''
  name: WebhookNotification
  type: ''
property_count: 8
provider_name: braintree
provider_slug: braintree
slug: braintree-context
source_filename: braintree-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"braintree\": \"https://api-evangelist.github.io/braintree/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n\n    \"Transaction\": {\n      \"@id\": \"braintree:Transaction\",\n      \"@context\": {\n        \"id\": \"dcterms:identifier\",\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": \"braintree:transactionStatus\",\n        \"type\": \"braintree:transactionType\",\n        \"currency_iso_code\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"order_id\": \"schema:orderNumber\",\n        \"merchant_account_id\": {\n          \"@id\": \"braintree:merchantAccountId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"\
  customer_id\": {\n          \"@id\": \"braintree:customerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"payment_method_token\": {\n          \"@id\": \"braintree:paymentMethodToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"payment_method_nonce\": {\n          \"@id\": \"braintree:paymentMethodNonce\",\n          \"@type\": \"xsd:string\"\n        },\n        \"processor_response_code\": \"braintree:processorResponseCode\",\n        \"processor_response_text\": \"braintree:processorResponseText\",\n        \"gateway_rejection_reason\": \"braintree:gatewayRejectionReason\",\n        \"tax_amount\": {\n          \"@id\": \"schema:taxValue\",\n          \"@type\": \"xsd:string\"\n        },\n        \"shipping_amount\": {\n          \"@id\": \"schema:shippingDetails\",\n          \"@type\": \"xsd:string\"\n        },\n        \"transaction_source\": \"braintree:transactionSource\",\n        \"billing\": {\n          \"@id\": \"schema:billingAddress\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"shipping\": {\n          \"@id\": \"schema:deliveryAddress\",\n          \"@type\": \"@id\"\n        },\n        \"customer_details\": {\n          \"@id\": \"schema:customer\",\n          \"@type\": \"@id\"\n        },\n        \"credit_card_details\": {\n          \"@id\": \"braintree:creditCardDetails\",\n          \"@type\": \"@id\"\n        },\n        \"descriptor\": {\n          \"@id\": \"braintree:descriptor\",\n          \"@type\": \"@id\"\n        },\n        \"refund_ids\": {\n          \"@id\": \"braintree:refundId\",\n          \"@container\": \"@set\"\n        },\n        \"refunded_transaction_id\": {\n          \"@id\": \"braintree:refundedTransactionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subscription_id\": {\n          \"@id\": \"braintree:subscriptionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"line_items\": {\n          \"@id\": \"schema:orderedItem\",\n          \"\
  @container\": \"@set\"\n        },\n        \"disbursement_details\": {\n          \"@id\": \"braintree:disbursementDetails\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Customer\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"dcterms:identifier\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\",\n        \"company\": \"schema:worksFor\",\n        \"website\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"fax\": \"schema:faxNumber\",\n        \"payment_methods\": {\n          \"@id\": \"braintree:paymentMethod\",\n          \"\
  @container\": \"@set\"\n        },\n        \"addresses\": {\n          \"@id\": \"schema:address\",\n          \"@container\": \"@set\"\n        },\n        \"custom_fields\": \"braintree:customFields\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PaymentMethod\": {\n      \"@id\": \"schema:PaymentMethod\",\n      \"@context\": {\n        \"token\": \"dcterms:identifier\",\n        \"customer_id\": {\n          \"@id\": \"schema:customer\",\n          \"@type\": \"xsd:string\"\n        },\n        \"default\": \"braintree:isDefault\",\n        \"image_url\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"subscriptions\": {\n          \"@id\": \"braintree:subscription\",\n          \"@container\": \"@set\"\n        },\n    \
  \    \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"schema:Subscription\",\n      \"@context\": {\n        \"id\": \"dcterms:identifier\",\n        \"plan_id\": {\n          \"@id\": \"braintree:planId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": \"braintree:subscriptionStatus\",\n        \"price\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:string\"\n        },\n        \"merchant_account_id\": {\n          \"@id\": \"braintree:merchantAccountId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"payment_method_token\": {\n          \"@id\": \"braintree:paymentMethodToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"current_billing_cycle\": \"braintree:currentBillingCycle\"\
  ,\n        \"number_of_billing_cycles\": \"braintree:numberOfBillingCycles\",\n        \"never_expires\": \"braintree:neverExpires\",\n        \"trial_period\": \"braintree:trialPeriod\",\n        \"trial_duration\": \"braintree:trialDuration\",\n        \"trial_duration_unit\": \"braintree:trialDurationUnit\",\n        \"first_billing_date\": {\n          \"@id\": \"braintree:firstBillingDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"next_billing_date\": {\n          \"@id\": \"braintree:nextBillingDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"next_billing_amount\": {\n          \"@id\": \"braintree:nextBillingAmount\",\n          \"@type\": \"xsd:string\"\n        },\n        \"paid_through_date\": {\n          \"@id\": \"braintree:paidThroughDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"billing_day_of_month\": \"braintree:billingDayOfMonth\",\n        \"failure_count\": \"braintree:failureCount\",\n        \"add_ons\": {\n \
  \         \"@id\": \"braintree:addOn\",\n          \"@container\": \"@set\"\n        },\n        \"discounts\": {\n          \"@id\": \"braintree:discount\",\n          \"@container\": \"@set\"\n        },\n        \"transactions\": {\n          \"@id\": \"schema:orderHistory\",\n          \"@container\": \"@set\"\n        },\n        \"descriptor\": {\n          \"@id\": \"braintree:descriptor\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Plan\": {\n      \"@id\": \"braintree:BillingPlan\",\n      \"@context\": {\n        \"id\": \"dcterms:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"dcterms:description\",\n        \"price\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"currency_iso_code\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"billing_frequency\": \"braintree:billingFrequency\",\n        \"number_of_billing_cycles\": \"braintree:numberOfBillingCycles\",\n        \"trial_period\": \"braintree:trialPeriod\",\n        \"trial_duration\": \"braintree:trialDuration\",\n        \"trial_duration_unit\": \"braintree:trialDurationUnit\",\n        \"add_ons\": {\n          \"@id\": \"braintree:addOn\",\n          \"@container\": \"@set\"\n        },\n        \"discounts\": {\n          \"@id\": \"braintree:discount\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Dispute\": {\n      \"@id\": \"braintree:PaymentDispute\"\
  ,\n      \"@context\": {\n        \"id\": \"dcterms:identifier\",\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currency_iso_code\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": \"braintree:disputeStatus\",\n        \"reason\": \"braintree:disputeReason\",\n        \"received_date\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"reply_by_date\": {\n          \"@id\": \"braintree:replyByDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"transaction_id\": {\n          \"@id\": \"braintree:transactionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n\
  \        }\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"id\": \"dcterms:identifier\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"company\": \"schema:name\",\n        \"street_address\": \"schema:streetAddress\",\n        \"extended_address\": \"schema:streetAddress\",\n        \"locality\": \"schema:addressLocality\",\n        \"region\": \"schema:addressRegion\",\n        \"postal_code\": \"schema:postalCode\",\n        \"country_code_alpha2\": \"schema:addressCountry\",\n        \"country_name\": \"schema:addressCountry\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"WebhookNotification\": {\n      \"@id\": \"braintree:WebhookNotification\"\
  ,\n      \"@context\": {\n        \"kind\": \"braintree:notificationKind\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"subscription\": {\n          \"@id\": \"braintree:subscription\",\n          \"@type\": \"@id\"\n        },\n        \"transaction\": {\n          \"@id\": \"braintree:transaction\",\n          \"@type\": \"@id\"\n        },\n        \"dispute\": {\n          \"@id\": \"braintree:dispute\",\n          \"@type\": \"@id\"\n        },\n        \"merchant_account\": {\n          \"@id\": \"braintree:merchantAccount\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/braintree/refs/heads/main/json-ld/braintree-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
