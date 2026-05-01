---
api_specs:
- filename: gainsight-rest-api-openapi.yml
  format: yaml
  label: Gainsight REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-rest-api-openapi.yml
- filename: gainsight-px-api-openapi.yml
  format: yaml
  label: Gainsight PX API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-px-api-openapi.yml
- filename: gainsight-cs-company-api-openapi.yml
  format: yaml
  label: Gainsight CS Company API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-company-api-openapi.yml
- filename: gainsight-cs-person-api-openapi.yml
  format: yaml
  label: Gainsight CS Person API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-person-api-openapi.yml
- filename: gainsight-cs-custom-object-api-openapi.yml
  format: yaml
  label: Gainsight CS Custom Object API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-custom-object-api-openapi.yml
- filename: gainsight-cs-cta-api-openapi.yml
  format: yaml
  label: Gainsight CS CTA API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-cta-api-openapi.yml
- filename: gainsight-cs-timeline-api-openapi.yml
  format: yaml
  label: Gainsight CS Timeline API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-timeline-api-openapi.yml
- filename: gainsight-cs-success-plan-api-openapi.yml
  format: yaml
  label: Gainsight CS Success Plan API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-success-plan-api-openapi.yml
- filename: gainsight-cs-data-management-api-openapi.yml
  format: yaml
  label: Gainsight CS Data Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-data-management-api-openapi.yml
- filename: gainsight-cs-bulk-api-openapi.yml
  format: yaml
  label: Gainsight CS Bulk API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-bulk-api-openapi.yml
- filename: gainsight-cs-events-api-openapi.yml
  format: yaml
  label: Gainsight CS Events API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-events-api-openapi.yml
- filename: gainsight-cs-user-management-api-openapi.yml
  format: yaml
  label: Gainsight CS User Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-user-management-api-openapi.yml
- filename: gainsight-cs-customer-goals-api-openapi.yml
  format: yaml
  label: Gainsight CS Customer Goals API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-customer-goals-api-openapi.yml
- filename: gainsight-cs-renewal-center-api-openapi.yml
  format: yaml
  label: Gainsight CS Renewal Center API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-renewal-center-api-openapi.yml
- filename: gainsight-cs-task-and-playbook-api-openapi.yml
  format: yaml
  label: Gainsight CS Task and Playbook API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-task-and-playbook-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/gainsight-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/json-ld/gainsight-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Gainsight from Gainsight.
layout: jsonld
name: Gainsight Context
namespaces:
- prefix: gainsight
  uri: https://www.gainsight.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Company
  type: ''
- container: ''
  name: Person
  type: ''
- container: ''
  name: CTA
  type: ''
- container: ''
  name: TimelineActivity
  type: ''
- container: ''
  name: SuccessPlan
  type: ''
- container: ''
  name: Opportunity
  type: ''
- container: ''
  name: Goal
  type: ''
- container: ''
  name: Task
  type: ''
- container: ''
  name: GainsightUser
  type: ''
- container: ''
  name: PXUser
  type: ''
- container: ''
  name: PXAccount
  type: ''
property_count: 11
provider_name: Gainsight
provider_slug: gainsight
slug: gainsight-context
source_filename: gainsight-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"gainsight\": \"https://www.gainsight.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Company\": {\n      \"@id\": \"gainsight:Company\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"industry\": \"gainsight:industry\",\n        \"arr\": {\n          \"@id\": \"gainsight:annualRecurringRevenue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"mrr\": {\n          \"@id\": \"gainsight:monthlyRecurringRevenue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"lifecycleStage\": \"gainsight:lifecycleStage\",\n        \"status\": \"gainsight:status\",\n        \"csmName\": \"gainsight:customerSuccessManager\",\n        \"employees\": {\n          \"@id\": \"schema:numberOfEmployees\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"renewalDate\": {\n          \"@id\": \"gainsight:renewalDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"overallScore\": {\n          \"@id\": \"gainsight:healthScore\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Person\": {\n      \"@id\": \"gainsight:Person\",\n      \"@context\": {\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"title\": \"schema:jobTitle\",\n        \"role\": \"gainsight:contactRole\",\n        \"phone\": \"schema:telephone\",\n        \"location\": \"schema:location\",\n        \"nps\": {\n          \"@id\": \"gainsight:netPromoterScore\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"isPrimary\": {\n          \"@id\": \"gainsight:isPrimaryContact\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isActive\": {\n          \"@id\": \"gainsight:isActive\",\n          \"@type\"\
  : \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"CTA\": {\n      \"@id\": \"gainsight:CallToAction\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"companyName\": \"gainsight:companyName\",\n        \"typeName\": \"gainsight:ctaType\",\n        \"reasonName\": \"gainsight:ctaReason\",\n        \"statusName\": \"gainsight:ctaStatus\",\n        \"ownerName\": \"gainsight:owner\",\n        \"dueDate\": {\n          \"@id\": \"gainsight:dueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"closedDate\": {\n          \"@id\": \"gainsight:closedDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"comments\": \"schema:comment\",\n        \"source\": \"gainsight:source\"\n      }\n    },\n\n    \"TimelineActivity\": {\n      \"@id\": \"gainsight:TimelineActivity\",\n      \"@context\": {\n        \"subject\": \"schema:name\",\n        \"notes\": \"schema:text\",\n        \"activityTypeName\": \"gainsight:activityType\",\n        \"companyName\"\
  : \"gainsight:companyName\",\n        \"activityDate\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"ownerName\": \"gainsight:owner\",\n        \"sentiment\": \"gainsight:sentiment\"\n      }\n    },\n\n    \"SuccessPlan\": {\n      \"@id\": \"gainsight:SuccessPlan\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"companyName\": \"gainsight:companyName\",\n        \"typeName\": \"gainsight:planType\",\n        \"status\": \"gainsight:planStatus\",\n        \"ownerName\": \"gainsight:owner\",\n        \"startDate\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"endDate\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"Opportunity\": {\n      \"@id\": \"gainsight:Opportunity\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"companyName\": \"gainsight:companyName\",\n\
  \        \"bookingType\": \"gainsight:bookingType\",\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": \"schema:priceCurrency\",\n        \"closeDate\": {\n          \"@id\": \"gainsight:closeDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"stage\": \"gainsight:opportunityStage\",\n        \"probability\": {\n          \"@id\": \"gainsight:winProbability\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"isClosed\": {\n          \"@id\": \"gainsight:isClosed\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isWon\": {\n          \"@id\": \"gainsight:isWon\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Goal\": {\n      \"@id\": \"gainsight:CustomerGoal\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"companyName\": \"gainsight:companyName\",\n        \"status\"\
  : \"gainsight:goalStatus\",\n        \"ownerName\": \"gainsight:owner\",\n        \"targetDate\": {\n          \"@id\": \"gainsight:targetDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"completionPercentage\": {\n          \"@id\": \"gainsight:completionPercentage\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Task\": {\n      \"@id\": \"gainsight:Task\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"gainsight:taskStatus\",\n        \"ownerName\": \"gainsight:owner\",\n        \"dueDate\": {\n          \"@id\": \"gainsight:dueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"completedDate\": {\n          \"@id\": \"gainsight:completedDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"priority\": \"gainsight:priority\"\n      }\n    },\n\n    \"GainsightUser\": {\n      \"@id\": \"gainsight:GainsightUser\",\n      \"@context\"\
  : {\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"userType\": \"gainsight:userType\",\n        \"licenseType\": \"gainsight:licenseType\",\n        \"role\": \"gainsight:userRole\",\n        \"isActive\": {\n          \"@id\": \"gainsight:isActive\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"PXUser\": {\n      \"@id\": \"gainsight:PXUser\",\n      \"@context\": {\n        \"email\": \"schema:email\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"title\": \"schema:jobTitle\",\n        \"role\": \"gainsight:userRole\",\n        \"score\": {\n          \"@id\": \"gainsight:engagementScore\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"numberOfVisits\": {\n          \"@id\": \"gainsight:numberOfVisits\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"lastSeenDate\": {\n       \
  \   \"@id\": \"gainsight:lastSeenDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PXAccount\": {\n      \"@id\": \"gainsight:PXAccount\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"plan\": \"gainsight:plan\",\n        \"numberOfUsers\": {\n          \"@id\": \"gainsight:numberOfUsers\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"numberOfVisits\": {\n          \"@id\": \"gainsight:numberOfVisits\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"lastSeenDate\": {\n          \"@id\": \"gainsight:lastSeenDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/json-ld/gainsight-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
