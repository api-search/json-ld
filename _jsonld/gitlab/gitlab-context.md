---
api_specs:
- filename: gitlab-api-v4-groups-openapi-original.yml
  format: yaml
  label: GitLab Groups API
  slug: apiv4groups
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/openapi/gitlab-api-v4-groups-openapi-original.yml
- filename: gitlab-api-v4-projects-openapi-original.yml
  format: yaml
  label: GitLab Projects API
  slug: apiv4projects
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/openapi/gitlab-api-v4-projects-openapi-original.yml
- filename: gitlab-api-v4-admin-openapi-original.yml
  format: yaml
  label: GitLab Admin API
  slug: apiv4admin
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/openapi/gitlab-api-v4-admin-openapi-original.yml
- filename: gitlab-api-v4-applications-openapi-original.yml
  format: yaml
  label: GitLab Applications API
  slug: apiv4applications
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/openapi/gitlab-api-v4-applications-openapi-original.yml
- filename: gitlab-api-v4-avatar-openapi-original.yml
  format: yaml
  label: GitLab Avatar API
  slug: apiv4avatar
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/openapi/gitlab-api-v4-avatar-openapi-original.yml
- filename: gitlab-api-v4-broadcast-messages-openapi-original.yml
  format: yaml
  label: GitLab Broadcast Messages API
  slug: apiv4broadcast-messages
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/openapi/gitlab-api-v4-broadcast-messages-openapi-original.yml
- filename: gitlab-api-v4-bulk-imports-openapi-original.yml
  format: yaml
  label: GitLab Bulk Imports API
  slug: apiv4bulk-imports
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/openapi/gitlab-api-v4-bulk-imports-openapi-original.yml
- filename: gitlab-api-v4-application-openapi-original.yml
  format: yaml
  label: GitLab Application Settings API
  slug: apiv4application
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/openapi/gitlab-api-v4-application-openapi-original.yml
- filename: gitlab-api-v4-metadata-openapi-original.yml
  format: yaml
  label: GitLab Metadata API
  slug: apiv4metadata
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/openapi/gitlab-api-v4-metadata-openapi-original.yml
- filename: gitlab-api-v4-version-openapi-original.yml
  format: yaml
  label: GitLab Version API
  slug: apiv4version
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/openapi/gitlab-api-v4-version-openapi-original.yml
- filename: gitlab-openapi-original.yml
  format: yaml
  label: GitLab REST API
  slug: gitlab-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/openapi/gitlab-openapi-original.yml
- filename: gitlab-oauth2-openapi.yml
  format: yaml
  label: GitLab OAuth 2.0 API
  slug: gitlab-oauth2-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/openapi/gitlab-oauth2-openapi.yml
- filename: gitlab-webhooks-openapi.yml
  format: yaml
  label: GitLab Webhooks
  slug: gitlab-webhooks
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/openapi/gitlab-webhooks-openapi.yml
class_count: 38
classes:
- API_Entities_AccessRequester
- API_Entities_Appearance
- API_Entities_ApplicationWithSecret
- API_Entities_Avatar
- API_Entities_Badge
- API_Entities_BasicBadgeDetails
- API_Entities_BatchedBackgroundMigration
- API_Entities_Branch
- API_Entities_BroadcastMessage
- API_Entities_BulkImport
- API_Entities_BulkImports
- API_Entities_Ci_Variable
- API_Entities_Cluster
- API_Entities_Commit
- API_Entities_CustomAttribute
- API_Entities_Dictionary_Table
- API_Entities_Job
- API_Entities_Metadata
- API_Entities_MetricImage
- API_Entities_PlanLimit
- API_Entities_Platform_Kubernetes
- API_Entities_ProjectIdentity
- API_Entities_Provider_Gcp
- API_Entities_UserBasic
- DeviceAuthorizationRequest
- DeviceAuthorizationResponse
- GitLab Issue
- GitLab Merge Request
- GitLab Pipeline
- GitLab Project
- RevokeTokenRequest
- TokenInfo
- TokenRequest
- TokenResponse
- UserInfo
- Webhook
- WebhookEvent
- WebhookInput
context_file: json-ld/gitlab-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/json-ld/gitlab-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Gitlab from GitLab.
layout: jsonld
name: Gitlab Context
namespaces:
- prefix: gl
  uri: https://docs.gitlab.com/api/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: access_token
  type: string
- container: ''
  name: active
  type: string
- container: ''
  name: alert_status
  type: string
- container: ''
  name: allow_failure
  type: boolean
- container: ''
  name: api_url
  type: string
- container: ''
  name: application
  type: reference
- container: ''
  name: application_id
  type: string
- container: ''
  name: application_name
  type: string
- container: ''
  name: archived
  type: boolean
- container: set
  name: artifacts
  type: string
- container: set
  name: assignees
  type: string
- container: ''
  name: author
  type: string
- container: ''
  name: author_email
  type: string
- container: ''
  name: author_name
  type: string
- container: ''
  name: authored_date
  type: dateTime
- container: ''
  name: authorization_type
  type: string
- container: ''
  name: avatar_path
  type: string
- container: ''
  name: avatar_url
  type: string
- container: ''
  name: before_sha
  type: string
- container: ''
  name: branch_filter_strategy
  type: string
- container: ''
  name: broadcast_type
  type: string
- container: ''
  name: builds_access_level
  type: string
- container: ''
  name: bulk_import_id
  type: string
- container: ''
  name: ca_cert
  type: string
- container: ''
  name: callback_url
  type: string
- container: ''
  name: can_push
  type: boolean
- container: ''
  name: changes_count
  type: string
- container: ''
  name: ci_active_jobs
  type: string
- container: ''
  name: ci_config_path
  type: string
- container: ''
  name: ci_needs_size_limit
  type: string
- container: ''
  name: ci_pipeline_schedules
  type: string
- container: ''
  name: ci_pipeline_size
  type: string
- container: ''
  name: ci_project_subscriptions
  type: string
- container: ''
  name: ci_registered_group_runners
  type: string
- container: ''
  name: ci_registered_project_runners
  type: string
- container: ''
  name: client_id
  type: string
- container: ''
  name: client_secret
  type: string
- container: ''
  name: closed_at
  type: dateTime
- container: ''
  name: closed_by
  type: string
- container: ''
  name: cluster_id
  type: string
- container: ''
  name: cluster_type
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: code_verifier
  type: string
- container: ''
  name: color
  type: string
- container: ''
  name: commit
  type: string
- container: ''
  name: committed_at
  type: dateTime
- container: ''
  name: committed_date
  type: dateTime
- container: ''
  name: committer_email
  type: string
- container: ''
  name: committer_name
  type: string
- container: ''
  name: conan_max_file_size
  type: string
- container: ''
  name: confidential
  type: boolean
- container: ''
  name: confidential_issues_events
  type: boolean
- container: ''
  name: confidential_note_events
  type: boolean
- container: ''
  name: container_registry_access_level
  type: string
- container: ''
  name: coverage
  type: string
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: creator_id
  type: integer
- container: set
  name: custom_attributes
  type: string
- container: ''
  name: default
  type: boolean
- container: ''
  name: default_branch
  type: string
- container: ''
  name: deployment_events
  type: boolean
- container: ''
  name: description
  type: string
- container: ''
  name: destination_full_path
  type: string
- container: ''
  name: destination_name
  type: string
- container: ''
  name: destination_namespace
  type: string
- container: ''
  name: destination_slug
  type: string
- container: ''
  name: detailed_merge_status
  type: string
- container: ''
  name: developers_can_merge
  type: boolean
- container: ''
  name: developers_can_push
  type: boolean
- container: ''
  name: device_code
  type: string
- container: ''
  name: disabled_until
  type: dateTime
- container: ''
  name: dismissable
  type: string
- container: ''
  name: domain
  type: string
- container: ''
  name: downvotes
  type: integer
- container: ''
  name: draft
  type: boolean
- container: ''
  name: due_date
  type: string
- container: ''
  name: duration
  type: integer
- container: ''
  name: email
  type: string
- container: ''
  name: email_header_and_footer_enabled
  type: string
- container: ''
  name: email_verified
  type: boolean
- container: ''
  name: empty_repo
  type: boolean
- container: ''
  name: enable_ssl_verification
  type: boolean
- container: ''
  name: enabled
  type: string
- container: ''
  name: endpoint
  type: string
- container: ''
  name: ends_at
  type: string
- container: ''
  name: enforcement_limit
  type: string
- container: ''
  name: enterprise
  type: boolean
- container: ''
  name: entity_type
  type: string
- container: ''
  name: environment_scope
  type: string
- container: ''
  name: erased_at
  type: dateTime
- container: ''
  name: execution_duration
  type: decimal
- container: ''
  name: expires_in
  type: integer
- container: ''
  name: expires_in_seconds
  type: integer
- container: set
  name: failures
  type: string
- container: ''
  name: favicon
  type: string
- container: set
  name: feature_categories
  type: string
- container: ''
  name: file_path
  type: string
- container: ''
  name: filename
  type: string
- container: ''
  name: finished_at
  type: dateTime
- container: ''
  name: font
  type: string
- container: ''
  name: footer_message
  type: string
- container: ''
  name: forks_count
  type: integer
- container: ''
  name: gcp_project_id
  type: string
- container: ''
  name: generic_packages_max_file_size
  type: string
- container: ''
  name: grant_type
  type: string
- container: set
  name: groups
  type: string
- container: ''
  name: has_tasks
  type: boolean
- container: ''
  name: header_logo
  type: string
- container: ''
  name: header_message
  type: string
- container: ''
  name: helm_max_file_size
  type: string
- container: ''
  name: http_url_to_repo
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: iid
  type: integer
- container: ''
  name: image_url
  type: string
- container: ''
  name: interval
  type: integer
- container: ''
  name: issue_type
  type: string
- container: ''
  name: issues_access_level
  type: string
- container: ''
  name: issues_events
  type: boolean
- container: ''
  name: job_class_name
  type: string
- container: ''
  name: job_events
  type: boolean
- container: ''
  name: kas
  type: reference
- container: ''
  name: key
  type: string
- container: ''
  name: kind
  type: string
- container: set
  name: labels
  type: string
- container: ''
  name: last_activity_at
  type: dateTime
- container: ''
  name: limits_history
  type: reference
- container: ''
  name: link_url
  type: string
- container: ''
  name: logo
  type: string
- container: ''
  name: machine_type
  type: string
- container: ''
  name: managed
  type: string
- container: ''
  name: management_project
  type: string
- container: ''
  name: masked
  type: boolean
- container: ''
  name: maven_max_file_size
  type: string
- container: ''
  name: member_events
  type: boolean
- container: ''
  name: merge_commit_sha
  type: string
- container: ''
  name: merge_requests_access_level
  type: string
- container: ''
  name: merge_requests_count
  type: integer
- container: ''
  name: merge_requests_events
  type: boolean
- container: ''
  name: merge_user
  type: string
- container: ''
  name: merged
  type: boolean
- container: ''
  name: merged_at
  type: dateTime
- container: ''
  name: message
  type: string
- container: ''
  name: message_background_color
  type: string
- container: ''
  name: message_font_color
  type: string
- container: ''
  name: migrate_projects
  type: boolean
- container: ''
  name: milestone
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: name_with_namespace
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: namespace_id
  type: string
- container: ''
  name: namespace_per_environment
  type: string
- container: ''
  name: new_project_guidelines
  type: string
- container: ''
  name: nickname
  type: string
- container: ''
  name: note_events
  type: boolean
- container: ''
  name: notification_limit
  type: string
- container: ''
  name: npm_max_file_size
  type: string
- container: ''
  name: nuget_max_file_size
  type: string
- container: ''
  name: num_nodes
  type: string
- container: ''
  name: open_issues_count
  type: integer
- container: ''
  name: owner
  type: string
- container: ''
  name: pages_access_level
  type: string
- container: ''
  name: parent_id
  type: string
- container: set
  name: parent_ids
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: path_with_namespace
  type: string
- container: ''
  name: permissions
  type: string
- container: ''
  name: picture
  type: reference
- container: ''
  name: pipeline_events
  type: boolean
- container: ''
  name: pipeline_hierarchy_size
  type: string
- container: ''
  name: platform_kubernetes
  type: string
- container: ''
  name: platform_type
  type: string
- container: ''
  name: prepared_at
  type: dateTime
- container: ''
  name: profile
  type: reference
- container: ''
  name: profile_image_guidelines
  type: string
- container: ''
  name: progress
  type: string
- container: ''
  name: project
  type: reference
- container: ''
  name: project_id
  type: string
- container: ''
  name: protected
  type: boolean
- container: ''
  name: provider_gcp
  type: string
- container: ''
  name: provider_type
  type: string
- container: ''
  name: push_events
  type: boolean
- container: ''
  name: push_events_branch_filter
  type: string
- container: ''
  name: pwa_description
  type: string
- container: ''
  name: pwa_icon
  type: string
- container: ''
  name: pwa_name
  type: string
- container: ''
  name: pwa_short_name
  type: string
- container: ''
  name: pypi_max_file_size
  type: string
- container: ''
  name: queued_duration
  type: decimal
- container: ''
  name: raw
  type: boolean
- container: ''
  name: readme_url
  type: reference
- container: ''
  name: redirect_uri
  type: reference
- container: ''
  name: ref
  type: string
- container: ''
  name: references
  type: string
- container: ''
  name: refresh_token
  type: string
- container: ''
  name: releases_events
  type: boolean
- container: ''
  name: rendered_image_url
  type: string
- container: ''
  name: rendered_link_url
  type: string
- container: ''
  name: request_data
  type: string
- container: ''
  name: request_headers
  type: reference
- container: ''
  name: requested_at
  type: string
- container: ''
  name: resource_owner_id
  type: integer
- container: ''
  name: response_body
  type: string
- container: ''
  name: response_headers
  type: reference
- container: ''
  name: response_status
  type: string
- container: set
  name: reviewers
  type: string
- container: ''
  name: revision
  type: string
- container: ''
  name: scope
  type: string
- container: ''
  name: secret
  type: string
- container: ''
  name: secret_token
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: sha
  type: string
- container: ''
  name: short_id
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: source_branch
  type: string
- container: ''
  name: source_full_path
  type: string
- container: ''
  name: source_project_id
  type: integer
- container: ''
  name: source_type
  type: string
- container: ''
  name: squash
  type: boolean
- container: ''
  name: squash_commit_sha
  type: string
- container: ''
  name: ssh_url_to_repo
  type: string
- container: ''
  name: stage
  type: string
- container: ''
  name: star_count
  type: integer
- container: ''
  name: started_at
  type: dateTime
- container: ''
  name: starts_at
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: statistics
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: status_name
  type: string
- container: ''
  name: storage_size_limit
  type: string
- container: ''
  name: sub
  type: string
- container: ''
  name: table_name
  type: string
- container: ''
  name: tag
  type: boolean
- container: ''
  name: tag_push_events
  type: boolean
- container: ''
  name: target_access_levels
  type: string
- container: ''
  name: target_branch
  type: string
- container: ''
  name: target_path
  type: string
- container: ''
  name: target_project_id
  type: integer
- container: ''
  name: task_completion_status
  type: string
- container: ''
  name: terraform_module_max_file_size
  type: string
- container: ''
  name: time_stats
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: token
  type: string
- container: ''
  name: token_type
  type: string
- container: set
  name: topics
  type: string
- container: ''
  name: trailers
  type: reference
- container: ''
  name: trigger
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: upvotes
  type: integer
- container: ''
  name: url
  type: string
- container: ''
  name: url_text
  type: string
- container: ''
  name: user
  type: string
- container: ''
  name: user_code
  type: string
- container: ''
  name: user_notes_count
  type: integer
- container: ''
  name: username
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: variable_type
  type: string
- container: ''
  name: verification_uri
  type: reference
- container: ''
  name: verification_uri_complete
  type: reference
- container: ''
  name: version
  type: string
- container: ''
  name: visibility
  type: string
- container: ''
  name: web_url
  type: string
- container: ''
  name: weight
  type: integer
- container: ''
  name: wiki_access_level
  type: string
- container: ''
  name: wiki_page_events
  type: boolean
- container: ''
  name: yaml_errors
  type: string
- container: ''
  name: zone
  type: string
property_count: 268
provider_name: GitLab
provider_slug: gitlab
slug: gitlab-context
source_filename: gitlab-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"gl\": \"https://docs.gitlab.com/api/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"API_Entities_AccessRequester\": \"gl:API_Entities_AccessRequester\",\n    \"API_Entities_Appearance\": \"gl:API_Entities_Appearance\",\n    \"API_Entities_ApplicationWithSecret\": \"gl:API_Entities_ApplicationWithSecret\",\n    \"API_Entities_Avatar\": \"gl:API_Entities_Avatar\",\n    \"API_Entities_Badge\": \"gl:API_Entities_Badge\",\n    \"API_Entities_BasicBadgeDetails\": \"gl:API_Entities_BasicBadgeDetails\",\n    \"API_Entities_BatchedBackgroundMigration\": \"gl:API_Entities_BatchedBackgroundMigration\",\n    \"API_Entities_Branch\": \"gl:API_Entities_Branch\",\n    \"API_Entities_BroadcastMessage\": \"gl:API_Entities_BroadcastMessage\",\n    \"API_Entities_BulkImport\": \"gl:API_Entities_BulkImport\",\n    \"API_Entities_BulkImports\": \"gl:API_Entities_BulkImports\",\n\
  \    \"API_Entities_Ci_Variable\": \"gl:API_Entities_Ci_Variable\",\n    \"API_Entities_Cluster\": \"gl:API_Entities_Cluster\",\n    \"API_Entities_Commit\": \"gl:API_Entities_Commit\",\n    \"API_Entities_CustomAttribute\": \"gl:API_Entities_CustomAttribute\",\n    \"API_Entities_Dictionary_Table\": \"gl:API_Entities_Dictionary_Table\",\n    \"API_Entities_Job\": \"gl:API_Entities_Job\",\n    \"API_Entities_Metadata\": \"gl:API_Entities_Metadata\",\n    \"API_Entities_MetricImage\": \"gl:API_Entities_MetricImage\",\n    \"API_Entities_PlanLimit\": \"gl:API_Entities_PlanLimit\",\n    \"API_Entities_Platform_Kubernetes\": \"gl:API_Entities_Platform_Kubernetes\",\n    \"API_Entities_ProjectIdentity\": \"gl:API_Entities_ProjectIdentity\",\n    \"API_Entities_Provider_Gcp\": \"gl:API_Entities_Provider_Gcp\",\n    \"API_Entities_UserBasic\": \"gl:API_Entities_UserBasic\",\n    \"DeviceAuthorizationRequest\": \"gl:DeviceAuthorizationRequest\",\n    \"DeviceAuthorizationResponse\": \"gl:DeviceAuthorizationResponse\"\
  ,\n    \"GitLab Issue\": \"gl:GitLab Issue\",\n    \"GitLab Merge Request\": \"gl:GitLab Merge Request\",\n    \"GitLab Pipeline\": \"gl:GitLab Pipeline\",\n    \"GitLab Project\": \"gl:GitLab Project\",\n    \"RevokeTokenRequest\": \"gl:RevokeTokenRequest\",\n    \"TokenInfo\": \"gl:TokenInfo\",\n    \"TokenRequest\": \"gl:TokenRequest\",\n    \"TokenResponse\": \"gl:TokenResponse\",\n    \"UserInfo\": \"gl:UserInfo\",\n    \"Webhook\": \"gl:Webhook\",\n    \"WebhookEvent\": \"gl:WebhookEvent\",\n    \"WebhookInput\": \"gl:WebhookInput\",\n    \"access_token\": {\n      \"@id\": \"gl:access_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active\": {\n      \"@id\": \"gl:active\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alert_status\": {\n      \"@id\": \"gl:alert_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allow_failure\": {\n      \"@id\": \"gl:allow_failure\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"api_url\": {\n      \"@id\": \"gl:api_url\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"application\": {\n      \"@id\": \"gl:application\",\n      \"@type\": \"@id\"\n    },\n    \"application_id\": {\n      \"@id\": \"gl:application_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application_name\": {\n      \"@id\": \"gl:application_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"archived\": {\n      \"@id\": \"gl:archived\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"artifacts\": {\n      \"@id\": \"gl:artifacts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assignees\": {\n      \"@id\": \"gl:assignees\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"author\": {\n      \"@id\": \"gl:author\",\n      \"@type\": \"xsd:string\"\n    },\n    \"author_email\": {\n      \"@id\": \"gl:author_email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"author_name\": {\n      \"@id\": \"gl:author_name\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"authored_date\": {\n      \"@id\": \"gl:authored_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"authorization_type\": {\n      \"@id\": \"gl:authorization_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"avatar_path\": {\n      \"@id\": \"gl:avatar_path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"avatar_url\": {\n      \"@id\": \"gl:avatar_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"before_sha\": {\n      \"@id\": \"gl:before_sha\",\n      \"@type\": \"xsd:string\"\n    },\n    \"branch_filter_strategy\": {\n      \"@id\": \"gl:branch_filter_strategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"broadcast_type\": {\n      \"@id\": \"gl:broadcast_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"builds_access_level\": {\n      \"@id\": \"gl:builds_access_level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bulk_import_id\": {\n      \"@id\": \"gl:bulk_import_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ca_cert\"\
  : {\n      \"@id\": \"gl:ca_cert\",\n      \"@type\": \"xsd:string\"\n    },\n    \"callback_url\": {\n      \"@id\": \"gl:callback_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"can_push\": {\n      \"@id\": \"gl:can_push\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"changes_count\": {\n      \"@id\": \"gl:changes_count\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ci_active_jobs\": {\n      \"@id\": \"gl:ci_active_jobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ci_config_path\": {\n      \"@id\": \"gl:ci_config_path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ci_needs_size_limit\": {\n      \"@id\": \"gl:ci_needs_size_limit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ci_pipeline_schedules\": {\n      \"@id\": \"gl:ci_pipeline_schedules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ci_pipeline_size\": {\n      \"@id\": \"gl:ci_pipeline_size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ci_project_subscriptions\": {\n      \"@id\": \"\
  gl:ci_project_subscriptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ci_registered_group_runners\": {\n      \"@id\": \"gl:ci_registered_group_runners\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ci_registered_project_runners\": {\n      \"@id\": \"gl:ci_registered_project_runners\",\n      \"@type\": \"xsd:string\"\n    },\n    \"client_id\": {\n      \"@id\": \"gl:client_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"client_secret\": {\n      \"@id\": \"gl:client_secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"closed_at\": {\n      \"@id\": \"gl:closed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"closed_by\": {\n      \"@id\": \"gl:closed_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cluster_id\": {\n      \"@id\": \"gl:cluster_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cluster_type\": {\n      \"@id\": \"gl:cluster_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"gl:code\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"code_verifier\": {\n      \"@id\": \"gl:code_verifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"color\": {\n      \"@id\": \"gl:color\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commit\": {\n      \"@id\": \"gl:commit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"committed_at\": {\n      \"@id\": \"gl:committed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"committed_date\": {\n      \"@id\": \"gl:committed_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"committer_email\": {\n      \"@id\": \"gl:committer_email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"committer_name\": {\n      \"@id\": \"gl:committer_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"conan_max_file_size\": {\n      \"@id\": \"gl:conan_max_file_size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"confidential\": {\n      \"@id\": \"gl:confidential\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"confidential_issues_events\": {\n\
  \      \"@id\": \"gl:confidential_issues_events\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"confidential_note_events\": {\n      \"@id\": \"gl:confidential_note_events\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"container_registry_access_level\": {\n      \"@id\": \"gl:container_registry_access_level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coverage\": {\n      \"@id\": \"gl:coverage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created_at\": {\n      \"@id\": \"gl:created_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"creator_id\": {\n      \"@id\": \"gl:creator_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"custom_attributes\": {\n      \"@id\": \"gl:custom_attributes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"default\": {\n      \"@id\": \"gl:default\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"default_branch\": {\n      \"@id\": \"gl:default_branch\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"deployment_events\": {\n      \"@id\": \"gl:deployment_events\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination_full_path\": {\n      \"@id\": \"gl:destination_full_path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination_name\": {\n      \"@id\": \"gl:destination_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination_namespace\": {\n      \"@id\": \"gl:destination_namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination_slug\": {\n      \"@id\": \"gl:destination_slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detailed_merge_status\": {\n      \"@id\": \"gl:detailed_merge_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"developers_can_merge\": {\n      \"@id\": \"gl:developers_can_merge\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"developers_can_push\": {\n      \"@id\": \"gl:developers_can_push\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"device_code\": {\n      \"@id\": \"gl:device_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disabled_until\": {\n      \"@id\": \"gl:disabled_until\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dismissable\": {\n      \"@id\": \"gl:dismissable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain\": {\n      \"@id\": \"gl:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downvotes\": {\n      \"@id\": \"gl:downvotes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"draft\": {\n      \"@id\": \"gl:draft\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"due_date\": {\n      \"@id\": \"gl:due_date\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"gl:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email_header_and_footer_enabled\": {\n      \"@id\": \"gl:email_header_and_footer_enabled\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"email_verified\": {\n      \"@id\": \"gl:email_verified\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"empty_repo\": {\n      \"@id\": \"gl:empty_repo\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enable_ssl_verification\": {\n      \"@id\": \"gl:enable_ssl_verification\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enabled\": {\n      \"@id\": \"gl:enabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpoint\": {\n      \"@id\": \"gl:endpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ends_at\": {\n      \"@id\": \"gl:ends_at\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enforcement_limit\": {\n      \"@id\": \"gl:enforcement_limit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enterprise\": {\n      \"@id\": \"gl:enterprise\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"entity_type\": {\n      \"@id\": \"gl:entity_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environment_scope\":\
  \ {\n      \"@id\": \"gl:environment_scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"erased_at\": {\n      \"@id\": \"gl:erased_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"execution_duration\": {\n      \"@id\": \"gl:execution_duration\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"expires_in\": {\n      \"@id\": \"gl:expires_in\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"expires_in_seconds\": {\n      \"@id\": \"gl:expires_in_seconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"failures\": {\n      \"@id\": \"gl:failures\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"favicon\": {\n      \"@id\": \"gl:favicon\",\n      \"@type\": \"xsd:string\"\n    },\n    \"feature_categories\": {\n      \"@id\": \"gl:feature_categories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"file_path\": {\n      \"@id\": \"gl:file_path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filename\"\
  : {\n      \"@id\": \"gl:filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"finished_at\": {\n      \"@id\": \"gl:finished_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"font\": {\n      \"@id\": \"gl:font\",\n      \"@type\": \"xsd:string\"\n    },\n    \"footer_message\": {\n      \"@id\": \"gl:footer_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"forks_count\": {\n      \"@id\": \"gl:forks_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"gcp_project_id\": {\n      \"@id\": \"gl:gcp_project_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generic_packages_max_file_size\": {\n      \"@id\": \"gl:generic_packages_max_file_size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grant_type\": {\n      \"@id\": \"gl:grant_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groups\": {\n      \"@id\": \"gl:groups\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"has_tasks\": {\n      \"@id\": \"gl:has_tasks\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"header_logo\": {\n      \"@id\": \"gl:header_logo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"header_message\": {\n      \"@id\": \"gl:header_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"helm_max_file_size\": {\n      \"@id\": \"gl:helm_max_file_size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"http_url_to_repo\": {\n      \"@id\": \"gl:http_url_to_repo\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"gl:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iid\": {\n      \"@id\": \"gl:iid\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"image_url\": {\n      \"@id\": \"gl:image_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interval\": {\n      \"@id\": \"gl:interval\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"issue_type\": {\n      \"@id\": \"gl:issue_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issues_access_level\": {\n      \"@id\": \"gl:issues_access_level\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"issues_events\": {\n      \"@id\": \"gl:issues_events\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"job_class_name\": {\n      \"@id\": \"gl:job_class_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"job_events\": {\n      \"@id\": \"gl:job_events\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"kas\": {\n      \"@id\": \"gl:kas\",\n      \"@type\": \"@id\"\n    },\n    \"key\": {\n      \"@id\": \"gl:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kind\": {\n      \"@id\": \"gl:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labels\": {\n      \"@id\": \"gl:labels\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last_activity_at\": {\n      \"@id\": \"gl:last_activity_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"limits_history\": {\n      \"@id\": \"gl:limits_history\",\n      \"@type\": \"@id\"\n    },\n    \"link_url\": {\n      \"@id\": \"gl:link_url\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"logo\": {\n      \"@id\": \"gl:logo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"machine_type\": {\n      \"@id\": \"gl:machine_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"managed\": {\n      \"@id\": \"gl:managed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"management_project\": {\n      \"@id\": \"gl:management_project\",\n      \"@type\": \"xsd:string\"\n    },\n    \"masked\": {\n      \"@id\": \"gl:masked\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"maven_max_file_size\": {\n      \"@id\": \"gl:maven_max_file_size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"member_events\": {\n      \"@id\": \"gl:member_events\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"merge_commit_sha\": {\n      \"@id\": \"gl:merge_commit_sha\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merge_requests_access_level\": {\n      \"@id\": \"gl:merge_requests_access_level\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"merge_requests_count\": {\n      \"@id\": \"gl:merge_requests_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"merge_requests_events\": {\n      \"@id\": \"gl:merge_requests_events\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"merge_user\": {\n      \"@id\": \"gl:merge_user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merged\": {\n      \"@id\": \"gl:merged\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"merged_at\": {\n      \"@id\": \"gl:merged_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"message\": {\n      \"@id\": \"gl:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message_background_color\": {\n      \"@id\": \"gl:message_background_color\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message_font_color\": {\n      \"@id\": \"gl:message_font_color\",\n      \"@type\": \"xsd:string\"\n    },\n    \"migrate_projects\": {\n      \"@id\": \"gl:migrate_projects\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"milestone\": {\n\
  \      \"@id\": \"gl:milestone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name_with_namespace\": {\n      \"@id\": \"gl:name_with_namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"gl:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace_id\": {\n      \"@id\": \"gl:namespace_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace_per_environment\": {\n      \"@id\": \"gl:namespace_per_environment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"new_project_guidelines\": {\n      \"@id\": \"gl:new_project_guidelines\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nickname\": {\n      \"@id\": \"gl:nickname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"note_events\": {\n      \"@id\": \"gl:note_events\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"notification_limit\": {\n      \"@id\": \"gl:notification_limit\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"npm_max_file_size\": {\n      \"@id\": \"gl:npm_max_file_size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nuget_max_file_size\": {\n      \"@id\": \"gl:nuget_max_file_size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"num_nodes\": {\n      \"@id\": \"gl:num_nodes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"open_issues_count\": {\n      \"@id\": \"gl:open_issues_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"owner\": {\n      \"@id\": \"gl:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pages_access_level\": {\n      \"@id\": \"gl:pages_access_level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parent_id\": {\n      \"@id\": \"gl:parent_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parent_ids\": {\n      \"@id\": \"gl:parent_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"gl:password\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"path\": {\n      \"@id\": \"gl:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path_with_namespace\": {\n      \"@id\": \"gl:path_with_namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"permissions\": {\n      \"@id\": \"gl:permissions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"picture\": {\n      \"@id\": \"gl:picture\",\n      \"@type\": \"@id\"\n    },\n    \"pipeline_events\": {\n      \"@id\": \"gl:pipeline_events\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"pipeline_hierarchy_size\": {\n      \"@id\": \"gl:pipeline_hierarchy_size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform_kubernetes\": {\n      \"@id\": \"gl:platform_kubernetes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform_type\": {\n      \"@id\": \"gl:platform_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prepared_at\": {\n      \"@id\": \"gl:prepared_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"profile\": {\n      \"@id\": \"gl:profile\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"profile_image_guidelines\": {\n      \"@id\": \"gl:profile_image_guidelines\",\n      \"@type\": \"xsd:string\"\n    },\n    \"progress\": {\n      \"@id\": \"gl:progress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"project\": {\n      \"@id\": \"gl:project\",\n      \"@type\": \"@id\"\n    },\n    \"project_id\": {\n      \"@id\": \"gl:project_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protected\": {\n      \"@id\": \"gl:protected\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"provider_gcp\": {\n      \"@id\": \"gl:provider_gcp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider_type\": {\n      \"@id\": \"gl:provider_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"push_events\": {\n      \"@id\": \"gl:push_events\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"push_events_branch_filter\": {\n      \"@id\": \"gl:push_events_branch_filter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pwa_description\"\
  : {\n      \"@id\": \"gl:pwa_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pwa_icon\": {\n      \"@id\": \"gl:pwa_icon\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pwa_name\": {\n      \"@id\": \"gl:pwa_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pwa_short_name\": {\n      \"@id\": \"gl:pwa_short_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pypi_max_file_size\": {\n      \"@id\": \"gl:pypi_max_file_size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queued_duration\": {\n      \"@id\": \"gl:queued_duration\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"raw\": {\n      \"@id\": \"gl:raw\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"readme_url\": {\n      \"@id\": \"gl:readme_url\",\n      \"@type\": \"@id\"\n    },\n    \"redirect_uri\": {\n      \"@id\": \"gl:redirect_uri\",\n      \"@type\": \"@id\"\n    },\n    \"ref\": {\n      \"@id\": \"gl:ref\",\n      \"@type\": \"xsd:string\"\n    },\n    \"references\": {\n      \"@id\"\
  : \"gl:references\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refresh_token\": {\n      \"@id\": \"gl:refresh_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"releases_events\": {\n      \"@id\": \"gl:releases_events\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"rendered_image_url\": {\n      \"@id\": \"gl:rendered_image_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rendered_link_url\": {\n      \"@id\": \"gl:rendered_link_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"request_data\": {\n      \"@id\": \"gl:request_data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"request_headers\": {\n      \"@id\": \"gl:request_headers\",\n      \"@type\": \"@id\"\n    },\n    \"requested_at\": {\n      \"@id\": \"gl:requested_at\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resource_owner_id\": {\n      \"@id\": \"gl:resource_owner_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"response_body\": {\n      \"@id\": \"gl:response_body\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"response_headers\": {\n      \"@id\": \"gl:response_headers\",\n      \"@type\": \"@id\"\n    },\n    \"response_status\": {\n      \"@id\": \"gl:response_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reviewers\": {\n      \"@id\": \"gl:reviewers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revision\": {\n      \"@id\": \"gl:revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scope\": {\n      \"@id\": \"gl:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secret\": {\n      \"@id\": \"gl:secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secret_token\": {\n      \"@id\": \"gl:secret_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"gl:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sha\": {\n      \"@id\": \"gl:sha\",\n      \"@type\": \"xsd:string\"\n    },\n    \"short_id\": {\n      \"@id\": \"gl:short_id\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"gl:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source_branch\": {\n      \"@id\": \"gl:source_branch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source_full_path\": {\n      \"@id\": \"gl:source_full_path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source_project_id\": {\n      \"@id\": \"gl:source_project_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"source_type\": {\n      \"@id\": \"gl:source_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"squash\": {\n      \"@id\": \"gl:squash\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"squash_commit_sha\": {\n      \"@id\": \"gl:squash_commit_sha\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ssh_url_to_repo\": {\n      \"@id\": \"gl:ssh_url_to_repo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stage\": {\n      \"@id\": \"gl:stage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"star_count\": {\n      \"@id\": \"gl:star_count\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"started_at\": {\n      \"@id\": \"gl:started_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"starts_at\": {\n      \"@id\": \"gl:starts_at\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"gl:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statistics\": {\n      \"@id\": \"gl:statistics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"gl:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status_name\": {\n      \"@id\": \"gl:status_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storage_size_limit\": {\n      \"@id\": \"gl:storage_size_limit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sub\": {\n      \"@id\": \"gl:sub\",\n      \"@type\": \"xsd:string\"\n    },\n    \"table_name\": {\n      \"@id\": \"gl:table_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tag\": {\n      \"@id\": \"gl:tag\",\n      \"@type\": \"xsd:boolean\"\n\
  \    },\n    \"tag_push_events\": {\n      \"@id\": \"gl:tag_push_events\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"target_access_levels\": {\n      \"@id\": \"gl:target_access_levels\",\n      \"@type\": \"xsd:string\"\n    },\n    \"target_branch\": {\n      \"@id\": \"gl:target_branch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"target_path\": {\n      \"@id\": \"gl:target_path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"target_project_id\": {\n      \"@id\": \"gl:target_project_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"task_completion_status\": {\n      \"@id\": \"gl:task_completion_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terraform_module_max_file_size\": {\n      \"@id\": \"gl:terraform_module_max_file_size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"time_stats\": {\n      \"@id\": \"gl:time_stats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"gl:title\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"token\": {\n      \"@id\": \"gl:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token_type\": {\n      \"@id\": \"gl:token_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topics\": {\n      \"@id\": \"gl:topics\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trailers\": {\n      \"@id\": \"gl:trailers\",\n      \"@type\": \"@id\"\n    },\n    \"trigger\": {\n      \"@id\": \"gl:trigger\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"gl:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updated_at\": {\n      \"@id\": \"gl:updated_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"upvotes\": {\n      \"@id\": \"gl:upvotes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url_text\": {\n      \"@id\": \"gl:url_text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user\": {\n      \"@id\":\
  \ \"gl:user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user_code\": {\n      \"@id\": \"gl:user_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user_notes_count\": {\n      \"@id\": \"gl:user_notes_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"username\": {\n      \"@id\": \"gl:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"gl:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variable_type\": {\n      \"@id\": \"gl:variable_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verification_uri\": {\n      \"@id\": \"gl:verification_uri\",\n      \"@type\": \"@id\"\n    },\n    \"verification_uri_complete\": {\n      \"@id\": \"gl:verification_uri_complete\",\n      \"@type\": \"@id\"\n    },\n    \"version\": {\n      \"@id\": \"gl:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"visibility\": {\n      \"@id\": \"gl:visibility\",\n      \"@type\": \"xsd:string\"\n    },\n    \"web_url\": {\n      \"\
  @id\": \"gl:web_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"gl:weight\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"wiki_access_level\": {\n      \"@id\": \"gl:wiki_access_level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wiki_page_events\": {\n      \"@id\": \"gl:wiki_page_events\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"yaml_errors\": {\n      \"@id\": \"gl:yaml_errors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zone\": {\n      \"@id\": \"gl:zone\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/json-ld/gitlab-context.jsonld
tags:
- Code
- Platform
- Software Development
- Source Control
- JSON-LD
- Linked Data
- Semantic Web
---
