---
api_specs:
- filename: shipstation-v1-openapi.yml
  format: yaml
  label: ShipStation V1 API
  slug: shipstation-v1-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shipstation/refs/heads/main/openapi/shipstation-v1-openapi.yml
class_count: 43
classes:
- Order
- Shipment
- Label
- Rate
- Customer
- Product
- Warehouse
- Store
- Fulfillment
- orderId
- orderKey
- orderStatus
- customerId
- customerEmail
- customerUsername
- name
- company
- street1
- street2
- city
- state
- postalCode
- country
- phone
- residential
- lineItemKey
- sku
- carrierCode
- serviceCode
- packageCode
- trackingNumber
- shipmentId
- voided
- labelData
- units
- warehouseId
- warehouseName
- isDefault
- storeId
- storeName
- marketplaceId
- marketplaceName
- active
context_file: json-ld/shipstation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/shipstation/refs/heads/main/json-ld/shipstation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Shipstation from ShipStation.
layout: jsonld
name: Shipstation Context
namespaces:
- prefix: shipstation
  uri: https://ssapi.shipstation.com/schema/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: orderNumber
  type: string
- container: ''
  name: orderDate
  type: dateTime
- container: ''
  name: createDate
  type: dateTime
- container: ''
  name: modifyDate
  type: dateTime
- container: ''
  name: paymentDate
  type: dateTime
- container: ''
  name: shipByDate
  type: dateTime
- container: ''
  name: billTo
  type: schema:PostalAddress
- container: ''
  name: shipTo
  type: schema:PostalAddress
- container: list
  name: items
  type: ''
- container: ''
  name: quantity
  type: integer
- container: ''
  name: unitPrice
  type: float
- container: ''
  name: orderTotal
  type: float
- container: ''
  name: amountPaid
  type: float
- container: ''
  name: taxAmount
  type: float
- container: ''
  name: shippingAmount
  type: float
- container: ''
  name: shipDate
  type: date
- container: ''
  name: shipmentCost
  type: float
- container: ''
  name: weight
  type: schema:QuantitativeValue
- container: ''
  name: dimensions
  type: schema:QuantitativeValue
- container: ''
  name: value
  type: float
property_count: 20
provider_name: ShipStation
provider_slug: shipstation
slug: shipstation-context
source_filename: shipstation-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"shipstation\": \"https://ssapi.shipstation.com/schema/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Order\": \"schema:Order\",\n    \"Shipment\": \"shipstation:Shipment\",\n    \"Label\": \"shipstation:ShippingLabel\",\n    \"Rate\": \"schema:DeliveryChargeSpecification\",\n    \"Customer\": \"schema:Customer\",\n    \"Product\": \"schema:Product\",\n    \"Warehouse\": \"schema:Warehouse\",\n    \"Store\": \"schema:Store\",\n    \"Fulfillment\": \"schema:OrderItem\",\n\n    \"orderId\": \"schema:orderNumber\",\n    \"orderNumber\": { \"@id\": \"schema:orderNumber\", \"@type\": \"xsd:string\" },\n    \"orderKey\": \"shipstation:orderKey\",\n    \"orderDate\": { \"@id\": \"schema:orderDate\", \"@type\": \"xsd:dateTime\" },\n    \"createDate\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"modifyDate\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"\
  \ },\n    \"paymentDate\": { \"@id\": \"schema:paymentDueDate\", \"@type\": \"xsd:dateTime\" },\n    \"shipByDate\": { \"@id\": \"shipstation:shipByDate\", \"@type\": \"xsd:dateTime\" },\n    \"orderStatus\": \"schema:orderStatus\",\n\n    \"customerId\": \"schema:identifier\",\n    \"customerEmail\": \"schema:email\",\n    \"customerUsername\": \"schema:alternateName\",\n\n    \"billTo\": { \"@id\": \"schema:billingAddress\", \"@type\": \"schema:PostalAddress\" },\n    \"shipTo\": { \"@id\": \"schema:deliveryAddress\", \"@type\": \"schema:PostalAddress\" },\n\n    \"name\": \"schema:name\",\n    \"company\": \"schema:legalName\",\n    \"street1\": \"schema:streetAddress\",\n    \"street2\": \"shipstation:streetAddress2\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"postalCode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n    \"phone\": \"schema:telephone\",\n    \"residential\": \"shipstation:isResidential\",\n\n\
  \    \"items\": { \"@id\": \"schema:orderedItem\", \"@container\": \"@list\" },\n    \"lineItemKey\": \"schema:identifier\",\n    \"sku\": \"schema:sku\",\n    \"quantity\": { \"@id\": \"schema:orderQuantity\", \"@type\": \"xsd:integer\" },\n    \"unitPrice\": { \"@id\": \"schema:price\", \"@type\": \"xsd:float\" },\n\n    \"orderTotal\": { \"@id\": \"schema:totalPrice\", \"@type\": \"xsd:float\" },\n    \"amountPaid\": { \"@id\": \"schema:totalPaymentDue\", \"@type\": \"xsd:float\" },\n    \"taxAmount\": { \"@id\": \"schema:taxAmount\", \"@type\": \"xsd:float\" },\n    \"shippingAmount\": { \"@id\": \"schema:deliveryChargeSpecification\", \"@type\": \"xsd:float\" },\n\n    \"carrierCode\": \"schema:provider\",\n    \"serviceCode\": \"shipstation:serviceCode\",\n    \"packageCode\": \"shipstation:packageCode\",\n    \"trackingNumber\": \"schema:trackingNumber\",\n\n    \"shipmentId\": \"schema:identifier\",\n    \"shipDate\": { \"@id\": \"schema:dateShipped\", \"@type\": \"xsd:date\" },\n\
  \    \"shipmentCost\": { \"@id\": \"schema:price\", \"@type\": \"xsd:float\" },\n    \"voided\": \"shipstation:isVoided\",\n    \"labelData\": \"shipstation:labelData\",\n\n    \"weight\": { \"@id\": \"schema:weight\", \"@type\": \"schema:QuantitativeValue\" },\n    \"dimensions\": { \"@id\": \"schema:hasMeasurement\", \"@type\": \"schema:QuantitativeValue\" },\n    \"value\": { \"@id\": \"schema:value\", \"@type\": \"xsd:float\" },\n    \"units\": \"schema:unitCode\",\n\n    \"warehouseId\": \"schema:identifier\",\n    \"warehouseName\": \"schema:name\",\n    \"isDefault\": \"shipstation:isDefault\",\n\n    \"storeId\": \"schema:identifier\",\n    \"storeName\": \"schema:name\",\n    \"marketplaceId\": \"schema:identifier\",\n    \"marketplaceName\": \"schema:name\",\n    \"active\": \"schema:isAccessibleForFree\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/shipstation/refs/heads/main/json-ld/shipstation-context.jsonld
tags:
- Ecommerce
- Labels
- Logistics
- Order Management
- Shipping
- Warehousing
- JSON-LD
- Linked Data
- Semantic Web
---
