---
api_specs:
- filename: amazon-control-tower-openapi.yml
  format: yaml
  label: AWS Control Tower API
  slug: aws-control-tower-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-control-tower/refs/heads/main/openapi/amazon-control-tower-openapi.yml
class_count: 46
classes:
- LandingZoneSummary
- GetLandingZoneResponse
- GetControlOperationResponse
- Baseline
- ResetEnabledBaselineResponse
- EnabledControlParameter
- BaselineOperation
- EnableControlResponse
- CreateLandingZoneRequest
- EnabledBaselineSummary
- LandingZone
- ControlOperation
- DisableBaselineResponse
- ResetEnabledControlResponse
- ControlOperationSummary
- EnabledBaselineParameter
- GetEnabledControlResponse
- DeleteLandingZoneResponse
- CreateLandingZoneResponse
- UpdateEnabledControlResponse
- ListLandingZonesResponse
- ResetLandingZoneResponse
- GetEnabledBaselineResponse
- EnabledControl
- UpdateEnabledBaselineResponse
- ListLandingZoneOperationsResponse
- LandingZoneOperationSummary
- ListBaselinesResponse
- ListEnabledControlsResponse
- UpdateLandingZoneResponse
- EnabledBaseline
- UpdateLandingZoneRequest
- EnableBaselineRequest
- GetLandingZoneOperationResponse
- ListEnabledBaselinesResponse
- DisableControlResponse
- EnabledControlSummary
- EnableBaselineResponse
- LandingZoneOperationDetail
- ListControlOperationsResponse
- GetBaselineOperationResponse
- EnableControlRequest
- GetBaselineResponse
- description
- name
- version
context_file: json-ld/amazon-control-tower-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-control-tower/refs/heads/main/json-ld/amazon-control-tower-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Control Tower from Amazon Control Tower.
layout: jsonld
name: Amazon Control Tower Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/controltower/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: arn
  type: string
- container: ''
  name: baselineIdentifier
  type: string
- container: ''
  name: baselineOperation
  type: string
- container: ''
  name: baselineVersion
  type: string
- container: set
  name: baselines
  type: string
- container: ''
  name: controlIdentifier
  type: string
- container: ''
  name: controlOperation
  type: string
- container: set
  name: controlOperations
  type: string
- container: ''
  name: driftStatus
  type: reference
- container: ''
  name: driftStatusSummary
  type: reference
- container: ''
  name: enabledBaselineDetails
  type: string
- container: set
  name: enabledBaselines
  type: string
- container: ''
  name: enabledControl
  type: string
- container: ''
  name: enabledControlIdentifier
  type: string
- container: set
  name: enabledControls
  type: string
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: key
  type: string
- container: ''
  name: landingZone
  type: string
- container: ''
  name: landingZoneIdentifier
  type: string
- container: set
  name: landingZoneOperations
  type: string
- container: set
  name: landingZones
  type: string
- container: ''
  name: lastOperationIdentifier
  type: string
- container: ''
  name: latestAvailableVersion
  type: string
- container: ''
  name: manifest
  type: reference
- container: ''
  name: nextToken
  type: string
- container: ''
  name: operationDetails
  type: string
- container: ''
  name: operationIdentifier
  type: string
- container: ''
  name: operationType
  type: string
- container: set
  name: parameters
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: statusMessage
  type: string
- container: ''
  name: statusSummary
  type: reference
- container: ''
  name: tags
  type: reference
- container: ''
  name: targetIdentifier
  type: string
- container: ''
  name: value
  type: string
property_count: 36
provider_name: Amazon Control Tower
provider_slug: amazon-control-tower
slug: amazon-control-tower-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/controltower/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LandingZoneSummary\": \"aws:LandingZoneSummary\",\n    \"GetLandingZoneResponse\": \"aws:GetLandingZoneResponse\",\n    \"GetControlOperationResponse\": \"aws:GetControlOperationResponse\",\n    \"Baseline\": \"aws:Baseline\",\n    \"ResetEnabledBaselineResponse\": \"aws:ResetEnabledBaselineResponse\",\n    \"EnabledControlParameter\": \"aws:EnabledControlParameter\",\n    \"BaselineOperation\": \"aws:BaselineOperation\",\n    \"EnableControlResponse\": \"aws:EnableControlResponse\",\n    \"CreateLandingZoneRequest\": \"aws:CreateLandingZoneRequest\",\n    \"EnabledBaselineSummary\": \"aws:EnabledBaselineSummary\",\n    \"LandingZone\": \"aws:LandingZone\",\n    \"ControlOperation\": \"aws:ControlOperation\",\n    \"DisableBaselineResponse\"\
  : \"aws:DisableBaselineResponse\",\n    \"ResetEnabledControlResponse\": \"aws:ResetEnabledControlResponse\",\n    \"ControlOperationSummary\": \"aws:ControlOperationSummary\",\n    \"EnabledBaselineParameter\": \"aws:EnabledBaselineParameter\",\n    \"GetEnabledControlResponse\": \"aws:GetEnabledControlResponse\",\n    \"DeleteLandingZoneResponse\": \"aws:DeleteLandingZoneResponse\",\n    \"CreateLandingZoneResponse\": \"aws:CreateLandingZoneResponse\",\n    \"UpdateEnabledControlResponse\": \"aws:UpdateEnabledControlResponse\",\n    \"ListLandingZonesResponse\": \"aws:ListLandingZonesResponse\",\n    \"ResetLandingZoneResponse\": \"aws:ResetLandingZoneResponse\",\n    \"GetEnabledBaselineResponse\": \"aws:GetEnabledBaselineResponse\",\n    \"EnabledControl\": \"aws:EnabledControl\",\n    \"UpdateEnabledBaselineResponse\": \"aws:UpdateEnabledBaselineResponse\",\n    \"ListLandingZoneOperationsResponse\": \"aws:ListLandingZoneOperationsResponse\",\n    \"LandingZoneOperationSummary\":\
  \ \"aws:LandingZoneOperationSummary\",\n    \"ListBaselinesResponse\": \"aws:ListBaselinesResponse\",\n    \"ListEnabledControlsResponse\": \"aws:ListEnabledControlsResponse\",\n    \"UpdateLandingZoneResponse\": \"aws:UpdateLandingZoneResponse\",\n    \"EnabledBaseline\": \"aws:EnabledBaseline\",\n    \"UpdateLandingZoneRequest\": \"aws:UpdateLandingZoneRequest\",\n    \"EnableBaselineRequest\": \"aws:EnableBaselineRequest\",\n    \"GetLandingZoneOperationResponse\": \"aws:GetLandingZoneOperationResponse\",\n    \"ListEnabledBaselinesResponse\": \"aws:ListEnabledBaselinesResponse\",\n    \"DisableControlResponse\": \"aws:DisableControlResponse\",\n    \"EnabledControlSummary\": \"aws:EnabledControlSummary\",\n    \"EnableBaselineResponse\": \"aws:EnableBaselineResponse\",\n    \"LandingZoneOperationDetail\": \"aws:LandingZoneOperationDetail\",\n    \"ListControlOperationsResponse\": \"aws:ListControlOperationsResponse\",\n    \"GetBaselineOperationResponse\": \"aws:GetBaselineOperationResponse\"\
  ,\n    \"EnableControlRequest\": \"aws:EnableControlRequest\",\n    \"GetBaselineResponse\": \"aws:GetBaselineResponse\",\n    \"arn\": {\n      \"@id\": \"aws:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baselineIdentifier\": {\n      \"@id\": \"aws:baseline_identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baselineOperation\": {\n      \"@id\": \"aws:baseline_operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baselineVersion\": {\n      \"@id\": \"aws:baseline_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baselines\": {\n      \"@id\": \"aws:baselines\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"controlIdentifier\": {\n      \"@id\": \"aws:control_identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"controlOperation\": {\n      \"@id\": \"aws:control_operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"controlOperations\": {\n      \"@id\": \"aws:control_operations\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"driftStatus\": {\n      \"@id\": \"aws:drift_status\",\n      \"@type\": \"@id\"\n    },\n    \"driftStatusSummary\": {\n      \"@id\": \"aws:drift_status_summary\",\n      \"@type\": \"@id\"\n    },\n    \"enabledBaselineDetails\": {\n      \"@id\": \"aws:enabled_baseline_details\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabledBaselines\": {\n      \"@id\": \"aws:enabled_baselines\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabledControl\": {\n      \"@id\": \"aws:enabled_control\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabledControlIdentifier\": {\n      \"@id\": \"aws:enabled_control_identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabledControls\": {\n      \"@id\": \"aws:enabled_controls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"\
  aws:end_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"key\": {\n      \"@id\": \"aws:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"landingZone\": {\n      \"@id\": \"aws:landing_zone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"landingZoneIdentifier\": {\n      \"@id\": \"aws:landing_zone_identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"landingZoneOperations\": {\n      \"@id\": \"aws:landing_zone_operations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"landingZones\": {\n      \"@id\": \"aws:landing_zones\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastOperationIdentifier\": {\n      \"@id\": \"aws:last_operation_identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latestAvailableVersion\": {\n      \"@id\": \"aws:latest_available_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manifest\": {\n      \"@id\": \"aws:manifest\",\n      \"@type\": \"@id\"\
  \n    },\n    \"name\": \"schema:name\",\n    \"nextToken\": {\n      \"@id\": \"aws:next_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operationDetails\": {\n      \"@id\": \"aws:operation_details\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operationIdentifier\": {\n      \"@id\": \"aws:operation_identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operationType\": {\n      \"@id\": \"aws:operation_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"aws:parameters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"aws:start_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusMessage\": {\n      \"@id\": \"aws:status_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusSummary\": {\n      \"@id\": \"aws:status_summary\",\n      \"@type\": \"@id\"\
  \n    },\n    \"tags\": {\n      \"@id\": \"aws:tags\",\n      \"@type\": \"@id\"\n    },\n    \"targetIdentifier\": {\n      \"@id\": \"aws:target_identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"aws:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-control-tower/refs/heads/main/json-ld/amazon-control-tower-context.jsonld
tags:
- AWS
- Compliance
- Governance
- Landing Zone
- Multi-Account
- Security
- Controls
- JSON-LD
- Linked Data
- Semantic Web
---
