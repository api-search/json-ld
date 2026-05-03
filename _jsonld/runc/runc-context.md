---
class_count: 43
classes:
- ContainerConfig
- ociVersion
- process
- root
- hostname
- mounts
- annotations
- Process
- terminal
- user
- args
- env
- cwd
- capabilities
- noNewPrivileges
- RootFilesystem
- path
- readonly
- Mount
- destination
- source
- type
- options
- LinuxConfig
- namespaces
- resources
- seccomp
- maskedPaths
- readonlyPaths
- Namespace
- namespaceType
- CgroupResources
- memory
- cpu
- pids
- SeccompProfile
- defaultAction
- syscalls
- Hook
- timeout
- programmingLanguage
- operatingSystem
- softwareVersion
context_file: json-ld/runc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/runc/refs/heads/main/json-ld/runc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Runc from Runc.
layout: jsonld
name: Runc Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: oci
  uri: https://opencontainers.org/schema/
- prefix: runc
  uri: https://github.com/opencontainers/runc#
properties:
- container: ''
  name: ContainerRuntime
  type: reference
- container: ''
  name: openContainersProject
  type: reference
- container: ''
  name: implementsSpec
  type: reference
- container: ''
  name: license
  type: reference
- container: ''
  name: codeRepository
  type: reference
property_count: 5
provider_name: Runc
provider_slug: runc
slug: runc-context
source_filename: runc-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"oci\": \"https://opencontainers.org/schema/\",\n    \"runc\": \"https://github.com/opencontainers/runc#\",\n\n    \"ContainerConfig\": \"oci:ContainerConfig\",\n    \"ociVersion\": \"oci:ociVersion\",\n    \"process\": \"oci:process\",\n    \"root\": \"oci:root\",\n    \"hostname\": \"schema:name\",\n    \"mounts\": \"oci:mounts\",\n    \"annotations\": \"schema:additionalProperty\",\n\n    \"Process\": \"oci:Process\",\n    \"terminal\": \"oci:terminal\",\n    \"user\": \"schema:agent\",\n    \"args\": \"oci:args\",\n    \"env\": \"oci:env\",\n    \"cwd\": \"oci:cwd\",\n    \"capabilities\": \"oci:capabilities\",\n    \"noNewPrivileges\": \"oci:noNewPrivileges\",\n\n    \"RootFilesystem\": \"oci:RootFilesystem\",\n    \"path\": \"oci:path\",\n    \"readonly\": \"oci:readonly\",\n\n    \"Mount\": \"oci:Mount\",\n    \"destination\": \"oci:destination\",\n    \"source\": \"oci:source\"\
  ,\n    \"type\": \"schema:additionalType\",\n    \"options\": \"oci:mountOptions\",\n\n    \"LinuxConfig\": \"oci:LinuxConfig\",\n    \"namespaces\": \"oci:namespaces\",\n    \"resources\": \"oci:resources\",\n    \"seccomp\": \"oci:seccomp\",\n    \"maskedPaths\": \"oci:maskedPaths\",\n    \"readonlyPaths\": \"oci:readonlyPaths\",\n\n    \"Namespace\": \"oci:Namespace\",\n    \"namespaceType\": \"oci:namespaceType\",\n\n    \"CgroupResources\": \"oci:CgroupResources\",\n    \"memory\": \"oci:memoryResources\",\n    \"cpu\": \"oci:cpuResources\",\n    \"pids\": \"oci:pidsResources\",\n\n    \"SeccompProfile\": \"oci:SeccompProfile\",\n    \"defaultAction\": \"oci:defaultAction\",\n    \"syscalls\": \"oci:syscalls\",\n\n    \"Hook\": \"oci:Hook\",\n    \"timeout\": \"oci:timeout\",\n\n    \"ContainerRuntime\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@type\": \"@id\"\n    },\n    \"openContainersProject\": {\n      \"@id\": \"schema:isPartOf\",\n      \"@type\": \"@id\"\
  \n    },\n    \"implementsSpec\": {\n      \"@id\": \"schema:isBasedOn\",\n      \"@type\": \"@id\"\n    },\n    \"license\": {\n      \"@id\": \"schema:license\",\n      \"@type\": \"@id\"\n    },\n    \"codeRepository\": {\n      \"@id\": \"schema:codeRepository\",\n      \"@type\": \"@id\"\n    },\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"operatingSystem\": \"schema:operatingSystem\",\n    \"softwareVersion\": \"schema:softwareVersion\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/runc/refs/heads/main/json-ld/runc-context.jsonld
tags:
- Container Runtime
- Containers
- Linux
- OCI
- Open Source
- CNCF
- Open Container Initiative
- Cloud Native
- JSON-LD
- Linked Data
- Semantic Web
---
