---
api_specs:
- filename: upwork-graphql-api-openapi.yml
  format: yaml
  label: Upwork GraphQL API
  slug: graphql-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/upwork/refs/heads/main/openapi/upwork-graphql-api-openapi.yml
- filename: upwork-rest-api-openapi.yml
  format: yaml
  label: Upwork REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/upwork/refs/heads/main/openapi/upwork-rest-api-openapi.yml
class_count: 24
classes:
- Budget
- Client
- Contract
- ContractListResponse
- Engagement
- EngagementListResponse
- FreelancerProfile
- FreelancerSearchResponse
- GraphQLError
- GraphQLRequest
- GraphQLResponse
- Job
- JobSearchResponse
- Message
- MessageCreate
- MessageListResponse
- OAuthToken
- Paging
- ReportResponse
- Skill
- Team
- TeamListResponse
- description
- name
context_file: json-ld/upwork-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/upwork/refs/heads/main/json-ld/upwork-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Upwork from Upwork.
layout: jsonld
name: Upwork Context
namespaces:
- prefix: upwork
  uri: https://developers.upwork.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accessToken
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: authorId
  type: string
- container: ''
  name: authorName
  type: string
- container: ''
  name: availability
  type: string
- container: ''
  name: budget
  type: string
- container: set
  name: c
  type: string
- container: ''
  name: client
  type: string
- container: ''
  name: clientId
  type: string
- container: set
  name: cols
  type: string
- container: ''
  name: column
  type: integer
- container: ''
  name: companyId
  type: string
- container: set
  name: contracts
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: country
  type: string
- container: ''
  name: createdDateTime
  type: dateTime
- container: ''
  name: currency
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: duration
  type: string
- container: ''
  name: endedTime
  type: dateTime
- container: set
  name: engagements
  type: string
- container: set
  name: errors
  type: string
- container: ''
  name: experienceLevel
  type: string
- container: ''
  name: expiresIn
  type: integer
- container: ''
  name: freelancerId
  type: string
- container: ''
  name: freelancerName
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: jobTitle
  type: string
- container: ''
  name: jobType
  type: string
- container: set
  name: jobs
  type: string
- container: ''
  name: jobsCompleted
  type: integer
- container: ''
  name: label
  type: string
- container: ''
  name: line
  type: integer
- container: set
  name: locations
  type: string
- container: ''
  name: message
  type: string
- container: set
  name: messages
  type: string
- container: ''
  name: offset
  type: integer
- container: ''
  name: operationName
  type: string
- container: ''
  name: paging
  type: string
- container: set
  name: path
  type: string
- container: ''
  name: providerId
  type: string
- container: set
  name: providers
  type: string
- container: ''
  name: query
  type: string
- container: ''
  name: rate
  type: decimal
- container: ''
  name: rating
  type: decimal
- container: ''
  name: refreshToken
  type: string
- container: ''
  name: roomId
  type: string
- container: set
  name: rows
  type: string
- container: set
  name: skills
  type: string
- container: ''
  name: startedTime
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: table
  type: string
- container: set
  name: teams
  type: string
- container: ''
  name: text
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: tokenType
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: totalSpent
  type: decimal
- container: ''
  name: type
  type: string
- container: ''
  name: uid
  type: string
- container: ''
  name: variables
  type: string
property_count: 61
provider_name: Upwork
provider_slug: upwork
slug: upwork-context
source_filename: upwork-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"upwork\": \"https://developers.upwork.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Budget\": \"upwork:Budget\",\n    \"Client\": \"upwork:Client\",\n    \"Contract\": \"upwork:Contract\",\n    \"ContractListResponse\": \"upwork:ContractListResponse\",\n    \"Engagement\": \"upwork:Engagement\",\n    \"EngagementListResponse\": \"upwork:EngagementListResponse\",\n    \"FreelancerProfile\": \"upwork:FreelancerProfile\",\n    \"FreelancerSearchResponse\": \"upwork:FreelancerSearchResponse\",\n    \"GraphQLError\": \"upwork:GraphQLError\",\n    \"GraphQLRequest\": \"upwork:GraphQLRequest\",\n    \"GraphQLResponse\": \"upwork:GraphQLResponse\",\n    \"Job\": \"upwork:Job\",\n    \"JobSearchResponse\": \"upwork:JobSearchResponse\",\n    \"Message\": \"upwork:Message\",\n    \"MessageCreate\": \"upwork:MessageCreate\"\
  ,\n    \"MessageListResponse\": \"upwork:MessageListResponse\",\n    \"OAuthToken\": \"upwork:OAuthToken\",\n    \"Paging\": \"upwork:Paging\",\n    \"ReportResponse\": \"upwork:ReportResponse\",\n    \"Skill\": \"upwork:Skill\",\n    \"Team\": \"upwork:Team\",\n    \"TeamListResponse\": \"upwork:TeamListResponse\",\n    \"accessToken\": {\n      \"@id\": \"upwork:access_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"upwork:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"authorId\": {\n      \"@id\": \"upwork:authorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorName\": {\n      \"@id\": \"upwork:authorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availability\": {\n      \"@id\": \"upwork:availability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"budget\": {\n      \"@id\": \"upwork:budget\",\n      \"@type\": \"xsd:string\"\n    },\n    \"c\": {\n      \"@id\": \"upwork:c\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"client\": {\n      \"@id\": \"upwork:client\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientId\": {\n      \"@id\": \"upwork:clientId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cols\": {\n      \"@id\": \"upwork:cols\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"column\": {\n      \"@id\": \"upwork:column\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"companyId\": {\n      \"@id\": \"upwork:company_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contracts\": {\n      \"@id\": \"upwork:contracts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"upwork:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"country\": {\n      \"@id\": \"upwork:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdDateTime\": {\n      \"@id\": \"upwork:createdDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\
  \    \"currency\": {\n      \"@id\": \"upwork:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"upwork:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"duration\": {\n      \"@id\": \"upwork:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endedTime\": {\n      \"@id\": \"upwork:endedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"engagements\": {\n      \"@id\": \"upwork:engagements\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"upwork:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"experienceLevel\": {\n      \"@id\": \"upwork:experienceLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresIn\": {\n      \"@id\": \"upwork:expires_in\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"freelancerId\": {\n      \"@id\": \"upwork:freelancerId\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"freelancerName\": {\n      \"@id\": \"upwork:freelancerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"upwork:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobTitle\": {\n      \"@id\": \"upwork:job_title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobType\": {\n      \"@id\": \"upwork:jobType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobs\": {\n      \"@id\": \"upwork:jobs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobsCompleted\": {\n      \"@id\": \"upwork:jobsCompleted\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"label\": {\n      \"@id\": \"upwork:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"line\": {\n      \"@id\": \"upwork:line\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"locations\": {\n      \"@id\": \"upwork:locations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n     \
  \ \"@id\": \"upwork:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messages\": {\n      \"@id\": \"upwork:messages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"offset\": {\n      \"@id\": \"upwork:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"operationName\": {\n      \"@id\": \"upwork:operationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paging\": {\n      \"@id\": \"upwork:paging\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"upwork:path\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"providerId\": {\n      \"@id\": \"upwork:provider_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"providers\": {\n      \"@id\": \"upwork:providers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"query\": {\n      \"@id\": \"upwork:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rate\"\
  : {\n      \"@id\": \"upwork:rate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"rating\": {\n      \"@id\": \"upwork:rating\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"refreshToken\": {\n      \"@id\": \"upwork:refresh_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roomId\": {\n      \"@id\": \"upwork:roomId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rows\": {\n      \"@id\": \"upwork:rows\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"skills\": {\n      \"@id\": \"upwork:skills\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startedTime\": {\n      \"@id\": \"upwork:startedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"upwork:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"table\": {\n      \"@id\": \"upwork:table\",\n      \"@type\": \"xsd:string\"\n    },\n    \"teams\": {\n      \"@id\": \"upwork:teams\",\n      \"@container\":\
  \ \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"upwork:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"upwork:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenType\": {\n      \"@id\": \"upwork:token_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"upwork:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalSpent\": {\n      \"@id\": \"upwork:totalSpent\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"type\": {\n      \"@id\": \"upwork:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uid\": {\n      \"@id\": \"upwork:uid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variables\": {\n      \"@id\": \"upwork:variables\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/upwork/refs/heads/main/json-ld/upwork-context.jsonld
tags:
- Freelancing
- Jobs
- Talent
- Marketplace
- Contracts
- Hiring
- JSON-LD
- Linked Data
- Semantic Web
---
