---
class_count: 7
classes:
- MapStringObject
- MapStringString
- OciImageConfig
- OciImageContentDescriptor
- OciImageIndex
- OciImageLayout
- OciImageManifest
context_file: json-ld/youki-oci-image-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/youki/refs/heads/main/json-ld/youki-oci-image-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Youki Oci Image from Youki.
layout: jsonld
name: Youki Oci Image Context
namespaces:
- prefix: oci
  uri: https://opencontainers.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ArgsEscaped
  type: boolean
- container: ''
  name: Cmd
  type: ''
- container: ''
  name: Entrypoint
  type: ''
- container: set
  name: Env
  type: string
- container: ''
  name: ExposedPorts
  type: ''
- container: ''
  name: Labels
  type: ''
- container: ''
  name: StopSignal
  type: string
- container: ''
  name: User
  type: string
- container: ''
  name: Volumes
  type: ''
- container: ''
  name: WorkingDir
  type: string
- container: ''
  name: annotations
  type: ''
- container: ''
  name: architecture
  type: string
- container: ''
  name: artifactType
  type: ''
- container: ''
  name: author
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: config
  type: reference
- container: ''
  name: created
  type: dateTime
- container: ''
  name: createdBy
  type: string
- container: ''
  name: data
  type: ''
- container: set
  name: diffIds
  type: string
- container: ''
  name: digest
  type: ''
- container: ''
  name: emptyLayer
  type: boolean
- container: set
  name: history
  type: reference
- container: ''
  name: imageLayoutVersion
  type: string
- container: set
  name: layers
  type: reference
- container: set
  name: manifests
  type: reference
- container: ''
  name: mediaType
  type: ''
- container: ''
  name: os
  type: string
- container: set
  name: osFeatures
  type: string
- container: ''
  name: osVersion
  type: string
- container: ''
  name: platform
  type: reference
- container: ''
  name: rootfs
  type: reference
- container: ''
  name: schemaVersion
  type: integer
- container: ''
  name: size
  type: ''
- container: ''
  name: subject
  type: ''
- container: ''
  name: type
  type: string
- container: ''
  name: urls
  type: ''
- container: ''
  name: variant
  type: string
property_count: 38
provider_name: Youki
provider_slug: youki
slug: youki-oci-image-context
source_filename: youki-oci-image-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://opencontainers.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MapStringObject\": \"oci:MapStringObject\",\n    \"MapStringString\": \"oci:MapStringString\",\n    \"OciImageConfig\": \"oci:OciImageConfig\",\n    \"OciImageContentDescriptor\": \"oci:OciImageContentDescriptor\",\n    \"OciImageIndex\": \"oci:OciImageIndex\",\n    \"OciImageLayout\": \"oci:OciImageLayout\",\n    \"OciImageManifest\": \"oci:OciImageManifest\",\n    \"ArgsEscaped\": {\n      \"@id\": \"oci:args_escaped\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Cmd\": {\n      \"@id\": \"oci:cmd\"\n    },\n    \"Entrypoint\": {\n      \"@id\": \"oci:entrypoint\"\n    },\n    \"Env\": {\n      \"@id\": \"oci:env\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExposedPorts\": {\n      \"\
  @id\": \"oci:exposed_ports\"\n    },\n    \"Labels\": {\n      \"@id\": \"oci:labels\"\n    },\n    \"StopSignal\": {\n      \"@id\": \"oci:stop_signal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"User\": {\n      \"@id\": \"oci:user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Volumes\": {\n      \"@id\": \"oci:volumes\"\n    },\n    \"WorkingDir\": {\n      \"@id\": \"oci:working_dir\",\n      \"@type\": \"xsd:string\"\n    },\n    \"annotations\": {\n      \"@id\": \"oci:annotations\"\n    },\n    \"architecture\": {\n      \"@id\": \"oci:architecture\",\n      \"@type\": \"xsd:string\"\n    },\n    \"artifactType\": {\n      \"@id\": \"oci:artifact_type\"\n    },\n    \"author\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"oci:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"config\": {\n      \"@id\": \"oci:config\",\n      \"@type\": \"@id\"\n    },\n    \"created\": {\n      \"@id\": \"\
  schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdBy\": {\n      \"@id\": \"oci:created_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"oci:data\"\n    },\n    \"diffIds\": {\n      \"@id\": \"oci:diff_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"digest\": {\n      \"@id\": \"oci:digest\"\n    },\n    \"emptyLayer\": {\n      \"@id\": \"oci:empty_layer\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"history\": {\n      \"@id\": \"oci:history\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"imageLayoutVersion\": {\n      \"@id\": \"oci:image_layout_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"layers\": {\n      \"@id\": \"oci:layers\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"manifests\": {\n      \"@id\": \"oci:manifests\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"mediaType\"\
  : {\n      \"@id\": \"oci:media_type\"\n    },\n    \"os\": {\n      \"@id\": \"oci:os\",\n      \"@type\": \"xsd:string\"\n    },\n    \"osFeatures\": {\n      \"@id\": \"oci:os_features\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"osVersion\": {\n      \"@id\": \"oci:os_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"oci:platform\",\n      \"@type\": \"@id\"\n    },\n    \"rootfs\": {\n      \"@id\": \"oci:rootfs\",\n      \"@type\": \"@id\"\n    },\n    \"schemaVersion\": {\n      \"@id\": \"oci:schema_version\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"size\": {\n      \"@id\": \"oci:size\"\n    },\n    \"subject\": {\n      \"@id\": \"oci:subject\"\n    },\n    \"type\": {\n      \"@id\": \"oci:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"urls\": {\n      \"@id\": \"oci:urls\"\n    },\n    \"variant\": {\n      \"@id\": \"oci:variant\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n\
  }\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/youki/refs/heads/main/json-ld/youki-oci-image-context.jsonld
tags:
- Containers
- Container Runtime
- OCI
- Rust
- CNCF
- Cloud Native
- Kubernetes
- JSON-LD
- Linked Data
- Semantic Web
---
