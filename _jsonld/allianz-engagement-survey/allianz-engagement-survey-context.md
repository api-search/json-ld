---
class_count: 16
classes:
- QuestionScore
- ParticipantList
- CreateSurveyRequest
- SurveyResponse
- CreateActionPlanRequest
- ResponseList
- Participant
- AddParticipantsResponse
- Survey
- AddParticipantsRequest
- SurveyList
- Answer
- SurveyAnalytics
- ActionPlan
- ActionPlanList
- description
context_file: json-ld/allianz-engagement-survey-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/allianz-engagement-survey/refs/heads/main/json-ld/allianz-engagement-survey-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Allianz Engagement Survey from Allianz Engagement Survey.
layout: jsonld
name: Allianz Engagement Survey Context
namespaces:
- prefix: allianz
  uri: https://api.allianz.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: questionId
  type: string
- container: ''
  name: question
  type: string
- container: ''
  name: score
  type: double
- container: ''
  name: favorable
  type: double
- container: ''
  name: total
  type: integer
- container: ''
  name: responded
  type: integer
- container: ''
  name: participationRate
  type: double
- container: set
  name: items
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: surveyType
  type: string
- container: ''
  name: startDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: responseId
  type: string
- container: ''
  name: surveyId
  type: string
- container: ''
  name: submittedAt
  type: dateTime
- container: set
  name: answers
  type: string
- container: ''
  name: ownerEmployeeId
  type: string
- container: ''
  name: dueDate
  type: date
- container: ''
  name: participantId
  type: string
- container: ''
  name: employeeId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: invitedAt
  type: dateTime
- container: ''
  name: respondedAt
  type: dateTime
- container: ''
  name: added
  type: integer
- container: ''
  name: invitationSent
  type: boolean
- container: ''
  name: failed
  type: integer
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
- container: set
  name: employeeIds
  type: string
- container: ''
  name: sendInvitation
  type: boolean
- container: ''
  name: offset
  type: integer
- container: ''
  name: limit
  type: integer
- container: ''
  name: textResponse
  type: string
- container: ''
  name: engagementScore
  type: double
- container: ''
  name: favorablePercentage
  type: double
- container: set
  name: questionScores
  type: string
- container: ''
  name: planId
  type: string
- container: ''
  name: owner
  type: string
property_count: 38
provider_name: Allianz Engagement Survey
provider_slug: allianz-engagement-survey
slug: allianz-engagement-survey-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"allianz\": \"https://api.allianz.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"QuestionScore\": \"allianz:QuestionScore\",\n    \"ParticipantList\": \"allianz:ParticipantList\",\n    \"CreateSurveyRequest\": \"allianz:CreateSurveyRequest\",\n    \"SurveyResponse\": \"allianz:SurveyResponse\",\n    \"CreateActionPlanRequest\": \"allianz:CreateActionPlanRequest\",\n    \"ResponseList\": \"allianz:ResponseList\",\n    \"Participant\": \"allianz:Participant\",\n    \"AddParticipantsResponse\": \"allianz:AddParticipantsResponse\",\n    \"Survey\": \"allianz:Survey\",\n    \"AddParticipantsRequest\": \"allianz:AddParticipantsRequest\",\n    \"SurveyList\": \"allianz:SurveyList\",\n    \"Answer\": \"allianz:Answer\",\n    \"SurveyAnalytics\": \"allianz:SurveyAnalytics\",\n    \"ActionPlan\": \"allianz:ActionPlan\"\
  ,\n    \"ActionPlanList\": \"allianz:ActionPlanList\",\n    \"questionId\": {\n      \"@id\": \"allianz:question_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"question\": {\n      \"@id\": \"allianz:question\",\n      \"@type\": \"xsd:string\"\n    },\n    \"score\": {\n      \"@id\": \"allianz:score\",\n      \"@type\": \"xsd:double\"\n    },\n    \"favorable\": {\n      \"@id\": \"allianz:favorable\",\n      \"@type\": \"xsd:double\"\n    },\n    \"total\": {\n      \"@id\": \"allianz:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"responded\": {\n      \"@id\": \"allianz:responded\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"participationRate\": {\n      \"@id\": \"allianz:participation_rate\",\n      \"@type\": \"xsd:double\"\n    },\n    \"items\": {\n      \"@id\": \"allianz:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"allianz:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  surveyType\": {\n      \"@id\": \"allianz:survey_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"startDate\": {\n      \"@id\": \"allianz:start_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"allianz:end_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"responseId\": {\n      \"@id\": \"allianz:response_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"surveyId\": {\n      \"@id\": \"allianz:survey_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submittedAt\": {\n      \"@id\": \"allianz:submitted_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"answers\": {\n      \"@id\": \"allianz:answers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerEmployeeId\": {\n      \"@id\": \"allianz:owner_employee_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dueDate\": {\n      \"@id\": \"allianz:due_date\",\n      \"@type\": \"xsd:date\"\n    },\n\
  \    \"participantId\": {\n      \"@id\": \"allianz:participant_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"employeeId\": {\n      \"@id\": \"allianz:employee_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"allianz:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invitedAt\": {\n      \"@id\": \"allianz:invited_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"respondedAt\": {\n      \"@id\": \"allianz:responded_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"added\": {\n      \"@id\": \"allianz:added\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"invitationSent\": {\n      \"@id\": \"allianz:invitation_sent\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"failed\": {\n      \"@id\": \"allianz:failed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"allianz:created_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedAt\": {\n      \"@id\": \"allianz:modified_at\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"employeeIds\": {\n      \"@id\": \"allianz:employee_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sendInvitation\": {\n      \"@id\": \"allianz:send_invitation\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"offset\": {\n      \"@id\": \"allianz:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"limit\": {\n      \"@id\": \"allianz:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"textResponse\": {\n      \"@id\": \"allianz:text_response\",\n      \"@type\": \"xsd:string\"\n    },\n    \"engagementScore\": {\n      \"@id\": \"allianz:engagement_score\",\n      \"@type\": \"xsd:double\"\n    },\n    \"favorablePercentage\": {\n      \"@id\": \"allianz:favorable_percentage\",\n      \"@type\": \"xsd:double\"\n    },\n    \"questionScores\": {\n      \"@id\": \"allianz:question_scores\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"planId\"\
  : {\n      \"@id\": \"allianz:plan_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"allianz:owner\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/allianz-engagement-survey/refs/heads/main/json-ld/allianz-engagement-survey-context.jsonld
tags:
- Analytics
- Enterprise
- Human Resources
- Insurance
- Surveys
- Employee Experience
- JSON-LD
- Linked Data
- Semantic Web
---
