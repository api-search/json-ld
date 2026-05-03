---
api_specs:
- filename: Recruiting_OpenAPI.yaml
  format: yaml
  label: Workday Recruiting REST API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v41.2/Recruiting_OpenAPI.yaml
class_count: 31
classes:
- Applicant
- ApplicantImport
- Attachment
- BackgroundCheck
- BackgroundCheckCreate
- BackgroundCheckPackage
- Candidate
- CandidateAssessment
- CandidateCreate
- EvergreenRequisition
- EvergreenRequisitionCreate
- Interview
- InterviewCreate
- InterviewFeedback
- InterviewFeedbackCreate
- JobApplication
- JobPosting
- JobPostingSite
- JobRequisition
- JobRequisitionCreate
- Offer
- OfferCreate
- Position
- PositionCreate
- Questionnaire
- RecruitingAgency
- Reference
- VeteranStatus
- description
- email
- name
context_file: json-ld/workday-recruiting-rest-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workday-recruiting/refs/heads/main/json-ld/workday-recruiting-rest-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Workday Recruiting Rest Api from Workday Recruiting.
layout: jsonld
name: Workday Recruiting Rest Api Context
namespaces:
- prefix: workday
  uri: https://community.workday.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: active
  type: boolean
- container: ''
  name: address
  type: reference
- container: ''
  name: addressLine1
  type: string
- container: ''
  name: addressLine2
  type: string
- container: ''
  name: appliedOn
  type: dateTime
- container: ''
  name: assessedOn
  type: dateTime
- container: ''
  name: assessmentCategory
  type: reference
- container: ''
  name: availableDate
  type: date
- container: ''
  name: candidate
  type: reference
- container: ''
  name: category
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: comments
  type: string
- container: ''
  name: compensationAmount
  type: decimal
- container: ''
  name: compensationFrequency
  type: string
- container: ''
  name: compensationRange
  type: reference
- container: ''
  name: competency
  type: reference
- container: set
  name: competencyRatings
  type: reference
- container: ''
  name: completedOn
  type: dateTime
- container: ''
  name: contactEmail
  type: string
- container: ''
  name: contactName
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: country
  type: reference
- container: ''
  name: createdOn
  type: dateTime
- container: ''
  name: currency
  type: reference
- container: ''
  name: currentStage
  type: string
- container: ''
  name: descriptor
  type: string
- container: ''
  name: dispositionReason
  type: reference
- container: ''
  name: endDate
  type: date
- container: ''
  name: endTime
  type: time
- container: ''
  name: expirationDate
  type: date
- container: ''
  name: feePercentage
  type: decimal
- container: ''
  name: fileName
  type: string
- container: ''
  name: fileSize
  type: integer
- container: ''
  name: firstName
  type: string
- container: ''
  name: frequency
  type: string
- container: ''
  name: fullName
  type: string
- container: ''
  name: hireDate
  type: date
- container: ''
  name: hiringManager
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: interviewType
  type: string
- container: ''
  name: interviewer
  type: reference
- container: set
  name: interviewers
  type: reference
- container: ''
  name: isActive
  type: boolean
- container: ''
  name: isDispositioned
  type: boolean
- container: ''
  name: isFilled
  type: boolean
- container: ''
  name: isInternal
  type: boolean
- container: ''
  name: isPrimary
  type: boolean
- container: ''
  name: jobApplication
  type: reference
- container: set
  name: jobApplications
  type: reference
- container: ''
  name: jobDescription
  type: string
- container: ''
  name: jobProfile
  type: reference
- container: ''
  name: jobRequisition
  type: reference
- container: ''
  name: lastName
  type: string
- container: set
  name: linkedJobRequisitions
  type: reference
- container: ''
  name: location
  type: string
- container: ''
  name: maximum
  type: decimal
- container: ''
  name: minimum
  type: decimal
- container: ''
  name: numberOfOpenings
  type: integer
- container: set
  name: options
  type: string
- container: ''
  name: overallRating
  type: string
- container: ''
  name: package
  type: reference
- container: ''
  name: phone
  type: string
- container: ''
  name: position
  type: reference
- container: ''
  name: positionId
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: postedOn
  type: dateTime
- container: ''
  name: postingSite
  type: reference
- container: ''
  name: proposedStartDate
  type: date
- container: ''
  name: provider
  type: reference
- container: ''
  name: qualifications
  type: string
- container: ''
  name: questionText
  type: string
- container: ''
  name: questionType
  type: string
- container: set
  name: questions
  type: reference
- container: ''
  name: rating
  type: integer
- container: ''
  name: recruiter
  type: reference
- container: ''
  name: required
  type: boolean
- container: ''
  name: requisitionNumber
  type: string
- container: ''
  name: result
  type: string
- container: ''
  name: scheduledDate
  type: date
- container: ''
  name: score
  type: decimal
- container: ''
  name: siteUrl
  type: reference
- container: ''
  name: source
  type: reference
- container: ''
  name: startDate
  type: date
- container: ''
  name: startTime
  type: time
- container: ''
  name: stateProvince
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: submittedOn
  type: dateTime
- container: ''
  name: supervisoryOrganization
  type: reference
- container: set
  name: tags
  type: string
- container: ''
  name: targetEndDate
  type: date
- container: ''
  name: targetHireDate
  type: date
- container: ''
  name: timeType
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: updatedOn
  type: dateTime
- container: ''
  name: uploadedOn
  type: dateTime
- container: ''
  name: webConferenceUrl
  type: reference
- container: ''
  name: worker
  type: reference
- container: ''
  name: workerType
  type: reference
property_count: 99
provider_name: Workday Recruiting
provider_slug: workday-recruiting
slug: workday-recruiting-rest-api-context
source_filename: workday-recruiting-rest-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"workday\": \"https://community.workday.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Applicant\": \"workday:Applicant\",\n    \"ApplicantImport\": \"workday:ApplicantImport\",\n    \"Attachment\": \"workday:Attachment\",\n    \"BackgroundCheck\": \"workday:BackgroundCheck\",\n    \"BackgroundCheckCreate\": \"workday:BackgroundCheckCreate\",\n    \"BackgroundCheckPackage\": \"workday:BackgroundCheckPackage\",\n    \"Candidate\": \"workday:Candidate\",\n    \"CandidateAssessment\": \"workday:CandidateAssessment\",\n    \"CandidateCreate\": \"workday:CandidateCreate\",\n    \"EvergreenRequisition\": \"workday:EvergreenRequisition\",\n    \"EvergreenRequisitionCreate\": \"workday:EvergreenRequisitionCreate\",\n    \"Interview\": \"workday:Interview\",\n    \"InterviewCreate\": \"workday:InterviewCreate\",\n\
  \    \"InterviewFeedback\": \"workday:InterviewFeedback\",\n    \"InterviewFeedbackCreate\": \"workday:InterviewFeedbackCreate\",\n    \"JobApplication\": \"workday:JobApplication\",\n    \"JobPosting\": \"workday:JobPosting\",\n    \"JobPostingSite\": \"workday:JobPostingSite\",\n    \"JobRequisition\": \"workday:JobRequisition\",\n    \"JobRequisitionCreate\": \"workday:JobRequisitionCreate\",\n    \"Offer\": \"workday:Offer\",\n    \"OfferCreate\": \"workday:OfferCreate\",\n    \"Position\": \"workday:Position\",\n    \"PositionCreate\": \"workday:PositionCreate\",\n    \"Questionnaire\": \"workday:Questionnaire\",\n    \"RecruitingAgency\": \"workday:RecruitingAgency\",\n    \"Reference\": \"workday:Reference\",\n    \"VeteranStatus\": \"workday:VeteranStatus\",\n    \"active\": {\n      \"@id\": \"workday:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"address\": {\n      \"@id\": \"workday:address\",\n      \"@type\": \"@id\"\n    },\n    \"addressLine1\": {\n      \"\
  @id\": \"workday:address_line1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addressLine2\": {\n      \"@id\": \"workday:address_line2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appliedOn\": {\n      \"@id\": \"workday:applied_on\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"assessedOn\": {\n      \"@id\": \"workday:assessed_on\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"assessmentCategory\": {\n      \"@id\": \"workday:assessment_category\",\n      \"@type\": \"@id\"\n    },\n    \"availableDate\": {\n      \"@id\": \"workday:available_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"candidate\": {\n      \"@id\": \"workday:candidate\",\n      \"@type\": \"@id\"\n    },\n    \"category\": {\n      \"@id\": \"workday:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"workday:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"workday:code\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"comments\": {\n      \"@id\": \"workday:comments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compensationAmount\": {\n      \"@id\": \"workday:compensation_amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"compensationFrequency\": {\n      \"@id\": \"workday:compensation_frequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compensationRange\": {\n      \"@id\": \"workday:compensation_range\",\n      \"@type\": \"@id\"\n    },\n    \"competency\": {\n      \"@id\": \"workday:competency\",\n      \"@type\": \"@id\"\n    },\n    \"competencyRatings\": {\n      \"@id\": \"workday:competency_ratings\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"completedOn\": {\n      \"@id\": \"workday:completed_on\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"contactEmail\": {\n      \"@id\": \"workday:contact_email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contactName\": {\n      \"@id\": \"workday:contact_name\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"workday:content_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"workday:country\",\n      \"@type\": \"@id\"\n    },\n    \"createdOn\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"currency\": {\n      \"@id\": \"workday:currency\",\n      \"@type\": \"@id\"\n    },\n    \"currentStage\": {\n      \"@id\": \"workday:current_stage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"descriptor\": {\n      \"@id\": \"workday:descriptor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dispositionReason\": {\n      \"@id\": \"workday:disposition_reason\",\n      \"@type\": \"@id\"\n    },\n    \"email\": \"schema:email\",\n    \"endDate\": {\n      \"@id\": \"workday:end_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endTime\": {\n      \"@id\": \"workday:end_time\",\n      \"@type\": \"xsd:time\"\
  \n    },\n    \"expirationDate\": {\n      \"@id\": \"workday:expiration_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"feePercentage\": {\n      \"@id\": \"workday:fee_percentage\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"fileName\": {\n      \"@id\": \"workday:file_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileSize\": {\n      \"@id\": \"workday:file_size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"firstName\": {\n      \"@id\": \"workday:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"frequency\": {\n      \"@id\": \"workday:frequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fullName\": {\n      \"@id\": \"workday:full_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hireDate\": {\n      \"@id\": \"workday:hire_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"hiringManager\": {\n      \"@id\": \"workday:hiring_manager\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"workday:id\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"interviewType\": {\n      \"@id\": \"workday:interview_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interviewer\": {\n      \"@id\": \"workday:interviewer\",\n      \"@type\": \"@id\"\n    },\n    \"interviewers\": {\n      \"@id\": \"workday:interviewers\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"isActive\": {\n      \"@id\": \"workday:is_active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isDispositioned\": {\n      \"@id\": \"workday:is_dispositioned\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isFilled\": {\n      \"@id\": \"workday:is_filled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isInternal\": {\n      \"@id\": \"workday:is_internal\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isPrimary\": {\n      \"@id\": \"workday:is_primary\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"jobApplication\": {\n      \"@id\": \"workday:job_application\",\n      \"@type\": \"@id\"\
  \n    },\n    \"jobApplications\": {\n      \"@id\": \"workday:job_applications\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"jobDescription\": {\n      \"@id\": \"workday:job_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobProfile\": {\n      \"@id\": \"workday:job_profile\",\n      \"@type\": \"@id\"\n    },\n    \"jobRequisition\": {\n      \"@id\": \"workday:job_requisition\",\n      \"@type\": \"@id\"\n    },\n    \"lastName\": {\n      \"@id\": \"workday:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"linkedJobRequisitions\": {\n      \"@id\": \"workday:linked_job_requisitions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"location\": {\n      \"@id\": \"workday:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maximum\": {\n      \"@id\": \"workday:maximum\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"minimum\": {\n      \"@id\": \"workday:minimum\",\n      \"@type\": \"xsd:decimal\"\
  \n    },\n    \"name\": \"schema:name\",\n    \"numberOfOpenings\": {\n      \"@id\": \"workday:number_of_openings\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"options\": {\n      \"@id\": \"workday:options\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overallRating\": {\n      \"@id\": \"workday:overall_rating\",\n      \"@type\": \"xsd:string\"\n    },\n    \"package\": {\n      \"@id\": \"workday:package\",\n      \"@type\": \"@id\"\n    },\n    \"phone\": {\n      \"@id\": \"workday:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"position\": {\n      \"@id\": \"workday:position\",\n      \"@type\": \"@id\"\n    },\n    \"positionId\": {\n      \"@id\": \"workday:position_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"workday:postal_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postedOn\": {\n      \"@id\": \"workday:posted_on\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"\
  postingSite\": {\n      \"@id\": \"workday:posting_site\",\n      \"@type\": \"@id\"\n    },\n    \"proposedStartDate\": {\n      \"@id\": \"workday:proposed_start_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"provider\": {\n      \"@id\": \"workday:provider\",\n      \"@type\": \"@id\"\n    },\n    \"qualifications\": {\n      \"@id\": \"workday:qualifications\",\n      \"@type\": \"xsd:string\"\n    },\n    \"questionText\": {\n      \"@id\": \"workday:question_text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"questionType\": {\n      \"@id\": \"workday:question_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"questions\": {\n      \"@id\": \"workday:questions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"rating\": {\n      \"@id\": \"workday:rating\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"recruiter\": {\n      \"@id\": \"workday:recruiter\",\n      \"@type\": \"@id\"\n    },\n    \"required\": {\n      \"@id\": \"workday:required\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"requisitionNumber\": {\n      \"@id\": \"workday:requisition_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"workday:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledDate\": {\n      \"@id\": \"workday:scheduled_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"score\": {\n      \"@id\": \"workday:score\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"siteUrl\": {\n      \"@id\": \"workday:site_url\",\n      \"@type\": \"@id\"\n    },\n    \"source\": {\n      \"@id\": \"workday:source\",\n      \"@type\": \"@id\"\n    },\n    \"startDate\": {\n      \"@id\": \"workday:start_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"startTime\": {\n      \"@id\": \"workday:start_time\",\n      \"@type\": \"xsd:time\"\n    },\n    \"stateProvince\": {\n      \"@id\": \"workday:state_province\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"workday:status\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"submittedOn\": {\n      \"@id\": \"workday:submitted_on\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"supervisoryOrganization\": {\n      \"@id\": \"workday:supervisory_organization\",\n      \"@type\": \"@id\"\n    },\n    \"tags\": {\n      \"@id\": \"workday:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetEndDate\": {\n      \"@id\": \"workday:target_end_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"targetHireDate\": {\n      \"@id\": \"workday:target_hire_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"timeType\": {\n      \"@id\": \"workday:time_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"workday:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedOn\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"uploadedOn\": {\n      \"@id\": \"workday:uploaded_on\",\n      \"@type\"\
  : \"xsd:dateTime\"\n    },\n    \"webConferenceUrl\": {\n      \"@id\": \"workday:web_conference_url\",\n      \"@type\": \"@id\"\n    },\n    \"worker\": {\n      \"@id\": \"workday:worker\",\n      \"@type\": \"@id\"\n    },\n    \"workerType\": {\n      \"@id\": \"workday:worker_type\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/workday-recruiting/refs/heads/main/json-ld/workday-recruiting-rest-api-context.jsonld
tags:
- HCM
- Human Resources
- Recruiting
- SaaS
- Talent Acquisition
- JSON-LD
- Linked Data
- Semantic Web
---
