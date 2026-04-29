---
class_count: 0
classes: []
context_file: json-ld/cisco-webex-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cisco-webex/refs/heads/main/json-ld/cisco-webex-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cisco Webex from Cisco Webex.
layout: jsonld
name: Cisco Webex Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: sioc
  uri: http://rdfs.org/sioc/ns#
- prefix: ical
  uri: http://www.w3.org/2002/12/cal/icaltzd#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Meeting
  type: ''
- container: ''
  name: Person
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: Room
  type: ''
- container: ''
  name: Team
  type: ''
- container: ''
  name: Membership
  type: ''
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: Device
  type: ''
- container: ''
  name: Recording
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: License
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: Role
  type: ''
property_count: 14
provider_name: Cisco Webex
provider_slug: cisco-webex
slug: cisco-webex-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://developer.webex.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"sioc\": \"http://rdfs.org/sioc/ns#\",\n    \"ical\": \"http://www.w3.org/2002/12/cal/icaltzd#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Meeting\": {\n      \"@id\": \"schema:Event\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"start\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"end\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"hostEmail\": \"schema:organizer\",\n        \"hostDisplayName\": \"schema:organizer\",\n        \"webLink\": {\n          \"@id\": \"schema:url\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"meetingNumber\": \"schema:identifier\",\n        \"password\": \"schema:accessCode\",\n        \"timezone\": \"schema:timeZone\",\n        \"recurrence\": \"ical:rrule\",\n        \"sipAddress\": \"schema:telephone\",\n        \"scheduledType\": \"schema:eventAttendanceMode\"\n      }\n    },\n\n    \"Person\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"nickName\": \"foaf:nick\",\n        \"emails\": \"schema:email\",\n        \"phoneNumbers\": \"schema:telephone\",\n        \"avatar\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"title\": \"schema:jobTitle\",\n        \"department\": \"schema:department\",\n        \"manager\": \"schema:colleague\",\n        \"orgId\": \"schema:memberOf\",\n      \
  \  \"addresses\": \"schema:address\",\n        \"timezone\": \"schema:timeZone\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"status\": \"schema:status\"\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"sioc:Post\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"text\": \"sioc:content\",\n        \"html\": \"sioc:content\",\n        \"markdown\": \"sioc:content\",\n        \"personId\": \"sioc:has_creator\",\n        \"personEmail\": \"schema:author\",\n        \"roomId\": \"sioc:has_container\",\n        \"parentId\": \"sioc:reply_of\",\n        \"files\": {\n          \"@id\": \"sioc:attachment\",\n          \"@type\": \"@id\"\n        },\n        \"mentionedPeople\": \"schema:mentions\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n       \
  \   \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Room\": {\n      \"@id\": \"sioc:Space\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"dcterms:type\",\n        \"teamId\": \"schema:partOf\",\n        \"creatorId\": \"dcterms:creator\",\n        \"ownerId\": \"schema:maintainer\",\n        \"lastActivity\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"isLocked\": \"schema:accessMode\",\n        \"isPublic\": \"schema:isAccessibleForFree\"\n      }\n    },\n\n    \"Team\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"id\": \"@id\",\n\
  \        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"creatorId\": \"dcterms:creator\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Membership\": {\n      \"@id\": \"schema:OrganizationRole\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"roomId\": \"schema:memberOf\",\n        \"personId\": \"schema:member\",\n        \"personEmail\": \"schema:email\",\n        \"personDisplayName\": \"schema:name\",\n        \"isModerator\": \"schema:roleName\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Webhook\": {\n      \"@id\": \"schema:WebAPI\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"targetUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"resource\"\
  : \"schema:about\",\n        \"event\": \"schema:potentialAction\",\n        \"status\": \"schema:status\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Device\": {\n      \"@id\": \"schema:Product\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\",\n        \"product\": \"schema:model\",\n        \"serial\": \"schema:serialNumber\",\n        \"mac\": \"schema:identifier\",\n        \"ip\": \"schema:identifier\",\n        \"software\": \"schema:softwareVersion\",\n        \"connectionStatus\": \"schema:status\",\n        \"workspaceId\": \"schema:location\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Recording\": {\n      \"@id\": \"schema:MediaObject\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"topic\": \"schema:name\",\n        \"downloadUrl\"\
  : {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"playbackUrl\": {\n          \"@id\": \"schema:embedUrl\",\n          \"@type\": \"@id\"\n        },\n        \"format\": \"schema:encodingFormat\",\n        \"durationSeconds\": \"schema:duration\",\n        \"sizeBytes\": \"schema:contentSize\",\n        \"status\": \"schema:status\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Workspace\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\",\n        \"capacity\": \"schema:maximumAttendeeCapacity\"\
  ,\n        \"type\": \"dcterms:type\",\n        \"notes\": \"schema:description\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"License\": {\n      \"@id\": \"schema:Offer\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"totalUnits\": \"schema:inventoryLevel\",\n        \"subscriptionId\": \"schema:identifier\"\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"resource\": \"schema:object\",\n        \"type\": \"schema:actionStatus\",\n        \"actorId\": \"schema:agent\",\n        \"orgId\": \"schema:participant\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n  \
  \  },\n\n    \"Role\": {\n      \"@id\": \"schema:Role\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:roleName\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cisco-webex/refs/heads/main/json-ld/cisco-webex-context.jsonld
tags:
- Collaboration
- Communications
- Meetings
- Messaging
- Teams
- Video Conferencing
- JSON-LD
- Linked Data
- Semantic Web
---
