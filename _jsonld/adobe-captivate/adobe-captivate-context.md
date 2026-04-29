---
api_specs:
- filename: adobe-captivate-prime-api-openapi.yml
  format: yaml
  label: Adobe Captivate Prime API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-captivate/refs/heads/main/openapi/adobe-captivate-prime-api-openapi.yml
- filename: adobe-captivate-learning-manager-webhooks-asyncapi.yml
  format: yaml
  label: Adobe Learning Manager Webhooks API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-captivate/refs/heads/main/asyncapi/adobe-captivate-learning-manager-webhooks-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/adobe-captivate-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-captivate/refs/heads/main/json-ld/adobe-captivate-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Captivate from Adobe Captivate.
layout: jsonld
name: Adobe Captivate Context
namespaces:
- prefix: alm
  uri: https://learningmanager.adobe.com/primeapi/v2/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xapi
  uri: https://w3id.org/xapi/ontology#
properties:
- container: ''
  name: LearningObject
  type: ''
- container: ''
  name: LearningObjectInstance
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Enrollment
  type: ''
- container: ''
  name: Catalog
  type: ''
- container: ''
  name: Skill
  type: ''
- container: ''
  name: SkillLevel
  type: ''
- container: ''
  name: Badge
  type: ''
- container: ''
  name: UserBadge
  type: ''
- container: ''
  name: UserGroup
  type: ''
- container: ''
  name: Certification
  type: ''
- container: ''
  name: Gamification
  type: ''
- container: ''
  name: Job
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: Notification
  type: ''
- container: ''
  name: WebhookEvent
  type: ''
property_count: 16
provider_name: Adobe Captivate
provider_slug: adobe-captivate
slug: adobe-captivate-context
source_filename: adobe-captivate-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"alm\": \"https://learningmanager.adobe.com/primeapi/v2/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xapi\": \"https://w3id.org/xapi/ontology#\",\n\n    \"LearningObject\": {\n      \"@id\": \"alm:LearningObject\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"loType\": \"alm:learningObjectType\",\n        \"state\": \"alm:state\",\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"datePublished\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dateUpdated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"duration\": {\n          \"@id\": \"schema:timeRequired\",\n          \"@type\": \"xsd:integer\"\n\
  \        },\n        \"enrollmentType\": \"alm:enrollmentType\",\n        \"imageUrl\": {\n          \"@id\": \"schema:thumbnailUrl\",\n          \"@type\": \"@id\"\n        },\n        \"loFormat\": \"alm:learningFormat\",\n        \"localizedMetadata\": {\n          \"@id\": \"alm:localizedMetadata\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"authorNames\": {\n          \"@id\": \"schema:author\",\n          \"@container\": \"@list\"\n        },\n        \"unenrollmentAllowed\": \"alm:unenrollmentAllowed\",\n        \"rating\": \"schema:aggregateRating\"\n      }\n    },\n\n    \"LearningObjectInstance\": {\n      \"@id\": \"alm:LearningObjectInstance\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"completionDeadline\": {\n          \"@id\": \"alm:completionDeadline\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"enrollmentDeadline\"\
  : {\n          \"@id\": \"alm:enrollmentDeadline\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"isDefault\": \"alm:isDefault\",\n        \"seatLimit\": \"alm:seatLimit\",\n        \"state\": \"alm:state\"\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"alm:User\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"avatarUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"profile\": \"schema:description\",\n        \"roles\": {\n          \"@id\": \"alm:roles\",\n          \"@container\": \"@set\"\n        },\n        \"state\": \"alm:accountState\",\n        \"userType\": \"alm:userType\",\n        \"pointsEarned\": \"alm:gamificationPoints\"\n      }\n    },\n\n    \"Enrollment\": {\n      \"@id\": \"alm:Enrollment\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"dateEnrolled\": {\n          \"@id\": \"alm:dateEnrolled\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dateStarted\": {\n          \"@id\": \"alm:dateStarted\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedOn\": {\n          \"@id\": \"alm:completedOn\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"progressPercent\": \"alm:progressPercent\",\n        \"score\": \"alm:score\",\n        \"hasPassed\": \"alm:hasPassed\",\n        \"state\": \"alm:enrollmentState\",\n        \"learner\": {\n          \"@id\": \"alm:learner\",\n          \"@type\": \"@id\"\n        },\n        \"learningObject\": {\n          \"@id\": \"alm:learningObject\",\n          \"@type\": \"@id\"\n        },\n        \"loInstance\": {\n          \"@id\": \"alm:loInstance\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Catalog\": {\n      \"@id\": \"alm:Catalog\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"dcterms:description\"\
  ,\n        \"isDefault\": \"alm:isDefault\",\n        \"isInternallySearchable\": \"alm:isInternallySearchable\",\n        \"state\": \"alm:state\",\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dateUpdated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"learningObjects\": {\n          \"@id\": \"alm:learningObjects\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Skill\": {\n      \"@id\": \"alm:Skill\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"dcterms:description\",\n        \"state\": \"alm:state\",\n        \"skillLevels\": {\n          \"@id\": \"alm:skillLevels\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"SkillLevel\": {\n      \"@id\": \"alm:SkillLevel\",\n      \"@context\": {\n        \"id\": \"@id\",\n \
  \       \"name\": \"schema:name\",\n        \"maxCredits\": \"alm:maxCredits\",\n        \"level\": \"alm:level\"\n      }\n    },\n\n    \"Badge\": {\n      \"@id\": \"alm:Badge\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"imageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"state\": \"alm:state\"\n      }\n    },\n\n    \"UserBadge\": {\n      \"@id\": \"alm:UserBadge\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"dateAchieved\": {\n          \"@id\": \"alm:dateAchieved\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"assertionUrl\": {\n          \"@id\": \"alm:assertionUrl\",\n          \"@type\": \"@id\"\n        },\n        \"badge\": {\n          \"@id\": \"alm:badge\",\n          \"@type\": \"@id\"\n        },\n        \"learner\": {\n          \"@id\": \"alm:learner\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"UserGroup\"\
  : {\n      \"@id\": \"alm:UserGroup\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"dcterms:description\",\n        \"state\": \"alm:state\",\n        \"userCount\": \"alm:userCount\",\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Certification\": {\n      \"@id\": \"alm:Certification\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"validityDuration\": \"alm:validityDuration\",\n        \"recertificationDeadline\": {\n          \"@id\": \"alm:recertificationDeadline\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"validUntil\": {\n          \"@id\": \"alm:validUntil\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Gamification\": {\n      \"@id\": \"alm:Gamification\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"\
  learnerPoints\": \"alm:learnerPoints\",\n        \"managerPoints\": \"alm:managerPoints\",\n        \"overallPoints\": \"alm:overallPoints\"\n      }\n    },\n\n    \"Job\": {\n      \"@id\": \"alm:Job\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"jobType\": \"alm:jobType\",\n        \"status\": \"alm:jobStatus\",\n        \"description\": \"dcterms:description\",\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dateCompleted\": {\n          \"@id\": \"alm:dateCompleted\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"downloadUrl\": {\n          \"@id\": \"alm:downloadUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Account\": {\n      \"@id\": \"alm:Account\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"subdomain\": \"alm:subdomain\",\n        \"locale\": \"schema:inLanguage\",\n        \"timezone\"\
  : \"alm:timezone\",\n        \"gamificationEnabled\": \"alm:gamificationEnabled\",\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Notification\": {\n      \"@id\": \"alm:Notification\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"message\": \"alm:message\",\n        \"channel\": \"alm:channel\",\n        \"read\": \"alm:read\",\n        \"actionTaken\": \"alm:actionTaken\",\n        \"modelType\": \"alm:modelType\",\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"WebhookEvent\": {\n      \"@id\": \"alm:WebhookEvent\",\n      \"@context\": {\n        \"eventType\": \"alm:eventType\",\n        \"eventId\": {\n          \"@id\": \"alm:eventId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountId\": \"alm:accountId\",\n        \"timestamp\": {\n          \"@id\":\
  \ \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"source\": \"alm:eventSource\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-captivate/refs/heads/main/json-ld/adobe-captivate-context.jsonld
tags:
- Authoring
- Education
- eLearning
- LMS
- SCORM
- Training
- xAPI
- JSON-LD
- Linked Data
- Semantic Web
---
