---
class_count: 24
classes:
- GovernmentOrganization
- ResearchProject
- ResearchOrganization
- GovernmentService
- Report
- id
- title
- description
- category
- reportPeriod
- objectives
- leadAgency
- partnerAgencies
- geographicScope
- relevantLegislation
- ArcticResearchPriority
- ArcticResearchObjective
- ArcticRegion
- IndigenousKnowledge
- ClimateResearch
- MarineEcosystem
- PolarScience
- ArcticCommunity
- CriticalMinerals
context_file: json-ld/us-arctic-research-commission-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-arctic-research-commission/refs/heads/main/json-ld/us-arctic-research-commission-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Arctic Research Commission from US Arctic Research Commission.
layout: jsonld
name: Us Arctic Research Commission Context
namespaces:
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: usarc
  uri: https://www.arctic.gov/vocab/
properties:
- container: ''
  name: created
  type: date
- container: ''
  name: modified
  type: date
- container: ''
  name: USARC
  type: GovernmentOrganization
- container: ''
  name: IARPC
  type: GovernmentOrganization
property_count: 4
provider_name: US Arctic Research Commission
provider_slug: us-arctic-research-commission
slug: us-arctic-research-commission-context
source_filename: us-arctic-research-commission-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"usarc\": \"https://www.arctic.gov/vocab/\",\n\n    \"GovernmentOrganization\": \"GovernmentOrganization\",\n    \"ResearchProject\": \"ResearchProject\",\n    \"ResearchOrganization\": \"ResearchOrganization\",\n    \"GovernmentService\": \"GovernmentService\",\n    \"Report\": \"Report\",\n\n    \"id\": \"@id\",\n    \"title\": \"dct:title\",\n    \"description\": \"dct:description\",\n    \"category\": \"dct:subject\",\n    \"reportPeriod\": \"dct:temporal\",\n    \"created\": {\n      \"@id\": \"dct:created\",\n      \"@type\": \"xsd:date\"\n    },\n    \"modified\": {\n      \"@id\": \"dct:modified\",\n      \"@type\": \"xsd:date\"\n    },\n  \
  \  \"objectives\": \"usarc:objectives\",\n    \"leadAgency\": \"usarc:leadAgency\",\n    \"partnerAgencies\": \"usarc:partnerAgencies\",\n    \"geographicScope\": \"dct:spatial\",\n    \"relevantLegislation\": \"usarc:relevantLegislation\",\n\n    \"ArcticResearchPriority\": \"usarc:ArcticResearchPriority\",\n    \"ArcticResearchObjective\": \"usarc:ArcticResearchObjective\",\n    \"ArcticRegion\": \"usarc:ArcticRegion\",\n    \"IndigenousKnowledge\": \"usarc:IndigenousKnowledge\",\n    \"ClimateResearch\": \"usarc:ClimateResearch\",\n    \"MarineEcosystem\": \"usarc:MarineEcosystem\",\n    \"PolarScience\": \"usarc:PolarScience\",\n    \"ArcticCommunity\": \"usarc:ArcticCommunity\",\n    \"CriticalMinerals\": \"usarc:CriticalMinerals\",\n\n    \"USARC\": {\n      \"@id\": \"usarc:USARC\",\n      \"@type\": \"GovernmentOrganization\"\n    },\n    \"IARPC\": {\n      \"@id\": \"usarc:IARPC\",\n      \"@type\": \"GovernmentOrganization\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-arctic-research-commission/refs/heads/main/json-ld/us-arctic-research-commission-context.jsonld
tags:
- Arctic Research
- Federal Government
- Climate Change
- Research Policy
- Advisory Commission
- Arctic
- Environmental Science
- JSON-LD
- Linked Data
- Semantic Web
---
