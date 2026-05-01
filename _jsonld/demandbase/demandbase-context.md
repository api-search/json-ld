---
api_specs:
- filename: demandbase-api-openapi.yml
  format: yaml
  label: Demandbase API
  slug: demandbase-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/demandbase/refs/heads/main/openapi/demandbase-api-openapi.yml
- filename: demandbase-real-time-identification-openapi.yml
  format: yaml
  label: Demandbase Real-Time Identification API
  slug: demandbase-real-time-identification-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/demandbase/refs/heads/main/openapi/demandbase-real-time-identification-openapi.yml
- filename: demandbase-advertising-openapi.yml
  format: yaml
  label: Demandbase Advertising API
  slug: demandbase-advertising-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/demandbase/refs/heads/main/openapi/demandbase-advertising-openapi.yml
- filename: demandbase-engagement-openapi.yml
  format: yaml
  label: Demandbase Engagement API
  slug: demandbase-engagement-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/demandbase/refs/heads/main/openapi/demandbase-engagement-openapi.yml
- filename: demandbase-account-list-openapi.yml
  format: yaml
  label: Demandbase Account List API
  slug: demandbase-account-list-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/demandbase/refs/heads/main/openapi/demandbase-account-list-openapi.yml
- filename: demandbase-b2b-data-openapi.yml
  format: yaml
  label: Demandbase B2B Data API
  slug: demandbase-b2b-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/demandbase/refs/heads/main/openapi/demandbase-b2b-data-openapi.yml
- filename: demandbase-ip-openapi.yml
  format: yaml
  label: Demandbase IP API
  slug: demandbase-ip-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/demandbase/refs/heads/main/openapi/demandbase-ip-openapi.yml
- filename: demandbase-admin-openapi.yml
  format: yaml
  label: Demandbase Admin API
  slug: demandbase-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/demandbase/refs/heads/main/openapi/demandbase-admin-openapi.yml
- filename: demandbase-data-export-openapi.yml
  format: yaml
  label: Demandbase Data Export API
  slug: demandbase-data-export-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/demandbase/refs/heads/main/openapi/demandbase-data-export-openapi.yml
- filename: demandbase-data-import-openapi.yml
  format: yaml
  label: Demandbase Data Import API
  slug: demandbase-data-import-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/demandbase/refs/heads/main/openapi/demandbase-data-import-openapi.yml
class_count: 0
classes: []
context_file: json-ld/demandbase-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/demandbase/refs/heads/main/json-ld/demandbase-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Demandbase from Demandbase.
layout: jsonld
name: Demandbase Context
namespaces:
- prefix: demandbase
  uri: https://api.demandbase.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Account
  type: ''
- container: ''
  name: Contact
  type: ''
- container: ''
  name: Campaign
  type: ''
- container: ''
  name: Engagement
  type: ''
- container: ''
  name: Activity
  type: ''
- container: ''
  name: Audience
  type: ''
- container: ''
  name: AccountList
  type: ''
- container: ''
  name: ExportJob
  type: ''
- container: ''
  name: ImportJob
  type: ''
- container: ''
  name: User
  type: ''
property_count: 10
provider_name: Demandbase
provider_slug: demandbase
slug: demandbase-context
source_filename: demandbase-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"demandbase\": \"https://api.demandbase.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Account\": {\n      \"@id\": \"demandbase:Account\",\n      \"@context\": {\n        \"company_name\": \"schema:name\",\n        \"domain\": \"schema:url\",\n        \"website\": \"schema:url\",\n        \"industry\": \"schema:industry\",\n        \"employee_count\": {\n          \"@id\": \"schema:numberOfEmployees\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"revenue\": {\n          \"@id\": \"demandbase:revenue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"address\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"country\": \"schema:addressCountry\",\n        \"zip\": \"schema:postalCode\",\n       \
  \ \"phone\": \"schema:telephone\",\n        \"stock_ticker\": \"schema:tickerSymbol\",\n        \"founded_year\": {\n          \"@id\": \"schema:foundingDate\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"fortune_1000\": {\n          \"@id\": \"demandbase:fortune1000\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"forbes_2000\": {\n          \"@id\": \"demandbase:forbes2000\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"parent_company_id\": \"demandbase:parentCompanyId\",\n        \"ultimate_parent_company_id\": \"demandbase:ultimateParentCompanyId\"\n      }\n    },\n\n    \"Contact\": {\n      \"@id\": \"demandbase:Contact\",\n      \"@context\": {\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"title\": \"schema:jobTitle\",\n        \"department\": \"demandbase:department\",\n        \"seniority\": \"demandbase:seniority\",\n        \"phone\"\
  : \"schema:telephone\",\n        \"linkedin_url\": \"schema:sameAs\",\n        \"company_name\": \"schema:worksFor\"\n      }\n    },\n\n    \"Campaign\": {\n      \"@id\": \"demandbase:Campaign\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"status\": \"demandbase:campaignStatus\",\n        \"budget\": {\n          \"@id\": \"demandbase:budget\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"daily_budget\": {\n          \"@id\": \"demandbase:dailyBudget\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"start_date\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"end_date\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"impressions\": {\n          \"@id\": \"demandbase:impressions\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"clicks\": {\n          \"@id\": \"demandbase:clicks\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"accounts_reached\": {\n          \"@id\": \"demandbase:accountsReached\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Engagement\": {\n      \"@id\": \"demandbase:Engagement\",\n      \"@context\": {\n        \"engagement_score\": {\n          \"@id\": \"demandbase:engagementScore\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"engagement_trend\": \"demandbase:engagementTrend\",\n        \"web_engagement\": {\n          \"@id\": \"demandbase:webEngagement\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"email_engagement\": {\n          \"@id\": \"demandbase:emailEngagement\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"ad_engagement\": {\n          \"@id\": \"demandbase:adEngagement\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"last_activity_date\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"total_activities\"\
  : {\n          \"@id\": \"demandbase:totalActivities\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"intent_strength\": \"demandbase:intentStrength\"\n      }\n    },\n\n    \"Activity\": {\n      \"@id\": \"demandbase:Activity\",\n      \"@context\": {\n        \"type\": \"demandbase:activityType\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"url\": \"schema:url\",\n        \"page_title\": \"schema:name\",\n        \"channel\": \"demandbase:channel\"\n      }\n    },\n\n    \"Audience\": {\n      \"@id\": \"demandbase:Audience\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"account_count\": {\n          \"@id\": \"demandbase:accountCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n    \
  \  }\n    },\n\n    \"AccountList\": {\n      \"@id\": \"demandbase:AccountList\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"demandbase:listType\",\n        \"account_count\": {\n          \"@id\": \"demandbase:accountCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ExportJob\": {\n      \"@id\": \"demandbase:ExportJob\",\n      \"@context\": {\n        \"entity_type\": \"demandbase:entityType\",\n        \"status\": \"demandbase:jobStatus\",\n        \"record_count\": {\n          \"@id\": \"demandbase:recordCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completed_at\": {\n          \"@id\": \"demandbase:completedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ImportJob\": {\n      \"@id\": \"demandbase:ImportJob\",\n      \"@context\": {\n        \"entity_type\": \"demandbase:entityType\",\n        \"operation\": \"demandbase:importOperation\",\n        \"status\": \"demandbase:jobStatus\",\n        \"total_rows\": {\n          \"@id\": \"demandbase:totalRows\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"success_count\": {\n          \"@id\": \"demandbase:successCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"error_count\": {\n          \"@id\": \"demandbase:errorCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"demandbase:User\"\
  ,\n      \"@context\": {\n        \"email\": \"schema:email\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"role\": \"demandbase:userRole\",\n        \"status\": \"demandbase:userStatus\",\n        \"last_login\": {\n          \"@id\": \"demandbase:lastLogin\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/demandbase/refs/heads/main/json-ld/demandbase-context.jsonld
tags:
- Account-Based Marketing
- Advertising
- AI Agents
- B2B Marketing
- Data Enrichment
- Intent Data
- Personalization
- Sales Intelligence
- JSON-LD
- Linked Data
- Semantic Web
---
