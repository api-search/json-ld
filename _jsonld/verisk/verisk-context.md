---
api_specs:
- filename: verisk-insurance-analytics-openapi.yml
  format: yaml
  label: Verisk Insurance Analytics API
  slug: insurance-analytics
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/openapi/verisk-insurance-analytics-openapi.yml
class_count: 27
classes:
- PropertyRisk
- FireProtectionClass
- PerilScore
- ConstructionData
- ClaimsBenchmarks
- propertyId
- coordinates
- street
- city
- state
- zipCode
- country
- squareFootage
- stories
- constructionType
- occupancyType
- ppcGrade
- fireDistrictName
- distanceToFireStation
- distanceToHydrant
- score
- riskCategory
- annualExceedanceProbability
- lineOfBusiness
- frequency
- averageSeverity
- lossRatio
context_file: json-ld/verisk-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-ld/verisk-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Verisk from Verisk.
layout: jsonld
name: Verisk Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: verisk
  uri: https://www.verisk.com/vocab/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: address
  type: schema:PostalAddress
- container: ''
  name: lastUpdated
  type: date
- container: ''
  name: latitude
  type: double
- container: ''
  name: longitude
  type: double
- container: ''
  name: yearBuilt
  type: integer
property_count: 5
provider_name: Verisk
provider_slug: verisk
slug: verisk-context
source_filename: verisk-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"verisk\": \"https://www.verisk.com/vocab/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"PropertyRisk\": \"schema:Place\",\n    \"FireProtectionClass\": \"verisk:FireProtectionClass\",\n    \"PerilScore\": \"verisk:PerilScore\",\n    \"ConstructionData\": \"schema:Accommodation\",\n    \"ClaimsBenchmarks\": \"verisk:ClaimsBenchmarks\",\n\n    \"propertyId\": \"schema:identifier\",\n    \"address\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n    \"coordinates\": \"schema:geo\",\n    \"lastUpdated\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"street\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"zipCode\": \"schema:postalCode\",\n    \"country\"\
  : \"schema:addressCountry\",\n\n    \"latitude\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:double\"\n    },\n    \"longitude\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:double\"\n    },\n\n    \"yearBuilt\": {\n      \"@id\": \"schema:yearBuilt\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"squareFootage\": \"schema:floorSize\",\n    \"stories\": \"schema:numberOfFloors\",\n    \"constructionType\": \"schema:material\",\n    \"occupancyType\": \"schema:additionalType\",\n\n    \"ppcGrade\": \"verisk:ppcGrade\",\n    \"fireDistrictName\": \"schema:name\",\n    \"distanceToFireStation\": \"verisk:distanceToFireStation\",\n    \"distanceToHydrant\": \"verisk:distanceToHydrant\",\n\n    \"score\": \"verisk:riskScore\",\n    \"riskCategory\": \"verisk:riskCategory\",\n    \"annualExceedanceProbability\": \"verisk:exceedanceProbability\",\n\n    \"lineOfBusiness\": \"verisk:lineOfBusiness\",\n    \"frequency\": \"verisk:claimFrequency\",\n    \"averageSeverity\"\
  : \"verisk:averageClaimSeverity\",\n    \"lossRatio\": \"verisk:lossRatio\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-ld/verisk-context.jsonld
tags:
- Insurance
- Analytics
- Risk Management
- Property Data
- Catastrophe Modeling
- Underwriting
- Claims
- JSON-LD
- Linked Data
- Semantic Web
---
