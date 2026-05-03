---
api_specs:
- filename: salesforce-experience-cloud-sites-openapi.yml
  format: yaml
  label: Experience Cloud Sites API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-experience-cloud/refs/heads/main/openapi/salesforce-experience-cloud-sites-openapi.yml
- filename: salesforce-experience-cloud-connect-communities-openapi.yml
  format: yaml
  label: Connect REST API (Communities)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-experience-cloud/refs/heads/main/openapi/salesforce-experience-cloud-connect-communities-openapi.yml
- filename: salesforce-experience-cloud-cms-connect-openapi.yml
  format: yaml
  label: CMS Connect API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-experience-cloud/refs/heads/main/openapi/salesforce-experience-cloud-cms-connect-openapi.yml
- filename: salesforce-experience-cloud-rest-api-openapi.yml
  format: yaml
  label: Salesforce REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-experience-cloud/refs/heads/main/openapi/salesforce-experience-cloud-rest-api-openapi.yml
- filename: salesforce-experience-cloud-templates-openapi.yml
  format: yaml
  label: Experience Cloud Templates API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-experience-cloud/refs/heads/main/openapi/salesforce-experience-cloud-templates-openapi.yml
- filename: salesforce-experience-cloud-graphql-openapi.yml
  format: yaml
  label: GraphQL API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-experience-cloud/refs/heads/main/openapi/salesforce-experience-cloud-graphql-openapi.yml
- filename: salesforce-experience-cloud-cms-managed-content-openapi.yml
  format: yaml
  label: CMS Managed Content API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-experience-cloud/refs/heads/main/openapi/salesforce-experience-cloud-cms-managed-content-openapi.yml
- filename: salesforce-experience-cloud-cms-delivery-openapi.yml
  format: yaml
  label: CMS Delivery API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-experience-cloud/refs/heads/main/openapi/salesforce-experience-cloud-cms-delivery-openapi.yml
- filename: salesforce-experience-cloud-user-interface-openapi.yml
  format: yaml
  label: User Interface API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-experience-cloud/refs/heads/main/openapi/salesforce-experience-cloud-user-interface-openapi.yml
class_count: 0
classes: []
context_file: json-ld/salesforce-experience-cloud-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/salesforce-experience-cloud/refs/heads/main/json-ld/salesforce-experience-cloud-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Salesforce Experience Cloud from Salesforce Experience Cloud.
layout: jsonld
name: Salesforce Experience Cloud Context
namespaces:
- prefix: sf
  uri: https://developer.salesforce.com/schemas/experience-cloud/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: sioc
  uri: http://rdfs.org/sioc/ns#
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: hydra
  uri: http://www.w3.org/ns/hydra/core#
- prefix: as
  uri: https://www.w3.org/ns/activitystreams#
properties:
- container: ''
  name: ExperienceCloudSite
  type: ''
- container: ''
  name: ManagedContent
  type: ''
- container: ''
  name: ContentNode
  type: ''
- container: ''
  name: CmsChannel
  type: ''
- container: ''
  name: FeedElement
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: Like
  type: ''
- container: ''
  name: Topic
  type: ''
- container: ''
  name: CommunityUser
  type: ''
- container: ''
  name: SObjectRecord
  type: ''
- container: ''
  name: NavigationMenuItem
  type: ''
- container: ''
  name: Theme
  type: ''
- container: ''
  name: Template
  type: ''
- container: ''
  name: RecordRepresentation
  type: ''
property_count: 14
provider_name: Salesforce Experience Cloud
provider_slug: salesforce-experience-cloud
slug: salesforce-experience-cloud-context
source_filename: salesforce-experience-cloud-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"sf\": \"https://developer.salesforce.com/schemas/experience-cloud/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"sioc\": \"http://rdfs.org/sioc/ns#\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n    \"as\": \"https://www.w3.org/ns/activitystreams#\",\n\n    \"ExperienceCloudSite\": {\n      \"@id\": \"sf:Site\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"url\": \"schema:url\",\n        \"siteUrl\": \"schema:url\",\n        \"loginUrl\": {\n          \"@id\": \"sf:loginUrl\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"schema:serverStatus\",\n        \"templateName\": \"sf:templateName\",\n        \"urlPathPrefix\": \"sf:urlPathPrefix\"\
  ,\n        \"memberVisibilityEnabled\": \"sf:memberVisibilityEnabled\",\n        \"reputationEnabled\": \"sf:reputationEnabled\"\n      }\n    },\n\n    \"ManagedContent\": {\n      \"@id\": \"sf:ManagedContent\",\n      \"@context\": {\n        \"managedContentId\": \"@id\",\n        \"contentKey\": \"dcterms:identifier\",\n        \"title\": \"schema:headline\",\n        \"description\": \"schema:description\",\n        \"type\": \"dcterms:type\",\n        \"typeLabel\": \"schema:additionalType\",\n        \"language\": \"schema:inLanguage\",\n        \"publishedDate\": \"schema:datePublished\",\n        \"status\": \"schema:creativeWorkStatus\",\n        \"contentUrlName\": \"schema:urlTemplate\",\n        \"contentNodes\": \"schema:hasPart\",\n        \"unauthenticatedUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ContentNode\": {\n      \"@id\": \"sf:ContentNode\",\n      \"@context\": {\n        \"nodeType\": \"dcterms:type\"\
  ,\n        \"value\": \"schema:value\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"altText\": \"schema:alternateName\",\n        \"title\": \"schema:name\",\n        \"fileName\": \"schema:name\",\n        \"mimeType\": \"schema:encodingFormat\",\n        \"mediaType\": \"dcterms:format\"\n      }\n    },\n\n    \"CmsChannel\": {\n      \"@id\": \"sf:CmsChannel\",\n      \"@context\": {\n        \"channelId\": \"@id\",\n        \"channelName\": \"schema:name\",\n        \"channelType\": \"dcterms:type\",\n        \"domain\": \"schema:url\",\n        \"domainName\": \"schema:name\"\n      }\n    },\n\n    \"FeedElement\": {\n      \"@id\": \"sf:FeedElement\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"feedElementType\": \"dcterms:type\",\n        \"createdDate\": \"schema:dateCreated\",\n        \"modifiedDate\": \"schema:dateModified\",\n        \"actor\": \"schema:author\",\n        \"parent\": \"schema:isPartOf\"\
  ,\n        \"body\": \"schema:articleBody\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Comment\": {\n      \"@id\": \"as:Note\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"body\": \"schema:text\",\n        \"createdDate\": \"schema:dateCreated\",\n        \"user\": \"schema:author\"\n      }\n    },\n\n    \"Like\": {\n      \"@id\": \"as:Like\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"createdDate\": \"schema:dateCreated\",\n        \"user\": \"as:actor\"\n      }\n    },\n\n    \"Topic\": {\n      \"@id\": \"skos:Concept\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"skos:prefLabel\",\n        \"description\": \"skos:definition\",\n        \"talkingAbout\": \"sf:talkingAbout\"\n      }\n    },\n\n    \"CommunityUser\": {\n      \"@id\": \"sf:CommunityUser\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"username\": \"schema:alternateName\"\
  ,\n        \"name\": \"schema:name\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"displayName\": \"foaf:nick\",\n        \"communityNickname\": \"foaf:nick\",\n        \"email\": \"schema:email\",\n        \"title\": \"schema:jobTitle\",\n        \"companyName\": \"schema:worksFor\",\n        \"photo\": \"schema:image\"\n      }\n    },\n\n    \"SObjectRecord\": {\n      \"@id\": \"sf:SObjectRecord\",\n      \"@context\": {\n        \"Id\": \"@id\",\n        \"Name\": \"schema:name\",\n        \"CreatedDate\": \"schema:dateCreated\",\n        \"LastModifiedDate\": \"schema:dateModified\",\n        \"OwnerId\": \"sf:ownerId\"\n      }\n    },\n\n    \"NavigationMenuItem\": {\n      \"@id\": \"schema:SiteNavigationElement\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"label\": \"schema:name\",\n        \"target\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"position\"\
  : \"schema:position\",\n        \"menuItemType\": \"dcterms:type\",\n        \"subMenu\": \"schema:hasPart\"\n      }\n    },\n\n    \"Theme\": {\n      \"@id\": \"sf:Theme\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"isActive\": \"sf:isActive\",\n        \"themeType\": \"dcterms:type\"\n      }\n    },\n\n    \"Template\": {\n      \"@id\": \"sf:Template\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"label\": \"schema:name\",\n        \"developerName\": \"schema:identifier\",\n        \"description\": \"schema:description\",\n        \"templateCategory\": \"dcterms:type\",\n        \"publisher\": \"schema:publisher\"\n      }\n    },\n\n    \"RecordRepresentation\": {\n      \"@id\": \"sf:RecordRepresentation\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"apiName\": \"dcterms:type\",\n        \"fields\": \"schema:additionalProperty\",\n        \"lastModifiedDate\"\
  : \"schema:dateModified\",\n        \"recordTypeId\": \"sf:recordTypeId\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/salesforce-experience-cloud/refs/heads/main/json-ld/salesforce-experience-cloud-context.jsonld
tags:
- CMS
- Communities
- CRM
- Customer Portal
- Digital Experience
- Experience Cloud
- Partner Portal
- JSON-LD
- Linked Data
- Semantic Web
---
