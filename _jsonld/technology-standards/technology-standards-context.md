---
class_count: 44
classes:
- Standard
- standardId
- standardName
- standardDescription
- standardNumber
- standardStatus
- standardUrl
- StandardsBody
- bodyName
- bodyAcronym
- bodyUrl
- bodyMission
- WorkingGroup
- groupName
- groupCharter
- parentBody
- RFC
- rfcNumber
- rfcTitle
- rfcAuthors
- rfcDate
- rfcStatus
- rfcUrl
- obsoletes
- updatedBy
- Protocol
- protocolName
- protocolPort
- protocolScheme
- protocolRfc
- protocolVersion
- SecurityStandard
- securityStandardName
- authorizationFlows
- tokenTypes
- scopes
- Conformance
- conformanceLevel
- requirement
- requirementKeyword
- Implementation
- implementationName
- implementationType
- implementationLanguage
context_file: json-ld/technology-standards-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/technology-standards/refs/heads/main/json-ld/technology-standards-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Technology Standards from Technology Standards.
layout: jsonld
name: Technology Standards Context
namespaces:
- prefix: std
  uri: https://raw.githubusercontent.com/api-evangelist/technology-standards/main/json-ld/technology-standards-context.jsonld#
- prefix: schema
  uri: https://schema.org/
properties: []
property_count: 0
provider_name: Technology Standards
provider_slug: technology-standards
slug: technology-standards-context
source_filename: technology-standards-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"std\": \"https://raw.githubusercontent.com/api-evangelist/technology-standards/main/json-ld/technology-standards-context.jsonld#\",\n    \"schema\": \"https://schema.org/\",\n\n    \"Standard\": \"schema:TechArticle\",\n    \"standardId\": \"schema:identifier\",\n    \"standardName\": \"schema:name\",\n    \"standardDescription\": \"schema:description\",\n    \"standardNumber\": \"schema:legislationIdentifier\",\n    \"standardStatus\": \"std:status\",\n    \"standardUrl\": \"schema:url\",\n\n    \"StandardsBody\": \"schema:Organization\",\n    \"bodyName\": \"schema:name\",\n    \"bodyAcronym\": \"schema:alternateName\",\n    \"bodyUrl\": \"schema:url\",\n    \"bodyMission\": \"schema:description\",\n\n    \"WorkingGroup\": \"schema:Organization\",\n    \"groupName\": \"schema:name\",\n    \"groupCharter\": \"schema:description\",\n    \"parentBody\": \"schema:parentOrganization\",\n\n    \"RFC\": \"std:RFC\"\
  ,\n    \"rfcNumber\": \"schema:identifier\",\n    \"rfcTitle\": \"schema:name\",\n    \"rfcAuthors\": \"schema:author\",\n    \"rfcDate\": \"schema:datePublished\",\n    \"rfcStatus\": \"std:rfcStatus\",\n    \"rfcUrl\": \"schema:url\",\n    \"obsoletes\": \"std:obsoletes\",\n    \"updatedBy\": \"std:updatedBy\",\n\n    \"Protocol\": \"std:Protocol\",\n    \"protocolName\": \"schema:name\",\n    \"protocolPort\": \"std:port\",\n    \"protocolScheme\": \"std:scheme\",\n    \"protocolRfc\": \"std:rfc\",\n    \"protocolVersion\": \"schema:version\",\n\n    \"SecurityStandard\": \"std:SecurityStandard\",\n    \"securityStandardName\": \"schema:name\",\n    \"authorizationFlows\": \"std:authorizationFlows\",\n    \"tokenTypes\": \"std:tokenTypes\",\n    \"scopes\": \"std:scopes\",\n\n    \"Conformance\": \"std:Conformance\",\n    \"conformanceLevel\": \"std:level\",\n    \"requirement\": \"std:requirement\",\n    \"requirementKeyword\": \"std:keyword\",\n\n    \"Implementation\": \"schema:SoftwareApplication\"\
  ,\n    \"implementationName\": \"schema:name\",\n    \"implementationType\": \"std:implementationType\",\n    \"implementationLanguage\": \"schema:programmingLanguage\",\n    \"conformanceLevel\": \"std:conformanceLevel\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/technology-standards/refs/heads/main/json-ld/technology-standards-context.jsonld
tags:
- IEEE
- IETF
- ISO
- Protocols
- Standards
- Technology Standards
- W3C
- JSON-LD
- Linked Data
- Semantic Web
---
