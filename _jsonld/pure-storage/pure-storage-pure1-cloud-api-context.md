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
class_count: 13
classes:
- Alert
- Array
- Audit
- Blade
- Bucket
- FileSystem
- FileSystemSnapshot
- Metric
- ProtectionGroupSnapshot
- SubscriptionLicense
- Subscription
- SupportContract
- Tag
context_file: json-ld/pure-storage-pure1-cloud-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/pure-storage/refs/heads/main/json-ld/pure-storage-pure1-cloud-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Pure Storage Pure1 Cloud Api from Pure Storage.
layout: jsonld
name: Pure Storage Pure1 Cloud Api Context
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
  name: expected
  type: string
- container: ''
  name: knowledgeBaseUrl
  type: string
- container: ''
  name: notified
  type: integer
- container: ''
  name: origin
  type: string
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
  name: id
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: fqdn
  type: string
- container: ''
  name: model
  type: string
- container: ''
  name: os
  type: string
- container: ''
  name: version
  type: ''
- container: ''
  name: arguments
  type: string
- container: ''
  name: command
  type: string
- container: ''
  name: subcommand
  type: string
- container: ''
  name: time
  type: integer
- container: ''
  name: user
  type: string
- container: set
  name: arrays
  type: string
- container: ''
  name: details
  type: string
- container: ''
  name: rawCapacity
  type: decimal
- container: ''
  name: status
  type: string
- container: ''
  name: account
  type: reference
- container: ''
  name: resourceType
  type: string
- container: ''
  name: destroyed
  type: boolean
- container: ''
  name: objectCount
  type: integer
- container: ''
  name: versioning
  type: string
- container: ''
  name: fastRemoveDirectoryEnabled
  type: boolean
- container: ''
  name: hardLimitEnabled
  type: boolean
- container: ''
  name: http
  type: string
- container: ''
  name: nfs
  type: string
- container: ''
  name: provisioned
  type: integer
- container: ''
  name: smb
  type: string
- container: ''
  name: snapshotDirectoryEnabled
  type: boolean
- container: ''
  name: 'on'
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: suffix
  type: string
- container: set
  name: availabilities
  type: string
- container: set
  name: resourceTypes
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: pod
  type: string
- container: set
  name: addOnSlas
  type: string
- container: ''
  name: averageOnDemand
  type: string
- container: ''
  name: expirationDate
  type: integer
- container: ''
  name: lastUpdatedDate
  type: integer
- container: ''
  name: marketplacePartner
  type: string
- container: ''
  name: preRatio
  type: string
- container: ''
  name: data
  type: float
- container: ''
  name: quarterOnDemand
  type: string
- container: ''
  name: reservation
  type: string
- container: set
  name: resources
  type: string
- container: ''
  name: serviceTier
  type: string
- container: ''
  name: siteAddress
  type: string
- container: ''
  name: startDate
  type: integer
- container: ''
  name: subscription
  type: string
- container: ''
  name: usage
  type: string
- container: ''
  name: customerName
  type: string
- container: ''
  name: initialName
  type: string
- container: ''
  name: organization
  type: string
- container: ''
  name: partnerName
  type: string
- container: ''
  name: service
  type: string
- container: ''
  name: serviceDetails
  type: string
- container: ''
  name: subscriptionTerm
  type: integer
- container: ''
  name: endDate
  type: integer
- container: ''
  name: resource
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: tagOrganizationId
  type: integer
- container: ''
  name: value
  type: string
property_count: 78
provider_name: Pure Storage
provider_slug: pure-storage
slug: pure-storage-pure1-cloud-api-context
source_filename: pure-storage-pure1-cloud-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pure\": \"https://code.purestorage.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Alert\": \"pure:Alert\",\n    \"Array\": \"pure:Array\",\n    \"Audit\": \"pure:Audit\",\n    \"Blade\": \"pure:Blade\",\n    \"Bucket\": \"pure:Bucket\",\n    \"FileSystem\": \"pure:FileSystem\",\n    \"FileSystemSnapshot\": \"pure:FileSystemSnapshot\",\n    \"Metric\": \"pure:Metric\",\n    \"ProtectionGroupSnapshot\": \"pure:ProtectionGroupSnapshot\",\n    \"SubscriptionLicense\": \"pure:SubscriptionLicense\",\n    \"Subscription\": \"pure:Subscription\",\n    \"SupportContract\": \"pure:SupportContract\",\n    \"Tag\": \"pure:Tag\",\n    \"actual\": {\n      \"@id\": \"pure:actual\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"pure:category\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"closed\": {\n      \"@id\": \"pure:closed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"code\": {\n      \"@id\": \"pure:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"componentName\": {\n      \"@id\": \"pure:component_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentType\": {\n      \"@id\": \"pure:component_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"schema:dateCreated\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"expected\": {\n      \"@id\": \"pure:expected\",\n      \"@type\": \"xsd:string\"\n    },\n    \"knowledgeBaseUrl\": {\n      \"@id\": \"pure:knowledge_base_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notified\": {\n      \"@id\": \"pure:notified\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"origin\": {\n      \"@id\": \"pure:origin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pure:severity\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"pure:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"pure:summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updated\": {\n      \"@id\": \"pure:updated\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"pure:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"fqdn\": {\n      \"@id\": \"pure:fqdn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model\": {\n      \"@id\": \"pure:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"os\": {\n      \"@id\": \"pure:os\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\"\n    },\n    \"arguments\": {\n      \"@id\": \"pure:arguments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"command\": {\n      \"@id\": \"pure:command\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subcommand\"\
  : {\n      \"@id\": \"pure:subcommand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"time\": {\n      \"@id\": \"pure:time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"user\": {\n      \"@id\": \"pure:user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arrays\": {\n      \"@id\": \"pure:arrays\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"details\": {\n      \"@id\": \"pure:details\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rawCapacity\": {\n      \"@id\": \"pure:raw_capacity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"status\": {\n      \"@id\": \"pure:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"account\": {\n      \"@id\": \"pure:account\",\n      \"@type\": \"@id\"\n    },\n    \"resourceType\": {\n      \"@id\": \"pure:resource_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destroyed\": {\n      \"@id\": \"pure:destroyed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"objectCount\": {\n\
  \      \"@id\": \"pure:object_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"versioning\": {\n      \"@id\": \"pure:versioning\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fastRemoveDirectoryEnabled\": {\n      \"@id\": \"pure:fast_remove_directory_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"hardLimitEnabled\": {\n      \"@id\": \"pure:hard_limit_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"http\": {\n      \"@id\": \"pure:http\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nfs\": {\n      \"@id\": \"pure:nfs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provisioned\": {\n      \"@id\": \"pure:provisioned\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"smb\": {\n      \"@id\": \"pure:smb\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshotDirectoryEnabled\": {\n      \"@id\": \"pure:snapshot_directory_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"on\": {\n      \"@id\": \"pure:on\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"source\": {\n      \"@id\": \"pure:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suffix\": {\n      \"@id\": \"pure:suffix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availabilities\": {\n      \"@id\": \"pure:availabilities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceTypes\": {\n      \"@id\": \"pure:resource_types\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"pure:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pod\": {\n      \"@id\": \"pure:pod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addOnSlas\": {\n      \"@id\": \"pure:add_on_slas\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"averageOnDemand\": {\n      \"@id\": \"pure:average_on_demand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"pure:expiration_date\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"lastUpdatedDate\": {\n      \"@id\": \"pure:last_updated_date\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"marketplacePartner\": {\n      \"@id\": \"pure:marketplace_partner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preRatio\": {\n      \"@id\": \"pure:pre_ratio\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"pure:data\",\n      \"@type\": \"xsd:float\"\n    },\n    \"quarterOnDemand\": {\n      \"@id\": \"pure:quarter_on_demand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reservation\": {\n      \"@id\": \"pure:reservation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resources\": {\n      \"@id\": \"pure:resources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceTier\": {\n      \"@id\": \"pure:service_tier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"siteAddress\": {\n      \"@id\": \"pure:site_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\"\
  : {\n      \"@id\": \"pure:start_date\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"subscription\": {\n      \"@id\": \"pure:subscription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usage\": {\n      \"@id\": \"pure:usage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerName\": {\n      \"@id\": \"pure:customer_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"initialName\": {\n      \"@id\": \"pure:initial_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organization\": {\n      \"@id\": \"pure:organization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partnerName\": {\n      \"@id\": \"pure:partner_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"pure:service\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceDetails\": {\n      \"@id\": \"pure:service_details\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriptionTerm\": {\n      \"@id\": \"pure:subscription_term\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"endDate\": {\n      \"@id\": \"pure:end_date\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"resource\": {\n      \"@id\": \"pure:resource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"pure:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"pure:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tagOrganizationId\": {\n      \"@id\": \"pure:tag_organization_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"value\": {\n      \"@id\": \"pure:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/pure-storage/refs/heads/main/json-ld/pure-storage-pure1-cloud-api-context.jsonld
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
