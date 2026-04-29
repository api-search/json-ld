---
api_specs:
- filename: commercetools-http-api-openapi.yml
  format: yaml
  label: Commercetools HTTP API
  slug: http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/commercetools/refs/heads/main/openapi/commercetools-http-api-openapi.yml
- filename: commercetools-import-api-openapi.yml
  format: yaml
  label: Commercetools Import API
  slug: import-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/commercetools/refs/heads/main/openapi/commercetools-import-api-openapi.yml
- filename: commercetools-change-history-api-openapi.yml
  format: yaml
  label: Commercetools Change History API
  slug: change-history-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/commercetools/refs/heads/main/openapi/commercetools-change-history-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/commercetools-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/commercetools/refs/heads/main/json-ld/commercetools-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Commercetools from commercetools.
layout: jsonld
name: Commercetools Context
namespaces:
- prefix: ct
  uri: https://api.commercetools.com/ontology#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
properties:
- container: ''
  name: Product
  type: ''
- container: ''
  name: ProductVariant
  type: ''
- container: ''
  name: Category
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: Cart
  type: ''
- container: ''
  name: Customer
  type: ''
- container: ''
  name: Payment
  type: ''
- container: ''
  name: InventoryEntry
  type: ''
- container: ''
  name: Store
  type: ''
- container: ''
  name: Money
  type: ''
- container: ''
  name: Address
  type: ''
- container: ''
  name: LineItem
  type: ''
- container: ''
  name: Subscription
  type: ''
property_count: 13
provider_name: commercetools
provider_slug: commercetools
slug: commercetools-context
source_filename: commercetools-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ct\": \"https://api.commercetools.com/ontology#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n\n    \"Product\": {\n      \"@id\": \"ct:Product\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"key\": \"ct:key\",\n        \"productType\": {\n          \"@id\": \"ct:productType\",\n          \"@type\": \"@id\"\n        },\n        \"masterData\": \"ct:masterData\",\n        \"taxCategory\": {\n          \"@id\": \"ct:taxCategory\",\n          \"@type\": \"@id\"\n        },\n        \"state\": {\n          \"@id\": \"ct:state\",\n          \"@type\": \"@id\"\n        },\n        \"priceMode\": \"ct:priceMode\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedAt\":\
  \ {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ProductVariant\": {\n      \"@id\": \"ct:ProductVariant\",\n      \"@context\": {\n        \"sku\": \"ct:sku\",\n        \"key\": \"ct:key\",\n        \"prices\": {\n          \"@id\": \"ct:prices\",\n          \"@container\": \"@set\"\n        },\n        \"attributes\": {\n          \"@id\": \"ct:attributes\",\n          \"@container\": \"@set\"\n        },\n        \"images\": {\n          \"@id\": \"ct:images\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Category\": {\n      \"@id\": \"ct:Category\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"key\": \"ct:key\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"slug\": \"ct:slug\",\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"parent\": {\n          \"@id\": \"ct:parent\",\n          \"@type\"\
  : \"@id\"\n        },\n        \"ancestors\": {\n          \"@id\": \"ct:ancestors\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"orderHint\": \"ct:orderHint\",\n        \"metaTitle\": \"ct:metaTitle\",\n        \"metaDescription\": \"ct:metaDescription\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"ct:Order\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"orderNumber\": \"ct:orderNumber\",\n        \"purchaseOrderNumber\": \"ct:purchaseOrderNumber\",\n        \"customerId\": \"ct:customerId\",\n        \"customerEmail\": {\n          \"@id\": \"schema:email\"\n        },\n        \"customerGroup\": {\n          \"@id\": \"ct:customerGroup\",\n          \"@type\": \"@id\"\n     \
  \   },\n        \"orderState\": \"ct:orderState\",\n        \"shipmentState\": \"ct:shipmentState\",\n        \"paymentState\": \"ct:paymentState\",\n        \"totalPrice\": \"ct:totalPrice\",\n        \"taxedPrice\": \"ct:taxedPrice\",\n        \"billingAddress\": {\n          \"@id\": \"schema:billingAddress\",\n          \"@type\": \"schema:PostalAddress\"\n        },\n        \"shippingAddress\": {\n          \"@id\": \"schema:deliveryAddress\",\n          \"@type\": \"schema:PostalAddress\"\n        },\n        \"lineItems\": {\n          \"@id\": \"ct:lineItems\",\n          \"@container\": \"@set\"\n        },\n        \"customLineItems\": {\n          \"@id\": \"ct:customLineItems\",\n          \"@container\": \"@set\"\n        },\n        \"deliveries\": {\n          \"@id\": \"ct:deliveries\",\n          \"@container\": \"@set\"\n        },\n        \"returnInfo\": {\n          \"@id\": \"ct:returnInfo\",\n          \"@container\": \"@set\"\n        },\n        \"store\": {\n\
  \          \"@id\": \"ct:store\",\n          \"@type\": \"@id\"\n        },\n        \"businessUnit\": {\n          \"@id\": \"ct:businessUnit\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedAt\": {\n          \"@id\": \"ct:completedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Cart\": {\n      \"@id\": \"ct:Cart\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"key\": \"ct:key\",\n        \"customerId\": \"ct:customerId\",\n        \"customerEmail\": {\n          \"@id\": \"schema:email\"\n        },\n        \"cartState\": \"ct:cartState\",\n        \"totalPrice\": \"ct:totalPrice\",\n        \"taxedPrice\": \"ct:taxedPrice\",\n        \"billingAddress\": {\n          \"@id\": \"schema:billingAddress\"\
  ,\n          \"@type\": \"schema:PostalAddress\"\n        },\n        \"shippingAddress\": {\n          \"@id\": \"schema:deliveryAddress\",\n          \"@type\": \"schema:PostalAddress\"\n        },\n        \"lineItems\": {\n          \"@id\": \"ct:lineItems\",\n          \"@container\": \"@set\"\n        },\n        \"taxMode\": \"ct:taxMode\",\n        \"inventoryMode\": \"ct:inventoryMode\",\n        \"store\": {\n          \"@id\": \"ct:store\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Customer\": {\n      \"@id\": \"ct:Customer\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"key\": \"ct:key\",\n        \"email\": {\n          \"@id\": \"schema:email\"\n        },\n        \"firstName\": {\n          \"\
  @id\": \"schema:givenName\"\n        },\n        \"lastName\": {\n          \"@id\": \"schema:familyName\"\n        },\n        \"dateOfBirth\": {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"isEmailVerified\": \"ct:isEmailVerified\",\n        \"customerGroup\": {\n          \"@id\": \"ct:customerGroup\",\n          \"@type\": \"@id\"\n        },\n        \"addresses\": {\n          \"@id\": \"schema:address\",\n          \"@type\": \"schema:PostalAddress\",\n          \"@container\": \"@set\"\n        },\n        \"stores\": {\n          \"@id\": \"ct:stores\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Payment\": {\n      \"@id\": \"\
  ct:Payment\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"key\": \"ct:key\",\n        \"customer\": {\n          \"@id\": \"ct:customer\",\n          \"@type\": \"@id\"\n        },\n        \"interfaceId\": \"ct:interfaceId\",\n        \"amountPlanned\": \"ct:amountPlanned\",\n        \"paymentMethodInfo\": \"ct:paymentMethodInfo\",\n        \"paymentStatus\": \"ct:paymentStatus\",\n        \"transactions\": {\n          \"@id\": \"ct:transactions\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"InventoryEntry\": {\n      \"@id\": \"ct:InventoryEntry\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"key\": \"ct:key\",\n        \"sku\": \"ct:sku\",\n        \"supplyChannel\": {\n          \"@id\"\
  : \"ct:supplyChannel\",\n          \"@type\": \"@id\"\n        },\n        \"quantityOnStock\": \"ct:quantityOnStock\",\n        \"availableQuantity\": \"ct:availableQuantity\",\n        \"restockableInDays\": \"ct:restockableInDays\",\n        \"expectedDelivery\": {\n          \"@id\": \"ct:expectedDelivery\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Store\": {\n      \"@id\": \"ct:Store\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"key\": \"ct:key\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"languages\": {\n          \"@id\": \"ct:languages\",\n          \"@container\": \"@set\"\n        },\n        \"countries\": {\n          \"@id\": \"ct:countries\",\n \
  \         \"@container\": \"@set\"\n        },\n        \"distributionChannels\": {\n          \"@id\": \"ct:distributionChannels\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"supplyChannels\": {\n          \"@id\": \"ct:supplyChannels\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"productSelections\": {\n          \"@id\": \"ct:productSelections\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Money\": {\n      \"@id\": \"ct:Money\",\n      \"@context\": {\n        \"currencyCode\": \"ct:currencyCode\",\n        \"centAmount\": \"ct:centAmount\",\n        \"fractionDigits\": \"ct:fractionDigits\"\n      }\n    },\n\n    \"Address\"\
  : {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"country\": {\n          \"@id\": \"schema:addressCountry\"\n        },\n        \"firstName\": {\n          \"@id\": \"schema:givenName\"\n        },\n        \"lastName\": {\n          \"@id\": \"schema:familyName\"\n        },\n        \"streetName\": {\n          \"@id\": \"schema:streetAddress\"\n        },\n        \"city\": {\n          \"@id\": \"schema:addressLocality\"\n        },\n        \"postalCode\": {\n          \"@id\": \"schema:postalCode\"\n        },\n        \"region\": {\n          \"@id\": \"schema:addressRegion\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\"\n        },\n        \"phone\": {\n          \"@id\": \"schema:telephone\"\n        }\n      }\n    },\n\n    \"LineItem\": {\n      \"@id\": \"ct:LineItem\",\n      \"@context\": {\n        \"productId\": {\n          \"@id\": \"ct:product\",\n          \"@type\": \"@id\"\n        },\n        \"name\": {\n\
  \          \"@id\": \"schema:name\"\n        },\n        \"quantity\": {\n          \"@id\": \"schema:amount\"\n        },\n        \"totalPrice\": \"ct:totalPrice\",\n        \"lineItemMode\": \"ct:lineItemMode\",\n        \"priceMode\": \"ct:priceMode\"\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"ct:Subscription\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"key\": \"ct:key\",\n        \"destination\": \"ct:destination\",\n        \"messages\": {\n          \"@id\": \"ct:messages\",\n          \"@container\": \"@set\"\n        },\n        \"changes\": {\n          \"@id\": \"ct:changes\",\n          \"@container\": \"@set\"\n        },\n        \"format\": \"ct:format\",\n        \"status\": \"ct:status\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n     \
  \ }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/commercetools/refs/heads/main/json-ld/commercetools-context.jsonld
tags:
- Commerce
- Composable Commerce
- E-Commerce
- GraphQL
- REST
- SDK
- JSON-LD
- Linked Data
- Semantic Web
---
