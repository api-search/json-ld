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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"availity\": \"https://availity.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Availity Eligibility Response\": \"availity:Availity Eligibility Response\",\n    \"id\": {\n      \"@id\": \"availity:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"controlNumber\": {\n      \"@id\": \"availity:controlNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedDate\": {\n      \"@id\": \"availity:requestedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"serviceDate\": {\n      \"@id\": \"availity:serviceDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"subscriber\": {\n      \"@id\": \"availity:subscriber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payer\": {\n      \"@id\": \"availity:payer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coverages\": {\n      \"@id\": \"availity:coverages\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"planInformation\": {\n      \"@id\": \"availity:planInformation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memberId\": {\n      \"@id\": \"availity:memberId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"availity:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"availity:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"availity:dateOfBirth\",\n      \"@type\": \"xsd:date\"\n    },\n    \"gender\": {\n      \"@id\": \"availity:gender\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupNumber\": {\n      \"@id\": \"availity:groupNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupName\": {\n      \"@id\": \"availity:groupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"serviceTypeCodes\": {\n      \"@id\": \"availity:serviceTypeCodes\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceTypeNames\": {\n      \"@id\": \"availity:serviceTypeNames\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coverageStatus\": {\n      \"@id\": \"availity:coverageStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"availity:effectiveDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"availity:expirationDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"benefits\": {\n      \"@id\": \"availity:benefits\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"availity:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coverageLevel\": {\n      \"@id\": \"availity:coverageLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"benefitAmount\": {\n      \"@id\": \"availity:benefitAmount\",\n      \"@type\": \"@id\"\n    },\n\
  \    \"value\": {\n      \"@id\": \"availity:value\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"availity:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"benefitPercent\": {\n      \"@id\": \"availity:benefitPercent\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"inPlanNetworkIndicator\": {\n      \"@id\": \"availity:inPlanNetworkIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeQualifier\": {\n      \"@id\": \"availity:timeQualifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"planName\": {\n      \"@id\": \"availity:planName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"planBeginDate\": {\n      \"@id\": \"availity:planBeginDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"planEndDate\": {\n      \"@id\": \"availity:planEndDate\",\n      \"@type\": \"xsd:date\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-ld/availity-availity-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
