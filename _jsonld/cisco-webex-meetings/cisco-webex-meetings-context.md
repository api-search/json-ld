---
class_count: 18
classes:
- Meeting
- Recording
- Transcript
- Participant
- Invitee
- Host
- Site
- PersonalRoom
- Poll
- QandA
- name
- title
- startTime
- endTime
- duration
- joinLink
- createdAt
- updatedAt
context_file: json-ld/cisco-webex-meetings-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cisco-webex-meetings/refs/heads/main/json-ld/cisco-webex-meetings-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cisco Webex Meetings from Cisco Webex Meetings.
layout: jsonld
name: Cisco Webex Meetings Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: webex
  uri: https://developer.webex.com/vocab/
properties: []
property_count: 0
provider_name: Cisco Webex Meetings
provider_slug: cisco-webex-meetings
slug: cisco-webex-meetings-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://apievangelist.com/vocab/cisco-webex-meetings/\",\n    \"schema\": \"https://schema.org/\",\n    \"webex\": \"https://developer.webex.com/vocab/\",\n    \"Meeting\": \"schema:Event\",\n    \"Recording\": \"schema:VideoObject\",\n    \"Transcript\": \"schema:CreativeWork\",\n    \"Participant\": \"schema:Person\",\n    \"Invitee\": \"schema:Person\",\n    \"Host\": \"schema:Person\",\n    \"Site\": \"webex:Site\",\n    \"PersonalRoom\": \"webex:PersonalRoom\",\n    \"Poll\": \"webex:Poll\",\n    \"QandA\": \"webex:QandA\",\n    \"name\": \"schema:name\",\n    \"title\": \"webex:title\",\n    \"startTime\": \"schema:startDate\",\n    \"endTime\": \"schema:endDate\",\n    \"duration\": \"schema:duration\",\n    \"joinLink\": \"webex:joinLink\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cisco-webex-meetings/refs/heads/main/json-ld/cisco-webex-meetings-context.jsonld
tags:
- Collaboration
- Communications
- Enterprise
- Meetings
- Video Conferencing
- JSON-LD
- Linked Data
- Semantic Web
---
