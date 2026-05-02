---
api_specs:
- filename: overview
  format: yaml
  label: Microsoft Graph API
  slug: ''
  spec_type: OpenAPI
  url: https://learn.microsoft.com/en-us/graph/api/overview
- filename: microsoft-azure-rest-openapi.yml
  format: yaml
  label: Azure REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/openapi/microsoft-azure-rest-openapi.yml
- filename: microsoft-azure-openai-openapi.yml
  format: yaml
  label: Azure OpenAI Service API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/openapi/microsoft-azure-openai-openapi.yml
- filename: microsoft-azure-cognitive-services-openapi.yml
  format: yaml
  label: Azure Cognitive Services API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/openapi/microsoft-azure-cognitive-services-openapi.yml
- filename: microsoft-teams-openapi.yml
  format: yaml
  label: Microsoft Teams API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/openapi/microsoft-teams-openapi.yml
- filename: microsoft-onedrive-openapi.yml
  format: yaml
  label: OneDrive API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/openapi/microsoft-onedrive-openapi.yml
- filename: microsoft-power-platform-openapi.yml
  format: yaml
  label: Power Platform API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/openapi/microsoft-power-platform-openapi.yml
- filename: microsoft-bing-search-openapi.yml
  format: yaml
  label: Bing Search APIs
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/openapi/microsoft-bing-search-openapi.yml
- filename: microsoft-sharepoint-openapi.yml
  format: yaml
  label: SharePoint REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/openapi/microsoft-sharepoint-openapi.yml
- filename: microsoft-power-bi-openapi.yml
  format: yaml
  label: Power BI REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/openapi/microsoft-power-bi-openapi.yml
- filename: microsoft-azure-devops-openapi.yml
  format: yaml
  label: Azure DevOps REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/openapi/microsoft-azure-devops-openapi.yml
- filename: microsoft-dynamics-365-openapi.yml
  format: yaml
  label: Dynamics 365 REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/openapi/microsoft-dynamics-365-openapi.yml
- filename: microsoft-linkedin-openapi.yml
  format: yaml
  label: LinkedIn API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/openapi/microsoft-linkedin-openapi.yml
- filename: microsoft-azure-communication-services-openapi.yml
  format: yaml
  label: Azure Communication Services API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/openapi/microsoft-azure-communication-services-openapi.yml
- filename: microsoft-entra-id-openapi.yml
  format: yaml
  label: Microsoft Entra ID API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/openapi/microsoft-entra-id-openapi.yml
- filename: microsoft-outlook-openapi.yml
  format: yaml
  label: Microsoft Outlook API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/openapi/microsoft-outlook-openapi.yml
- filename: microsoft-intune-openapi.yml
  format: yaml
  label: Microsoft Intune API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/openapi/microsoft-intune-openapi.yml
class_count: 0
classes: []
context_file: json-ld/microsoft-graph-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/json-ld/microsoft-graph-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Graph from Microsoft.
layout: jsonld
name: Microsoft Graph Context
namespaces:
- prefix: msgraph
  uri: https://graph.microsoft.com/v1.0/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
properties:
- container: ''
  name: User
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: DriveItem
  type: ''
- container: ''
  name: Team
  type: ''
- container: ''
  name: Channel
  type: ''
- container: ''
  name: Application
  type: ''
property_count: 8
provider_name: Microsoft
provider_slug: microsoft
slug: microsoft-graph-context
source_filename: microsoft-graph-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"msgraph\": \"https://graph.microsoft.com/v1.0/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n\n    \"User\": {\n      \"@id\": \"msgraph:User\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"givenName\": \"schema:givenName\",\n        \"surname\": \"schema:familyName\",\n        \"mail\": \"schema:email\",\n        \"userPrincipalName\": \"msgraph:userPrincipalName\",\n        \"jobTitle\": \"schema:jobTitle\",\n        \"department\": \"msgraph:department\",\n        \"officeLocation\": \"schema:workLocation\",\n        \"companyName\": \"schema:worksFor\",\n        \"businessPhones\": \"schema:telephone\",\n        \"mobilePhone\": \"vcard:cell\",\n        \"city\": \"vcard:locality\",\n        \"state\": \"vcard:region\",\n        \"country\"\
  : \"vcard:country-name\",\n        \"postalCode\": \"vcard:postal-code\",\n        \"streetAddress\": \"vcard:street-address\",\n        \"employeeId\": \"msgraph:employeeId\",\n        \"employeeType\": \"msgraph:employeeType\",\n        \"accountEnabled\": {\n          \"@id\": \"msgraph:accountEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastPasswordChangeDateTime\": {\n          \"@id\": \"msgraph:lastPasswordChangeDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"msgraph:Group\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"mail\": \"schema:email\",\n        \"mailEnabled\": {\n          \"@id\": \"msgraph:mailEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"mailNickname\"\
  : \"msgraph:mailNickname\",\n        \"securityEnabled\": {\n          \"@id\": \"msgraph:securityEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"visibility\": \"msgraph:visibility\",\n        \"classification\": \"msgraph:classification\",\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expirationDateTime\": {\n          \"@id\": \"msgraph:expirationDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"isAssignableToRole\": {\n          \"@id\": \"msgraph:isAssignableToRole\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"msgraph:Message\",\n      \"@context\": {\n        \"subject\": \"schema:name\",\n        \"bodyPreview\": \"schema:description\",\n        \"from\": \"schema:sender\",\n        \"toRecipients\": \"schema:recipient\",\n        \"importance\": \"msgraph:importance\",\n        \"isRead\"\
  : {\n          \"@id\": \"msgraph:isRead\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isDraft\": {\n          \"@id\": \"msgraph:isDraft\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"hasAttachments\": {\n          \"@id\": \"msgraph:hasAttachments\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"receivedDateTime\": {\n          \"@id\": \"schema:dateReceived\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"sentDateTime\": {\n          \"@id\": \"schema:dateSent\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"conversationId\": \"msgraph:conversationId\"\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"msgraph:Event\",\n      \"@context\": {\n        \"subject\": \"schema:name\",\n        \"start\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"end\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n      \
  \  },\n        \"location\": \"schema:location\",\n        \"organizer\": \"schema:organizer\",\n        \"attendees\": \"schema:attendee\",\n        \"isAllDay\": {\n          \"@id\": \"msgraph:isAllDay\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isCancelled\": {\n          \"@id\": \"msgraph:isCancelled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"showAs\": \"msgraph:showAs\",\n        \"sensitivity\": \"msgraph:sensitivity\",\n        \"importance\": \"msgraph:importance\",\n        \"isOnlineMeeting\": {\n          \"@id\": \"msgraph:isOnlineMeeting\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DriveItem\": {\n      \"@id\": \"msgraph:DriveItem\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"size\": {\n          \"\
  @id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"webUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedDateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Team\": {\n      \"@id\": \"msgraph:Team\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"visibility\": \"msgraph:visibility\",\n        \"isArchived\": {\n          \"@id\": \"msgraph:isArchived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"webUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\
  \n        }\n      }\n    },\n\n    \"Channel\": {\n      \"@id\": \"msgraph:Channel\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"membershipType\": \"msgraph:membershipType\",\n        \"email\": \"schema:email\",\n        \"webUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Application\": {\n      \"@id\": \"msgraph:Application\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"appId\": \"msgraph:appId\",\n        \"signInAudience\": \"msgraph:signInAudience\",\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/json-ld/microsoft-graph-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
