---
api_specs:
- filename: sam-gov-location-services-openapi.yml
  format: yaml
  label: SAM.gov Public Location Services API
  slug: location-services-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sam.gov/refs/heads/main/openapi/sam-gov-location-services-openapi.yml
class_count: 0
classes: []
context_file: json-ld/sam-gov-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sam.gov/refs/heads/main/json-ld/sam-gov-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sam Gov from SAM.gov.
layout: jsonld
name: Sam Gov Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: gov
  uri: https://schema.org/GovernmentOrganization
- prefix: sam
  uri: https://api-evangelist.github.io/sam.gov/vocab#
- prefix: dcat
  uri: http://www.w3.org/ns/dcat#
properties:
- container: ''
  name: ContractOpportunity
  type: ''
- container: ''
  name: City
  type: ''
- container: ''
  name: State
  type: ''
- container: ''
  name: Entity
  type: ''
- container: ''
  name: GovernmentAgency
  type: ''
property_count: 5
provider_name: SAM.gov
provider_slug: sam.gov
slug: sam-gov-context
source_filename: sam-gov-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"gov\": \"https://schema.org/GovernmentOrganization\",\n    \"sam\": \"https://api-evangelist.github.io/sam.gov/vocab#\",\n    \"dcat\": \"http://www.w3.org/ns/dcat#\",\n\n    \"ContractOpportunity\": {\n      \"@id\": \"schema:Offer\",\n      \"@context\": {\n        \"noticeId\": \"@id\",\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"schema:additionalType\",\n        \"solicitationNumber\": \"sam:solicitationNumber\",\n        \"naicsCode\": \"sam:naicsCode\",\n        \"classificationCode\": \"sam:classificationCode\",\n        \"department\": \"schema:provider\",\n        \"placeOfPerformance\": \"schema:areaServed\",\n        \"responseDeadLine\": {\n          \"@id\": \"schema:validThrough\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"active\":\
  \ \"schema:availability\",\n        \"uiLink\": \"schema:url\",\n        \"postedDate\": {\n          \"@id\": \"schema:datePosted\",\n          \"@type\": \"xsd:date\"\n        },\n        \"modifiedDate\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"City\": {\n      \"@id\": \"schema:City\",\n      \"@context\": {\n        \"cityCode\": \"@id\",\n        \"cityName\": \"schema:name\",\n        \"stateCode\": \"schema:addressRegion\",\n        \"stateName\": \"schema:addressRegion\",\n        \"countryCode\": \"schema:addressCountry\",\n        \"countryName\": \"schema:addressCountry\",\n        \"countyCode\": \"sam:countyCode\",\n        \"countyName\": \"sam:countyName\",\n        \"activeInd\": \"sam:activeIndicator\"\n      }\n    },\n\n    \"State\": {\n      \"@id\": \"schema:AdministrativeArea\",\n      \"@context\": {\n        \"stateCode\": \"@id\",\n        \"stateName\": \"schema:name\",\n        \"\
  countryCode\": \"schema:containedInPlace\",\n        \"activeInd\": \"sam:activeIndicator\"\n      }\n    },\n\n    \"Entity\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"ueiSAM\": \"@id\",\n        \"legalBusinessName\": \"schema:legalName\",\n        \"physicalAddress\": \"schema:address\",\n        \"registrationStatus\": \"sam:registrationStatus\",\n        \"expirationDate\": {\n          \"@id\": \"sam:registrationExpiration\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"GovernmentAgency\": {\n      \"@id\": \"schema:GovernmentOrganization\",\n      \"@context\": {\n        \"departmentId\": \"@id\",\n        \"departmentName\": \"schema:name\",\n        \"subTier\": \"sam:subTier\",\n        \"office\": \"sam:office\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sam.gov/refs/heads/main/json-ld/sam-gov-context.jsonld
tags:
- Federal Government
- Procurement
- Contracts
- Entity Management
- Location Services
- GSA
- JSON-LD
- Linked Data
- Semantic Web
---
