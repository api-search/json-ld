---
class_count: 45
classes:
- ResourceIdentifier
- SkillResponse
- LocalizedMetadata
- Notification
- LearningObjectResponse
- GamificationPointsResponse
- UserGroupListResponse
- Skill
- UserBadgeListResponse
- Catalog
- UserResponse
- EnrollmentListResponse
- NotificationListResponse
- UserSkillListResponse
- UserGroup
- EnrollmentCreateRequest
- UserGroupResponse
- CatalogListResponse
- LearningObjectInstance
- User
- CertificationListResponse
- CatalogResponse
- AccountResponse
- JobCreateRequest
- BadgeResponse
- EnrollmentResponse
- Relationship
- Account
- Job
- BadgeListResponse
- Badge
- GamificationPoints
- LearningObjectListResponse
- SkillListResponse
- PaginationLinks
- JobResponse
- Enrollment
- LearningObject
- LearningObjectInstanceListResponse
- JobListResponse
- UserUpdateRequest
- UserListResponse
- description
- name
- email
context_file: json-ld/adobe-captivate-prime-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-captivate/refs/heads/main/json-ld/adobe-captivate-prime-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Captivate Prime Api from Adobe Captivate.
layout: jsonld
name: Adobe Captivate Prime Api Context
namespaces:
- prefix: alm
  uri: https://learningmanager.adobe.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: data
  type: reference
- container: ''
  name: attributes
  type: reference
- container: ''
  name: state
  type: string
- container: ''
  name: relationships
  type: reference
- container: ''
  name: skillLevels
  type: reference
- container: ''
  name: links
  type: reference
- container: ''
  name: learningObjects
  type: reference
- container: ''
  name: locale
  type: string
- container: ''
  name: overview
  type: string
- container: ''
  name: richTextOverview
  type: string
- container: ''
  name: actionTaken
  type: boolean
- container: ''
  name: channel
  type: string
- container: ''
  name: dateCreated
  type: dateTime
- container: ''
  name: message
  type: reference
- container: ''
  name: modelType
  type: string
- container: ''
  name: read
  type: boolean
- container: set
  name: authorNames
  type: string
- container: ''
  name: datePublished
  type: dateTime
- container: ''
  name: dateUpdated
  type: dateTime
- container: ''
  name: duration
  type: integer
- container: ''
  name: effectiveModifiedDate
  type: dateTime
- container: ''
  name: enrollmentType
  type: string
- container: ''
  name: imageUrl
  type: reference
- container: ''
  name: loFormat
  type: string
- container: ''
  name: loType
  type: string
- container: set
  name: localizedMetadata
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: unenrollmentAllowed
  type: boolean
- container: ''
  name: instances
  type: reference
- container: ''
  name: skills
  type: reference
- container: ''
  name: prerequisiteLOs
  type: reference
- container: ''
  name: subLOs
  type: reference
- container: ''
  name: authors
  type: reference
- container: ''
  name: catalog
  type: reference
- container: set
  name: included
  type: string
- container: ''
  name: learnerPoints
  type: integer
- container: ''
  name: managerPoints
  type: integer
- container: ''
  name: overallPoints
  type: integer
- container: ''
  name: userCount
  type: integer
- container: ''
  name: self
  type: reference
- container: ''
  name: next
  type: reference
- container: ''
  name: prev
  type: reference
- container: ''
  name: related
  type: reference
- container: ''
  name: assertionUrl
  type: reference
- container: ''
  name: dateAchieved
  type: dateTime
- container: ''
  name: badge
  type: reference
- container: ''
  name: learningObject
  type: reference
- container: ''
  name: isDefault
  type: boolean
- container: ''
  name: isInternallySearchable
  type: boolean
- container: ''
  name: avatarUrl
  type: reference
- container: ''
  name: pointsEarned
  type: integer
- container: ''
  name: profile
  type: string
- container: set
  name: roles
  type: string
- container: ''
  name: userType
  type: string
- container: ''
  name: manager
  type: reference
- container: ''
  name: userGroups
  type: reference
- container: ''
  name: account
  type: reference
- container: ''
  name: completedOn
  type: dateTime
- container: ''
  name: dateEnrolled
  type: dateTime
- container: ''
  name: dateStarted
  type: dateTime
- container: ''
  name: hasPassed
  type: boolean
- container: ''
  name: progressPercent
  type: integer
- container: ''
  name: score
  type: decimal
- container: ''
  name: learner
  type: reference
- container: ''
  name: loInstance
  type: reference
- container: ''
  name: skill
  type: reference
- container: ''
  name: skillLevel
  type: reference
- container: ''
  name: loInstanceId
  type: string
- container: ''
  name: completionDeadline
  type: dateTime
- container: ''
  name: enrollmentDeadline
  type: dateTime
- container: ''
  name: seatLimit
  type: integer
- container: ''
  name: gamificationEnabled
  type: boolean
- container: ''
  name: subdomain
  type: string
- container: ''
  name: timezone
  type: string
- container: ''
  name: jobType
  type: string
- container: ''
  name: dateCompleted
  type: dateTime
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: status
  type: string
property_count: 80
provider_name: Adobe Captivate
provider_slug: adobe-captivate
slug: adobe-captivate-prime-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"alm\": \"https://learningmanager.adobe.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ResourceIdentifier\": \"alm:ResourceIdentifier\",\n    \"SkillResponse\": \"alm:SkillResponse\",\n    \"LocalizedMetadata\": \"alm:LocalizedMetadata\",\n    \"Notification\": \"alm:Notification\",\n    \"LearningObjectResponse\": \"alm:LearningObjectResponse\",\n    \"GamificationPointsResponse\": \"alm:GamificationPointsResponse\",\n    \"UserGroupListResponse\": \"alm:UserGroupListResponse\",\n    \"Skill\": \"alm:Skill\",\n    \"UserBadgeListResponse\": \"alm:UserBadgeListResponse\",\n    \"Catalog\": \"alm:Catalog\",\n    \"UserResponse\": \"alm:UserResponse\",\n    \"EnrollmentListResponse\": \"alm:EnrollmentListResponse\",\n    \"NotificationListResponse\": \"alm:NotificationListResponse\",\n    \"UserSkillListResponse\"\
  : \"alm:UserSkillListResponse\",\n    \"UserGroup\": \"alm:UserGroup\",\n    \"EnrollmentCreateRequest\": \"alm:EnrollmentCreateRequest\",\n    \"UserGroupResponse\": \"alm:UserGroupResponse\",\n    \"CatalogListResponse\": \"alm:CatalogListResponse\",\n    \"LearningObjectInstance\": \"alm:LearningObjectInstance\",\n    \"User\": \"alm:User\",\n    \"CertificationListResponse\": \"alm:CertificationListResponse\",\n    \"CatalogResponse\": \"alm:CatalogResponse\",\n    \"AccountResponse\": \"alm:AccountResponse\",\n    \"JobCreateRequest\": \"alm:JobCreateRequest\",\n    \"BadgeResponse\": \"alm:BadgeResponse\",\n    \"EnrollmentResponse\": \"alm:EnrollmentResponse\",\n    \"Relationship\": \"alm:Relationship\",\n    \"Account\": \"alm:Account\",\n    \"Job\": \"alm:Job\",\n    \"BadgeListResponse\": \"alm:BadgeListResponse\",\n    \"Badge\": \"alm:Badge\",\n    \"GamificationPoints\": \"alm:GamificationPoints\",\n    \"LearningObjectListResponse\": \"alm:LearningObjectListResponse\",\n\
  \    \"SkillListResponse\": \"alm:SkillListResponse\",\n    \"PaginationLinks\": \"alm:PaginationLinks\",\n    \"JobResponse\": \"alm:JobResponse\",\n    \"Enrollment\": \"alm:Enrollment\",\n    \"LearningObject\": \"alm:LearningObject\",\n    \"LearningObjectInstanceListResponse\": \"alm:LearningObjectInstanceListResponse\",\n    \"JobListResponse\": \"alm:JobListResponse\",\n    \"UserUpdateRequest\": \"alm:UserUpdateRequest\",\n    \"UserListResponse\": \"alm:UserListResponse\",\n    \"id\": {\n      \"@id\": \"alm:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"alm:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"alm:data\",\n      \"@type\": \"@id\"\n    },\n    \"attributes\": {\n      \"@id\": \"alm:attributes\",\n      \"@type\": \"@id\"\n    },\n    \"description\": \"schema:description\",\n    \"name\": \"schema:name\",\n    \"state\": {\n      \"@id\": \"alm:state\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"relationships\": {\n      \"@id\": \"alm:relationships\",\n      \"@type\": \"@id\"\n    },\n    \"skillLevels\": {\n      \"@id\": \"alm:skillLevels\",\n      \"@type\": \"@id\"\n    },\n    \"links\": {\n      \"@id\": \"alm:links\",\n      \"@type\": \"@id\"\n    },\n    \"learningObjects\": {\n      \"@id\": \"alm:learningObjects\",\n      \"@type\": \"@id\"\n    },\n    \"locale\": {\n      \"@id\": \"alm:locale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overview\": {\n      \"@id\": \"alm:overview\",\n      \"@type\": \"xsd:string\"\n    },\n    \"richTextOverview\": {\n      \"@id\": \"alm:richTextOverview\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionTaken\": {\n      \"@id\": \"alm:actionTaken\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"channel\": {\n      \"@id\": \"alm:channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateCreated\": {\n      \"@id\": \"alm:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"message\": {\n\
  \      \"@id\": \"alm:message\",\n      \"@type\": \"@id\"\n    },\n    \"modelType\": {\n      \"@id\": \"alm:modelType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"read\": {\n      \"@id\": \"alm:read\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"authorNames\": {\n      \"@id\": \"alm:authorNames\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"datePublished\": {\n      \"@id\": \"alm:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateUpdated\": {\n      \"@id\": \"alm:dateUpdated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"duration\": {\n      \"@id\": \"alm:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"effectiveModifiedDate\": {\n      \"@id\": \"alm:effectiveModifiedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"enrollmentType\": {\n      \"@id\": \"alm:enrollmentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageUrl\": {\n      \"@id\": \"alm:imageUrl\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"loFormat\": {\n      \"@id\": \"alm:loFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loType\": {\n      \"@id\": \"alm:loType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localizedMetadata\": {\n      \"@id\": \"alm:localizedMetadata\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"alm:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unenrollmentAllowed\": {\n      \"@id\": \"alm:unenrollmentAllowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"instances\": {\n      \"@id\": \"alm:instances\",\n      \"@type\": \"@id\"\n    },\n    \"skills\": {\n      \"@id\": \"alm:skills\",\n      \"@type\": \"@id\"\n    },\n    \"prerequisiteLOs\": {\n      \"@id\": \"alm:prerequisiteLOs\",\n      \"@type\": \"@id\"\n    },\n    \"subLOs\": {\n      \"@id\": \"alm:subLOs\",\n      \"@type\": \"@id\"\n    },\n    \"authors\": {\n      \"@id\": \"alm:authors\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"catalog\": {\n      \"@id\": \"alm:catalog\",\n      \"@type\": \"@id\"\n    },\n    \"included\": {\n      \"@id\": \"alm:included\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"learnerPoints\": {\n      \"@id\": \"alm:learnerPoints\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"managerPoints\": {\n      \"@id\": \"alm:managerPoints\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"overallPoints\": {\n      \"@id\": \"alm:overallPoints\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"userCount\": {\n      \"@id\": \"alm:userCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"self\": {\n      \"@id\": \"alm:self\",\n      \"@type\": \"@id\"\n    },\n    \"next\": {\n      \"@id\": \"alm:next\",\n      \"@type\": \"@id\"\n    },\n    \"prev\": {\n      \"@id\": \"alm:prev\",\n      \"@type\": \"@id\"\n    },\n    \"related\": {\n      \"@id\": \"alm:related\",\n      \"@type\": \"@id\"\n    },\n\
  \    \"assertionUrl\": {\n      \"@id\": \"alm:assertionUrl\",\n      \"@type\": \"@id\"\n    },\n    \"dateAchieved\": {\n      \"@id\": \"alm:dateAchieved\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"badge\": {\n      \"@id\": \"alm:badge\",\n      \"@type\": \"@id\"\n    },\n    \"learningObject\": {\n      \"@id\": \"alm:learningObject\",\n      \"@type\": \"@id\"\n    },\n    \"isDefault\": {\n      \"@id\": \"alm:isDefault\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isInternallySearchable\": {\n      \"@id\": \"alm:isInternallySearchable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"avatarUrl\": {\n      \"@id\": \"alm:avatarUrl\",\n      \"@type\": \"@id\"\n    },\n    \"email\": \"schema:email\",\n    \"pointsEarned\": {\n      \"@id\": \"alm:pointsEarned\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"profile\": {\n      \"@id\": \"alm:profile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roles\": {\n      \"@id\": \"alm:roles\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userType\": {\n      \"@id\": \"alm:userType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manager\": {\n      \"@id\": \"alm:manager\",\n      \"@type\": \"@id\"\n    },\n    \"userGroups\": {\n      \"@id\": \"alm:userGroups\",\n      \"@type\": \"@id\"\n    },\n    \"account\": {\n      \"@id\": \"alm:account\",\n      \"@type\": \"@id\"\n    },\n    \"completedOn\": {\n      \"@id\": \"alm:completedOn\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateEnrolled\": {\n      \"@id\": \"alm:dateEnrolled\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateStarted\": {\n      \"@id\": \"alm:dateStarted\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"hasPassed\": {\n      \"@id\": \"alm:hasPassed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"progressPercent\": {\n      \"@id\": \"alm:progressPercent\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"score\": {\n      \"@id\": \"alm:score\",\n      \"@type\"\
  : \"xsd:decimal\"\n    },\n    \"learner\": {\n      \"@id\": \"alm:learner\",\n      \"@type\": \"@id\"\n    },\n    \"loInstance\": {\n      \"@id\": \"alm:loInstance\",\n      \"@type\": \"@id\"\n    },\n    \"skill\": {\n      \"@id\": \"alm:skill\",\n      \"@type\": \"@id\"\n    },\n    \"skillLevel\": {\n      \"@id\": \"alm:skillLevel\",\n      \"@type\": \"@id\"\n    },\n    \"loInstanceId\": {\n      \"@id\": \"alm:loInstanceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completionDeadline\": {\n      \"@id\": \"alm:completionDeadline\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"enrollmentDeadline\": {\n      \"@id\": \"alm:enrollmentDeadline\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"seatLimit\": {\n      \"@id\": \"alm:seatLimit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"gamificationEnabled\": {\n      \"@id\": \"alm:gamificationEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"subdomain\": {\n      \"@id\": \"alm:subdomain\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"timezone\": {\n      \"@id\": \"alm:timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobType\": {\n      \"@id\": \"alm:jobType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateCompleted\": {\n      \"@id\": \"alm:dateCompleted\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"alm:downloadUrl\",\n      \"@type\": \"@id\"\n    },\n    \"status\": {\n      \"@id\": \"alm:status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-captivate/refs/heads/main/json-ld/adobe-captivate-prime-api-context.jsonld
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
