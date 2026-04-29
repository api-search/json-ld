---
api_specs:
- filename: merge-hris-api-openapi.yaml
  format: yaml
  label: Merge HRIS API
  slug: hris-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-hris-api-openapi.yaml
- filename: merge-ats-api-openapi.yaml
  format: yaml
  label: Merge ATS API
  slug: ats-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-ats-api-openapi.yaml
- filename: merge-accounting-api-openapi.yaml
  format: yaml
  label: Merge Accounting API
  slug: accounting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-accounting-api-openapi.yaml
- filename: merge-ticketing-api-openapi.yaml
  format: yaml
  label: Merge Ticketing API
  slug: ticketing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-ticketing-api-openapi.yaml
- filename: merge-crm-api-openapi.yaml
  format: yaml
  label: Merge CRM API
  slug: crm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-crm-api-openapi.yaml
- filename: merge-file-storage-api-openapi.yaml
  format: yaml
  label: Merge File Storage API
  slug: file-storage-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-file-storage-api-openapi.yaml
class_count: 11
classes:
- Candidate
- Application
- Job
- Offer
- ScheduledInterview
- JobInterviewStage
- Scorecard
- Department
- Office
- Activity
- RemoteUser
context_file: json-ld/merge-ats-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/json-ld/merge-ats-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Merge Ats Api from Merge.
layout: jsonld
name: Merge Ats Api Context
namespaces:
- prefix: merge
  uri: https://api.merge.dev/schema/
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
  name: remoteId
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: company
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: isPrivate
  type: boolean
- container: ''
  name: canEmail
  type: boolean
- container: set
  name: emailAddresses
  type: ''
- container: set
  name: phoneNumbers
  type: ''
- container: set
  name: tags
  type: string
- container: set
  name: applications
  type: reference
- container: ''
  name: candidate
  type: reference
- container: ''
  name: job
  type: reference
- container: ''
  name: appliedAt
  type: dateTime
- container: ''
  name: rejectedAt
  type: dateTime
- container: ''
  name: source
  type: string
- container: ''
  name: currentStage
  type: reference
- container: ''
  name: name
  type: string
- container: ''
  name: status
  type: string
- container: set
  name: departments
  type: reference
- container: set
  name: offices
  type: reference
- container: set
  name: hiringManagers
  type: reference
- container: set
  name: recruiters
  type: reference
- container: ''
  name: overallRecommendation
  type: string
- container: ''
  name: activityType
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: body
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: accessRole
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
- container: ''
  name: remoteWasDeleted
  type: boolean
property_count: 33
provider_name: Merge
provider_slug: merge
slug: merge-ats-api-context
source_filename: merge-ats-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"merge\": \"https://api.merge.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Candidate\": \"merge:Candidate\",\n    \"Application\": \"merge:Application\",\n    \"Job\": \"merge:Job\",\n    \"Offer\": \"merge:Offer\",\n    \"ScheduledInterview\": \"merge:ScheduledInterview\",\n    \"JobInterviewStage\": \"merge:JobInterviewStage\",\n    \"Scorecard\": \"merge:Scorecard\",\n    \"Department\": \"merge:Department\",\n    \"Office\": \"merge:Office\",\n    \"Activity\": \"merge:Activity\",\n    \"RemoteUser\": \"merge:RemoteUser\",\n\n    \"id\": { \"@id\": \"dcterms:identifier\", \"@type\": \"xsd:string\" },\n    \"remoteId\": { \"@id\": \"merge:remote_id\", \"@type\": \"xsd:string\" },\n    \"firstName\": { \"@id\": \"schema:givenName\", \"@type\": \"xsd:string\" },\n    \"lastName\": { \"@id\": \"schema:familyName\"\
  , \"@type\": \"xsd:string\" },\n    \"company\": { \"@id\": \"merge:company\", \"@type\": \"xsd:string\" },\n    \"title\": { \"@id\": \"schema:jobTitle\", \"@type\": \"xsd:string\" },\n    \"isPrivate\": { \"@id\": \"merge:is_private\", \"@type\": \"xsd:boolean\" },\n    \"canEmail\": { \"@id\": \"merge:can_email\", \"@type\": \"xsd:boolean\" },\n    \"emailAddresses\": { \"@id\": \"merge:email_addresses\", \"@container\": \"@set\" },\n    \"phoneNumbers\": { \"@id\": \"merge:phone_numbers\", \"@container\": \"@set\" },\n    \"tags\": { \"@id\": \"merge:tags\", \"@container\": \"@set\", \"@type\": \"xsd:string\" },\n    \"applications\": { \"@id\": \"merge:applications\", \"@container\": \"@set\", \"@type\": \"@id\" },\n    \"candidate\": { \"@id\": \"merge:candidate\", \"@type\": \"@id\" },\n    \"job\": { \"@id\": \"merge:job\", \"@type\": \"@id\" },\n    \"appliedAt\": { \"@id\": \"merge:applied_at\", \"@type\": \"xsd:dateTime\" },\n    \"rejectedAt\": { \"@id\": \"merge:rejected_at\"\
  , \"@type\": \"xsd:dateTime\" },\n    \"source\": { \"@id\": \"merge:source\", \"@type\": \"xsd:string\" },\n    \"currentStage\": { \"@id\": \"merge:current_stage\", \"@type\": \"@id\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"status\": { \"@id\": \"merge:status\", \"@type\": \"xsd:string\" },\n    \"departments\": { \"@id\": \"merge:departments\", \"@container\": \"@set\", \"@type\": \"@id\" },\n    \"offices\": { \"@id\": \"merge:offices\", \"@container\": \"@set\", \"@type\": \"@id\" },\n    \"hiringManagers\": { \"@id\": \"merge:hiring_managers\", \"@container\": \"@set\", \"@type\": \"@id\" },\n    \"recruiters\": { \"@id\": \"merge:recruiters\", \"@container\": \"@set\", \"@type\": \"@id\" },\n    \"overallRecommendation\": { \"@id\": \"merge:overall_recommendation\", \"@type\": \"xsd:string\" },\n    \"activityType\": { \"@id\": \"merge:activity_type\", \"@type\": \"xsd:string\" },\n    \"subject\": { \"@id\": \"merge:subject\", \"@type\"\
  : \"xsd:string\" },\n    \"body\": { \"@id\": \"merge:body\", \"@type\": \"xsd:string\" },\n    \"email\": { \"@id\": \"schema:email\", \"@type\": \"xsd:string\" },\n    \"accessRole\": { \"@id\": \"merge:access_role\", \"@type\": \"xsd:string\" },\n    \"createdAt\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"modifiedAt\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n    \"remoteWasDeleted\": { \"@id\": \"merge:remote_was_deleted\", \"@type\": \"xsd:boolean\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/json-ld/merge-ats-api-context.jsonld
tags:
- Integrations
- Platform
- Unified API
- JSON-LD
- Linked Data
- Semantic Web
---
