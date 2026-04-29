---
class_count: 4
classes:
- ToxProfile
- MinimumRiskLevel
- ExposureInvestigation
- SubstancePriority
context_file: json-ld/agency-for-toxic-substances-and-disease-registry-atsdr-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/json-ld/agency-for-toxic-substances-and-disease-registry-atsdr-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Agency For Toxic Substances And Disease Registry Atsdr from Agency for Toxic Substances and Disease Registry.
layout: jsonld
name: Agency For Toxic Substances And Disease Registry Atsdr Context
namespaces:
- prefix: agency-for-toxic-substances-and-disease-registry
  uri: https://agency-for-toxic-substances-and-disease-registry.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: substanceName
  type: string
- container: ''
  name: casNumber
  type: string
- container: ''
  name: profileYear
  type: integer
- container: ''
  name: substancePriorityListRank
  type: integer
- container: ''
  name: healthEffects
  type: string
- container: ''
  name: primaryRouteOfExposure
  type: string
- container: ''
  name: profileUrl
  type: string
- container: ''
  name: route
  type: string
- container: ''
  name: duration
  type: string
- container: ''
  name: mrlValue
  type: decimal
- container: ''
  name: mrlUnit
  type: string
- container: ''
  name: yearUpdated
  type: integer
- container: ''
  name: siteName
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: county
  type: string
- container: ''
  name: year
  type: integer
- container: ''
  name: investigationType
  type: string
- container: ''
  name: primaryContaminant
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: rank
  type: integer
- container: ''
  name: totalScore
  type: decimal
- container: ''
  name: nplFrequency
  type: integer
- container: ''
  name: toxicityScore
  type: decimal
property_count: 23
provider_name: Agency for Toxic Substances and Disease Registry
provider_slug: agency-for-toxic-substances-and-disease-registry
slug: agency-for-toxic-substances-and-disease-registry-atsdr-context
source_filename: agency-for-toxic-substances-and-disease-registry-atsdr-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"agency-for-toxic-substances-and-disease-registry\": \"https://agency-for-toxic-substances-and-disease-registry.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ToxProfile\": \"agency-for-toxic-substances-and-disease-registry:ToxProfile\",\n    \"substanceName\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:substance_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"casNumber\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:cas_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profileYear\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:profile_year\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"substancePriorityListRank\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:substance_priority_list_rank\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"healthEffects\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:health_effects\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primaryRouteOfExposure\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:primary_route_of_exposure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profileUrl\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:profile_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MinimumRiskLevel\": \"agency-for-toxic-substances-and-disease-registry:MinimumRiskLevel\",\n    \"route\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:route\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mrlValue\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:mrl_value\",\n      \"@type\"\
  : \"xsd:decimal\"\n    },\n    \"mrlUnit\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:mrl_unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"yearUpdated\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:year_updated\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ExposureInvestigation\": \"agency-for-toxic-substances-and-disease-registry:ExposureInvestigation\",\n    \"siteName\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:site_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"county\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:county\",\n      \"@type\": \"xsd:string\"\n    },\n    \"year\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:year\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"investigationType\": {\n\
  \      \"@id\": \"agency-for-toxic-substances-and-disease-registry:investigation_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primaryContaminant\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:primary_contaminant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubstancePriority\": \"agency-for-toxic-substances-and-disease-registry:SubstancePriority\",\n    \"rank\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:rank\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalScore\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:total_score\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"nplFrequency\": {\n      \"@id\": \"agency-for-toxic-substances-and-disease-registry:npl_frequency\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"toxicityScore\": {\n      \"@id\"\
  : \"agency-for-toxic-substances-and-disease-registry:toxicity_score\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/json-ld/agency-for-toxic-substances-and-disease-registry-atsdr-context.jsonld
tags:
- Diseases
- Federal Government
- Public Health
- Toxic Substances
- Environmental Health
- Hazardous Materials
- JSON-LD
- Linked Data
- Semantic Web
---
