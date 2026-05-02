---
api_specs:
- filename: instacart-developer-platform-api-openapi.yml
  format: yaml
  label: Instacart Developer Platform API
  slug: developer-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/instacart/refs/heads/main/openapi/instacart-developer-platform-api-openapi.yml
- filename: instacart-connect-fulfillment-api-openapi.yml
  format: yaml
  label: Instacart Connect Fulfillment API
  slug: connect-fulfillment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/instacart/refs/heads/main/openapi/instacart-connect-fulfillment-api-openapi.yml
- filename: instacart-connect-post-checkout-api-openapi.yml
  format: yaml
  label: Instacart Connect Post-Checkout API
  slug: connect-post-checkout-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/instacart/refs/heads/main/openapi/instacart-connect-post-checkout-api-openapi.yml
- filename: instacart-catalog-api-openapi.yml
  format: yaml
  label: Instacart Catalog API
  slug: catalog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/instacart/refs/heads/main/openapi/instacart-catalog-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/instacart-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/instacart/refs/heads/main/json-ld/instacart-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Instacart from instacart.
layout: jsonld
name: Instacart Context
namespaces:
- prefix: instacart
  uri: https://connect.instacart.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Order
  type: ''
- container: ''
  name: Store
  type: ''
- container: ''
  name: Product
  type: ''
- container: ''
  name: OrderItem
  type: ''
- container: ''
  name: Shopper
  type: ''
- container: ''
  name: ServiceOption
  type: ''
- container: ''
  name: Address
  type: ''
- container: ''
  name: Recipe
  type: ''
property_count: 8
provider_name: instacart
provider_slug: instacart
slug: instacart-context
source_filename: instacart-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"instacart\": \"https://connect.instacart.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Order\": {\n      \"@id\": \"instacart:Order\",\n      \"@context\": {\n        \"orderId\": \"instacart:orderId\",\n        \"status\": \"instacart:orderStatus\",\n        \"fulfillmentType\": \"instacart:fulfillmentType\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"estimatedDeliveryAt\": {\n          \"@id\": \"instacart:estimatedDeliveryAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"deliveryAddress\": {\n          \"@id\": \"schema:deliveryAddress\",\n          \"@type\": \"@id\"\n        },\n        \"deliveryInstructions\": \"instacart:deliveryInstructions\",\n        \"items\": {\n          \"@id\": \"instacart:orderItems\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"store\": {\n          \"@id\": \"instacart:store\",\n          \"@type\": \"@id\"\n        },\n        \"shopper\": {\n          \"@id\": \"instacart:shopper\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Store\": {\n      \"@id\": \"schema:Store\",\n      \"@context\": {\n        \"storeId\": \"instacart:storeId\",\n        \"name\": \"schema:name\",\n        \"address\": {\n          \"@id\": \"schema:address\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Product\": {\n      \"@id\": \"schema:Product\",\n      \"@context\": {\n        \"productCode\": \"instacart:productCode\",\n        \"name\": \"schema:name\",\n        \"brand\": \"schema:brand\",\n        \"description\": \"schema:description\",\n        \"size\": \"schema:size\",\n        \"upc\": \"schema:gtin\",\n        \"imageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n    \
  \    \"category\": \"schema:category\",\n        \"department\": \"instacart:department\"\n      }\n    },\n\n    \"OrderItem\": {\n      \"@id\": \"instacart:OrderItem\",\n      \"@context\": {\n        \"productId\": \"instacart:productId\",\n        \"upc\": \"schema:gtin\",\n        \"name\": \"schema:name\",\n        \"quantity\": \"schema:amount\",\n        \"status\": \"instacart:itemStatus\",\n        \"replacement\": {\n          \"@id\": \"instacart:replacement\",\n          \"@type\": \"@id\"\n        },\n        \"replacementStatus\": \"instacart:replacementStatus\",\n        \"refunded\": \"instacart:refunded\"\n      }\n    },\n\n    \"Shopper\": {\n      \"@id\": \"instacart:Shopper\",\n      \"@context\": {\n        \"name\": \"schema:givenName\",\n        \"phoneNumber\": \"schema:telephone\"\n      }\n    },\n\n    \"ServiceOption\": {\n      \"@id\": \"instacart:ServiceOption\",\n      \"@context\": {\n        \"serviceOptionId\": \"instacart:serviceOptionId\",\n   \
  \     \"date\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"windowStartsAt\": {\n          \"@id\": \"instacart:windowStartsAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"windowEndsAt\": {\n          \"@id\": \"instacart:windowEndsAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"fulfillmentType\": \"instacart:fulfillmentType\"\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"addressLine1\": \"schema:streetAddress\",\n        \"addressLine2\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"postalCode\": \"schema:postalCode\",\n        \"latitude\": \"schema:latitude\",\n        \"longitude\": \"schema:longitude\"\n      }\n    },\n\n    \"Recipe\": {\n      \"@id\": \"schema:Recipe\",\n      \"@context\": {\n        \"title\": \"schema:name\",\n\
  \        \"imageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"author\": \"schema:author\",\n        \"servings\": \"schema:recipeYield\",\n        \"cookingTime\": \"schema:cookTime\",\n        \"instructions\": \"schema:recipeInstructions\",\n        \"ingredients\": {\n          \"@id\": \"schema:recipeIngredient\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/instacart/refs/heads/main/json-ld/instacart-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
