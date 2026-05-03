---
api_specs:
- filename: toast-orders-openapi.yaml
  format: yaml
  label: Toast Orders API
  slug: toast-orders
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-orders-openapi.yaml
- filename: toast-menus-openapi.yaml
  format: yaml
  label: Toast Menus API
  slug: toast-menus
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-menus-openapi.yaml
- filename: toast-labor-openapi.yaml
  format: yaml
  label: Toast Labor API
  slug: toast-labor
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-labor-openapi.yaml
- filename: toast-restaurants-openapi.yaml
  format: yaml
  label: Toast Restaurants API
  slug: toast-restaurants
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-restaurants-openapi.yaml
- filename: toast-stock-openapi.yaml
  format: yaml
  label: Toast Stock API
  slug: toast-stock
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-stock-openapi.yaml
- filename: toast-partners-openapi.yaml
  format: yaml
  label: Toast Partners API
  slug: toast-partners
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-partners-openapi.yaml
- filename: toast-authentication-openapi.yaml
  format: yaml
  label: Toast Authentication API
  slug: toast-authentication
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-authentication-openapi.yaml
class_count: 9
classes:
- Employee
- ExternalReference
- Job
- JobWageOverride
- ScheduleConfig
- Shift
- TimeEntry
- TimeEntryBreak
- ToastReference
context_file: json-ld/toast-labor-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/json-ld/toast-labor-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Toast Labor from Toast.
layout: jsonld
name: Toast Labor Context
namespaces:
- prefix: toast
  uri: https://developer.toasttab.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: auditResponse
  type: boolean
- container: ''
  name: breakType
  type: reference
- container: ''
  name: entityType
  type: string
- container: ''
  name: guid
  type: string
- container: ''
  name: inDate
  type: dateTime
- container: ''
  name: jobReference
  type: reference
- container: ''
  name: minAfterClockIn
  type: decimal
- container: ''
  name: minAfterClockOut
  type: decimal
- container: ''
  name: minBeforeClockIn
  type: decimal
- container: ''
  name: minBeforeClockOut
  type: decimal
- container: ''
  name: missed
  type: boolean
- container: ''
  name: outDate
  type: dateTime
- container: ''
  name: paid
  type: boolean
- container: ''
  name: wage
  type: decimal
- container: ''
  name: waived
  type: boolean
property_count: 15
provider_name: Toast
provider_slug: toast
slug: toast-labor-context
source_filename: toast-labor-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"toast\": \"https://developer.toasttab.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Employee\": \"toast:Employee\",\n    \"ExternalReference\": \"toast:ExternalReference\",\n    \"Job\": \"toast:Job\",\n    \"JobWageOverride\": \"toast:JobWageOverride\",\n    \"ScheduleConfig\": \"toast:ScheduleConfig\",\n    \"Shift\": \"toast:Shift\",\n    \"TimeEntry\": \"toast:TimeEntry\",\n    \"TimeEntryBreak\": \"toast:TimeEntryBreak\",\n    \"ToastReference\": \"toast:ToastReference\",\n    \"auditResponse\": {\n      \"@id\": \"toast:auditResponse\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"breakType\": {\n      \"@id\": \"toast:breakType\",\n      \"@type\": \"@id\"\n    },\n    \"entityType\": {\n      \"@id\": \"toast:entityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"guid\": {\n      \"@id\"\
  : \"toast:guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inDate\": {\n      \"@id\": \"toast:inDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"jobReference\": {\n      \"@id\": \"toast:jobReference\",\n      \"@type\": \"@id\"\n    },\n    \"minAfterClockIn\": {\n      \"@id\": \"toast:minAfterClockIn\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"minAfterClockOut\": {\n      \"@id\": \"toast:minAfterClockOut\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"minBeforeClockIn\": {\n      \"@id\": \"toast:minBeforeClockIn\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"minBeforeClockOut\": {\n      \"@id\": \"toast:minBeforeClockOut\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"missed\": {\n      \"@id\": \"toast:missed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"outDate\": {\n      \"@id\": \"toast:outDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"paid\": {\n      \"@id\": \"toast:paid\",\n      \"@type\": \"xsd:boolean\"\n    },\n\
  \    \"wage\": {\n      \"@id\": \"toast:wage\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"waived\": {\n      \"@id\": \"toast:waived\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/json-ld/toast-labor-context.jsonld
tags:
- Food Service
- Point of Sale
- Restaurants
- Hospitality
- JSON-LD
- Linked Data
- Semantic Web
---
