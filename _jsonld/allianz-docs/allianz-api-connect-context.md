---
api_specs:
- filename: allianz-api-connect.yaml
  format: yaml
  label: Allianz API Connect
  slug: allianz-api-connect
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/allianz-docs/refs/heads/main/openapi/allianz-api-connect.yaml
class_count: 21
classes:
- CertificateOfCurrency
- EmailSentResponse
- RatingFactor
- SelfServiceSessionResponse
- LeadReferralRequest
- PolicyDetailsResponse
- PriceEstimateAssistedRequest
- PriceEstimateResponse
- PolicyDetailsAssistedRequest
- LeadReferralResponse
- PolicyDetailsSelfServiceRequest
- Vehicle
- Address
- PriceEstimateEmailRequest
- RatingFactorsResponse
- PriceEstimateSelfServiceRequest
- PriceEstimateSummary
- SelfServiceEstimateResponse
- name
- description
- createdAt
context_file: json-ld/allianz-api-connect-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/allianz-docs/refs/heads/main/json-ld/allianz-api-connect-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Allianz Api Connect from Allianz.
layout: jsonld
name: Allianz Api Connect Context
namespaces:
- prefix: allianz
  uri: https://api.allianz.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: certificateId
  type: string
- container: ''
  name: policyNumber
  type: string
- container: ''
  name: insuredName
  type: string
- container: ''
  name: productType
  type: string
- container: ''
  name: coverageStart
  type: date
- container: ''
  name: coverageEnd
  type: date
- container: ''
  name: sumInsured
  type: double
- container: ''
  name: currency
  type: string
- container: ''
  name: issuedAt
  type: dateTime
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: messageId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: sentAt
  type: dateTime
- container: ''
  name: value
  type: string
- container: ''
  name: sessionId
  type: string
- container: ''
  name: sessionUrl
  type: reference
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: customerName
  type: string
- container: ''
  name: customerEmail
  type: string
- container: ''
  name: customerPhone
  type: string
- container: ''
  name: notes
  type: string
- container: ''
  name: quoteId
  type: string
- container: ''
  name: annualPremium
  type: double
- container: ''
  name: customerId
  type: string
- container: ''
  name: propertyAddress
  type: string
- container: ''
  name: estimateId
  type: string
- container: ''
  name: monthlyPremium
  type: double
- container: ''
  name: validUntil
  type: date
- container: ''
  name: paymentFrequency
  type: string
- container: ''
  name: leadId
  type: string
- container: ''
  name: assignedTo
  type: string
- container: ''
  name: redirectUrl
  type: reference
- container: ''
  name: make
  type: string
- container: ''
  name: model
  type: string
- container: ''
  name: year
  type: integer
- container: ''
  name: registration
  type: string
- container: ''
  name: street
  type: string
- container: ''
  name: suburb
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: postcode
  type: string
- container: ''
  name: basePremium
  type: double
- container: ''
  name: riskLoading
  type: double
- container: ''
  name: discounts
  type: double
- container: ''
  name: stampDuty
  type: double
- container: set
  name: factors
  type: string
- container: ''
  name: vehicle
  type: string
- container: ''
  name: driverAge
  type: integer
- container: ''
  name: estimateUrl
  type: reference
property_count: 48
provider_name: Allianz
provider_slug: allianz-docs
slug: allianz-api-connect-context
source_filename: allianz-api-connect-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"allianz\": \"https://api.allianz.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CertificateOfCurrency\": \"allianz:CertificateOfCurrency\",\n    \"EmailSentResponse\": \"allianz:EmailSentResponse\",\n    \"RatingFactor\": \"allianz:RatingFactor\",\n    \"SelfServiceSessionResponse\": \"allianz:SelfServiceSessionResponse\",\n    \"LeadReferralRequest\": \"allianz:LeadReferralRequest\",\n    \"PolicyDetailsResponse\": \"allianz:PolicyDetailsResponse\",\n    \"PriceEstimateAssistedRequest\": \"allianz:PriceEstimateAssistedRequest\",\n    \"PriceEstimateResponse\": \"allianz:PriceEstimateResponse\",\n    \"PolicyDetailsAssistedRequest\": \"allianz:PolicyDetailsAssistedRequest\",\n    \"LeadReferralResponse\": \"allianz:LeadReferralResponse\",\n    \"PolicyDetailsSelfServiceRequest\": \"allianz:PolicyDetailsSelfServiceRequest\"\
  ,\n    \"Vehicle\": \"allianz:Vehicle\",\n    \"Address\": \"allianz:Address\",\n    \"PriceEstimateEmailRequest\": \"allianz:PriceEstimateEmailRequest\",\n    \"RatingFactorsResponse\": \"allianz:RatingFactorsResponse\",\n    \"PriceEstimateSelfServiceRequest\": \"allianz:PriceEstimateSelfServiceRequest\",\n    \"PriceEstimateSummary\": \"allianz:PriceEstimateSummary\",\n    \"SelfServiceEstimateResponse\": \"allianz:SelfServiceEstimateResponse\",\n    \"certificateId\": {\n      \"@id\": \"allianz:certificate_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyNumber\": {\n      \"@id\": \"allianz:policy_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"insuredName\": {\n      \"@id\": \"allianz:insured_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productType\": {\n      \"@id\": \"allianz:product_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coverageStart\": {\n      \"@id\": \"allianz:coverage_start\",\n      \"@type\": \"xsd:date\"\n    },\n  \
  \  \"coverageEnd\": {\n      \"@id\": \"allianz:coverage_end\",\n      \"@type\": \"xsd:date\"\n    },\n    \"sumInsured\": {\n      \"@id\": \"allianz:sum_insured\",\n      \"@type\": \"xsd:double\"\n    },\n    \"currency\": {\n      \"@id\": \"allianz:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuedAt\": {\n      \"@id\": \"allianz:issued_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"allianz:download_url\",\n      \"@type\": \"@id\"\n    },\n    \"messageId\": {\n      \"@id\": \"allianz:message_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"allianz:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sentAt\": {\n      \"@id\": \"allianz:sent_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"name\": \"schema:name\",\n    \"value\": {\n      \"@id\": \"allianz:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"sessionId\"\
  : {\n      \"@id\": \"allianz:session_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionUrl\": {\n      \"@id\": \"allianz:session_url\",\n      \"@type\": \"@id\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"allianz:expires_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"customerName\": {\n      \"@id\": \"allianz:customer_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerEmail\": {\n      \"@id\": \"allianz:customer_email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerPhone\": {\n      \"@id\": \"allianz:customer_phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notes\": {\n      \"@id\": \"allianz:notes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quoteId\": {\n      \"@id\": \"allianz:quote_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"annualPremium\": {\n      \"@id\": \"allianz:annual_premium\",\n      \"@type\": \"xsd:double\"\n    },\n    \"customerId\": {\n      \"@id\": \"allianz:customer_id\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"propertyAddress\": {\n      \"@id\": \"allianz:property_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"estimateId\": {\n      \"@id\": \"allianz:estimate_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"monthlyPremium\": {\n      \"@id\": \"allianz:monthly_premium\",\n      \"@type\": \"xsd:double\"\n    },\n    \"validUntil\": {\n      \"@id\": \"allianz:valid_until\",\n      \"@type\": \"xsd:date\"\n    },\n    \"paymentFrequency\": {\n      \"@id\": \"allianz:payment_frequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"leadId\": {\n      \"@id\": \"allianz:lead_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"assignedTo\": {\n      \"@id\": \"allianz:assigned_to\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redirectUrl\": {\n      \"@id\": \"allianz:redirect_url\",\n      \"@type\": \"@id\"\n    },\n    \"make\": {\n      \"@id\": \"allianz:make\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"model\": {\n      \"@id\": \"allianz:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"year\": {\n      \"@id\": \"allianz:year\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"registration\": {\n      \"@id\": \"allianz:registration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"street\": {\n      \"@id\": \"allianz:street\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suburb\": {\n      \"@id\": \"allianz:suburb\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"allianz:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postcode\": {\n      \"@id\": \"allianz:postcode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"basePremium\": {\n      \"@id\": \"allianz:base_premium\",\n      \"@type\": \"xsd:double\"\n    },\n    \"riskLoading\": {\n      \"@id\": \"allianz:risk_loading\",\n      \"@type\": \"xsd:double\"\n    },\n    \"discounts\": {\n      \"@id\": \"allianz:discounts\",\n      \"@type\": \"xsd:double\"\n\
  \    },\n    \"stampDuty\": {\n      \"@id\": \"allianz:stamp_duty\",\n      \"@type\": \"xsd:double\"\n    },\n    \"factors\": {\n      \"@id\": \"allianz:factors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vehicle\": {\n      \"@id\": \"allianz:vehicle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"driverAge\": {\n      \"@id\": \"allianz:driver_age\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"estimateUrl\": {\n      \"@id\": \"allianz:estimate_url\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/allianz-docs/refs/heads/main/json-ld/allianz-api-connect-context.jsonld
tags:
- Financial Services
- Insurance
- Asset Management
- JSON-LD
- Linked Data
- Semantic Web
---
