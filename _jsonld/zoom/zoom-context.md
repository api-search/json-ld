---
api_specs:
- filename: zoom-chat--openapi-original.yml
  format: yaml
  label: Zoom Chat API
  slug: zoom-chat-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zoom/refs/heads/main/openapi/zoom-chat--openapi-original.yml
- filename: zoom-group--openapi-original.yml
  format: yaml
  label: Zoom Group API
  slug: zoom-group-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zoom/refs/heads/main/openapi/zoom-group--openapi-original.yml
- filename: zoom-device--openapi-original.yml
  format: yaml
  label: Zoom Device API
  slug: zoom-device-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zoom/refs/heads/main/openapi/zoom-device--openapi-original.yml
- filename: zoom-im--openapi-original.yml
  format: yaml
  label: Zoom Instant Message API
  slug: zoom-instant-message-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zoom/refs/heads/main/openapi/zoom-im--openapi-original.yml
- filename: zoom-account--openapi-original.yml
  format: yaml
  label: Zoom Account API
  slug: zoom-account-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zoom/refs/heads/main/openapi/zoom-account--openapi-original.yml
- filename: zoom-recording--openapi-original.yml
  format: yaml
  label: Zoom Recording API
  slug: zoom-recording-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zoom/refs/heads/main/openapi/zoom-recording--openapi-original.yml
- filename: zoom-meeting--openapi-original.yml
  format: yaml
  label: Zoom Meeting API
  slug: zoom-meeting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zoom/refs/heads/main/openapi/zoom-meeting--openapi-original.yml
- filename: zoom-metrics--openapi-original.yml
  format: yaml
  label: Zoom Metrics API
  slug: zoom-metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zoom/refs/heads/main/openapi/zoom-metrics--openapi-original.yml
- filename: zoom-report--openapi-original.yml
  format: yaml
  label: Zoom Report API
  slug: zoom-report-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zoom/refs/heads/main/openapi/zoom-report--openapi-original.yml
- filename: zoom-user--openapi-original.yml
  format: yaml
  label: Zoom User API
  slug: zoom-user-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zoom/refs/heads/main/openapi/zoom-user--openapi-original.yml
- filename: zoom-webinar--openapi-original.yml
  format: yaml
  label: Zoom Webinar API
  slug: zoom-webinar-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zoom/refs/heads/main/openapi/zoom-webinar--openapi-original.yml
class_count: 0
classes: []
context_file: json-ld/zoom-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zoom/refs/heads/main/json-ld/zoom-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zoom from Zoom.
layout: jsonld
name: Zoom Context
namespaces:
- prefix: zoom
  uri: https://developers.zoom.us/docs/api/rest/reference/zoom-api/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: ical
  uri: http://www.w3.org/2002/12/cal/ical#
properties:
- container: ''
  name: Meeting
  type: ''
- container: ''
  name: MeetingSettings
  type: ''
- container: ''
  name: Recurrence
  type: ''
- container: ''
  name: Occurrence
  type: ''
- container: ''
  name: Participant
  type: ''
- container: ''
  name: Registrant
  type: ''
- container: ''
  name: Poll
  type: ''
- container: ''
  name: RecordingFile
  type: ''
- container: ''
  name: LiveStream
  type: ''
- container: ''
  name: WebhookEvent
  type: ''
- container: ''
  name: User
  type: ''
property_count: 11
provider_name: Zoom
provider_slug: zoom
slug: zoom-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://developers.zoom.us/docs/api/rest/reference/zoom-api/\",\n    \"zoom\": \"https://developers.zoom.us/docs/api/rest/reference/zoom-api/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"ical\": \"http://www.w3.org/2002/12/cal/ical#\",\n\n    \"Meeting\": {\n      \"@id\": \"zoom:Meeting\",\n      \"@context\": {\n        \"uuid\": {\n          \"@id\": \"zoom:Meeting/uuid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"topic\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"agenda\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n  \
  \      \"type\": {\n          \"@id\": \"zoom:Meeting/type\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"status\": {\n          \"@id\": \"schema:eventStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"start_time\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"timezone\": {\n          \"@id\": \"zoom:Meeting/timezone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"start_url\": {\n          \"@id\": \"zoom:Meeting/startUrl\",\n          \"@type\": \"@id\"\n        },\n        \"join_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"password\": {\n          \"@id\": \"zoom:Meeting/password\",\n \
  \         \"@type\": \"xsd:string\"\n        },\n        \"h323_password\": {\n          \"@id\": \"zoom:Meeting/h323Password\",\n          \"@type\": \"xsd:string\"\n        },\n        \"encrypted_password\": {\n          \"@id\": \"zoom:Meeting/encryptedPassword\",\n          \"@type\": \"xsd:string\"\n        },\n        \"host_id\": {\n          \"@id\": \"zoom:Meeting/hostId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"host_email\": {\n          \"@id\": \"zoom:Meeting/hostEmail\",\n          \"@type\": \"xsd:string\"\n        },\n        \"settings\": {\n          \"@id\": \"zoom:Meeting/settings\",\n          \"@type\": \"@id\"\n        },\n        \"recurrence\": {\n          \"@id\": \"zoom:Meeting/recurrence\",\n          \"@type\": \"@id\"\n        },\n        \"occurrences\": {\n          \"@id\": \"zoom:Meeting/occurrences\",\n          \"@container\": \"@list\"\n        },\n        \"tracking_fields\": {\n          \"@id\": \"zoom:Meeting/trackingFields\"\
  ,\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"MeetingSettings\": {\n      \"@id\": \"zoom:MeetingSettings\",\n      \"@context\": {\n        \"host_video\": {\n          \"@id\": \"zoom:MeetingSettings/hostVideo\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"participant_video\": {\n          \"@id\": \"zoom:MeetingSettings/participantVideo\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"join_before_host\": {\n          \"@id\": \"zoom:MeetingSettings/joinBeforeHost\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"mute_upon_entry\": {\n          \"@id\": \"zoom:MeetingSettings/muteUponEntry\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"watermark\": {\n          \"@id\": \"zoom:MeetingSettings/watermark\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"use_pmi\": {\n          \"@id\": \"zoom:MeetingSettings/usePmi\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"approval_type\"\
  : {\n          \"@id\": \"zoom:MeetingSettings/approvalType\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"registration_type\": {\n          \"@id\": \"zoom:MeetingSettings/registrationType\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"audio\": {\n          \"@id\": \"zoom:MeetingSettings/audio\",\n          \"@type\": \"xsd:string\"\n        },\n        \"auto_recording\": {\n          \"@id\": \"zoom:MeetingSettings/autoRecording\",\n          \"@type\": \"xsd:string\"\n        },\n        \"waiting_room\": {\n          \"@id\": \"zoom:MeetingSettings/waitingRoom\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"encryption_type\": {\n          \"@id\": \"zoom:MeetingSettings/encryptionType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"alternative_hosts\": {\n          \"@id\": \"zoom:MeetingSettings/alternativeHosts\",\n          \"@type\": \"xsd:string\"\n        },\n        \"focus_mode\": {\n          \"@id\": \"zoom:MeetingSettings/focusMode\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        },\n        \"breakout_room\": {\n          \"@id\": \"zoom:MeetingSettings/breakoutRoom\",\n          \"@type\": \"@id\"\n        },\n        \"language_interpretation\": {\n          \"@id\": \"zoom:MeetingSettings/languageInterpretation\",\n          \"@type\": \"@id\"\n        },\n        \"meeting_authentication\": {\n          \"@id\": \"zoom:MeetingSettings/meetingAuthentication\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"private_meeting\": {\n          \"@id\": \"zoom:MeetingSettings/privateMeeting\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"continuous_meeting_chat\": {\n          \"@id\": \"zoom:MeetingSettings/continuousMeetingChat\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Recurrence\": {\n      \"@id\": \"zoom:Recurrence\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"zoom:Recurrence/type\",\n          \"@type\": \"xsd:integer\"\n        },\n\
  \        \"repeat_interval\": {\n          \"@id\": \"zoom:Recurrence/repeatInterval\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"weekly_days\": {\n          \"@id\": \"zoom:Recurrence/weeklyDays\",\n          \"@type\": \"xsd:string\"\n        },\n        \"monthly_day\": {\n          \"@id\": \"zoom:Recurrence/monthlyDay\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"monthly_week\": {\n          \"@id\": \"zoom:Recurrence/monthlyWeek\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"monthly_week_day\": {\n          \"@id\": \"zoom:Recurrence/monthlyWeekDay\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"end_times\": {\n          \"@id\": \"zoom:Recurrence/endTimes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"end_date_time\": {\n          \"@id\": \"zoom:Recurrence/endDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Occurrence\": {\n      \"@id\": \"zoom:Occurrence\"\
  ,\n      \"@context\": {\n        \"occurrence_id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"start_time\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"status\": {\n          \"@id\": \"schema:eventStatus\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Participant\": {\n      \"@id\": \"zoom:Participant\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"user_id\": {\n          \"@id\": \"zoom:Participant/userId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"user_email\": {\n          \"@id\": \"schema:email\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"join_time\": {\n          \"@id\": \"zoom:Participant/joinTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"leave_time\": {\n          \"@id\": \"zoom:Participant/leaveTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"registrant_id\": {\n          \"@id\": \"zoom:Participant/registrantId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"zoom:Participant/status\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Registrant\": {\n      \"@id\": \"zoom:Registrant\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"first_name\": {\n          \"@id\": \"schema:givenName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"last_name\": {\n          \"@id\": \"schema:familyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address\": {\n          \"@id\": \"schema:streetAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"zip\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"phone\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"org\": {\n          \"@id\": \"schema:memberOf\",\n  \
  \        \"@type\": \"xsd:string\"\n        },\n        \"job_title\": {\n          \"@id\": \"schema:jobTitle\",\n          \"@type\": \"xsd:string\"\n        },\n        \"industry\": {\n          \"@id\": \"zoom:Registrant/industry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"comments\": {\n          \"@id\": \"schema:comment\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"zoom:Registrant/status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"create_time\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"join_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"language\": {\n          \"@id\": \"schema:inLanguage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"no_of_employees\": {\n          \"@id\": \"schema:numberOfEmployees\",\n          \"@type\": \"xsd:string\"\n        },\n   \
  \     \"purchasing_time_frame\": {\n          \"@id\": \"zoom:Registrant/purchasingTimeFrame\",\n          \"@type\": \"xsd:string\"\n        },\n        \"role_in_purchase_process\": {\n          \"@id\": \"zoom:Registrant/roleInPurchaseProcess\",\n          \"@type\": \"xsd:string\"\n        },\n        \"custom_questions\": {\n          \"@id\": \"zoom:Registrant/customQuestions\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Poll\": {\n      \"@id\": \"zoom:Poll\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"title\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"anonymous\": {\n          \"@id\": \"zoom:Poll/anonymous\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"status\": {\n          \"@id\": \"zoom:Poll/status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"poll_type\"\
  : {\n          \"@id\": \"zoom:Poll/pollType\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"questions\": {\n          \"@id\": \"zoom:Poll/questions\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"RecordingFile\": {\n      \"@id\": \"zoom:RecordingFile\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"meeting_id\": {\n          \"@id\": \"zoom:RecordingFile/meetingId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"recording_start\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"recording_end\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"file_type\": {\n          \"@id\": \"schema:encodingFormat\",\n          \"@type\": \"xsd:string\"\n        },\n        \"file_extension\": {\n          \"@id\": \"zoom:RecordingFile/fileExtension\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"file_size\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"download_url\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"play_url\": {\n          \"@id\": \"schema:embedUrl\",\n          \"@type\": \"@id\"\n        },\n        \"status\": {\n          \"@id\": \"zoom:RecordingFile/status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"recording_type\": {\n          \"@id\": \"zoom:RecordingFile/recordingType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"LiveStream\": {\n      \"@id\": \"zoom:LiveStream\",\n      \"@context\": {\n        \"stream_url\": {\n          \"@id\": \"zoom:LiveStream/streamUrl\",\n          \"@type\": \"@id\"\n        },\n        \"stream_key\": {\n          \"@id\": \"zoom:LiveStream/streamKey\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"page_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"resolution\": {\n          \"@id\": \"zoom:LiveStream/resolution\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"WebhookEvent\": {\n      \"@id\": \"zoom:WebhookEvent\",\n      \"@context\": {\n        \"event\": {\n          \"@id\": \"zoom:WebhookEvent/event\",\n          \"@type\": \"xsd:string\"\n        },\n        \"event_ts\": {\n          \"@id\": \"zoom:WebhookEvent/eventTimestamp\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"payload\": {\n          \"@id\": \"zoom:WebhookEvent/payload\",\n          \"@type\": \"@id\"\n        },\n        \"download_token\": {\n          \"@id\": \"zoom:WebhookEvent/downloadToken\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"zoom:User\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n    \
  \      \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"first_name\": {\n          \"@id\": \"schema:givenName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"last_name\": {\n          \"@id\": \"schema:familyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"display_name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"zoom:User/type\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"role_name\": {\n          \"@id\": \"schema:roleName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"pmi\": {\n          \"@id\": \"zoom:User/personalMeetingId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"timezone\": {\n          \"@id\": \"zoom:User/timezone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dept\": {\n    \
  \      \"@id\": \"zoom:User/department\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_login_time\": {\n          \"@id\": \"zoom:User/lastLoginTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"pic_url\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"language\": {\n          \"@id\": \"schema:inLanguage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"zoom:User/status\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zoom/refs/heads/main/json-ld/zoom-context.jsonld
tags:
- Chat
- Collaboration
- Communications
- Meetings
- Video Conferencing
- Videos
- Webinars
- JSON-LD
- Linked Data
- Semantic Web
---
