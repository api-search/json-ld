---
api_specs:
- filename: marqeta-core-api-openapi.yml
  format: yaml
  label: Marqeta Core API
  slug: core-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/marqeta/refs/heads/main/openapi/marqeta-core-api-openapi.yml
- filename: marqeta-diva-api-openapi.yml
  format: yaml
  label: Marqeta DiVA API
  slug: diva-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/marqeta/refs/heads/main/openapi/marqeta-diva-api-openapi.yml
- filename: marqeta-webhooks-asyncapi.yml
  format: yaml
  label: Marqeta Webhooks
  slug: webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/marqeta/refs/heads/main/asyncapi/marqeta-webhooks-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/marqeta-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/marqeta/refs/heads/main/json-ld/marqeta-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Marqeta from marqeta.
layout: jsonld
name: Marqeta Context
namespaces:
- prefix: marqeta
  uri: https://marqeta.com/vocab/
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
  name: CardProgram
  type: ''
- container: ''
  name: Cardholder
  type: ''
- container: ''
  name: PaymentCard
  type: ''
- container: ''
  name: CardProduct
  type: ''
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: CardAcceptor
  type: ''
- container: ''
  name: GpaOrder
  type: ''
- container: ''
  name: FundingSource
  type: ''
- container: ''
  name: GpaBalance
  type: ''
- container: ''
  name: VelocityControl
  type: ''
- container: ''
  name: AuthorizationControl
  type: ''
- container: ''
  name: WebhookConfig
  type: ''
- container: ''
  name: Business
  type: ''
property_count: 13
provider_name: marqeta
provider_slug: marqeta
slug: marqeta-context
source_filename: marqeta-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"marqeta\": \"https://marqeta.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fibo-fnd-acc-cur\": \"https://spec.edmcouncil.org/fibo/ontology/FND/Accounting/CurrencyAmount/\",\n\n    \"CardProgram\": {\n      \"@id\": \"marqeta:CardProgram\",\n      \"@context\": {\n        \"token\": \"marqeta:token\",\n        \"name\": \"schema:name\",\n        \"description\": \"dcterms:description\",\n        \"baseURL\": {\n          \"@id\": \"marqeta:baseURL\",\n          \"@type\": \"@id\"\n        },\n        \"humanURL\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Cardholder\": {\n      \"@id\": \"marqeta:Cardholder\",\n      \"@context\": {\n        \"token\": \"marqeta:token\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\"\
  ,\n        \"middle_name\": \"schema:additionalName\",\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\",\n        \"birth_date\": {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"status\": \"marqeta:accountStatus\",\n        \"kyc_required\": \"marqeta:kycRequired\",\n        \"address1\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"zip\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\",\n        \"corporate_card_holder\": \"marqeta:corporateCardHolder\",\n        \"account_holder_group_token\": \"marqeta:accountHolderGroup\",\n        \"metadata\": \"marqeta:metadata\",\n        \"created_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_modified_time\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\
  \n        }\n      }\n    },\n\n    \"PaymentCard\": {\n      \"@id\": \"marqeta:PaymentCard\",\n      \"@context\": {\n        \"token\": \"marqeta:token\",\n        \"card_product_token\": \"marqeta:cardProduct\",\n        \"user_token\": \"marqeta:cardholder\",\n        \"business_token\": \"marqeta:businessHolder\",\n        \"last_four\": \"marqeta:lastFour\",\n        \"expiration\": \"marqeta:expiration\",\n        \"expiration_time\": {\n          \"@id\": \"marqeta:expirationTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"state\": \"marqeta:cardState\",\n        \"state_reason\": \"marqeta:stateReason\",\n        \"fulfillment_status\": \"marqeta:fulfillmentStatus\",\n        \"instrument_type\": \"marqeta:instrumentType\",\n        \"pin_is_set\": \"marqeta:pinIsSet\",\n        \"metadata\": \"marqeta:metadata\",\n        \"created_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_modified_time\"\
  : {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CardProduct\": {\n      \"@id\": \"marqeta:CardProduct\",\n      \"@context\": {\n        \"token\": \"marqeta:token\",\n        \"name\": \"schema:name\",\n        \"active\": \"marqeta:active\",\n        \"start_date\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"end_date\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"created_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_modified_time\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Transaction\": {\n      \"@id\": \"marqeta:Transaction\",\n      \"@context\": {\n        \"token\": \"marqeta:token\",\n        \"type\": \"marqeta:transactionType\",\n        \"\
  state\": \"marqeta:transactionState\",\n        \"user_token\": \"marqeta:cardholder\",\n        \"card_token\": \"marqeta:paymentCard\",\n        \"business_token\": \"marqeta:businessHolder\",\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency_code\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"network\": \"marqeta:cardNetwork\",\n        \"settlement_date\": {\n          \"@id\": \"marqeta:settlementDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"created_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"user_transaction_time\": {\n          \"@id\": \"marqeta:userTransactionTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CardAcceptor\": {\n      \"@id\": \"marqeta:CardAcceptor\",\n      \"@context\": {\n        \"mid\": \"marqeta:merchantId\"\
  ,\n        \"mcc\": \"marqeta:merchantCategoryCode\",\n        \"name\": \"schema:name\",\n        \"address\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"zip\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\"\n      }\n    },\n\n    \"GpaOrder\": {\n      \"@id\": \"marqeta:GpaOrder\",\n      \"@context\": {\n        \"token\": \"marqeta:token\",\n        \"user_token\": \"marqeta:cardholder\",\n        \"business_token\": \"marqeta:businessHolder\",\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency_code\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": \"marqeta:orderState\",\n        \"funding_source_token\": \"marqeta:fundingSource\",\n        \"memo\": \"dcterms:description\",\n        \"created_time\": {\n          \"@id\"\
  : \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"FundingSource\": {\n      \"@id\": \"marqeta:FundingSource\",\n      \"@context\": {\n        \"token\": \"marqeta:token\",\n        \"account_type\": \"marqeta:accountType\",\n        \"account_suffix\": \"marqeta:accountSuffix\",\n        \"routing_number\": \"marqeta:routingNumber\",\n        \"name_on_account\": \"marqeta:nameOnAccount\",\n        \"verification_status\": \"marqeta:verificationStatus\",\n        \"is_default_account\": \"marqeta:isDefaultAccount\",\n        \"created_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_modified_time\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"GpaBalance\": {\n      \"@id\": \"marqeta:GpaBalance\",\n      \"@context\": {\n        \"currency_code\": {\n          \"@id\": \"schema:priceCurrency\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"ledger_balance\": {\n          \"@id\": \"marqeta:ledgerBalance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"available_balance\": {\n          \"@id\": \"marqeta:availableBalance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"credit_balance\": {\n          \"@id\": \"marqeta:creditBalance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"pending_credits\": {\n          \"@id\": \"marqeta:pendingCredits\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"VelocityControl\": {\n      \"@id\": \"marqeta:VelocityControl\",\n      \"@context\": {\n        \"token\": \"marqeta:token\",\n        \"name\": \"schema:name\",\n        \"velocity_window\": \"marqeta:velocityWindow\",\n        \"amount_limit\": {\n          \"@id\": \"marqeta:amountLimit\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"usage_limit\": {\n          \"@id\": \"marqeta:usageLimit\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"currency_code\": \"schema:priceCurrency\",\n        \"active\": \"marqeta:active\",\n        \"created_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AuthorizationControl\": {\n      \"@id\": \"marqeta:AuthorizationControl\",\n      \"@context\": {\n        \"token\": \"marqeta:token\",\n        \"name\": \"schema:name\",\n        \"active\": \"marqeta:active\",\n        \"start_time\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"end_time\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"created_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"WebhookConfig\": {\n      \"@id\": \"marqeta:WebhookConfig\",\n      \"@context\": {\n        \"token\": \"marqeta:token\"\
  ,\n        \"name\": \"schema:name\",\n        \"active\": \"marqeta:active\",\n        \"events\": {\n          \"@id\": \"marqeta:events\",\n          \"@container\": \"@set\"\n        },\n        \"created_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_modified_time\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Business\": {\n      \"@id\": \"marqeta:Business\",\n      \"@context\": {\n        \"token\": \"marqeta:token\",\n        \"business_name_legal\": \"schema:legalName\",\n        \"business_name_dba\": \"schema:name\",\n        \"business_type\": \"marqeta:businessType\",\n        \"tax_id_number\": \"marqeta:taxIdNumber\",\n        \"phone\": \"schema:telephone\",\n        \"email\": \"schema:email\",\n        \"status\": \"marqeta:accountStatus\",\n        \"metadata\": \"marqeta:metadata\",\n        \"created_time\": {\n      \
  \    \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_modified_time\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/marqeta/refs/heads/main/json-ld/marqeta-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
