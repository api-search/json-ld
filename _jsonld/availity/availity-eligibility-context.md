---
class_count: 15
classes:
- PlanInformation
- Subscriber
- Payer
- Benefit
- PayerList
- EligibilityResponse
- EligibilityList
- EligibilityRequest
- EligibilityError
- SubscriberInfo
- Provider
- Coverage
- Dependent
- PayerInfo
- name
context_file: json-ld/availity-eligibility-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-ld/availity-eligibility-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Availity Eligibility from availity.
layout: jsonld
name: Availity Eligibility Context
namespaces:
- prefix: availity
  uri: https://availity.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: planName
  type: string
- container: ''
  name: groupName
  type: string
- container: ''
  name: groupNumber
  type: string
- container: ''
  name: planBeginDate
  type: date
- container: ''
  name: planEndDate
  type: date
- container: ''
  name: memberId
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
  name: gender
  type: string
- container: ''
  name: ssn
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: coverageLevel
  type: string
- container: ''
  name: benefitAmount
  type: reference
- container: ''
  name: value
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: benefitPercent
  type: decimal
- container: ''
  name: inPlanNetworkIndicator
  type: string
- container: ''
  name: timeQualifier
  type: string
- container: set
  name: data
  type: reference
- container: ''
  name: eligibilityUrl
  type: string
- container: set
  name: supportedTransactions
  type: string
- container: ''
  name: controlNumber
  type: string
- container: ''
  name: requestedDate
  type: dateTime
- container: ''
  name: serviceDate
  type: date
- container: ''
  name: subscriber
  type: string
- container: ''
  name: payer
  type: string
- container: set
  name: coverages
  type: string
- container: ''
  name: planInformation
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: offset
  type: integer
- container: ''
  name: provider
  type: string
- container: ''
  name: dependent
  type: string
- container: ''
  name: encounter
  type: reference
- container: set
  name: serviceTypeCodes
  type: string
- container: ''
  name: beginningDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: rejectCode
  type: string
- container: ''
  name: rejectReason
  type: string
- container: ''
  name: followUpAction
  type: string
- container: ''
  name: npi
  type: string
- container: ''
  name: organizationName
  type: string
- container: ''
  name: taxId
  type: string
- container: ''
  name: serviceProviderNumber
  type: string
- container: set
  name: serviceTypeNames
  type: string
- container: ''
  name: insuranceType
  type: string
- container: ''
  name: planCoverage
  type: string
- container: ''
  name: coverageStatus
  type: string
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: expirationDate
  type: date
- container: set
  name: benefits
  type: string
- container: ''
  name: relationship
  type: string
- container: ''
  name: address
  type: reference
- container: ''
  name: address1
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: postalCode
  type: string
property_count: 58
provider_name: availity
provider_slug: availity
slug: availity-eligibility-context
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
