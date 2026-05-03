---
class_count: 8
classes:
- name
- description
- url
- identifier
- Organization
- AutoRepair
- Product
- SoftwareApplication
context_file: json-ld/snap-on-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/snap-on/refs/heads/main/json-ld/snap-on-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Snap On from Snap-on.
layout: jsonld
name: Snap On Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: snap
  uri: https://api-evangelist.github.io/snap-on/vocabulary/
properties:
- container: ''
  name: manufacturer
  type: reference
- container: ''
  name: product
  type: reference
- container: ''
  name: ElectronicPartsCatalog
  type: schema:SoftwareApplication
- container: ''
  name: DiagnosticTool
  type: schema:Product
- container: ''
  name: RepairInformationSystem
  type: schema:SoftwareApplication
- container: ''
  name: DealerManagementSystem
  type: schema:SoftwareApplication
- container: ''
  name: vehicleMake
  type: string
- container: ''
  name: vehicleModel
  type: string
- container: ''
  name: modelYear
  type: integer
- container: ''
  name: partNumber
  type: string
- container: ''
  name: repairOrderId
  type: string
- container: ''
  name: technicianId
  type: string
- container: ''
  name: faultCode
  type: string
- container: ''
  name: diagnosticCode
  type: string
- container: ''
  name: repairProcedure
  type: schema:HowTo
- container: ''
  name: technicalServiceBulletin
  type: schema:Article
- container: ''
  name: picklist
  type: reference
- container: ''
  name: picklistItem
  type: reference
- container: ''
  name: quantity
  type: integer
- container: ''
  name: unitPrice
  type: decimal
- container: ''
  name: availability
  type: reference
- container: ''
  name: realFix
  type: schema:HowTo
- container: ''
  name: vehicleIdentificationNumber
  type: string
- container: ''
  name: dmsProvider
  type: string
- container: ''
  name: integrationMethod
  type: string
- container: ''
  name: dealerCode
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 28
provider_name: Snap-on
provider_slug: snap-on
slug: snap-on-context
source_filename: snap-on-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"snap\": \"https://api-evangelist.github.io/snap-on/vocabulary/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"manufacturer\": {\n      \"@id\": \"schema:manufacturer\",\n      \"@type\": \"@id\"\n    },\n    \"product\": {\n      \"@id\": \"schema:Product\",\n      \"@type\": \"@id\"\n    },\n    \"Organization\": \"schema:Organization\",\n    \"AutoRepair\": \"schema:AutoRepair\",\n    \"Product\": \"schema:Product\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"ElectronicPartsCatalog\": {\n      \"@id\": \"snap:ElectronicPartsCatalog\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"DiagnosticTool\": {\n      \"@id\": \"snap:DiagnosticTool\",\n      \"@type\": \"schema:Product\"\
  \n    },\n    \"RepairInformationSystem\": {\n      \"@id\": \"snap:RepairInformationSystem\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"DealerManagementSystem\": {\n      \"@id\": \"snap:DealerManagementSystem\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"vehicleMake\": {\n      \"@id\": \"snap:vehicleMake\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vehicleModel\": {\n      \"@id\": \"snap:vehicleModel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modelYear\": {\n      \"@id\": \"snap:modelYear\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"partNumber\": {\n      \"@id\": \"snap:partNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repairOrderId\": {\n      \"@id\": \"snap:repairOrderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"technicianId\": {\n      \"@id\": \"snap:technicianId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"faultCode\": {\n      \"@id\": \"snap:faultCode\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"diagnosticCode\": {\n      \"@id\": \"snap:diagnosticCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repairProcedure\": {\n      \"@id\": \"snap:repairProcedure\",\n      \"@type\": \"schema:HowTo\"\n    },\n    \"technicalServiceBulletin\": {\n      \"@id\": \"snap:technicalServiceBulletin\",\n      \"@type\": \"schema:Article\"\n    },\n    \"picklist\": {\n      \"@id\": \"snap:picklist\",\n      \"@type\": \"@id\"\n    },\n    \"picklistItem\": {\n      \"@id\": \"snap:picklistItem\",\n      \"@type\": \"@id\"\n    },\n    \"quantity\": {\n      \"@id\": \"snap:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"unitPrice\": {\n      \"@id\": \"snap:unitPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"availability\": {\n      \"@id\": \"schema:availability\",\n      \"@type\": \"@id\"\n    },\n    \"realFix\": {\n      \"@id\": \"snap:realFix\",\n      \"@type\": \"schema:HowTo\"\n    },\n    \"vehicleIdentificationNumber\": {\n      \"@id\"\
  : \"snap:vehicleIdentificationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dmsProvider\": {\n      \"@id\": \"snap:dmsProvider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"integrationMethod\": {\n      \"@id\": \"snap:integrationMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dealerCode\": {\n      \"@id\": \"snap:dealerCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/snap-on/refs/heads/main/json-ld/snap-on-context.jsonld
tags:
- Automotive
- Diagnostics
- Electronic Parts Catalog
- Industrial Tools
- Manufacturing
- Repair Information
- Vehicle Repair
- JSON-LD
- Linked Data
- Semantic Web
---
