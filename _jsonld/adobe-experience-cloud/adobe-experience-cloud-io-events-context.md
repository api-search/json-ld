---
api_specs:
- filename: adobe-analytics-api-openapi.yml
  format: yaml
  label: Adobe Analytics 2.0 API
  slug: analytics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/openapi/adobe-analytics-api-openapi.yml
- filename: adobe-experience-platform-api-openapi.yml
  format: yaml
  label: Adobe Experience Platform API
  slug: experience-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/openapi/adobe-experience-platform-api-openapi.yml
- filename: adobe-target-api-openapi.yml
  format: yaml
  label: Adobe Target API
  slug: target-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/openapi/adobe-target-api-openapi.yml
- filename: adobe-journey-optimizer-api-openapi.yml
  format: yaml
  label: Adobe Journey Optimizer API
  slug: journey-optimizer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/openapi/adobe-journey-optimizer-api-openapi.yml
- filename: adobe-campaign-api-openapi.yml
  format: yaml
  label: Adobe Campaign API
  slug: campaign-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/openapi/adobe-campaign-api-openapi.yml
- filename: adobe-io-events-asyncapi.yml
  format: yaml
  label: Adobe I/O Events
  slug: io-events
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/asyncapi/adobe-io-events-asyncapi.yml
class_count: 10
classes:
- Adobe Experience Cloud Event
- Adobe Experience Cloud Campaign
- Adobe Experience Cloud Offer
- Adobe Experience Cloud Journey
- Adobe Experience Cloud Segment
- Adobe Experience Cloud Profile
- name
- version
- description
- email
context_file: json-ld/adobe-experience-cloud-io-events-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/json-ld/adobe-experience-cloud-io-events-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Experience Cloud Io Events from Adobe Experience Cloud.
layout: jsonld
name: Adobe Experience Cloud Io Events Context
namespaces:
- prefix: aec
  uri: https://developer.adobe.com/schema/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: schema
  type: reference
- container: ''
  name: eventId
  type: string
- container: ''
  name: eventType
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: identityMap
  type: reference
- container: ''
  name: web
  type: reference
- container: ''
  name: webPageDetails
  type: reference
- container: ''
  name: URL
  type: reference
- container: ''
  name: siteSection
  type: string
- container: ''
  name: isHomePage
  type: boolean
- container: ''
  name: webInteraction
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: webReferrer
  type: reference
- container: ''
  name: commerce
  type: reference
- container: ''
  name: purchases
  type: reference
- container: ''
  name: value
  type: decimal
- container: ''
  name: order
  type: reference
- container: ''
  name: purchaseID
  type: string
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: priceTotal
  type: decimal
- container: set
  name: payments
  type: string
- container: ''
  name: paymentType
  type: string
- container: ''
  name: paymentAmount
  type: decimal
- container: set
  name: productListItems
  type: string
- container: ''
  name: SKU
  type: string
- container: ''
  name: quantity
  type: integer
- container: ''
  name: device
  type: reference
- container: ''
  name: manufacturer
  type: string
- container: ''
  name: model
  type: string
- container: ''
  name: screenHeight
  type: integer
- container: ''
  name: screenWidth
  type: integer
- container: ''
  name: environment
  type: reference
- container: ''
  name: browserDetails
  type: reference
- container: ''
  name: userAgent
  type: string
- container: ''
  name: operatingSystem
  type: string
- container: ''
  name: operatingSystemVersion
  type: string
- container: ''
  name: ipV4
  type: string
- container: ''
  name: source
  type: reference
- container: ''
  name: datasetId
  type: string
- container: ''
  name: campaignId
  type: string
- container: ''
  name: channel
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: audience
  type: reference
- container: ''
  name: segmentId
  type: string
- container: ''
  name: estimatedSize
  type: integer
- container: ''
  name: content
  type: reference
- container: ''
  name: subject
  type: string
- container: ''
  name: body
  type: string
- container: ''
  name: templateId
  type: string
- container: ''
  name: sender
  type: reference
- container: ''
  name: schedule
  type: reference
- container: ''
  name: startDate
  type: dateTime
- container: ''
  name: endDate
  type: dateTime
- container: ''
  name: timezone
  type: string
- container: ''
  name: recurring
  type: boolean
- container: ''
  name: metrics
  type: reference
- container: ''
  name: sent
  type: integer
- container: ''
  name: delivered
  type: integer
- container: ''
  name: opened
  type: integer
- container: ''
  name: clicked
  type: integer
- container: ''
  name: bounced
  type: integer
- container: ''
  name: unsubscribed
  type: integer
- container: ''
  name: created
  type: dateTime
- container: ''
  name: lastModified
  type: dateTime
- container: ''
  name: offerId
  type: string
- container: ''
  name: offerType
  type: string
- container: set
  name: representations
  type: string
- container: ''
  name: placementId
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: eligibilityRule
  type: reference
- container: ''
  name: ruleId
  type: string
- container: ''
  name: priority
  type: integer
- container: ''
  name: cappingConstraint
  type: reference
- container: ''
  name: maxImpressions
  type: integer
- container: ''
  name: scope
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: journeyId
  type: string
- container: ''
  name: entryCondition
  type: reference
- container: ''
  name: frequency
  type: string
- container: set
  name: activities
  type: string
- container: ''
  name: activityId
  type: string
- container: ''
  name: configuration
  type: reference
- container: ''
  name: nextActivityId
  type: string
- container: ''
  name: totalEntered
  type: integer
- container: ''
  name: currentlyInJourney
  type: integer
- container: ''
  name: totalExited
  type: integer
- container: ''
  name: totalErrored
  type: integer
- container: ''
  name: publishedAt
  type: dateTime
- container: ''
  name: expression
  type: reference
- container: ''
  name: format
  type: string
- container: ''
  name: evaluationType
  type: string
- container: ''
  name: mergePolicyId
  type: string
- container: ''
  name: profileCount
  type: integer
- container: ''
  name: owner
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: lastEvaluated
  type: dateTime
- container: ''
  name: profileId
  type: string
- container: ''
  name: person
  type: reference
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: fullName
  type: string
- container: ''
  name: birthDate
  type: date
- container: ''
  name: gender
  type: string
- container: ''
  name: personalEmail
  type: reference
- container: ''
  name: address
  type: string
- container: ''
  name: primary
  type: boolean
- container: ''
  name: mobilePhone
  type: reference
- container: ''
  name: number
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: homeAddress
  type: reference
- container: ''
  name: street1
  type: string
- container: ''
  name: street2
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: stateProvince
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: segmentMembership
  type: reference
- container: ''
  name: consents
  type: reference
- container: ''
  name: marketing
  type: reference
- container: ''
  name: val
  type: string
- container: ''
  name: push
  type: reference
- container: ''
  name: sms
  type: reference
property_count: 122
provider_name: Adobe Experience Cloud
provider_slug: adobe-experience-cloud
slug: adobe-experience-cloud-io-events-context
source_filename: adobe-experience-cloud-io-events-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aec\": \"https://developer.adobe.com/schema/\",\n    \"schema\": {\n      \"@id\": \"aec:schema\",\n      \"@type\": \"@id\"\n    },\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Adobe Experience Cloud Event\": \"aec:Adobe Experience Cloud Event\",\n    \"Adobe Experience Cloud Campaign\": \"aec:Adobe Experience Cloud Campaign\",\n    \"Adobe Experience Cloud Offer\": \"aec:Adobe Experience Cloud Offer\",\n    \"Adobe Experience Cloud Journey\": \"aec:Adobe Experience Cloud Journey\",\n    \"Adobe Experience Cloud Segment\": \"aec:Adobe Experience Cloud Segment\",\n    \"Adobe Experience Cloud Profile\": \"aec:Adobe Experience Cloud Profile\",\n    \"eventId\": {\n      \"@id\": \"aec:eventId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"aec:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n     \
  \ \"@id\": \"aec:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"identityMap\": {\n      \"@id\": \"aec:identityMap\",\n      \"@type\": \"@id\"\n    },\n    \"web\": {\n      \"@id\": \"aec:web\",\n      \"@type\": \"@id\"\n    },\n    \"webPageDetails\": {\n      \"@id\": \"aec:webPageDetails\",\n      \"@type\": \"@id\"\n    },\n    \"URL\": {\n      \"@id\": \"aec:URL\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"siteSection\": {\n      \"@id\": \"aec:siteSection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isHomePage\": {\n      \"@id\": \"aec:isHomePage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"webInteraction\": {\n      \"@id\": \"aec:webInteraction\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"aec:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webReferrer\": {\n      \"@id\": \"aec:webReferrer\",\n      \"@type\": \"@id\"\n    },\n    \"commerce\": {\n      \"@id\": \"aec:commerce\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"purchases\": {\n      \"@id\": \"aec:purchases\",\n      \"@type\": \"@id\"\n    },\n    \"value\": {\n      \"@id\": \"aec:value\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"order\": {\n      \"@id\": \"aec:order\",\n      \"@type\": \"@id\"\n    },\n    \"purchaseID\": {\n      \"@id\": \"aec:purchaseID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"aec:currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priceTotal\": {\n      \"@id\": \"aec:priceTotal\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"payments\": {\n      \"@id\": \"aec:payments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentType\": {\n      \"@id\": \"aec:paymentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentAmount\": {\n      \"@id\": \"aec:paymentAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"productListItems\": {\n      \"@id\": \"aec:productListItems\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SKU\": {\n      \"@id\": \"aec:SKU\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"aec:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"device\": {\n      \"@id\": \"aec:device\",\n      \"@type\": \"@id\"\n    },\n    \"manufacturer\": {\n      \"@id\": \"aec:manufacturer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model\": {\n      \"@id\": \"aec:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"screenHeight\": {\n      \"@id\": \"aec:screenHeight\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"screenWidth\": {\n      \"@id\": \"aec:screenWidth\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"environment\": {\n      \"@id\": \"aec:environment\",\n      \"@type\": \"@id\"\n    },\n    \"browserDetails\": {\n      \"@id\": \"aec:browserDetails\",\n      \"@type\": \"@id\"\n    },\n    \"version\": \"schema:version\",\n    \"userAgent\":\
  \ {\n      \"@id\": \"aec:userAgent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operatingSystem\": {\n      \"@id\": \"aec:operatingSystem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operatingSystemVersion\": {\n      \"@id\": \"aec:operatingSystemVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipV4\": {\n      \"@id\": \"aec:ipV4\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"aec:source\",\n      \"@type\": \"@id\"\n    },\n    \"datasetId\": {\n      \"@id\": \"aec:datasetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"campaignId\": {\n      \"@id\": \"aec:campaignId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"channel\": {\n      \"@id\": \"aec:channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aec:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"audience\": {\n      \"@id\": \"aec:audience\",\n      \"@type\": \"@id\"\n\
  \    },\n    \"segmentId\": {\n      \"@id\": \"aec:segmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"estimatedSize\": {\n      \"@id\": \"aec:estimatedSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"content\": {\n      \"@id\": \"aec:content\",\n      \"@type\": \"@id\"\n    },\n    \"subject\": {\n      \"@id\": \"aec:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"body\": {\n      \"@id\": \"aec:body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templateId\": {\n      \"@id\": \"aec:templateId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sender\": {\n      \"@id\": \"aec:sender\",\n      \"@type\": \"@id\"\n    },\n    \"email\": \"schema:email\",\n    \"schedule\": {\n      \"@id\": \"aec:schedule\",\n      \"@type\": \"@id\"\n    },\n    \"startDate\": {\n      \"@id\": \"aec:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endDate\": {\n      \"@id\": \"aec:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"timezone\"\
  : {\n      \"@id\": \"aec:timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurring\": {\n      \"@id\": \"aec:recurring\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"metrics\": {\n      \"@id\": \"aec:metrics\",\n      \"@type\": \"@id\"\n    },\n    \"sent\": {\n      \"@id\": \"aec:sent\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"delivered\": {\n      \"@id\": \"aec:delivered\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"opened\": {\n      \"@id\": \"aec:opened\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"clicked\": {\n      \"@id\": \"aec:clicked\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bounced\": {\n      \"@id\": \"aec:bounced\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"unsubscribed\": {\n      \"@id\": \"aec:unsubscribed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"created\": {\n      \"@id\": \"aec:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastModified\": {\n      \"@id\": \"aec:lastModified\",\n\
  \      \"@type\": \"xsd:dateTime\"\n    },\n    \"offerId\": {\n      \"@id\": \"aec:offerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offerType\": {\n      \"@id\": \"aec:offerType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"representations\": {\n      \"@id\": \"aec:representations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"placementId\": {\n      \"@id\": \"aec:placementId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"aec:contentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eligibilityRule\": {\n      \"@id\": \"aec:eligibilityRule\",\n      \"@type\": \"@id\"\n    },\n    \"ruleId\": {\n      \"@id\": \"aec:ruleId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"aec:priority\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cappingConstraint\": {\n      \"@id\": \"aec:cappingConstraint\",\n      \"@type\": \"@id\"\n    },\n    \"maxImpressions\"\
  : {\n      \"@id\": \"aec:maxImpressions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"scope\": {\n      \"@id\": \"aec:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"aec:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"journeyId\": {\n      \"@id\": \"aec:journeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entryCondition\": {\n      \"@id\": \"aec:entryCondition\",\n      \"@type\": \"@id\"\n    },\n    \"frequency\": {\n      \"@id\": \"aec:frequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activities\": {\n      \"@id\": \"aec:activities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activityId\": {\n      \"@id\": \"aec:activityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configuration\": {\n      \"@id\": \"aec:configuration\",\n      \"@type\": \"@id\"\n    },\n    \"nextActivityId\": {\n      \"@id\": \"aec:nextActivityId\",\n     \
  \ \"@type\": \"xsd:string\"\n    },\n    \"totalEntered\": {\n      \"@id\": \"aec:totalEntered\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currentlyInJourney\": {\n      \"@id\": \"aec:currentlyInJourney\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalExited\": {\n      \"@id\": \"aec:totalExited\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalErrored\": {\n      \"@id\": \"aec:totalErrored\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"publishedAt\": {\n      \"@id\": \"aec:publishedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"expression\": {\n      \"@id\": \"aec:expression\",\n      \"@type\": \"@id\"\n    },\n    \"format\": {\n      \"@id\": \"aec:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"evaluationType\": {\n      \"@id\": \"aec:evaluationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mergePolicyId\": {\n      \"@id\": \"aec:mergePolicyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profileCount\": {\n    \
  \  \"@id\": \"aec:profileCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"owner\": {\n      \"@id\": \"aec:owner\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"aec:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastEvaluated\": {\n      \"@id\": \"aec:lastEvaluated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"profileId\": {\n      \"@id\": \"aec:profileId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"person\": {\n      \"@id\": \"aec:person\",\n      \"@type\": \"@id\"\n    },\n    \"firstName\": {\n      \"@id\": \"aec:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"aec:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fullName\": {\n      \"@id\": \"aec:fullName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"birthDate\": {\n      \"@id\": \"aec:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"gender\": {\n      \"@id\": \"aec:gender\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"personalEmail\": {\n      \"@id\": \"aec:personalEmail\",\n      \"@type\": \"@id\"\n    },\n    \"address\": {\n      \"@id\": \"aec:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primary\": {\n      \"@id\": \"aec:primary\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"mobilePhone\": {\n      \"@id\": \"aec:mobilePhone\",\n      \"@type\": \"@id\"\n    },\n    \"number\": {\n      \"@id\": \"aec:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"aec:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"homeAddress\": {\n      \"@id\": \"aec:homeAddress\",\n      \"@type\": \"@id\"\n    },\n    \"street1\": {\n      \"@id\": \"aec:street1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"street2\": {\n      \"@id\": \"aec:street2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"aec:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateProvince\": {\n      \"@id\": \"\
  aec:stateProvince\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"aec:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"aec:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentMembership\": {\n      \"@id\": \"aec:segmentMembership\",\n      \"@type\": \"@id\"\n    },\n    \"consents\": {\n      \"@id\": \"aec:consents\",\n      \"@type\": \"@id\"\n    },\n    \"marketing\": {\n      \"@id\": \"aec:marketing\",\n      \"@type\": \"@id\"\n    },\n    \"val\": {\n      \"@id\": \"aec:val\",\n      \"@type\": \"xsd:string\"\n    },\n    \"push\": {\n      \"@id\": \"aec:push\",\n      \"@type\": \"@id\"\n    },\n    \"sms\": {\n      \"@id\": \"aec:sms\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/json-ld/adobe-experience-cloud-io-events-context.jsonld
tags:
- Analytics
- Customer Experience
- Digital Marketing
- Personalization
- Campaign Management
- Journey Orchestration
- JSON-LD
- Linked Data
- Semantic Web
---
