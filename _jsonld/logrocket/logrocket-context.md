---
api_specs:
- filename: logrocket-rest-api-openapi.yml
  format: yaml
  label: LogRocket REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/logrocket/refs/heads/main/openapi/logrocket-rest-api-openapi.yml
- filename: logrocket-graphql-api-openapi.yml
  format: yaml
  label: LogRocket GraphQL API
  slug: graphql-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/logrocket/refs/heads/main/openapi/logrocket-graphql-api-openapi.yml
- filename: logrocket-highlights-webhook-asyncapi.yml
  format: yaml
  label: LogRocket Galileo Highlights API
  slug: session-highlights-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/logrocket/refs/heads/main/asyncapi/logrocket-highlights-webhook-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/logrocket-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/logrocket/refs/heads/main/json-ld/logrocket-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Logrocket from LogRocket.
layout: jsonld
name: Logrocket Context
namespaces:
- prefix: lr
  uri: https://logrocket.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Session
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Highlight
  type: ''
- container: ''
  name: DataExport
  type: ''
- container: ''
  name: NetworkRequest
  type: ''
- container: ''
  name: JavaScriptError
  type: ''
property_count: 6
provider_name: LogRocket
provider_slug: logrocket
slug: logrocket-context
source_filename: logrocket-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"lr\": \"https://logrocket.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Session\": {\n      \"@id\": \"lr:Session\",\n      \"@context\": {\n        \"sessionId\": \"lr:sessionId\",\n        \"appId\": \"lr:appId\",\n        \"orgId\": \"lr:orgId\",\n        \"userId\": \"schema:identifier\",\n        \"userEmail\": \"schema:email\",\n        \"userName\": \"schema:name\",\n        \"startTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"browser\": \"lr:browser\",\n        \"deviceType\": \"lr:deviceType\",\n       \
  \ \"operatingSystem\": \"lr:operatingSystem\",\n        \"country\": \"schema:addressCountry\",\n        \"region\": \"schema:addressRegion\",\n        \"city\": \"schema:addressLocality\",\n        \"sdkVersion\": \"schema:softwareVersion\",\n        \"release\": \"schema:version\",\n        \"pagesVisited\": {\n          \"@id\": \"lr:pagesVisited\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"errorCount\": {\n          \"@id\": \"lr:errorCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"lr:User\",\n      \"@context\": {\n        \"userId\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"traits\": \"lr:traits\"\n      }\n    },\n\n    \"Highlight\": {\n      \"@id\": \"lr:Highlight\",\n      \"@context\": {\n        \"requestID\": \"lr:requestID\",\n        \"appID\": \"lr:appID\",\n        \"status\": \"lr:status\",\n\
  \        \"highlights\": \"lr:highlights\",\n        \"sessions\": {\n          \"@id\": \"lr:sessions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"DataExport\": {\n      \"@id\": \"lr:DataExport\",\n      \"@context\": {\n        \"cursor\": \"lr:cursor\",\n        \"sessions\": {\n          \"@id\": \"lr:exportedSessions\",\n          \"@container\": \"@set\"\n        },\n        \"url\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"NetworkRequest\": {\n      \"@id\": \"lr:NetworkRequest\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"method\": \"lr:httpMethod\",\n        \"statusCode\": {\n          \"@id\": \"lr:statusCode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"duration\": {\n          \"@id\": \"lr:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"timestamp\"\
  : {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"JavaScriptError\": {\n      \"@id\": \"lr:JavaScriptError\",\n      \"@context\": {\n        \"message\": \"schema:description\",\n        \"stack\": \"lr:stackTrace\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"url\": {\n          \"@id\": \"lr:sourceUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/logrocket/refs/heads/main/json-ld/logrocket-context.jsonld
tags:
- Analytics
- Error Monitoring
- Frontend Monitoring
- Observability
- Session Replay
- JSON-LD
- Linked Data
- Semantic Web
---
