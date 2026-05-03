---
api_specs:
- filename: fred-openapi.yml
  format: yaml
  label: FRED API - Reserve Data
  slug: fred-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/openapi/fred-openapi.yml
class_count: 11
classes:
- seasonal_adjustment
- popularity
- realtime_start
- realtime_end
- ReserveRequirements
- RegulationD
- reserveRequirementRatio
- exemptionAmount
- lowReserveTranche
- monetaryBase
- reserveBalance
context_file: json-ld/reserve-requirements-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/json-ld/reserve-requirements-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Reserve Requirements from Reserve Requirements.
layout: jsonld
name: Reserve Requirements Context
namespaces:
- prefix: fed
  uri: https://www.federalreserve.gov/vocab/
- prefix: fred
  uri: https://fred.stlouisfed.org/vocab/
- prefix: Dataset
  uri: https://schema.org/Dataset
- prefix: GovernmentOrganization
  uri: https://schema.org/GovernmentOrganization
- prefix: id
  uri: https://schema.org/identifier
- prefix: title
  uri: https://schema.org/name
- prefix: description
  uri: https://schema.org/description
- prefix: url
  uri: https://schema.org/url
- prefix: observation_start
  uri: https://schema.org/temporalCoverage
- prefix: observation_end
  uri: https://schema.org/temporalCoverage
- prefix: frequency
  uri: https://schema.org/frequency
- prefix: units
  uri: https://schema.org/unitText
- prefix: last_updated
  uri: https://schema.org/dateModified
- prefix: notes
  uri: https://schema.org/description
- prefix: Observation
  uri: https://schema.org/Observation
- prefix: date
  uri: https://schema.org/observationDate
- prefix: value
  uri: https://schema.org/value
- prefix: depositoryInstitution
  uri: https://schema.org/FinancialService
properties: []
property_count: 0
provider_name: Reserve Requirements
provider_slug: reserve-requirements
slug: reserve-requirements-context
source_filename: reserve-requirements-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"fed\": \"https://www.federalreserve.gov/vocab/\",\n    \"fred\": \"https://fred.stlouisfed.org/vocab/\",\n    \"Dataset\": \"https://schema.org/Dataset\",\n    \"GovernmentOrganization\": \"https://schema.org/GovernmentOrganization\",\n    \"id\": \"https://schema.org/identifier\",\n    \"title\": \"https://schema.org/name\",\n    \"description\": \"https://schema.org/description\",\n    \"url\": \"https://schema.org/url\",\n    \"observation_start\": \"https://schema.org/temporalCoverage\",\n    \"observation_end\": \"https://schema.org/temporalCoverage\",\n    \"frequency\": \"https://schema.org/frequency\",\n    \"units\": \"https://schema.org/unitText\",\n    \"seasonal_adjustment\": \"fred:seasonalAdjustment\",\n    \"last_updated\": \"https://schema.org/dateModified\",\n    \"popularity\": \"fred:popularity\",\n    \"notes\": \"https://schema.org/description\",\n    \"Observation\": \"https://schema.org/Observation\"\
  ,\n    \"date\": \"https://schema.org/observationDate\",\n    \"value\": \"https://schema.org/value\",\n    \"realtime_start\": \"fred:realtimeStart\",\n    \"realtime_end\": \"fred:realtimeEnd\",\n    \"ReserveRequirements\": \"fed:ReserveRequirements\",\n    \"RegulationD\": \"fed:RegulationD\",\n    \"reserveRequirementRatio\": \"fed:reserveRequirementRatio\",\n    \"exemptionAmount\": \"fed:exemptionAmount\",\n    \"lowReserveTranche\": \"fed:lowReserveTranche\",\n    \"depositoryInstitution\": \"https://schema.org/FinancialService\",\n    \"monetaryBase\": \"fed:monetaryBase\",\n    \"reserveBalance\": \"fed:reserveBalance\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/json-ld/reserve-requirements-context.jsonld
tags:
- Reserve Requirements
- Federal Reserve
- Banking Regulation
- Monetary Policy
- Regulation D
- Finance
- JSON-LD
- Linked Data
- Semantic Web
---
