---
api_specs:
- filename: toys-r-us-commerce-openapi.yml
  format: yaml
  label: Toys R Us Commerce API
  slug: logicbroker-commerce
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toys-r-us/refs/heads/main/openapi/toys-r-us-commerce-openapi.yml
class_count: 34
classes:
- Order
- key
- PartnerPO
- OrderDate
- Status
- ShipToAddress
- Name
- Address1
- Address2
- City
- State
- Zip
- Country
- LineItems
- LineNumber
- SupplierSKU
- BuyerSKU
- UPC
- Description
- Quantity
- UnitPrice
- UOM
- Shipment
- TrackingNumber
- Carrier
- ShipDate
- Package
- Weight
- Invoice
- InvoiceNumber
- InvoiceDate
- Product
- MSRP
- InStock
context_file: json-ld/toys-r-us-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/toys-r-us/refs/heads/main/json-ld/toys-r-us-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Toys R Us from Toys R Us.
layout: jsonld
name: Toys R Us Context
namespaces:
- prefix: toys-r-us
  uri: https://api-evangelist.com/context/toys-r-us/
- prefix: lb
  uri: https://api-evangelist.com/context/logicbroker/
properties: []
property_count: 0
provider_name: Toys R Us
provider_slug: toys-r-us
slug: toys-r-us-context
source_filename: toys-r-us-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"toys-r-us\": \"https://api-evangelist.com/context/toys-r-us/\",\n    \"lb\": \"https://api-evangelist.com/context/logicbroker/\",\n    \"Order\": \"schema:Order\",\n    \"key\": \"lb:documentKey\",\n    \"PartnerPO\": \"schema:orderNumber\",\n    \"OrderDate\": \"schema:orderDate\",\n    \"Status\": \"lb:documentStatus\",\n    \"ShipToAddress\": \"schema:deliveryAddress\",\n    \"Name\": \"schema:name\",\n    \"Address1\": \"schema:streetAddress\",\n    \"Address2\": \"lb:streetAddressLine2\",\n    \"City\": \"schema:addressLocality\",\n    \"State\": \"schema:addressRegion\",\n    \"Zip\": \"schema:postalCode\",\n    \"Country\": \"schema:addressCountry\",\n    \"LineItems\": \"schema:orderedItem\",\n    \"LineNumber\": \"lb:lineNumber\",\n    \"SupplierSKU\": \"toys-r-us:supplierSKU\",\n    \"BuyerSKU\": \"toys-r-us:buyerSKU\",\n    \"UPC\": \"schema:gtin12\",\n    \"Description\": \"schema:description\"\
  ,\n    \"Quantity\": \"schema:orderQuantity\",\n    \"UnitPrice\": \"schema:price\",\n    \"UOM\": \"lb:unitOfMeasure\",\n    \"Shipment\": \"schema:ParcelDelivery\",\n    \"TrackingNumber\": \"schema:trackingNumber\",\n    \"Carrier\": \"schema:hasDeliveryMethod\",\n    \"ShipDate\": \"schema:expectedArrivalFrom\",\n    \"Package\": \"lb:package\",\n    \"Weight\": \"schema:weight\",\n    \"Invoice\": \"schema:Invoice\",\n    \"InvoiceNumber\": \"schema:confirmationNumber\",\n    \"InvoiceDate\": \"schema:dateIssued\",\n    \"Product\": \"schema:Product\",\n    \"MSRP\": \"schema:suggestedRetailPrice\",\n    \"InStock\": \"schema:itemAvailability\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/toys-r-us/refs/heads/main/json-ld/toys-r-us-context.jsonld
tags:
- Commerce
- Dropship
- E-Commerce
- Retail
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
