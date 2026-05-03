---
class_count: 2
classes:
- GovernmentOrganization
- Dataset
context_file: json-ld/us-chemical-safety-and-hazard-investigation-board-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-chemical-safety-and-hazard-investigation-board/refs/heads/main/json-ld/us-chemical-safety-and-hazard-investigation-board-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Chemical Safety And Hazard Investigation Board from US Chemical Safety and Hazard Investigation Board.
layout: jsonld
name: Us Chemical Safety And Hazard Investigation Board Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: dcat
  uri: https://www.w3.org/ns/dcat#
- prefix: csb
  uri: https://www.csb.gov/
properties:
- container: ''
  name: ChemicalIncident
  type: reference
- container: ''
  name: Investigation
  type: reference
- container: ''
  name: SafetyRecommendation
  type: reference
- container: ''
  name: ChemicalFacility
  type: reference
- container: ''
  name: HazardousChemical
  type: reference
- container: ''
  name: incidentId
  type: string
- container: ''
  name: incidentDate
  type: date
- container: ''
  name: incidentTime
  type: time
- container: ''
  name: facilityName
  type: string
- container: ''
  name: facilityLocation
  type: reference
- container: ''
  name: facilityType
  type: string
- container: ''
  name: naicsCode
  type: string
- container: ''
  name: incidentType
  type: string
- container: set
  name: chemicalsInvolved
  type: ''
- container: ''
  name: chemicalName
  type: string
- container: ''
  name: casNumber
  type: string
- container: ''
  name: quantity
  type: decimal
- container: ''
  name: quantityUnit
  type: string
- container: ''
  name: hazardClass
  type: string
- container: ''
  name: fatalities
  type: integer
- container: ''
  name: injuries
  type: integer
- container: ''
  name: evacuated
  type: integer
- container: ''
  name: investigationStatus
  type: string
- container: ''
  name: investigationReport
  type: reference
- container: set
  name: recommendations
  type: ''
- container: ''
  name: recommendationNumber
  type: string
- container: ''
  name: recipientOrganization
  type: string
- container: set
  name: rootCauses
  type: ''
- container: set
  name: regulatoryNotifications
  type: ''
- container: ''
  name: issueDate
  type: date
- container: ''
  name: publisher
  type: reference
- container: ''
  name: description
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: modified
  type: date
property_count: 34
provider_name: US Chemical Safety and Hazard Investigation Board
provider_slug: us-chemical-safety-and-hazard-investigation-board
slug: us-chemical-safety-and-hazard-investigation-board-context
source_filename: us-chemical-safety-and-hazard-investigation-board-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"dcat\": \"https://www.w3.org/ns/dcat#\",\n    \"csb\": \"https://www.csb.gov/\",\n\n    \"ChemicalIncident\": {\n      \"@id\": \"schema:Event\",\n      \"@type\": \"@id\"\n    },\n    \"Investigation\": {\n      \"@id\": \"schema:Observation\",\n      \"@type\": \"@id\"\n    },\n    \"SafetyRecommendation\": {\n      \"@id\": \"schema:Action\",\n      \"@type\": \"@id\"\n    },\n    \"ChemicalFacility\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"@id\"\n    },\n    \"HazardousChemical\": {\n      \"@id\": \"schema:Drug\",\n      \"@type\": \"@id\"\n    },\n\n    \"incidentId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"\
  incidentTime\": {\n      \"@id\": \"schema:startTime\",\n      \"@type\": \"xsd:time\"\n    },\n    \"facilityName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"facilityLocation\": {\n      \"@id\": \"schema:location\",\n      \"@type\": \"@id\"\n    },\n    \"facilityType\": {\n      \"@id\": \"schema:additionalType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"naicsCode\": {\n      \"@id\": \"schema:naics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentType\": {\n      \"@id\": \"schema:additionalType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chemicalsInvolved\": {\n      \"@id\": \"csb:chemicalsInvolved\",\n      \"@container\": \"@set\"\n    },\n    \"chemicalName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"casNumber\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"schema:quantity\",\n      \"@type\": \"\
  xsd:decimal\"\n    },\n    \"quantityUnit\": {\n      \"@id\": \"schema:unitCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hazardClass\": {\n      \"@id\": \"schema:additionalType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fatalities\": {\n      \"@id\": \"csb:fatalities\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"injuries\": {\n      \"@id\": \"csb:injuries\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"evacuated\": {\n      \"@id\": \"csb:evacuated\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"investigationStatus\": {\n      \"@id\": \"csb:investigationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"investigationReport\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"recommendations\": {\n      \"@id\": \"csb:recommendations\",\n      \"@container\": \"@set\"\n    },\n    \"recommendationNumber\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recipientOrganization\":\
  \ {\n      \"@id\": \"schema:recipient\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rootCauses\": {\n      \"@id\": \"csb:rootCauses\",\n      \"@container\": \"@set\"\n    },\n    \"regulatoryNotifications\": {\n      \"@id\": \"csb:regulatoryNotifications\",\n      \"@container\": \"@set\"\n    },\n    \"issueDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"GovernmentOrganization\": \"schema:GovernmentOrganization\",\n    \"Dataset\": \"dcat:Dataset\",\n    \"publisher\": {\n      \"@id\": \"dct:publisher\",\n      \"@type\": \"@id\"\n    },\n    \"description\": {\n      \"@id\": \"dct:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"dct:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modified\": {\n      \"@id\": \"dct:modified\",\n      \"@type\": \"xsd:date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-chemical-safety-and-hazard-investigation-board/refs/heads/main/json-ld/us-chemical-safety-and-hazard-investigation-board-context.jsonld
tags:
- Federal Government
- Chemical Safety
- Incident Investigation
- Hazardous Materials
- Public Safety
- Environmental Safety
- JSON-LD
- Linked Data
- Semantic Web
---
