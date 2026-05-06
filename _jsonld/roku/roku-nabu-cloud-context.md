---
api_specs:
- filename: roku-external-control-protocol.yaml
  format: yaml
  label: Roku External Control Protocol (ECP)
  slug: external-control-protocol
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/openapi/roku-external-control-protocol.yaml
- filename: roku-pay-web-services.yaml
  format: yaml
  label: Roku Pay Web Services
  slug: pay
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/openapi/roku-pay-web-services.yaml
- filename: roku-nabu-cloud.yaml
  format: yaml
  label: Roku Nabu Cloud
  slug: nabu-cloud
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/openapi/roku-nabu-cloud.yaml
class_count: 39
classes:
- AgentStreamOption
- Body_serviceaccounts-login_token
- BuildOut
- DeviceCreate
- DeviceHistoryOut
- DeviceInstanceInfo
- DeviceOut
- DeviceStart
- DeviceUpdate
- GroupAddMember
- GroupCreate
- GroupMemberOut
- GroupOut
- GroupRoleOut
- GroupUpdate
- IceServer
- OIDCTokenResponseModel
- OrganisationMemberOut
- OrganisationOut
- OrganisationRegionOut
- OrganisationRoleOut
- PersonalAccessTokenCreate
- PersonalAccessTokenCreated
- PersonalAccessTokenOut
- PersonalAccessTokenRefresh
- ProjectCreate
- ProjectGroupAdd
- ProjectGroupOut
- ProjectGroupUpdate
- ProjectMemberAdd
- ProjectMemberOut
- ProjectOut
- ProjectRoleOut
- ProjectUpdate
- ScopeOut
- SnapshotCreate
- SnapshotOut
- SnapshotUpdate
- UserOut
context_file: json-ld/roku-nabu-cloud-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/json-ld/roku-nabu-cloud-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Roku Nabu Cloud from Roku.
layout: jsonld
name: Roku Nabu Cloud Context
namespaces:
- prefix: roku
  uri: https://developer.roku.com/schema/
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
  name: accountName
  type: ''
- container: ''
  name: agentActive
  type: boolean
- container: set
  name: agentStreamOptions
  type: ''
- container: ''
  name: artifactoryPath
  type: string
- container: ''
  name: asan
  type: boolean
- container: ''
  name: awsRegion
  type: ''
- container: ''
  name: billingEntity
  type: string
- container: set
  name: children
  type: integer
- container: ''
  name: clientId
  type: string
- container: ''
  name: clientSecret
  type: string
- container: ''
  name: configServerOverridesChanges
  type: ''
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: creatorId
  type: string
- container: ''
  name: creatorUsername
  type: string
- container: ''
  name: credential
  type: ''
- container: ''
  name: currentDevices
  type: integer
- container: ''
  name: currentSnapshots
  type: integer
- container: ''
  name: description
  type: ''
- container: ''
  name: deviceType
  type: ''
- container: ''
  name: email
  type: ''
- container: ''
  name: endedAt
  type: ''
- container: ''
  name: esn
  type: string
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: expiresIn
  type: integer
- container: ''
  name: expiresInDays
  type: integer
- container: ''
  name: fullName
  type: ''
- container: ''
  name: fullVersion
  type: ''
- container: ''
  name: grantType
  type: string
- container: ''
  name: groupId
  type: integer
- container: ''
  name: groupName
  type: string
- container: ''
  name: groupRoleId
  type: integer
- container: ''
  name: groupRoleName
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: idpId
  type: ''
- container: ''
  name: instanceApiUrl
  type: ''
- container: ''
  name: instanceId
  type: integer
- container: ''
  name: instanceUuid
  type: string
- container: ''
  name: ipAddress
  type: ''
- container: ''
  name: janusIceServers
  type: ''
- container: ''
  name: janusId
  type: ''
- container: ''
  name: janusPin
  type: ''
- container: ''
  name: janusToken
  type: ''
- container: ''
  name: janusWebsocketUrl
  type: ''
- container: ''
  name: lastSnapshot
  type: integer
- container: ''
  name: lastSnapshotName
  type: string
- container: ''
  name: lastUsedAt
  type: ''
- container: ''
  name: maxDevices
  type: integer
- container: ''
  name: maxProjectDevices
  type: integer
- container: ''
  name: maxProjectRuntime
  type: integer
- container: ''
  name: maxProjectSnapshots
  type: integer
- container: ''
  name: maxRuntime
  type: integer
- container: ''
  name: maxSnapshots
  type: integer
- container: ''
  name: name
  type: ''
- container: ''
  name: organisationId
  type: integer
- container: ''
  name: organisationRoleId
  type: integer
- container: ''
  name: organisationRoleName
  type: string
- container: ''
  name: overrideIsAsan
  type: ''
- container: ''
  name: parentId
  type: ''
- container: set
  name: permissions
  type: string
- container: ''
  name: private
  type: boolean
- container: ''
  name: projectRoleId
  type: integer
- container: ''
  name: projectRoleName
  type: string
- container: ''
  name: properties
  type: ''
- container: ''
  name: public
  type: boolean
- container: ''
  name: qaHub
  type: boolean
- container: ''
  name: ready
  type: boolean
- container: ''
  name: reboot
  type: integer
- container: ''
  name: refreshExpiresIn
  type: integer
- container: ''
  name: refreshToken
  type: ''
- container: ''
  name: regionId
  type: integer
- container: ''
  name: regionName
  type: string
- container: ''
  name: revokedAt
  type: ''
- container: ''
  name: rootfsArtifactoryPath
  type: string
- container: ''
  name: runningDevice
  type: ''
- container: ''
  name: runtime
  type: integer
- container: ''
  name: scope
  type: string
- container: set
  name: scopes
  type: string
- container: ''
  name: slug
  type: string
- container: ''
  name: snapshotId
  type: integer
- container: ''
  name: snapshotName
  type: string
- container: set
  name: snapshots
  type: integer
- container: ''
  name: source
  type: ''
- container: ''
  name: startedAt
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: streamOptionId
  type: integer
- container: ''
  name: streamOptionName
  type: string
- container: ''
  name: systemSettingChanges
  type: ''
- container: ''
  name: tag
  type: string
- container: ''
  name: token
  type: string
- container: ''
  name: tokenInfo
  type: ''
- container: ''
  name: tokenType
  type: string
- container: set
  name: urls
  type: string
- container: ''
  name: userId
  type: string
- container: ''
  name: userProject
  type: boolean
- container: ''
  name: username
  type: string
- container: ''
  name: version
  type: ''
property_count: 97
provider_name: Roku
provider_slug: roku
slug: roku-nabu-cloud-context
source_filename: roku-nabu-cloud-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"roku\": \"https://developer.roku.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AgentStreamOption\": \"roku:AgentStreamOption\",\n    \"Body_serviceaccounts-login_token\": \"roku:Body_serviceaccounts-login_token\",\n    \"BuildOut\": \"roku:BuildOut\",\n    \"DeviceCreate\": \"roku:DeviceCreate\",\n    \"DeviceHistoryOut\": \"roku:DeviceHistoryOut\",\n    \"DeviceInstanceInfo\": \"roku:DeviceInstanceInfo\",\n    \"DeviceOut\": \"roku:DeviceOut\",\n    \"DeviceStart\": \"roku:DeviceStart\",\n    \"DeviceUpdate\": \"roku:DeviceUpdate\",\n    \"GroupAddMember\": \"roku:GroupAddMember\",\n    \"GroupCreate\": \"roku:GroupCreate\",\n    \"GroupMemberOut\": \"roku:GroupMemberOut\",\n    \"GroupOut\": \"roku:GroupOut\",\n    \"GroupRoleOut\": \"roku:GroupRoleOut\",\n    \"GroupUpdate\": \"roku:GroupUpdate\",\n  \
  \  \"IceServer\": \"roku:IceServer\",\n    \"OIDCTokenResponseModel\": \"roku:OIDCTokenResponseModel\",\n    \"OrganisationMemberOut\": \"roku:OrganisationMemberOut\",\n    \"OrganisationOut\": \"roku:OrganisationOut\",\n    \"OrganisationRegionOut\": \"roku:OrganisationRegionOut\",\n    \"OrganisationRoleOut\": \"roku:OrganisationRoleOut\",\n    \"PersonalAccessTokenCreate\": \"roku:PersonalAccessTokenCreate\",\n    \"PersonalAccessTokenCreated\": \"roku:PersonalAccessTokenCreated\",\n    \"PersonalAccessTokenOut\": \"roku:PersonalAccessTokenOut\",\n    \"PersonalAccessTokenRefresh\": \"roku:PersonalAccessTokenRefresh\",\n    \"ProjectCreate\": \"roku:ProjectCreate\",\n    \"ProjectGroupAdd\": \"roku:ProjectGroupAdd\",\n    \"ProjectGroupOut\": \"roku:ProjectGroupOut\",\n    \"ProjectGroupUpdate\": \"roku:ProjectGroupUpdate\",\n    \"ProjectMemberAdd\": \"roku:ProjectMemberAdd\",\n    \"ProjectMemberOut\": \"roku:ProjectMemberOut\",\n    \"ProjectOut\": \"roku:ProjectOut\",\n    \"ProjectRoleOut\"\
  : \"roku:ProjectRoleOut\",\n    \"ProjectUpdate\": \"roku:ProjectUpdate\",\n    \"ScopeOut\": \"roku:ScopeOut\",\n    \"SnapshotCreate\": \"roku:SnapshotCreate\",\n    \"SnapshotOut\": \"roku:SnapshotOut\",\n    \"SnapshotUpdate\": \"roku:SnapshotUpdate\",\n    \"UserOut\": \"roku:UserOut\",\n    \"accessToken\": {\n      \"@id\": \"roku:access_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountName\": {\n      \"@id\": \"roku:account_name\"\n    },\n    \"agentActive\": {\n      \"@id\": \"roku:agent_active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"agentStreamOptions\": {\n      \"@id\": \"roku:agent_stream_options\",\n      \"@container\": \"@set\"\n    },\n    \"artifactoryPath\": {\n      \"@id\": \"roku:artifactory_path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"asan\": {\n      \"@id\": \"roku:asan\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"awsRegion\": {\n      \"@id\": \"roku:aws_region\"\n    },\n    \"billingEntity\": {\n      \"@id\":\
  \ \"roku:billing_entity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"children\": {\n      \"@id\": \"roku:children\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"clientId\": {\n      \"@id\": \"roku:client_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientSecret\": {\n      \"@id\": \"roku:client_secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configServerOverridesChanges\": {\n      \"@id\": \"roku:config_server_overrides_changes\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"creatorId\": {\n      \"@id\": \"roku:creator_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creatorUsername\": {\n      \"@id\": \"roku:creator_username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"credential\": {\n      \"@id\": \"roku:credential\"\n    },\n    \"currentDevices\": {\n      \"@id\": \"roku:current_devices\",\n      \"@type\": \"xsd:integer\"\n  \
  \  },\n    \"currentSnapshots\": {\n      \"@id\": \"roku:current_snapshots\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"deviceType\": {\n      \"@id\": \"roku:device_type\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\"\n    },\n    \"endedAt\": {\n      \"@id\": \"roku:ended_at\"\n    },\n    \"esn\": {\n      \"@id\": \"roku:esn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"roku:expires_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"expiresIn\": {\n      \"@id\": \"roku:expires_in\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"expiresInDays\": {\n      \"@id\": \"roku:expires_in_days\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fullName\": {\n      \"@id\": \"roku:full_name\"\n    },\n    \"fullVersion\": {\n      \"@id\": \"roku:full_version\"\n    },\n    \"grantType\": {\n      \"@id\": \"roku:grant_type\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"groupId\": {\n      \"@id\": \"roku:group_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"groupName\": {\n      \"@id\": \"roku:group_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupRoleId\": {\n      \"@id\": \"roku:group_role_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"groupRoleName\": {\n      \"@id\": \"roku:group_role_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"roku:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"idpId\": {\n      \"@id\": \"roku:idp_id\"\n    },\n    \"instanceApiUrl\": {\n      \"@id\": \"roku:instance_api_url\"\n    },\n    \"instanceId\": {\n      \"@id\": \"roku:instance_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"instanceUuid\": {\n      \"@id\": \"roku:instance_uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipAddress\": {\n      \"@id\": \"roku:ip_address\"\n    },\n    \"janusIceServers\": {\n      \"@id\": \"roku:janus_ice_servers\"\n    },\n  \
  \  \"janusId\": {\n      \"@id\": \"roku:janus_id\"\n    },\n    \"janusPin\": {\n      \"@id\": \"roku:janus_pin\"\n    },\n    \"janusToken\": {\n      \"@id\": \"roku:janus_token\"\n    },\n    \"janusWebsocketUrl\": {\n      \"@id\": \"roku:janus_websocket_url\"\n    },\n    \"lastSnapshot\": {\n      \"@id\": \"roku:last_snapshot\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"lastSnapshotName\": {\n      \"@id\": \"roku:last_snapshot_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUsedAt\": {\n      \"@id\": \"roku:last_used_at\"\n    },\n    \"maxDevices\": {\n      \"@id\": \"roku:max_devices\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxProjectDevices\": {\n      \"@id\": \"roku:max_project_devices\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxProjectRuntime\": {\n      \"@id\": \"roku:max_project_runtime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxProjectSnapshots\": {\n      \"@id\": \"roku:max_project_snapshots\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"maxRuntime\": {\n      \"@id\": \"roku:max_runtime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxSnapshots\": {\n      \"@id\": \"roku:max_snapshots\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"organisationId\": {\n      \"@id\": \"roku:organisation_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"organisationRoleId\": {\n      \"@id\": \"roku:organisation_role_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"organisationRoleName\": {\n      \"@id\": \"roku:organisation_role_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overrideIsAsan\": {\n      \"@id\": \"roku:override_is_asan\"\n    },\n    \"parentId\": {\n      \"@id\": \"roku:parent_id\"\n    },\n    \"permissions\": {\n      \"@id\": \"roku:permissions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"private\": {\n      \"@id\": \"roku:private\",\n      \"@type\": \"xsd:boolean\"\
  \n    },\n    \"projectRoleId\": {\n      \"@id\": \"roku:project_role_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"projectRoleName\": {\n      \"@id\": \"roku:project_role_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"roku:properties\"\n    },\n    \"public\": {\n      \"@id\": \"roku:public\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"qaHub\": {\n      \"@id\": \"roku:qa_hub\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ready\": {\n      \"@id\": \"roku:ready\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reboot\": {\n      \"@id\": \"roku:reboot\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"refreshExpiresIn\": {\n      \"@id\": \"roku:refresh_expires_in\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"refreshToken\": {\n      \"@id\": \"roku:refresh_token\"\n    },\n    \"regionId\": {\n      \"@id\": \"roku:region_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"regionName\": {\n      \"@id\": \"\
  roku:region_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revokedAt\": {\n      \"@id\": \"roku:revoked_at\"\n    },\n    \"rootfsArtifactoryPath\": {\n      \"@id\": \"roku:rootfs_artifactory_path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"runningDevice\": {\n      \"@id\": \"roku:running_device\"\n    },\n    \"runtime\": {\n      \"@id\": \"roku:runtime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"scope\": {\n      \"@id\": \"roku:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scopes\": {\n      \"@id\": \"roku:scopes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slug\": {\n      \"@id\": \"roku:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshotId\": {\n      \"@id\": \"roku:snapshot_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"snapshotName\": {\n      \"@id\": \"roku:snapshot_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshots\": {\n      \"@id\": \"roku:snapshots\",\n   \
  \   \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"source\": {\n      \"@id\": \"roku:source\"\n    },\n    \"startedAt\": {\n      \"@id\": \"roku:started_at\"\n    },\n    \"status\": {\n      \"@id\": \"roku:status\"\n    },\n    \"streamOptionId\": {\n      \"@id\": \"roku:stream_option_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"streamOptionName\": {\n      \"@id\": \"roku:stream_option_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"systemSettingChanges\": {\n      \"@id\": \"roku:system_setting_changes\"\n    },\n    \"tag\": {\n      \"@id\": \"roku:tag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token\": {\n      \"@id\": \"roku:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenInfo\": {\n      \"@id\": \"roku:token_info\"\n    },\n    \"tokenType\": {\n      \"@id\": \"roku:token_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"urls\": {\n      \"@id\": \"roku:urls\",\n      \"@container\": \"@set\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"userId\": {\n      \"@id\": \"roku:user_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userProject\": {\n      \"@id\": \"roku:user_project\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"username\": {\n      \"@id\": \"roku:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/json-ld/roku-nabu-cloud-context.jsonld
tags:
- Streaming
- Television
- Media
- Entertainment
- Connected TV
- Consumer Electronics
- JSON-LD
- Linked Data
- Semantic Web
---
