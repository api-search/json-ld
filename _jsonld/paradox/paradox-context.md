---
api_specs:
- filename: paradox-api-openapi.yml
  format: yaml
  label: Paradox Conversational AI API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/paradox/refs/heads/main/openapi/paradox-api-openapi.yml
- filename: paradox-api-openapi.yml
  format: yaml
  label: Paradox Company API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/paradox/refs/heads/main/openapi/paradox-api-openapi.yml
- filename: paradox-api-openapi.yml
  format: yaml
  label: Paradox Candidates API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/paradox/refs/heads/main/openapi/paradox-api-openapi.yml
- filename: paradox-api-openapi.yml
  format: yaml
  label: Paradox Users API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/paradox/refs/heads/main/openapi/paradox-api-openapi.yml
- filename: paradox-api-openapi.yml
  format: yaml
  label: Paradox Scheduling API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/paradox/refs/heads/main/openapi/paradox-api-openapi.yml
- filename: paradox-api-openapi.yml
  format: yaml
  label: Paradox Locations API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/paradox/refs/heads/main/openapi/paradox-api-openapi.yml
- filename: paradox-api-openapi.yml
  format: yaml
  label: Paradox Reporting API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/paradox/refs/heads/main/openapi/paradox-api-openapi.yml
- filename: paradox-api-openapi.yml
  format: yaml
  label: Paradox Candidate Attributes API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/paradox/refs/heads/main/openapi/paradox-api-openapi.yml
- filename: paradox-api-openapi.yml
  format: yaml
  label: Paradox User Permissions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/paradox/refs/heads/main/openapi/paradox-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/paradox-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/paradox/refs/heads/main/json-ld/paradox-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Paradox from Paradox.
layout: jsonld
name: Paradox Context
namespaces:
- prefix: paradox
  uri: https://api.paradox.ai/ns/
- prefix: hr
  uri: https://purl.org/hr-terms/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Candidate
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Location
  type: ''
- container: ''
  name: Interview
  type: ''
- container: ''
  name: Conversation
  type: ''
- container: ''
  name: Room
  type: ''
- container: ''
  name: Area
  type: ''
- container: ''
  name: Report
  type: ''
- container: ''
  name: AiAssistant
  type: ''
property_count: 9
provider_name: Paradox
provider_slug: paradox
slug: paradox-context
source_filename: paradox-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"paradox\": \"https://api.paradox.ai/ns/\",\n    \"hr\": \"https://purl.org/hr-terms/\",\n\n    \"Candidate\": {\n      \"@id\": \"paradox:Candidate\",\n      \"@context\": {\n        \"OID\": {\n          \"@id\": \"paradox:candidateOID\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"external_oid\": {\n          \"@id\": \"paradox:externalOID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": \"schema:name\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\",\n        \"ex_id\": {\n          \"@id\": \"paradox:externalId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ex_status\": {\n          \"@id\": \"paradox:externalStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ex_step\": {\n          \"@id\": \"paradox:externalStep\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"ex_reason\": {\n          \"@id\": \"paradox:externalReason\",\n          \"@type\": \"xsd:string\"\n        },\n        \"job_req_id\": {\n          \"@id\": \"paradox:jobRequisitionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"job_title\": \"schema:jobTitle\",\n        \"job_loc_code\": {\n          \"@id\": \"paradox:jobLocationCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"primary_contact_method\": {\n          \"@id\": \"paradox:primaryContactMethod\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"hired_date\": {\n          \"@id\": \"hr:hiredDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"hirevue_link\": {\n          \"@id\": \"paradox:hirevueLink\",\n          \"@type\": \"@id\"\n        },\n        \"pymetrics_link\": {\n          \"@id\": \"paradox:pymetricsLink\",\n          \"@type\": \"@id\"\n        },\n        \"adp_link\": {\n      \
  \    \"@id\": \"paradox:adpLink\",\n          \"@type\": \"@id\"\n        },\n        \"hirevue_instructions\": {\n          \"@id\": \"paradox:hirevueInstructions\",\n          \"@type\": \"xsd:string\"\n        },\n        \"audience_type\": {\n          \"@id\": \"paradox:audienceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"referrer_email\": {\n          \"@id\": \"paradox:referrerEmail\",\n          \"@type\": \"xsd:string\"\n        },\n        \"referrer_name\": {\n          \"@id\": \"paradox:referrerName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"recruiter_email\": {\n          \"@id\": \"paradox:recruiterEmail\",\n          \"@type\": \"xsd:string\"\n        },\n        \"hiring_manager\": {\n          \"@id\": \"paradox:hiringManager\",\n          \"@type\": \"xsd:string\"\n        },\n        \"external_referrer\": {\n          \"@id\": \"paradox:externalReferrer\",\n          \"@type\": \"xsd:string\"\n        },\n        \"language_preference\"\
  : \"schema:knowsLanguage\",\n        \"candidate_journey\": {\n          \"@id\": \"paradox:candidateJourney\",\n          \"@type\": \"xsd:string\"\n        },\n        \"candidate_journey_status\": {\n          \"@id\": \"paradox:candidateJourneyStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"candidate_attribute_data\": {\n          \"@id\": \"paradox:candidateAttributes\",\n          \"@type\": \"@json\"\n        },\n        \"job_application_id\": {\n          \"@id\": \"paradox:jobApplicationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"candidate_location_info\": \"schema:homeLocation\",\n        \"external_source_id\": {\n          \"@id\": \"paradox:externalSourceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"talent_community\": {\n          \"@id\": \"paradox:talentCommunity\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"consent_to_marketing\": {\n          \"@id\": \"paradox:consentToMarketing\",\n \
  \         \"@type\": \"xsd:string\"\n        },\n        \"note\": {\n          \"@id\": \"paradox:note\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"paradox:User\",\n      \"@context\": {\n        \"OID\": {\n          \"@id\": \"paradox:userOID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"phone_number\": \"schema:telephone\",\n        \"role_id\": {\n          \"@id\": \"paradox:roleId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timezone\": {\n          \"@id\": \"paradox:timezone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"language_preference\": \"schema:knowsLanguage\",\n        \"employee_id\": {\n          \"@id\": \"paradox:employeeId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"job_title\": \"schema:jobTitle\",\n        \"location_ids\": {\n          \"@id\": \"paradox:locationIds\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"active\": {\n          \"@id\": \"paradox:isActive\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Location\": {\n      \"@id\": \"paradox:Location\",\n      \"@context\": {\n        \"oid\": {\n          \"@id\": \"paradox:locationOID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": \"schema:name\",\n        \"job_loc_code\": {\n          \"@id\": \"paradox:jobLocationCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"zip_code\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\"\
  ,\n        \"timezone\": {\n          \"@id\": \"paradox:timezone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"active\": {\n          \"@id\": \"paradox:isActive\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Interview\": {\n      \"@id\": \"paradox:Interview\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"paradox:interviewId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"candidate_id\": {\n          \"@id\": \"paradox:candidateId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"interviewer_id\": {\n          \"@id\": \"paradox:interviewerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"location_id\": {\n          \"@id\": \"paradox:locationId\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"room_id\": {\n          \"@id\": \"paradox:roomId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"scheduled_at\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"status\": {\n          \"@id\": \"paradox:interviewStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"paradox:interviewType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Conversation\": {\n      \"@id\": \"paradox:Conversation\",\n      \"@context\": {\n     \
  \   \"oid\": {\n          \"@id\": \"paradox:conversationOID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": \"schema:name\",\n        \"is_remote\": {\n          \"@id\": \"paradox:isRemote\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"deactivated\": {\n          \"@id\": \"paradox:isDeactivated\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Room\": {\n      \"@id\": \"paradox:Room\",\n      \"@context\": {\n        \"oid\": {\n          \"@id\": \"paradox:roomOID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": \"schema:name\",\n        \"location_id\": {\n          \"@id\": \"paradox:locationId\",\n          \"@type\": \"xsd:string\"\n        },\n \
  \       \"capacity\": {\n          \"@id\": \"paradox:roomCapacity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"active\": {\n          \"@id\": \"paradox:isActive\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Area\": {\n      \"@id\": \"paradox:Area\",\n      \"@context\": {\n        \"oid\": {\n          \"@id\": \"paradox:areaOID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": \"schema:name\",\n        \"location_id\": {\n          \"@id\": \"paradox:locationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"paradox:areaType\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Report\": {\n      \"@id\": \"paradox:Report\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"paradox:reportId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": \"schema:name\",\n        \"type\": {\n          \"@id\": \"paradox:reportType\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"paradox:reportStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AiAssistant\": {\n      \"@id\": \"paradox:AiAssistant\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"paradox:assistantId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ai_name\": \"schema:name\",\n        \"ai_logo_uri\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/paradox/refs/heads/main/json-ld/paradox-context.jsonld
tags:
- Artificial Intelligence
- Candidate Screening
- Chatbot
- Conversational AI
- Hiring Automation
- HR Technology
- Interview Scheduling
- Recruiting
- SMS
- Talent Acquisition
- JSON-LD
- Linked Data
- Semantic Web
---
