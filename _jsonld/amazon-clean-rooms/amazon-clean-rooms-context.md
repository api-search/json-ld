---
api_specs:
- filename: amazon-clean-rooms-openapi.yml
  format: yaml
  label: Amazon Clean Rooms API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-clean-rooms/refs/heads/main/openapi/amazon-clean-rooms-openapi.yml
class_count: 19
classes:
- Collaboration
- name
- description
- Membership
- ProtectedQuery
- ConfiguredTable
- ListCollaborationsResponse
- CreateCollaborationRequest
- CreateCollaborationResponse
- GetCollaborationResponse
- ListMembershipsResponse
- CreateMembershipRequest
- CreateMembershipResponse
- ListProtectedQueriesResponse
- StartProtectedQueryRequest
- StartProtectedQueryResponse
- ListConfiguredTablesResponse
- CreateConfiguredTableRequest
- CreateConfiguredTableResponse
context_file: json-ld/amazon-clean-rooms-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-clean-rooms/refs/heads/main/json-ld/amazon-clean-rooms-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Clean Rooms from Amazon Clean Rooms.
layout: jsonld
name: Amazon Clean Rooms Context
namespaces:
- prefix: cleanrooms
  uri: https://aws.amazon.com/clean-rooms/schema/
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
  name: arn
  type: string
- container: ''
  name: creatorAccountId
  type: string
- container: ''
  name: creatorDisplayName
  type: string
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: updateTime
  type: dateTime
- container: ''
  name: queryLogStatus
  type: string
- container: ''
  name: collaborationArn
  type: string
- container: ''
  name: collaborationId
  type: string
- container: ''
  name: collaborationCreatorAccountId
  type: string
- container: ''
  name: collaborationName
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: membershipId
  type: string
- container: ''
  name: membershipArn
  type: string
- container: ''
  name: analysisMethod
  type: string
- container: ''
  name: nextToken
  type: string
- container: set
  name: collaborationList
  type: string
- container: set
  name: members
  type: string
- container: set
  name: creatorMemberAbilities
  type: string
- container: ''
  name: collaboration
  type: string
- container: set
  name: membershipList
  type: string
- container: ''
  name: collaborationIdentifier
  type: string
- container: ''
  name: membership
  type: string
- container: set
  name: protectedQueries
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: sqlParameters
  type: string
- container: ''
  name: resultConfiguration
  type: string
- container: ''
  name: protectedQuery
  type: string
- container: set
  name: configuredTableList
  type: string
- container: ''
  name: tableReference
  type: string
- container: set
  name: allowedColumns
  type: string
- container: ''
  name: configuredTable
  type: string
property_count: 32
provider_name: Amazon Clean Rooms
provider_slug: amazon-clean-rooms
slug: amazon-clean-rooms-context
source_filename: amazon-clean-rooms-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cleanrooms\": \"https://aws.amazon.com/clean-rooms/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Collaboration\": \"cleanrooms:Collaboration\",\n    \"id\": {\n      \"@id\": \"cleanrooms:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"cleanrooms:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"creatorAccountId\": {\n      \"@id\": \"cleanrooms:creator_account_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creatorDisplayName\": {\n      \"@id\": \"cleanrooms:creator_display_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createTime\": {\n      \"@id\": \"cleanrooms:create_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updateTime\": {\n      \"@id\": \"cleanrooms:update_time\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"queryLogStatus\": {\n      \"@id\": \"cleanrooms:query_log_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Membership\": \"cleanrooms:Membership\",\n    \"collaborationArn\": {\n      \"@id\": \"cleanrooms:collaboration_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"collaborationId\": {\n      \"@id\": \"cleanrooms:collaboration_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"collaborationCreatorAccountId\": {\n      \"@id\": \"cleanrooms:collaboration_creator_account_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"collaborationName\": {\n      \"@id\": \"cleanrooms:collaboration_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"cleanrooms:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProtectedQuery\": \"cleanrooms:ProtectedQuery\",\n    \"membershipId\": {\n      \"@id\": \"cleanrooms:membership_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"membershipArn\"\
  : {\n      \"@id\": \"cleanrooms:membership_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConfiguredTable\": \"cleanrooms:ConfiguredTable\",\n    \"analysisMethod\": {\n      \"@id\": \"cleanrooms:analysis_method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListCollaborationsResponse\": \"cleanrooms:ListCollaborationsResponse\",\n    \"nextToken\": {\n      \"@id\": \"cleanrooms:next_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"collaborationList\": {\n      \"@id\": \"cleanrooms:collaboration_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateCollaborationRequest\": \"cleanrooms:CreateCollaborationRequest\",\n    \"members\": {\n      \"@id\": \"cleanrooms:members\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creatorMemberAbilities\": {\n      \"@id\": \"cleanrooms:creator_member_abilities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateCollaborationResponse\"\
  : \"cleanrooms:CreateCollaborationResponse\",\n    \"collaboration\": {\n      \"@id\": \"cleanrooms:collaboration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetCollaborationResponse\": \"cleanrooms:GetCollaborationResponse\",\n    \"ListMembershipsResponse\": \"cleanrooms:ListMembershipsResponse\",\n    \"membershipList\": {\n      \"@id\": \"cleanrooms:membership_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateMembershipRequest\": \"cleanrooms:CreateMembershipRequest\",\n    \"collaborationIdentifier\": {\n      \"@id\": \"cleanrooms:collaboration_identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateMembershipResponse\": \"cleanrooms:CreateMembershipResponse\",\n    \"membership\": {\n      \"@id\": \"cleanrooms:membership\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListProtectedQueriesResponse\": \"cleanrooms:ListProtectedQueriesResponse\",\n    \"protectedQueries\": {\n      \"@id\": \"cleanrooms:protected_queries\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartProtectedQueryRequest\": \"cleanrooms:StartProtectedQueryRequest\",\n    \"type\": {\n      \"@id\": \"cleanrooms:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sqlParameters\": {\n      \"@id\": \"cleanrooms:sql_parameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultConfiguration\": {\n      \"@id\": \"cleanrooms:result_configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartProtectedQueryResponse\": \"cleanrooms:StartProtectedQueryResponse\",\n    \"protectedQuery\": {\n      \"@id\": \"cleanrooms:protected_query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListConfiguredTablesResponse\": \"cleanrooms:ListConfiguredTablesResponse\",\n    \"configuredTableList\": {\n      \"@id\": \"cleanrooms:configured_table_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateConfiguredTableRequest\": \"cleanrooms:CreateConfiguredTableRequest\"\
  ,\n    \"tableReference\": {\n      \"@id\": \"cleanrooms:table_reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowedColumns\": {\n      \"@id\": \"cleanrooms:allowed_columns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateConfiguredTableResponse\": \"cleanrooms:CreateConfiguredTableResponse\",\n    \"configuredTable\": {\n      \"@id\": \"cleanrooms:configured_table\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-clean-rooms/refs/heads/main/json-ld/amazon-clean-rooms-context.jsonld
tags:
- AWS
- Clean Rooms
- Data Collaboration
- Privacy
- Analytics
- Marketing
- JSON-LD
- Linked Data
- Semantic Web
---
