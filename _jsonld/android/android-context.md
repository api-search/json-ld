---
api_specs:
- filename: google-play-developer-api.yml
  format: yaml
  label: Google Play Developer APIs
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/android/refs/heads/main/openapi/google-play-developer-api.yml
class_count: 0
classes: []
context_file: json-ld/android-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/android/refs/heads/main/json-ld/android-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Android from Android.
layout: jsonld
name: Android Context
namespaces:
- prefix: android
  uri: https://developer.android.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: gplay
  uri: https://developers.google.com/android-publisher/ns/
- prefix: dc
  uri: http://purl.org/dc/elements/1.1/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdf
  uri: http://www.w3.org/1999/02/22-rdf-syntax-ns#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: AndroidApplication
  type: ''
- container: ''
  name: AndroidPermission
  type: ''
- container: ''
  name: AndroidActivity
  type: ''
- container: ''
  name: AndroidService
  type: ''
- container: ''
  name: AndroidBroadcastReceiver
  type: ''
- container: ''
  name: AndroidContentProvider
  type: ''
- container: ''
  name: IntentFilter
  type: ''
- container: ''
  name: PlayStoreListing
  type: ''
- container: ''
  name: InAppProduct
  type: ''
- container: ''
  name: SubscriptionProduct
  type: ''
- container: ''
  name: BasePlan
  type: ''
- container: ''
  name: SubscriptionOffer
  type: ''
- container: ''
  name: ProductPurchase
  type: ''
- container: ''
  name: SubscriptionPurchase
  type: ''
- container: ''
  name: Review
  type: ''
- container: ''
  name: DeveloperReply
  type: ''
- container: ''
  name: DataSafety
  type: ''
- container: ''
  name: DeviceMetadata
  type: ''
- container: ''
  name: ApiIntegration
  type: ''
property_count: 19
provider_name: Android
provider_slug: android
slug: android-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://developer.android.com/ns/\",\n    \"android\": \"https://developer.android.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"gplay\": \"https://developers.google.com/android-publisher/ns/\",\n    \"dc\": \"http://purl.org/dc/elements/1.1/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdf\": \"http://www.w3.org/1999/02/22-rdf-syntax-ns#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"AndroidApplication\": {\n      \"@id\": \"android:AndroidApplication\",\n      \"@context\": {\n        \"packageName\": {\n          \"@id\": \"android:packageName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"appName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"versionCode\": {\n          \"@id\": \"android:versionCode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"versionName\": {\n          \"@id\": \"schema:softwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"minSdkVersion\": {\n          \"@id\": \"android:minSdkVersion\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"targetSdkVersion\": {\n          \"@id\": \"android:targetSdkVersion\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"compileSdkVersion\": {\n          \"@id\": \"android:compileSdkVersion\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"applicationCategory\": {\n          \"@id\": \"schema:applicationCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"operatingSystem\": {\n          \"@id\": \"schema:operatingSystem\",\n          \"@type\": \"xsd:string\"\n        },\n        \"downloadUrl\": {\n          \"@id\": \"schema:downloadUrl\",\n    \
  \      \"@type\": \"@id\"\n        },\n        \"installUrl\": {\n          \"@id\": \"schema:installUrl\",\n          \"@type\": \"@id\"\n        },\n        \"datePublished\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:date\"\n        },\n        \"dateModified\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"AndroidPermission\": {\n      \"@id\": \"android:AndroidPermission\",\n      \"@context\": {\n        \"permissionName\": {\n          \"@id\": \"android:permissionName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"protectionLevel\": {\n          \"@id\": \"android:protectionLevel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"permissionGroup\": {\n          \"@id\": \"android:permissionGroup\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isRequired\": {\n          \"@id\": \"android:isRequired\",\n          \"@type\": \"xsd:boolean\"\
  \n        },\n        \"maxSdkVersion\": {\n          \"@id\": \"android:maxSdkVersion\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"AndroidActivity\": {\n      \"@id\": \"android:AndroidActivity\",\n      \"@context\": {\n        \"className\": {\n          \"@id\": \"android:className\",\n          \"@type\": \"xsd:string\"\n        },\n        \"exported\": {\n          \"@id\": \"android:exported\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"launchMode\": {\n          \"@id\": \"android:launchMode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"intentFilter\": {\n          \"@id\": \"android:intentFilter\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"AndroidService\": {\n      \"@id\": \"android:AndroidService\",\n      \"@context\": {\n        \"className\": {\n          \"@id\": \"android:className\",\n          \"@type\": \"xsd:string\"\n        },\n        \"exported\": {\n          \"@id\"\
  : \"android:exported\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"foregroundServiceType\": {\n          \"@id\": \"android:foregroundServiceType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"AndroidBroadcastReceiver\": {\n      \"@id\": \"android:AndroidBroadcastReceiver\",\n      \"@context\": {\n        \"className\": {\n          \"@id\": \"android:className\",\n          \"@type\": \"xsd:string\"\n        },\n        \"exported\": {\n          \"@id\": \"android:exported\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"AndroidContentProvider\": {\n      \"@id\": \"android:AndroidContentProvider\",\n      \"@context\": {\n        \"className\": {\n          \"@id\": \"android:className\",\n          \"@type\": \"xsd:string\"\n        },\n        \"authorities\": {\n          \"@id\": \"android:authorities\",\n          \"@type\": \"xsd:string\"\n        },\n        \"exported\": {\n          \"@id\": \"android:exported\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"IntentFilter\": {\n      \"@id\": \"android:IntentFilter\",\n      \"@context\": {\n        \"action\": {\n          \"@id\": \"android:action\",\n          \"@type\": \"xsd:string\",\n          \"@container\": \"@set\"\n        },\n        \"category\": {\n          \"@id\": \"android:category\",\n          \"@type\": \"xsd:string\",\n          \"@container\": \"@set\"\n        },\n        \"dataScheme\": {\n          \"@id\": \"android:dataScheme\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dataHost\": {\n          \"@id\": \"android:dataHost\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dataMimeType\": {\n          \"@id\": \"android:dataMimeType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"PlayStoreListing\": {\n      \"@id\": \"gplay:PlayStoreListing\",\n      \"@context\": {\n        \"title\": {\n          \"@id\": \"schema:name\",\n   \
  \       \"@type\": \"xsd:string\"\n        },\n        \"shortDescription\": {\n          \"@id\": \"schema:abstract\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fullDescription\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"schema:applicationCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contentRating\": {\n          \"@id\": \"schema:contentRating\",\n          \"@type\": \"xsd:string\"\n        },\n        \"price\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:string\"\n        },\n        \"priceCurrency\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isFree\": {\n          \"@id\": \"schema:isAccessibleForFree\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"screenshot\": {\n          \"@id\": \"schema:screenshot\",\n          \"@type\": \"@id\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"icon\": {\n          \"@id\": \"schema:thumbnailUrl\",\n          \"@type\": \"@id\"\n        },\n        \"videoUrl\": {\n          \"@id\": \"schema:video\",\n          \"@type\": \"@id\"\n        },\n        \"privacyPolicyUrl\": {\n          \"@id\": \"gplay:privacyPolicyUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"InAppProduct\": {\n      \"@id\": \"gplay:InAppProduct\",\n      \"@context\": {\n        \"productId\": {\n          \"@id\": \"gplay:productId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"productType\": {\n          \"@id\": \"gplay:productType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"gplay:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"price\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:string\"\n        },\n        \"priceCurrency\": {\n          \"@id\": \"\
  schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"SubscriptionProduct\": {\n      \"@id\": \"gplay:SubscriptionProduct\",\n      \"@context\": {\n        \"productId\": {\n          \"@id\": \"gplay:productId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"basePlan\": {\n          \"@id\": \"gplay:basePlan\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"offer\": {\n          \"@id\": \"gplay:offer\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"BasePlan\": {\n      \"@id\": \"gplay:BasePlan\",\n      \"@context\": {\n        \"basePlanId\": {\n          \"@id\": \"gplay:basePlanId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"billingPeriod\": {\n          \"@id\": \"gplay:billingPeriod\",\n        \
  \  \"@type\": \"xsd:duration\"\n        },\n        \"renewalType\": {\n          \"@id\": \"gplay:renewalType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"price\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:string\"\n        },\n        \"priceCurrency\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"gplay:state\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"SubscriptionOffer\": {\n      \"@id\": \"gplay:SubscriptionOffer\",\n      \"@context\": {\n        \"offerId\": {\n          \"@id\": \"gplay:offerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"basePlanId\": {\n          \"@id\": \"gplay:basePlanId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"phase\": {\n          \"@id\": \"gplay:phase\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        },\n        \"\
  state\": {\n          \"@id\": \"gplay:state\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ProductPurchase\": {\n      \"@id\": \"gplay:ProductPurchase\",\n      \"@context\": {\n        \"purchaseToken\": {\n          \"@id\": \"gplay:purchaseToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"orderId\": {\n          \"@id\": \"gplay:orderId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"purchaseTime\": {\n          \"@id\": \"gplay:purchaseTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"purchaseState\": {\n          \"@id\": \"gplay:purchaseState\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"consumptionState\": {\n          \"@id\": \"gplay:consumptionState\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"acknowledgementState\": {\n          \"@id\": \"gplay:acknowledgementState\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"regionCode\": {\n       \
  \   \"@id\": \"gplay:regionCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"productId\": {\n          \"@id\": \"gplay:productId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"quantity\": {\n          \"@id\": \"gplay:quantity\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"SubscriptionPurchase\": {\n      \"@id\": \"gplay:SubscriptionPurchase\",\n      \"@context\": {\n        \"purchaseToken\": {\n          \"@id\": \"gplay:purchaseToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"orderId\": {\n          \"@id\": \"gplay:orderId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startTime\": {\n          \"@id\": \"gplay:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expiryTime\": {\n          \"@id\": \"gplay:expiryTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"autoRenewing\": {\n          \"@id\": \"gplay:autoRenewing\",\n          \"@type\"\
  : \"xsd:boolean\"\n        },\n        \"priceCurrency\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"priceAmountMicros\": {\n          \"@id\": \"gplay:priceAmountMicros\",\n          \"@type\": \"xsd:long\"\n        },\n        \"paymentState\": {\n          \"@id\": \"gplay:paymentState\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"cancelReason\": {\n          \"@id\": \"gplay:cancelReason\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"subscriptionState\": {\n          \"@id\": \"gplay:subscriptionState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"acknowledgementState\": {\n          \"@id\": \"gplay:acknowledgementState\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"linkedPurchaseToken\": {\n          \"@id\": \"gplay:linkedPurchaseToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"countryCode\": {\n          \"@id\": \"gplay:countryCode\"\
  ,\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Review\": {\n      \"@id\": \"gplay:Review\",\n      \"@context\": {\n        \"reviewId\": {\n          \"@id\": \"gplay:reviewId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"authorName\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"xsd:string\"\n        },\n        \"reviewText\": {\n          \"@id\": \"schema:reviewBody\",\n          \"@type\": \"xsd:string\"\n        },\n        \"starRating\": {\n          \"@id\": \"schema:ratingValue\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"reviewerLanguage\": {\n          \"@id\": \"schema:inLanguage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastModified\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"appVersionCode\": {\n          \"@id\": \"android:versionCode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"\
  appVersionName\": {\n          \"@id\": \"schema:softwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"thumbsUpCount\": {\n          \"@id\": \"schema:upvoteCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"developerReply\": {\n          \"@id\": \"gplay:developerReply\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"DeveloperReply\": {\n      \"@id\": \"gplay:DeveloperReply\",\n      \"@context\": {\n        \"replyText\": {\n          \"@id\": \"schema:text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastModified\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DataSafety\": {\n      \"@id\": \"android:DataSafety\",\n      \"@context\": {\n        \"dataCollected\": {\n          \"@id\": \"android:dataCollected\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"dataShared\": {\n    \
  \      \"@id\": \"android:dataShared\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"dataEncryptedInTransit\": {\n          \"@id\": \"android:dataEncryptedInTransit\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"dataCanBeDeleted\": {\n          \"@id\": \"android:dataCanBeDeleted\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"DeviceMetadata\": {\n      \"@id\": \"android:DeviceMetadata\",\n      \"@context\": {\n        \"manufacturer\": {\n          \"@id\": \"schema:manufacturer\",\n          \"@type\": \"xsd:string\"\n        },\n        \"deviceClass\": {\n          \"@id\": \"android:deviceClass\",\n          \"@type\": \"xsd:string\"\n        },\n        \"productName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"screenWidthPx\": {\n          \"@id\": \"android:screenWidthPx\",\n          \"@type\": \"xsd:integer\"\n        },\n   \
  \     \"screenHeightPx\": {\n          \"@id\": \"android:screenHeightPx\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"screenDensityDpi\": {\n          \"@id\": \"android:screenDensityDpi\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"ramMb\": {\n          \"@id\": \"android:ramMb\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"ApiIntegration\": {\n      \"@id\": \"android:ApiIntegration\",\n      \"@context\": {\n        \"apiName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"apiVersion\": {\n          \"@id\": \"schema:softwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"integrationType\": {\n          \"@id\": \"android:integrationType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"documentationUrl\": {\n          \"@id\": \"schema:documentation\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/android/refs/heads/main/json-ld/android-context.jsonld
tags:
- AI
- Android
- Automotive
- Google
- Machine Learning
- Mobile Development
- SDK
- TV
- Wearables
- JSON-LD
- Linked Data
- Semantic Web
---
