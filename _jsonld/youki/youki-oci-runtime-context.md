---
class_count: 20
classes:
- BlockIODevice
- BlockIODeviceWeight
- Device
- DeviceCgroup
- Hook
- IDMapping
- IOMemEntryFormat
- MapStringString
- Mount
- NamespaceReference
- NetDevice
- NetworkInterfacePriority
- OciRuntimeConfig
- OciRuntimeFeatures
- OciRuntimeState
- Personality
- Rdma
- Syscall
- SyscallArg
- TimeOffsets
context_file: json-ld/youki-oci-runtime-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/youki/refs/heads/main/json-ld/youki-oci-runtime-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Youki Oci Runtime from Youki.
layout: jsonld
name: Youki Oci Runtime Context
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
  name: access
  type: string
- container: ''
  name: action
  type: ''
- container: ''
  name: additionalGids
  type: ''
- container: ''
  name: allow
  type: boolean
- container: ''
  name: ambient
  type: ''
- container: ''
  name: annotations
  type: ''
- container: ''
  name: apparmorProfile
  type: string
- container: ''
  name: args
  type: ''
- container: ''
  name: bounding
  type: ''
- container: ''
  name: bundle
  type: string
- container: ''
  name: capabilities
  type: reference
- container: ''
  name: class
  type: string
- container: ''
  name: commandLine
  type: string
- container: ''
  name: consoleSize
  type: reference
- container: ''
  name: containerID
  type: ''
- container: ''
  name: createContainer
  type: ''
- container: ''
  name: createRuntime
  type: ''
- container: ''
  name: cwd
  type: string
- container: ''
  name: deadline
  type: ''
- container: ''
  name: destination
  type: ''
- container: ''
  name: domain
  type: ''
- container: ''
  name: domainname
  type: string
- container: ''
  name: effective
  type: ''
- container: ''
  name: env
  type: ''
- container: ''
  name: errnoRet
  type: ''
- container: ''
  name: execCPUAffinity
  type: reference
- container: ''
  name: fileMode
  type: ''
- container: ''
  name: final
  type: string
- container: ''
  name: firstGFN
  type: ''
- container: ''
  name: firstMFN
  type: ''
- container: set
  name: flags
  type: reference
- container: ''
  name: freebsd
  type: ''
- container: ''
  name: gid
  type: ''
- container: set
  name: gidMappings
  type: reference
- container: ''
  name: hard
  type: ''
- container: ''
  name: hcaHandles
  type: ''
- container: ''
  name: hcaObjects
  type: ''
- container: ''
  name: height
  type: ''
- container: ''
  name: hooks
  type: reference
- container: ''
  name: hostID
  type: ''
- container: ''
  name: hostname
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: idType
  type: string
- container: ''
  name: index
  type: ''
- container: ''
  name: inheritable
  type: ''
- container: ''
  name: initial
  type: string
- container: ''
  name: ioPriority
  type: reference
- container: ''
  name: leafWeight
  type: ''
- container: ''
  name: linux
  type: ''
- container: ''
  name: major
  type: ''
- container: ''
  name: minor
  type: ''
- container: ''
  name: mode
  type: ''
- container: ''
  name: mountOptions
  type: ''
- container: set
  name: mounts
  type: reference
- container: ''
  name: name
  type: string
- container: set
  name: names
  type: string
- container: ''
  name: nanosecs
  type: ''
- container: ''
  name: nice
  type: ''
- container: ''
  name: noNewPrivileges
  type: boolean
- container: ''
  name: nrMFNs
  type: ''
- container: ''
  name: ociVersion
  type: ''
- container: ''
  name: ociVersionMax
  type: ''
- container: ''
  name: ociVersionMin
  type: ''
- container: ''
  name: oomScoreAdj
  type: integer
- container: ''
  name: op
  type: ''
- container: ''
  name: options
  type: ''
- container: ''
  name: path
  type: ''
- container: ''
  name: period
  type: ''
- container: ''
  name: permitted
  type: ''
- container: ''
  name: pid
  type: integer
- container: ''
  name: policy
  type: ''
- container: ''
  name: poststart
  type: ''
- container: ''
  name: poststop
  type: ''
- container: ''
  name: potentiallyUnsafeConfigAnnotations
  type: ''
- container: ''
  name: prestart
  type: ''
- container: ''
  name: priority
  type: ''
- container: ''
  name: process
  type: reference
- container: ''
  name: rate
  type: ''
- container: ''
  name: readonly
  type: boolean
- container: set
  name: rlimits
  type: reference
- container: ''
  name: root
  type: reference
- container: ''
  name: runtime
  type: ''
- container: ''
  name: scheduler
  type: reference
- container: ''
  name: secs
  type: ''
- container: ''
  name: selinuxLabel
  type: string
- container: ''
  name: size
  type: ''
- container: ''
  name: soft
  type: ''
- container: ''
  name: solaris
  type: ''
- container: ''
  name: source
  type: ''
- container: ''
  name: startContainer
  type: ''
- container: ''
  name: status
  type: string
- container: ''
  name: terminal
  type: boolean
- container: ''
  name: timeout
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: uid
  type: ''
- container: set
  name: uidMappings
  type: reference
- container: ''
  name: umask
  type: ''
- container: ''
  name: user
  type: reference
- container: ''
  name: username
  type: string
- container: ''
  name: value
  type: ''
- container: ''
  name: valueTwo
  type: ''
- container: ''
  name: vm
  type: ''
- container: ''
  name: weight
  type: ''
- container: ''
  name: width
  type: ''
- container: ''
  name: windows
  type: ''
- container: ''
  name: zos
  type: ''
property_count: 106
provider_name: Youki
provider_slug: youki
slug: youki-oci-runtime-context
source_filename: youki-oci-runtime-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://opencontainers.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BlockIODevice\": \"oci:BlockIODevice\",\n    \"BlockIODeviceWeight\": \"oci:BlockIODeviceWeight\",\n    \"Device\": \"oci:Device\",\n    \"DeviceCgroup\": \"oci:DeviceCgroup\",\n    \"Hook\": \"oci:Hook\",\n    \"IDMapping\": \"oci:IDMapping\",\n    \"IOMemEntryFormat\": \"oci:IOMemEntryFormat\",\n    \"MapStringString\": \"oci:MapStringString\",\n    \"Mount\": \"oci:Mount\",\n    \"NamespaceReference\": \"oci:NamespaceReference\",\n    \"NetDevice\": \"oci:NetDevice\",\n    \"NetworkInterfacePriority\": \"oci:NetworkInterfacePriority\",\n    \"OciRuntimeConfig\": \"oci:OciRuntimeConfig\",\n    \"OciRuntimeFeatures\": \"oci:OciRuntimeFeatures\",\n    \"OciRuntimeState\": \"oci:OciRuntimeState\",\n    \"Personality\": \"oci:Personality\"\
  ,\n    \"Rdma\": \"oci:Rdma\",\n    \"Syscall\": \"oci:Syscall\",\n    \"SyscallArg\": \"oci:SyscallArg\",\n    \"TimeOffsets\": \"oci:TimeOffsets\",\n    \"access\": {\n      \"@id\": \"oci:access\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"oci:action\"\n    },\n    \"additionalGids\": {\n      \"@id\": \"oci:additional_gids\"\n    },\n    \"allow\": {\n      \"@id\": \"oci:allow\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ambient\": {\n      \"@id\": \"oci:ambient\"\n    },\n    \"annotations\": {\n      \"@id\": \"oci:annotations\"\n    },\n    \"apparmorProfile\": {\n      \"@id\": \"oci:apparmor_profile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"args\": {\n      \"@id\": \"oci:args\"\n    },\n    \"bounding\": {\n      \"@id\": \"oci:bounding\"\n    },\n    \"bundle\": {\n      \"@id\": \"oci:bundle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capabilities\": {\n      \"@id\": \"oci:capabilities\",\n      \"@type\": \"@id\"\
  \n    },\n    \"class\": {\n      \"@id\": \"oci:class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commandLine\": {\n      \"@id\": \"oci:command_line\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consoleSize\": {\n      \"@id\": \"oci:console_size\",\n      \"@type\": \"@id\"\n    },\n    \"containerID\": {\n      \"@id\": \"oci:container_id\"\n    },\n    \"createContainer\": {\n      \"@id\": \"oci:create_container\"\n    },\n    \"createRuntime\": {\n      \"@id\": \"oci:create_runtime\"\n    },\n    \"cwd\": {\n      \"@id\": \"oci:cwd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deadline\": {\n      \"@id\": \"oci:deadline\"\n    },\n    \"destination\": {\n      \"@id\": \"oci:destination\"\n    },\n    \"domain\": {\n      \"@id\": \"oci:domain\"\n    },\n    \"domainname\": {\n      \"@id\": \"oci:domainname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effective\": {\n      \"@id\": \"oci:effective\"\n    },\n    \"env\": {\n      \"@id\": \"oci:env\"\n\
  \    },\n    \"errnoRet\": {\n      \"@id\": \"oci:errno_ret\"\n    },\n    \"execCPUAffinity\": {\n      \"@id\": \"oci:exec_cpu_affinity\",\n      \"@type\": \"@id\"\n    },\n    \"fileMode\": {\n      \"@id\": \"oci:file_mode\"\n    },\n    \"final\": {\n      \"@id\": \"oci:final\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstGFN\": {\n      \"@id\": \"oci:first_gfn\"\n    },\n    \"firstMFN\": {\n      \"@id\": \"oci:first_mfn\"\n    },\n    \"flags\": {\n      \"@id\": \"oci:flags\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"freebsd\": {\n      \"@id\": \"oci:freebsd\"\n    },\n    \"gid\": {\n      \"@id\": \"oci:gid\"\n    },\n    \"gidMappings\": {\n      \"@id\": \"oci:gid_mappings\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"hard\": {\n      \"@id\": \"oci:hard\"\n    },\n    \"hcaHandles\": {\n      \"@id\": \"oci:hca_handles\"\n    },\n    \"hcaObjects\": {\n      \"@id\": \"oci:hca_objects\"\n    },\n\
  \    \"height\": {\n      \"@id\": \"oci:height\"\n    },\n    \"hooks\": {\n      \"@id\": \"oci:hooks\",\n      \"@type\": \"@id\"\n    },\n    \"hostID\": {\n      \"@id\": \"oci:host_id\"\n    },\n    \"hostname\": {\n      \"@id\": \"oci:hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"oci:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idType\": {\n      \"@id\": \"oci:id_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"index\": {\n      \"@id\": \"oci:index\"\n    },\n    \"inheritable\": {\n      \"@id\": \"oci:inheritable\"\n    },\n    \"initial\": {\n      \"@id\": \"oci:initial\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ioPriority\": {\n      \"@id\": \"oci:io_priority\",\n      \"@type\": \"@id\"\n    },\n    \"leafWeight\": {\n      \"@id\": \"oci:leaf_weight\"\n    },\n    \"linux\": {\n      \"@id\": \"oci:linux\"\n    },\n    \"major\": {\n      \"@id\": \"oci:major\"\n    },\n    \"minor\": {\n      \"@id\": \"\
  oci:minor\"\n    },\n    \"mode\": {\n      \"@id\": \"oci:mode\"\n    },\n    \"mountOptions\": {\n      \"@id\": \"oci:mount_options\"\n    },\n    \"mounts\": {\n      \"@id\": \"oci:mounts\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"names\": {\n      \"@id\": \"oci:names\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nanosecs\": {\n      \"@id\": \"oci:nanosecs\"\n    },\n    \"nice\": {\n      \"@id\": \"oci:nice\"\n    },\n    \"noNewPrivileges\": {\n      \"@id\": \"oci:no_new_privileges\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"nrMFNs\": {\n      \"@id\": \"oci:nr_mf_ns\"\n    },\n    \"ociVersion\": {\n      \"@id\": \"oci:oci_version\"\n    },\n    \"ociVersionMax\": {\n      \"@id\": \"oci:oci_version_max\"\n    },\n    \"ociVersionMin\": {\n      \"@id\": \"oci:oci_version_min\"\n    },\n    \"oomScoreAdj\"\
  : {\n      \"@id\": \"oci:oom_score_adj\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"op\": {\n      \"@id\": \"oci:op\"\n    },\n    \"options\": {\n      \"@id\": \"oci:options\"\n    },\n    \"path\": {\n      \"@id\": \"oci:path\"\n    },\n    \"period\": {\n      \"@id\": \"oci:period\"\n    },\n    \"permitted\": {\n      \"@id\": \"oci:permitted\"\n    },\n    \"pid\": {\n      \"@id\": \"oci:pid\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"policy\": {\n      \"@id\": \"oci:policy\"\n    },\n    \"poststart\": {\n      \"@id\": \"oci:poststart\"\n    },\n    \"poststop\": {\n      \"@id\": \"oci:poststop\"\n    },\n    \"potentiallyUnsafeConfigAnnotations\": {\n      \"@id\": \"oci:potentially_unsafe_config_annotations\"\n    },\n    \"prestart\": {\n      \"@id\": \"oci:prestart\"\n    },\n    \"priority\": {\n      \"@id\": \"oci:priority\"\n    },\n    \"process\": {\n      \"@id\": \"oci:process\",\n      \"@type\": \"@id\"\n    },\n    \"rate\": {\n      \"@id\"\
  : \"oci:rate\"\n    },\n    \"readonly\": {\n      \"@id\": \"oci:readonly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"rlimits\": {\n      \"@id\": \"oci:rlimits\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"root\": {\n      \"@id\": \"oci:root\",\n      \"@type\": \"@id\"\n    },\n    \"runtime\": {\n      \"@id\": \"oci:runtime\"\n    },\n    \"scheduler\": {\n      \"@id\": \"oci:scheduler\",\n      \"@type\": \"@id\"\n    },\n    \"secs\": {\n      \"@id\": \"oci:secs\"\n    },\n    \"selinuxLabel\": {\n      \"@id\": \"oci:selinux_label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"oci:size\"\n    },\n    \"soft\": {\n      \"@id\": \"oci:soft\"\n    },\n    \"solaris\": {\n      \"@id\": \"oci:solaris\"\n    },\n    \"source\": {\n      \"@id\": \"oci:source\"\n    },\n    \"startContainer\": {\n      \"@id\": \"oci:start_container\"\n    },\n    \"status\": {\n      \"@id\": \"oci:status\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"terminal\": {\n      \"@id\": \"oci:terminal\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"timeout\": {\n      \"@id\": \"oci:timeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"oci:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uid\": {\n      \"@id\": \"oci:uid\"\n    },\n    \"uidMappings\": {\n      \"@id\": \"oci:uid_mappings\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"umask\": {\n      \"@id\": \"oci:umask\"\n    },\n    \"user\": {\n      \"@id\": \"oci:user\",\n      \"@type\": \"@id\"\n    },\n    \"username\": {\n      \"@id\": \"oci:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"oci:value\"\n    },\n    \"valueTwo\": {\n      \"@id\": \"oci:value_two\"\n    },\n    \"vm\": {\n      \"@id\": \"oci:vm\"\n    },\n    \"weight\": {\n      \"@id\": \"oci:weight\"\n    },\n    \"width\": {\n      \"@id\": \"oci:width\"\n    },\n\
  \    \"windows\": {\n      \"@id\": \"oci:windows\"\n    },\n    \"zos\": {\n      \"@id\": \"oci:zos\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/youki/refs/heads/main/json-ld/youki-oci-runtime-context.jsonld
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
