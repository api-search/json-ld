---
api_specs:
- filename: oci-compute-api-openapi.yml
  format: yaml
  label: OCI Compute API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle/refs/heads/main/openapi/oci-compute-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/oracle-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle/refs/heads/main/json-ld/oracle-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle from Oracle.
layout: jsonld
name: Oracle Context
namespaces:
- prefix: oci
  uri: https://docs.oracle.com/en-us/iaas/api/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: ComputeInstance
  type: ''
- container: ''
  name: ShapeConfig
  type: ''
- container: ''
  name: Shape
  type: ''
- container: ''
  name: Image
  type: ''
- container: ''
  name: VnicAttachment
  type: ''
- container: ''
  name: VolumeAttachment
  type: ''
- container: ''
  name: Compartment
  type: ''
- container: ''
  name: ConsoleConnection
  type: ''
- container: ''
  name: Tag
  type: ''
property_count: 9
provider_name: Oracle
provider_slug: oracle
slug: oracle-context
source_filename: oracle-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/api/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"ComputeInstance\": {\n      \"@id\": \"oci:ComputeInstance\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\",\n        \"compartmentId\": \"oci:compartmentId\",\n        \"availabilityDomain\": \"oci:availabilityDomain\",\n        \"faultDomain\": \"oci:faultDomain\",\n        \"shape\": \"oci:shape\",\n        \"region\": \"oci:region\",\n        \"lifecycleState\": \"oci:lifecycleState\",\n        \"timeCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"metadata\": \"oci:metadata\",\n        \"imageId\": \"oci:imageId\",\n        \"launchMode\": \"oci:launchMode\",\n        \"capacityReservationId\": \"oci:capacityReservationId\"\
  ,\n        \"dedicatedVmHostId\": \"oci:dedicatedVmHostId\",\n        \"isCrossNumaNode\": {\n          \"@id\": \"oci:isCrossNumaNode\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"definedTags\": \"oci:definedTags\",\n        \"freeformTags\": \"oci:freeformTags\"\n      }\n    },\n\n    \"ShapeConfig\": {\n      \"@id\": \"oci:ShapeConfig\",\n      \"@context\": {\n        \"ocpus\": {\n          \"@id\": \"oci:ocpus\",\n          \"@type\": \"xsd:float\"\n        },\n        \"memoryInGBs\": {\n          \"@id\": \"oci:memoryInGBs\",\n          \"@type\": \"xsd:float\"\n        },\n        \"baselineOcpuUtilization\": \"oci:baselineOcpuUtilization\",\n        \"processorDescription\": \"schema:description\",\n        \"networkingBandwidthInGbps\": {\n          \"@id\": \"oci:networkingBandwidthInGbps\",\n          \"@type\": \"xsd:float\"\n        },\n        \"maxVnicAttachments\": {\n          \"@id\": \"oci:maxVnicAttachments\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"gpus\": {\n          \"@id\": \"oci:gpus\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"gpuDescription\": \"oci:gpuDescription\",\n        \"localDisks\": {\n          \"@id\": \"oci:localDisks\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"localDisksTotalSizeInGBs\": {\n          \"@id\": \"oci:localDisksTotalSizeInGBs\",\n          \"@type\": \"xsd:float\"\n        },\n        \"vcpus\": {\n          \"@id\": \"oci:vcpus\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Shape\": {\n      \"@id\": \"oci:Shape\",\n      \"@context\": {\n        \"shape\": \"schema:name\",\n        \"availabilityDomain\": \"oci:availabilityDomain\",\n        \"ocpus\": {\n          \"@id\": \"oci:ocpus\",\n          \"@type\": \"xsd:float\"\n        },\n        \"memoryInGBs\": {\n          \"@id\": \"oci:memoryInGBs\",\n          \"@type\": \"xsd:float\"\n        },\n        \"processorDescription\": \"schema:description\"\
  ,\n        \"networkingBandwidthInGbps\": {\n          \"@id\": \"oci:networkingBandwidthInGbps\",\n          \"@type\": \"xsd:float\"\n        },\n        \"maxVnicAttachments\": {\n          \"@id\": \"oci:maxVnicAttachments\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"gpus\": {\n          \"@id\": \"oci:gpus\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"gpuDescription\": \"oci:gpuDescription\",\n        \"localDisks\": {\n          \"@id\": \"oci:localDisks\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"localDisksTotalSizeInGBs\": {\n          \"@id\": \"oci:localDisksTotalSizeInGBs\",\n          \"@type\": \"xsd:float\"\n        },\n        \"isFlexible\": {\n          \"@id\": \"oci:isFlexible\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isBilledForStoppedInstance\": {\n          \"@id\": \"oci:isBilledForStoppedInstance\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"quotaNames\": {\n       \
  \   \"@id\": \"oci:quotaNames\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Image\": {\n      \"@id\": \"oci:Image\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\",\n        \"compartmentId\": \"oci:compartmentId\",\n        \"operatingSystem\": \"schema:operatingSystem\",\n        \"operatingSystemVersion\": \"schema:softwareVersion\",\n        \"lifecycleState\": \"oci:lifecycleState\",\n        \"timeCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"baseImageId\": \"oci:baseImageId\",\n        \"sizeInMBs\": {\n          \"@id\": \"oci:sizeInMBs\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"billableSizeInGBs\": {\n          \"@id\": \"oci:billableSizeInGBs\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createImageAllowed\": {\n          \"@id\": \"oci:createImageAllowed\",\n          \"@type\": \"xsd:boolean\"\
  \n        },\n        \"launchMode\": \"oci:launchMode\"\n      }\n    },\n\n    \"VnicAttachment\": {\n      \"@id\": \"oci:VnicAttachment\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"instanceId\": \"oci:instanceId\",\n        \"compartmentId\": \"oci:compartmentId\",\n        \"availabilityDomain\": \"oci:availabilityDomain\",\n        \"displayName\": \"schema:name\",\n        \"vnicId\": \"oci:vnicId\",\n        \"subnetId\": \"oci:subnetId\",\n        \"nicIndex\": {\n          \"@id\": \"oci:nicIndex\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"vlanTag\": {\n          \"@id\": \"oci:vlanTag\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"lifecycleState\": \"oci:lifecycleState\",\n        \"timeCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"VolumeAttachment\": {\n      \"@id\": \"oci:VolumeAttachment\",\n      \"@context\": {\n        \"id\": \"@id\"\
  ,\n        \"instanceId\": \"oci:instanceId\",\n        \"volumeId\": \"oci:volumeId\",\n        \"compartmentId\": \"oci:compartmentId\",\n        \"availabilityDomain\": \"oci:availabilityDomain\",\n        \"displayName\": \"schema:name\",\n        \"device\": \"oci:device\",\n        \"attachmentType\": \"oci:attachmentType\",\n        \"lifecycleState\": \"oci:lifecycleState\",\n        \"timeCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"isReadOnly\": {\n          \"@id\": \"oci:isReadOnly\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isShareable\": {\n          \"@id\": \"oci:isShareable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isPvEncryptionInTransitEnabled\": {\n          \"@id\": \"oci:isPvEncryptionInTransitEnabled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Compartment\": {\n      \"@id\": \"oci:Compartment\",\n      \"@context\": {\n\
  \        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"dcterms:description\",\n        \"compartmentId\": \"oci:parentCompartmentId\",\n        \"lifecycleState\": \"oci:lifecycleState\",\n        \"timeCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"definedTags\": \"oci:definedTags\",\n        \"freeformTags\": \"oci:freeformTags\"\n      }\n    },\n\n    \"ConsoleConnection\": {\n      \"@id\": \"oci:InstanceConsoleConnection\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"instanceId\": \"oci:instanceId\",\n        \"compartmentId\": \"oci:compartmentId\",\n        \"connectionString\": \"oci:connectionString\",\n        \"fingerprint\": \"oci:fingerprint\",\n        \"vncConnectionString\": \"oci:vncConnectionString\",\n        \"lifecycleState\": \"oci:lifecycleState\",\n        \"serviceHostKeyFingerprint\": \"oci:serviceHostKeyFingerprint\"\n      }\n    },\n\n  \
  \  \"Tag\": {\n      \"@id\": \"oci:Tag\",\n      \"@context\": {\n        \"key\": \"schema:name\",\n        \"value\": \"schema:value\",\n        \"namespace\": \"oci:tagNamespace\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle/refs/heads/main/json-ld/oracle-context.jsonld
tags:
- Cloud
- Database
- Enterprise
- Infrastructure
- SaaS
- JSON-LD
- Linked Data
- Semantic Web
---
