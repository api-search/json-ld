---
api_specs:
- filename: sinch-sms-openapi.yml
  format: yaml
  label: Sinch SMS API
  slug: sms-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-sms-openapi.yml
- filename: sinch-conversation-openapi.yml
  format: yaml
  label: Sinch Conversation API
  slug: conversation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-conversation-openapi.yml
- filename: sinch-voice-openapi.yml
  format: yaml
  label: Sinch Voice API
  slug: voice-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-voice-openapi.yml
- filename: sinch-verification-openapi.yml
  format: yaml
  label: Sinch Verification API
  slug: verification-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-verification-openapi.yml
- filename: sinch-numbers-openapi.yml
  format: yaml
  label: Sinch Numbers API
  slug: numbers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-numbers-openapi.yml
- filename: sinch-fax-openapi.yml
  format: yaml
  label: Sinch Fax API
  slug: fax-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-fax-openapi.yml
- filename: sinch-elastic-sip-trunking-openapi.yml
  format: yaml
  label: Sinch Elastic SIP Trunking API
  slug: elastic-sip-trunking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-elastic-sip-trunking-openapi.yml
- filename: sinch-brands-openapi.yml
  format: yaml
  label: Sinch Brands API
  slug: brands-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-brands-openapi.yml
- filename: sinch-provisioning-openapi.yml
  format: yaml
  label: Sinch Provisioning API
  slug: provisioning-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-provisioning-openapi.yml
- filename: sinch-registration-openapi.yml
  format: yaml
  label: Sinch Registration API
  slug: registration-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-registration-openapi.yml
class_count: 0
classes: []
context_file: json-ld/sinch-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/json-ld/sinch-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sinch from Sinch.
layout: jsonld
name: Sinch Context
namespaces:
- prefix: sinch
  uri: https://developers.sinch.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Message
  type: ''
- container: ''
  name: Contact
  type: ''
- container: ''
  name: ChannelIdentity
  type: ''
- container: ''
  name: Conversation
  type: ''
- container: ''
  name: Verification
  type: ''
- container: ''
  name: Batch
  type: ''
- container: ''
  name: PhoneNumber
  type: ''
- container: ''
  name: Brand
  type: ''
- container: ''
  name: SipTrunk
  type: ''
- container: ''
  name: FaxDocument
  type: ''
- container: ''
  name: VoiceCall
  type: ''
- container: ''
  name: Registration
  type: ''
property_count: 12
provider_name: Sinch
provider_slug: sinch
slug: sinch-context
source_filename: sinch-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sinch\": \"https://developers.sinch.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Message\": {\n      \"@id\": \"sinch:Message\",\n      \"@context\": {\n        \"messageId\": \"sinch:messageId\",\n        \"body\": \"sinch:body\",\n        \"from\": \"sinch:from\",\n        \"to\": \"sinch:to\",\n        \"channel\": \"sinch:channel\",\n        \"direction\": \"sinch:direction\",\n        \"status\": \"sinch:status\",\n        \"type\": \"sinch:messageType\",\n        \"conversationId\": \"sinch:conversationId\",\n        \"contactId\": \"sinch:contactId\",\n        \"appId\": \"sinch:appId\",\n        \"metadata\": \"sinch:metadata\",\n        \"callbackUrl\": {\n          \"@id\": \"sinch:callbackUrl\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"receivedAt\": {\n          \"@id\": \"sinch:receivedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"sendAt\": {\n          \"@id\": \"sinch:sendAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expireAt\": {\n          \"@id\": \"sinch:expireAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Contact\": {\n      \"@id\": \"sinch:Contact\",\n      \"@context\": {\n        \"contactId\": \"sinch:contactId\",\n        \"displayName\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"externalId\": \"sinch:externalId\",\n        \"language\": \"schema:inLanguage\",\n        \"metadata\": \"sinch:metadata\",\n        \"channelIdentities\": {\n          \"@id\": \"sinch:channelIdentities\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ChannelIdentity\": {\n      \"@id\": \"sinch:ChannelIdentity\",\n      \"@context\":\
  \ {\n        \"channel\": \"sinch:channel\",\n        \"identity\": \"sinch:identity\",\n        \"appId\": \"sinch:appId\"\n      }\n    },\n\n    \"Conversation\": {\n      \"@id\": \"sinch:Conversation\",\n      \"@context\": {\n        \"conversationId\": \"sinch:conversationId\",\n        \"appId\": \"sinch:appId\",\n        \"contactId\": \"sinch:contactId\",\n        \"active\": \"sinch:active\",\n        \"activeChannel\": \"sinch:activeChannel\",\n        \"metadata\": \"sinch:metadata\"\n      }\n    },\n\n    \"Verification\": {\n      \"@id\": \"sinch:Verification\",\n      \"@context\": {\n        \"verificationId\": \"sinch:verificationId\",\n        \"method\": \"sinch:verificationMethod\",\n        \"status\": \"sinch:verificationStatus\",\n        \"reason\": \"sinch:reason\",\n        \"reference\": \"sinch:reference\",\n        \"identity\": \"sinch:identity\",\n        \"price\": \"schema:price\"\n      }\n    },\n\n    \"Batch\": {\n      \"@id\": \"sinch:Batch\",\n\
  \      \"@context\": {\n        \"batchId\": \"sinch:batchId\",\n        \"from\": \"sinch:from\",\n        \"body\": \"sinch:body\",\n        \"deliveryReport\": \"sinch:deliveryReport\",\n        \"canceled\": \"sinch:canceled\",\n        \"recipients\": {\n          \"@id\": \"sinch:recipients\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"sendAt\": {\n          \"@id\": \"sinch:sendAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PhoneNumber\": {\n      \"@id\": \"sinch:PhoneNumber\",\n      \"@context\": {\n        \"phoneNumber\": \"schema:telephone\",\n        \"regionCode\": \"sinch:regionCode\",\n        \"type\": \"sinch:numberType\",\n        \"displayName\": \"schema:name\",\n        \"capability\"\
  : {\n          \"@id\": \"sinch:capability\",\n          \"@container\": \"@set\"\n        },\n        \"nextChargeDate\": {\n          \"@id\": \"sinch:nextChargeDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Brand\": {\n      \"@id\": \"sinch:Brand\",\n      \"@context\": {\n        \"brandId\": \"sinch:brandId\",\n        \"displayName\": \"schema:name\",\n        \"companyName\": \"schema:legalName\",\n        \"entityType\": \"sinch:entityType\",\n        \"country\": \"schema:addressCountry\",\n        \"street\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"postalCode\": \"schema:postalCode\",\n        \"website\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"verticalType\": \"schema:industry\",\n        \"contactEmail\": \"schema:email\",\n        \"contactPhone\": \"schema:telephone\",\n        \"status\": \"sinch:status\"\
  ,\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"SipTrunk\": {\n      \"@id\": \"sinch:SipTrunk\",\n      \"@context\": {\n        \"trunkId\": \"sinch:trunkId\",\n        \"name\": \"schema:name\",\n        \"hostName\": \"sinch:hostName\",\n        \"domain\": \"sinch:domain\",\n        \"callsPerSecond\": \"sinch:callsPerSecond\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"FaxDocument\": {\n      \"@id\": \"sinch:FaxDocument\",\n      \"@context\": {\n        \"faxId\": \"sinch:faxId\",\n        \"from\": \"sinch:from\",\n        \"to\": \"sinch:to\",\n        \"direction\": \"sinch:direction\",\n        \"status\": \"sinch:status\",\n        \"pageCount\": \"sinch:pageCount\"\
  ,\n        \"contentUrl\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedAt\": {\n          \"@id\": \"sinch:completedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"VoiceCall\": {\n      \"@id\": \"sinch:VoiceCall\",\n      \"@context\": {\n        \"callId\": \"sinch:callId\",\n        \"from\": \"sinch:from\",\n        \"to\": \"sinch:to\",\n        \"domain\": \"sinch:domain\",\n        \"status\": \"sinch:status\",\n        \"result\": \"sinch:result\",\n        \"reason\": \"sinch:reason\",\n        \"duration\": \"sinch:duration\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Registration\": {\n      \"@id\": \"sinch:Registration\",\n      \"@context\": {\n        \"registrationId\"\
  : \"sinch:registrationId\",\n        \"marketId\": \"sinch:marketId\",\n        \"senderId\": \"sinch:senderId\",\n        \"senderType\": \"sinch:senderType\",\n        \"status\": \"sinch:status\",\n        \"displayName\": \"schema:name\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"submittedAt\": {\n          \"@id\": \"sinch:submittedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/json-ld/sinch-context.jsonld
tags:
- Communications
- Messaging
- SMS
- Voice
- Verification
- CPaaS
- JSON-LD
- Linked Data
- Semantic Web
---
