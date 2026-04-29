---
class_count: 0
classes: []
context_file: json-ld/square-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/square/refs/heads/main/json-ld/square-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Square from Square.
layout: jsonld
name: Square Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: square
  uri: https://developer.squareup.com/reference/square/objects/
properties:
- container: ''
  name: Payment
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: OrderLineItem
  type: ''
- container: ''
  name: CatalogItem
  type: ''
- container: ''
  name: CatalogItemVariation
  type: ''
- container: ''
  name: Customer
  type: ''
- container: ''
  name: Location
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: Money
  type: ''
- container: ''
  name: Address
  type: ''
property_count: 10
provider_name: Square
provider_slug: square
slug: square-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"square\": \"https://developer.squareup.com/reference/square/objects/\",\n\n    \"Payment\": {\n      \"@id\": \"schema:PayAction\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"created_at\": \"schema:dateCreated\",\n        \"updated_at\": \"schema:dateModified\",\n        \"amount_money\": \"schema:price\",\n        \"tip_money\": \"schema:tip\",\n        \"total_money\": \"schema:totalPrice\",\n        \"status\": \"schema:paymentStatus\",\n        \"source_type\": \"schema:paymentMethod\",\n        \"currency\": \"schema:priceCurrency\",\n        \"receipt_url\": \"schema:url\",\n        \"receipt_number\": \"schema:confirmationNumber\",\n        \"buyer_email_address\": \"schema:email\",\n        \"billing_address\": \"schema:billingAddress\",\n        \"shipping_address\": \"schema:deliveryAddress\",\n        \"note\": \"schema:description\",\n   \
  \     \"location_id\": \"schema:locationCreated\",\n        \"order_id\": \"schema:referencesOrder\",\n        \"customer_id\": \"schema:customer\",\n        \"reference_id\": \"schema:orderNumber\",\n        \"card_details\": \"schema:paymentMethodId\",\n        \"refunded_money\": \"schema:totalPaymentDue\"\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"schema:Order\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"created_at\": \"schema:orderDate\",\n        \"updated_at\": \"schema:dateModified\",\n        \"closed_at\": \"schema:dateCompleted\",\n        \"location_id\": \"schema:seller\",\n        \"customer_id\": \"schema:customer\",\n        \"reference_id\": \"schema:orderNumber\",\n        \"state\": \"schema:orderStatus\",\n        \"line_items\": \"schema:orderedItem\",\n        \"taxes\": \"schema:taxApplied\",\n        \"discounts\": \"schema:discount\",\n        \"service_charges\": \"schema:serviceCharge\",\n        \"fulfillments\": \"\
  schema:orderDelivery\",\n        \"total_money\": \"schema:totalPrice\",\n        \"total_tax_money\": \"schema:tax\",\n        \"total_discount_money\": \"schema:discount\",\n        \"total_tip_money\": \"schema:tip\",\n        \"tenders\": \"schema:paymentMethod\",\n        \"metadata\": \"schema:additionalProperty\",\n        \"ticket_name\": \"schema:name\",\n        \"returns\": \"schema:orderItemStatus\"\n      }\n    },\n\n    \"OrderLineItem\": {\n      \"@id\": \"schema:OrderItem\",\n      \"@context\": {\n        \"uid\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"quantity\": \"schema:orderQuantity\",\n        \"catalog_object_id\": \"schema:orderedItem\",\n        \"variation_name\": \"schema:additionalType\",\n        \"note\": \"schema:description\",\n        \"base_price_money\": \"schema:price\",\n        \"total_money\": \"schema:totalPrice\",\n        \"item_type\": \"schema:category\"\n      }\n    },\n\n    \"CatalogItem\": {\n      \"@id\"\
  : \"schema:Product\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"description_html\": \"schema:description\",\n        \"abbreviation\": \"schema:alternateName\",\n        \"categories\": \"schema:category\",\n        \"variations\": \"schema:hasVariant\",\n        \"image_ids\": \"schema:image\",\n        \"is_taxable\": \"schema:additionalProperty\",\n        \"product_type\": \"schema:additionalType\",\n        \"modifier_list_info\": \"schema:addOn\",\n        \"item_options\": \"schema:itemOption\",\n        \"sort_name\": \"schema:alternateName\",\n        \"reporting_category\": \"schema:category\",\n        \"is_archived\": \"schema:discontinued\"\n      }\n    },\n\n    \"CatalogItemVariation\": {\n      \"@id\": \"schema:ProductModel\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"sku\": \"schema:sku\",\n        \"upc\": \"schema:gtin\",\n        \"pricing_type\": \"schema:priceSpecification\"\
  ,\n        \"price_money\": \"schema:price\",\n        \"track_inventory\": \"schema:inventoryLevel\",\n        \"sellable\": \"schema:availability\",\n        \"stockable\": \"schema:inventoryLevel\"\n      }\n    },\n\n    \"Customer\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"created_at\": \"schema:dateCreated\",\n        \"updated_at\": \"schema:dateModified\",\n        \"given_name\": \"schema:givenName\",\n        \"family_name\": \"schema:familyName\",\n        \"nickname\": \"schema:alternateName\",\n        \"company_name\": \"schema:worksFor\",\n        \"email_address\": \"schema:email\",\n        \"address\": \"schema:address\",\n        \"phone_number\": \"schema:telephone\",\n        \"birthday\": \"schema:birthDate\",\n        \"note\": \"schema:description\",\n        \"reference_id\": \"schema:additionalName\",\n        \"group_ids\": \"schema:memberOf\",\n        \"segment_ids\": \"schema:memberOf\"\
  ,\n        \"creation_source\": \"schema:additionalProperty\",\n        \"preferences\": \"schema:interactionStatistic\"\n      }\n    },\n\n    \"Location\": {\n      \"@id\": \"schema:LocalBusiness\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"address\": \"schema:address\",\n        \"timezone\": \"schema:timezone\",\n        \"status\": \"schema:eventStatus\",\n        \"created_at\": \"schema:dateCreated\",\n        \"merchant_id\": \"schema:parentOrganization\",\n        \"country\": \"schema:addressCountry\",\n        \"language_code\": \"schema:inLanguage\",\n        \"currency\": \"schema:currenciesAccepted\",\n        \"phone_number\": \"schema:telephone\",\n        \"business_name\": \"schema:legalName\",\n        \"type\": \"schema:additionalType\",\n        \"website_url\": \"schema:url\",\n        \"business_hours\": \"schema:openingHoursSpecification\",\n        \"business_email\": \"schema:email\",\n    \
  \    \"description\": \"schema:description\",\n        \"twitter_username\": \"schema:sameAs\",\n        \"instagram_username\": \"schema:sameAs\",\n        \"facebook_url\": \"schema:sameAs\",\n        \"coordinates\": \"schema:geo\",\n        \"logo_url\": \"schema:logo\",\n        \"mcc\": \"schema:naics\"\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"schema:SubscribeAction\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"location_id\": \"schema:location\",\n        \"plan_variation_id\": \"schema:object\",\n        \"customer_id\": \"schema:agent\",\n        \"start_date\": \"schema:startDate\",\n        \"canceled_date\": \"schema:endDate\",\n        \"charged_through_date\": \"schema:validThrough\",\n        \"status\": \"schema:actionStatus\",\n        \"tax_percentage\": \"schema:taxPercentage\",\n        \"invoice_ids\": \"schema:referencesOrder\",\n        \"price_override_money\": \"schema:price\",\n        \"created_at\": \"schema:dateCreated\"\
  ,\n        \"timezone\": \"schema:timezone\",\n        \"monthly_billing_anchor_date\": \"schema:billingPeriod\",\n        \"phases\": \"schema:priceSpecification\"\n      }\n    },\n\n    \"Money\": {\n      \"@id\": \"schema:MonetaryAmount\",\n      \"@context\": {\n        \"amount\": \"schema:value\",\n        \"currency\": \"schema:currency\"\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"address_line_1\": \"schema:streetAddress\",\n        \"address_line_2\": \"schema:streetAddress\",\n        \"address_line_3\": \"schema:streetAddress\",\n        \"locality\": \"schema:addressLocality\",\n        \"sublocality\": \"schema:addressLocality\",\n        \"administrative_district_level_1\": \"schema:addressRegion\",\n        \"postal_code\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/square/refs/heads/main/json-ld/square-context.jsonld
tags:
- Bookings
- Catalog
- Checkout
- Customers
- Disputes
- Ecommerce
- Financial Technology
- Gift Cards
- Inventory
- Invoicing
- Labor
- Locations
- Loyalty
- Merchants
- Orders
- Payments
- Point of Sale
- Refunds
- Retail
- Subscriptions
- Team
- Terminal
- Webhooks
- JSON-LD
- Linked Data
- Semantic Web
---
