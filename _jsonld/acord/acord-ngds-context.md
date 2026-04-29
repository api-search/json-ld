---
class_count: 19
classes:
- Party
- PolicyList
- CoverageRequest
- Address
- ACORD Policy
- UnderwritingSubmissionResponse
- PolicyRequest
- PolicyUpdate
- Contact
- PartyRequest
- ClaimRequest
- Coverage
- PartyList
- ClaimList
- UnderwritingSubmission
- ACORD Claim
- createdAt
- updatedAt
- description
context_file: json-ld/acord-ngds-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-ld/acord-ngds-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Acord Ngds from ACORD.
layout: jsonld
name: Acord Ngds Context
namespaces:
- prefix: acord
  uri: https://www.acord.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: partyId
  type: string
- container: ''
  name: partyType
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: organizationName
  type: string
- container: ''
  name: taxId
  type: string
- container: ''
  name: address
  type: string
- container: set
  name: contacts
  type: string
- container: set
  name: data
  type: string
- container: ''
  name: pagination
  type: string
- container: ''
  name: coverageType
  type: string
- container: ''
  name: limit
  type: decimal
- container: ''
  name: deductible
  type: decimal
- container: ''
  name: premium
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: street1
  type: string
- container: ''
  name: street2
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
- container: ''
  name: country
  type: string
- container: ''
  name: policyId
  type: string
- container: ''
  name: policyNumber
  type: string
- container: ''
  name: lineOfBusiness
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: expirationDate
  type: date
- container: ''
  name: premiumAmount
  type: decimal
- container: ''
  name: insuredParty
  type: string
- container: set
  name: coverages
  type: string
- container: set
  name: endorsements
  type: string
- container: ''
  name: submissionId
  type: string
- container: ''
  name: submittedAt
  type: dateTime
- container: ''
  name: notes
  type: string
- container: ''
  name: endorsementNumber
  type: string
- container: ''
  name: contactType
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: lossDate
  type: date
- container: ''
  name: lossDescription
  type: string
- container: ''
  name: lossLocation
  type: string
- container: ''
  name: claimant
  type: string
- container: ''
  name: estimatedLossAmount
  type: decimal
- container: ''
  name: coverageId
  type: string
- container: ''
  name: applicant
  type: string
- container: ''
  name: requestedEffectiveDate
  type: date
- container: ''
  name: requestedExpirationDate
  type: date
- container: ''
  name: riskDetails
  type: string
- container: ''
  name: claimId
  type: string
- container: ''
  name: claimNumber
  type: string
- container: ''
  name: reportedDate
  type: date
- container: ''
  name: lossType
  type: string
- container: ''
  name: adjuster
  type: string
- container: ''
  name: reserveAmount
  type: decimal
- container: ''
  name: paidAmount
  type: decimal
- container: set
  name: payments
  type: string
property_count: 55
provider_name: ACORD
provider_slug: acord
slug: acord-ngds-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"acord\": \"https://www.acord.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Party\": \"acord:Party\",\n    \"PolicyList\": \"acord:PolicyList\",\n    \"CoverageRequest\": \"acord:CoverageRequest\",\n    \"Address\": \"acord:Address\",\n    \"ACORD Policy\": \"acord:ACORD Policy\",\n    \"UnderwritingSubmissionResponse\": \"acord:UnderwritingSubmissionResponse\",\n    \"PolicyRequest\": \"acord:PolicyRequest\",\n    \"PolicyUpdate\": \"acord:PolicyUpdate\",\n    \"Contact\": \"acord:Contact\",\n    \"PartyRequest\": \"acord:PartyRequest\",\n    \"ClaimRequest\": \"acord:ClaimRequest\",\n    \"Coverage\": \"acord:Coverage\",\n    \"PartyList\": \"acord:PartyList\",\n    \"ClaimList\": \"acord:ClaimList\",\n    \"UnderwritingSubmission\": \"acord:UnderwritingSubmission\",\n    \"ACORD Claim\": \"acord:ACORD Claim\"\
  ,\n    \"partyId\": {\n      \"@id\": \"acord:partyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partyType\": {\n      \"@id\": \"acord:partyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"acord:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"acord:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationName\": {\n      \"@id\": \"acord:organizationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxId\": {\n      \"@id\": \"acord:taxId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"acord:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contacts\": {\n      \"@id\": \"acord:contacts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"acord:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pagination\": {\n      \"@id\": \"acord:pagination\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"coverageType\": {\n      \"@id\": \"acord:coverageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"acord:limit\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"deductible\": {\n      \"@id\": \"acord:deductible\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"premium\": {\n      \"@id\": \"acord:premium\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"acord:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"street1\": {\n      \"@id\": \"acord:street1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"street2\": {\n      \"@id\": \"acord:street2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"acord:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"acord:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"acord:postalCode\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"country\": {\n      \"@id\": \"acord:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyId\": {\n      \"@id\": \"acord:policyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyNumber\": {\n      \"@id\": \"acord:policyNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lineOfBusiness\": {\n      \"@id\": \"acord:lineOfBusiness\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"acord:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"acord:effectiveDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"acord:expirationDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"premiumAmount\": {\n      \"@id\": \"acord:premiumAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"insuredParty\": {\n      \"@id\": \"acord:insuredParty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coverages\": {\n      \"@id\": \"acord:coverages\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endorsements\": {\n      \"@id\": \"acord:endorsements\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\",\n    \"submissionId\": {\n      \"@id\": \"acord:submissionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submittedAt\": {\n      \"@id\": \"acord:submittedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"notes\": {\n      \"@id\": \"acord:notes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endorsementNumber\": {\n      \"@id\": \"acord:endorsementNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"contactType\": {\n      \"@id\": \"acord:contactType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"acord:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lossDate\": {\n      \"@id\"\
  : \"acord:lossDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"lossDescription\": {\n      \"@id\": \"acord:lossDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lossLocation\": {\n      \"@id\": \"acord:lossLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"claimant\": {\n      \"@id\": \"acord:claimant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"estimatedLossAmount\": {\n      \"@id\": \"acord:estimatedLossAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"coverageId\": {\n      \"@id\": \"acord:coverageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicant\": {\n      \"@id\": \"acord:applicant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedEffectiveDate\": {\n      \"@id\": \"acord:requestedEffectiveDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"requestedExpirationDate\": {\n      \"@id\": \"acord:requestedExpirationDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"riskDetails\": {\n      \"@id\": \"acord:riskDetails\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"claimId\": {\n      \"@id\": \"acord:claimId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"claimNumber\": {\n      \"@id\": \"acord:claimNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportedDate\": {\n      \"@id\": \"acord:reportedDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"lossType\": {\n      \"@id\": \"acord:lossType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adjuster\": {\n      \"@id\": \"acord:adjuster\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reserveAmount\": {\n      \"@id\": \"acord:reserveAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"paidAmount\": {\n      \"@id\": \"acord:paidAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"payments\": {\n      \"@id\": \"acord:payments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-ld/acord-ngds-context.jsonld
tags:
- Claims
- Insurance
- Policy
- Standards
- Underwriting
- JSON-LD
- Linked Data
- Semantic Web
---
