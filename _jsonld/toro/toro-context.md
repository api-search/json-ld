---
api_specs:
- filename: toro-horizon360-openapi.yml
  format: yaml
  label: Toro Horizon360
  slug: horizon360
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toro/refs/heads/main/openapi/toro-horizon360-openapi.yml
- filename: toro-intellidash-openapi.yml
  format: yaml
  label: Toro IntelliDash
  slug: intellidash
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toro/refs/heads/main/openapi/toro-intellidash-openapi.yml
class_count: 55
classes:
- Customer
- id
- name
- email
- phone
- address
- street
- city
- state
- zip
- country
- createdAt
- updatedAt
- notes
- Job
- customerId
- title
- description
- status
- jobType
- serviceAddress
- estimatedHours
- actualHours
- scheduledDate
- completedDate
- crewId
- Invoice
- invoiceNumber
- lineItems
- subtotal
- tax
- total
- dueDate
- Equipment
- brand
- model
- serialNumber
- purchaseDate
- hoursUsed
- IrrigationZone
- zoneId
- soilMoisture
- flowRateGpm
- lastWateredAt
- nextScheduledAt
- SensorReading
- value
- unit
- timestamp
- Payment
- amount
- currency
- paymentMethod
- transactionId
- processedAt
context_file: json-ld/toro-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/toro/refs/heads/main/json-ld/toro-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Toro from Toro.
layout: jsonld
name: Toro Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: toro
  uri: https://api.horizon360.toro.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: Toro
provider_slug: toro
slug: toro-context
source_filename: toro-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"toro\": \"https://api.horizon360.toro.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Customer\": \"schema:Person\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"address\": \"schema:address\",\n    \"street\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"zip\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\",\n    \"notes\": \"schema:description\",\n\n    \"Job\": \"schema:Action\",\n    \"customerId\": \"schema:agent\",\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"toro:jobStatus\",\n    \"jobType\": \"toro:serviceType\",\n    \"serviceAddress\"\
  : \"schema:location\",\n    \"estimatedHours\": \"toro:estimatedDuration\",\n    \"actualHours\": \"toro:actualDuration\",\n    \"scheduledDate\": \"schema:scheduledTime\",\n    \"completedDate\": \"schema:endTime\",\n    \"crewId\": \"toro:assignedCrew\",\n\n    \"Invoice\": \"schema:Invoice\",\n    \"invoiceNumber\": \"schema:confirmationNumber\",\n    \"lineItems\": \"schema:itemListElement\",\n    \"subtotal\": \"schema:price\",\n    \"tax\": \"toro:taxAmount\",\n    \"total\": \"schema:totalPrice\",\n    \"dueDate\": \"toro:paymentDueDate\",\n\n    \"Equipment\": \"schema:Product\",\n    \"brand\": \"schema:brand\",\n    \"model\": \"schema:model\",\n    \"serialNumber\": \"schema:serialNumber\",\n    \"purchaseDate\": \"schema:purchaseDate\",\n    \"hoursUsed\": \"toro:equipmentHours\",\n\n    \"IrrigationZone\": \"toro:IrrigationZone\",\n    \"zoneId\": \"@id\",\n    \"soilMoisture\": \"toro:soilMoisture\",\n    \"flowRateGpm\": \"toro:flowRate\",\n    \"lastWateredAt\": \"toro:lastIrrigated\"\
  ,\n    \"nextScheduledAt\": \"toro:nextIrrigationSchedule\",\n\n    \"SensorReading\": \"schema:Observation\",\n    \"value\": \"schema:value\",\n    \"unit\": \"schema:unitText\",\n    \"timestamp\": \"schema:dateObserved\",\n\n    \"Payment\": \"schema:PayAction\",\n    \"amount\": \"schema:totalPaymentDue\",\n    \"currency\": \"schema:currency\",\n    \"paymentMethod\": \"schema:paymentMethod\",\n    \"transactionId\": \"schema:identifier\",\n    \"processedAt\": \"schema:endTime\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/toro/refs/heads/main/json-ld/toro-context.jsonld
tags:
- Landscaping
- Irrigation
- Golf
- Equipment
- Smart Connected Products
- Fleet Management
- Turf Management
- JSON-LD
- Linked Data
- Semantic Web
---
