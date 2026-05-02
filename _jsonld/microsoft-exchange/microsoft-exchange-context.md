---
api_specs:
- filename: microsoft-exchange-graph-mail-openapi.yml
  format: yaml
  label: Microsoft Graph Mail API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/openapi/microsoft-exchange-graph-mail-openapi.yml
- filename: microsoft-exchange-graph-calendar-openapi.yml
  format: yaml
  label: Microsoft Graph Calendar API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/openapi/microsoft-exchange-graph-calendar-openapi.yml
- filename: microsoft-exchange-graph-contacts-openapi.yml
  format: yaml
  label: Microsoft Graph Contacts API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/openapi/microsoft-exchange-graph-contacts-openapi.yml
- filename: microsoft-exchange-graph-people-openapi.yml
  format: yaml
  label: Microsoft Graph People API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/openapi/microsoft-exchange-graph-people-openapi.yml
- filename: microsoft-exchange-admin-api-openapi.yml
  format: yaml
  label: Exchange Online Admin API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/openapi/microsoft-exchange-admin-api-openapi.yml
- filename: microsoft-exchange-graph-import-export-openapi.yml
  format: yaml
  label: Microsoft Graph Mailbox Import Export API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/openapi/microsoft-exchange-graph-import-export-openapi.yml
class_count: 0
classes: []
context_file: json-ld/microsoft-exchange-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/json-ld/microsoft-exchange-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Exchange from Microsoft Exchange.
layout: jsonld
name: Microsoft Exchange Context
namespaces:
- prefix: graph
  uri: https://graph.microsoft.com/v1.0/
- prefix: exchange
  uri: https://learn.microsoft.com/en-us/graph/api/resources/
properties:
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
  name: Contact
  type: ''
- container: ''
  name: Person
  type: ''
- container: ''
  name: MailFolder
  type: ''
- container: ''
  name: ContactFolder
  type: ''
- container: ''
  name: Attachment
  type: ''
- container: ''
  name: EmailAddress
  type: ''
- container: ''
  name: PhysicalAddress
  type: ''
- container: ''
  name: Location
  type: ''
- container: ''
  name: Recipient
  type: ''
- container: ''
  name: OnlineMeetingInfo
  type: ''
property_count: 13
provider_name: Microsoft Exchange
provider_slug: microsoft-exchange
slug: microsoft-exchange-context
source_filename: microsoft-exchange-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"graph\": \"https://graph.microsoft.com/v1.0/\",\n    \"exchange\": \"https://learn.microsoft.com/en-us/graph/api/resources/\",\n    \"Message\": {\n      \"@id\": \"schema:EmailMessage\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"subject\": \"schema:name\",\n        \"body\": \"schema:text\",\n        \"from\": \"schema:sender\",\n        \"toRecipients\": \"schema:recipient\",\n        \"ccRecipients\": \"schema:ccRecipient\",\n        \"bccRecipients\": \"schema:bccRecipient\",\n        \"sentDateTime\": \"schema:dateSent\",\n        \"receivedDateTime\": \"schema:dateReceived\",\n        \"createdDateTime\": \"schema:dateCreated\",\n        \"lastModifiedDateTime\": \"schema:dateModified\",\n        \"hasAttachments\": \"schema:associatedMedia\",\n        \"importance\": \"schema:interactionStatistic\",\n        \"internetMessageId\": \"schema:identifier\",\n        \"conversationId\"\
  : \"schema:isPartOf\",\n        \"webLink\": \"schema:url\",\n        \"isRead\": \"schema:status\",\n        \"isDraft\": \"schema:creativeWorkStatus\",\n        \"categories\": \"schema:keywords\"\n      }\n    },\n    \"Event\": {\n      \"@id\": \"schema:Event\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"subject\": \"schema:name\",\n        \"body\": \"schema:description\",\n        \"start\": \"schema:startDate\",\n        \"end\": \"schema:endDate\",\n        \"location\": \"schema:location\",\n        \"locations\": \"schema:location\",\n        \"attendees\": \"schema:attendee\",\n        \"organizer\": \"schema:organizer\",\n        \"isAllDay\": \"schema:eventSchedule\",\n        \"recurrence\": \"schema:repeatFrequency\",\n        \"createdDateTime\": \"schema:dateCreated\",\n        \"lastModifiedDateTime\": \"schema:dateModified\",\n        \"webLink\": \"schema:url\",\n        \"onlineMeetingUrl\": \"schema:url\",\n        \"sensitivity\": \"schema:accessMode\"\
  ,\n        \"categories\": \"schema:keywords\",\n        \"importance\": \"schema:interactionStatistic\",\n        \"showAs\": \"schema:eventStatus\"\n      }\n    },\n    \"Calendar\": {\n      \"@id\": \"schema:Schedule\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"owner\": \"schema:creator\",\n        \"color\": \"schema:color\"\n      }\n    },\n    \"Contact\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\",\n        \"givenName\": \"schema:givenName\",\n        \"surname\": \"schema:familyName\",\n        \"middleName\": \"schema:additionalName\",\n        \"emailAddresses\": \"schema:email\",\n        \"businessPhones\": \"schema:telephone\",\n        \"homePhones\": \"schema:telephone\",\n        \"mobilePhone\": \"schema:telephone\",\n        \"jobTitle\": \"schema:jobTitle\",\n        \"companyName\": \"schema:worksFor\",\n        \"department\"\
  : \"schema:department\",\n        \"officeLocation\": \"schema:workLocation\",\n        \"businessAddress\": \"schema:address\",\n        \"homeAddress\": \"schema:homeLocation\",\n        \"birthday\": \"schema:birthDate\",\n        \"children\": \"schema:children\",\n        \"spouseName\": \"schema:spouse\",\n        \"profession\": \"schema:hasOccupation\",\n        \"businessHomePage\": \"schema:url\",\n        \"categories\": \"schema:keywords\",\n        \"createdDateTime\": \"schema:dateCreated\",\n        \"lastModifiedDateTime\": \"schema:dateModified\"\n      }\n    },\n    \"Person\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\",\n        \"givenName\": \"schema:givenName\",\n        \"surname\": \"schema:familyName\",\n        \"jobTitle\": \"schema:jobTitle\",\n        \"companyName\": \"schema:worksFor\",\n        \"department\": \"schema:department\",\n        \"officeLocation\": \"schema:workLocation\"\
  ,\n        \"profession\": \"schema:hasOccupation\",\n        \"scoredEmailAddresses\": \"schema:email\",\n        \"phones\": \"schema:telephone\",\n        \"postalAddresses\": \"schema:address\",\n        \"websites\": \"schema:url\",\n        \"isFavorite\": \"schema:interactionStatistic\",\n        \"userPrincipalName\": \"schema:identifier\"\n      }\n    },\n    \"MailFolder\": {\n      \"@id\": \"schema:DataCatalog\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\",\n        \"totalItemCount\": \"schema:size\",\n        \"unreadItemCount\": \"schema:interactionStatistic\",\n        \"childFolderCount\": \"schema:numberOfItems\"\n      }\n    },\n    \"ContactFolder\": {\n      \"@id\": \"schema:DataCatalog\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\"\n      }\n    },\n    \"Attachment\": {\n      \"@id\": \"schema:MediaObject\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"\
  name\": \"schema:name\",\n        \"contentType\": \"schema:encodingFormat\",\n        \"size\": \"schema:contentSize\",\n        \"contentBytes\": \"schema:contentUrl\",\n        \"lastModifiedDateTime\": \"schema:dateModified\"\n      }\n    },\n    \"EmailAddress\": {\n      \"@id\": \"schema:ContactPoint\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"address\": \"schema:email\"\n      }\n    },\n    \"PhysicalAddress\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"street\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"countryOrRegion\": \"schema:addressCountry\",\n        \"postalCode\": \"schema:postalCode\"\n      }\n    },\n    \"Location\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"address\": \"schema:address\",\n        \"coordinates\": \"schema:geo\",\n        \"locationUri\"\
  : \"schema:url\"\n      }\n    },\n    \"Recipient\": {\n      \"@id\": \"schema:ContactPoint\",\n      \"@context\": {\n        \"emailAddress\": \"schema:email\"\n      }\n    },\n    \"OnlineMeetingInfo\": {\n      \"@id\": \"schema:VirtualLocation\",\n      \"@context\": {\n        \"joinUrl\": \"schema:url\",\n        \"conferenceId\": \"schema:identifier\",\n        \"tollNumber\": \"schema:telephone\",\n        \"tollFreeNumbers\": \"schema:telephone\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/json-ld/microsoft-exchange-context.jsonld
tags:
- Calendar
- Collaboration
- Contacts
- Email
- Enterprise
- JSON-LD
- Linked Data
- Semantic Web
---
