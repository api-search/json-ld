---
api_specs:
- filename: app-store-connect-api.yml
  format: yaml
  label: App Store Connect API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apple/refs/heads/main/openapi/app-store-connect-api.yml
class_count: 2
classes:
- id
- type
context_file: json-ld/apple-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apple/refs/heads/main/json-ld/apple-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apple from Apple.
layout: jsonld
name: Apple Context
namespaces:
- prefix: apple
  uri: https://developer.apple.com/documentation/appstoreconnectapi/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: jsonapi
  uri: https://jsonapi.org/format/#
properties:
- container: ''
  name: App
  type: ''
- container: ''
  name: Build
  type: ''
- container: ''
  name: BetaTester
  type: ''
- container: ''
  name: BetaGroup
  type: ''
- container: ''
  name: AppStoreVersion
  type: ''
- container: ''
  name: PreReleaseVersion
  type: ''
- container: ''
  name: SoftwareApplication
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: WebAPI
  type: ''
property_count: 9
provider_name: Apple
provider_slug: apple
slug: apple-context
source_filename: apple-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"apple\": \"https://developer.apple.com/documentation/appstoreconnectapi/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"jsonapi\": \"https://jsonapi.org/format/#\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"App\": {\n      \"@id\": \"apple:app\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"bundleId\": {\n          \"@id\": \"apple:app/attributes/bundleid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sku\": {\n          \"@id\": \"apple:app/attributes/sku\",\n          \"@type\": \"xsd:string\"\n        },\n        \"primaryLocale\": {\n          \"@id\": \"apple:app/attributes/primarylocale\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isOrEverWasMadeForKids\": {\n          \"@id\": \"apple:app/attributes/isoreverwasmadefor-kids\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        },\n        \"contentRightsDeclaration\": {\n          \"@id\": \"apple:app/attributes/contentrightsdeclaration\",\n          \"@type\": \"xsd:string\"\n        },\n        \"streamlinedPurchasingEnabled\": {\n          \"@id\": \"apple:app/attributes/streamlinedpurchasingenabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"subscriptionStatusUrl\": {\n          \"@id\": \"apple:app/attributes/subscriptionstatusurl\",\n          \"@type\": \"xsd:anyURI\"\n        },\n        \"subscriptionStatusUrlForSandbox\": {\n          \"@id\": \"apple:app/attributes/subscriptionstatusurlfor-sandbox\",\n          \"@type\": \"xsd:anyURI\"\n        },\n        \"builds\": {\n          \"@id\": \"apple:app/relationships/builds\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"betaGroups\": {\n          \"@id\": \"apple:app/relationships/betagroups\",\n          \"@type\": \"@id\",\n        \
  \  \"@container\": \"@set\"\n        },\n        \"appStoreVersions\": {\n          \"@id\": \"apple:app/relationships/appstoreversions\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"preReleaseVersions\": {\n          \"@id\": \"apple:app/relationships/prereleaseversions\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Build\": {\n      \"@id\": \"apple:build\",\n      \"@context\": {\n        \"version\": {\n          \"@id\": \"schema:softwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"uploadedDate\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expirationDate\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expired\": {\n          \"@id\": \"apple:build/attributes/expired\",\n          \"@type\": \"xsd:boolean\"\n        },\n       \
  \ \"minOsVersion\": {\n          \"@id\": \"apple:build/attributes/minosversion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lsMinimumSystemVersion\": {\n          \"@id\": \"apple:build/attributes/lsminimumsystemversion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"computedMinMacOsVersion\": {\n          \"@id\": \"apple:build/attributes/computedminmacosversion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"processingState\": {\n          \"@id\": \"apple:build/attributes/processingstate\",\n          \"@type\": \"xsd:string\"\n        },\n        \"buildAudienceType\": {\n          \"@id\": \"apple:build/attributes/buildaudiencetype\",\n          \"@type\": \"xsd:string\"\n        },\n        \"usesNonExemptEncryption\": {\n          \"@id\": \"apple:build/attributes/usesnonexemptencryption\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"app\": {\n          \"@id\": \"apple:build/relationships/app\",\n          \"@type\"\
  : \"@id\"\n        },\n        \"preReleaseVersion\": {\n          \"@id\": \"apple:build/relationships/prereleaseversion\",\n          \"@type\": \"@id\"\n        },\n        \"individualTesters\": {\n          \"@id\": \"apple:build/relationships/individualtesters\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"betaGroups\": {\n          \"@id\": \"apple:build/relationships/betagroups\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"BetaTester\": {\n      \"@id\": \"apple:betatester\",\n      \"@context\": {\n        \"firstName\": {\n          \"@id\": \"schema:givenName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastName\": {\n          \"@id\": \"schema:familyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"inviteType\": {\n         \
  \ \"@id\": \"apple:betatester/attributes/invitetype\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"apple:betatester/attributes/state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"apps\": {\n          \"@id\": \"apple:betatester/relationships/apps\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"betaGroups\": {\n          \"@id\": \"apple:betatester/relationships/betagroups\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"builds\": {\n          \"@id\": \"apple:betatester/relationships/builds\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"BetaGroup\": {\n      \"@id\": \"apple:betagroup\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDate\": {\n          \"@id\": \"schema:dateCreated\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"isInternalGroup\": {\n          \"@id\": \"apple:betagroup/attributes/isinternalgroup\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"hasAccessToAllBuilds\": {\n          \"@id\": \"apple:betagroup/attributes/hasaccesstoallbuilds\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"publicLinkEnabled\": {\n          \"@id\": \"apple:betagroup/attributes/publiclinkenabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"publicLink\": {\n          \"@id\": \"apple:betagroup/attributes/publiclink\",\n          \"@type\": \"xsd:anyURI\"\n        },\n        \"publicLinkId\": {\n          \"@id\": \"apple:betagroup/attributes/publiclinkid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"publicLinkLimitEnabled\": {\n          \"@id\": \"apple:betagroup/attributes/publiclinklimitenabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"publicLinkLimit\": {\n   \
  \       \"@id\": \"apple:betagroup/attributes/publiclinklimit\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"feedbackEnabled\": {\n          \"@id\": \"apple:betagroup/attributes/feedbackenabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"iosBuildsAvailableForAppleSiliconMac\": {\n          \"@id\": \"apple:betagroup/attributes/iosbuildsavailableforapplesiliconmac\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"app\": {\n          \"@id\": \"apple:betagroup/relationships/app\",\n          \"@type\": \"@id\"\n        },\n        \"betaTesters\": {\n          \"@id\": \"apple:betagroup/relationships/betatesters\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"builds\": {\n          \"@id\": \"apple:betagroup/relationships/builds\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"AppStoreVersion\": {\n      \"@id\": \"apple:appstoreversion\"\
  ,\n      \"@context\": {\n        \"versionString\": {\n          \"@id\": \"schema:softwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"platform\": {\n          \"@id\": \"apple:appstoreversion/attributes/platform\",\n          \"@type\": \"xsd:string\"\n        },\n        \"appStoreState\": {\n          \"@id\": \"apple:appstoreversion/attributes/appstorestate\",\n          \"@type\": \"xsd:string\"\n        },\n        \"copyright\": {\n          \"@id\": \"schema:copyrightNotice\",\n          \"@type\": \"xsd:string\"\n        },\n        \"releaseType\": {\n          \"@id\": \"apple:appstoreversion/attributes/releasetype\",\n          \"@type\": \"xsd:string\"\n        },\n        \"earliestReleaseDate\": {\n          \"@id\": \"apple:appstoreversion/attributes/earliestreleasedate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"downloadable\": {\n          \"@id\": \"apple:appstoreversion/attributes/downloadable\",\n          \"@type\"\
  : \"xsd:boolean\"\n        },\n        \"createdDate\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"app\": {\n          \"@id\": \"apple:appstoreversion/relationships/app\",\n          \"@type\": \"@id\"\n        },\n        \"build\": {\n          \"@id\": \"apple:appstoreversion/relationships/build\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"PreReleaseVersion\": {\n      \"@id\": \"apple:prereleaseversion\",\n      \"@context\": {\n        \"version\": {\n          \"@id\": \"schema:softwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"platform\": {\n          \"@id\": \"apple:prereleaseversion/attributes/platform\",\n          \"@type\": \"xsd:string\"\n        },\n        \"builds\": {\n          \"@id\": \"apple:prereleaseversion/relationships/builds\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"app\": {\n          \"@id\"\
  : \"apple:prereleaseversion/relationships/app\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"SoftwareApplication\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"applicationCategory\": \"schema:applicationCategory\",\n        \"operatingSystem\": \"schema:operatingSystem\",\n        \"softwareVersion\": \"schema:softwareVersion\",\n        \"downloadUrl\": {\n          \"@id\": \"schema:downloadUrl\",\n          \"@type\": \"@id\"\n        },\n        \"screenshot\": {\n          \"@id\": \"schema:screenshot\",\n          \"@type\": \"@id\"\n        },\n        \"author\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"offers\": {\n          \"@id\": \"schema:offers\",\n          \"@type\": \"@id\"\n        },\n        \"aggregateRating\": {\n          \"@id\": \"schema:aggregateRating\",\n    \
  \      \"@type\": \"@id\"\n        },\n        \"datePublished\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:date\"\n        },\n        \"dateModified\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"logo\": {\n          \"@id\": \"schema:logo\",\n          \"@type\": \"@id\"\n        },\n        \"email\": \"schema:email\"\n      }\n    },\n\n    \"WebAPI\": {\n      \"@id\": \"schema:WebAPI\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"documentation\": {\n          \"@id\": \"schema:documentation\",\n          \"@type\": \"@id\"\n        },\n        \"provider\": {\n          \"@id\"\
  : \"schema:provider\",\n          \"@type\": \"@id\"\n        },\n        \"termsOfService\": {\n          \"@id\": \"schema:termsOfService\",\n          \"@type\": \"@id\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apple/refs/heads/main/json-ld/apple-context.jsonld
tags:
- Developer
- iOS
- macOS
- Mobile
- Technology
- JSON-LD
- Linked Data
- Semantic Web
---
