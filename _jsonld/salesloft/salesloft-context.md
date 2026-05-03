---
api_specs:
- filename: salesloft-openapi.yml
  format: yaml
  label: Salesloft API
  slug: salesloft-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesloft/refs/heads/main/openapi/salesloft-openapi.yml
class_count: 0
classes: []
context_file: json-ld/salesloft-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/salesloft/refs/heads/main/json-ld/salesloft-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Salesloft from Salesloft.
layout: jsonld
name: Salesloft Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: sl
  uri: https://api-evangelist.github.io/salesloft/vocab#
properties:
- container: ''
  name: Account
  type: ''
- container: ''
  name: Person
  type: ''
- container: ''
  name: Cadence
  type: ''
- container: ''
  name: Opportunity
  type: ''
- container: ''
  name: Task
  type: ''
property_count: 5
provider_name: Salesloft
provider_slug: salesloft
slug: salesloft-context
source_filename: salesloft-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"sl\": \"https://api-evangelist.github.io/salesloft/vocab#\",\n\n    \"Account\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"domain\": \"schema:url\",\n        \"phone\": \"schema:telephone\",\n        \"website\": \"schema:url\",\n        \"linkedin_url\": \"schema:sameAs\",\n        \"twitter_handle\": \"schema:sameAs\",\n        \"street\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"postal_code\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\",\n        \"industry\": \"schema:industry\",\n        \"description\": \"schema:description\",\n        \"size\": \"schema:numberOfEmployees\",\n        \"founded\": \"schema:foundingDate\"\
  ,\n        \"owner_id\": \"sl:ownedBy\",\n        \"tags\": \"schema:keywords\",\n        \"do_not_contact\": \"sl:doNotContact\",\n        \"crm_id\": \"sl:externalId\",\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Person\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"email_address\": \"schema:email\",\n        \"phone\": \"schema:telephone\",\n        \"mobile_phone\": \"schema:telephone\",\n        \"title\": \"schema:jobTitle\",\n        \"linkedin_url\": \"schema:sameAs\",\n        \"twitter_handle\": \"schema:sameAs\",\n        \"personal_website\": \"schema:url\",\n        \"city\": \"schema:addressLocality\",\n \
  \       \"state\": \"schema:addressRegion\",\n        \"country\": \"schema:addressCountry\",\n        \"person_company_name\": \"schema:worksFor\",\n        \"job_seniority\": \"sl:seniority\",\n        \"do_not_contact\": \"sl:doNotContact\",\n        \"eu_resident\": \"sl:euResident\",\n        \"tags\": \"schema:keywords\",\n        \"account_id\": \"sl:associatedAccount\",\n        \"owner_id\": \"sl:ownedBy\",\n        \"crm_id\": \"sl:externalId\",\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Cadence\": {\n      \"@id\": \"sl:Cadence\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"current_state\": \"sl:state\",\n        \"cadence_function\": \"sl:cadenceFunction\"\
  ,\n        \"is_team\": \"sl:isTeamCadence\",\n        \"owner_id\": \"sl:ownedBy\",\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Opportunity\": {\n      \"@id\": \"schema:Offer\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"owner_id\": \"sl:ownedBy\",\n        \"account_id\": \"sl:associatedAccount\",\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Task\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"id\": \"@id\",\n   \
  \     \"description\": \"schema:description\",\n        \"due_on\": \"schema:scheduledTime\",\n        \"owner_id\": \"sl:ownedBy\",\n        \"person_id\": \"sl:associatedPerson\",\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/salesloft/refs/heads/main/json-ld/salesloft-context.jsonld
tags:
- Sales
- CRM
- Revenue
- Automation
- AI
- JSON-LD
- Linked Data
- Semantic Web
---
