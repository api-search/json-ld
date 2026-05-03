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
class_count: 17
classes:
- DaySchedule
- Delivery
- DeliveryPaymentOptions
- General
- Hours
- Image
- Location
- OnlineOrdering
- PaymentOptions
- PrepTimes
- Restaurant
- RestaurantInfo
- Schedules
- Service
- TakeoutPaymentOptions
- URLs
- WeekSchedule
context_file: json-ld/toast-restaurants-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/json-ld/toast-restaurants-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Toast Restaurants from Toast.
layout: jsonld
name: Toast Restaurants Context
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
  name: address1
  type: string
- container: ''
  name: address2
  type: string
- container: ''
  name: administrativeArea
  type: string
- container: ''
  name: archived
  type: boolean
- container: ''
  name: area
  type: string
- container: ''
  name: cash
  type: boolean
- container: ''
  name: ccFuture
  type: boolean
- container: ''
  name: ccInStore
  type: boolean
- container: ''
  name: ccSameDay
  type: boolean
- container: ''
  name: ccTip
  type: boolean
- container: ''
  name: checkGiftCard
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: closeTime
  type: string
- container: ''
  name: closeoutHour
  type: integer
- container: ''
  name: country
  type: string
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: daySchedules
  type: reference
- container: ''
  name: delivery
  type: string
- container: ''
  name: deliveryPrepTime
  type: integer
- container: ''
  name: deliveryThrottlingTime
  type: integer
- container: ''
  name: deliveryTimeAfterOpen
  type: integer
- container: ''
  name: deliveryTimeBeforeClose
  type: integer
- container: ''
  name: description
  type: ''
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: endTime
  type: string
- container: ''
  name: facebook
  type: string
- container: ''
  name: firstBusinessDate
  type: integer
- container: ''
  name: friday
  type: string
- container: ''
  name: general
  type: string
- container: ''
  name: guid
  type: string
- container: ''
  name: height
  type: integer
- container: ''
  name: heightWidthRatio
  type: decimal
- container: ''
  name: hours
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: location
  type: string
- container: ''
  name: locationCode
  type: string
- container: ''
  name: locationName
  type: string
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: managementGroupGuid
  type: string
- container: ''
  name: minimum
  type: decimal
- container: ''
  name: monday
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: onlineOrdering
  type: string
- container: ''
  name: openTime
  type: string
- container: ''
  name: orderOnline
  type: string
- container: ''
  name: overnight
  type: boolean
- container: ''
  name: paymentOptions
  type: string
- container: ''
  name: phone
  type: string
- container: ''
  name: phoneCountryCode
  type: string
- container: ''
  name: prepTimes
  type: string
- container: ''
  name: purchaseGiftCard
  type: string
- container: ''
  name: saturday
  type: string
- container: ''
  name: scheduleName
  type: string
- container: ''
  name: schedules
  type: string
- container: ''
  name: scheduling
  type: boolean
- container: set
  name: services
  type: string
- container: ''
  name: specialRequests
  type: boolean
- container: ''
  name: specialRequestsMessage
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: stateCode
  type: string
- container: ''
  name: sunday
  type: string
- container: ''
  name: takeout
  type: string
- container: ''
  name: takeoutPrepTime
  type: integer
- container: ''
  name: takeoutThrottlingTime
  type: integer
- container: ''
  name: takeoutTimeAfterOpen
  type: integer
- container: ''
  name: takeoutTimeBeforeClose
  type: integer
- container: ''
  name: thursday
  type: string
- container: ''
  name: timeZone
  type: string
- container: ''
  name: tuesday
  type: string
- container: ''
  name: twitter
  type: string
- container: ''
  name: url
  type: ''
- container: ''
  name: urls
  type: string
- container: ''
  name: website
  type: string
- container: ''
  name: wednesday
  type: string
- container: ''
  name: weekSchedule
  type: string
- container: ''
  name: width
  type: integer
- container: ''
  name: zipCode
  type: string
property_count: 77
provider_name: Toast
provider_slug: toast
slug: toast-restaurants-context
source_filename: toast-restaurants-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"toast\": \"https://developer.toasttab.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DaySchedule\": \"toast:DaySchedule\",\n    \"Delivery\": \"toast:Delivery\",\n    \"DeliveryPaymentOptions\": \"toast:DeliveryPaymentOptions\",\n    \"General\": \"toast:General\",\n    \"Hours\": \"toast:Hours\",\n    \"Image\": \"toast:Image\",\n    \"Location\": \"toast:Location\",\n    \"OnlineOrdering\": \"toast:OnlineOrdering\",\n    \"PaymentOptions\": \"toast:PaymentOptions\",\n    \"PrepTimes\": \"toast:PrepTimes\",\n    \"Restaurant\": \"toast:Restaurant\",\n    \"RestaurantInfo\": \"toast:RestaurantInfo\",\n    \"Schedules\": \"toast:Schedules\",\n    \"Service\": \"toast:Service\",\n    \"TakeoutPaymentOptions\": \"toast:TakeoutPaymentOptions\",\n    \"URLs\": \"toast:URLs\",\n    \"WeekSchedule\": \"toast:WeekSchedule\"\
  ,\n    \"address1\": {\n      \"@id\": \"toast:address1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address2\": {\n      \"@id\": \"toast:address2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"administrativeArea\": {\n      \"@id\": \"toast:administrativeArea\",\n      \"@type\": \"xsd:string\"\n    },\n    \"archived\": {\n      \"@id\": \"toast:archived\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"area\": {\n      \"@id\": \"toast:area\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cash\": {\n      \"@id\": \"toast:cash\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ccFuture\": {\n      \"@id\": \"toast:ccFuture\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ccInStore\": {\n      \"@id\": \"toast:ccInStore\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ccSameDay\": {\n      \"@id\": \"toast:ccSameDay\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ccTip\": {\n      \"@id\": \"toast:ccTip\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"checkGiftCard\"\
  : {\n      \"@id\": \"toast:checkGiftCard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"toast:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"closeTime\": {\n      \"@id\": \"toast:closeTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"closeoutHour\": {\n      \"@id\": \"toast:closeoutHour\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"country\": {\n      \"@id\": \"toast:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"toast:currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"daySchedules\": {\n      \"@id\": \"toast:daySchedules\",\n      \"@type\": \"@id\"\n    },\n    \"delivery\": {\n      \"@id\": \"toast:delivery\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryPrepTime\": {\n      \"@id\": \"toast:deliveryPrepTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deliveryThrottlingTime\": {\n      \"@id\": \"toast:deliveryThrottlingTime\",\n      \"@type\":\
  \ \"xsd:integer\"\n    },\n    \"deliveryTimeAfterOpen\": {\n      \"@id\": \"toast:deliveryTimeAfterOpen\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deliveryTimeBeforeClose\": {\n      \"@id\": \"toast:deliveryTimeBeforeClose\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"enabled\": {\n      \"@id\": \"toast:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"endTime\": {\n      \"@id\": \"toast:endTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"facebook\": {\n      \"@id\": \"toast:facebook\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstBusinessDate\": {\n      \"@id\": \"toast:firstBusinessDate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"friday\": {\n      \"@id\": \"toast:friday\",\n      \"@type\": \"xsd:string\"\n    },\n    \"general\": {\n      \"@id\": \"toast:general\",\n      \"@type\": \"xsd:string\"\n    },\n    \"guid\": {\n      \"@id\": \"toast:guid\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"height\": {\n      \"@id\": \"toast:height\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"heightWidthRatio\": {\n      \"@id\": \"toast:heightWidthRatio\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"hours\": {\n      \"@id\": \"toast:hours\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"toast:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"location\": {\n      \"@id\": \"toast:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locationCode\": {\n      \"@id\": \"toast:locationCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locationName\": {\n      \"@id\": \"toast:locationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"longitude\": {\n      \"@id\": \"toast:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"managementGroupGuid\": {\n      \"@id\": \"toast:managementGroupGuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minimum\": {\n     \
  \ \"@id\": \"toast:minimum\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"monday\": {\n      \"@id\": \"toast:monday\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"onlineOrdering\": {\n      \"@id\": \"toast:onlineOrdering\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openTime\": {\n      \"@id\": \"toast:openTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderOnline\": {\n      \"@id\": \"toast:orderOnline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overnight\": {\n      \"@id\": \"toast:overnight\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"paymentOptions\": {\n      \"@id\": \"toast:paymentOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phone\": {\n      \"@id\": \"toast:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneCountryCode\": {\n      \"@id\": \"toast:phoneCountryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prepTimes\": {\n      \"@id\": \"toast:prepTimes\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"purchaseGiftCard\": {\n      \"@id\": \"toast:purchaseGiftCard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"saturday\": {\n      \"@id\": \"toast:saturday\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduleName\": {\n      \"@id\": \"toast:scheduleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schedules\": {\n      \"@id\": \"toast:schedules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduling\": {\n      \"@id\": \"toast:scheduling\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"services\": {\n      \"@id\": \"toast:services\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"specialRequests\": {\n      \"@id\": \"toast:specialRequests\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"specialRequestsMessage\": {\n      \"@id\": \"toast:specialRequestsMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"toast:startTime\",\n     \
  \ \"@type\": \"xsd:string\"\n    },\n    \"stateCode\": {\n      \"@id\": \"toast:stateCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sunday\": {\n      \"@id\": \"toast:sunday\",\n      \"@type\": \"xsd:string\"\n    },\n    \"takeout\": {\n      \"@id\": \"toast:takeout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"takeoutPrepTime\": {\n      \"@id\": \"toast:takeoutPrepTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"takeoutThrottlingTime\": {\n      \"@id\": \"toast:takeoutThrottlingTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"takeoutTimeAfterOpen\": {\n      \"@id\": \"toast:takeoutTimeAfterOpen\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"takeoutTimeBeforeClose\": {\n      \"@id\": \"toast:takeoutTimeBeforeClose\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"thursday\": {\n      \"@id\": \"toast:thursday\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeZone\": {\n      \"@id\": \"toast:timeZone\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"tuesday\": {\n      \"@id\": \"toast:tuesday\",\n      \"@type\": \"xsd:string\"\n    },\n    \"twitter\": {\n      \"@id\": \"toast:twitter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\"\n    },\n    \"urls\": {\n      \"@id\": \"toast:urls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"website\": {\n      \"@id\": \"toast:website\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wednesday\": {\n      \"@id\": \"toast:wednesday\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weekSchedule\": {\n      \"@id\": \"toast:weekSchedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"width\": {\n      \"@id\": \"toast:width\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"zipCode\": {\n      \"@id\": \"toast:zipCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/json-ld/toast-restaurants-context.jsonld
tags:
- Food Service
- Point of Sale
- Restaurants
- Hospitality
- JSON-LD
- Linked Data
- Semantic Web
---
