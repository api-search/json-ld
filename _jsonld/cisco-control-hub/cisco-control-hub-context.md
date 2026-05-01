---
api_specs:
- filename: openapi.json
  format: json
  label: Webex Admin API
  slug: webex-admin-api
  spec_type: OpenAPI
  url: https://developer.webex.com/docs/api/v1/openapi.json
- filename: openapi.json
  format: json
  label: Webex Calling API
  slug: webex-calling-api
  spec_type: OpenAPI
  url: https://developer.webex.com/docs/api/v1/openapi.json
- filename: openapi.json
  format: json
  label: Webex Devices API
  slug: webex-devices-api
  spec_type: OpenAPI
  url: https://developer.webex.com/docs/api/v1/openapi.json
- filename: openapi.json
  format: json
  label: Webex Workspaces API
  slug: webex-workspaces-api
  spec_type: OpenAPI
  url: https://developer.webex.com/docs/api/v1/openapi.json
- filename: openapi.json
  format: json
  label: Webex People API
  slug: webex-people-api
  spec_type: OpenAPI
  url: https://developer.webex.com/docs/api/v1/openapi.json
- filename: openapi.json
  format: json
  label: Webex Organizations API
  slug: webex-organizations-api
  spec_type: OpenAPI
  url: https://developer.webex.com/docs/api/v1/openapi.json
- filename: openapi.json
  format: json
  label: Webex Licenses API
  slug: webex-licenses-api
  spec_type: OpenAPI
  url: https://developer.webex.com/docs/api/v1/openapi.json
- filename: openapi.json
  format: json
  label: Webex Locations API
  slug: webex-locations-api
  spec_type: OpenAPI
  url: https://developer.webex.com/docs/api/v1/openapi.json
- filename: openapi.json
  format: json
  label: Webex Reports API
  slug: webex-reports-api
  spec_type: OpenAPI
  url: https://developer.webex.com/docs/api/v1/openapi.json
class_count: 0
classes: []
context_file: json-ld/cisco-control-hub-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cisco-control-hub/refs/heads/main/json-ld/cisco-control-hub-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cisco Control Hub from Cisco Control Hub.
layout: jsonld
name: Cisco Control Hub Context
namespaces:
- prefix: webex
  uri: https://webexapis.com/v1/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Person
  type: ''
- container: ''
  name: License
  type: ''
- container: ''
  name: Location
  type: ''
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: Device
  type: ''
- container: ''
  name: AuditEvent
  type: ''
property_count: 7
provider_name: Cisco Control Hub
provider_slug: cisco-control-hub
slug: cisco-control-hub-context
source_filename: cisco-control-hub-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"webex\": \"https://webexapis.com/v1/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Organization\": {\n      \"@id\": \"webex:Organization\",\n      \"@context\": {\n        \"id\": \"webex:id\",\n        \"displayName\": \"schema:name\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Person\": {\n      \"@id\": \"webex:Person\",\n      \"@context\": {\n        \"id\": \"webex:id\",\n        \"displayName\": \"schema:name\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"emails\": \"schema:email\",\n        \"orgId\": \"schema:memberOf\",\n        \"roles\": \"webex:roles\",\n        \"licenses\": \"webex:licenses\",\n        \"phoneNumbers\": \"schema:telephone\",\n \
  \       \"extension\": \"webex:extension\",\n        \"locationId\": \"webex:location_id\",\n        \"status\": \"webex:status\",\n        \"type\": \"webex:person_type\"\n      }\n    },\n\n    \"License\": {\n      \"@id\": \"webex:License\",\n      \"@context\": {\n        \"id\": \"webex:id\",\n        \"name\": \"schema:name\",\n        \"totalUnits\": \"webex:total_units\",\n        \"consumedUnits\": \"webex:consumed_units\",\n        \"subscriptionId\": \"webex:subscription_id\",\n        \"siteUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Location\": {\n      \"@id\": \"webex:Location\",\n      \"@context\": {\n        \"id\": \"webex:id\",\n        \"name\": \"schema:name\",\n        \"address\": \"schema:address\",\n        \"timeZone\": \"schema:timezone\",\n        \"preferredLanguage\": \"schema:inLanguage\"\n      }\n    },\n\n    \"Workspace\": {\n      \"@id\": \"webex:Workspace\",\n      \"@context\":\
  \ {\n        \"id\": \"webex:id\",\n        \"displayName\": \"schema:name\",\n        \"type\": \"webex:workspace_type\",\n        \"capacity\": \"webex:capacity\",\n        \"locationId\": \"webex:location_id\",\n        \"calling\": \"webex:calling\",\n        \"calendar\": \"webex:calendar\"\n      }\n    },\n\n    \"Device\": {\n      \"@id\": \"webex:Device\",\n      \"@context\": {\n        \"id\": \"webex:id\",\n        \"displayName\": \"schema:name\",\n        \"product\": \"schema:model\",\n        \"type\": \"webex:device_type\",\n        \"ip\": \"webex:ip\",\n        \"mac\": \"webex:mac\",\n        \"connectionStatus\": \"webex:connection_status\",\n        \"softwareVersion\": \"schema:softwareVersion\",\n        \"personId\": \"webex:person_id\",\n        \"workspaceId\": \"webex:workspace_id\"\n      }\n    },\n\n    \"AuditEvent\": {\n      \"@id\": \"webex:AuditEvent\",\n      \"@context\": {\n        \"id\": \"webex:id\",\n        \"actorOrgId\": \"webex:actor_org_id\"\
  ,\n        \"actorId\": \"webex:actor_id\",\n        \"actorName\": \"webex:actor_name\",\n        \"actorEmail\": \"schema:email\",\n        \"actionText\": \"schema:description\",\n        \"category\": \"schema:category\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cisco-control-hub/refs/heads/main/json-ld/cisco-control-hub-context.jsonld
tags:
- Administration
- Calling
- Collaboration
- Communications
- Device Management
- Identity Management
- Licenses
- Reporting
- Webex
- JSON-LD
- Linked Data
- Semantic Web
---
