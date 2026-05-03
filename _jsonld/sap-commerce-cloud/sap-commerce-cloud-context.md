---
api_specs:
- filename: overview
  format: yaml
  label: Commerce Web Services API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/commerce_web_services/overview
- filename: sap-commerce-cloud-assisted-service-openapi.yml
  format: yaml
  label: Assisted Service Module API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-commerce-cloud/refs/heads/main/openapi/sap-commerce-cloud-assisted-service-openapi.yml
- filename: sap-commerce-cloud-integration-openapi.yml
  format: yaml
  label: Integration API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-commerce-cloud/refs/heads/main/openapi/sap-commerce-cloud-integration-openapi.yml
- filename: sap-commerce-cloud-admin-openapi.yml
  format: yaml
  label: Admin API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-commerce-cloud/refs/heads/main/openapi/sap-commerce-cloud-admin-openapi.yml
- filename: sap-commerce-cloud-product-content-management-openapi.yml
  format: yaml
  label: Product Content Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-commerce-cloud/refs/heads/main/openapi/sap-commerce-cloud-product-content-management-openapi.yml
class_count: 0
classes: []
context_file: json-ld/sap-commerce-cloud-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sap-commerce-cloud/refs/heads/main/json-ld/sap-commerce-cloud-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sap Commerce Cloud from SAP Commerce Cloud.
layout: jsonld
name: Sap Commerce Cloud Context
namespaces:
- prefix: sap
  uri: https://api.sap.com/schemas/sap-commerce-cloud/
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
  name: Product
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
  name: Address
  type: ''
- container: ''
  name: Price
  type: ''
- container: ''
  name: DeliveryMode
  type: ''
- container: ''
  name: PaymentDetails
  type: ''
- container: ''
  name: PointOfService
  type: ''
- container: ''
  name: Review
  type: ''
- container: ''
  name: Category
  type: ''
- container: ''
  name: Consignment
  type: ''
- container: ''
  name: Voucher
  type: ''
- container: ''
  name: Catalog
  type: ''
property_count: 14
provider_name: SAP Commerce Cloud
provider_slug: sap-commerce-cloud
slug: sap-commerce-cloud-context
source_filename: sap-commerce-cloud-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sap\": \"https://api.sap.com/schemas/sap-commerce-cloud/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n\n    \"Product\": {\n      \"@id\": \"schema:Product\",\n      \"@context\": {\n        \"code\": \"schema:sku\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"summary\": \"sap:summary\",\n        \"manufacturer\": \"schema:manufacturer\",\n        \"ean\": \"schema:gtin13\",\n        \"url\": \"schema:url\",\n        \"purchasable\": {\n          \"@id\": \"schema:offers\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"averageRating\": {\n          \"@id\": \"schema:aggregateRating\",\n          \"@type\": \"xsd:double\"\n        },\n        \"price\": \"schema:offers\",\n        \"images\": \"schema:image\"\
  ,\n        \"categories\": \"schema:category\"\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"schema:Order\",\n      \"@context\": {\n        \"code\": \"schema:orderNumber\",\n        \"status\": \"schema:orderStatus\",\n        \"created\": {\n          \"@id\": \"schema:orderDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"totalPrice\": \"schema:totalPrice\",\n        \"entries\": \"sap:orderEntries\",\n        \"deliveryAddress\": \"schema:deliveryAddress\",\n        \"deliveryMode\": \"sap:deliveryMode\",\n        \"paymentInfo\": \"schema:paymentMethod\",\n        \"user\": \"schema:customer\"\n      }\n    },\n\n    \"Cart\": {\n      \"@id\": \"sap:Cart\",\n      \"@context\": {\n        \"code\": \"schema:identifier\",\n        \"totalItems\": {\n          \"@id\": \"sap:totalItems\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalPrice\": \"schema:totalPrice\",\n        \"entries\": \"sap:cartEntries\",\n        \"deliveryAddress\"\
  : \"schema:deliveryAddress\",\n        \"deliveryMode\": \"sap:deliveryMode\",\n        \"paymentInfo\": \"schema:paymentMethod\",\n        \"user\": \"schema:customer\",\n        \"appliedVouchers\": \"sap:appliedVouchers\"\n      }\n    },\n\n    \"Customer\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"uid\": \"schema:email\",\n        \"name\": \"schema:name\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"titleCode\": \"schema:honorificPrefix\",\n        \"currency\": \"sap:preferredCurrency\",\n        \"language\": \"sap:preferredLanguage\",\n        \"defaultAddress\": \"schema:address\",\n        \"addresses\": \"schema:address\",\n        \"paymentDetails\": \"schema:paymentMethod\"\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"line1\"\
  : \"schema:streetAddress\",\n        \"town\": \"schema:addressLocality\",\n        \"postalCode\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\",\n        \"region\": \"schema:addressRegion\",\n        \"phone\": \"schema:telephone\",\n        \"email\": \"schema:email\"\n      }\n    },\n\n    \"Price\": {\n      \"@id\": \"schema:PriceSpecification\",\n      \"@context\": {\n        \"currencyIso\": \"schema:priceCurrency\",\n        \"value\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:double\"\n        },\n        \"formattedValue\": \"sap:formattedPrice\"\n      }\n    },\n\n    \"DeliveryMode\": {\n      \"@id\": \"schema:DeliveryMethod\",\n      \"@context\": {\n        \"code\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"deliveryCost\": \"schema:price\"\n      }\n    },\n\n    \"PaymentDetails\": {\n      \"@id\": \"schema:PaymentMethod\",\n      \"@context\"\
  : {\n        \"accountHolderName\": \"schema:name\",\n        \"cardNumber\": \"sap:maskedCardNumber\",\n        \"expiryMonth\": \"sap:expiryMonth\",\n        \"expiryYear\": \"sap:expiryYear\",\n        \"billingAddress\": \"schema:billingAddress\"\n      }\n    },\n\n    \"PointOfService\": {\n      \"@id\": \"schema:Store\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"description\": \"schema:description\",\n        \"address\": \"schema:address\",\n        \"geoPoint\": \"schema:geo\",\n        \"openingHours\": \"schema:openingHoursSpecification\"\n      }\n    },\n\n    \"Review\": {\n      \"@id\": \"schema:Review\",\n      \"@context\": {\n        \"headline\": \"schema:headline\",\n        \"comment\": \"schema:reviewBody\",\n        \"rating\": {\n          \"@id\": \"schema:reviewRating\",\n          \"@type\": \"xsd:double\"\n        },\n        \"date\": {\n          \"@id\": \"schema:datePublished\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"alias\": \"schema:author\"\n      }\n    },\n\n    \"Category\": {\n      \"@id\": \"schema:Category\",\n      \"@context\": {\n        \"code\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"url\": \"schema:url\"\n      }\n    },\n\n    \"Consignment\": {\n      \"@id\": \"schema:ParcelDelivery\",\n      \"@context\": {\n        \"code\": \"schema:identifier\",\n        \"status\": \"schema:deliveryStatus\",\n        \"trackingID\": \"schema:trackingNumber\"\n      }\n    },\n\n    \"Voucher\": {\n      \"@id\": \"sap:Voucher\",\n      \"@context\": {\n        \"code\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"value\": {\n          \"@id\": \"schema:discount\",\n          \"@type\": \"xsd:double\"\n        },\n        \"freeShipping\": {\n          \"@id\": \"sap:freeShipping\",\n          \"@type\": \"xsd:boolean\"\n  \
  \      }\n      }\n    },\n\n    \"Catalog\": {\n      \"@id\": \"schema:DataCatalog\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sap-commerce-cloud/refs/heads/main/json-ld/sap-commerce-cloud-context.jsonld
tags:
- B2B
- B2C
- Commerce
- Customer Experience
- Ecommerce
- Omnichannel
- Retail
- JSON-LD
- Linked Data
- Semantic Web
---
