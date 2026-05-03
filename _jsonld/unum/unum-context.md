---
api_specs:
- filename: unum-hr-connect-openapi.yml
  format: yaml
  label: Unum HR Connect API
  slug: hr-connect
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unum/refs/heads/main/openapi/unum-hr-connect-openapi.yml
class_count: 5
classes:
- Member
- Coverage
- LeaveRequest
- EoiSubmission
- BillingInvoice
context_file: json-ld/unum-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/unum/refs/heads/main/json-ld/unum-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Unum from Unum.
layout: jsonld
name: Unum Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: unum
  uri: https://api.unum.com/v1/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: memberId
  type: string
- container: ''
  name: groupId
  type: string
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
  name: employeeId
  type: string
- container: ''
  name: hireDate
  type: date
- container: ''
  name: employmentStatus
  type: string
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: terminationDate
  type: date
- container: set
  name: coverages
  type: ''
- container: ''
  name: productType
  type: string
- container: ''
  name: planCode
  type: string
- container: ''
  name: benefitAmount
  type: decimal
- container: ''
  name: coverageLevel
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: leaveType
  type: string
- container: ''
  name: startDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: returnToWorkDate
  type: date
- container: ''
  name: submissionId
  type: string
- container: ''
  name: requestedBenefitAmount
  type: decimal
- container: ''
  name: invoiceId
  type: string
- container: ''
  name: totalPremium
  type: decimal
- container: ''
  name: billingPeriodStart
  type: date
- container: ''
  name: billingPeriodEnd
  type: date
- container: ''
  name: dueDate
  type: date
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: status
  type: string
property_count: 30
provider_name: Unum
provider_slug: unum
slug: unum-context
source_filename: unum-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"unum\": \"https://api.unum.com/v1/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Member\": \"schema:Person\",\n    \"memberId\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"groupId\": { \"@id\": \"unum:groupId\", \"@type\": \"xsd:string\" },\n    \"firstName\": { \"@id\": \"schema:givenName\", \"@type\": \"xsd:string\" },\n    \"lastName\": { \"@id\": \"schema:familyName\", \"@type\": \"xsd:string\" },\n    \"dateOfBirth\": { \"@id\": \"schema:birthDate\", \"@type\": \"xsd:date\" },\n    \"employeeId\": { \"@id\": \"schema:employeeID\", \"@type\": \"xsd:string\" },\n    \"hireDate\": { \"@id\": \"schema:startDate\", \"@type\": \"xsd:date\" },\n    \"employmentStatus\": { \"@id\": \"schema:employmentType\", \"@type\": \"xsd:string\" },\n    \"effectiveDate\": { \"@id\": \"unum:effectiveDate\", \"@type\": \"xsd:date\" },\n    \"terminationDate\"\
  : { \"@id\": \"unum:terminationDate\", \"@type\": \"xsd:date\" },\n    \"coverages\": { \"@id\": \"unum:coverages\", \"@container\": \"@set\" },\n\n    \"Coverage\": \"schema:InsurancePolicy\",\n    \"productType\": { \"@id\": \"schema:additionalType\", \"@type\": \"xsd:string\" },\n    \"planCode\": { \"@id\": \"unum:planCode\", \"@type\": \"xsd:string\" },\n    \"benefitAmount\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n    \"coverageLevel\": { \"@id\": \"unum:coverageLevel\", \"@type\": \"xsd:string\" },\n\n    \"LeaveRequest\": \"schema:EventReservation\",\n    \"requestId\": { \"@id\": \"schema:reservationId\", \"@type\": \"xsd:string\" },\n    \"leaveType\": { \"@id\": \"unum:leaveType\", \"@type\": \"xsd:string\" },\n    \"startDate\": { \"@id\": \"schema:startDate\", \"@type\": \"xsd:date\" },\n    \"endDate\": { \"@id\": \"schema:endDate\", \"@type\": \"xsd:date\" },\n    \"returnToWorkDate\": { \"@id\": \"unum:returnToWorkDate\", \"@type\": \"xsd:date\" },\n\
  \n    \"EoiSubmission\": \"schema:MedicalCondition\",\n    \"submissionId\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"requestedBenefitAmount\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n\n    \"BillingInvoice\": \"schema:Invoice\",\n    \"invoiceId\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"totalPremium\": { \"@id\": \"schema:totalPrice\", \"@type\": \"xsd:decimal\" },\n    \"billingPeriodStart\": { \"@id\": \"schema:billingStart\", \"@type\": \"xsd:date\" },\n    \"billingPeriodEnd\": { \"@id\": \"schema:billingEnd\", \"@type\": \"xsd:date\" },\n    \"dueDate\": { \"@id\": \"schema:paymentDueDate\", \"@type\": \"xsd:date\" },\n\n    \"createdAt\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"updatedAt\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n    \"status\": { \"@id\": \"unum:status\", \"@type\": \"xsd:string\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/unum/refs/heads/main/json-ld/unum-context.jsonld
tags:
- Insurance
- Benefits Administration
- HR Integration
- Disability Insurance
- Life Insurance
- JSON-LD
- Linked Data
- Semantic Web
---
