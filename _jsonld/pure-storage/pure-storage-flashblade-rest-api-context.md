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
- Array
- Bucket
- FileSystem
- FileSystemSnapshot
- NetworkInterface
- ObjectStoreAccount
- ObjectStoreUser
- ObjectStoreVirtualHost
- Policy
context_file: json-ld/pure-storage-flashblade-rest-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/pure-storage/refs/heads/main/json-ld/pure-storage-flashblade-rest-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Pure Storage Flashblade Rest Api from Pure Storage.
layout: jsonld
name: Pure Storage Flashblade Rest Api Context
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
  name: action
  type: string
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
  name: flagged
  type: boolean
- container: ''
  name: index
  type: integer
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
- container: ''
  name: variables
  type: reference
- container: set
  name: accessPolicies
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
  name: context
  type: string
- container: ''
  name: AsOf
  type: integer
- container: ''
  name: banner
  type: string
- container: ''
  name: defaultInboundTlsPolicy
  type: string
- container: ''
  name: encryption
  type: string
- container: ''
  name: eradicationConfig
  type: string
- container: ''
  name: idleTimeout
  type: integer
- container: ''
  name: networkAccessPolicy
  type: string
- container: set
  name: ntpServers
  type: string
- container: ''
  name: os
  type: string
- container: ''
  name: productType
  type: string
- container: ''
  name: revision
  type: string
- container: ''
  name: securityUpdate
  type: string
- container: ''
  name: smbMode
  type: string
- container: ''
  name: timeZone
  type: string
- container: ''
  name: version
  type: ''
- container: ''
  name: account
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: bucketType
  type: string
- container: ''
  name: destroyed
  type: boolean
- container: ''
  name: hardLimitEnabled
  type: boolean
- container: ''
  name: objectCount
  type: integer
- container: ''
  name: objectLockConfig
  type: string
- container: ''
  name: defaultRetention
  type: integer
- container: ''
  name: publicAccessConfig
  type: reference
- container: ''
  name: blockNewPublicPolicies
  type: boolean
- container: ''
  name: blockPublicAccess
  type: boolean
- container: ''
  name: publicStatus
  type: string
- container: ''
  name: qosPolicy
  type: string
- container: ''
  name: quotaLimit
  type: integer
- container: ''
  name: retentionLock
  type: string
- container: ''
  name: space
  type: string
- container: ''
  name: storageClass
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusDetails
  type: string
- container: ''
  name: tieringPolicy
  type: string
- container: ''
  name: timeRemaining
  type: integer
- container: ''
  name: timeRemainingStatus
  type: string
- container: ''
  name: versioning
  type: string
- container: set
  name: realms
  type: string
- container: ''
  name: defaultGroupQuota
  type: integer
- container: ''
  name: defaultUserQuota
  type: integer
- container: ''
  name: eradicationMode
  type: string
- container: ''
  name: manualEradication
  type: string
- container: ''
  name: fastRemoveDirectoryEnabled
  type: boolean
- container: ''
  name: groupOwnership
  type: string
- container: ''
  name: http
  type: string
- container: ''
  name: multiProtocol
  type: string
- container: ''
  name: nfs
  type: string
- container: ''
  name: nodeGroup
  type: string
- container: ''
  name: promotionStatus
  type: string
- container: ''
  name: provisioned
  type: integer
- container: ''
  name: requestedPromotionState
  type: string
- container: ''
  name: smb
  type: string
- container: ''
  name: snapshotDirectoryEnabled
  type: boolean
- container: ''
  name: source
  type: string
- container: ''
  name: workload
  type: reference
- container: ''
  name: configuration
  type: string
- container: ''
  name: writable
  type: boolean
- container: ''
  name: owner
  type: string
- container: ''
  name: ownerDestroyed
  type: boolean
- container: set
  name: policies
  type: string
- container: ''
  name: policy
  type: string
- container: ''
  name: suffix
  type: string
- container: ''
  name: address
  type: string
- container: set
  name: attachedServers
  type: string
- container: ''
  name: gateway
  type: string
- container: ''
  name: mtu
  type: integer
- container: ''
  name: netmask
  type: string
- container: set
  name: services
  type: string
- container: ''
  name: subnet
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: vlan
  type: integer
- container: ''
  name: bucketDefaults
  type: string
- container: set
  name: accessKeys
  type: string
- container: ''
  name: hostname
  type: string
- container: set
  name: rules
  type: string
property_count: 102
provider_name: Pure Storage
provider_slug: pure-storage
slug: pure-storage-flashblade-rest-api-context
source_filename: pure-storage-flashblade-rest-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pure\": \"https://code.purestorage.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Alert\": \"pure:Alert\",\n    \"ApiClient\": \"pure:ApiClient\",\n    \"Array\": \"pure:Array\",\n    \"Bucket\": \"pure:Bucket\",\n    \"FileSystem\": \"pure:FileSystem\",\n    \"FileSystemSnapshot\": \"pure:FileSystemSnapshot\",\n    \"NetworkInterface\": \"pure:NetworkInterface\",\n    \"ObjectStoreAccount\": \"pure:ObjectStoreAccount\",\n    \"ObjectStoreUser\": \"pure:ObjectStoreUser\",\n    \"ObjectStoreVirtualHost\": \"pure:ObjectStoreVirtualHost\",\n    \"Policy\": \"pure:Policy\",\n    \"id\": {\n      \"@id\": \"pure:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"action\": {\n      \"@id\": \"pure:action\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"code\": {\n      \"@id\": \"pure:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"componentName\": {\n      \"@id\": \"pure:component_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentType\": {\n      \"@id\": \"pure:component_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"schema:dateCreated\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"duration\": {\n      \"@id\": \"pure:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"flagged\": {\n      \"@id\": \"pure:flagged\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"index\": {\n      \"@id\": \"pure:index\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"knowledgeBaseUrl\": {\n      \"@id\": \"pure:knowledge_base_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notified\": {\n      \"@id\": \"pure:notified\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"severity\": {\n      \"@id\": \"pure:severity\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"pure:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"pure:summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updated\": {\n      \"@id\": \"pure:updated\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"variables\": {\n      \"@id\": \"pure:variables\",\n      \"@type\": \"@id\"\n    },\n    \"accessPolicies\": {\n      \"@id\": \"pure:access_policies\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessTokenTtlInMs\": {\n      \"@id\": \"pure:access_token_ttl_in_ms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"enabled\": {\n      \"@id\": \"pure:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"issuer\": {\n      \"@id\": \"pure:issuer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyId\": {\n      \"@id\": \"pure:key_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxRole\": {\n      \"@id\": \"pure:max_role\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"publicKey\": {\n      \"@id\": \"pure:public_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"context\": {\n      \"@id\": \"pure:context\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AsOf\": {\n      \"@id\": \"pure:_as_of\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"banner\": {\n      \"@id\": \"pure:banner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultInboundTlsPolicy\": {\n      \"@id\": \"pure:default_inbound_tls_policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryption\": {\n      \"@id\": \"pure:encryption\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eradicationConfig\": {\n      \"@id\": \"pure:eradication_config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idleTimeout\": {\n      \"@id\": \"pure:idle_timeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"networkAccessPolicy\": {\n      \"@id\": \"pure:network_access_policy\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"ntpServers\": {\n      \"@id\": \"pure:ntp_servers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"os\": {\n      \"@id\": \"pure:os\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productType\": {\n      \"@id\": \"pure:product_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revision\": {\n      \"@id\": \"pure:revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityUpdate\": {\n      \"@id\": \"pure:security_update\",\n      \"@type\": \"xsd:string\"\n    },\n    \"smbMode\": {\n      \"@id\": \"pure:smb_mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeZone\": {\n      \"@id\": \"pure:time_zone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\"\n    },\n    \"account\": {\n      \"@id\": \"pure:account\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"pure:resource_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketType\"\
  : {\n      \"@id\": \"pure:bucket_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destroyed\": {\n      \"@id\": \"pure:destroyed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"hardLimitEnabled\": {\n      \"@id\": \"pure:hard_limit_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"objectCount\": {\n      \"@id\": \"pure:object_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"objectLockConfig\": {\n      \"@id\": \"pure:object_lock_config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultRetention\": {\n      \"@id\": \"pure:default_retention\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"publicAccessConfig\": {\n      \"@id\": \"pure:public_access_config\",\n      \"@type\": \"@id\"\n    },\n    \"blockNewPublicPolicies\": {\n      \"@id\": \"pure:block_new_public_policies\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"blockPublicAccess\": {\n      \"@id\": \"pure:block_public_access\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"\
  publicStatus\": {\n      \"@id\": \"pure:public_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"qosPolicy\": {\n      \"@id\": \"pure:qos_policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quotaLimit\": {\n      \"@id\": \"pure:quota_limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"retentionLock\": {\n      \"@id\": \"pure:retention_lock\",\n      \"@type\": \"xsd:string\"\n    },\n    \"space\": {\n      \"@id\": \"pure:space\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storageClass\": {\n      \"@id\": \"pure:storage_class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pure:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusDetails\": {\n      \"@id\": \"pure:status_details\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tieringPolicy\": {\n      \"@id\": \"pure:tiering_policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeRemaining\": {\n      \"@id\": \"pure:time_remaining\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"timeRemainingStatus\": {\n      \"@id\": \"pure:time_remaining_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versioning\": {\n      \"@id\": \"pure:versioning\",\n      \"@type\": \"xsd:string\"\n    },\n    \"realms\": {\n      \"@id\": \"pure:realms\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultGroupQuota\": {\n      \"@id\": \"pure:default_group_quota\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"defaultUserQuota\": {\n      \"@id\": \"pure:default_user_quota\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"eradicationMode\": {\n      \"@id\": \"pure:eradication_mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manualEradication\": {\n      \"@id\": \"pure:manual_eradication\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fastRemoveDirectoryEnabled\": {\n      \"@id\": \"pure:fast_remove_directory_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"groupOwnership\": {\n\
  \      \"@id\": \"pure:group_ownership\",\n      \"@type\": \"xsd:string\"\n    },\n    \"http\": {\n      \"@id\": \"pure:http\",\n      \"@type\": \"xsd:string\"\n    },\n    \"multiProtocol\": {\n      \"@id\": \"pure:multi_protocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nfs\": {\n      \"@id\": \"pure:nfs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nodeGroup\": {\n      \"@id\": \"pure:node_group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"promotionStatus\": {\n      \"@id\": \"pure:promotion_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provisioned\": {\n      \"@id\": \"pure:provisioned\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"requestedPromotionState\": {\n      \"@id\": \"pure:requested_promotion_state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"smb\": {\n      \"@id\": \"pure:smb\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshotDirectoryEnabled\": {\n      \"@id\": \"pure:snapshot_directory_enabled\",\n      \"@type\"\
  : \"xsd:boolean\"\n    },\n    \"source\": {\n      \"@id\": \"pure:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workload\": {\n      \"@id\": \"pure:workload\",\n      \"@type\": \"@id\"\n    },\n    \"configuration\": {\n      \"@id\": \"pure:configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"writable\": {\n      \"@id\": \"pure:writable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"owner\": {\n      \"@id\": \"pure:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerDestroyed\": {\n      \"@id\": \"pure:owner_destroyed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"policies\": {\n      \"@id\": \"pure:policies\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policy\": {\n      \"@id\": \"pure:policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suffix\": {\n      \"@id\": \"pure:suffix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"pure:address\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"attachedServers\": {\n      \"@id\": \"pure:attached_servers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gateway\": {\n      \"@id\": \"pure:gateway\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mtu\": {\n      \"@id\": \"pure:mtu\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"netmask\": {\n      \"@id\": \"pure:netmask\",\n      \"@type\": \"xsd:string\"\n    },\n    \"services\": {\n      \"@id\": \"pure:services\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnet\": {\n      \"@id\": \"pure:subnet\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"pure:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vlan\": {\n      \"@id\": \"pure:vlan\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bucketDefaults\": {\n      \"@id\": \"pure:bucket_defaults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessKeys\": {\n      \"@id\": \"pure:access_keys\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostname\": {\n      \"@id\": \"pure:hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rules\": {\n      \"@id\": \"pure:rules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/pure-storage/refs/heads/main/json-ld/pure-storage-flashblade-rest-api-context.jsonld
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
