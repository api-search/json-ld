---
class_count: 0
classes: []
context_file: json-ld/docusign-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/docusign/refs/heads/main/json-ld/docusign-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Docusign from Docusign.
layout: jsonld
name: Docusign Context
namespaces:
- prefix: docusign
  uri: https://developers.docusign.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: prov
  uri: http://www.w3.org/ns/prov#
properties:
- container: ''
  name: Envelope
  type: ''
- container: ''
  name: Document
  type: ''
- container: ''
  name: Recipients
  type: ''
- container: ''
  name: Signer
  type: ''
- container: ''
  name: CarbonCopy
  type: ''
- container: ''
  name: InPersonSigner
  type: ''
- container: ''
  name: RecipientTabs
  type: ''
- container: ''
  name: Tab
  type: ''
- container: ''
  name: EnvelopeTemplate
  type: ''
- container: ''
  name: Notification
  type: ''
- container: ''
  name: CustomFields
  type: ''
- container: ''
  name: EventNotification
  type: ''
- container: ''
  name: UserInfo
  type: ''
- container: ''
  name: ConnectEvent
  type: ''
- container: ''
  name: ConnectEventData
  type: ''
property_count: 15
provider_name: Docusign
provider_slug: docusign
slug: docusign-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://developers.docusign.com/ns/\",\n    \"docusign\": \"https://developers.docusign.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"prov\": \"http://www.w3.org/ns/prov#\",\n\n    \"Envelope\": {\n      \"@id\": \"docusign:Envelope\",\n      \"@context\": {\n        \"envelopeId\": {\n          \"@id\": \"docusign:envelopeId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"envelopeUri\": {\n          \"@id\": \"docusign:envelopeUri\",\n          \"@type\": \"@id\"\n        },\n        \"status\": {\n          \"@id\": \"docusign:envelopeStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"statusChangedDateTime\": {\n          \"@id\": \"docusign:statusChangedDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n\
  \        \"emailSubject\": {\n          \"@id\": \"docusign:emailSubject\",\n          \"@type\": \"xsd:string\"\n        },\n        \"emailBlurb\": {\n          \"@id\": \"docusign:emailBlurb\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"sentDateTime\": {\n          \"@id\": \"docusign:sentDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"deliveredDateTime\": {\n          \"@id\": \"docusign:deliveredDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedDateTime\": {\n          \"@id\": \"docusign:completedDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"declinedDateTime\": {\n          \"@id\": \"docusign:declinedDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"voidedDateTime\": {\n          \"@id\": \"docusign:voidedDateTime\",\n          \"\
  @type\": \"xsd:dateTime\"\n        },\n        \"voidedReason\": {\n          \"@id\": \"docusign:voidedReason\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sender\": {\n          \"@id\": \"docusign:sender\",\n          \"@type\": \"docusign:UserInfo\"\n        },\n        \"recipients\": {\n          \"@id\": \"docusign:recipients\",\n          \"@type\": \"docusign:Recipients\"\n        },\n        \"documents\": {\n          \"@id\": \"docusign:documents\",\n          \"@type\": \"docusign:Document\",\n          \"@container\": \"@set\"\n        },\n        \"customFields\": {\n          \"@id\": \"docusign:customFields\",\n          \"@type\": \"docusign:CustomFields\"\n        },\n        \"notification\": {\n          \"@id\": \"docusign:notification\",\n          \"@type\": \"docusign:Notification\"\n        },\n        \"purgeState\": {\n          \"@id\": \"docusign:purgeState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"brandId\": {\n     \
  \     \"@id\": \"docusign:brandId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"signingLocation\": {\n          \"@id\": \"docusign:signingLocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"expireEnabled\": {\n          \"@id\": \"docusign:expireEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"expireDateTime\": {\n          \"@id\": \"docusign:expireDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Document\": {\n      \"@id\": \"docusign:Document\",\n      \"@context\": {\n        \"documentId\": {\n          \"@id\": \"docusign:documentId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fileExtension\": {\n          \"@id\": \"docusign:fileExtension\",\n          \"@type\": \"xsd:string\"\n        },\n        \"documentBase64\": {\n          \"@id\": \"docusign:documentBase64\"\
  ,\n          \"@type\": \"xsd:base64Binary\"\n        },\n        \"remoteUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"order\": {\n          \"@id\": \"schema:position\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"pages\": {\n          \"@id\": \"schema:numberOfPages\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"display\": {\n          \"@id\": \"docusign:display\",\n          \"@type\": \"xsd:string\"\n        },\n        \"includeInDownload\": {\n          \"@id\": \"docusign:includeInDownload\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"transformPdfFields\": {\n          \"@id\": \"docusign:transformPdfFields\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Recipients\": {\n      \"@id\": \"docusign:Recipients\",\n      \"@context\": {\n        \"signers\": {\n          \"@id\": \"docusign:signers\",\n          \"@type\": \"docusign:Signer\",\n   \
  \       \"@container\": \"@set\"\n        },\n        \"carbonCopies\": {\n          \"@id\": \"docusign:carbonCopies\",\n          \"@type\": \"docusign:CarbonCopy\",\n          \"@container\": \"@set\"\n        },\n        \"certifiedDeliveries\": {\n          \"@id\": \"docusign:certifiedDeliveries\",\n          \"@type\": \"docusign:CertifiedDelivery\",\n          \"@container\": \"@set\"\n        },\n        \"inPersonSigners\": {\n          \"@id\": \"docusign:inPersonSigners\",\n          \"@type\": \"docusign:InPersonSigner\",\n          \"@container\": \"@set\"\n        },\n        \"agents\": {\n          \"@id\": \"docusign:agents\",\n          \"@type\": \"docusign:Agent\",\n          \"@container\": \"@set\"\n        },\n        \"editors\": {\n          \"@id\": \"docusign:editors\",\n          \"@type\": \"docusign:Editor\",\n          \"@container\": \"@set\"\n        },\n        \"intermediaries\": {\n          \"@id\": \"docusign:intermediaries\",\n          \"@type\"\
  : \"docusign:Intermediary\",\n          \"@container\": \"@set\"\n        },\n        \"witnesses\": {\n          \"@id\": \"docusign:witnesses\",\n          \"@type\": \"docusign:Witness\",\n          \"@container\": \"@set\"\n        },\n        \"recipientCount\": {\n          \"@id\": \"docusign:recipientCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"currentRoutingOrder\": {\n          \"@id\": \"docusign:currentRoutingOrder\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Signer\": {\n      \"@id\": \"docusign:Signer\",\n      \"@context\": {\n        \"recipientId\": {\n          \"@id\": \"docusign:recipientId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"recipientIdGuid\": {\n          \"@id\": \"docusign:recipientIdGuid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n         \
  \ \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"routingOrder\": {\n          \"@id\": \"docusign:routingOrder\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"roleName\": {\n          \"@id\": \"docusign:roleName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"clientUserId\": {\n          \"@id\": \"docusign:clientUserId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"docusign:recipientStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"signedDateTime\": {\n          \"@id\": \"docusign:signedDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"deliveredDateTime\": {\n          \"@id\": \"docusign:deliveredDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"declinedDateTime\": {\n          \"@id\": \"docusign:declinedDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"declinedReason\":\
  \ {\n          \"@id\": \"docusign:declinedReason\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tabs\": {\n          \"@id\": \"docusign:tabs\",\n          \"@type\": \"docusign:RecipientTabs\"\n        },\n        \"accessCode\": {\n          \"@id\": \"docusign:accessCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"note\": {\n          \"@id\": \"docusign:note\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"CarbonCopy\": {\n      \"@id\": \"docusign:CarbonCopy\",\n      \"@context\": {\n        \"recipientId\": {\n          \"@id\": \"docusign:recipientId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"routingOrder\": {\n          \"@id\": \"docusign:routingOrder\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"status\": {\n          \"@id\": \"docusign:recipientStatus\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"InPersonSigner\": {\n      \"@id\": \"docusign:InPersonSigner\",\n      \"@context\": {\n        \"recipientId\": {\n          \"@id\": \"docusign:recipientId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"hostName\": {\n          \"@id\": \"docusign:hostName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"hostEmail\": {\n          \"@id\": \"docusign:hostEmail\",\n          \"@type\": \"xsd:string\"\n        },\n        \"signerName\": {\n          \"@id\": \"docusign:signerName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"signerEmail\": {\n          \"@id\": \"docusign:signerEmail\",\n          \"@type\": \"xsd:string\"\n        },\n        \"routingOrder\": {\n          \"@id\": \"docusign:routingOrder\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"status\": {\n\
  \          \"@id\": \"docusign:recipientStatus\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"RecipientTabs\": {\n      \"@id\": \"docusign:RecipientTabs\",\n      \"@context\": {\n        \"signHereTabs\": {\n          \"@id\": \"docusign:signHereTabs\",\n          \"@type\": \"docusign:SignHereTab\",\n          \"@container\": \"@set\"\n        },\n        \"initialHereTabs\": {\n          \"@id\": \"docusign:initialHereTabs\",\n          \"@type\": \"docusign:Tab\",\n          \"@container\": \"@set\"\n        },\n        \"dateSignedTabs\": {\n          \"@id\": \"docusign:dateSignedTabs\",\n          \"@type\": \"docusign:Tab\",\n          \"@container\": \"@set\"\n        },\n        \"textTabs\": {\n          \"@id\": \"docusign:textTabs\",\n          \"@type\": \"docusign:TextTab\",\n          \"@container\": \"@set\"\n        },\n        \"fullNameTabs\": {\n          \"@id\": \"docusign:fullNameTabs\",\n          \"@type\": \"docusign:Tab\",\n  \
  \        \"@container\": \"@set\"\n        },\n        \"checkboxTabs\": {\n          \"@id\": \"docusign:checkboxTabs\",\n          \"@type\": \"docusign:CheckboxTab\",\n          \"@container\": \"@set\"\n        },\n        \"radioGroupTabs\": {\n          \"@id\": \"docusign:radioGroupTabs\",\n          \"@type\": \"docusign:RadioGroupTab\",\n          \"@container\": \"@set\"\n        },\n        \"listTabs\": {\n          \"@id\": \"docusign:listTabs\",\n          \"@type\": \"docusign:ListTab\",\n          \"@container\": \"@set\"\n        },\n        \"formulaTabs\": {\n          \"@id\": \"docusign:formulaTabs\",\n          \"@type\": \"docusign:FormulaTab\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Tab\": {\n      \"@id\": \"docusign:Tab\",\n      \"@context\": {\n        \"tabId\": {\n          \"@id\": \"docusign:tabId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tabLabel\": {\n          \"@id\": \"docusign:tabLabel\",\n   \
  \       \"@type\": \"xsd:string\"\n        },\n        \"documentId\": {\n          \"@id\": \"docusign:documentId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"pageNumber\": {\n          \"@id\": \"docusign:pageNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"recipientId\": {\n          \"@id\": \"docusign:recipientId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"xPosition\": {\n          \"@id\": \"docusign:xPosition\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"yPosition\": {\n          \"@id\": \"docusign:yPosition\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"anchorString\": {\n          \"@id\": \"docusign:anchorString\",\n          \"@type\": \"xsd:string\"\n        },\n        \"value\": {\n          \"@id\": \"schema:value\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"EnvelopeTemplate\": {\n      \"@id\": \"docusign:EnvelopeTemplate\",\n      \"@context\"\
  : {\n        \"templateId\": {\n          \"@id\": \"docusign:templateId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastUsed\": {\n          \"@id\": \"docusign:lastUsed\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"shared\": {\n          \"@id\": \"docusign:shared\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"owner\": {\n          \"@id\": \"docusign:owner\",\n          \"@type\": \"docusign:UserInfo\"\n        },\n        \"emailSubject\": {\n          \"@id\": \"docusign:emailSubject\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"documents\": {\n          \"@id\": \"docusign:documents\",\n          \"@type\": \"docusign:Document\",\n          \"@container\": \"@set\"\n        },\n        \"recipients\": {\n          \"@id\": \"docusign:recipients\",\n          \"@type\": \"docusign:Recipients\"\n        }\n      }\n    },\n\n    \"Notification\": {\n      \"@id\": \"docusign:Notification\",\n      \"@context\": {\n        \"useAccountDefaults\": {\n          \"@id\": \"docusign:useAccountDefaults\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"reminders\": {\n          \"@id\": \"docusign:reminders\",\n          \"@type\": \"docusign:ReminderSettings\"\n        },\n        \"expirations\": {\n          \"@id\": \"docusign:expirations\",\n          \"@type\": \"docusign:ExpirationSettings\"\n        }\n      }\n    },\n\n    \"CustomFields\": {\n      \"@id\": \"docusign:CustomFields\",\n      \"@context\": {\n        \"textCustomFields\"\
  : {\n          \"@id\": \"docusign:textCustomFields\",\n          \"@container\": \"@set\"\n        },\n        \"listCustomFields\": {\n          \"@id\": \"docusign:listCustomFields\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"EventNotification\": {\n      \"@id\": \"docusign:EventNotification\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"docusign:webhookUrl\",\n          \"@type\": \"@id\"\n        },\n        \"loggingEnabled\": {\n          \"@id\": \"docusign:loggingEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"envelopeEvents\": {\n          \"@id\": \"docusign:envelopeEvents\",\n          \"@container\": \"@set\"\n        },\n        \"recipientEvents\": {\n          \"@id\": \"docusign:recipientEvents\",\n          \"@container\": \"@set\"\n        },\n        \"includeDocuments\": {\n          \"@id\": \"docusign:includeDocuments\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"includeHMAC\"\
  : {\n          \"@id\": \"docusign:includeHMAC\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"UserInfo\": {\n      \"@id\": \"docusign:UserInfo\",\n      \"@context\": {\n        \"userName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"userId\": {\n          \"@id\": \"docusign:userId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountId\": {\n          \"@id\": \"docusign:accountId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ConnectEvent\": {\n      \"@id\": \"docusign:ConnectEvent\",\n      \"@context\": {\n        \"event\": {\n          \"@id\": \"docusign:eventType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"apiVersion\": {\n          \"@id\": \"docusign:apiVersion\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"configurationId\": {\n          \"@id\": \"docusign:configurationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"uri\": {\n          \"@id\": \"docusign:resourceUri\",\n          \"@type\": \"@id\"\n        },\n        \"retryCount\": {\n          \"@id\": \"docusign:retryCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"generatedDateTime\": {\n          \"@id\": \"prov:generatedAtTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"data\": {\n          \"@id\": \"docusign:eventData\",\n          \"@type\": \"docusign:ConnectEventData\"\n        }\n      }\n    },\n\n    \"ConnectEventData\": {\n      \"@id\": \"docusign:ConnectEventData\",\n      \"@context\": {\n        \"accountId\": {\n          \"@id\": \"docusign:accountId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"userId\": {\n          \"@id\": \"docusign:userId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"envelopeId\": {\n \
  \         \"@id\": \"docusign:envelopeId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"envelopeSummary\": {\n          \"@id\": \"docusign:envelopeSummary\",\n          \"@type\": \"docusign:Envelope\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/docusign/refs/heads/main/json-ld/docusign-context.jsonld
tags:
- Agreements
- Contracts
- Digital Transaction Management
- Documents
- Electronic Signatures
- eSignature
- JSON-LD
- Linked Data
- Semantic Web
---
