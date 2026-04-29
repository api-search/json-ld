---
class_count: 30
classes:
- Device
- id
- name
- model
- vbios
- driverVersion
- memoryTotal
- pcieBusId
- computeUnits
- DeviceList
- devices
- DeviceHealth
- deviceId
- status
- temperature
- fanSpeed
- powerDraw
- eccErrors
- DevicePerformance
- gpuUtilization
- memoryUtilization
- memoryBandwidth
- computeThroughput
- RocmVersion
- rocmVersion
- hipVersion
- kernelVersion
- ErrorResponse
- code
- message
context_file: json-ld/amd-rocm-management-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/advanced-micro-devices/refs/heads/main/json-ld/amd-rocm-management-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amd Rocm Management Api from Advanced Micro Devices.
layout: jsonld
name: Amd Rocm Management Api Context
namespaces:
- prefix: rocm
  uri: https://rocm.docs.amd.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: Advanced Micro Devices
provider_slug: advanced-micro-devices
slug: amd-rocm-management-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"rocm\": \"https://rocm.docs.amd.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Device\": \"rocm:GPUDevice\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"model\": \"rocm:gpuModel\",\n    \"vbios\": \"rocm:vbios\",\n    \"driverVersion\": \"rocm:driverVersion\",\n    \"memoryTotal\": \"rocm:memoryTotal\",\n    \"pcieBusId\": \"rocm:pcieBusId\",\n    \"computeUnits\": \"rocm:computeUnits\",\n    \"DeviceList\": \"rocm:DeviceList\",\n    \"devices\": \"rocm:devices\",\n    \"DeviceHealth\": \"rocm:DeviceHealth\",\n    \"deviceId\": \"rocm:deviceId\",\n    \"status\": \"schema:status\",\n    \"temperature\": \"rocm:temperature\",\n    \"fanSpeed\": \"rocm:fanSpeed\",\n    \"powerDraw\": \"rocm:powerDraw\",\n    \"eccErrors\": \"rocm:eccErrors\",\n    \"DevicePerformance\": \"rocm:DevicePerformance\",\n    \"gpuUtilization\": \"rocm:gpuUtilization\"\
  ,\n    \"memoryUtilization\": \"rocm:memoryUtilization\",\n    \"memoryBandwidth\": \"rocm:memoryBandwidth\",\n    \"computeThroughput\": \"rocm:computeThroughput\",\n    \"RocmVersion\": \"rocm:RocmVersion\",\n    \"rocmVersion\": \"rocm:rocmVersion\",\n    \"hipVersion\": \"rocm:hipVersion\",\n    \"kernelVersion\": \"rocm:kernelVersion\",\n    \"ErrorResponse\": \"rocm:ErrorResponse\",\n    \"code\": \"rocm:errorCode\",\n    \"message\": \"schema:description\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/advanced-micro-devices/refs/heads/main/json-ld/amd-rocm-management-api-context.jsonld
tags:
- AI
- Cloud Computing
- GPU
- HPC
- Machine Learning
- Semiconductor
- JSON-LD
- Linked Data
- Semantic Web
---
