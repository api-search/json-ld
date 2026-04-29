---
class_count: 7
classes:
- AnnouncementNotification
- CertificateExpiryNotification
- DataplaneUpgradeNotification
- IncidentDetail
- IncidentNotification
- ServiceInfo
- TenantContext
context_file: json-ld/palo-alto-sase-notifications-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-notifications-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Sase Notifications from Palo Alto Networks.
layout: jsonld
name: Palo Alto Sase Notifications Context
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
- container: set
  name: affectedResources
  type: reference
- container: set
  name: affectedServices
  type: string
- container: ''
  name: body
  type: string
- container: ''
  name: callbackUrl
  type: reference
- container: ''
  name: category
  type: string
- container: ''
  name: certificateName
  type: string
- container: ''
  name: currentVersion
  type: string
- container: ''
  name: daysUntilExpiry
  type: integer
- container: ''
  name: description
  type: string
- container: ''
  name: detectionSource
  type: string
- container: ''
  name: effectiveDate
  type: dateTime
- container: ''
  name: estimatedEndTime
  type: dateTime
- container: ''
  name: expirationDate
  type: dateTime
- container: ''
  name: incidentId
  type: string
- container: ''
  name: issuer
  type: string
- container: ''
  name: notificationId
  type: string
- container: ''
  name: parentTsgId
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: resourceId
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: scheduledTime
  type: dateTime
- container: ''
  name: serialNumber
  type: string
- container: ''
  name: serviceName
  type: string
- container: ''
  name: serviceStatus
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: targetVersion
  type: string
- container: ''
  name: tenantName
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: title
  type: string
- container: ''
  name: tsgId
  type: string
- container: ''
  name: type
  type: string
- container: set
  name: usedBy
  type: string
property_count: 34
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-sase-notifications-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AnnouncementNotification\": \"pan:AnnouncementNotification\",\n    \"CertificateExpiryNotification\": \"pan:CertificateExpiryNotification\",\n    \"DataplaneUpgradeNotification\": \"pan:DataplaneUpgradeNotification\",\n    \"IncidentDetail\": \"pan:IncidentDetail\",\n    \"IncidentNotification\": \"pan:IncidentNotification\",\n    \"ServiceInfo\": \"pan:ServiceInfo\",\n    \"TenantContext\": \"pan:TenantContext\",\n    \"affectedResources\": {\n      \"@id\": \"pan:affectedResources\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"affectedServices\": {\n      \"@id\": \"pan:affectedServices\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"body\": {\n      \"@id\": \"pan:body\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"callbackUrl\": {\n      \"@id\": \"pan:callbackUrl\",\n      \"@type\": \"@id\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateName\": {\n      \"@id\": \"pan:certificateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentVersion\": {\n      \"@id\": \"pan:currentVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"daysUntilExpiry\": {\n      \"@id\": \"pan:daysUntilExpiry\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectionSource\": {\n      \"@id\": \"pan:detectionSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"pan:effectiveDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"estimatedEndTime\": {\n      \"@id\": \"pan:estimatedEndTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\
  \    \"expirationDate\": {\n      \"@id\": \"pan:expirationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"incidentId\": {\n      \"@id\": \"pan:incidentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuer\": {\n      \"@id\": \"pan:issuer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notificationId\": {\n      \"@id\": \"pan:notificationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentTsgId\": {\n      \"@id\": \"pan:parentTsgId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"pan:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceId\": {\n      \"@id\": \"pan:resourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"pan:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledTime\": {\n      \"@id\": \"pan:scheduledTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"serialNumber\": {\n      \"@id\": \"pan:serialNumber\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"serviceName\": {\n      \"@id\": \"pan:serviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceStatus\": {\n      \"@id\": \"pan:serviceStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"pan:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetVersion\": {\n      \"@id\": \"pan:targetVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenantName\": {\n      \"@id\": \"pan:tenantName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"pan:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"title\": {\n      \"@id\": \"pan:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tsgId\": {\n      \"@id\": \"pan:tsg_id\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usedBy\": {\n      \"@id\": \"pan:usedBy\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-notifications-context.jsonld
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
