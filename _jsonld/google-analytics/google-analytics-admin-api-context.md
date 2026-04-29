---
class_count: 10
classes:
- Account
- ChangeHistoryEvent
- ConversionEvent
- CustomDimension
- CustomMetric
- DataStream
- FirebaseLink
- GoogleAdsLink
- MeasurementProtocolSecret
- Property
context_file: json-ld/google-analytics-admin-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/json-ld/google-analytics-admin-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Analytics Admin Api from Google Analytics.
layout: jsonld
name: Google Analytics Admin Api Context
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
  name: account
  type: string
- container: ''
  name: actorType
  type: string
- container: ''
  name: adsPersonalizationEnabled
  type: boolean
- container: ''
  name: androidAppStreamData
  type: reference
- container: ''
  name: bundleId
  type: string
- container: ''
  name: canManageClients
  type: boolean
- container: ''
  name: changeTime
  type: dateTime
- container: set
  name: changes
  type: reference
- container: ''
  name: changesFiltered
  type: boolean
- container: ''
  name: countingMethod
  type: string
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: creatorEmailAddress
  type: string
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: custom
  type: boolean
- container: ''
  name: customerId
  type: string
- container: ''
  name: defaultConversionValue
  type: reference
- container: ''
  name: defaultUri
  type: string
- container: ''
  name: deletable
  type: boolean
- container: ''
  name: deleteTime
  type: dateTime
- container: ''
  name: deleted
  type: boolean
- container: ''
  name: description
  type: string
- container: ''
  name: disallowAdsPersonalization
  type: boolean
- container: ''
  name: displayName
  type: string
- container: ''
  name: eventName
  type: string
- container: ''
  name: expireTime
  type: dateTime
- container: ''
  name: firebaseAppId
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: industryCategory
  type: string
- container: ''
  name: iosAppStreamData
  type: reference
- container: ''
  name: measurementId
  type: string
- container: ''
  name: measurementUnit
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: packageName
  type: string
- container: ''
  name: parameterName
  type: string
- container: ''
  name: parent
  type: string
- container: ''
  name: project
  type: string
- container: ''
  name: propertyType
  type: string
- container: ''
  name: regionCode
  type: string
- container: set
  name: restrictedMetricType
  type: string
- container: ''
  name: scope
  type: string
- container: ''
  name: secretValue
  type: string
- container: ''
  name: serviceLevel
  type: string
- container: ''
  name: timeZone
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: updateTime
  type: dateTime
- container: ''
  name: userActorEmail
  type: string
- container: ''
  name: value
  type: double
- container: ''
  name: webStreamData
  type: reference
property_count: 48
provider_name: Google Analytics
provider_slug: google-analytics
slug: google-analytics-admin-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ga\": \"https://developers.google.com/analytics/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Account\": \"ga:Account\",\n    \"ChangeHistoryEvent\": \"ga:ChangeHistoryEvent\",\n    \"ConversionEvent\": \"ga:ConversionEvent\",\n    \"CustomDimension\": \"ga:CustomDimension\",\n    \"CustomMetric\": \"ga:CustomMetric\",\n    \"DataStream\": \"ga:DataStream\",\n    \"FirebaseLink\": \"ga:FirebaseLink\",\n    \"GoogleAdsLink\": \"ga:GoogleAdsLink\",\n    \"MeasurementProtocolSecret\": \"ga:MeasurementProtocolSecret\",\n    \"Property\": \"ga:Property\",\n    \"account\": {\n      \"@id\": \"ga:account\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actorType\": {\n      \"@id\": \"ga:actorType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adsPersonalizationEnabled\": {\n      \"@id\": \"ga:adsPersonalizationEnabled\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"androidAppStreamData\": {\n      \"@id\": \"ga:androidAppStreamData\",\n      \"@type\": \"@id\"\n    },\n    \"bundleId\": {\n      \"@id\": \"ga:bundleId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"canManageClients\": {\n      \"@id\": \"ga:canManageClients\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"changeTime\": {\n      \"@id\": \"ga:changeTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"changes\": {\n      \"@id\": \"ga:changes\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"changesFiltered\": {\n      \"@id\": \"ga:changesFiltered\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"countingMethod\": {\n      \"@id\": \"ga:countingMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createTime\": {\n      \"@id\": \"ga:createTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"creatorEmailAddress\": {\n      \"@id\": \"ga:creatorEmailAddress\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"currencyCode\": {\n      \"@id\": \"ga:currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"custom\": {\n      \"@id\": \"ga:custom\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"customerId\": {\n      \"@id\": \"ga:customerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultConversionValue\": {\n      \"@id\": \"ga:defaultConversionValue\",\n      \"@type\": \"@id\"\n    },\n    \"defaultUri\": {\n      \"@id\": \"ga:defaultUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deletable\": {\n      \"@id\": \"ga:deletable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"deleteTime\": {\n      \"@id\": \"ga:deleteTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deleted\": {\n      \"@id\": \"ga:deleted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disallowAdsPersonalization\": {\n      \"@id\": \"ga:disallowAdsPersonalization\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"displayName\": {\n      \"@id\": \"ga:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventName\": {\n      \"@id\": \"ga:eventName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expireTime\": {\n      \"@id\": \"ga:expireTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"firebaseAppId\": {\n      \"@id\": \"ga:firebaseAppId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"ga:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"industryCategory\": {\n      \"@id\": \"ga:industryCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iosAppStreamData\": {\n      \"@id\": \"ga:iosAppStreamData\",\n      \"@type\": \"@id\"\n    },\n    \"measurementId\": {\n      \"@id\": \"ga:measurementId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"measurementUnit\": {\n      \"@id\": \"ga:measurementUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"packageName\": {\n      \"@id\": \"ga:packageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameterName\": {\n      \"@id\": \"ga:parameterName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parent\": {\n      \"@id\": \"ga:parent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"project\": {\n      \"@id\": \"ga:project\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyType\": {\n      \"@id\": \"ga:propertyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regionCode\": {\n      \"@id\": \"ga:regionCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"restrictedMetricType\": {\n      \"@id\": \"ga:restrictedMetricType\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scope\": {\n      \"@id\": \"ga:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretValue\": {\n      \"@id\": \"ga:secretValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceLevel\":\
  \ {\n      \"@id\": \"ga:serviceLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeZone\": {\n      \"@id\": \"ga:timeZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"ga:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updateTime\": {\n      \"@id\": \"ga:updateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"userActorEmail\": {\n      \"@id\": \"ga:userActorEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"ga:value\",\n      \"@type\": \"xsd:double\"\n    },\n    \"webStreamData\": {\n      \"@id\": \"ga:webStreamData\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/json-ld/google-analytics-admin-api-context.jsonld
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
