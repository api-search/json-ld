---
api_specs:
- filename: apache-openmeetings-rest-api.json
  format: json
  label: Apache OpenMeetings REST API
  slug: apache-openmeetings-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-openmeetings/refs/heads/main/openapi/apache-openmeetings-rest-api.json
class_count: 32
classes:
- RoomDTO
- RoomOptionsDTO
- AppointmentDTOWrapper
- GroupDTO
- Health
- UserSearchResultWrapper
- ExternalUserDTO
- FileItemDTO
- FileItemDTOWrapper
- HealthWrapper
- AppointmentDTO
- RecordingDTO
- UserDTO
- ServiceResultWrapper
- Address
- MeetingMemberDTO
- FileExplorerObjectWrapper
- RoomDTOListWrapper
- UserSearchResult
- FileExplorerObject
- UserDTOListWrapper
- AppointmentDTOListWrapper
- ServiceResult
- RoomFileDTO
- FileItemDTOListWrapper
- UserDTOWrapper
- Info
- InvitationDTO
- RoomDTOWrapper
- GroupDTOListWrapper
- RecordingDTOListWrapper
- InfoWrapper
context_file: json-ld/apache-openmeetings-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-openmeetings/refs/heads/main/json-ld/apache-openmeetings-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Openmeetings from Apache OpenMeetings.
layout: jsonld
name: Apache Openmeetings Context
namespaces:
- prefix: om
  uri: https://openmeetings.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: integer
- container: ''
  name: name
  type: schema:name
- container: ''
  name: tag
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: capacity
  type: integer
- container: ''
  name: appointment
  type: boolean
- container: ''
  name: confno
  type: string
- container: ''
  name: demo
  type: boolean
- container: ''
  name: closed
  type: boolean
- container: ''
  name: demoTime
  type: integer
- container: ''
  name: externalId
  type: string
- container: ''
  name: externalType
  type: string
- container: ''
  name: redirectUrl
  type: string
- container: ''
  name: moderated
  type: boolean
- container: ''
  name: waitModerator
  type: boolean
- container: ''
  name: allowUserQuestions
  type: boolean
- container: ''
  name: allowRecording
  type: boolean
- container: ''
  name: waitRecording
  type: boolean
- container: ''
  name: audioOnly
  type: boolean
- container: set
  name: hiddenElements
  type: string
- container: set
  name: files
  type: string
- container: ''
  name: public
  type: boolean
- container: ''
  name: roomId
  type: integer
- container: ''
  name: externalRoomId
  type: string
- container: ''
  name: recordingId
  type: integer
- container: ''
  name: moderator
  type: boolean
- container: ''
  name: showAudioVideoTest
  type: boolean
- container: ''
  name: allowSameURLMultipleTimes
  type: boolean
- container: ''
  name: appointmentDTO
  type: string
- container: ''
  name: inited
  type: boolean
- container: ''
  name: installed
  type: boolean
- container: ''
  name: dbOk
  type: boolean
- container: ''
  name: userSearchResult
  type: string
- container: ''
  name: login
  type: string
- container: ''
  name: firstname
  type: string
- container: ''
  name: lastname
  type: string
- container: ''
  name: profilePictureUrl
  type: string
- container: ''
  name: email
  type: schema:email
- container: ''
  name: hash
  type: string
- container: ''
  name: parentId
  type: integer
- container: ''
  name: groupId
  type: integer
- container: ''
  name: ownerId
  type: integer
- container: ''
  name: size
  type: integer
- container: ''
  name: width
  type: integer
- container: ''
  name: height
  type: integer
- container: ''
  name: fileItemDTO
  type: string
- container: ''
  name: health
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: start
  type: dateTime
- container: ''
  name: end
  type: dateTime
- container: ''
  name: description
  type: schema:description
- container: ''
  name: owner
  type: string
- container: ''
  name: inserted
  type: dateTime
- container: ''
  name: updated
  type: dateTime
- container: ''
  name: deleted
  type: boolean
- container: ''
  name: reminder
  type: string
- container: ''
  name: room
  type: string
- container: ''
  name: icalId
  type: string
- container: set
  name: meetingMembers
  type: string
- container: ''
  name: languageId
  type: integer
- container: ''
  name: password
  type: string
- container: ''
  name: passwordProtected
  type: boolean
- container: ''
  name: connectedEvent
  type: boolean
- container: ''
  name: reminderEmailSend
  type: boolean
- container: ''
  name: status
  type: string
- container: ''
  name: interview
  type: boolean
- container: set
  name: rights
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: timeZoneId
  type: string
- container: ''
  name: pictureUri
  type: string
- container: ''
  name: serviceResult
  type: string
- container: ''
  name: additionalname
  type: string
- container: ''
  name: fax
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: street
  type: string
- container: ''
  name: town
  type: string
- container: ''
  name: zip
  type: string
- container: ''
  name: phone
  type: string
- container: ''
  name: user
  type: string
- container: ''
  name: fileExplorerObject
  type: string
- container: set
  name: roomDTO
  type: string
- container: ''
  name: objectName
  type: string
- container: ''
  name: records
  type: integer
- container: set
  name: result
  type: string
- container: ''
  name: errorKey
  type: string
- container: set
  name: userHome
  type: string
- container: set
  name: roomHome
  type: string
- container: ''
  name: userHomeSize
  type: integer
- container: ''
  name: roomHomeSize
  type: integer
- container: set
  name: userDTO
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: fileId
  type: integer
- container: ''
  name: wbIdx
  type: integer
- container: ''
  name: version
  type: string
- container: ''
  name: revision
  type: string
- container: ''
  name: buildDate
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: valid
  type: string
- container: ''
  name: validFrom
  type: string
- container: ''
  name: validTo
  type: string
- container: set
  name: groupDTO
  type: string
- container: set
  name: recordingDTO
  type: string
- container: ''
  name: info
  type: string
property_count: 105
provider_name: Apache OpenMeetings
provider_slug: apache-openmeetings
slug: apache-openmeetings-context
source_filename: apache-openmeetings-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"om\": \"https://openmeetings.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"RoomDTO\": \"om:RoomDTO\",\n    \"RoomOptionsDTO\": \"om:RoomOptionsDTO\",\n    \"AppointmentDTOWrapper\": \"om:AppointmentDTOWrapper\",\n    \"GroupDTO\": \"om:GroupDTO\",\n    \"Health\": \"om:Health\",\n    \"UserSearchResultWrapper\": \"om:UserSearchResultWrapper\",\n    \"ExternalUserDTO\": \"om:ExternalUserDTO\",\n    \"FileItemDTO\": \"om:FileItemDTO\",\n    \"FileItemDTOWrapper\": \"om:FileItemDTOWrapper\",\n    \"HealthWrapper\": \"om:HealthWrapper\",\n    \"AppointmentDTO\": \"om:AppointmentDTO\",\n    \"RecordingDTO\": \"om:RecordingDTO\",\n    \"UserDTO\": \"om:UserDTO\",\n    \"ServiceResultWrapper\": \"om:ServiceResultWrapper\",\n    \"Address\": \"om:Address\",\n    \"MeetingMemberDTO\": \"om:MeetingMemberDTO\",\n    \"FileExplorerObjectWrapper\": \"om:FileExplorerObjectWrapper\"\
  ,\n    \"RoomDTOListWrapper\": \"om:RoomDTOListWrapper\",\n    \"UserSearchResult\": \"om:UserSearchResult\",\n    \"FileExplorerObject\": \"om:FileExplorerObject\",\n    \"UserDTOListWrapper\": \"om:UserDTOListWrapper\",\n    \"AppointmentDTOListWrapper\": \"om:AppointmentDTOListWrapper\",\n    \"ServiceResult\": \"om:ServiceResult\",\n    \"RoomFileDTO\": \"om:RoomFileDTO\",\n    \"FileItemDTOListWrapper\": \"om:FileItemDTOListWrapper\",\n    \"UserDTOWrapper\": \"om:UserDTOWrapper\",\n    \"Info\": \"om:Info\",\n    \"InvitationDTO\": \"om:InvitationDTO\",\n    \"RoomDTOWrapper\": \"om:RoomDTOWrapper\",\n    \"GroupDTOListWrapper\": \"om:GroupDTOListWrapper\",\n    \"RecordingDTOListWrapper\": \"om:RecordingDTOListWrapper\",\n    \"InfoWrapper\": \"om:InfoWrapper\",\n    \"id\": {\n      \"@id\": \"om:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"om:name\",\n      \"@type\": \"schema:name\"\n    },\n    \"tag\": {\n      \"@id\": \"om:tag\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"om:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"om:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capacity\": {\n      \"@id\": \"om:capacity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"appointment\": {\n      \"@id\": \"om:appointment\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"confno\": {\n      \"@id\": \"om:confno\",\n      \"@type\": \"xsd:string\"\n    },\n    \"demo\": {\n      \"@id\": \"om:demo\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"closed\": {\n      \"@id\": \"om:closed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"demoTime\": {\n      \"@id\": \"om:demoTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"externalId\": {\n      \"@id\": \"om:externalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalType\": {\n      \"@id\": \"om:externalType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redirectUrl\"\
  : {\n      \"@id\": \"om:redirectUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"moderated\": {\n      \"@id\": \"om:moderated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"waitModerator\": {\n      \"@id\": \"om:waitModerator\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"allowUserQuestions\": {\n      \"@id\": \"om:allowUserQuestions\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"allowRecording\": {\n      \"@id\": \"om:allowRecording\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"waitRecording\": {\n      \"@id\": \"om:waitRecording\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"audioOnly\": {\n      \"@id\": \"om:audioOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"hiddenElements\": {\n      \"@id\": \"om:hiddenElements\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"files\": {\n      \"@id\": \"om:files\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"public\": {\n    \
  \  \"@id\": \"om:public\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"roomId\": {\n      \"@id\": \"om:roomId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"externalRoomId\": {\n      \"@id\": \"om:externalRoomId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordingId\": {\n      \"@id\": \"om:recordingId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"moderator\": {\n      \"@id\": \"om:moderator\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"showAudioVideoTest\": {\n      \"@id\": \"om:showAudioVideoTest\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"allowSameURLMultipleTimes\": {\n      \"@id\": \"om:allowSameURLMultipleTimes\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"appointmentDTO\": {\n      \"@id\": \"om:appointmentDTO\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inited\": {\n      \"@id\": \"om:inited\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"installed\": {\n      \"@id\": \"om:installed\",\n      \"@type\": \"xsd:boolean\"\
  \n    },\n    \"dbOk\": {\n      \"@id\": \"om:dbOk\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"userSearchResult\": {\n      \"@id\": \"om:userSearchResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"login\": {\n      \"@id\": \"om:login\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstname\": {\n      \"@id\": \"om:firstname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastname\": {\n      \"@id\": \"om:lastname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profilePictureUrl\": {\n      \"@id\": \"om:profilePictureUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"om:email\",\n      \"@type\": \"schema:email\"\n    },\n    \"hash\": {\n      \"@id\": \"om:hash\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentId\": {\n      \"@id\": \"om:parentId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"groupId\": {\n      \"@id\": \"om:groupId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ownerId\": {\n      \"\
  @id\": \"om:ownerId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"size\": {\n      \"@id\": \"om:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"width\": {\n      \"@id\": \"om:width\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"height\": {\n      \"@id\": \"om:height\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fileItemDTO\": {\n      \"@id\": \"om:fileItemDTO\",\n      \"@type\": \"xsd:string\"\n    },\n    \"health\": {\n      \"@id\": \"om:health\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"om:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"om:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start\": {\n      \"@id\": \"om:start\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"end\": {\n      \"@id\": \"om:end\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": {\n      \"@id\": \"om:description\",\n      \"@type\": \"schema:description\"\n    },\n\
  \    \"owner\": {\n      \"@id\": \"om:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inserted\": {\n      \"@id\": \"om:inserted\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated\": {\n      \"@id\": \"om:updated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deleted\": {\n      \"@id\": \"om:deleted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reminder\": {\n      \"@id\": \"om:reminder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"room\": {\n      \"@id\": \"om:room\",\n      \"@type\": \"xsd:string\"\n    },\n    \"icalId\": {\n      \"@id\": \"om:icalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meetingMembers\": {\n      \"@id\": \"om:meetingMembers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"languageId\": {\n      \"@id\": \"om:languageId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"password\": {\n      \"@id\": \"om:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"passwordProtected\"\
  : {\n      \"@id\": \"om:passwordProtected\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"connectedEvent\": {\n      \"@id\": \"om:connectedEvent\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reminderEmailSend\": {\n      \"@id\": \"om:reminderEmailSend\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"status\": {\n      \"@id\": \"om:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interview\": {\n      \"@id\": \"om:interview\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"rights\": {\n      \"@id\": \"om:rights\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"om:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeZoneId\": {\n      \"@id\": \"om:timeZoneId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pictureUri\": {\n      \"@id\": \"om:pictureUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceResult\": {\n      \"@id\": \"om:serviceResult\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"additionalname\": {\n      \"@id\": \"om:additionalname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fax\": {\n      \"@id\": \"om:fax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"om:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"street\": {\n      \"@id\": \"om:street\",\n      \"@type\": \"xsd:string\"\n    },\n    \"town\": {\n      \"@id\": \"om:town\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zip\": {\n      \"@id\": \"om:zip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phone\": {\n      \"@id\": \"om:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user\": {\n      \"@id\": \"om:user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileExplorerObject\": {\n      \"@id\": \"om:fileExplorerObject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roomDTO\": {\n      \"@id\": \"om:roomDTO\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objectName\": {\n \
  \     \"@id\": \"om:objectName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"records\": {\n      \"@id\": \"om:records\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"result\": {\n      \"@id\": \"om:result\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorKey\": {\n      \"@id\": \"om:errorKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userHome\": {\n      \"@id\": \"om:userHome\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roomHome\": {\n      \"@id\": \"om:roomHome\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userHomeSize\": {\n      \"@id\": \"om:userHomeSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"roomHomeSize\": {\n      \"@id\": \"om:roomHomeSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"userDTO\": {\n      \"@id\": \"om:userDTO\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n\
  \      \"@id\": \"om:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileId\": {\n      \"@id\": \"om:fileId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"wbIdx\": {\n      \"@id\": \"om:wbIdx\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"version\": {\n      \"@id\": \"om:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revision\": {\n      \"@id\": \"om:revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buildDate\": {\n      \"@id\": \"om:buildDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"om:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valid\": {\n      \"@id\": \"om:valid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validFrom\": {\n      \"@id\": \"om:validFrom\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validTo\": {\n      \"@id\": \"om:validTo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupDTO\": {\n      \"@id\": \"om:groupDTO\",\n      \"@container\": \"@set\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"recordingDTO\": {\n      \"@id\": \"om:recordingDTO\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"info\": {\n      \"@id\": \"om:info\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-openmeetings/refs/heads/main/json-ld/apache-openmeetings-context.jsonld
tags:
- Collaboration
- Video Conferencing
- Web Conferencing
- Whiteboard
- Apache
- Open Source
- Conferencing
- JSON-LD
- Linked Data
- Semantic Web
---
