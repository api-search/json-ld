---
class_count: 49
classes:
- Application
- AppSummary
- AppDetails
- UsageEvent
- SpendData
- ProvisionedUser
- OrgChartUser
- ProvisioningWorkflow
- AuditEvent
- appId
- ApplicationId
- AppName
- AppStatus
- VendorName
- AppCategory
- email
- firstName
- lastName
- role
- department
- title
- managerEmail
- eventName
- eventType
- eventId
- userEmail
- amount
- currency
- date
- description
- workflowId
- workflowName
- applicationId
- status
- executionId
- startTime
- endTime
- totalUsers
- activeUsers
- lastActivityDate
- totalSpend
- totalValue
- contractId
- startDate
- endDate
- instanceId
- instanceName
- suggestedOutcome
- actionedOutcome
context_file: json-ld/productiv-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/productiv/refs/heads/main/json-ld/productiv-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Productiv from Productiv.
layout: jsonld
name: Productiv Context
namespaces:
- prefix: productiv
  uri: https://public-api.productiv.com/schema/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: appName
  type: string
- container: ''
  name: appDescription
  type: string
- container: ''
  name: appCategory
  type: string
- container: ''
  name: appUrl
  type: reference
- container: ''
  name: timestamp
  type: dateTime
property_count: 5
provider_name: Productiv
provider_slug: productiv
slug: productiv-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"productiv\": \"https://public-api.productiv.com/schema/\",\n    \"Application\": \"productiv:Application\",\n    \"AppSummary\": \"productiv:AppSummary\",\n    \"AppDetails\": \"productiv:AppDetails\",\n    \"UsageEvent\": \"productiv:UsageEvent\",\n    \"SpendData\": \"productiv:SpendData\",\n    \"ProvisionedUser\": \"productiv:ProvisionedUser\",\n    \"OrgChartUser\": \"productiv:OrgChartUser\",\n    \"ProvisioningWorkflow\": \"productiv:ProvisioningWorkflow\",\n    \"AuditEvent\": \"productiv:AuditEvent\",\n    \"appId\": \"productiv:appId\",\n    \"appName\": {\n      \"@id\": \"productiv:appName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appDescription\": {\n      \"@id\": \"productiv:appDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appCategory\": {\n      \"@id\": \"productiv:appCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appUrl\": {\n      \"@id\": \"productiv:appUrl\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"ApplicationId\": \"productiv:ApplicationId\",\n    \"AppName\": \"productiv:AppName\",\n    \"AppStatus\": \"productiv:AppStatus\",\n    \"VendorName\": \"productiv:VendorName\",\n    \"AppCategory\": \"productiv:AppCategory\",\n    \"email\": \"schema:email\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"role\": \"schema:roleName\",\n    \"department\": \"schema:department\",\n    \"title\": \"schema:jobTitle\",\n    \"managerEmail\": \"productiv:managerEmail\",\n    \"timestamp\": {\n      \"@id\": \"productiv:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"eventName\": \"productiv:eventName\",\n    \"eventType\": \"productiv:eventType\",\n    \"eventId\": \"productiv:eventId\",\n    \"userEmail\": \"productiv:userEmail\",\n    \"amount\": \"schema:price\",\n    \"currency\": \"schema:priceCurrency\",\n    \"date\": \"schema:date\",\n    \"description\": \"schema:description\",\n \
  \   \"workflowId\": \"productiv:workflowId\",\n    \"workflowName\": \"productiv:workflowName\",\n    \"applicationId\": \"productiv:applicationId\",\n    \"status\": \"productiv:status\",\n    \"executionId\": \"productiv:executionId\",\n    \"startTime\": \"productiv:startTime\",\n    \"endTime\": \"productiv:endTime\",\n    \"totalUsers\": \"productiv:totalUsers\",\n    \"activeUsers\": \"productiv:activeUsers\",\n    \"lastActivityDate\": \"productiv:lastActivityDate\",\n    \"totalSpend\": \"productiv:totalSpend\",\n    \"totalValue\": \"productiv:totalValue\",\n    \"contractId\": \"productiv:contractId\",\n    \"startDate\": \"productiv:startDate\",\n    \"endDate\": \"productiv:endDate\",\n    \"instanceId\": \"productiv:instanceId\",\n    \"instanceName\": \"productiv:instanceName\",\n    \"suggestedOutcome\": \"productiv:suggestedOutcome\",\n    \"actionedOutcome\": \"productiv:actionedOutcome\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/productiv/refs/heads/main/json-ld/productiv-context.jsonld
tags:
- Application Portfolio
- Provisioning
- SaaS Management
- Spend Management
- Usage Analytics
- JSON-LD
- Linked Data
- Semantic Web
---
