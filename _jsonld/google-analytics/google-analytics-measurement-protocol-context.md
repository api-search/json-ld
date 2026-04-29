---
api_specs:
- filename: google-analytics-data-api.yaml
  format: yaml
  label: Google Analytics Data API (GA4)
  slug: google-analytics-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-data-api.yaml
- filename: google-analytics-admin-api.yaml
  format: yaml
  label: Google Analytics Admin API
  slug: google-analytics-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-admin-api.yaml
- filename: google-analytics-measurement-protocol.yaml
  format: yaml
  label: Google Analytics Measurement Protocol (GA4)
  slug: google-analytics-measurement-protocol
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-measurement-protocol.yaml
- filename: google-analytics-user-deletion-api.yaml
  format: yaml
  label: Google Analytics User Deletion API
  slug: google-analytics-user-deletion-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-user-deletion-api.yaml
- filename: google-analytics-reporting-api-v4.yaml
  format: yaml
  label: Google Analytics Reporting API v4 (Universal Analytics)
  slug: google-analytics-reporting-api-v4
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-reporting-api-v4.yaml
- filename: google-analytics-management-api-v3.yaml
  format: yaml
  label: Google Analytics Management API v3
  slug: google-analytics-management-api-v3
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-management-api-v3.yaml
class_count: 7
classes:
- Consent
- Device
- Event
- MeasurementPayload
- UserLocation
- ValidationMessage
- ValidationResponse
context_file: json-ld/google-analytics-measurement-protocol-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/json-ld/google-analytics-measurement-protocol-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Analytics Measurement Protocol from Google Analytics.
layout: jsonld
name: Google Analytics Measurement Protocol Context
namespaces:
- prefix: ga
  uri: https://developers.google.com/analytics/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: adPersonalization
  type: string
- container: ''
  name: adUserData
  type: string
- container: ''
  name: appInstanceId
  type: string
- container: ''
  name: brand
  type: string
- container: ''
  name: browser
  type: string
- container: ''
  name: browserVersion
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: clientId
  type: string
- container: ''
  name: consent
  type: reference
- container: ''
  name: continentId
  type: string
- container: ''
  name: countryId
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: device
  type: reference
- container: ''
  name: engagementTimeMsec
  type: integer
- container: set
  name: events
  type: reference
- container: ''
  name: fieldPath
  type: string
- container: ''
  name: ipOverride
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: model
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: nonPersonalizedAds
  type: boolean
- container: ''
  name: operatingSystem
  type: string
- container: ''
  name: operatingSystemVersion
  type: string
- container: ''
  name: params
  type: reference
- container: ''
  name: regionId
  type: string
- container: ''
  name: screenResolution
  type: string
- container: ''
  name: sessionId
  type: string
- container: ''
  name: subcontinentId
  type: string
- container: ''
  name: timestampMicros
  type: integer
- container: ''
  name: userData
  type: reference
- container: ''
  name: userId
  type: string
- container: ''
  name: userLocation
  type: reference
- container: ''
  name: userProperties
  type: reference
- container: ''
  name: validationCode
  type: string
- container: set
  name: validationMessages
  type: reference
- container: ''
  name: validationBehavior
  type: string
property_count: 37
provider_name: Google Analytics
provider_slug: google-analytics
slug: google-analytics-measurement-protocol-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ga\": \"https://developers.google.com/analytics/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Consent\": \"ga:Consent\",\n    \"Device\": \"ga:Device\",\n    \"Event\": \"ga:Event\",\n    \"MeasurementPayload\": \"ga:MeasurementPayload\",\n    \"UserLocation\": \"ga:UserLocation\",\n    \"ValidationMessage\": \"ga:ValidationMessage\",\n    \"ValidationResponse\": \"ga:ValidationResponse\",\n    \"adPersonalization\": {\n      \"@id\": \"ga:ad_personalization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adUserData\": {\n      \"@id\": \"ga:ad_user_data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appInstanceId\": {\n      \"@id\": \"ga:app_instance_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brand\": {\n      \"@id\": \"ga:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"browser\"\
  : {\n      \"@id\": \"ga:browser\",\n      \"@type\": \"xsd:string\"\n    },\n    \"browserVersion\": {\n      \"@id\": \"ga:browser_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"ga:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"ga:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientId\": {\n      \"@id\": \"ga:client_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consent\": {\n      \"@id\": \"ga:consent\",\n      \"@type\": \"@id\"\n    },\n    \"continentId\": {\n      \"@id\": \"ga:continent_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryId\": {\n      \"@id\": \"ga:country_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"device\": {\n      \"@id\": \"ga:device\",\n      \"@type\": \"@id\"\n    },\n    \"engagementTimeMsec\": {\n      \"@id\": \"ga:engagement_time_msec\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"events\": {\n      \"@id\": \"ga:events\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"fieldPath\": {\n      \"@id\": \"ga:fieldPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipOverride\": {\n      \"@id\": \"ga:ip_override\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"ga:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model\": {\n      \"@id\": \"ga:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nonPersonalizedAds\": {\n      \"@id\": \"ga:non_personalized_ads\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"operatingSystem\": {\n      \"@id\": \"ga:operating_system\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operatingSystemVersion\": {\n      \"@id\": \"ga:operating_system_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"params\"\
  : {\n      \"@id\": \"ga:params\",\n      \"@type\": \"@id\"\n    },\n    \"regionId\": {\n      \"@id\": \"ga:region_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"screenResolution\": {\n      \"@id\": \"ga:screen_resolution\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionId\": {\n      \"@id\": \"ga:session_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subcontinentId\": {\n      \"@id\": \"ga:subcontinent_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestampMicros\": {\n      \"@id\": \"ga:timestamp_micros\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"userData\": {\n      \"@id\": \"ga:user_data\",\n      \"@type\": \"@id\"\n    },\n    \"userId\": {\n      \"@id\": \"ga:user_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userLocation\": {\n      \"@id\": \"ga:user_location\",\n      \"@type\": \"@id\"\n    },\n    \"userProperties\": {\n      \"@id\": \"ga:user_properties\",\n      \"@type\": \"@id\"\n    },\n    \"validationCode\": {\n\
  \      \"@id\": \"ga:validationCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validationMessages\": {\n      \"@id\": \"ga:validationMessages\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"validationBehavior\": {\n      \"@id\": \"ga:validation_behavior\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/json-ld/google-analytics-measurement-protocol-context.jsonld
tags:
- Analytics
- Data
- Google
- Metrics
- Reporting
- Web Analytics
- Machine Learning
- Attribution
- JSON-LD
- Linked Data
- Semantic Web
---
