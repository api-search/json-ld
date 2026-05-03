---
api_specs:
- filename: truto-admin-openapi.yml
  format: yaml
  label: Truto Admin API
  slug: truto-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/openapi/truto-admin-openapi.yml
- filename: truto-unified-hris-openapi.yml
  format: yaml
  label: Truto Unified HRIS API
  slug: truto-unified-hris-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/openapi/truto-unified-hris-openapi.yml
- filename: truto-unified-ats-openapi.yml
  format: yaml
  label: Truto Unified ATS API
  slug: truto-unified-ats-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/openapi/truto-unified-ats-openapi.yml
- filename: truto-unified-crm-openapi.yml
  format: yaml
  label: Truto Unified CRM API
  slug: truto-unified-crm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/openapi/truto-unified-crm-openapi.yml
class_count: 50
classes:
- IntegratedAccount
- Employee
- Employment
- Company
- Group
- Candidate
- Job
- Application
- Contact
- Account
- Opportunity
- id
- name
- description
- status
- integration
- externalId
- remoteId
- firstName
- lastName
- displayName
- email
- personalEmail
- phone
- jobTitle
- location
- avatar
- employmentType
- payRate
- payCurrency
- payPeriod
- source
- tags
- title
- remoteAllowed
- jobType
- leadSource
- domain
- industry
- employeeCount
- annualRevenue
- website
- amount
- currency
- probability
- context
- allowedMethods
- mcpUrl
- transport
- linkUrl
context_file: json-ld/truto-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/json-ld/truto-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Truto from Truto.
layout: jsonld
name: Truto Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: hr
  uri: https://www.w3.org/ns/org#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: departmentId
  type: reference
- container: ''
  name: managerId
  type: reference
- container: ''
  name: hireDate
  type: date
- container: ''
  name: terminationDate
  type: date
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: openedAt
  type: dateTime
- container: ''
  name: closedAt
  type: dateTime
- container: ''
  name: candidateId
  type: reference
- container: ''
  name: jobId
  type: reference
- container: ''
  name: appliedAt
  type: dateTime
- container: ''
  name: accountId
  type: reference
- container: ''
  name: ownerId
  type: reference
- container: ''
  name: closeDate
  type: date
- container: ''
  name: expiresAt
  type: dateTime
property_count: 16
provider_name: Truto
provider_slug: truto
slug: truto-context
source_filename: truto-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"hr\": \"https://www.w3.org/ns/org#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"IntegratedAccount\": \"schema:Service\",\n    \"Employee\": \"schema:Person\",\n    \"Employment\": \"schema:EmployeeRole\",\n    \"Company\": \"schema:Organization\",\n    \"Group\": \"hr:OrganizationalUnit\",\n    \"Candidate\": \"schema:Person\",\n    \"Job\": \"schema:JobPosting\",\n    \"Application\": \"schema:Demand\",\n    \"Contact\": \"schema:Person\",\n    \"Account\": \"schema:Organization\",\n    \"Opportunity\": \"schema:BusinessAudience\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"schema:status\",\n    \"integration\": \"schema:identifier\",\n    \"externalId\": \"dcterms:identifier\",\n    \"createdAt\": {\n      \"@id\": \"dcterms:created\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"remoteId\": \"schema:identifier\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"displayName\": \"schema:alternateName\",\n    \"email\": \"schema:email\",\n    \"personalEmail\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"jobTitle\": \"schema:jobTitle\",\n    \"departmentId\": {\n      \"@id\": \"schema:department\",\n      \"@type\": \"@id\"\n    },\n    \"managerId\": {\n      \"@id\": \"schema:worksFor\",\n      \"@type\": \"@id\"\n    },\n    \"hireDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"terminationDate\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"location\": \"schema:workLocation\",\n    \"avatar\": \"schema:image\",\n    \"employmentType\": \"schema:employmentType\"\
  ,\n\n    \"payRate\": \"schema:baseSalary\",\n    \"payCurrency\": \"schema:priceCurrency\",\n    \"payPeriod\": \"schema:paymentFrequency\",\n    \"effectiveDate\": {\n      \"@id\": \"schema:validFrom\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"source\": \"schema:source\",\n    \"tags\": \"schema:keywords\",\n\n    \"title\": \"schema:title\",\n    \"openedAt\": {\n      \"@id\": \"schema:datePosted\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"closedAt\": {\n      \"@id\": \"schema:validThrough\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"remoteAllowed\": \"schema:jobLocationType\",\n    \"jobType\": \"schema:employmentType\",\n\n    \"candidateId\": {\n      \"@id\": \"schema:candidate\",\n      \"@type\": \"@id\"\n    },\n    \"jobId\": {\n      \"@id\": \"schema:hiringOrganization\",\n      \"@type\": \"@id\"\n    },\n    \"appliedAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"accountId\": {\n      \"@id\"\
  : \"schema:worksFor\",\n      \"@type\": \"@id\"\n    },\n    \"ownerId\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"@id\"\n    },\n    \"leadSource\": \"schema:source\",\n\n    \"domain\": \"schema:url\",\n    \"industry\": \"schema:industry\",\n    \"employeeCount\": \"schema:numberOfEmployees\",\n    \"annualRevenue\": \"schema:revenue\",\n    \"website\": \"schema:url\",\n\n    \"amount\": \"schema:price\",\n    \"currency\": \"schema:priceCurrency\",\n    \"probability\": \"schema:estimatedSalary\",\n    \"closeDate\": {\n      \"@id\": \"schema:validThrough\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"context\": \"schema:additionalProperty\",\n    \"allowedMethods\": \"schema:option\",\n    \"mcpUrl\": \"schema:url\",\n    \"transport\": \"schema:encodingFormat\",\n    \"linkUrl\": \"schema:url\",\n    \"expiresAt\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/json-ld/truto-context.jsonld
tags:
- Unified API
- Integration Platform
- HRIS
- ATS
- CRM
- Embedded Integrations
- MCP
- AI Agents
- SaaS
- JSON-LD
- Linked Data
- Semantic Web
---
