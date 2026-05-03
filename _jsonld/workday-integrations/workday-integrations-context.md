---
api_specs:
- filename: openapi.json
  format: json
  label: Workday REST API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/restapi/openapi.json
- filename: workday-integrations-raas-openapi.yml
  format: yaml
  label: Workday RaaS (Report-as-a-Service)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-integrations/refs/heads/main/openapi/workday-integrations-raas-openapi.yml
- filename: workday-integrations-prism-analytics-openapi.yml
  format: yaml
  label: Workday Prism Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-integrations/refs/heads/main/openapi/workday-integrations-prism-analytics-openapi.yml
class_count: 0
classes: []
context_file: json-ld/workday-integrations-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workday-integrations/refs/heads/main/json-ld/workday-integrations-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Workday Integrations from Workday Integrations.
layout: jsonld
name: Workday Integrations Context
namespaces:
- prefix: workday
  uri: https://community.workday.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Worker
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Position
  type: ''
- container: ''
  name: JobProfile
  type: ''
- container: ''
  name: Compensation
  type: ''
- container: ''
  name: BenefitEnrollment
  type: ''
- container: ''
  name: TimeOffPlan
  type: ''
- container: ''
  name: JobRequisition
  type: ''
- container: ''
  name: BusinessProcess
  type: ''
- container: ''
  name: Dataset
  type: ''
- container: ''
  name: PayGroup
  type: ''
property_count: 11
provider_name: Workday Integrations
provider_slug: workday-integrations
slug: workday-integrations-context
source_filename: workday-integrations-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"workday\": \"https://community.workday.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Worker\": {\n      \"@id\": \"workday:Worker\",\n      \"@context\": {\n        \"descriptor\": \"schema:name\",\n        \"workerType\": \"workday:workerType\",\n        \"personalData\": \"workday:personalData\",\n        \"employmentData\": \"workday:employmentData\",\n        \"contactData\": \"workday:contactData\",\n        \"hireDate\": {\n          \"@id\": \"workday:hireDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"terminationDate\": {\n          \"@id\": \"workday:terminationDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"workerStatus\": \"workday:workerStatus\",\n        \"primaryWorkEmail\": \"schema:email\",\n        \"primaryWorkPhone\": \"schema:telephone\"\n      }\n\
  \    },\n\n    \"Organization\": {\n      \"@id\": \"workday:Organization\",\n      \"@context\": {\n        \"descriptor\": \"schema:name\",\n        \"organizationType\": \"workday:organizationType\",\n        \"organizationCode\": \"workday:organizationCode\",\n        \"isActive\": {\n          \"@id\": \"workday:isActive\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"manager\": \"workday:manager\",\n        \"superiorOrganization\": \"workday:superiorOrganization\",\n        \"subordinateOrganizations\": \"workday:subordinateOrganizations\"\n      }\n    },\n\n    \"Position\": {\n      \"@id\": \"workday:Position\",\n      \"@context\": {\n        \"descriptor\": \"schema:name\",\n        \"positionId\": \"workday:positionId\",\n        \"isFilled\": {\n          \"@id\": \"workday:isFilled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"worker\": \"workday:worker\",\n        \"jobProfile\": \"workday:jobProfile\",\n        \"supervisoryOrganization\"\
  : \"workday:supervisoryOrganization\",\n        \"location\": \"schema:location\",\n        \"availableDate\": {\n          \"@id\": \"workday:availableDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"JobProfile\": {\n      \"@id\": \"workday:JobProfile\",\n      \"@context\": {\n        \"descriptor\": \"schema:name\",\n        \"jobCode\": \"workday:jobCode\",\n        \"jobFamily\": \"workday:jobFamily\",\n        \"managementLevel\": \"workday:managementLevel\",\n        \"jobCategory\": \"workday:jobCategory\",\n        \"isActive\": {\n          \"@id\": \"workday:isActive\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"jobDescription\": \"schema:description\"\n      }\n    },\n\n    \"Compensation\": {\n      \"@id\": \"workday:Compensation\",\n      \"@context\": {\n        \"worker\": \"workday:worker\",\n        \"effectiveDate\": {\n          \"@id\": \"workday:effectiveDate\",\n          \"@type\": \"xsd:date\"\n        },\n  \
  \      \"totalBasePayAnnualized\": {\n          \"@id\": \"workday:totalBasePayAnnualized\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": \"workday:currency\",\n        \"compensationGrade\": \"workday:compensationGrade\",\n        \"compensationStep\": \"workday:compensationStep\"\n      }\n    },\n\n    \"BenefitEnrollment\": {\n      \"@id\": \"workday:BenefitEnrollment\",\n      \"@context\": {\n        \"benefitPlan\": \"workday:benefitPlan\",\n        \"coverageLevel\": \"workday:coverageLevel\",\n        \"coverageBeginDate\": {\n          \"@id\": \"workday:coverageBeginDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"coverageEndDate\": {\n          \"@id\": \"workday:coverageEndDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"employeeCost\": {\n          \"@id\": \"workday:employeeCost\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"employerCost\": {\n          \"@id\": \"workday:employerCost\",\n  \
  \        \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"TimeOffPlan\": {\n      \"@id\": \"workday:TimeOffPlan\",\n      \"@context\": {\n        \"timeOffPlan\": \"workday:timeOffPlan\",\n        \"balance\": {\n          \"@id\": \"workday:balance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"accrued\": {\n          \"@id\": \"workday:accrued\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"used\": {\n          \"@id\": \"workday:used\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"unit\": \"workday:unit\",\n        \"asOfDate\": {\n          \"@id\": \"workday:asOfDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"JobRequisition\": {\n      \"@id\": \"workday:JobRequisition\",\n      \"@context\": {\n        \"descriptor\": \"schema:name\",\n        \"requisitionNumber\": \"workday:requisitionNumber\",\n        \"status\": \"workday:requisitionStatus\",\n        \"jobProfile\": \"workday:jobProfile\"\
  ,\n        \"numberOfOpenings\": {\n          \"@id\": \"workday:numberOfOpenings\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"targetHireDate\": {\n          \"@id\": \"workday:targetHireDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:date\"\n        },\n        \"hiringManager\": \"workday:hiringManager\"\n      }\n    },\n\n    \"BusinessProcess\": {\n      \"@id\": \"workday:BusinessProcess\",\n      \"@context\": {\n        \"descriptor\": \"schema:name\",\n        \"businessProcessType\": \"workday:businessProcessType\",\n        \"status\": \"workday:processStatus\",\n        \"initiatedDate\": {\n          \"@id\": \"workday:initiatedDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedDate\": {\n          \"@id\": \"workday:completedDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"initiator\": \"workday:initiator\"\
  ,\n        \"subject\": \"workday:subject\",\n        \"currentStep\": \"workday:currentStep\"\n      }\n    },\n\n    \"Dataset\": {\n      \"@id\": \"workday:Dataset\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"workday:datasetStatus\",\n        \"rowCount\": {\n          \"@id\": \"workday:rowCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"publishedDate\": {\n          \"@id\": \"workday:publishedDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PayGroup\": {\n      \"@id\": \"workday:PayGroup\",\n      \"@context\": {\n        \"descriptor\": \"schema:name\",\n        \"payFrequency\": \"workday:payFrequency\"\
  ,\n        \"country\": \"workday:country\",\n        \"currency\": \"workday:currency\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/workday-integrations/refs/heads/main/json-ld/workday-integrations-context.jsonld
tags:
- Cloud
- Enterprise Software
- ERP
- Finance
- HCM
- HR
- Integration
- JSON-LD
- Linked Data
- Semantic Web
---
