---
api_specs:
- filename: trustwell-foodlogiq-openapi.yml
  format: yaml
  label: Trustwell FoodLogiQ API
  slug: trustwell-foodlogiq-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trustwell/refs/heads/main/openapi/trustwell-foodlogiq-openapi.yml
class_count: 46
classes:
- FoodItem
- Supplier
- QualityIncident
- Recall
- NutritionLabel
- id
- name
- description
- email
- phone
- status
- servingSize
- servingUnit
- servingsPerContainer
- nutrients
- allergens
- ingredients
- labels
- nutrientId
- amount
- unit
- dailyValue
- allergenId
- containsStatus
- lotNumbers
- severity
- incidentType
- rootCause
- correctiveAction
- recallType
- recallClass
- distributionScope
- regulatoryNotification
- publicNotification
- certifications
- complianceStatus
- address
- street
- city
- state
- postalCode
- country
- regulations
- format
- imageUrl
- language
context_file: json-ld/trustwell-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trustwell/refs/heads/main/json-ld/trustwell-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trustwell from Trustwell.
layout: jsonld
name: Trustwell Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: gs1
  uri: https://www.gs1.org/voc/
- prefix: foodon
  uri: http://purl.obolibrary.org/obo/FOODON_
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: supplierId
  type: reference
- container: ''
  name: productId
  type: reference
- container: set
  name: productIds
  type: reference
- container: ''
  name: resolvedAt
  type: dateTime
property_count: 6
provider_name: Trustwell
provider_slug: trustwell
slug: trustwell-context
source_filename: trustwell-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"gs1\": \"https://www.gs1.org/voc/\",\n    \"foodon\": \"http://purl.obolibrary.org/obo/FOODON_\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"FoodItem\": \"schema:Product\",\n    \"Supplier\": \"schema:Organization\",\n    \"QualityIncident\": \"schema:Event\",\n    \"Recall\": \"schema:Event\",\n    \"NutritionLabel\": \"schema:NutritionInformation\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"status\": \"schema:status\",\n    \"createdAt\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"servingSize\": \"schema:servingSize\",\n    \"servingUnit\"\
  : \"schema:unitText\",\n    \"servingsPerContainer\": \"gs1:servingSize\",\n    \"nutrients\": \"schema:nutrition\",\n    \"allergens\": \"gs1:allergenRelatedInformation\",\n    \"ingredients\": \"schema:ingredients\",\n    \"labels\": \"schema:image\",\n\n    \"nutrientId\": \"@id\",\n    \"amount\": \"schema:value\",\n    \"unit\": \"schema:unitCode\",\n    \"dailyValue\": \"gs1:percentOfDailyValueIntakeReference\",\n\n    \"allergenId\": \"@id\",\n    \"containsStatus\": \"gs1:levelOfContainment\",\n\n    \"supplierId\": {\n      \"@id\": \"schema:supplier\",\n      \"@type\": \"@id\"\n    },\n    \"productId\": {\n      \"@id\": \"schema:productID\",\n      \"@type\": \"@id\"\n    },\n    \"productIds\": {\n      \"@id\": \"schema:productID\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"lotNumbers\": \"gs1:batchLotNumber\",\n\n    \"severity\": \"schema:importance\",\n    \"incidentType\": \"schema:additionalType\",\n    \"rootCause\": \"schema:description\"\
  ,\n    \"correctiveAction\": \"schema:potentialAction\",\n    \"resolvedAt\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"recallType\": \"schema:additionalType\",\n    \"recallClass\": \"schema:category\",\n    \"distributionScope\": \"schema:geographicArea\",\n    \"regulatoryNotification\": \"schema:isRelatedTo\",\n    \"publicNotification\": \"schema:isPartOf\",\n\n    \"certifications\": \"schema:hasCredential\",\n    \"complianceStatus\": \"schema:status\",\n    \"address\": \"schema:address\",\n    \"street\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"postalCode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n\n    \"regulations\": \"schema:legislationPassedBy\",\n    \"format\": \"schema:encodingFormat\",\n    \"imageUrl\": \"schema:url\",\n    \"language\": \"schema:inLanguage\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trustwell/refs/heads/main/json-ld/trustwell-context.jsonld
tags:
- Food Industry
- Food Safety
- Nutrition
- Supply Chain
- Food Labeling
- Traceability
- Compliance
- Food Technology
- JSON-LD
- Linked Data
- Semantic Web
---
