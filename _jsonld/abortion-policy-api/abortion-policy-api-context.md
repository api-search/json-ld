---
class_count: 4
classes:
- WaitingPeriods
- MinorsRestrictions
- InsuranceCoverage
- GestationalLimits
context_file: json-ld/abortion-policy-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/abortion-policy-api/refs/heads/main/json-ld/abortion-policy-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Abortion Policy Api from Abortion Policy API.
layout: jsonld
name: Abortion Policy Api Context
namespaces:
- prefix: abortion
  uri: https://abortionpolicyapi.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: waitingPeriodHours
  type: integer
- container: ''
  name: counselingVisits
  type: integer
- container: ''
  name: exceptionHealth
  type: string
- container: ''
  name: waitingPeriodNotes
  type: string
- container: ''
  name: counselingWaivedCondition
  type: string
- container: ''
  name: LastUpdated
  type: string
- container: ''
  name: belowAge
  type: integer
- container: ''
  name: parentsRequired
  type: integer
- container: ''
  name: parentalConsentRequired
  type: boolean
- container: ''
  name: parentalNotificationRequired
  type: boolean
- container: ''
  name: judicialBypassAvailable
  type: boolean
- container: ''
  name: allowsMinorToConsent
  type: boolean
- container: ''
  name: requiresCoverage
  type: boolean
- container: ''
  name: privateCoverageNoRestrictions
  type: boolean
- container: ''
  name: privateExceptionLife
  type: boolean
- container: ''
  name: privateExceptionHealth
  type: string
- container: ''
  name: privateExceptionFetal
  type: string
- container: ''
  name: privateExceptionRapeOrIncest
  type: boolean
- container: ''
  name: exchangeCoverageNoRestrictions
  type: boolean
- container: ''
  name: exchangeExceptionLife
  type: boolean
- container: ''
  name: exchangeExceptionHealth
  type: string
- container: ''
  name: exchangeExceptionFetal
  type: string
- container: ''
  name: exchangeExceptionRapeOrIncest
  type: boolean
- container: ''
  name: exchangeForbidsCoverage
  type: boolean
- container: ''
  name: medicaidCoverageProviderPatientDecision
  type: boolean
- container: ''
  name: medicaidExceptionLife
  type: boolean
- container: ''
  name: medicaidExceptionHealth
  type: string
- container: ''
  name: medicaidExceptionFetal
  type: string
- container: ''
  name: medicaidExceptionRapeOrIncest
  type: boolean
- container: ''
  name: bannedAfterWeeksSinceLmp
  type: integer
- container: ''
  name: exceptionLife
  type: boolean
- container: ''
  name: exceptionFetal
  type: string
- container: ''
  name: exceptionRapeOrIncest
  type: boolean
property_count: 33
provider_name: Abortion Policy API
provider_slug: abortion-policy-api
slug: abortion-policy-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"abortion\": \"https://abortionpolicyapi.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WaitingPeriods\": \"abortion:WaitingPeriods\",\n    \"waitingPeriodHours\": {\n      \"@id\": \"abortion:waiting_period_hours\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"counselingVisits\": {\n      \"@id\": \"abortion:counseling_visits\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"exceptionHealth\": {\n      \"@id\": \"abortion:exception_health\",\n      \"@type\": \"xsd:string\"\n    },\n    \"waitingPeriodNotes\": {\n      \"@id\": \"abortion:waiting_period_notes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"counselingWaivedCondition\": {\n      \"@id\": \"abortion:counseling_waived_condition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastUpdated\": {\n      \"@id\": \"abortion:Last Updated\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"MinorsRestrictions\": \"abortion:MinorsRestrictions\",\n    \"belowAge\": {\n      \"@id\": \"abortion:below_age\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"parentsRequired\": {\n      \"@id\": \"abortion:parents_required\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"parentalConsentRequired\": {\n      \"@id\": \"abortion:parental_consent_required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"parentalNotificationRequired\": {\n      \"@id\": \"abortion:parental_notification_required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"judicialBypassAvailable\": {\n      \"@id\": \"abortion:judicial_bypass_available\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"allowsMinorToConsent\": {\n      \"@id\": \"abortion:allows_minor_to_consent\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"InsuranceCoverage\": \"abortion:InsuranceCoverage\",\n    \"requiresCoverage\": {\n      \"@id\": \"abortion:requires_coverage\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"privateCoverageNoRestrictions\": {\n      \"@id\": \"abortion:private_coverage_no_restrictions\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"privateExceptionLife\": {\n      \"@id\": \"abortion:private_exception_life\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"privateExceptionHealth\": {\n      \"@id\": \"abortion:private_exception_health\",\n      \"@type\": \"xsd:string\"\n    },\n    \"privateExceptionFetal\": {\n      \"@id\": \"abortion:private_exception_fetal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"privateExceptionRapeOrIncest\": {\n      \"@id\": \"abortion:private_exception_rape_or_incest\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"exchangeCoverageNoRestrictions\": {\n      \"@id\": \"abortion:exchange_coverage_no_restrictions\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"exchangeExceptionLife\": {\n      \"@id\": \"abortion:exchange_exception_life\",\n      \"@type\": \"xsd:boolean\"\n  \
  \  },\n    \"exchangeExceptionHealth\": {\n      \"@id\": \"abortion:exchange_exception_health\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exchangeExceptionFetal\": {\n      \"@id\": \"abortion:exchange_exception_fetal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exchangeExceptionRapeOrIncest\": {\n      \"@id\": \"abortion:exchange_exception_rape_or_incest\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"exchangeForbidsCoverage\": {\n      \"@id\": \"abortion:exchange_forbids_coverage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"medicaidCoverageProviderPatientDecision\": {\n      \"@id\": \"abortion:medicaid_coverage_provider_patient_decision\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"medicaidExceptionLife\": {\n      \"@id\": \"abortion:medicaid_exception_life\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"medicaidExceptionHealth\": {\n      \"@id\": \"abortion:medicaid_exception_health\",\n      \"@type\": \"xsd:string\"\n    },\n    \"medicaidExceptionFetal\"\
  : {\n      \"@id\": \"abortion:medicaid_exception_fetal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"medicaidExceptionRapeOrIncest\": {\n      \"@id\": \"abortion:medicaid_exception_rape_or_incest\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"GestationalLimits\": \"abortion:GestationalLimits\",\n    \"bannedAfterWeeksSinceLmp\": {\n      \"@id\": \"abortion:banned_after_weeks_since_LMP\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"exceptionLife\": {\n      \"@id\": \"abortion:exception_life\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"exceptionFetal\": {\n      \"@id\": \"abortion:exception_fetal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exceptionRapeOrIncest\": {\n      \"@id\": \"abortion:exception_rape_or_incest\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/abortion-policy-api/refs/heads/main/json-ld/abortion-policy-api-context.jsonld
tags:
- Abortion
- Policies
- Healthcare
- Government
- JSON-LD
- Linked Data
- Semantic Web
---
