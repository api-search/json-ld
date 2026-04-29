---
class_count: 0
classes: []
context_file: json-ld/carvana-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/carvana/refs/heads/main/json-ld/carvana-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Carvana from Carvana.
layout: jsonld
name: Carvana Context
namespaces:
- prefix: carvana
  uri: https://carvana.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Partner
  type: ''
- container: ''
  name: Vehicle
  type: ''
- container: ''
  name: InventoryItem
  type: ''
- container: ''
  name: Listing
  type: ''
- container: ''
  name: InspectionReport
  type: ''
- container: ''
  name: DeliveryOption
  type: ''
- container: ''
  name: VendingMachine
  type: ''
- container: ''
  name: FinancingOffer
  type: ''
- container: ''
  name: DataProduct
  type: ''
property_count: 9
provider_name: Carvana
provider_slug: carvana
slug: carvana-context
source_filename: carvana-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"carvana\": \"https://carvana.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Partner\": {\n      \"@id\": \"carvana:Partner\",\n      \"@context\": {\n        \"partnerId\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"partnerType\": \"carvana:partnerType\",\n        \"apiKeyId\": {\n          \"@id\": \"carvana:apiKeyId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Vehicle\": {\n      \"@id\": \"schema:Vehicle\",\n      \"@context\": {\n        \"vin\": {\n          \"@id\": \"schema:vehicleIdentificationNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"year\": {\n          \"@id\": \"schema:vehicleModelDate\",\n          \"@type\": \"xsd:gYear\"\n        },\n        \"make\": \"schema:brand\",\n        \"model\": \"schema:model\",\n        \"trim\": \"carvana:trim\",\n        \"\
  mileage\": {\n          \"@id\": \"schema:mileageFromOdometer\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"color\": \"schema:color\"\n      }\n    },\n\n    \"InventoryItem\": {\n      \"@id\": \"schema:Product\",\n      \"@context\": {\n        \"inventoryId\": \"schema:identifier\",\n        \"vehicle\": {\n          \"@id\": \"carvana:vehicle\",\n          \"@type\": \"@id\"\n        },\n        \"partner\": {\n          \"@id\": \"carvana:partner\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"carvana:inventoryStatus\",\n        \"postedAt\": {\n          \"@id\": \"schema:datePosted\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Listing\": {\n      \"@id\": \"schema:Offer\",\n      \"@context\": {\n        \"listingId\": \"schema:identifier\",\n        \"price\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": \"schema:priceCurrency\",\n        \"\
  availability\": \"schema:availability\",\n        \"itemOffered\": {\n          \"@id\": \"schema:itemOffered\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"InspectionReport\": {\n      \"@id\": \"carvana:InspectionReport\",\n      \"@context\": {\n        \"reportId\": \"schema:identifier\",\n        \"performedAt\": {\n          \"@id\": \"carvana:performedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"passed\": {\n          \"@id\": \"carvana:passed\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"findings\": \"schema:description\"\n      }\n    },\n\n    \"DeliveryOption\": {\n      \"@id\": \"carvana:DeliveryOption\",\n      \"@context\": {\n        \"deliveryType\": \"carvana:deliveryType\",\n        \"estimatedAvailable\": {\n          \"@id\": \"carvana:estimatedAvailable\",\n          \"@type\": \"xsd:date\"\n        },\n        \"vendingMachine\": {\n          \"@id\": \"carvana:vendingMachine\",\n          \"@type\"\
  : \"@id\"\n        }\n      }\n    },\n\n    \"VendingMachine\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"vendingMachineId\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"address\": \"schema:address\",\n        \"geo\": \"schema:geo\"\n      }\n    },\n\n    \"FinancingOffer\": {\n      \"@id\": \"schema:LoanOrCredit\",\n      \"@context\": {\n        \"offerId\": \"schema:identifier\",\n        \"apr\": {\n          \"@id\": \"carvana:apr\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"termMonths\": {\n          \"@id\": \"schema:loanTerm\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"monthlyPayment\": {\n          \"@id\": \"carvana:monthlyPayment\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"DataProduct\": {\n      \"@id\": \"schema:Dataset\",\n      \"@context\": {\n        \"productId\": \"schema:identifier\",\n        \"marketplace\": \"schema:provider\",\n     \
  \   \"refreshCadence\": \"carvana:refreshCadence\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/carvana/refs/heads/main/json-ld/carvana-context.jsonld
tags:
- Automotive
- E-Commerce
- Used Cars
- Inventory
- Partner API
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
