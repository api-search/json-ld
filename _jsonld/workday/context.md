---
api_specs:
- filename: hcm.yml
  format: yaml
  label: Workday HCM API
  slug: hcm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/openapi/hcm.yml
- filename: financialManagement.yml
  format: yaml
  label: Workday Financial Management API
  slug: financial-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/openapi/financialManagement.yml
- filename: recruiting.yml
  format: yaml
  label: Workday Recruiting API
  slug: recruiting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/openapi/recruiting.yml
- filename: timeTracking.yml
  format: yaml
  label: Workday Time Tracking API
  slug: time-tracking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/openapi/timeTracking.yml
- filename: benefits.yml
  format: yaml
  label: Workday Benefits API
  slug: benefits-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/openapi/benefits.yml
- filename: absenceManagement.yml
  format: yaml
  label: Workday Absence Management API
  slug: absence-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/openapi/absenceManagement.yml
- filename: compensation.yml
  format: yaml
  label: Workday Compensation API
  slug: compensation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/openapi/compensation.yml
- filename: payroll.yml
  format: yaml
  label: Workday Payroll API
  slug: payroll-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/openapi/payroll.yml
- filename: person.yml
  format: yaml
  label: Workday Person API
  slug: person-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/openapi/person.yml
- filename: performanceManagement.yml
  format: yaml
  label: Workday Performance Management API
  slug: performance-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/openapi/performanceManagement.yml
- filename: talent.yml
  format: yaml
  label: Workday Talent Management API
  slug: talent-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/openapi/talent.yml
- filename: common.yml
  format: yaml
  label: Workday Common API
  slug: common-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/openapi/common.yml
- filename: staffing.yml
  format: yaml
  label: Workday Staffing API
  slug: staffing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/openapi/staffing.yml
- filename: prismAnalytics.yml
  format: yaml
  label: Workday Prism Analytics API
  slug: prism-analytics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/openapi/prismAnalytics.yml
- filename: raas.yml
  format: yaml
  label: Workday Report-as-a-Service API
  slug: raas-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/openapi/raas.yml
- filename: wql.yml
  format: yaml
  label: Workday WQL API
  slug: wql-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/openapi/wql.yml
class_count: 3
classes:
- id
- type
- descriptor
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Workday.
layout: jsonld
name: context Context
namespaces:
- prefix: wd
  uri: https://workday.com/api/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: org
  uri: http://www.w3.org/ns/org#
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
properties:
- container: ''
  name: href
  type: reference
- container: ''
  name: Worker
  type: ''
- container: ''
  name: PersonName
  type: ''
- container: ''
  name: Position
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: SupervisoryOrganization
  type: ''
- container: ''
  name: JobProfile
  type: ''
- container: ''
  name: CompensationPlan
  type: ''
- container: ''
  name: CompensationGrade
  type: ''
- container: ''
  name: TimeOffEntry
  type: ''
- container: ''
  name: TimeOffBalance
  type: ''
- container: ''
  name: LeaveOfAbsence
  type: ''
- container: ''
  name: Location
  type: ''
- container: ''
  name: BenefitElection
  type: ''
- container: ''
  name: Dataset
  type: ''
- container: ''
  name: JobRequisition
  type: ''
- container: ''
  name: Candidate
  type: ''
- container: ''
  name: PerformanceReview
  type: ''
- container: ''
  name: Goal
  type: ''
property_count: 19
provider_name: Workday
provider_slug: workday
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://workday.com/api/vocab#\",\n    \"wd\": \"https://workday.com/api/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"org\": \"http://www.w3.org/ns/org#\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"descriptor\": \"rdfs:label\",\n    \"href\": {\n      \"@id\": \"wd:href\",\n      \"@type\": \"@id\"\n    },\n\n    \"Worker\": {\n      \"@id\": \"wd:Worker\",\n      \"@context\": {\n        \"workerID\": \"wd:workerID\",\n        \"workerType\": {\n          \"@id\": \"wd:workerType\",\n          \"@type\": \"@id\"\n        },\n        \"businessTitle\": \"schema:jobTitle\",\n        \"hireDate\": {\n          \"@id\": \"wd:hireDate\",\n          \"@type\"\
  : \"xsd:date\"\n        },\n        \"originalHireDate\": {\n          \"@id\": \"wd:originalHireDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"terminationDate\": {\n          \"@id\": \"wd:terminationDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"isActive\": {\n          \"@id\": \"wd:isActive\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isManager\": {\n          \"@id\": \"wd:isManager\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"primaryWorkEmail\": \"schema:email\",\n        \"primaryWorkPhone\": \"schema:telephone\",\n        \"externalID\": \"wd:externalID\"\n      }\n    },\n\n    \"PersonName\": {\n      \"@id\": \"wd:PersonName\",\n      \"@context\": {\n        \"firstName\": \"schema:givenName\",\n        \"middleName\": \"schema:additionalName\",\n        \"lastName\": \"schema:familyName\",\n        \"fullName\": \"schema:name\",\n        \"prefix\": \"schema:honorificPrefix\",\n        \"suffix\":\
  \ \"schema:honorificSuffix\"\n      }\n    },\n\n    \"Position\": {\n      \"@id\": \"wd:Position\",\n      \"@context\": {\n        \"positionID\": \"wd:positionID\",\n        \"isFilled\": {\n          \"@id\": \"wd:isFilled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isAvailableForRecruit\": {\n          \"@id\": \"wd:isAvailableForRecruit\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isClosed\": {\n          \"@id\": \"wd:isClosed\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"jobProfile\": {\n          \"@id\": \"wd:jobProfile\",\n          \"@type\": \"@id\"\n        },\n        \"supervisoryOrganization\": {\n          \"@id\": \"wd:supervisoryOrganization\",\n          \"@type\": \"@id\"\n        },\n        \"location\": {\n          \"@id\": \"wd:location\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"org:Organization\",\n      \"@context\": {\n        \"name\":\
  \ \"schema:name\",\n        \"code\": \"wd:organizationCode\",\n        \"organizationType\": {\n          \"@id\": \"wd:organizationType\",\n          \"@type\": \"@id\"\n        },\n        \"superiorOrganization\": {\n          \"@id\": \"org:subOrganizationOf\",\n          \"@type\": \"@id\"\n        },\n        \"subordinateOrganizations\": {\n          \"@id\": \"org:hasSubOrganization\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"manager\": {\n          \"@id\": \"org:headOf\",\n          \"@type\": \"@id\"\n        },\n        \"isInactive\": {\n          \"@id\": \"wd:isInactive\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"staffingModel\": \"wd:staffingModel\",\n        \"memberCount\": {\n          \"@id\": \"wd:memberCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"SupervisoryOrganization\": {\n      \"@id\": \"wd:SupervisoryOrganization\",\n      \"@context\": {\n        \"\
  name\": \"schema:name\",\n        \"manager\": {\n          \"@id\": \"org:headOf\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"JobProfile\": {\n      \"@id\": \"wd:JobProfile\",\n      \"@context\": {\n        \"jobProfileName\": \"schema:name\",\n        \"jobCode\": \"wd:jobCode\",\n        \"jobFamily\": {\n          \"@id\": \"wd:jobFamily\",\n          \"@type\": \"@id\"\n        },\n        \"jobCategory\": {\n          \"@id\": \"wd:jobCategory\",\n          \"@type\": \"@id\"\n        },\n        \"managementLevel\": {\n          \"@id\": \"wd:managementLevel\",\n          \"@type\": \"@id\"\n        },\n        \"summary\": \"schema:description\"\n      }\n    },\n\n    \"CompensationPlan\": {\n      \"@id\": \"wd:CompensationPlan\",\n      \"@context\": {\n        \"compensationPlanType\": \"wd:compensationPlanType\",\n        \"amount\": {\n          \"@id\": \"schema:amount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\":\
  \ {\n          \"@id\": \"schema:currency\",\n          \"@type\": \"@id\"\n        },\n        \"frequency\": {\n          \"@id\": \"wd:frequency\",\n          \"@type\": \"@id\"\n        },\n        \"effectiveDate\": {\n          \"@id\": \"wd:effectiveDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"CompensationGrade\": {\n      \"@id\": \"wd:CompensationGrade\",\n      \"@context\": {\n        \"minimumAmount\": {\n          \"@id\": \"wd:minimumAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"midpointAmount\": {\n          \"@id\": \"wd:midpointAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"maximumAmount\": {\n          \"@id\": \"wd:maximumAmount\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"TimeOffEntry\": {\n      \"@id\": \"wd:TimeOffEntry\",\n      \"@context\": {\n        \"date\": {\n          \"@id\": \"wd:timeOffDate\",\n          \"@type\": \"xsd:date\"\n      \
  \  },\n        \"dailyQuantity\": {\n          \"@id\": \"wd:dailyQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"timeOffType\": {\n          \"@id\": \"wd:timeOffType\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"wd:status\"\n      }\n    },\n\n    \"TimeOffBalance\": {\n      \"@id\": \"wd:TimeOffBalance\",\n      \"@context\": {\n        \"timeOffPlan\": {\n          \"@id\": \"wd:timeOffPlan\",\n          \"@type\": \"@id\"\n        },\n        \"balance\": {\n          \"@id\": \"wd:balance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"unit\": \"wd:unit\",\n        \"asOfDate\": {\n          \"@id\": \"wd:asOfDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"LeaveOfAbsence\": {\n      \"@id\": \"wd:LeaveOfAbsence\",\n      \"@context\": {\n        \"leaveType\": {\n          \"@id\": \"wd:leaveType\",\n          \"@type\": \"@id\"\n        },\n        \"startDate\": {\n          \"@id\"\
  : \"schema:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"estimatedEndDate\": {\n          \"@id\": \"wd:estimatedEndDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"actualEndDate\": {\n          \"@id\": \"wd:actualEndDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"status\": \"wd:leaveStatus\"\n      }\n    },\n\n    \"Location\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"latitude\": {\n          \"@id\": \"schema:latitude\",\n          \"@type\": \"xsd:double\"\n        },\n        \"longitude\": {\n          \"@id\": \"schema:longitude\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"BenefitElection\": {\n      \"@id\": \"wd:BenefitElection\",\n      \"@context\": {\n        \"benefitPlan\": {\n          \"@id\": \"wd:benefitPlan\",\n          \"@type\": \"@id\"\n        },\n        \"coverageLevel\": {\n          \"@id\": \"wd:coverageLevel\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"coverageBeginDate\": {\n          \"@id\": \"wd:coverageBeginDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"coverageEndDate\": {\n          \"@id\": \"wd:coverageEndDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"employeeCost\": {\n          \"@id\": \"wd:employeeCost\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"employerCost\": {\n          \"@id\": \"wd:employerCost\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Dataset\": {\n      \"@id\": \"wd:PrismDataset\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"rdfs:label\",\n        \"description\": \"schema:description\",\n        \"rowCount\": {\n          \"@id\": \"wd:rowCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdOn\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n     \
  \   \"updatedOn\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"JobRequisition\": {\n      \"@id\": \"wd:JobRequisition\",\n      \"@context\": {\n        \"requisitionNumber\": \"wd:requisitionNumber\",\n        \"jobTitle\": \"schema:title\",\n        \"numberOfOpenings\": {\n          \"@id\": \"wd:numberOfOpenings\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"targetHireDate\": {\n          \"@id\": \"wd:targetHireDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"Candidate\": {\n      \"@id\": \"wd:Candidate\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\"\n      }\n    },\n\n    \"PerformanceReview\": {\n      \"@id\": \"wd:PerformanceReview\",\n      \"@context\": {\n        \"overallRating\": {\n          \"@id\": \"wd:overallRating\",\n          \"@type\": \"@id\"\n\
  \        },\n        \"completedDate\": {\n          \"@id\": \"wd:completedDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"Goal\": {\n      \"@id\": \"wd:Goal\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"dueDate\": {\n          \"@id\": \"wd:dueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"status\": \"wd:goalStatus\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/json-ld/context.jsonld
tags:
- Cloud Computing
- Enterprise Software
- Financial Management
- HCM
- SaaS
- JSON-LD
- Linked Data
- Semantic Web
---
