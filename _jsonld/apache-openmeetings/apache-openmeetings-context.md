---
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
