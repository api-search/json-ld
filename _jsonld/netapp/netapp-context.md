---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: NetApp Cloud Manager API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.netapp.com/us-en/cloud-manager-automation/api/openapi.yaml
- filename: netapp-ontap-openapi.yml
  format: yaml
  label: NetApp ONTAP REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/netapp/refs/heads/main/openapi/netapp-ontap-openapi.yml
class_count: 0
classes: []
context_file: json-ld/netapp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/netapp/refs/heads/main/json-ld/netapp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Netapp from NetApp.
layout: jsonld
name: Netapp Context
namespaces:
- prefix: netapp
  uri: https://netapp.com/ns/ontap/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: ClusterNode
  type: ''
- container: ''
  name: Volume
  type: ''
- container: ''
  name: Aggregate
  type: ''
- container: ''
  name: Svm
  type: ''
- container: ''
  name: Snapshot
  type: ''
- container: ''
  name: NetworkInterface
  type: ''
- container: ''
  name: License
  type: ''
property_count: 8
provider_name: NetApp
provider_slug: netapp
slug: netapp-context
source_filename: netapp-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"netapp\": \"https://netapp.com/ns/ontap/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Cluster\": {\n      \"@id\": \"netapp:Cluster\",\n      \"@context\": {\n        \"uuid\": {\n          \"@id\": \"netapp:uuid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contact\": {\n          \"@id\": \"schema:contactPoint\",\n          \"@type\": \"xsd:string\"\n        },\n        \"location\": {\n          \"@id\": \"schema:location\",\n          \"@type\": \"xsd:string\"\n        },\n        \"version\": \"netapp:version\",\n        \"dns_domains\": {\n          \"@id\": \"netapp:dnsDomains\",\n          \"@container\": \"@set\"\n        },\n        \"ntp_servers\": {\n          \"@id\": \"netapp:ntpServers\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"timezone\": \"netapp:timezone\",\n        \"nodes\": {\n          \"@id\": \"netapp:hasNode\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ClusterNode\": {\n      \"@id\": \"netapp:ClusterNode\",\n      \"@context\": {\n        \"uuid\": {\n          \"@id\": \"netapp:uuid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"model\": {\n          \"@id\": \"schema:model\",\n          \"@type\": \"xsd:string\"\n        },\n        \"serial_number\": {\n          \"@id\": \"netapp:serialNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"uptime\": {\n          \"@id\": \"netapp:uptime\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"state\": \"netapp:operationalState\"\n      }\n    },\n\n    \"Volume\": {\n      \"@id\"\
  : \"netapp:Volume\",\n      \"@context\": {\n        \"uuid\": {\n          \"@id\": \"netapp:uuid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": \"netapp:volumeType\",\n        \"state\": \"netapp:operationalState\",\n        \"style\": \"netapp:volumeStyle\",\n        \"size\": {\n          \"@id\": \"netapp:sizeBytes\",\n          \"@type\": \"xsd:long\"\n        },\n        \"comment\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"language\": \"netapp:languageEncoding\",\n        \"create_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"svm\": {\n          \"@id\": \"netapp:belongsToSvm\",\n          \"@type\": \"@id\"\n        },\n        \"aggregates\": {\n          \"@id\": \"netapp:residesOnAggregate\",\n          \"@type\": \"\
  @id\",\n          \"@container\": \"@set\"\n        },\n        \"space\": \"netapp:spaceUtilization\",\n        \"nas\": \"netapp:nasConfiguration\",\n        \"guarantee\": \"netapp:spaceGuarantee\",\n        \"snapshot_policy\": {\n          \"@id\": \"netapp:snapshotPolicy\",\n          \"@type\": \"@id\"\n        },\n        \"qos\": \"netapp:qosConfiguration\",\n        \"tiering\": \"netapp:tieringPolicy\",\n        \"encryption\": \"netapp:encryptionConfiguration\",\n        \"autosize\": \"netapp:autosizeConfiguration\"\n      }\n    },\n\n    \"Aggregate\": {\n      \"@id\": \"netapp:Aggregate\",\n      \"@context\": {\n        \"uuid\": {\n          \"@id\": \"netapp:uuid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": \"netapp:operationalState\",\n        \"node\": {\n          \"@id\": \"netapp:ownedByNode\",\n          \"@type\": \"@id\"\n   \
  \     },\n        \"space\": \"netapp:spaceUtilization\",\n        \"block_storage\": \"netapp:blockStorageConfiguration\",\n        \"data_encryption\": \"netapp:dataEncryption\",\n        \"create_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Svm\": {\n      \"@id\": \"netapp:StorageVirtualMachine\",\n      \"@context\": {\n        \"uuid\": {\n          \"@id\": \"netapp:uuid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": \"netapp:operationalState\",\n        \"subtype\": \"netapp:svmSubtype\",\n        \"language\": \"netapp:languageEncoding\",\n        \"comment\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ipspace\": \"netapp:ipspace\",\n        \"aggregates\": {\n          \"@id\": \"netapp:assignedAggregate\"\
  ,\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"ip_interfaces\": {\n          \"@id\": \"netapp:hasInterface\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"nfs\": \"netapp:nfsConfiguration\",\n        \"cifs\": \"netapp:cifsConfiguration\",\n        \"iscsi\": \"netapp:iscsiConfiguration\",\n        \"fcp\": \"netapp:fcpConfiguration\",\n        \"nvme\": \"netapp:nvmeConfiguration\",\n        \"dns\": \"netapp:dnsConfiguration\",\n        \"max_volumes\": {\n          \"@id\": \"netapp:maxVolumes\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Snapshot\": {\n      \"@id\": \"netapp:Snapshot\",\n      \"@context\": {\n        \"uuid\": {\n          \"@id\": \"netapp:uuid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"create_time\": {\n          \"\
  @id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expiry_time\": {\n          \"@id\": \"netapp:expiryTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"comment\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"size\": {\n          \"@id\": \"netapp:sizeBytes\",\n          \"@type\": \"xsd:long\"\n        },\n        \"state\": \"netapp:snapshotState\",\n        \"snapmirror_label\": \"netapp:snapmirrorLabel\",\n        \"volume\": {\n          \"@id\": \"netapp:belongsToVolume\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"NetworkInterface\": {\n      \"@id\": \"netapp:NetworkInterface\",\n      \"@context\": {\n        \"uuid\": {\n          \"@id\": \"netapp:uuid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ip\": \"netapp:ipConfiguration\"\
  ,\n        \"state\": \"netapp:operationalState\",\n        \"enabled\": {\n          \"@id\": \"netapp:enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"scope\": \"netapp:interfaceScope\",\n        \"service_policy\": \"netapp:servicePolicy\",\n        \"svm\": {\n          \"@id\": \"netapp:belongsToSvm\",\n          \"@type\": \"@id\"\n        },\n        \"location\": \"netapp:interfaceLocation\"\n      }\n    },\n\n    \"License\": {\n      \"@id\": \"netapp:License\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"scope\": \"netapp:licenseScope\",\n        \"state\": \"netapp:complianceState\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/netapp/refs/heads/main/json-ld/netapp-context.jsonld
tags:
- Cloud
- Data Management
- Hybrid Cloud
- Infrastructure
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
