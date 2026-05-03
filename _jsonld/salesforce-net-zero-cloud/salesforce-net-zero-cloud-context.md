---
api_specs:
- filename: salesforce-net-zero-cloud-rest-api-openapi.yml
  format: yaml
  label: Net Zero Cloud REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-net-zero-cloud/refs/heads/main/openapi/salesforce-net-zero-cloud-rest-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/salesforce-net-zero-cloud-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/salesforce-net-zero-cloud/refs/heads/main/json-ld/salesforce-net-zero-cloud-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Salesforce Net Zero Cloud from Salesforce Net Zero Cloud.
layout: jsonld
name: Salesforce Net Zero Cloud Context
namespaces:
- prefix: sf
  uri: https://developer.salesforce.com/docs/atlas.en-us.netzero_api.meta/netzero_api/
- prefix: schema
  uri: https://schema.org/
- prefix: qudt
  uri: http://qudt.org/schema/qudt/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: CarbonEmission
  type: reference
- container: ''
  name: SustainabilityGoal
  type: reference
- container: ''
  name: EmissionFactor
  type: reference
- container: ''
  name: EnergyConsumption
  type: reference
- container: ''
  name: WasteDisposal
  type: reference
- container: ''
  name: WaterWithdrawal
  type: reference
- container: ''
  name: Scope
  type: integer
- container: ''
  name: QuantityMtCO2e
  type: decimal
- container: ''
  name: ReportingYear
  type: integer
- container: ''
  name: EmissionSource
  type: string
- container: ''
  name: CalculationMethod
  type: string
- container: ''
  name: GoalType
  type: string
- container: ''
  name: BaselineYear
  type: integer
- container: ''
  name: TargetYear
  type: integer
- container: ''
  name: ReductionTargetPercentage
  type: decimal
- container: ''
  name: EnergyType
  type: string
- container: ''
  name: QuantityKWh
  type: decimal
- container: ''
  name: WasteType
  type: string
- container: ''
  name: DisposalMethod
  type: string
- container: ''
  name: QuantityKg
  type: decimal
- container: ''
  name: WaterSource
  type: string
- container: ''
  name: QuantityCubicMeters
  type: decimal
- container: ''
  name: CreatedDate
  type: dateTime
- container: ''
  name: LastModifiedDate
  type: dateTime
- container: ''
  name: Organization
  type: ''
- container: ''
  name: name
  type: ''
property_count: 26
provider_name: Salesforce Net Zero Cloud
provider_slug: salesforce-net-zero-cloud
slug: salesforce-net-zero-cloud-context
source_filename: salesforce-net-zero-cloud-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sf\": \"https://developer.salesforce.com/docs/atlas.en-us.netzero_api.meta/netzero_api/\",\n    \"schema\": \"https://schema.org/\",\n    \"qudt\": \"http://qudt.org/schema/qudt/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CarbonEmission\": {\n      \"@id\": \"sf:CarbonEmission\",\n      \"@type\": \"@id\"\n    },\n    \"SustainabilityGoal\": {\n      \"@id\": \"sf:SustainabilityGoal\",\n      \"@type\": \"@id\"\n    },\n    \"EmissionFactor\": {\n      \"@id\": \"sf:EmissionFactor\",\n      \"@type\": \"@id\"\n    },\n    \"EnergyConsumption\": {\n      \"@id\": \"sf:EnergyConsumption\",\n      \"@type\": \"@id\"\n    },\n    \"WasteDisposal\": {\n      \"@id\": \"sf:WasteDisposal\",\n      \"@type\": \"@id\"\n    },\n    \"WaterWithdrawal\": {\n      \"@id\": \"sf:WaterWithdrawal\",\n      \"@type\": \"@id\"\n    },\n    \"Scope\": {\n      \"@id\": \"sf:Scope\",\n      \"@type\": \"xsd:integer\"\n   \
  \ },\n    \"QuantityMtCO2e\": {\n      \"@id\": \"sf:QuantityMtCO2e\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ReportingYear\": {\n      \"@id\": \"sf:ReportingYear\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"EmissionSource\": {\n      \"@id\": \"sf:EmissionSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CalculationMethod\": {\n      \"@id\": \"sf:CalculationMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GoalType\": {\n      \"@id\": \"sf:GoalType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BaselineYear\": {\n      \"@id\": \"sf:BaselineYear\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"TargetYear\": {\n      \"@id\": \"sf:TargetYear\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ReductionTargetPercentage\": {\n      \"@id\": \"sf:ReductionTargetPercentage\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"EnergyType\": {\n      \"@id\": \"sf:EnergyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QuantityKWh\": {\n      \"\
  @id\": \"sf:QuantityKWh\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"WasteType\": {\n      \"@id\": \"sf:WasteType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DisposalMethod\": {\n      \"@id\": \"sf:DisposalMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QuantityKg\": {\n      \"@id\": \"sf:QuantityKg\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"WaterSource\": {\n      \"@id\": \"sf:WaterSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QuantityCubicMeters\": {\n      \"@id\": \"sf:QuantityCubicMeters\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"CreatedDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LastModifiedDate\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Organization\": {\n      \"@id\": \"schema:Organization\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/salesforce-net-zero-cloud/refs/heads/main/json-ld/salesforce-net-zero-cloud-context.jsonld
tags:
- Carbon Accounting
- Carbon Emissions
- Climate
- Environmental
- ESG
- Net Zero
- Sustainability
- JSON-LD
- Linked Data
- Semantic Web
---
