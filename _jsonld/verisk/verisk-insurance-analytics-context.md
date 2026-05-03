---
api_specs:
- filename: verisk-insurance-analytics-openapi.yml
  format: yaml
  label: Verisk Insurance Analytics API
  slug: insurance-analytics
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/openapi/verisk-insurance-analytics-openapi.yml
class_count: 13
classes:
- Address
- Verisk Property Risk Assessment
- PerilScoreRequest
- AddressLookupRequest
- Coordinates
- PropertyRisk
- FireProtectionClass
- ConstructionData
- PerilScoreResponse
- RiskScoreRequest
- ClaimsBenchmarks
- PropertyLookupResponse
- RiskScoreResponse
context_file: json-ld/verisk-insurance-analytics-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-ld/verisk-insurance-analytics-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Verisk Insurance Analytics from Verisk.
layout: jsonld
name: Verisk Insurance Analytics Context
namespaces:
- prefix: verisk
  uri: https://verisk.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: street
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: zipCode
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: propertyId
  type: string
- container: ''
  name: perilScores
  type: reference
- container: ''
  name: lastUpdated
  type: date
- container: set
  name: locations
  type: reference
- container: ''
  name: locationId
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: set
  name: perils
  type: string
- container: ''
  name: streetAddress
  type: string
- container: ''
  name: includeRiskData
  type: boolean
- container: set
  name: includePerils
  type: string
- container: ''
  name: ppcGrade
  type: integer
- container: ''
  name: splitCode
  type: string
- container: ''
  name: fireDistrictName
  type: string
- container: ''
  name: distanceToFireStation
  type: decimal
- container: ''
  name: distanceToHydrant
  type: decimal
- container: ''
  name: communityName
  type: string
- container: ''
  name: lastSurveyDate
  type: date
- container: ''
  name: yearBuilt
  type: integer
- container: ''
  name: squareFootage
  type: integer
- container: ''
  name: stories
  type: integer
- container: ''
  name: constructionType
  type: string
- container: ''
  name: roofType
  type: string
- container: ''
  name: occupancyType
  type: string
- container: ''
  name: buildingCode
  type: string
- container: set
  name: scoreTypes
  type: string
- container: ''
  name: lineOfBusiness
  type: string
- container: ''
  name: year
  type: integer
- container: ''
  name: metrics
  type: reference
- container: ''
  name: frequency
  type: decimal
- container: ''
  name: averageSeverity
  type: decimal
- container: ''
  name: lossRatio
  type: decimal
- container: ''
  name: combinedRatio
  type: decimal
- container: ''
  name: sampleSize
  type: integer
- container: ''
  name: source
  type: string
- container: ''
  name: matchQuality
  type: string
- container: ''
  name: scores
  type: reference
property_count: 42
provider_name: Verisk
provider_slug: verisk
slug: verisk-insurance-analytics-context
source_filename: verisk-insurance-analytics-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"verisk\": \"https://verisk.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Address\": \"verisk:Address\",\n    \"Verisk Property Risk Assessment\": \"verisk:Verisk Property Risk Assessment\",\n    \"PerilScoreRequest\": \"verisk:PerilScoreRequest\",\n    \"AddressLookupRequest\": \"verisk:AddressLookupRequest\",\n    \"Coordinates\": \"verisk:Coordinates\",\n    \"PropertyRisk\": \"verisk:PropertyRisk\",\n    \"FireProtectionClass\": \"verisk:FireProtectionClass\",\n    \"ConstructionData\": \"verisk:ConstructionData\",\n    \"PerilScoreResponse\": \"verisk:PerilScoreResponse\",\n    \"RiskScoreRequest\": \"verisk:RiskScoreRequest\",\n    \"ClaimsBenchmarks\": \"verisk:ClaimsBenchmarks\",\n    \"PropertyLookupResponse\": \"verisk:PropertyLookupResponse\",\n    \"RiskScoreResponse\": \"verisk:RiskScoreResponse\"\
  ,\n    \"street\": {\n      \"@id\": \"verisk:street\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"verisk:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"verisk:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zipCode\": {\n      \"@id\": \"verisk:zipCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"verisk:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyId\": {\n      \"@id\": \"verisk:propertyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"perilScores\": {\n      \"@id\": \"verisk:perilScores\",\n      \"@type\": \"@id\"\n    },\n    \"lastUpdated\": {\n      \"@id\": \"verisk:lastUpdated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"locations\": {\n      \"@id\": \"verisk:locations\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"locationId\": {\n      \"@id\": \"verisk:locationId\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"latitude\": {\n      \"@id\": \"verisk:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"verisk:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"perils\": {\n      \"@id\": \"verisk:perils\",\n      \"@type\": \"xsd:string\",\n      \"@container\": \"@set\"\n    },\n    \"streetAddress\": {\n      \"@id\": \"verisk:streetAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"includeRiskData\": {\n      \"@id\": \"verisk:includeRiskData\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"includePerils\": {\n      \"@id\": \"verisk:includePerils\",\n      \"@type\": \"xsd:string\",\n      \"@container\": \"@set\"\n    },\n    \"ppcGrade\": {\n      \"@id\": \"verisk:ppcGrade\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"splitCode\": {\n      \"@id\": \"verisk:splitCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fireDistrictName\": {\n      \"@id\": \"verisk:fireDistrictName\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"distanceToFireStation\": {\n      \"@id\": \"verisk:distanceToFireStation\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"distanceToHydrant\": {\n      \"@id\": \"verisk:distanceToHydrant\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"communityName\": {\n      \"@id\": \"verisk:communityName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastSurveyDate\": {\n      \"@id\": \"verisk:lastSurveyDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"yearBuilt\": {\n      \"@id\": \"verisk:yearBuilt\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"squareFootage\": {\n      \"@id\": \"verisk:squareFootage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stories\": {\n      \"@id\": \"verisk:stories\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"constructionType\": {\n      \"@id\": \"verisk:constructionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roofType\": {\n      \"@id\": \"verisk:roofType\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"occupancyType\": {\n      \"@id\": \"verisk:occupancyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buildingCode\": {\n      \"@id\": \"verisk:buildingCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scoreTypes\": {\n      \"@id\": \"verisk:scoreTypes\",\n      \"@type\": \"xsd:string\",\n      \"@container\": \"@set\"\n    },\n    \"lineOfBusiness\": {\n      \"@id\": \"verisk:lineOfBusiness\",\n      \"@type\": \"xsd:string\"\n    },\n    \"year\": {\n      \"@id\": \"verisk:year\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"metrics\": {\n      \"@id\": \"verisk:metrics\",\n      \"@type\": \"@id\"\n    },\n    \"frequency\": {\n      \"@id\": \"verisk:frequency\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"averageSeverity\": {\n      \"@id\": \"verisk:averageSeverity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"lossRatio\": {\n      \"@id\": \"verisk:lossRatio\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"combinedRatio\": {\n \
  \     \"@id\": \"verisk:combinedRatio\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"sampleSize\": {\n      \"@id\": \"verisk:sampleSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"source\": {\n      \"@id\": \"verisk:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"matchQuality\": {\n      \"@id\": \"verisk:matchQuality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scores\": {\n      \"@id\": \"verisk:scores\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-ld/verisk-insurance-analytics-context.jsonld
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
