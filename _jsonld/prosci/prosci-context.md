---
api_specs:
- filename: prosci-change-management-openapi.yml
  format: yaml
  label: Prosci Change Management
  slug: prosci
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prosci/refs/heads/main/openapi/prosci-change-management-openapi.yml
class_count: 22
classes:
- id
- type
- ChangeProject
- AdkarAssessment
- PctAssessment
- ChangePlan
- Stakeholder
- RiskAssessment
- TrainingProgram
- Enrollment
- MaturityAssessment
- name
- description
- status
- startDate
- endDate
- targetCompletionDate
- actualCompletionDate
- createdAt
- updatedAt
- email
- url
context_file: json-ld/prosci-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/prosci/refs/heads/main/json-ld/prosci-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Prosci from Prosci.
layout: jsonld
name: Prosci Context
namespaces:
- prefix: prosci
  uri: https://api.prosci.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: changeType
  type: string
- container: ''
  name: scope
  type: string
- container: ''
  name: phase
  type: string
- container: ''
  name: riskLevel
  type: string
- container: ''
  name: impactedEmployeeCount
  type: integer
- container: ''
  name: sponsor
  type: schema:Person
- container: ''
  name: changeManager
  type: schema:Person
- container: list
  name: impactedGroups
  type: ''
- container: ''
  name: projectId
  type: string
- container: ''
  name: stakeholderId
  type: string
- container: ''
  name: assessmentDate
  type: date
- container: ''
  name: awareness
  type: prosci:AdkarDimension
- container: ''
  name: desire
  type: prosci:AdkarDimension
- container: ''
  name: knowledge
  type: prosci:AdkarDimension
- container: ''
  name: ability
  type: prosci:AdkarDimension
- container: ''
  name: reinforcement
  type: prosci:AdkarDimension
- container: ''
  name: overallScore
  type: float
- container: ''
  name: barrierPoint
  type: string
- container: ''
  name: score
  type: float
- container: ''
  name: leadership
  type: prosci:PctDimension
- container: ''
  name: projectManagement
  type: prosci:PctDimension
- container: ''
  name: changeManagement
  type: prosci:PctDimension
- container: ''
  name: overallHealth
  type: string
- container: ''
  name: planType
  type: string
- container: list
  name: targetAudience
  type: ''
- container: list
  name: activities
  type: ''
- container: ''
  name: owner
  type: schema:Person
- container: ''
  name: role
  type: string
- container: ''
  name: impactLevel
  type: string
- container: ''
  name: influenceLevel
  type: string
- container: ''
  name: supportLevel
  type: string
- container: ''
  name: department
  type: string
- container: ''
  name: organizationalAttributes
  type: prosci:OrganizationalRiskAttributes
- container: ''
  name: changeCharacteristics
  type: prosci:ChangeCharacteristics
- container: ''
  name: overallRiskScore
  type: float
- container: list
  name: mitigationStrategies
  type: ''
- container: ''
  name: programType
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: durationDays
  type: integer
- container: ''
  name: certificationLevel
  type: string
- container: ''
  name: overallLevel
  type: integer
- container: ''
  name: leadershipCompetency
  type: prosci:MaturityDimension
- container: ''
  name: applicationCompetency
  type: prosci:MaturityDimension
- container: ''
  name: competencyDevelopment
  type: prosci:MaturityDimension
- container: ''
  name: standardization
  type: prosci:MaturityDimension
- container: ''
  name: socialization
  type: prosci:MaturityDimension
property_count: 46
provider_name: Prosci
provider_slug: prosci
slug: prosci-context
source_filename: prosci-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"prosci\": \"https://api.prosci.com/vocab#\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"ChangeProject\": \"prosci:ChangeProject\",\n    \"AdkarAssessment\": \"prosci:AdkarAssessment\",\n    \"PctAssessment\": \"prosci:PctAssessment\",\n    \"ChangePlan\": \"prosci:ChangePlan\",\n    \"Stakeholder\": \"prosci:Stakeholder\",\n    \"RiskAssessment\": \"prosci:RiskAssessment\",\n    \"TrainingProgram\": \"prosci:TrainingProgram\",\n    \"Enrollment\": \"prosci:Enrollment\",\n    \"MaturityAssessment\": \"prosci:MaturityAssessment\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"prosci:status\",\n    \"startDate\": \"schema:startDate\",\n    \"endDate\": \"schema:endDate\",\n    \"targetCompletionDate\": \"prosci:targetCompletionDate\",\n    \"actualCompletionDate\": \"prosci:actualCompletionDate\",\n    \"createdAt\": \"schema:dateCreated\",\n\
  \    \"updatedAt\": \"schema:dateModified\",\n    \"email\": \"schema:email\",\n    \"url\": \"schema:url\",\n\n    \"changeType\": {\n      \"@id\": \"prosci:changeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scope\": {\n      \"@id\": \"prosci:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phase\": {\n      \"@id\": \"prosci:phase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskLevel\": {\n      \"@id\": \"prosci:riskLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"impactedEmployeeCount\": {\n      \"@id\": \"prosci:impactedEmployeeCount\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"sponsor\": {\n      \"@id\": \"prosci:sponsor\",\n      \"@type\": \"schema:Person\"\n    },\n    \"changeManager\": {\n      \"@id\": \"prosci:changeManager\",\n      \"@type\": \"schema:Person\"\n    },\n    \"impactedGroups\": {\n      \"@id\": \"prosci:impactedGroups\",\n      \"@container\": \"@list\"\n    },\n\n    \"projectId\": {\n      \"@id\": \"prosci:projectId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"stakeholderId\": {\n      \"@id\": \"prosci:stakeholderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assessmentDate\": {\n      \"@id\": \"prosci:assessmentDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"awareness\": {\n      \"@id\": \"prosci:awareness\",\n      \"@type\": \"prosci:AdkarDimension\"\n    },\n    \"desire\": {\n      \"@id\": \"prosci:desire\",\n      \"@type\": \"prosci:AdkarDimension\"\n    },\n    \"knowledge\": {\n      \"@id\": \"prosci:knowledge\",\n      \"@type\": \"prosci:AdkarDimension\"\n    },\n    \"ability\": {\n      \"@id\": \"prosci:ability\",\n      \"@type\": \"prosci:AdkarDimension\"\n    },\n    \"reinforcement\": {\n      \"@id\": \"prosci:reinforcement\",\n      \"@type\": \"prosci:AdkarDimension\"\n    },\n    \"overallScore\": {\n      \"@id\": \"prosci:overallScore\",\n      \"@type\": \"xsd:float\"\n    },\n    \"barrierPoint\": {\n      \"@id\": \"prosci:barrierPoint\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"score\": {\n      \"@id\": \"prosci:score\",\n      \"@type\": \"xsd:float\"\n    },\n\n    \"leadership\": {\n      \"@id\": \"prosci:leadership\",\n      \"@type\": \"prosci:PctDimension\"\n    },\n    \"projectManagement\": {\n      \"@id\": \"prosci:projectManagement\",\n      \"@type\": \"prosci:PctDimension\"\n    },\n    \"changeManagement\": {\n      \"@id\": \"prosci:changeManagement\",\n      \"@type\": \"prosci:PctDimension\"\n    },\n    \"overallHealth\": {\n      \"@id\": \"prosci:overallHealth\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"planType\": {\n      \"@id\": \"prosci:planType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetAudience\": {\n      \"@id\": \"prosci:targetAudience\",\n      \"@container\": \"@list\"\n    },\n    \"activities\": {\n      \"@id\": \"prosci:activities\",\n      \"@container\": \"@list\"\n    },\n    \"owner\": {\n      \"@id\": \"prosci:owner\",\n      \"@type\": \"schema:Person\"\n\
  \    },\n\n    \"role\": {\n      \"@id\": \"prosci:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"impactLevel\": {\n      \"@id\": \"prosci:impactLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"influenceLevel\": {\n      \"@id\": \"prosci:influenceLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supportLevel\": {\n      \"@id\": \"prosci:supportLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"department\": {\n      \"@id\": \"schema:department\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"organizationalAttributes\": {\n      \"@id\": \"prosci:organizationalAttributes\",\n      \"@type\": \"prosci:OrganizationalRiskAttributes\"\n    },\n    \"changeCharacteristics\": {\n      \"@id\": \"prosci:changeCharacteristics\",\n      \"@type\": \"prosci:ChangeCharacteristics\"\n    },\n    \"overallRiskScore\": {\n      \"@id\": \"prosci:overallRiskScore\",\n      \"@type\": \"xsd:float\"\n    },\n    \"mitigationStrategies\": {\n      \"@id\": \"prosci:mitigationStrategies\"\
  ,\n      \"@container\": \"@list\"\n    },\n\n    \"programType\": {\n      \"@id\": \"prosci:programType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"prosci:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"durationDays\": {\n      \"@id\": \"prosci:durationDays\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"certificationLevel\": {\n      \"@id\": \"prosci:certificationLevel\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"overallLevel\": {\n      \"@id\": \"prosci:overallLevel\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"leadershipCompetency\": {\n      \"@id\": \"prosci:leadershipCompetency\",\n      \"@type\": \"prosci:MaturityDimension\"\n    },\n    \"applicationCompetency\": {\n      \"@id\": \"prosci:applicationCompetency\",\n      \"@type\": \"prosci:MaturityDimension\"\n    },\n    \"competencyDevelopment\": {\n      \"@id\": \"prosci:competencyDevelopment\",\n      \"@type\": \"prosci:MaturityDimension\"\n    },\n \
  \   \"standardization\": {\n      \"@id\": \"prosci:standardization\",\n      \"@type\": \"prosci:MaturityDimension\"\n    },\n    \"socialization\": {\n      \"@id\": \"prosci:socialization\",\n      \"@type\": \"prosci:MaturityDimension\"\n    },\n\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/prosci/refs/heads/main/json-ld/prosci-context.jsonld
tags:
- Change Management
- Methodology
- Training
- JSON-LD
- Linked Data
- Semantic Web
---
