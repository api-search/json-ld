---
class_count: 7
classes:
- name
- description
- identifier
- version
- platform
- publisher
- category
context_file: json-ld/google-chrome-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-chrome/refs/heads/main/json-ld/google-chrome-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Chrome from Google Chrome.
layout: jsonld
name: Google Chrome Context
namespaces:
- prefix: chrome
  uri: https://developer.chrome.com/docs/extensions/schema/
- prefix: chromeManagement
  uri: https://developers.google.com/chrome/management/schema/
- prefix: chromePolicy
  uri: https://developers.google.com/chrome/policy/schema/
- prefix: cws
  uri: https://developer.chrome.com/docs/webstore/schema/
- prefix: cdp
  uri: https://chromedevtools.github.io/devtools-protocol/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: BrowserExtension
  type: ''
- container: ''
  name: ExtensionAction
  type: ''
- container: ''
  name: ServiceWorker
  type: ''
- container: ''
  name: ContentScript
  type: ''
- container: ''
  name: DeclarativeNetRequestRuleset
  type: ''
- container: ''
  name: ChromeWebStoreItem
  type: ''
- container: ''
  name: ManagedDevice
  type: ''
- container: ''
  name: TelemetryDevice
  type: ''
- container: ''
  name: TelemetryEvent
  type: ''
- container: ''
  name: TelemetryUser
  type: ''
- container: ''
  name: ChromePolicy
  type: ''
- container: ''
  name: PolicySchema
  type: ''
- container: ''
  name: DevToolsTarget
  type: ''
- container: ''
  name: CrUXRecord
  type: ''
- container: ''
  name: BuiltInAISession
  type: ''
- container: ''
  name: SafeBrowsingThreat
  type: ''
- container: ''
  name: url
  type: reference
- container: ''
  name: dateCreated
  type: dateTime
- container: ''
  name: dateModified
  type: dateTime
property_count: 19
provider_name: Google Chrome
provider_slug: google-chrome
slug: google-chrome-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"chrome\": \"https://developer.chrome.com/docs/extensions/schema/\",\n    \"chromeManagement\": \"https://developers.google.com/chrome/management/schema/\",\n    \"chromePolicy\": \"https://developers.google.com/chrome/policy/schema/\",\n    \"cws\": \"https://developer.chrome.com/docs/webstore/schema/\",\n    \"cdp\": \"https://chromedevtools.github.io/devtools-protocol/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"BrowserExtension\": {\n      \"@id\": \"chrome:BrowserExtension\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"shortName\": \"schema:alternateName\",\n        \"description\": \"schema:description\",\n        \"version\": \"schema:softwareVersion\",\n        \"versionName\": \"chrome:versionName\",\n        \"manifestVersion\": {\n          \"@id\"\
  : \"chrome:manifestVersion\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"author\": \"schema:author\",\n        \"homepageUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"permissions\": {\n          \"@id\": \"chrome:permissions\",\n          \"@container\": \"@set\"\n        },\n        \"hostPermissions\": {\n          \"@id\": \"chrome:hostPermissions\",\n          \"@container\": \"@set\"\n        },\n        \"optionalPermissions\": {\n          \"@id\": \"chrome:optionalPermissions\",\n          \"@container\": \"@set\"\n        },\n        \"minimumChromeVersion\": \"chrome:minimumChromeVersion\",\n        \"incognito\": \"chrome:incognito\",\n        \"offlineEnabled\": {\n          \"@id\": \"chrome:offlineEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"key\": \"chrome:publicKey\",\n        \"updateUrl\": {\n          \"@id\": \"chrome:updateUrl\",\n          \"@type\": \"@id\"\n        },\n\
  \        \"defaultLocale\": \"chrome:defaultLocale\"\n      }\n    },\n\n    \"ExtensionAction\": {\n      \"@id\": \"chrome:ExtensionAction\",\n      \"@context\": {\n        \"defaultTitle\": \"schema:name\",\n        \"defaultPopup\": \"chrome:defaultPopup\",\n        \"defaultIcon\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ServiceWorker\": {\n      \"@id\": \"chrome:ServiceWorker\",\n      \"@context\": {\n        \"path\": \"chrome:serviceWorkerPath\",\n        \"type\": \"chrome:moduleType\"\n      }\n    },\n\n    \"ContentScript\": {\n      \"@id\": \"chrome:ContentScript\",\n      \"@context\": {\n        \"matches\": {\n          \"@id\": \"chrome:matchPatterns\",\n          \"@container\": \"@set\"\n        },\n        \"excludeMatches\": {\n          \"@id\": \"chrome:excludeMatchPatterns\",\n          \"@container\": \"@set\"\n        },\n        \"js\": {\n          \"@id\": \"chrome:jsFiles\",\n         \
  \ \"@container\": \"@list\"\n        },\n        \"css\": {\n          \"@id\": \"chrome:cssFiles\",\n          \"@container\": \"@list\"\n        },\n        \"runAt\": \"chrome:runAt\",\n        \"allFrames\": {\n          \"@id\": \"chrome:allFrames\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"world\": \"chrome:executionWorld\"\n      }\n    },\n\n    \"DeclarativeNetRequestRuleset\": {\n      \"@id\": \"chrome:DeclarativeNetRequestRuleset\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"enabled\": {\n          \"@id\": \"chrome:rulesetEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"path\": \"chrome:rulesetPath\"\n      }\n    },\n\n    \"ChromeWebStoreItem\": {\n      \"@id\": \"cws:WebStoreItem\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"version\": \"schema:softwareVersion\",\n        \"storeUrl\"\
  : {\n          \"@id\": \"cws:storeUrl\",\n          \"@type\": \"@id\"\n        },\n        \"iconUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"publisher\": \"schema:publisher\",\n        \"category\": \"schema:applicationCategory\",\n        \"rating\": {\n          \"@id\": \"schema:aggregateRating\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"reviewCount\": {\n          \"@id\": \"schema:reviewCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"userCount\": {\n          \"@id\": \"cws:userCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"datePublished\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:date\"\n        },\n        \"dateModified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ManagedDevice\": {\n      \"@id\": \"chromeManagement:ManagedDevice\",\n      \"@context\"\
  : {\n        \"deviceId\": \"schema:identifier\",\n        \"serialNumber\": \"chromeManagement:serialNumber\",\n        \"orgUnitId\": \"chromeManagement:orgUnitId\",\n        \"model\": \"schema:model\",\n        \"osVersion\": \"schema:operatingSystem\",\n        \"lastSync\": {\n          \"@id\": \"chromeManagement:lastSyncTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"annotatedUser\": \"chromeManagement:annotatedUser\",\n        \"annotatedLocation\": \"chromeManagement:annotatedLocation\",\n        \"annotatedAssetId\": \"chromeManagement:annotatedAssetId\",\n        \"status\": \"schema:additionalType\",\n        \"autoUpdateExpiration\": {\n          \"@id\": \"chromeManagement:autoUpdateExpiration\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"TelemetryDevice\": {\n      \"@id\": \"chromeManagement:TelemetryDevice\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"deviceId\": \"schema:identifier\",\n   \
  \     \"serialNumber\": \"chromeManagement:serialNumber\",\n        \"orgUnitId\": \"chromeManagement:orgUnitId\",\n        \"cpuInfo\": \"chromeManagement:cpuInfo\",\n        \"memoryInfo\": \"chromeManagement:memoryInfo\",\n        \"storageInfo\": \"chromeManagement:storageInfo\",\n        \"networkInfo\": \"chromeManagement:networkInfo\",\n        \"batteryInfo\": \"chromeManagement:batteryInfo\",\n        \"osUpdateStatus\": \"chromeManagement:osUpdateStatus\",\n        \"graphicsInfo\": \"chromeManagement:graphicsInfo\"\n      }\n    },\n\n    \"TelemetryEvent\": {\n      \"@id\": \"chromeManagement:TelemetryEvent\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"eventType\": \"chromeManagement:eventType\",\n        \"reportTime\": {\n          \"@id\": \"chromeManagement:reportTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"device\": {\n          \"@id\": \"chromeManagement:device\",\n          \"@type\": \"@id\"\n        },\n       \
  \ \"user\": {\n          \"@id\": \"chromeManagement:user\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"TelemetryUser\": {\n      \"@id\": \"chromeManagement:TelemetryUser\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"userEmail\": {\n          \"@id\": \"schema:email\"\n        },\n        \"userId\": \"schema:identifier\",\n        \"orgUnitId\": \"chromeManagement:orgUnitId\",\n        \"userDevice\": {\n          \"@id\": \"chromeManagement:userDevice\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ChromePolicy\": {\n      \"@id\": \"chromePolicy:ChromePolicy\",\n      \"@context\": {\n        \"schemaName\": \"schema:name\",\n        \"policyDescription\": \"schema:description\",\n        \"fieldDescriptions\": {\n          \"@id\": \"chromePolicy:fieldDescriptions\",\n          \"@container\": \"@set\"\n        },\n        \"definition\": \"chromePolicy:definition\",\n        \"additionalTargetKeyNames\"\
  : {\n          \"@id\": \"chromePolicy:additionalTargetKeyNames\",\n          \"@container\": \"@set\"\n        },\n        \"policyApiLifecycle\": \"chromePolicy:policyApiLifecycle\",\n        \"categoryTitle\": \"chromePolicy:categoryTitle\",\n        \"supportUri\": {\n          \"@id\": \"chromePolicy:supportUri\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"PolicySchema\": {\n      \"@id\": \"chromePolicy:PolicySchema\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"schemaName\": \"chromePolicy:schemaName\",\n        \"policyDescription\": \"schema:description\",\n        \"validTargetResources\": {\n          \"@id\": \"chromePolicy:validTargetResources\",\n          \"@container\": \"@set\"\n        },\n        \"notices\": {\n          \"@id\": \"chromePolicy:notices\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"DevToolsTarget\": {\n      \"@id\": \"cdp:DevToolsTarget\",\n      \"@context\": {\n      \
  \  \"id\": \"@id\",\n        \"title\": \"schema:name\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"type\": \"schema:additionalType\",\n        \"description\": \"schema:description\",\n        \"webSocketDebuggerUrl\": {\n          \"@id\": \"cdp:webSocketDebuggerUrl\",\n          \"@type\": \"@id\"\n        },\n        \"devtoolsFrontendUrl\": {\n          \"@id\": \"cdp:devtoolsFrontendUrl\",\n          \"@type\": \"@id\"\n        },\n        \"faviconUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"CrUXRecord\": {\n      \"@id\": \"chrome:CrUXRecord\",\n      \"@context\": {\n        \"origin\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"formFactor\": \"chrome:formFactor\",\n        \"metrics\": \"chrome:metrics\",\n        \"collectionPeriod\": \"chrome:collectionPeriod\",\n        \"firstContentfulPaint\"\
  : \"chrome:firstContentfulPaint\",\n        \"largestContentfulPaint\": \"chrome:largestContentfulPaint\",\n        \"cumulativeLayoutShift\": \"chrome:cumulativeLayoutShift\",\n        \"interactionToNextPaint\": \"chrome:interactionToNextPaint\",\n        \"timeToFirstByte\": \"chrome:timeToFirstByte\",\n        \"firstInputDelay\": \"chrome:firstInputDelay\"\n      }\n    },\n\n    \"BuiltInAISession\": {\n      \"@id\": \"chrome:BuiltInAISession\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"modelName\": \"schema:name\",\n        \"modelVersion\": \"schema:softwareVersion\",\n        \"topK\": {\n          \"@id\": \"chrome:topK\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"temperature\": {\n          \"@id\": \"chrome:temperature\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"initialPrompts\": {\n          \"@id\": \"chrome:initialPrompts\",\n          \"@container\": \"@set\"\n        },\n        \"systemPrompt\": \"chrome:systemPrompt\"\
  \n      }\n    },\n\n    \"SafeBrowsingThreat\": {\n      \"@id\": \"chrome:SafeBrowsingThreat\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"threatType\": \"chrome:threatType\",\n        \"platformType\": \"chrome:platformType\",\n        \"threatEntryType\": \"chrome:threatEntryType\",\n        \"cacheDuration\": \"chrome:cacheDuration\"\n      }\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n    \"identifier\": \"schema:identifier\",\n    \"dateCreated\": {\"@id\": \"dcterms:created\", \"@type\": \"xsd:dateTime\"},\n    \"dateModified\": {\"@id\": \"dcterms:modified\", \"@type\": \"xsd:dateTime\"},\n    \"version\": \"schema:softwareVersion\",\n    \"platform\": \"schema:operatingSystem\",\n    \"publisher\": \"schema:publisher\",\n    \"category\": \"schema:applicationCategory\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-chrome/refs/heads/main/json-ld/google-chrome-context.jsonld
tags:
- Browser
- Chrome Extensions
- Developer Tools
- Web Platform
- JSON-LD
- Linked Data
- Semantic Web
---
