---
api_specs:
- filename: oracle-retail-merchandising-openapi.yml
  format: yaml
  label: Oracle Retail Merchandising Foundation Cloud Service API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-retail/refs/heads/main/openapi/oracle-retail-merchandising-openapi.yml
- filename: oracle-retail-order-management-openapi.yml
  format: yaml
  label: Oracle Retail Order Management Suite Cloud Service API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-retail/refs/heads/main/openapi/oracle-retail-order-management-openapi.yml
class_count: 0
classes: []
context_file: json-ld/oracle-retail-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-retail/refs/heads/main/json-ld/oracle-retail-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Retail from Oracle Retail.
layout: jsonld
name: Oracle Retail Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: retail
  uri: https://docs.oracle.com/en/industries/retail/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
properties:
- container: ''
  name: Item
  type: reference
- container: ''
  name: item
  type: ''
- container: ''
  name: itemDesc
  type: ''
- container: ''
  name: itemDescSecond
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: dept
  type: integer
- container: ''
  name: class
  type: integer
- container: ''
  name: subclass
  type: integer
- container: ''
  name: unitRetail
  type: decimal
- container: ''
  name: currencyCode
  type: ''
- container: ''
  name: unitCost
  type: decimal
- container: ''
  name: supplier
  type: ''
- container: ''
  name: originCountry
  type: ''
- container: ''
  name: PurchaseOrder
  type: reference
- container: ''
  name: orderId
  type: ''
- container: ''
  name: orderDate
  type: dateTime
- container: ''
  name: orderTotal
  type: decimal
- container: ''
  name: Supplier
  type: reference
- container: ''
  name: supplierName
  type: ''
- container: ''
  name: primaryContactName
  type: ''
- container: ''
  name: primaryEmail
  type: ''
- container: ''
  name: primaryPhone
  type: ''
- container: ''
  name: Order
  type: reference
- container: ''
  name: channelId
  type: ''
- container: ''
  name: customerId
  type: ''
- container: ''
  name: shippingAddress
  type: ''
- container: ''
  name: billingAddress
  type: ''
- container: ''
  name: InventoryPosition
  type: reference
- container: ''
  name: stockOnHand
  type: decimal
- container: ''
  name: availableToSell
  type: decimal
property_count: 30
provider_name: Oracle Retail
provider_slug: oracle-retail
slug: oracle-retail-context
source_filename: oracle-retail-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"retail\": \"https://docs.oracle.com/en/industries/retail/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n\n    \"Item\": {\n      \"@id\": \"schema:Product\",\n      \"@type\": \"@id\"\n    },\n    \"item\": {\n      \"@id\": \"schema:productID\"\n    },\n    \"itemDesc\": {\n      \"@id\": \"schema:name\"\n    },\n    \"itemDescSecond\": {\n      \"@id\": \"schema:description\"\n    },\n    \"status\": {\n      \"@id\": \"schema:itemCondition\"\n    },\n    \"dept\": {\n      \"@id\": \"retail:department\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"class\": {\n      \"@id\": \"retail:class\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"subclass\": {\n      \"@id\": \"retail:subclass\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"unitRetail\": {\n      \"@id\": \"gr:hasPriceSpecification\",\n     \
  \ \"@type\": \"xsd:decimal\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"schema:priceCurrency\"\n    },\n    \"unitCost\": {\n      \"@id\": \"retail:unitCost\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"supplier\": {\n      \"@id\": \"schema:supplier\"\n    },\n    \"originCountry\": {\n      \"@id\": \"schema:countryOfOrigin\"\n    },\n\n    \"PurchaseOrder\": {\n      \"@id\": \"schema:Order\",\n      \"@type\": \"@id\"\n    },\n    \"orderId\": {\n      \"@id\": \"schema:orderNumber\"\n    },\n    \"orderDate\": {\n      \"@id\": \"schema:orderDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"orderTotal\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"Supplier\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"@id\"\n    },\n    \"supplierName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"primaryContactName\": {\n      \"@id\": \"schema:contactPoint\"\n    },\n    \"primaryEmail\": {\n      \"@id\"\
  : \"schema:email\"\n    },\n    \"primaryPhone\": {\n      \"@id\": \"schema:telephone\"\n    },\n\n    \"Order\": {\n      \"@id\": \"schema:Order\",\n      \"@type\": \"@id\"\n    },\n    \"channelId\": {\n      \"@id\": \"retail:salesChannel\"\n    },\n    \"customerId\": {\n      \"@id\": \"schema:customer\"\n    },\n    \"shippingAddress\": {\n      \"@id\": \"schema:deliveryAddress\"\n    },\n    \"billingAddress\": {\n      \"@id\": \"schema:billingAddress\"\n    },\n\n    \"InventoryPosition\": {\n      \"@id\": \"schema:ItemAvailability\",\n      \"@type\": \"@id\"\n    },\n    \"stockOnHand\": {\n      \"@id\": \"retail:stockOnHand\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"availableToSell\": {\n      \"@id\": \"retail:availableToSell\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-retail/refs/heads/main/json-ld/oracle-retail-context.jsonld
tags:
- Retail
- Merchandising
- Order Management
- Pricing
- Inventory
- Point of Sale
- Omnichannel
- Oracle
- JSON-LD
- Linked Data
- Semantic Web
---
