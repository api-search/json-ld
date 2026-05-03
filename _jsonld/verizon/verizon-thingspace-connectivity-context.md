---
api_specs:
- filename: verizon-thingspace-connectivity-openapi.yml
  format: yaml
  label: Verizon ThingSpace
  slug: thingspace
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/verizon/refs/heads/main/openapi/verizon-thingspace-connectivity-openapi.yml
class_count: 16
classes:
- Feature
- CallbackSummary
- AccountInformation
- DeviceInformation
- SessionLoginRequest
- RegisterCallbackRequest
- DeactivateDevicesRequest
- SendSmsRequest
- ActivateDevicesRequest
- IpPool
- DeviceRequestResponse
- SessionLoginResponse
- DeviceId
- DeviceListRequest
- CarrierInformation
- DeviceListResponse
context_file: json-ld/verizon-thingspace-connectivity-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/verizon/refs/heads/main/json-ld/verizon-thingspace-connectivity-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Verizon Thingspace Connectivity from Verizon.
layout: jsonld
name: Verizon Thingspace Connectivity Context
namespaces:
- prefix: verizon
  uri: https://verizon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: url
  type: string
- container: ''
  name: accountName
  type: string
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: organizationName
  type: string
- container: ''
  name: isProvisioningAllowed
  type: boolean
- container: set
  name: carrierInformation
  type: string
- container: set
  name: features
  type: string
- container: set
  name: ipPools
  type: string
- container: set
  name: deviceIds
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: servicePlan
  type: string
- container: ''
  name: mdn
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: password
  type: string
- container: set
  name: devices
  type: reference
- container: ''
  name: reasonCode
  type: string
- container: ''
  name: etfWaiver
  type: boolean
- container: ''
  name: smsMessage
  type: string
- container: ''
  name: encoding
  type: string
- container: ''
  name: mdnZipCode
  type: string
- container: set
  name: customFields
  type: reference
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: poolName
  type: string
- container: ''
  name: poolType
  type: string
- container: ''
  name: isDefaultPool
  type: boolean
- container: ''
  name: requestId
  type: string
- container: set
  name: failedDevices
  type: reference
- container: ''
  name: deviceId
  type: string
- container: ''
  name: cause
  type: string
- container: ''
  name: sessionToken
  type: string
- container: ''
  name: expiresIn
  type: integer
- container: ''
  name: kind
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: filter
  type: reference
- container: set
  name: servicePlans
  type: string
- container: set
  name: states
  type: string
- container: ''
  name: maxNumberOfDevices
  type: integer
- container: ''
  name: carrierName
  type: string
- container: ''
  name: hasMoreData
  type: boolean
- container: ''
  name: lastSeenDeviceId
  type: string
property_count: 43
provider_name: Verizon
provider_slug: verizon
slug: verizon-thingspace-connectivity-context
source_filename: verizon-thingspace-connectivity-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"verizon\": \"https://verizon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Feature\": \"verizon:Feature\",\n    \"CallbackSummary\": \"verizon:CallbackSummary\",\n    \"AccountInformation\": \"verizon:AccountInformation\",\n    \"DeviceInformation\": \"verizon:DeviceInformation\",\n    \"SessionLoginRequest\": \"verizon:SessionLoginRequest\",\n    \"RegisterCallbackRequest\": \"verizon:RegisterCallbackRequest\",\n    \"DeactivateDevicesRequest\": \"verizon:DeactivateDevicesRequest\",\n    \"SendSmsRequest\": \"verizon:SendSmsRequest\",\n    \"ActivateDevicesRequest\": \"verizon:ActivateDevicesRequest\",\n    \"IpPool\": \"verizon:IpPool\",\n    \"DeviceRequestResponse\": \"verizon:DeviceRequestResponse\",\n    \"SessionLoginResponse\": \"verizon:SessionLoginResponse\",\n    \"DeviceId\": \"verizon:DeviceId\"\
  ,\n    \"DeviceListRequest\": \"verizon:DeviceListRequest\",\n    \"CarrierInformation\": \"verizon:CarrierInformation\",\n    \"DeviceListResponse\": \"verizon:DeviceListResponse\",\n    \"name\": {\n      \"@id\": \"verizon:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"verizon:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"verizon:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountName\": {\n      \"@id\": \"verizon:accountName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountNumber\": {\n      \"@id\": \"verizon:accountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationName\": {\n      \"@id\": \"verizon:organizationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isProvisioningAllowed\": {\n      \"@id\": \"verizon:isProvisioningAllowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"carrierInformation\": {\n      \"@id\": \"verizon:carrierInformation\"\
  ,\n      \"@type\": \"xsd:string\",\n      \"@container\": \"@set\"\n    },\n    \"features\": {\n      \"@id\": \"verizon:features\",\n      \"@type\": \"xsd:string\",\n      \"@container\": \"@set\"\n    },\n    \"ipPools\": {\n      \"@id\": \"verizon:ipPools\",\n      \"@type\": \"xsd:string\",\n      \"@container\": \"@set\"\n    },\n    \"deviceIds\": {\n      \"@id\": \"verizon:deviceIds\",\n      \"@type\": \"xsd:string\",\n      \"@container\": \"@set\"\n    },\n    \"state\": {\n      \"@id\": \"verizon:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"servicePlan\": {\n      \"@id\": \"verizon:servicePlan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mdn\": {\n      \"@id\": \"verizon:mdn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": {\n      \"@id\": \"verizon:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"verizon:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"devices\": {\n      \"@id\"\
  : \"verizon:devices\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"reasonCode\": {\n      \"@id\": \"verizon:reasonCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"etfWaiver\": {\n      \"@id\": \"verizon:etfWaiver\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"smsMessage\": {\n      \"@id\": \"verizon:smsMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encoding\": {\n      \"@id\": \"verizon:encoding\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mdnZipCode\": {\n      \"@id\": \"verizon:mdnZipCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customFields\": {\n      \"@id\": \"verizon:customFields\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"key\": {\n      \"@id\": \"verizon:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"verizon:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"poolName\": {\n      \"@id\": \"verizon:poolName\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"poolType\": {\n      \"@id\": \"verizon:poolType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isDefaultPool\": {\n      \"@id\": \"verizon:isDefaultPool\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"requestId\": {\n      \"@id\": \"verizon:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failedDevices\": {\n      \"@id\": \"verizon:failedDevices\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"deviceId\": {\n      \"@id\": \"verizon:deviceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cause\": {\n      \"@id\": \"verizon:cause\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionToken\": {\n      \"@id\": \"verizon:sessionToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresIn\": {\n      \"@id\": \"verizon:expiresIn\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"kind\": {\n      \"@id\": \"verizon:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\"\
  : \"verizon:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filter\": {\n      \"@id\": \"verizon:filter\",\n      \"@type\": \"@id\"\n    },\n    \"servicePlans\": {\n      \"@id\": \"verizon:servicePlans\",\n      \"@type\": \"xsd:string\",\n      \"@container\": \"@set\"\n    },\n    \"states\": {\n      \"@id\": \"verizon:states\",\n      \"@type\": \"xsd:string\",\n      \"@container\": \"@set\"\n    },\n    \"maxNumberOfDevices\": {\n      \"@id\": \"verizon:maxNumberOfDevices\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"carrierName\": {\n      \"@id\": \"verizon:carrierName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasMoreData\": {\n      \"@id\": \"verizon:hasMoreData\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastSeenDeviceId\": {\n      \"@id\": \"verizon:lastSeenDeviceId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/verizon/refs/heads/main/json-ld/verizon-thingspace-connectivity-context.jsonld
tags:
- Wireless
- Telecommunications
- IoT
- 5G
- Enterprise
- Network APIs
- JSON-LD
- Linked Data
- Semantic Web
---
