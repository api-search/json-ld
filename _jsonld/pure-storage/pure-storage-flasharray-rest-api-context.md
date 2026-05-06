---
api_specs:
- filename: flasharray-rest-api-openapi.yml
  format: yaml
  label: FlashArray REST API
  slug: flasharray-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pure-storage/refs/heads/main/openapi/flasharray-rest-api-openapi.yml
- filename: flashblade-rest-api-openapi.yml
  format: yaml
  label: FlashBlade REST API
  slug: flashblade-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pure-storage/refs/heads/main/openapi/flashblade-rest-api-openapi.yml
- filename: pure1-cloud-api-openapi.yml
  format: yaml
  label: Pure1 Public REST API
  slug: pure1-cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pure-storage/refs/heads/main/openapi/pure1-cloud-api-openapi.yml
class_count: 11
classes:
- Alert
- ApiClient
- Directory
- HostGroup
- Host
- NetworkInterface
- Pod
- Policy
- ProtectionGroup
- Volume
- VolumeSnapshot
context_file: json-ld/pure-storage-flasharray-rest-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/pure-storage/refs/heads/main/json-ld/pure-storage-flasharray-rest-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Pure Storage Flasharray Rest Api from Pure Storage.
layout: jsonld
name: Pure Storage Flasharray Rest Api Context
namespaces:
- prefix: pure
  uri: https://code.purestorage.com/schema/
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
  name: name
  type: ''
- container: ''
  name: context
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: actual
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: closed
  type: integer
- container: ''
  name: code
  type: integer
- container: ''
  name: componentName
  type: string
- container: ''
  name: componentType
  type: string
- container: ''
  name: created
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: duration
  type: integer
- container: ''
  name: expected
  type: string
- container: ''
  name: flagged
  type: boolean
- container: ''
  name: issue
  type: string
- container: ''
  name: knowledgeBaseUrl
  type: string
- container: ''
  name: notified
  type: integer
- container: ''
  name: severity
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: updated
  type: integer
- container: set
  name: accessPolicies
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: accessTokenTtlInMs
  type: integer
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: issuer
  type: string
- container: ''
  name: keyId
  type: string
- container: ''
  name: maxRole
  type: string
- container: ''
  name: publicKey
  type: string
- container: ''
  name: destroyed
  type: boolean
- container: ''
  name: directoryName
  type: string
- container: ''
  name: fileSystem
  type: string
- container: ''
  name: limitedBy
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: space
  type: string
- container: ''
  name: timeRemaining
  type: integer
- container: ''
  name: workload
  type: reference
- container: ''
  name: configuration
  type: string
- container: ''
  name: connectionCount
  type: integer
- container: ''
  name: hostCount
  type: integer
- container: ''
  name: isLocal
  type: boolean
- container: ''
  name: qos
  type: string
- container: ''
  name: chap
  type: reference
- container: ''
  name: hostPassword
  type: string
- container: ''
  name: hostUser
  type: string
- container: ''
  name: targetPassword
  type: string
- container: ''
  name: targetUser
  type: string
- container: ''
  name: hostGroup
  type: string
- container: set
  name: iqns
  type: string
- container: set
  name: nqns
  type: string
- container: ''
  name: nvmeStretch
  type: string
- container: ''
  name: personality
  type: string
- container: ''
  name: portConnectivity
  type: reference
- container: ''
  name: details
  type: string
- container: ''
  name: status
  type: string
- container: set
  name: preferredArrays
  type: string
- container: ''
  name: vlan
  type: string
- container: set
  name: wwns
  type: string
- container: ''
  name: server
  type: string
- container: set
  name: attachedServers
  type: string
- container: ''
  name: eth
  type: reference
- container: ''
  name: address
  type: string
- container: ''
  name: gateway
  type: string
- container: ''
  name: macAddress
  type: string
- container: ''
  name: mtu
  type: integer
- container: ''
  name: netmask
  type: string
- container: set
  name: subinterfaces
  type: string
- container: ''
  name: subnet
  type: string
- container: ''
  name: subtype
  type: string
- container: ''
  name: fc
  type: reference
- container: ''
  name: wwn
  type: string
- container: ''
  name: interfaceType
  type: string
- container: set
  name: services
  type: string
- container: ''
  name: speed
  type: integer
- container: ''
  name: arrayCount
  type: integer
- container: set
  name: arrays
  type: string
- container: ''
  name: eradicationConfig
  type: string
- container: set
  name: failoverPreferences
  type: string
- container: ''
  name: footprint
  type: integer
- container: ''
  name: linkSourceCount
  type: integer
- container: ''
  name: linkTargetCount
  type: integer
- container: ''
  name: mediator
  type: string
- container: ''
  name: mediatorVersion
  type: string
- container: set
  name: members
  type: string
- container: ''
  name: promotionStatus
  type: string
- container: ''
  name: quotaLimit
  type: string
- container: ''
  name: requestedPromotionState
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: policyType
  type: string
- container: ''
  name: pod
  type: string
- container: ''
  name: manualEradication
  type: string
- container: ''
  name: hostGroupCount
  type: integer
- container: ''
  name: replicationSchedule
  type: string
- container: ''
  name: retentionLock
  type: string
- container: ''
  name: snapshotSchedule
  type: string
- container: ''
  name: sourceRetention
  type: string
- container: ''
  name: targetCount
  type: integer
- container: ''
  name: targetRetention
  type: string
- container: ''
  name: volumeCount
  type: integer
- container: ''
  name: hostEncryptionKeyStatus
  type: string
- container: ''
  name: priorityAdjustment
  type: string
- container: ''
  name: provisioned
  type: integer
- container: ''
  name: serial
  type: string
- container: ''
  name: priority
  type: integer
- container: ''
  name: protocolEndpoint
  type: string
- container: ''
  name: volumeGroup
  type: string
- container: ''
  name: suffix
  type: string
property_count: 108
provider_name: Pure Storage
provider_slug: pure-storage
slug: pure-storage-flasharray-rest-api-context
source_filename: pure-storage-flasharray-rest-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pure\": \"https://code.purestorage.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Alert\": \"pure:Alert\",\n    \"ApiClient\": \"pure:ApiClient\",\n    \"Directory\": \"pure:Directory\",\n    \"HostGroup\": \"pure:HostGroup\",\n    \"Host\": \"pure:Host\",\n    \"NetworkInterface\": \"pure:NetworkInterface\",\n    \"Pod\": \"pure:Pod\",\n    \"Policy\": \"pure:Policy\",\n    \"ProtectionGroup\": \"pure:ProtectionGroup\",\n    \"Volume\": \"pure:Volume\",\n    \"VolumeSnapshot\": \"pure:VolumeSnapshot\",\n    \"id\": {\n      \"@id\": \"pure:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"context\": {\n      \"@id\": \"pure:context\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"pure:action\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"actual\": {\n      \"@id\": \"pure:actual\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"pure:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"closed\": {\n      \"@id\": \"pure:closed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"code\": {\n      \"@id\": \"pure:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"componentName\": {\n      \"@id\": \"pure:component_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentType\": {\n      \"@id\": \"pure:component_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"schema:dateCreated\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"duration\": {\n      \"@id\": \"pure:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"expected\": {\n      \"@id\": \"pure:expected\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flagged\": {\n      \"@id\": \"pure:flagged\",\n\
  \      \"@type\": \"xsd:boolean\"\n    },\n    \"issue\": {\n      \"@id\": \"pure:issue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"knowledgeBaseUrl\": {\n      \"@id\": \"pure:knowledge_base_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notified\": {\n      \"@id\": \"pure:notified\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"severity\": {\n      \"@id\": \"pure:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"pure:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"pure:summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updated\": {\n      \"@id\": \"pure:updated\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"accessPolicies\": {\n      \"@id\": \"pure:access_policies\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"pure:resource_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessTokenTtlInMs\"\
  : {\n      \"@id\": \"pure:access_token_ttl_in_ms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"enabled\": {\n      \"@id\": \"pure:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"issuer\": {\n      \"@id\": \"pure:issuer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyId\": {\n      \"@id\": \"pure:key_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxRole\": {\n      \"@id\": \"pure:max_role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publicKey\": {\n      \"@id\": \"pure:public_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destroyed\": {\n      \"@id\": \"pure:destroyed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"directoryName\": {\n      \"@id\": \"pure:directory_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileSystem\": {\n      \"@id\": \"pure:file_system\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limitedBy\": {\n      \"@id\": \"pure:limited_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n\
  \      \"@id\": \"pure:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"space\": {\n      \"@id\": \"pure:space\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeRemaining\": {\n      \"@id\": \"pure:time_remaining\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"workload\": {\n      \"@id\": \"pure:workload\",\n      \"@type\": \"@id\"\n    },\n    \"configuration\": {\n      \"@id\": \"pure:configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionCount\": {\n      \"@id\": \"pure:connection_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hostCount\": {\n      \"@id\": \"pure:host_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isLocal\": {\n      \"@id\": \"pure:is_local\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"qos\": {\n      \"@id\": \"pure:qos\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chap\": {\n      \"@id\": \"pure:chap\",\n      \"@type\": \"@id\"\n    },\n    \"hostPassword\": {\n      \"@id\": \"pure:host_password\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"hostUser\": {\n      \"@id\": \"pure:host_user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetPassword\": {\n      \"@id\": \"pure:target_password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetUser\": {\n      \"@id\": \"pure:target_user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostGroup\": {\n      \"@id\": \"pure:host_group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iqns\": {\n      \"@id\": \"pure:iqns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nqns\": {\n      \"@id\": \"pure:nqns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nvmeStretch\": {\n      \"@id\": \"pure:nvme_stretch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"personality\": {\n      \"@id\": \"pure:personality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portConnectivity\": {\n      \"@id\": \"pure:port_connectivity\",\n      \"@type\": \"@id\"\
  \n    },\n    \"details\": {\n      \"@id\": \"pure:details\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pure:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preferredArrays\": {\n      \"@id\": \"pure:preferred_arrays\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vlan\": {\n      \"@id\": \"pure:vlan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wwns\": {\n      \"@id\": \"pure:wwns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"server\": {\n      \"@id\": \"pure:server\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachedServers\": {\n      \"@id\": \"pure:attached_servers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eth\": {\n      \"@id\": \"pure:eth\",\n      \"@type\": \"@id\"\n    },\n    \"address\": {\n      \"@id\": \"pure:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gateway\": {\n      \"@id\"\
  : \"pure:gateway\",\n      \"@type\": \"xsd:string\"\n    },\n    \"macAddress\": {\n      \"@id\": \"pure:mac_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mtu\": {\n      \"@id\": \"pure:mtu\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"netmask\": {\n      \"@id\": \"pure:netmask\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subinterfaces\": {\n      \"@id\": \"pure:subinterfaces\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnet\": {\n      \"@id\": \"pure:subnet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subtype\": {\n      \"@id\": \"pure:subtype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fc\": {\n      \"@id\": \"pure:fc\",\n      \"@type\": \"@id\"\n    },\n    \"wwn\": {\n      \"@id\": \"pure:wwn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interfaceType\": {\n      \"@id\": \"pure:interface_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"services\": {\n      \"@id\": \"pure:services\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"speed\": {\n      \"@id\": \"pure:speed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"arrayCount\": {\n      \"@id\": \"pure:array_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"arrays\": {\n      \"@id\": \"pure:arrays\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eradicationConfig\": {\n      \"@id\": \"pure:eradication_config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failoverPreferences\": {\n      \"@id\": \"pure:failover_preferences\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"footprint\": {\n      \"@id\": \"pure:footprint\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"linkSourceCount\": {\n      \"@id\": \"pure:link_source_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"linkTargetCount\": {\n      \"@id\": \"pure:link_target_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"\
  mediator\": {\n      \"@id\": \"pure:mediator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mediatorVersion\": {\n      \"@id\": \"pure:mediator_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"members\": {\n      \"@id\": \"pure:members\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"promotionStatus\": {\n      \"@id\": \"pure:promotion_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quotaLimit\": {\n      \"@id\": \"pure:quota_limit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedPromotionState\": {\n      \"@id\": \"pure:requested_promotion_state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"pure:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyType\": {\n      \"@id\": \"pure:policy_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pod\": {\n      \"@id\": \"pure:pod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manualEradication\": {\n      \"@id\"\
  : \"pure:manual_eradication\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostGroupCount\": {\n      \"@id\": \"pure:host_group_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"replicationSchedule\": {\n      \"@id\": \"pure:replication_schedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retentionLock\": {\n      \"@id\": \"pure:retention_lock\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshotSchedule\": {\n      \"@id\": \"pure:snapshot_schedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceRetention\": {\n      \"@id\": \"pure:source_retention\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetCount\": {\n      \"@id\": \"pure:target_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"targetRetention\": {\n      \"@id\": \"pure:target_retention\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeCount\": {\n      \"@id\": \"pure:volume_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hostEncryptionKeyStatus\": {\n  \
  \    \"@id\": \"pure:host_encryption_key_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priorityAdjustment\": {\n      \"@id\": \"pure:priority_adjustment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provisioned\": {\n      \"@id\": \"pure:provisioned\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"serial\": {\n      \"@id\": \"pure:serial\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"pure:priority\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"protocolEndpoint\": {\n      \"@id\": \"pure:protocol_endpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeGroup\": {\n      \"@id\": \"pure:volume_group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suffix\": {\n      \"@id\": \"pure:suffix\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/pure-storage/refs/heads/main/json-ld/pure-storage-flasharray-rest-api-context.jsonld
tags:
- Storage
- Data Storage
- Flash Storage
- Enterprise Storage
- Cloud Storage
- Object Storage
- File Storage
- Block Storage
- Kubernetes Storage
- Infrastructure
- JSON-LD
- Linked Data
- Semantic Web
---
