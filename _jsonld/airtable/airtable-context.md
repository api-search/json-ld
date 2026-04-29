---
api_specs:
- filename: airtable-airtable-api-openapi.yml
  format: yaml
  label: Airtable API
  slug: airtable-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/airtable/refs/heads/main/openapi/airtable-airtable-api-openapi.yml
- filename: airtable-metadata-api-openapi.yml
  format: yaml
  label: Airtable Metadata API
  slug: airtable-metadata-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/airtable/refs/heads/main/openapi/airtable-metadata-api-openapi.yml
- filename: airtable-enterprise-api-openapi.yml
  format: yaml
  label: Airtable Enterprise API
  slug: airtable-enterprise-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/airtable/refs/heads/main/openapi/airtable-enterprise-api-openapi.yml
- filename: airtable-scim-api-openapi.yml
  format: yaml
  label: Airtable SCIM API
  slug: airtable-scim-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/airtable/refs/heads/main/openapi/airtable-scim-api-openapi.yml
- filename: airtable-audit-logs-api-openapi.yml
  format: yaml
  label: Airtable Audit Logs API
  slug: airtable-audit-logs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/airtable/refs/heads/main/openapi/airtable-audit-logs-api-openapi.yml
- filename: airtable-shares-api-openapi.yml
  format: yaml
  label: Airtable Shares API
  slug: airtable-shares-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/airtable/refs/heads/main/openapi/airtable-shares-api-openapi.yml
class_count: 1
classes:
- scim
context_file: json-ld/airtable-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/airtable/refs/heads/main/json-ld/airtable-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Airtable from Airtable.
layout: jsonld
name: Airtable Context
namespaces:
- prefix: airtable
  uri: https://api.airtable.com/v0/schema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
- prefix: sec
  uri: https://w3id.org/security#
properties:
- container: ''
  name: Record
  type: ''
- container: ''
  name: Base
  type: ''
- container: ''
  name: Table
  type: ''
- container: ''
  name: Field
  type: ''
- container: ''
  name: View
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: AuditLogEvent
  type: ''
- container: ''
  name: Share
  type: ''
- container: ''
  name: ScimUser
  type: ''
- container: ''
  name: ScimGroup
  type: ''
- container: ''
  name: EnterpriseAccount
  type: ''
property_count: 14
provider_name: Airtable
provider_slug: airtable
slug: airtable-context
source_filename: airtable-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"airtable\": \"https://api.airtable.com/v0/schema#\",\n    \"scim\": \"urn:ietf:params:scim:schemas:core:2.0:\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n    \"sec\": \"https://w3id.org/security#\",\n\n    \"Record\": {\n      \"@id\": \"airtable:Record\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"fields\": \"airtable:fields\",\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\n        }\n      }\n    },\n\n    \"Base\": {\n      \"@id\": \"airtable:Base\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"permissionLevel\": \"airtable:permissionLevel\",\n        \"tables\": {\n          \"@id\": \"schema:hasPart\",\n          \"@type\": \"@id\"\n  \
  \      }\n      }\n    },\n\n    \"Table\": {\n      \"@id\": \"airtable:Table\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"primaryFieldId\": \"airtable:primaryFieldId\",\n        \"fields\": {\n          \"@id\": \"schema:hasPart\",\n          \"@type\": \"@id\"\n        },\n        \"views\": {\n          \"@id\": \"airtable:hasView\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Field\": {\n      \"@id\": \"airtable:Field\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"type\": \"airtable:fieldType\",\n        \"description\": \"schema:description\",\n        \"options\": \"airtable:fieldOptions\"\n      }\n    },\n\n    \"View\": {\n      \"@id\": \"airtable:View\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"type\": \"airtable:viewType\",\n        \"personalForUserId\"\
  : \"airtable:personalForUserId\",\n        \"visibleFieldIds\": \"airtable:visibleFieldIds\"\n      }\n    },\n\n    \"Comment\": {\n      \"@id\": \"schema:Comment\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"text\": \"schema:text\",\n        \"author\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\n        },\n        \"lastUpdatedTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\n        }\n      }\n    },\n\n    \"Webhook\": {\n      \"@id\": \"airtable:Webhook\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"notificationUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"isHookEnabled\": \"airtable:isHookEnabled\",\n        \"createdTime\": {\n          \"@id\": \"\
  dcterms:created\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\n        },\n        \"expirationTime\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\n        },\n        \"specification\": \"airtable:webhookSpecification\"\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"foaf:Person\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"email\": \"foaf:mbox\",\n        \"name\": \"foaf:name\",\n        \"state\": \"airtable:managementState\",\n        \"isAdmin\": \"airtable:isAdmin\",\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\n        },\n        \"lastActivityTime\": {\n          \"@id\": \"airtable:lastActivityTime\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\n        }\n      }\n    },\n\n    \"Workspace\": {\n      \"@id\": \"airtable:Workspace\",\n      \"@context\"\
  : {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"collaborators\": \"airtable:collaborators\",\n        \"groupCollaborators\": \"airtable:groupCollaborators\"\n      }\n    },\n\n    \"AuditLogEvent\": {\n      \"@id\": \"airtable:AuditLogEvent\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\n        },\n        \"action\": \"schema:actionStatus\",\n        \"actor\": {\n          \"@id\": \"schema:agent\",\n          \"@type\": \"@id\"\n        },\n        \"modelId\": \"airtable:modelId\",\n        \"modelType\": \"airtable:modelType\",\n        \"category\": \"schema:category\",\n        \"context\": \"airtable:eventContext\"\n      }\n    },\n\n    \"Share\": {\n      \"@id\": \"airtable:Share\",\n      \"@context\": {\n        \"shareId\": \"@id\",\n        \"type\": \"airtable:shareType\",\n        \"state\": \"airtable:shareState\"\
  ,\n        \"createdByUserId\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"@id\"\n        },\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\n        },\n        \"baseId\": \"airtable:baseId\",\n        \"viewId\": \"airtable:viewId\",\n        \"isPasswordEnabled\": \"airtable:isPasswordEnabled\",\n        \"effectivePermissionLevel\": \"airtable:effectivePermissionLevel\"\n      }\n    },\n\n    \"ScimUser\": {\n      \"@id\": \"scim:User\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"userName\": \"foaf:accountName\",\n        \"name\": \"foaf:name\",\n        \"emails\": \"vcard:hasEmail\",\n        \"active\": \"airtable:isActive\"\n      }\n    },\n\n    \"ScimGroup\": {\n      \"@id\": \"scim:Group\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\",\n        \"members\": {\n          \"@id\": \"schema:member\"\
  ,\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"EnterpriseAccount\": {\n      \"@id\": \"airtable:EnterpriseAccount\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\n        },\n        \"emailDomains\": \"airtable:emailDomains\",\n        \"userIds\": \"airtable:userIds\",\n        \"groupIds\": \"airtable:groupIds\",\n        \"workspaceIds\": \"airtable:workspaceIds\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/airtable/refs/heads/main/json-ld/airtable-context.jsonld
tags:
- Applications
- Collaboration
- Data
- Databases
- Low-Code
- Productivity
- Spreadsheets
- JSON-LD
- Linked Data
- Semantic Web
---
