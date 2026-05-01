---
api_specs:
- filename: nhtsa-vpic-api-openapi.yml
  format: yaml
  label: NHTSA vPIC API
  slug: nhtsa-vpic-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/department-of-transportation/refs/heads/main/openapi/nhtsa-vpic-api-openapi.yml
- filename: nhtsa-recalls-api-openapi.yml
  format: yaml
  label: NHTSA Vehicle Safety API
  slug: nhtsa-recalls-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/department-of-transportation/refs/heads/main/openapi/nhtsa-recalls-api-openapi.yml
- filename: fmcsa-qcmobile-api-openapi.yml
  format: yaml
  label: FMCSA QCMobile API
  slug: fmcsa-qcmobile-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/department-of-transportation/refs/heads/main/openapi/fmcsa-qcmobile-api-openapi.yml
- filename: faa-system-status-api-openapi.yml
  format: yaml
  label: FAA Airport Status API
  slug: faa-airport-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/department-of-transportation/refs/heads/main/openapi/faa-system-status-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/dot-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/department-of-transportation/refs/heads/main/json-ld/dot-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dot from Department of Transportation.
layout: jsonld
name: Dot Context
namespaces:
- prefix: dot
  uri: https://api-evangelist.com/department-of-transportation/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Vehicle
  type: ''
- container: ''
  name: Recall
  type: ''
- container: ''
  name: Carrier
  type: ''
- container: ''
  name: Airport
  type: ''
property_count: 4
provider_name: Department of Transportation
provider_slug: department-of-transportation
slug: dot-context
source_filename: dot-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dot\": \"https://api-evangelist.com/department-of-transportation/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Vehicle\": {\n      \"@id\": \"schema:Vehicle\",\n      \"@context\": {\n        \"VIN\": { \"@id\": \"schema:vehicleIdentificationNumber\" },\n        \"Make\": \"schema:brand\",\n        \"Model\": \"schema:model\",\n        \"ModelYear\": { \"@id\": \"schema:modelDate\", \"@type\": \"xsd:gYear\" },\n        \"FuelTypePrimary\": \"schema:fuelType\",\n        \"DriveType\": \"schema:driveWheelConfiguration\",\n        \"BodyClass\": \"schema:bodyType\",\n        \"Manufacturer\": \"schema:manufacturer\"\n      }\n    },\n    \"Recall\": {\n      \"@id\": \"dot:Recall\",\n      \"@context\": {\n        \"NHTSACampaignNumber\": \"schema:identifier\",\n        \"Manufacturer\": \"schema:manufacturer\"\
  ,\n        \"Summary\": \"schema:description\",\n        \"ReportReceivedDate\": { \"@id\": \"dcterms:date\", \"@type\": \"xsd:date\" },\n        \"ModelYear\": { \"@id\": \"schema:modelDate\", \"@type\": \"xsd:gYear\" }\n      }\n    },\n    \"Carrier\": {\n      \"@id\": \"dot:MotorCarrier\",\n      \"@context\": {\n        \"dotNumber\": \"schema:identifier\",\n        \"legalName\": \"schema:legalName\",\n        \"dbaName\": \"schema:alternateName\",\n        \"telephone\": \"schema:telephone\"\n      }\n    },\n    \"Airport\": {\n      \"@id\": \"schema:Airport\",\n      \"@context\": {\n        \"IATA\": \"schema:iataCode\",\n        \"Name\": \"schema:name\",\n        \"State\": \"schema:addressRegion\",\n        \"City\": \"schema:addressLocality\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/department-of-transportation/refs/heads/main/json-ld/dot-context.jsonld
tags:
- Federal Government
- Transportation
- Vehicles
- Aviation
- Motor Carriers
- JSON-LD
- Linked Data
- Semantic Web
---
