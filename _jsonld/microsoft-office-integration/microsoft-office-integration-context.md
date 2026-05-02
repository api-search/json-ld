---
api_specs:
- filename: microsoft-office-management-activity-api-openapi.yml
  format: yaml
  label: Microsoft Office 365 Management Activity API
  slug: management-activity-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-integration/refs/heads/main/openapi/microsoft-office-management-activity-api-openapi.yml
- filename: microsoft-office-service-communications-api-openapi.yml
  format: yaml
  label: Microsoft Office 365 Service Communications API
  slug: service-communications-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-integration/refs/heads/main/openapi/microsoft-office-service-communications-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/microsoft-office-integration-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-integration/refs/heads/main/json-ld/microsoft-office-integration-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Office Integration from Microsoft Office Integration.
layout: jsonld
name: Microsoft Office Integration Context
namespaces:
- prefix: office365
  uri: https://learn.microsoft.com/en-us/office/office-365-management-api/
- prefix: graph
  uri: https://learn.microsoft.com/en-us/graph/
properties:
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: ActivityRecord
  type: ''
- container: ''
  name: ContentBlob
  type: ''
- container: ''
  name: Service
  type: ''
- container: ''
  name: WorkloadStatus
  type: ''
- container: ''
  name: Message
  type: ''
property_count: 6
provider_name: Microsoft Office Integration
provider_slug: microsoft-office-integration
slug: microsoft-office-integration-context
source_filename: microsoft-office-integration-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"office365\": \"https://learn.microsoft.com/en-us/office/office-365-management-api/\",\n    \"graph\": \"https://learn.microsoft.com/en-us/graph/\",\n    \"Subscription\": {\n      \"@id\": \"office365:office-365-management-activity-api-reference#subscription\",\n      \"@context\": {\n        \"contentType\": \"office365:contentType\",\n        \"status\": \"schema:status\",\n        \"webhook\": \"office365:webhook\"\n      }\n    },\n    \"ActivityRecord\": {\n      \"@id\": \"office365:office-365-management-activity-api-schema\",\n      \"@context\": {\n        \"CreationTime\": \"schema:dateCreated\",\n        \"Operation\": \"schema:name\",\n        \"OrganizationId\": \"schema:identifier\",\n        \"RecordType\": \"schema:additionalType\",\n        \"ResultStatus\": \"schema:status\",\n        \"Workload\": \"schema:serviceType\",\n        \"UserId\": \"schema:identifier\",\n        \"ClientIP\":\
  \ \"schema:identifier\"\n      }\n    },\n    \"ContentBlob\": {\n      \"@id\": \"office365:office-365-management-activity-api-reference#content\",\n      \"@context\": {\n        \"contentType\": \"schema:encodingFormat\",\n        \"contentId\": \"schema:identifier\",\n        \"contentUri\": \"schema:url\",\n        \"contentCreated\": \"schema:dateCreated\",\n        \"contentExpiration\": \"schema:expires\"\n      }\n    },\n    \"Service\": {\n      \"@id\": \"office365:office-365-service-communications-api-reference#service\",\n      \"@context\": {\n        \"Id\": \"schema:identifier\",\n        \"DisplayName\": \"schema:name\",\n        \"FeatureNames\": \"schema:featureList\"\n      }\n    },\n    \"WorkloadStatus\": {\n      \"@id\": \"office365:office-365-service-communications-api-reference#workload-status\",\n      \"@context\": {\n        \"Id\": \"schema:identifier\",\n        \"Workload\": \"schema:name\",\n        \"StatusDate\": \"schema:dateModified\",\n        \"\
  WorkloadDisplayName\": \"schema:name\",\n        \"Status\": \"schema:status\",\n        \"IncidentIds\": \"schema:identifier\"\n      }\n    },\n    \"Message\": {\n      \"@id\": \"office365:office-365-service-communications-api-reference#messages\",\n      \"@context\": {\n        \"Id\": \"schema:identifier\",\n        \"Title\": \"schema:headline\",\n        \"StartTime\": \"schema:startDate\",\n        \"EndTime\": \"schema:endDate\",\n        \"Status\": \"schema:status\",\n        \"LastUpdatedTime\": \"schema:dateModified\",\n        \"Workload\": \"schema:serviceType\",\n        \"MessageType\": \"schema:additionalType\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-integration/refs/heads/main/json-ld/microsoft-office-integration-context.jsonld
tags:
- Microsoft 365
- Microsoft Office Integration
- Office 365
- JSON-LD
- Linked Data
- Semantic Web
---
