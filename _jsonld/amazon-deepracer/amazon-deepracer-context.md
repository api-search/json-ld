---
api_specs:
- filename: amazon-deepracer-openapi.yml
  format: yaml
  label: AWS DeepRacer API
  slug: aws-deepracer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-deepracer/refs/heads/main/openapi/amazon-deepracer-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-deepracer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-deepracer/refs/heads/main/json-ld/amazon-deepracer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Deepracer from Amazon DeepRacer.
layout: jsonld
name: Amazon Deepracer Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/deepracer/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Car
  type: ''
- container: ''
  name: Model
  type: ''
- container: ''
  name: Leaderboard
  type: ''
- container: ''
  name: LeaderboardSubmission
  type: ''
- container: ''
  name: Track
  type: ''
- container: ''
  name: vehicleArn
  type: string
- container: ''
  name: vehicleName
  type: string
- container: ''
  name: fleetArn
  type: string
- container: ''
  name: modelArn
  type: string
- container: ''
  name: modelName
  type: string
- container: ''
  name: modelStatus
  type: string
- container: ''
  name: trainingJobArn
  type: string
- container: ''
  name: rewardFunction
  type: string
- container: ''
  name: leaderboardSubmissionId
  type: string
- container: ''
  name: participantName
  type: string
- container: ''
  name: rank
  type: integer
- container: ''
  name: lapTime
  type: double
- container: ''
  name: avgLapTime
  type: double
- container: ''
  name: trackType
  type: string
- container: ''
  name: trackDimension
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: isQualifier
  type: boolean
- container: ''
  name: minimumCountOfLaps
  type: integer
- container: ''
  name: submissionClosureTime
  type: dateTime
- container: set
  name: tagsList
  type: ''
- container: set
  name: cars
  type: ''
- container: set
  name: models
  type: ''
- container: set
  name: leaderboards
  type: ''
- container: set
  name: leaderboardSubmissions
  type: ''
- container: set
  name: tracks
  type: ''
- container: ''
  name: nextToken
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: lastModifiedTime
  type: dateTime
- container: ''
  name: creationTime
  type: dateTime
- container: ''
  name: message
  type: string
- container: ''
  name: code
  type: string
property_count: 36
provider_name: Amazon DeepRacer
provider_slug: amazon-deepracer
slug: amazon-deepracer-context
source_filename: amazon-deepracer-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/deepracer/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Car\": {\"@id\": \"aws:Car\"},\n    \"Model\": {\"@id\": \"aws:ReinforcementLearningModel\"},\n    \"Leaderboard\": {\"@id\": \"aws:Leaderboard\"},\n    \"LeaderboardSubmission\": {\"@id\": \"aws:LeaderboardSubmission\"},\n    \"Track\": {\"@id\": \"aws:RacingTrack\"},\n\n    \"vehicleArn\": {\"@id\": \"aws:vehicleArn\", \"@type\": \"xsd:string\"},\n    \"vehicleName\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"fleetArn\": {\"@id\": \"aws:fleetArn\", \"@type\": \"xsd:string\"},\n    \"modelArn\": {\"@id\": \"aws:modelArn\", \"@type\": \"xsd:string\"},\n    \"modelName\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"modelStatus\": {\"@id\": \"aws:modelStatus\", \"@type\": \"xsd:string\"},\n    \"trainingJobArn\": {\"@id\": \"aws:trainingJobArn\"\
  , \"@type\": \"xsd:string\"},\n    \"rewardFunction\": {\"@id\": \"aws:rewardFunction\", \"@type\": \"xsd:string\"},\n    \"leaderboardSubmissionId\": {\"@id\": \"aws:leaderboardSubmissionId\", \"@type\": \"xsd:string\"},\n    \"participantName\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"rank\": {\"@id\": \"schema:position\", \"@type\": \"xsd:integer\"},\n    \"lapTime\": {\"@id\": \"aws:lapTime\", \"@type\": \"xsd:double\"},\n    \"avgLapTime\": {\"@id\": \"aws:avgLapTime\", \"@type\": \"xsd:double\"},\n    \"trackType\": {\"@id\": \"aws:trackType\", \"@type\": \"xsd:string\"},\n    \"trackDimension\": {\"@id\": \"aws:trackDimension\", \"@type\": \"xsd:string\"},\n    \"status\": {\"@id\": \"aws:status\", \"@type\": \"xsd:string\"},\n    \"isQualifier\": {\"@id\": \"aws:isQualifier\", \"@type\": \"xsd:boolean\"},\n    \"minimumCountOfLaps\": {\"@id\": \"aws:minimumCountOfLaps\", \"@type\": \"xsd:integer\"},\n    \"submissionClosureTime\": {\"@id\": \"aws:submissionClosureTime\"\
  , \"@type\": \"xsd:dateTime\"},\n    \"tagsList\": {\"@id\": \"aws:tagsList\", \"@container\": \"@set\"},\n\n    \"cars\": {\"@id\": \"aws:cars\", \"@container\": \"@set\"},\n    \"models\": {\"@id\": \"aws:models\", \"@container\": \"@set\"},\n    \"leaderboards\": {\"@id\": \"aws:leaderboards\", \"@container\": \"@set\"},\n    \"leaderboardSubmissions\": {\"@id\": \"aws:leaderboardSubmissions\", \"@container\": \"@set\"},\n    \"tracks\": {\"@id\": \"aws:tracks\", \"@container\": \"@set\"},\n    \"nextToken\": {\"@id\": \"aws:nextToken\", \"@type\": \"xsd:string\"},\n\n    \"createdAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"lastModifiedTime\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n    \"creationTime\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n\n    \"message\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"code\": {\"@id\": \"aws:errorCode\", \"@type\": \"xsd:string\"}\n  }\n\
  }\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-deepracer/refs/heads/main/json-ld/amazon-deepracer-context.jsonld
tags:
- Autonomous Vehicles
- Machine Learning
- Reinforcement Learning
- Robotics
- JSON-LD
- Linked Data
- Semantic Web
---
