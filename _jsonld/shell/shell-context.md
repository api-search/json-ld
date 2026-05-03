---
api_specs:
- filename: shell-b2b-mobility-openapi.yml
  format: yaml
  label: Shell B2B Mobility Card Management API
  slug: b2b-mobility-card-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shell/refs/heads/main/openapi/shell-b2b-mobility-openapi.yml
- filename: shell-b2b-mobility-openapi.yml
  format: yaml
  label: Shell B2B Mobility Card Transaction Data API
  slug: b2b-mobility-card-transaction-data
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shell/refs/heads/main/openapi/shell-b2b-mobility-openapi.yml
- filename: shell-b2b-mobility-openapi.yml
  format: yaml
  label: Shell B2B Mobility Invoice API
  slug: b2b-mobility-invoice
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shell/refs/heads/main/openapi/shell-b2b-mobility-openapi.yml
- filename: shell-loyalty-openapi.yml
  format: yaml
  label: Shell Loyalty Catalogue API
  slug: loyalty-catalogue
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shell/refs/heads/main/openapi/shell-loyalty-openapi.yml
- filename: shell-loyalty-openapi.yml
  format: yaml
  label: Shell Loyalty Account Management API
  slug: loyalty-account-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shell/refs/heads/main/openapi/shell-loyalty-openapi.yml
- filename: shell-loyalty-openapi.yml
  format: yaml
  label: Shell Loyalty Points Balance API
  slug: loyalty-points-balance
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shell/refs/heads/main/openapi/shell-loyalty-openapi.yml
- filename: shell-loyalty-openapi.yml
  format: yaml
  label: Shell Loyalty Points Redemption API
  slug: loyalty-points-redemption
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shell/refs/heads/main/openapi/shell-loyalty-openapi.yml
- filename: shell-lubricants-openapi.yml
  format: yaml
  label: Shell Lubricants Order Management API
  slug: lubricants-order-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shell/refs/heads/main/openapi/shell-lubricants-openapi.yml
- filename: shell-b2b-mobility-openapi.yml
  format: yaml
  label: Shell B2B Mobility Sites API
  slug: b2b-mobility-sites
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shell/refs/heads/main/openapi/shell-b2b-mobility-openapi.yml
class_count: 42
classes:
- FuelCard
- FuelTransaction
- FuelSite
- Invoice
- LoyaltyAccount
- LoyaltyTransaction
- LubricantsOrder
- cardId
- cardPAN
- maskedPAN
- cardStatus
- expiryDate
- accountNumber
- payerNumber
- vehicleRegistration
- cardType
- colCoCode
- transactionId
- siteCode
- siteName
- productCode
- productName
- quantityUnit
- currency
- mileage
- siteId
- fuelTypes
- evCharging
- evChargingPoints
- amenities
- invoiceNumber
- status
- accountId
- totalPoints
- redeemablePoints
- pendingPoints
- tier
- rewardId
- pointsRequired
- availableCountries
- offerId
- bonusPoints
context_file: json-ld/shell-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/shell/refs/heads/main/json-ld/shell-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Shell from Shell.
layout: jsonld
name: Shell Context
namespaces:
- prefix: shell
  uri: https://api.shell.com/schema/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: driverName
  type: string
- container: ''
  name: date
  type: dateTime
- container: ''
  name: quantity
  type: float
- container: ''
  name: unitPrice
  type: float
- container: ''
  name: amount
  type: float
- container: ''
  name: address
  type: schema:PostalAddress
- container: ''
  name: location
  type: schema:GeoCoordinates
- container: ''
  name: latitude
  type: float
- container: ''
  name: longitude
  type: float
- container: ''
  name: invoiceDate
  type: date
- container: ''
  name: dueDate
  type: date
- container: ''
  name: totalAmount
  type: float
- container: ''
  name: validFrom
  type: dateTime
- container: ''
  name: validTo
  type: dateTime
property_count: 14
provider_name: Shell
provider_slug: shell
slug: shell-context
source_filename: shell-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"shell\": \"https://api.shell.com/schema/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"FuelCard\": \"shell:FuelCard\",\n    \"FuelTransaction\": \"shell:FuelTransaction\",\n    \"FuelSite\": \"schema:GasStation\",\n    \"Invoice\": \"schema:Invoice\",\n    \"LoyaltyAccount\": \"schema:LoyaltyProgram\",\n    \"LoyaltyTransaction\": \"shell:LoyaltyTransaction\",\n    \"LubricantsOrder\": \"schema:Order\",\n\n    \"cardId\": \"schema:identifier\",\n    \"cardPAN\": \"shell:cardPAN\",\n    \"maskedPAN\": \"shell:maskedPAN\",\n    \"cardStatus\": \"schema:status\",\n    \"expiryDate\": \"schema:expires\",\n    \"accountNumber\": \"schema:accountId\",\n    \"payerNumber\": \"shell:payerNumber\",\n    \"driverName\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"vehicleRegistration\": \"shell:vehicleRegistration\",\n    \"cardType\": \"schema:additionalType\",\n    \"colCoCode\"\
  : \"shell:collectingCompanyCode\",\n\n    \"transactionId\": \"schema:identifier\",\n    \"date\": { \"@id\": \"schema:startDate\", \"@type\": \"xsd:dateTime\" },\n    \"siteCode\": \"schema:identifier\",\n    \"siteName\": \"schema:name\",\n    \"productCode\": \"schema:productID\",\n    \"productName\": \"schema:name\",\n    \"quantity\": { \"@id\": \"schema:amount\", \"@type\": \"xsd:float\" },\n    \"quantityUnit\": \"schema:unitCode\",\n    \"unitPrice\": { \"@id\": \"schema:unitPrice\", \"@type\": \"xsd:float\" },\n    \"amount\": { \"@id\": \"schema:totalPrice\", \"@type\": \"xsd:float\" },\n    \"currency\": \"schema:priceCurrency\",\n    \"mileage\": \"shell:mileage\",\n\n    \"siteId\": \"schema:identifier\",\n    \"address\": { \"@id\": \"schema:address\", \"@type\": \"schema:PostalAddress\" },\n    \"location\": { \"@id\": \"schema:geo\", \"@type\": \"schema:GeoCoordinates\" },\n    \"latitude\": { \"@id\": \"schema:latitude\", \"@type\": \"xsd:float\" },\n    \"longitude\"\
  : { \"@id\": \"schema:longitude\", \"@type\": \"xsd:float\" },\n    \"fuelTypes\": \"shell:fuelTypes\",\n    \"evCharging\": \"shell:hasEVCharging\",\n    \"evChargingPoints\": \"shell:evChargingPoints\",\n    \"amenities\": \"schema:amenityFeature\",\n\n    \"invoiceNumber\": \"schema:identifier\",\n    \"invoiceDate\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:date\" },\n    \"dueDate\": { \"@id\": \"schema:paymentDueDate\", \"@type\": \"xsd:date\" },\n    \"totalAmount\": { \"@id\": \"schema:totalPrice\", \"@type\": \"xsd:float\" },\n    \"status\": \"schema:status\",\n\n    \"accountId\": \"schema:identifier\",\n    \"totalPoints\": \"shell:loyaltyPoints\",\n    \"redeemablePoints\": \"shell:redeemablePoints\",\n    \"pendingPoints\": \"shell:pendingPoints\",\n    \"tier\": \"schema:membershipLevel\",\n\n    \"rewardId\": \"schema:identifier\",\n    \"pointsRequired\": \"shell:pointsRequired\",\n    \"availableCountries\": \"schema:availableAtOrFrom\",\n\n    \"offerId\"\
  : \"schema:identifier\",\n    \"bonusPoints\": \"shell:bonusPoints\",\n    \"validFrom\": { \"@id\": \"schema:validFrom\", \"@type\": \"xsd:dateTime\" },\n    \"validTo\": { \"@id\": \"schema:validThrough\", \"@type\": \"xsd:dateTime\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/shell/refs/heads/main/json-ld/shell-context.jsonld
tags:
- Aviation
- Electric Vehicle Charging
- Energy
- Fleet Management
- Fuel
- Gas
- Loyalty
- Lubricants
- Mobility
- Oil and Gas
- Renewable Energy
- JSON-LD
- Linked Data
- Semantic Web
---
