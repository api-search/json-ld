---
api_specs:
- filename: clear-channel-outdoor-direct-openapi.yml
  format: yaml
  label: Clear Channel Outdoor Automated Direct API
  slug: clear-channel-outdoor-direct
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/clear-channel-outdoor-hldgs/refs/heads/main/openapi/clear-channel-outdoor-direct-openapi.yml
class_count: 31
classes:
- OutOfHomeMediaCompany
- DemandSidePlatform
- SupplySidePlatform
- MeasurementProvider
- ProgrammaticDOOHIntegration
- DigitalOutOfHomeDisplay
- AudienceDataSuite
- Order
- Line
- Product
- Account
- name
- url
- description
- identifier
- billboard
- streetFurniture
- transit
- digitalOutOfHome
- airport
- guaranteed
- nonGuaranteed
- privateMarketplace
- openExchange
- OpenRTBBidRequest
- OpenRTBBidResponse
- DoohObject
- screen
- OrderId
- LineId
- ProductId
context_file: json-ld/clear-channel-outdoor-hldgs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/clear-channel-outdoor-hldgs/refs/heads/main/json-ld/clear-channel-outdoor-hldgs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Clear Channel Outdoor Hldgs from Clear Channel Outdoor Holdings.
layout: jsonld
name: Clear Channel Outdoor Hldgs Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: openrtb
  uri: https://iabtechlab.com/standards/openrtb/#
- prefix: opendirect
  uri: https://raw.githubusercontent.com/Outsmart-OOH/ooh_open_direct/master/schema/v1/
- prefix: cco
  uri: https://www.clearchanneloutdoor.com/vocab/
properties:
- container: ''
  name: ticker
  type: schema:Text
- container: ''
  name: fortune1000Rank
  type: schema:Integer
- container: set
  name: operatesInventory
  type: reference
- container: ''
  name: inventoryFormat
  type: schema:Text
- container: set
  name: dspPartner
  type: reference
- container: set
  name: sspPartner
  type: reference
- container: set
  name: measurementPartner
  type: reference
- container: set
  name: audienceDataPartner
  type: reference
- container: ''
  name: biddingProtocol
  type: schema:Text
- container: set
  name: supportedAdFormats
  type: schema:Text
- container: ''
  name: transactionType
  type: schema:Text
- container: ''
  name: audienceMeasurement
  type: reference
- container: ''
  name: attributionMethod
  type: schema:Text
- container: ''
  name: impressionMultiplier
  type: schema:Number
- container: ''
  name: venueType
  type: schema:Text
- container: ''
  name: venueTypeTax
  type: schema:Integer
- container: ''
  name: fixedScreenSize
  type: reference
- container: ''
  name: minBidToWin
  type: schema:Number
- container: ''
  name: geoPosition
  type: schema:GeoCoordinates
- container: ''
  name: marketArea
  type: schema:Text
- container: ''
  name: Budget
  type: schema:Number
- container: ''
  name: Currency
  type: schema:Text
- container: ''
  name: OrderStatus
  type: schema:Text
property_count: 23
provider_name: Clear Channel Outdoor Holdings
provider_slug: clear-channel-outdoor-hldgs
slug: clear-channel-outdoor-hldgs-context
source_filename: clear-channel-outdoor-hldgs-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"openrtb\": \"https://iabtechlab.com/standards/openrtb/#\",\n    \"opendirect\": \"https://raw.githubusercontent.com/Outsmart-OOH/ooh_open_direct/master/schema/v1/\",\n    \"cco\": \"https://www.clearchanneloutdoor.com/vocab/\",\n\n    \"OutOfHomeMediaCompany\": \"schema:Organization\",\n    \"DemandSidePlatform\": \"cco:DemandSidePlatform\",\n    \"SupplySidePlatform\": \"cco:SupplySidePlatform\",\n    \"MeasurementProvider\": \"cco:MeasurementProvider\",\n    \"ProgrammaticDOOHIntegration\": \"cco:ProgrammaticDOOHIntegration\",\n    \"DigitalOutOfHomeDisplay\": \"cco:DigitalOutOfHomeDisplay\",\n    \"AudienceDataSuite\": \"cco:AudienceDataSuite\",\n    \"Order\": \"opendirect:resources/order/order_object.json\",\n    \"Line\": \"opendirect:resources/line/line_object.json\",\n    \"Product\": \"opendirect:resources/product/product_object.json\",\n    \"Account\": \"opendirect:resources/account/account_object.json\"\
  ,\n\n    \"name\": \"schema:name\",\n    \"url\": \"schema:url\",\n    \"description\": \"schema:description\",\n    \"identifier\": \"schema:identifier\",\n    \"ticker\": {\n      \"@id\": \"schema:tickerSymbol\",\n      \"@type\": \"schema:Text\"\n    },\n    \"fortune1000Rank\": {\n      \"@id\": \"cco:fortune1000Rank\",\n      \"@type\": \"schema:Integer\"\n    },\n\n    \"operatesInventory\": {\n      \"@id\": \"cco:operatesInventory\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"inventoryFormat\": {\n      \"@id\": \"cco:inventoryFormat\",\n      \"@type\": \"schema:Text\"\n    },\n    \"billboard\": \"cco:billboard\",\n    \"streetFurniture\": \"cco:streetFurniture\",\n    \"transit\": \"cco:transit\",\n    \"digitalOutOfHome\": \"cco:digitalOutOfHome\",\n    \"airport\": \"cco:airport\",\n\n    \"dspPartner\": {\n      \"@id\": \"cco:dspPartner\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"sspPartner\": {\n      \"@id\"\
  : \"cco:sspPartner\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"measurementPartner\": {\n      \"@id\": \"cco:measurementPartner\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"audienceDataPartner\": {\n      \"@id\": \"cco:audienceDataPartner\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"biddingProtocol\": {\n      \"@id\": \"cco:biddingProtocol\",\n      \"@type\": \"schema:Text\"\n    },\n    \"supportedAdFormats\": {\n      \"@id\": \"cco:supportedAdFormats\",\n      \"@type\": \"schema:Text\",\n      \"@container\": \"@set\"\n    },\n    \"transactionType\": {\n      \"@id\": \"cco:transactionType\",\n      \"@type\": \"schema:Text\"\n    },\n    \"guaranteed\": \"cco:guaranteed\",\n    \"nonGuaranteed\": \"cco:nonGuaranteed\",\n    \"privateMarketplace\": \"cco:privateMarketplace\",\n    \"openExchange\": \"cco:openExchange\",\n\n    \"audienceMeasurement\": {\n      \"@id\": \"cco:audienceMeasurement\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"attributionMethod\": {\n      \"@id\": \"cco:attributionMethod\",\n      \"@type\": \"schema:Text\"\n    },\n    \"impressionMultiplier\": {\n      \"@id\": \"cco:impressionMultiplier\",\n      \"@type\": \"schema:Number\"\n    },\n\n    \"OpenRTBBidRequest\": \"openrtb:BidRequest\",\n    \"OpenRTBBidResponse\": \"openrtb:BidResponse\",\n    \"DoohObject\": \"openrtb:DOOH\",\n    \"venueType\": {\n      \"@id\": \"openrtb:venuetype\",\n      \"@type\": \"schema:Text\"\n    },\n    \"venueTypeTax\": {\n      \"@id\": \"openrtb:venuetypetax\",\n      \"@type\": \"schema:Integer\"\n    },\n    \"screen\": \"openrtb:screen\",\n    \"fixedScreenSize\": {\n      \"@id\": \"openrtb:fixedscreensize\",\n      \"@type\": \"@id\"\n    },\n    \"minBidToWin\": {\n      \"@id\": \"openrtb:mincpmperimp\",\n      \"@type\": \"schema:Number\"\n    },\n\n    \"geoPosition\": {\n      \"@id\": \"schema:geo\",\n      \"@type\": \"schema:GeoCoordinates\"\n    },\n\
  \    \"marketArea\": {\n      \"@id\": \"cco:marketArea\",\n      \"@type\": \"schema:Text\"\n    },\n\n    \"OrderId\": \"opendirect:resources/order/order_id_string.json\",\n    \"LineId\": \"opendirect:resources/line/line_id_string.json\",\n    \"ProductId\": \"opendirect:resources/product/product_id_string.json\",\n    \"Budget\": {\n      \"@id\": \"opendirect:resources/order/order_object.json#Budget\",\n      \"@type\": \"schema:Number\"\n    },\n    \"Currency\": {\n      \"@id\": \"opendirect:resources/order/order_object.json#Currency\",\n      \"@type\": \"schema:Text\"\n    },\n    \"OrderStatus\": {\n      \"@id\": \"opendirect:resources/order/order_object.json#OrderStatus\",\n      \"@type\": \"schema:Text\"\n    }\n  },\n  \"@graph\": [\n    {\n      \"@id\": \"https://www.clearchanneloutdoor.com/#org\",\n      \"@type\": \"OutOfHomeMediaCompany\",\n      \"name\": \"Clear Channel Outdoor Holdings\",\n      \"url\": \"https://www.clearchanneloutdoor.com\",\n      \"ticker\"\
  : \"CCO\",\n      \"fortune1000Rank\": 1000,\n      \"description\": \"Out-of-home advertising operator running billboards, street furniture, transit, and digital out-of-home displays in the U.S. and select international markets.\",\n      \"operatesInventory\": [\n        \"billboard\",\n        \"streetFurniture\",\n        \"transit\",\n        \"digitalOutOfHome\",\n        \"airport\"\n      ],\n      \"biddingProtocol\": \"OpenRTB 2.6 DOOH\",\n      \"transactionType\": [\n        \"guaranteed\",\n        \"nonGuaranteed\",\n        \"privateMarketplace\",\n        \"openExchange\"\n      ],\n      \"audienceDataPartner\": \"https://www.clearchanneloutdoor.com/#radar\",\n      \"dspPartner\": [\n        \"https://www.adelphic.com/#dsp\",\n        \"https://site.adform.com/#dsp\",\n        \"https://www.adomni.com/#dsp\",\n        \"https://www.adquick.com/#dsp\",\n        \"https://www.campsite.com/#dsp\",\n        \"https://displayce.com/#dsp\",\n        \"https://marketingplatform.google.com/about/display-video-360/#dsp\"\
  ,\n        \"https://hivestack.com/#ssp\",\n        \"https://www.nexxen.com/#dsp\",\n        \"https://www.roku.com/oneview/#dsp\",\n        \"https://outmoove.com/#dsp\",\n        \"https://www.pulsepoint.com/#dsp\",\n        \"https://www.quotient.com/#dsp\",\n        \"https://simpli.fi/#dsp\",\n        \"https://sito.mobi/#dsp\",\n        \"https://www.stackadapt.com/#dsp\",\n        \"https://www.thetradedesk.com/#dsp\",\n        \"https://www.vistarmedia.com/#dsp\",\n        \"https://www.xandr.com/#dsp\",\n        \"https://advertising.yahooinc.com/#dsp\",\n        \"https://www.zetaglobal.com/#dsp\"\n      ]\n    },\n    {\n      \"@id\": \"https://www.clearchanneloutdoor.com/#radar\",\n      \"@type\": \"AudienceDataSuite\",\n      \"name\": \"RADAR\",\n      \"url\": \"https://clearchanneloutdoor.com/radar-data-solutions/\",\n      \"description\": \"Audience and attribution suite for OOH planning, activation, and measurement based on aggregated mobile location data.\",\n  \
  \    \"attributionMethod\": \"MobileLocationPanel\"\n    }\n  ]\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/clear-channel-outdoor-hldgs/refs/heads/main/json-ld/clear-channel-outdoor-hldgs-context.jsonld
tags:
- Advertising
- Out Of Home
- Programmatic
- Digital Out Of Home
- pDOOH
- OpenRTB
- OpenDirect
- JSON-LD
- Linked Data
- Semantic Web
---
