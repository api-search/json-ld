---
class_count: 0
classes: []
context_file: json-ld/hubspot-marketing-emal-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-marketing-emal-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Marketing Emal from HubSpot.
layout: jsonld
name: Hubspot Marketing Emal Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: SmtpToken
  type: ''
- container: ''
  name: SmtpTokenWithPassword
  type: ''
- container: ''
  name: SmtpTokenCollectionResponse
  type: ''
- container: ''
  name: SmtpTokenCreateRequest
  type: ''
- container: ''
  name: TransactionalEmailRequest
  type: ''
- container: ''
  name: EmailMessage
  type: ''
- container: ''
  name: TransactionalEmailResponse
  type: ''
- container: ''
  name: Paging
  type: ''
- container: ''
  name: NextPage
  type: ''
- container: ''
  name: Error
  type: ''
- container: ''
  name: ErrorDetail
  type: ''
property_count: 11
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-marketing-emal-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"SmtpToken\": {\n      \"@id\": \"ns:SmtpToken\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"campaignName\": {\n          \"@id\": \"ns:campaignName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"emailCampaignId\": {\n          \"@id\": \"ns:emailCampaignId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createContact\": {\n          \"@id\": \"ns:createContact\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdBy\": {\n          \"@id\": \"ns:createdBy\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"SmtpTokenWithPassword\": {\n      \"@id\": \"ns:SmtpTokenWithPassword\"\
  ,\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"campaignName\": {\n          \"@id\": \"ns:campaignName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"emailCampaignId\": {\n          \"@id\": \"ns:emailCampaignId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createContact\": {\n          \"@id\": \"ns:createContact\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdBy\": {\n          \"@id\": \"ns:createdBy\",\n          \"@type\": \"xsd:string\"\n        },\n        \"password\": {\n          \"@id\": \"ns:password\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"SmtpTokenCollectionResponse\": {\n      \"@id\": \"ns:SmtpTokenCollectionResponse\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n  \
  \      \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"SmtpTokenCreateRequest\": {\n      \"@id\": \"ns:SmtpTokenCreateRequest\",\n      \"@context\": {\n        \"campaignName\": {\n          \"@id\": \"ns:campaignName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createContact\": {\n          \"@id\": \"ns:createContact\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"TransactionalEmailRequest\": {\n      \"@id\": \"ns:TransactionalEmailRequest\",\n      \"@context\": {\n        \"emailId\": {\n          \"@id\": \"ns:emailId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contactProperties\": \"ns:contactProperties\",\n        \"customProperties\": \"ns:customProperties\"\n      }\n    },\n    \"EmailMessage\": {\n      \"@id\": \"ns:EmailMessage\"\
  ,\n      \"@context\": {\n        \"to\": {\n          \"@id\": \"ns:to\",\n          \"@type\": \"xsd:string\"\n        },\n        \"from\": {\n          \"@id\": \"ns:from\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sendId\": {\n          \"@id\": \"ns:sendId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"replyTo\": \"ns:replyTo\",\n        \"cc\": \"ns:cc\",\n        \"bcc\": \"ns:bcc\"\n      }\n    },\n    \"TransactionalEmailResponse\": {\n      \"@id\": \"ns:TransactionalEmailResponse\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"statusId\": {\n          \"@id\": \"ns:statusId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sendResult\": {\n          \"@id\": \"ns:sendResult\",\n          \"@type\": \"xsd:string\"\n        },\n        \"requestedAt\": {\n          \"@id\": \"ns:requestedAt\",\n          \"@type\": \"xsd:string\"\n \
  \       },\n        \"startedAt\": {\n          \"@id\": \"ns:startedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"completedAt\": {\n          \"@id\": \"ns:completedAt\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Paging\": {\n      \"@id\": \"ns:Paging\",\n      \"@context\": {\n        \"next\": {\n          \"@id\": \"ns:next\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"NextPage\": {\n      \"@id\": \"ns:NextPage\",\n      \"@context\": {\n        \"after\": {\n          \"@id\": \"ns:after\",\n          \"@type\": \"xsd:string\"\n        },\n        \"link\": {\n          \"@id\": \"ns:link\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\",\n        \"errors\": \"ns:errors\"\n      }\n    },\n    \"ErrorDetail\": {\n      \"@id\": \"ns:ErrorDetail\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"in\": {\n          \"@id\": \"ns:in\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-marketing-emal-context.jsonld
tags:
- Analytics
- Commerce
- Content
- CRM
- Customer Service
- Email Marketing
- Marketing
- Marketing Automation
- Operations
- Sales
- JSON-LD
- Linked Data
- Semantic Web
---
