---
api_specs:
- filename: litmus-instant-openapi.yml
  format: yaml
  label: Litmus Instant API
  slug: litmus-instant-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/litmus/refs/heads/main/openapi/litmus-instant-openapi.yml
- filename: litmus-legacy-previews-openapi.yml
  format: yaml
  label: Litmus Legacy Previews API
  slug: litmus-legacy-previews-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/litmus/refs/heads/main/openapi/litmus-legacy-previews-openapi.yml
- filename: litmus-email-analytics-openapi.yml
  format: yaml
  label: Litmus Email Analytics API
  slug: litmus-email-analytics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/litmus/refs/heads/main/openapi/litmus-email-analytics-openapi.yml
class_count: 7
classes:
- EmailTest
- PreviewResult
- SpamResult
- LinkResult
- EmailClient
- Campaign
- CampaignSummary
context_file: json-ld/litmus-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/litmus/refs/heads/main/json-ld/litmus-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Litmus from Litmus.
layout: jsonld
name: Litmus Context
namespaces:
- prefix: litmus
  uri: https://litmus.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: guid
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: from_address
  type: string
- container: ''
  name: from_name
  type: string
- container: ''
  name: html
  type: string
- container: ''
  name: plain_text
  type: string
- container: ''
  name: client
  type: string
- container: ''
  name: client_name
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: orientation
  type: string
- container: ''
  name: available
  type: boolean
- container: ''
  name: full_image_url
  type: reference
- container: ''
  name: thumb_image_url
  type: reference
- container: ''
  name: tracking_pixel_url
  type: reference
- container: ''
  name: filter
  type: string
- container: ''
  name: is_spam
  type: boolean
- container: ''
  name: score
  type: decimal
- container: ''
  name: threshold
  type: decimal
- container: ''
  name: url
  type: reference
- container: ''
  name: redirect_url
  type: reference
- container: ''
  name: status_code
  type: integer
- container: ''
  name: reachable
  type: boolean
- container: ''
  name: total_opens
  type: integer
- container: ''
  name: unique_opens
  type: integer
- container: ''
  name: forwards
  type: integer
- container: ''
  name: prints
  type: integer
- container: ''
  name: read_rate
  type: decimal
- container: ''
  name: skim_rate
  type: decimal
- container: ''
  name: glance_rate
  type: decimal
- container: ''
  name: delete_rate
  type: decimal
- container: ''
  name: percentage
  type: decimal
- container: ''
  name: count
  type: integer
- container: ''
  name: country
  type: string
- container: ''
  name: country_code
  type: string
- container: ''
  name: device_type
  type: string
- container: set
  name: previews
  type: ''
- container: set
  name: spam_results
  type: ''
- container: set
  name: link_results
  type: ''
- container: set
  name: clients
  type: ''
- container: set
  name: tags
  type: ''
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: completed_at
  type: dateTime
property_count: 46
provider_name: Litmus
provider_slug: litmus
slug: litmus-context
source_filename: litmus-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"litmus\": \"https://litmus.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"EmailTest\": \"litmus:EmailTest\",\n    \"PreviewResult\": \"litmus:PreviewResult\",\n    \"SpamResult\": \"litmus:SpamResult\",\n    \"LinkResult\": \"litmus:LinkResult\",\n    \"EmailClient\": \"litmus:EmailClient\",\n    \"Campaign\": \"litmus:Campaign\",\n    \"CampaignSummary\": \"litmus:CampaignSummary\",\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"guid\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"\
  litmus:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from_address\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from_name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"html\": {\n      \"@id\": \"schema:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"plain_text\": {\n      \"@id\": \"schema:text\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"client\": {\n      \"@id\": \"litmus:emailClientId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"client_name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"litmus:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orientation\": {\n      \"@id\": \"litmus:orientation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"available\": {\n      \"@id\": \"schema:Boolean\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"full_image_url\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"thumb_image_url\": {\n      \"@id\": \"schema:thumbnail\",\n      \"@type\": \"@id\"\n    },\n    \"tracking_pixel_url\": {\n      \"@id\": \"litmus:trackingPixelUrl\",\n      \"@type\": \"@id\"\n    },\n\n    \"filter\": {\n      \"@id\": \"litmus:spamFilter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"is_spam\": {\n      \"@id\": \"litmus:isSpam\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"score\": {\n      \"@id\": \"litmus:spamScore\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"threshold\": {\n      \"@id\": \"litmus:spamThreshold\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"redirect_url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"status_code\": {\n      \"@id\": \"litmus:httpStatusCode\",\n   \
  \   \"@type\": \"xsd:integer\"\n    },\n    \"reachable\": {\n      \"@id\": \"litmus:isReachable\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"total_opens\": {\n      \"@id\": \"litmus:totalOpens\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"unique_opens\": {\n      \"@id\": \"litmus:uniqueOpens\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"forwards\": {\n      \"@id\": \"litmus:forwardCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"prints\": {\n      \"@id\": \"litmus:printCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"read_rate\": {\n      \"@id\": \"litmus:readRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"skim_rate\": {\n      \"@id\": \"litmus:skimRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"glance_rate\": {\n      \"@id\": \"litmus:glanceRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"delete_rate\": {\n      \"@id\": \"litmus:deleteRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"percentage\": {\n  \
  \    \"@id\": \"litmus:percentage\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"count\": {\n      \"@id\": \"schema:Number\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"country\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country_code\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"device_type\": {\n      \"@id\": \"schema:device\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"previews\": {\n      \"@id\": \"litmus:previewResult\",\n      \"@container\": \"@set\"\n    },\n    \"spam_results\": {\n      \"@id\": \"litmus:spamResult\",\n      \"@container\": \"@set\"\n    },\n    \"link_results\": {\n      \"@id\": \"litmus:linkResult\",\n      \"@container\": \"@set\"\n    },\n    \"clients\": {\n      \"@id\": \"litmus:emailClient\",\n      \"@container\": \"@set\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n\n\
  \    \"created_at\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completed_at\": {\n      \"@id\": \"litmus:completedAt\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/litmus/refs/heads/main/json-ld/litmus-context.jsonld
tags:
- Developer Tools
- Email Testing
- Marketing Tools
- Quality Assurance
- JSON-LD
- Linked Data
- Semantic Web
---
