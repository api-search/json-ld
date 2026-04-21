---
class_count: 2
classes:
- Availity Eligibility Response
- name
context_file: json-ld/availity-availity-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-ld/availity-availity-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Availity Availity from availity.
layout: jsonld
name: Availity Availity Context
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
  name: id
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
  name: groupNumber
  type: string
- container: ''
  name: groupName
  type: string
- container: set
  name: serviceTypeCodes
  type: string
- container: set
  name: serviceTypeNames
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
- container: ''
  name: planName
  type: string
- container: ''
  name: planBeginDate
  type: date
- container: ''
  name: planEndDate
  type: date
property_count: 32
provider_name: availity
provider_slug: availity
slug: availity-availity-context
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
