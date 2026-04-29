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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"availity\": \"https://availity.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PlanInformation\": \"availity:PlanInformation\",\n    \"Subscriber\": \"availity:Subscriber\",\n    \"Payer\": \"availity:Payer\",\n    \"Benefit\": \"availity:Benefit\",\n    \"PayerList\": \"availity:PayerList\",\n    \"EligibilityResponse\": \"availity:EligibilityResponse\",\n    \"EligibilityList\": \"availity:EligibilityList\",\n    \"EligibilityRequest\": \"availity:EligibilityRequest\",\n    \"EligibilityError\": \"availity:EligibilityError\",\n    \"SubscriberInfo\": \"availity:SubscriberInfo\",\n    \"Provider\": \"availity:Provider\",\n    \"Coverage\": \"availity:Coverage\",\n    \"Dependent\": \"availity:Dependent\",\n    \"PayerInfo\": \"availity:PayerInfo\",\n    \"planName\": {\n      \"@id\": \"availity:planName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"groupName\": {\n      \"@id\": \"availity:groupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupNumber\": {\n      \"@id\": \"availity:groupNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"planBeginDate\": {\n      \"@id\": \"availity:planBeginDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"planEndDate\": {\n      \"@id\": \"availity:planEndDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"memberId\": {\n      \"@id\": \"availity:memberId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"availity:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"availity:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"availity:dateOfBirth\",\n      \"@type\": \"xsd:date\"\n    },\n    \"gender\": {\n      \"@id\": \"availity:gender\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ssn\": {\n      \"\
  @id\": \"availity:ssn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"availity:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"code\": {\n      \"@id\": \"availity:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coverageLevel\": {\n      \"@id\": \"availity:coverageLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"benefitAmount\": {\n      \"@id\": \"availity:benefitAmount\",\n      \"@type\": \"@id\"\n    },\n    \"value\": {\n      \"@id\": \"availity:value\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"availity:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"benefitPercent\": {\n      \"@id\": \"availity:benefitPercent\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"inPlanNetworkIndicator\": {\n      \"@id\": \"availity:inPlanNetworkIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeQualifier\": {\n      \"@id\": \"availity:timeQualifier\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"availity:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"eligibilityUrl\": {\n      \"@id\": \"availity:eligibilityUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supportedTransactions\": {\n      \"@id\": \"availity:supportedTransactions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"controlNumber\": {\n      \"@id\": \"availity:controlNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedDate\": {\n      \"@id\": \"availity:requestedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"serviceDate\": {\n      \"@id\": \"availity:serviceDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"subscriber\": {\n      \"@id\": \"availity:subscriber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payer\": {\n      \"@id\": \"availity:payer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coverages\": {\n      \"@id\"\
  : \"availity:coverages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"planInformation\": {\n      \"@id\": \"availity:planInformation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"availity:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"offset\": {\n      \"@id\": \"availity:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"provider\": {\n      \"@id\": \"availity:provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dependent\": {\n      \"@id\": \"availity:dependent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encounter\": {\n      \"@id\": \"availity:encounter\",\n      \"@type\": \"@id\"\n    },\n    \"serviceTypeCodes\": {\n      \"@id\": \"availity:serviceTypeCodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"beginningDate\": {\n      \"@id\": \"availity:beginningDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\"\
  : \"availity:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"rejectCode\": {\n      \"@id\": \"availity:rejectCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rejectReason\": {\n      \"@id\": \"availity:rejectReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"followUpAction\": {\n      \"@id\": \"availity:followUpAction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"npi\": {\n      \"@id\": \"availity:npi\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationName\": {\n      \"@id\": \"availity:organizationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxId\": {\n      \"@id\": \"availity:taxId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceProviderNumber\": {\n      \"@id\": \"availity:serviceProviderNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceTypeNames\": {\n      \"@id\": \"availity:serviceTypeNames\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"insuranceType\": {\n  \
  \    \"@id\": \"availity:insuranceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"planCoverage\": {\n      \"@id\": \"availity:planCoverage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coverageStatus\": {\n      \"@id\": \"availity:coverageStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"availity:effectiveDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"availity:expirationDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"benefits\": {\n      \"@id\": \"availity:benefits\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relationship\": {\n      \"@id\": \"availity:relationship\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"availity:address\",\n      \"@type\": \"@id\"\n    },\n    \"address1\": {\n      \"@id\": \"availity:address1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"availity:city\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"availity:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"availity:postalCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-ld/availity-eligibility-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
