---
class_count: 0
classes: []
context_file: json-ld/indeed-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/indeed/refs/heads/main/json-ld/indeed-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Indeed from Indeed.
layout: jsonld
name: Indeed Context
namespaces:
- prefix: indeed
  uri: https://docs.indeed.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Employer
  type: ''
- container: ''
  name: Candidate
  type: ''
- container: ''
  name: JobPosting
  type: ''
- container: ''
  name: Resume
  type: ''
- container: ''
  name: WorkExperience
  type: ''
- container: ''
  name: Education
  type: ''
- container: ''
  name: Salary
  type: ''
- container: ''
  name: Benefit
  type: ''
- container: ''
  name: Qualification
  type: ''
- container: ''
  name: JobLocation
  type: ''
- container: ''
  name: ScreenerQuestion
  type: ''
- container: ''
  name: ScreenerQuestionResponse
  type: ''
- container: ''
  name: DispositionUpdate
  type: ''
- container: ''
  name: EmployerRegistration
  type: ''
property_count: 14
provider_name: Indeed
provider_slug: indeed
slug: indeed-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"indeed\": \"https://docs.indeed.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Employer\": {\n      \"@id\": \"indeed:Employer\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"employerName\": \"schema:name\",\n        \"employerType\": \"indeed:employerType\",\n        \"websiteUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"phoneNumber\": \"schema:telephone\",\n        \"address\": \"schema:address\",\n        \"countrySpecificAttributes\": {\n          \"@id\": \"indeed:countrySpecificAttributes\",\n          \"@container\": \"@set\"\n        },\n        \"localeSpecificAttributes\": {\n          \"@id\": \"indeed:localeSpecificAttributes\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\"\
  : \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Candidate\": {\n      \"@id\": \"indeed:Candidate\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"phoneNumber\": \"schema:telephone\",\n        \"location\": \"schema:homeLocation\",\n        \"resume\": \"indeed:resume\",\n        \"coverLetter\": \"indeed:coverLetter\",\n        \"applicationStatus\": \"indeed:applicationStatus\",\n        \"screenerQuestionResponses\": {\n          \"@id\": \"indeed:screenerQuestionResponses\",\n          \"@container\": \"@set\"\n        },\n        \"eeoResponses\": \"indeed:eeoResponses\",\n        \"appliedAt\": {\n          \"@id\": \"schema:dateCreated\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"source\": \"indeed:applicationSource\",\n        \"jobPostingId\": {\n          \"@id\": \"indeed:jobPostingId\",\n          \"@type\": \"@id\"\n        },\n        \"jobTitle\": \"schema:jobTitle\",\n        \"employerId\": {\n          \"@id\": \"indeed:employerId\",\n          \"@type\": \"@id\"\n        },\n        \"acknowledged\": \"indeed:isAcknowledged\",\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"JobPosting\": {\n      \"@id\": \"schema:JobPosting\",\n      \"@context\": {\n        \"jobPostingId\": \"schema:identifier\",\n        \"title\": \"schema:title\",\n        \"description\": \"schema:description\",\n        \"location\": \"schema:jobLocation\",\n        \"salary\": \"schema:baseSalary\",\n        \"benefits\": {\n          \"@id\": \"schema:jobBenefits\",\n          \"@container\": \"@set\"\n        },\n\
  \        \"qualifications\": {\n          \"@id\": \"schema:qualifications\",\n          \"@container\": \"@set\"\n        },\n        \"workingHours\": \"schema:workHours\",\n        \"employmentType\": \"schema:employmentType\",\n        \"remoteWorkPolicy\": \"indeed:remoteWorkPolicy\",\n        \"employer\": {\n          \"@id\": \"schema:hiringOrganization\",\n          \"@type\": \"@id\"\n        },\n        \"source\": \"indeed:jobSource\",\n        \"indeedApply\": \"indeed:indeedApplyConfig\",\n        \"status\": \"indeed:jobPostingStatus\",\n        \"applicationUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expiresAt\": {\n          \"@id\": \"schema:validThrough\",\n          \"@type\": \"\
  xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Resume\": {\n      \"@id\": \"indeed:Resume\",\n      \"@context\": {\n        \"file\": \"indeed:resumeFile\",\n        \"text\": \"schema:text\",\n        \"html\": \"indeed:htmlContent\",\n        \"json\": \"indeed:structuredContent\",\n        \"workExperience\": {\n          \"@id\": \"indeed:workExperience\",\n          \"@container\": \"@set\"\n        },\n        \"education\": {\n          \"@id\": \"indeed:education\",\n          \"@container\": \"@set\"\n        },\n        \"skills\": {\n          \"@id\": \"schema:skills\",\n          \"@container\": \"@set\"\n        },\n        \"certifications\": {\n          \"@id\": \"indeed:certifications\",\n          \"@container\": \"@set\"\n        },\n        \"summary\": \"schema:abstract\"\n      }\n    },\n\n    \"WorkExperience\": {\n      \"@id\": \"indeed:WorkExperience\",\n      \"@context\": {\n        \"title\": \"schema:jobTitle\",\n        \"company\": \"schema:worksFor\"\
  ,\n        \"location\": \"schema:location\",\n        \"startDate\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"endDate\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"current\": \"indeed:isCurrent\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"Education\": {\n      \"@id\": \"indeed:Education\",\n      \"@context\": {\n        \"institution\": \"schema:educationalCredentialAwarded\",\n        \"degree\": \"schema:credentialCategory\",\n        \"fieldOfStudy\": \"indeed:fieldOfStudy\",\n        \"startDate\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"endDate\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"location\": \"schema:location\"\n      }\n    },\n\n    \"Salary\": {\n      \"@id\": \"schema:MonetaryAmount\",\n      \"@context\"\
  : {\n        \"minimumAmount\": \"schema:minValue\",\n        \"maximumAmount\": \"schema:maxValue\",\n        \"currency\": \"schema:currency\",\n        \"period\": \"schema:unitText\"\n      }\n    },\n\n    \"Benefit\": {\n      \"@id\": \"indeed:Benefit\",\n      \"@context\": {\n        \"type\": \"indeed:benefitType\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"Qualification\": {\n      \"@id\": \"indeed:Qualification\",\n      \"@context\": {\n        \"type\": \"indeed:qualificationType\",\n        \"description\": \"schema:description\",\n        \"required\": \"indeed:isRequired\"\n      }\n    },\n\n    \"JobLocation\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"streetAddress\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"postalCode\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\",\n        \"formattedAddress\"\
  : \"schema:address\"\n      }\n    },\n\n    \"ScreenerQuestion\": {\n      \"@id\": \"indeed:ScreenerQuestion\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"question\": \"schema:text\",\n        \"type\": \"indeed:questionType\",\n        \"required\": \"indeed:isRequired\",\n        \"options\": {\n          \"@id\": \"indeed:options\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"ScreenerQuestionResponse\": {\n      \"@id\": \"indeed:ScreenerQuestionResponse\",\n      \"@context\": {\n        \"questionId\": \"schema:identifier\",\n        \"question\": \"schema:text\",\n        \"answer\": \"schema:acceptedAnswer\"\n      }\n    },\n\n    \"DispositionUpdate\": {\n      \"@id\": \"indeed:DispositionUpdate\",\n      \"@context\": {\n        \"applicationId\": \"schema:identifier\",\n        \"status\": \"indeed:dispositionStatus\",\n        \"statusUpdatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        },\n        \"rejectionReason\": \"indeed:rejectionReason\"\n      }\n    },\n\n    \"EmployerRegistration\": {\n      \"@id\": \"indeed:EmployerRegistration\",\n      \"@context\": {\n        \"employerId\": \"schema:identifier\",\n        \"registrationStatus\": \"indeed:registrationStatus\",\n        \"features\": {\n          \"@id\": \"indeed:enabledFeatures\",\n          \"@container\": \"@set\"\n        },\n        \"registeredAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/indeed/refs/heads/main/json-ld/indeed-context.jsonld
tags:
- Careers
- Employment
- Hiring
- Job Search
- Jobs
- Recruiting
- JSON-LD
- Linked Data
- Semantic Web
---
