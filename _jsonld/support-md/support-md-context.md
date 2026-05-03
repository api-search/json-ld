---
class_count: 0
classes: []
context_file: json-ld/support-md-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/support-md/refs/heads/main/json-ld/support-md-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Support Md from SUPPORT.md.
layout: jsonld
name: Support Md Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: github
  uri: https://docs.github.com/en/communities/
- prefix: support
  uri: https://api-evangelist.github.io/support-md/vocab#
properties:
- container: ''
  name: SupportFile
  type: reference
- container: ''
  name: CommunityHealthFile
  type: reference
- container: ''
  name: SupportChannel
  type: reference
- container: ''
  name: IssueTracker
  type: reference
- container: ''
  name: DiscussionForum
  type: reference
- container: ''
  name: MailingList
  type: reference
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: url
  type: reference
- container: ''
  name: email
  type: ''
- container: ''
  name: contactPoint
  type: reference
- container: ''
  name: maintainer
  type: reference
- container: ''
  name: contributor
  type: reference
- container: ''
  name: softwareHelp
  type: reference
- container: ''
  name: discussionUrl
  type: reference
- container: ''
  name: issueTracker
  type: reference
- container: ''
  name: license
  type: reference
- container: ''
  name: codeRepository
  type: reference
- container: ''
  name: programmingLanguage
  type: ''
- container: ''
  name: channelType
  type: ''
- container: ''
  name: priority
  type: ''
- container: ''
  name: responseTime
  type: ''
- container: ''
  name: securityContact
  type: ''
- container: ''
  name: codeOfConduct
  type: reference
- container: ''
  name: contributingGuide
  type: reference
- container: ''
  name: healthFile
  type: reference
property_count: 26
provider_name: SUPPORT.md
provider_slug: support-md
slug: support-md-context
source_filename: support-md-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"github\": \"https://docs.github.com/en/communities/\",\n    \"support\": \"https://api-evangelist.github.io/support-md/vocab#\",\n\n    \"SupportFile\": {\n      \"@id\": \"support:SupportFile\",\n      \"@type\": \"@id\"\n    },\n    \"CommunityHealthFile\": {\n      \"@id\": \"support:CommunityHealthFile\",\n      \"@type\": \"@id\"\n    },\n    \"SupportChannel\": {\n      \"@id\": \"support:SupportChannel\",\n      \"@type\": \"@id\"\n    },\n    \"IssueTracker\": {\n      \"@id\": \"support:IssueTracker\",\n      \"@type\": \"@id\"\n    },\n    \"DiscussionForum\": {\n      \"@id\": \"support:DiscussionForum\",\n      \"@type\": \"@id\"\n    },\n    \"MailingList\": {\n      \"@id\": \"support:MailingList\",\n      \"@type\": \"@id\"\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"\
  url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\"\n    },\n    \"contactPoint\": {\n      \"@id\": \"schema:contactPoint\",\n      \"@type\": \"@id\"\n    },\n    \"maintainer\": {\n      \"@id\": \"schema:maintainer\",\n      \"@type\": \"@id\"\n    },\n    \"contributor\": {\n      \"@id\": \"schema:contributor\",\n      \"@type\": \"@id\"\n    },\n    \"softwareHelp\": {\n      \"@id\": \"schema:softwareHelp\",\n      \"@type\": \"@id\"\n    },\n    \"discussionUrl\": {\n      \"@id\": \"schema:discussionUrl\",\n      \"@type\": \"@id\"\n    },\n    \"issueTracker\": {\n      \"@id\": \"schema:issueTracker\",\n      \"@type\": \"@id\"\n    },\n    \"license\": {\n      \"@id\": \"schema:license\",\n      \"@type\": \"@id\"\n    },\n    \"codeRepository\": {\n      \"@id\": \"schema:codeRepository\",\n      \"@type\": \"@id\"\n    },\n    \"programmingLanguage\": {\n      \"@id\": \"schema:programmingLanguage\"\
  \n    },\n\n    \"channelType\": {\n      \"@id\": \"support:channelType\"\n    },\n    \"priority\": {\n      \"@id\": \"support:priority\"\n    },\n    \"responseTime\": {\n      \"@id\": \"support:responseTime\"\n    },\n    \"securityContact\": {\n      \"@id\": \"support:securityContact\"\n    },\n    \"codeOfConduct\": {\n      \"@id\": \"support:codeOfConduct\",\n      \"@type\": \"@id\"\n    },\n    \"contributingGuide\": {\n      \"@id\": \"support:contributingGuide\",\n      \"@type\": \"@id\"\n    },\n    \"healthFile\": {\n      \"@id\": \"support:healthFile\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/support-md/refs/heads/main/json-ld/support-md-context.jsonld
tags:
- Community
- Documentation
- GitHub
- Open Source
- Repository
- Support
- JSON-LD
- Linked Data
- Semantic Web
---
