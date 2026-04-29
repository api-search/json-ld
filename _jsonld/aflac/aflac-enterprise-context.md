---
api_specs:
- filename: aflac-enterprise-connect-openapi.yml
  format: yaml
  label: Aflac Enterprise Connect API
  slug: enterprise-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aflac/refs/heads/main/openapi/aflac-enterprise-connect-openapi.yml
class_count: 17
classes:
- GroupList
- PolicyList
- EnrollmentList
- Group
- name
- EligibilityResponse
- Claim
- EnrollmentRequest
- EligibilityRequest
- ClaimRequest
- description
- Enrollment
- createdAt
- updatedAt
- Dependent
- Policy
- ClaimList
context_file: json-ld/aflac-enterprise-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aflac/refs/heads/main/json-ld/aflac-enterprise-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aflac Enterprise from aflac.
layout: jsonld
name: Aflac Enterprise Context
namespaces:
- prefix: aflac
  uri: https://aflac.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: items
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: limit
  type: integer
- container: ''
  name: offset
  type: integer
- container: ''
  name: groupId
  type: string
- container: ''
  name: employerName
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: employeeCount
  type: integer
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: eligible
  type: boolean
- container: ''
  name: employeeId
  type: string
- container: ''
  name: productType
  type: string
- container: ''
  name: ineligibilityReason
  type: string
- container: ''
  name: claimId
  type: string
- container: ''
  name: policyId
  type: string
- container: ''
  name: claimType
  type: string
- container: ''
  name: incidentDate
  type: date
- container: ''
  name: submissionDate
  type: dateTime
- container: ''
  name: benefitAmount
  type: decimal
- container: ''
  name: denialReason
  type: string
- container: ''
  name: coverageLevel
  type: string
- container: set
  name: dependents
  type: string
- container: ''
  name: enrollmentId
  type: string
- container: ''
  name: terminationDate
  type: date
- container: ''
  name: monthlyPremium
  type: decimal
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: dateOfBirth
  type: date
- container: ''
  name: relationship
  type: string
- container: ''
  name: faceValue
  type: decimal
property_count: 30
provider_name: aflac
provider_slug: aflac
slug: aflac-enterprise-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aflac\": \"https://aflac.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GroupList\": \"aflac:GroupList\",\n    \"items\": {\n      \"@id\": \"aflac:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"aflac:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"PolicyList\": \"aflac:PolicyList\",\n    \"EnrollmentList\": \"aflac:EnrollmentList\",\n    \"limit\": {\n      \"@id\": \"aflac:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"offset\": {\n      \"@id\": \"aflac:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Group\": \"aflac:Group\",\n    \"groupId\": {\n      \"@id\": \"aflac:group_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"employerName\": {\n      \"@id\": \"aflac:employer_name\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aflac:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"employeeCount\": {\n      \"@id\": \"aflac:employee_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"aflac:effective_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"EligibilityResponse\": \"aflac:EligibilityResponse\",\n    \"eligible\": {\n      \"@id\": \"aflac:eligible\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"employeeId\": {\n      \"@id\": \"aflac:employee_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productType\": {\n      \"@id\": \"aflac:product_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ineligibilityReason\": {\n      \"@id\": \"aflac:ineligibility_reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Claim\": \"aflac:Claim\",\n    \"claimId\": {\n      \"@id\": \"aflac:claim_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyId\": {\n    \
  \  \"@id\": \"aflac:policy_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"claimType\": {\n      \"@id\": \"aflac:claim_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentDate\": {\n      \"@id\": \"aflac:incident_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"submissionDate\": {\n      \"@id\": \"aflac:submission_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"benefitAmount\": {\n      \"@id\": \"aflac:benefit_amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"denialReason\": {\n      \"@id\": \"aflac:denial_reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EnrollmentRequest\": \"aflac:EnrollmentRequest\",\n    \"coverageLevel\": {\n      \"@id\": \"aflac:coverage_level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dependents\": {\n      \"@id\": \"aflac:dependents\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EligibilityRequest\": \"aflac:EligibilityRequest\",\n    \"ClaimRequest\": \"aflac:ClaimRequest\"\
  ,\n    \"description\": \"schema:description\",\n    \"Enrollment\": \"aflac:Enrollment\",\n    \"enrollmentId\": {\n      \"@id\": \"aflac:enrollment_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminationDate\": {\n      \"@id\": \"aflac:termination_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"monthlyPremium\": {\n      \"@id\": \"aflac:monthly_premium\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\",\n    \"Dependent\": \"aflac:Dependent\",\n    \"firstName\": {\n      \"@id\": \"aflac:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"aflac:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"aflac:date_of_birth\",\n      \"@type\": \"xsd:date\"\n    },\n    \"relationship\": {\n      \"@id\": \"aflac:relationship\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Policy\": \"aflac:Policy\",\n  \
  \  \"faceValue\": {\n      \"@id\": \"aflac:face_value\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ClaimList\": \"aflac:ClaimList\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aflac/refs/heads/main/json-ld/aflac-enterprise-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
