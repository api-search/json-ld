---
class_count: 34
classes:
- EDITransaction
- PurchaseOrder
- Invoice
- ShipNotice
- Prescription
- PharmacyLocation
- HealthScreening
- transactionSetId
- transactionName
- ediVersion
- controlNumber
- senderId
- receiverId
- transactionStatus
- ndc
- rxNumber
- drugName
- prescriber
- dispenseDate
- daysSupply
- quantity
- storeNumber
- hasPharmacy
- screeningType
- name
- description
- url
- identifier
- address
- telephone
- dateCreated
- dateModified
- price
- priceCurrency
context_file: json-ld/rite-aid-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rite-aid/refs/heads/main/json-ld/rite-aid-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rite Aid from Rite Aid.
layout: jsonld
name: Rite Aid Context
namespaces:
- prefix: ra
  uri: https://riteaid.com/vocab#
- prefix: edi
  uri: https://riteaid.com/vocab/edi#
- prefix: pharmacy
  uri: https://riteaid.com/vocab/pharmacy#
properties: []
property_count: 0
provider_name: Rite Aid
provider_slug: rite-aid
slug: rite-aid-context
source_filename: rite-aid-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"ra\": \"https://riteaid.com/vocab#\",\n    \"edi\": \"https://riteaid.com/vocab/edi#\",\n    \"pharmacy\": \"https://riteaid.com/vocab/pharmacy#\",\n\n    \"EDITransaction\": \"edi:EDITransaction\",\n    \"PurchaseOrder\": \"edi:PurchaseOrder\",\n    \"Invoice\": \"edi:Invoice\",\n    \"ShipNotice\": \"edi:ShipNotice\",\n    \"Prescription\": \"pharmacy:Prescription\",\n    \"PharmacyLocation\": \"pharmacy:PharmacyLocation\",\n    \"HealthScreening\": \"ra:HealthScreening\",\n\n    \"transactionSetId\": \"edi:transactionSetId\",\n    \"transactionName\": \"edi:transactionName\",\n    \"ediVersion\": \"edi:version\",\n    \"controlNumber\": \"edi:controlNumber\",\n    \"senderId\": \"edi:senderId\",\n    \"receiverId\": \"edi:receiverId\",\n    \"transactionStatus\": \"edi:status\",\n\n    \"ndc\": \"pharmacy:ndc\",\n    \"rxNumber\": \"pharmacy:rxNumber\",\n    \"drugName\": \"pharmacy:drugName\",\n    \"\
  prescriber\": \"pharmacy:prescriber\",\n    \"dispenseDate\": \"pharmacy:dispenseDate\",\n    \"daysSupply\": \"pharmacy:daysSupply\",\n    \"quantity\": \"pharmacy:quantity\",\n\n    \"storeNumber\": \"ra:storeNumber\",\n    \"hasPharmacy\": \"ra:hasPharmacy\",\n    \"screeningType\": \"ra:screeningType\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"address\": \"schema:address\",\n    \"telephone\": \"schema:telephone\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"price\": \"schema:price\",\n    \"priceCurrency\": \"schema:priceCurrency\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rite-aid/refs/heads/main/json-ld/rite-aid-context.jsonld
tags:
- EDI
- Fortune 500
- Health
- Pharmacy
- Prescriptions
- Retail
- JSON-LD
- Linked Data
- Semantic Web
---
