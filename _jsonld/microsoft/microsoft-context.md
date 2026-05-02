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
context_file: json-ld/microsoft-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/json-ld/microsoft-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft from Microsoft.
layout: jsonld
name: Microsoft Context
namespaces:
- prefix: microsoft
  uri: https://graph.microsoft.com/v1.0/
- prefix: azure
  uri: https://management.azure.com/
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
- container: ''
  name: ResourceGroup
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: ManagedDevice
  type: ''
- container: ''
  name: Dataset
  type: ''
- container: ''
  name: Report
  type: ''
- container: ''
  name: WorkItem
  type: ''
- container: ''
  name: ChatCompletionRequest
  type: ''
property_count: 15
provider_name: Microsoft
provider_slug: microsoft
slug: microsoft-context
source_filename: microsoft-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"microsoft\": \"https://graph.microsoft.com/v1.0/\",\n    \"azure\": \"https://management.azure.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n\n    \"User\": {\n      \"@id\": \"microsoft:User\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"givenName\": \"schema:givenName\",\n        \"surname\": \"schema:familyName\",\n        \"mail\": \"schema:email\",\n        \"userPrincipalName\": \"microsoft:userPrincipalName\",\n        \"jobTitle\": \"schema:jobTitle\",\n        \"department\": \"microsoft:department\",\n        \"officeLocation\": \"schema:workLocation\",\n        \"companyName\": \"schema:worksFor\",\n        \"mobilePhone\": \"vcard:cell\",\n        \"accountEnabled\": {\n          \"@id\": \"microsoft:accountEnabled\",\n\
  \          \"@type\": \"xsd:boolean\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"microsoft:Group\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"mail\": \"schema:email\",\n        \"mailEnabled\": {\n          \"@id\": \"microsoft:mailEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"securityEnabled\": {\n          \"@id\": \"microsoft:securityEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"visibility\": \"microsoft:visibility\",\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"microsoft:Message\",\n      \"@context\": {\n        \"subject\": \"schema:name\",\n        \"bodyPreview\": \"\
  schema:description\",\n        \"from\": \"schema:sender\",\n        \"toRecipients\": \"schema:recipient\",\n        \"importance\": \"microsoft:importance\",\n        \"isRead\": {\n          \"@id\": \"microsoft:isRead\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"receivedDateTime\": {\n          \"@id\": \"schema:dateReceived\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"sentDateTime\": {\n          \"@id\": \"schema:dateSent\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"microsoft:Event\",\n      \"@context\": {\n        \"subject\": \"schema:name\",\n        \"start\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"end\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"location\": \"schema:location\",\n        \"organizer\": \"schema:organizer\",\n        \"attendees\":\
  \ \"schema:attendee\",\n        \"isAllDay\": {\n          \"@id\": \"microsoft:isAllDay\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isCancelled\": {\n          \"@id\": \"microsoft:isCancelled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"DriveItem\": {\n      \"@id\": \"microsoft:DriveItem\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"size\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"webUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedDateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Team\": {\n      \"@id\": \"microsoft:Team\",\n\
  \      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"visibility\": \"microsoft:visibility\",\n        \"isArchived\": {\n          \"@id\": \"microsoft:isArchived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"webUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Channel\": {\n      \"@id\": \"microsoft:Channel\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"membershipType\": \"microsoft:membershipType\",\n        \"webUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Application\": {\n      \"@id\": \"microsoft:Application\",\n      \"@context\": {\n        \"displayName\"\
  : \"schema:name\",\n        \"description\": \"schema:description\",\n        \"appId\": \"microsoft:appId\",\n        \"signInAudience\": \"microsoft:signInAudience\",\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ResourceGroup\": {\n      \"@id\": \"azure:ResourceGroup\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"location\": \"schema:location\",\n        \"tags\": \"microsoft:tags\",\n        \"provisioningState\": \"azure:provisioningState\"\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"azure:Subscription\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"subscriptionId\": \"azure:subscriptionId\",\n        \"state\": \"azure:subscriptionState\",\n        \"tenantId\": \"azure:tenantId\"\n      }\n    },\n\n    \"ManagedDevice\": {\n      \"@id\": \"microsoft:ManagedDevice\",\n      \"@context\": {\n        \"\
  deviceName\": \"schema:name\",\n        \"operatingSystem\": \"microsoft:operatingSystem\",\n        \"osVersion\": \"microsoft:osVersion\",\n        \"complianceState\": \"microsoft:complianceState\",\n        \"model\": \"microsoft:deviceModel\",\n        \"manufacturer\": \"schema:manufacturer\",\n        \"serialNumber\": \"microsoft:serialNumber\",\n        \"userPrincipalName\": \"microsoft:userPrincipalName\",\n        \"isEncrypted\": {\n          \"@id\": \"microsoft:isEncrypted\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"enrolledDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastSyncDateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Dataset\": {\n      \"@id\": \"microsoft:powerbi/Dataset\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"configuredBy\": \"microsoft:configuredBy\",\n  \
  \      \"isRefreshable\": {\n          \"@id\": \"microsoft:isRefreshable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"webUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Report\": {\n      \"@id\": \"microsoft:powerbi/Report\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"webUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"embedUrl\": {\n          \"@id\": \"microsoft:embedUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"WorkItem\": {\n      \"@id\": \"microsoft:devops/WorkItem\",\n      \"@context\": {\n        \"title\": \"schema:name\",\n        \"state\": \"microsoft:workItemState\",\n        \"assignedTo\": \"schema:contributor\",\n        \"description\": \"schema:description\",\n  \
  \      \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ChatCompletionRequest\": {\n      \"@id\": \"microsoft:openai/ChatCompletionRequest\",\n      \"@context\": {\n        \"messages\": \"microsoft:messages\",\n        \"temperature\": {\n          \"@id\": \"microsoft:temperature\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"max_tokens\": {\n          \"@id\": \"microsoft:maxTokens\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft/refs/heads/main/json-ld/microsoft-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
