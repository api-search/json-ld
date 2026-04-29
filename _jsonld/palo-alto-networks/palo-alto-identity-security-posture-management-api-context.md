---
class_count: 19
classes:
- CreateTicketRequest
- DownloadCsvRequest
- FeatureState
- IdpInfo
- ListResponseIdpInfo
- ListResponseMapStringObject
- ListResponseMfaActivity
- ListResponseSaaSAccount
- ListResponseSaaSActivity
- ListResponseSaaSInstanceInfo
- ListResponseTicket
- MfaActivity
- MfaActivityCountByAppType
- RemediationRequest
- SaaSAccount
- SaaSActivity
- SaaSInstanceInfo
- Ticket
- UnlinkTicketRequest
context_file: json-ld/palo-alto-identity-security-posture-management-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-identity-security-posture-management-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Identity Security Posture Management Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Identity Security Posture Management Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accountName
  type: string
- container: ''
  name: accountType
  type: string
- container: ''
  name: activityDateTime
  type: dateTime
- container: ''
  name: activityType
  type: string
- container: ''
  name: admin
  type: boolean
- container: ''
  name: appId
  type: string
- container: ''
  name: appType
  type: string
- container: ''
  name: clientIP
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: createdTime
  type: dateTime
- container: ''
  name: creator
  type: string
- container: ''
  name: credentialsExpiresAt
  type: dateTime
- container: ''
  name: description
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: feature
  type: string
- container: ''
  name: fullName
  type: string
- container: ''
  name: githubOrgName
  type: string
- container: ''
  name: iconAppType
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: idpId
  type: string
- container: ''
  name: idpType
  type: string
- container: ''
  name: integrationId
  type: string
- container: ''
  name: ipAddress
  type: string
- container: ''
  name: isElevated
  type: boolean
- container: ''
  name: isLocal
  type: boolean
- container: ''
  name: isNonHuman
  type: boolean
- container: ''
  name: isOrphaned
  type: boolean
- container: ''
  name: issueTypeId
  type: string
- container: set
  name: items
  type: reference
- container: ''
  name: jobId
  type: string
- container: ''
  name: lastCredentialsRotated
  type: dateTime
- container: ''
  name: lastLoginTime
  type: dateTime
- container: ''
  name: lastModifiedTime
  type: dateTime
- container: ''
  name: lastScannedAt
  type: dateTime
- container: ''
  name: latestScanTime
  type: dateTime
- container: ''
  name: linkedHumanAccounts
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: mfaFactors
  type: string
- container: ''
  name: mfaStrength
  type: string
- container: ''
  name: rawData
  type: string
- container: set
  name: resourceIds
  type: string
- container: ''
  name: resourceName
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: roles
  type: string
- container: ''
  name: rotatedBy
  type: string
- container: ''
  name: saasInstanceId
  type: string
- container: ''
  name: saasProviderId
  type: string
- container: ''
  name: saasProviderMfaType
  type: string
- container: ''
  name: saasProviderNhiName
  type: string
- container: ''
  name: service
  type: string
- container: ''
  name: settings
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: tenant
  type: string
- container: ''
  name: ticketKey
  type: string
- container: ''
  name: ticketUrl
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: total
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: userAgent
  type: string
- container: ''
  name: userEmail
  type: string
- container: ''
  name: userFullName
  type: string
- container: ''
  name: userId
  type: string
- container: ''
  name: users
  type: string
property_count: 66
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-identity-security-posture-management-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateTicketRequest\": \"pan:CreateTicketRequest\",\n    \"DownloadCsvRequest\": \"pan:DownloadCsvRequest\",\n    \"FeatureState\": \"pan:FeatureState\",\n    \"IdpInfo\": \"pan:IdpInfo\",\n    \"ListResponseIdpInfo\": \"pan:ListResponseIdpInfo\",\n    \"ListResponseMapStringObject\": \"pan:ListResponseMapStringObject\",\n    \"ListResponseMfaActivity\": \"pan:ListResponseMfaActivity\",\n    \"ListResponseSaaSAccount\": \"pan:ListResponseSaaSAccount\",\n    \"ListResponseSaaSActivity\": \"pan:ListResponseSaaSActivity\",\n    \"ListResponseSaaSInstanceInfo\": \"pan:ListResponseSaaSInstanceInfo\",\n    \"ListResponseTicket\": \"pan:ListResponseTicket\",\n    \"MfaActivity\": \"pan:MfaActivity\",\n    \"MfaActivityCountByAppType\": \"pan:MfaActivityCountByAppType\"\
  ,\n    \"RemediationRequest\": \"pan:RemediationRequest\",\n    \"SaaSAccount\": \"pan:SaaSAccount\",\n    \"SaaSActivity\": \"pan:SaaSActivity\",\n    \"SaaSInstanceInfo\": \"pan:SaaSInstanceInfo\",\n    \"Ticket\": \"pan:Ticket\",\n    \"UnlinkTicketRequest\": \"pan:UnlinkTicketRequest\",\n    \"accountName\": {\n      \"@id\": \"pan:accountName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountType\": {\n      \"@id\": \"pan:accountType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activityDateTime\": {\n      \"@id\": \"pan:activityDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"activityType\": {\n      \"@id\": \"pan:activityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"admin\": {\n      \"@id\": \"pan:admin\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"appId\": {\n      \"@id\": \"pan:appId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appType\": {\n      \"@id\": \"pan:appType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientIP\"\
  : {\n      \"@id\": \"pan:clientIP\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"pan:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"pan:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdTime\": {\n      \"@id\": \"pan:createdTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"creator\": {\n      \"@id\": \"pan:creator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"credentialsExpiresAt\": {\n      \"@id\": \"pan:credentialsExpiresAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"pan:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"feature\": {\n      \"@id\": \"pan:feature\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fullName\"\
  : {\n      \"@id\": \"pan:fullName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"githubOrgName\": {\n      \"@id\": \"pan:githubOrgName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iconAppType\": {\n      \"@id\": \"pan:iconAppType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idpId\": {\n      \"@id\": \"pan:idpId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idpType\": {\n      \"@id\": \"pan:idpType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"integrationId\": {\n      \"@id\": \"pan:integrationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipAddress\": {\n      \"@id\": \"pan:ipAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isElevated\": {\n      \"@id\": \"pan:isElevated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isLocal\": {\n      \"@id\": \"pan:isLocal\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isNonHuman\": {\n      \"@id\": \"pan:isNonHuman\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isOrphaned\": {\n      \"@id\": \"pan:isOrphaned\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"issueTypeId\": {\n      \"@id\": \"pan:issueTypeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"pan:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"jobId\": {\n      \"@id\": \"pan:jobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastCredentialsRotated\": {\n      \"@id\": \"pan:lastCredentialsRotated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastLoginTime\": {\n      \"@id\": \"pan:lastLoginTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastModifiedTime\": {\n      \"@id\": \"pan:lastModifiedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastScannedAt\": {\n      \"@id\": \"pan:lastScannedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"latestScanTime\": {\n      \"@id\": \"pan:latestScanTime\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"linkedHumanAccounts\": {\n      \"@id\": \"pan:linkedHumanAccounts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"pan:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mfaFactors\": {\n      \"@id\": \"pan:mfaFactors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mfaStrength\": {\n      \"@id\": \"pan:mfaStrength\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rawData\": {\n      \"@id\": \"pan:rawData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceIds\": {\n      \"@id\": \"pan:resourceIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceName\": {\n      \"@id\": \"pan:resourceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"pan:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roles\": {\n      \"@id\": \"pan:roles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rotatedBy\": {\n      \"@id\": \"pan:rotatedBy\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"saasInstanceId\": {\n      \"@id\": \"pan:saasInstanceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"saasProviderId\": {\n      \"@id\": \"pan:saasProviderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"saasProviderMfaType\": {\n      \"@id\": \"pan:saasProviderMfaType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"saasProviderNhiName\": {\n      \"@id\": \"pan:saasProviderNhiName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"pan:service\",\n      \"@type\": \"xsd:string\"\n    },\n    \"settings\": {\n      \"@id\": \"pan:settings\",\n      \"@type\": \"@id\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"pan:summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenant\": {\n      \"@id\": \"pan:tenant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ticketKey\": {\n      \"@id\": \"pan:ticketKey\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ticketUrl\": {\n      \"@id\": \"pan:ticketUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"pan:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"total\": {\n      \"@id\": \"pan:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userAgent\": {\n      \"@id\": \"pan:userAgent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userEmail\": {\n      \"@id\": \"pan:userEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userFullName\": {\n      \"@id\": \"pan:userFullName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userId\": {\n      \"@id\": \"pan:userId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"users\": {\n      \"@id\": \"pan:users\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-identity-security-posture-management-api-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
