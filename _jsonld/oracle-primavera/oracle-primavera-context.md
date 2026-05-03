---
api_specs:
- filename: oracle-primavera-p6-eppm-openapi.yml
  format: yaml
  label: Oracle Primavera P6 EPPM REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-primavera/refs/heads/main/openapi/oracle-primavera-p6-eppm-openapi.yml
class_count: 0
classes: []
context_file: json-ld/oracle-primavera-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-primavera/refs/heads/main/json-ld/oracle-primavera-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Primavera from Oracle Primavera.
layout: jsonld
name: Oracle Primavera Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: primavera
  uri: https://docs.oracle.com/en/industries/construction-engineering/primavera/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Project
  type: reference
- container: ''
  name: ObjectId
  type: integer
- container: ''
  name: Id
  type: ''
- container: ''
  name: Name
  type: ''
- container: ''
  name: Status
  type: ''
- container: ''
  name: PlannedStartDate
  type: dateTime
- container: ''
  name: PlannedFinishDate
  type: dateTime
- container: ''
  name: ActualStartDate
  type: dateTime
- container: ''
  name: ActualFinishDate
  type: dateTime
- container: ''
  name: PercentComplete
  type: decimal
- container: ''
  name: TotalBudgetCost
  type: decimal
- container: ''
  name: DataDate
  type: dateTime
- container: ''
  name: RiskLevel
  type: ''
- container: ''
  name: Activity
  type: reference
- container: ''
  name: PlannedDuration
  type: decimal
- container: ''
  name: CriticalFlag
  type: boolean
- container: ''
  name: TotalFloat
  type: decimal
- container: ''
  name: WBSElement
  type: reference
- container: ''
  name: Resource
  type: reference
- container: ''
  name: ResourceType
  type: ''
- container: ''
  name: PricePerUnit
  type: decimal
- container: ''
  name: ResourceAssignment
  type: reference
- container: ''
  name: PlannedUnits
  type: decimal
- container: ''
  name: ActualUnits
  type: decimal
- container: ''
  name: PlannedCost
  type: decimal
- container: ''
  name: ActualCost
  type: decimal
property_count: 26
provider_name: Oracle Primavera
provider_slug: oracle-primavera
slug: oracle-primavera-context
source_filename: oracle-primavera-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"primavera\": \"https://docs.oracle.com/en/industries/construction-engineering/primavera/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Project\": {\n      \"@id\": \"schema:Project\",\n      \"@type\": \"@id\"\n    },\n    \"ObjectId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Id\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"Name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"Status\": {\n      \"@id\": \"schema:status\"\n    },\n    \"PlannedStartDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"PlannedFinishDate\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ActualStartDate\": {\n      \"@id\": \"primavera:actualStartDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ActualFinishDate\": {\n  \
  \    \"@id\": \"primavera:actualFinishDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"PercentComplete\": {\n      \"@id\": \"schema:percentComplete\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"TotalBudgetCost\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"DataDate\": {\n      \"@id\": \"primavera:dataDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"RiskLevel\": {\n      \"@id\": \"primavera:riskLevel\"\n    },\n\n    \"Activity\": {\n      \"@id\": \"schema:Action\",\n      \"@type\": \"@id\"\n    },\n    \"PlannedDuration\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"CriticalFlag\": {\n      \"@id\": \"primavera:criticalFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"TotalFloat\": {\n      \"@id\": \"primavera:totalFloat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"WBSElement\": {\n      \"@id\": \"schema:ItemList\",\n      \"@type\": \"@id\"\n    },\n\n    \"\
  Resource\": {\n      \"@id\": \"schema:Person\",\n      \"@type\": \"@id\"\n    },\n    \"ResourceType\": {\n      \"@id\": \"primavera:resourceType\"\n    },\n    \"PricePerUnit\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"ResourceAssignment\": {\n      \"@id\": \"schema:ScheduleAction\",\n      \"@type\": \"@id\"\n    },\n    \"PlannedUnits\": {\n      \"@id\": \"primavera:plannedUnits\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ActualUnits\": {\n      \"@id\": \"primavera:actualUnits\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"PlannedCost\": {\n      \"@id\": \"primavera:plannedCost\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ActualCost\": {\n      \"@id\": \"primavera:actualCost\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-primavera/refs/heads/main/json-ld/oracle-primavera-context.jsonld
tags:
- Construction
- Engineering
- Project Management
- Scheduling
- Portfolio Management
- Oracle
- JSON-LD
- Linked Data
- Semantic Web
---
