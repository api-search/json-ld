---
api_specs:
- filename: microsoft-graph-api-openapi.yml
  format: yaml
  label: Microsoft Graph API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-365/refs/heads/main/openapi/microsoft-graph-api-openapi.yml
- filename: microsoft-graph-api-openapi.yml
  format: yaml
  label: Outlook Mail API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-365/refs/heads/main/openapi/microsoft-graph-api-openapi.yml
- filename: microsoft-graph-api-openapi.yml
  format: yaml
  label: Outlook Calendar API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-365/refs/heads/main/openapi/microsoft-graph-api-openapi.yml
- filename: microsoft-graph-api-openapi.yml
  format: yaml
  label: Office 365 Groups API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-365/refs/heads/main/openapi/microsoft-graph-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/microsoft-office-365-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-365/refs/heads/main/json-ld/microsoft-office-365-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Office 365 from Microsoft Office 365.
layout: jsonld
name: Microsoft Office 365 Context
namespaces:
- prefix: msgraph
  uri: https://graph.microsoft.com/v1.0/
- prefix: schema
  uri: https://schema.org/
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: org
  uri: http://www.w3.org/ns/org#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: odata
  uri: http://docs.oasis-open.org/odata/ns/
properties:
- container: ''
  name: User
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: Calendar
  type: ''
- container: ''
  name: MailFolder
  type: ''
- container: ''
  name: Location
  type: ''
- container: ''
  name: EmailAddress
  type: ''
- container: ''
  name: PhysicalAddress
  type: ''
- container: ''
  name: DateTimeTimeZone
  type: ''
property_count: 10
provider_name: Microsoft Office 365
provider_slug: microsoft-office-365
slug: microsoft-office-365-context
source_filename: microsoft-office-365-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"msgraph\": \"https://graph.microsoft.com/v1.0/\",\n    \"schema\": \"https://schema.org/\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"org\": \"http://www.w3.org/ns/org#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"odata\": \"http://docs.oasis-open.org/odata/ns/\",\n\n    \"User\": {\n      \"@id\": \"msgraph:users\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"givenName\": {\n          \"@id\": \"schema:givenName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"surname\": {\n          \"@id\": \"schema:familyName\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"mail\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"userPrincipalName\": {\n          \"@id\": \"msgraph:userPrincipalName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"jobTitle\": {\n          \"@id\": \"schema:jobTitle\",\n          \"@type\": \"xsd:string\"\n        },\n        \"department\": {\n          \"@id\": \"org:unitOf\",\n          \"@type\": \"xsd:string\"\n        },\n        \"officeLocation\": {\n          \"@id\": \"schema:workLocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"companyName\": {\n          \"@id\": \"schema:worksFor\",\n          \"@type\": \"xsd:string\"\n        },\n        \"businessPhones\": {\n          \"@id\": \"schema:telephone\",\n          \"@container\": \"@set\"\n        },\n        \"mobilePhone\": {\n          \"@id\": \"vcard:hasTelephone\",\n          \"@type\": \"xsd:string\"\n     \
  \   },\n        \"streetAddress\": {\n          \"@id\": \"schema:streetAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"postalCode\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"preferredLanguage\": {\n          \"@id\": \"schema:knowsLanguage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountEnabled\": {\n          \"@id\": \"msgraph:accountEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"\
  employeeId\": {\n          \"@id\": \"schema:employeeId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"usageLocation\": {\n          \"@id\": \"schema:countryOfOrigin\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"msgraph:groups\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mail\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mailEnabled\": {\n          \"@id\": \"msgraph:mailEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"mailNickname\": {\n          \"@id\": \"msgraph:mailNickname\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"securityEnabled\": {\n          \"@id\": \"msgraph:securityEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"groupTypes\": {\n          \"@id\": \"msgraph:groupTypes\",\n          \"@container\": \"@set\"\n        },\n        \"visibility\": {\n          \"@id\": \"msgraph:visibility\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"classification\": {\n          \"@id\": \"skos:notation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"members\": {\n          \"@id\": \"org:hasMember\",\n          \"@container\": \"@set\"\n        },\n        \"owners\": {\n          \"@id\": \"msgraph:owners\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"schema:EmailMessage\",\n      \"@context\": {\n        \"id\": {\n          \"@id\"\
  : \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subject\": {\n          \"@id\": \"schema:about\",\n          \"@type\": \"xsd:string\"\n        },\n        \"body\": {\n          \"@id\": \"schema:text\"\n        },\n        \"bodyPreview\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sender\": {\n          \"@id\": \"schema:sender\"\n        },\n        \"from\": {\n          \"@id\": \"schema:author\"\n        },\n        \"toRecipients\": {\n          \"@id\": \"schema:recipient\",\n          \"@container\": \"@set\"\n        },\n        \"ccRecipients\": {\n          \"@id\": \"schema:ccRecipient\",\n          \"@container\": \"@set\"\n        },\n        \"bccRecipients\": {\n          \"@id\": \"schema:bccRecipient\",\n          \"@container\": \"@set\"\n        },\n        \"receivedDateTime\": {\n          \"@id\": \"schema:dateReceived\",\n          \"@type\": \"xsd:dateTime\"\n\
  \        },\n        \"sentDateTime\": {\n          \"@id\": \"schema:dateSent\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedDateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"hasAttachments\": {\n          \"@id\": \"msgraph:hasAttachments\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"importance\": {\n          \"@id\": \"msgraph:importance\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isRead\": {\n          \"@id\": \"msgraph:isRead\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isDraft\": {\n          \"@id\": \"msgraph:isDraft\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"categories\": {\n          \"@id\": \"dcterms:subject\",\n          \"@container\": \"@set\"\n        },\n        \"conversationId\"\
  : {\n          \"@id\": \"msgraph:conversationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"internetMessageId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"webLink\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"schema:Event\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subject\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"body\": {\n          \"@id\": \"schema:description\"\n        },\n        \"start\": {\n          \"@id\": \"schema:startDate\"\n        },\n        \"end\": {\n          \"@id\": \"schema:endDate\"\n        },\n        \"location\": {\n          \"@id\": \"schema:location\"\n        },\n        \"locations\": {\n          \"@id\": \"schema:location\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"attendees\": {\n          \"@id\": \"schema:attendee\",\n          \"@container\": \"@set\"\n        },\n        \"organizer\": {\n          \"@id\": \"schema:organizer\"\n        },\n        \"isAllDay\": {\n          \"@id\": \"msgraph:isAllDay\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isCancelled\": {\n          \"@id\": \"schema:eventStatus\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isOnlineMeeting\": {\n          \"@id\": \"msgraph:isOnlineMeeting\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"onlineMeetingUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"recurrence\": {\n          \"@id\": \"msgraph:recurrence\"\n        },\n        \"showAs\": {\n          \"@id\": \"msgraph:showAs\",\n          \"@type\": \"xsd:string\"\n        },\n        \"importance\": {\n          \"@id\": \"msgraph:importance\",\n        \
  \  \"@type\": \"xsd:string\"\n        },\n        \"sensitivity\": {\n          \"@id\": \"msgraph:sensitivity\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedDateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"categories\": {\n          \"@id\": \"dcterms:subject\",\n          \"@container\": \"@set\"\n        },\n        \"hasAttachments\": {\n          \"@id\": \"msgraph:hasAttachments\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"webLink\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"reminderMinutesBeforeStart\": {\n          \"@id\": \"msgraph:reminderMinutesBeforeStart\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"responseRequested\": {\n          \"@id\": \"msgraph:responseRequested\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        },\n        \"allowNewTimeProposals\": {\n          \"@id\": \"msgraph:allowNewTimeProposals\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Calendar\": {\n      \"@id\": \"msgraph:calendars\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"color\": {\n          \"@id\": \"msgraph:color\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isDefaultCalendar\": {\n          \"@id\": \"msgraph:isDefaultCalendar\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"canEdit\": {\n          \"@id\": \"msgraph:canEdit\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"canShare\": {\n          \"@id\": \"msgraph:canShare\",\n          \"@type\": \"xsd:boolean\"\n        },\n      \
  \  \"owner\": {\n          \"@id\": \"schema:creator\"\n        }\n      }\n    },\n\n    \"MailFolder\": {\n      \"@id\": \"msgraph:mailFolders\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalItemCount\": {\n          \"@id\": \"msgraph:totalItemCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"unreadItemCount\": {\n          \"@id\": \"msgraph:unreadItemCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"childFolderCount\": {\n          \"@id\": \"msgraph:childFolderCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Location\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"address\": {\n          \"@id\": \"schema:address\"\n        },\n        \"coordinates\": {\n          \"@id\": \"schema:geo\"\n        }\n      }\n    },\n\n    \"EmailAddress\": {\n      \"@id\": \"schema:ContactPoint\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"PhysicalAddress\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"street\": {\n          \"@id\": \"schema:streetAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"countryOrRegion\": {\n          \"@id\": \"schema:addressCountry\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"postalCode\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"DateTimeTimeZone\": {\n      \"@id\": \"msgraph:DateTimeTimeZone\",\n      \"@context\": {\n        \"dateTime\": {\n          \"@id\": \"schema:value\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"timeZone\": {\n          \"@id\": \"msgraph:timeZone\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-365/refs/heads/main/json-ld/microsoft-office-365-context.jsonld
tags:
- Cloud
- Collaboration
- Enterprise
- Microsoft
- Productivity
- JSON-LD
- Linked Data
- Semantic Web
---
