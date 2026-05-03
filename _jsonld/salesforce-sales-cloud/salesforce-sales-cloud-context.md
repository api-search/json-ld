---
api_specs:
- filename: salesforce-sales-cloud-rest-api-openapi.yml
  format: yaml
  label: Salesforce REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-rest-api-openapi.yml
- filename: salesforce-sales-cloud-bulk-api-openapi.yml
  format: yaml
  label: Bulk API 2.0
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-bulk-api-openapi.yml
- filename: salesforce-sales-cloud-platform-events-api-openapi.yml
  format: yaml
  label: Platform Events API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-platform-events-api-openapi.yml
- filename: salesforce-sales-cloud-analytics-api-openapi.yml
  format: yaml
  label: Analytics REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-analytics-api-openapi.yml
- filename: salesforce-sales-cloud-composite-api-openapi.yml
  format: yaml
  label: Salesforce Composite API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-composite-api-openapi.yml
- filename: salesforce-sales-cloud-graphql-api-openapi.yml
  format: yaml
  label: Salesforce GraphQL API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-graphql-api-openapi.yml
- filename: salesforce-sales-cloud-tooling-api-openapi.yml
  format: yaml
  label: Salesforce Tooling API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-tooling-api-openapi.yml
- filename: salesforce-sales-cloud-change-data-capture-api-openapi.yml
  format: yaml
  label: Salesforce Change Data Capture API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-change-data-capture-api-openapi.yml
- filename: salesforce-sales-cloud-connect-api-openapi.yml
  format: yaml
  label: Salesforce Connect REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-connect-api-openapi.yml
- filename: salesforce-sales-cloud-ui-api-openapi.yml
  format: yaml
  label: Salesforce User Interface API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-ui-api-openapi.yml
- filename: salesforce-sales-cloud-apex-rest-api-openapi.yml
  format: yaml
  label: Salesforce Apex REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-apex-rest-api-openapi.yml
class_count: 2
classes:
- IsDeleted
- OwnerId
context_file: json-ld/salesforce-sales-cloud-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/json-ld/salesforce-sales-cloud-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Salesforce Sales Cloud from Salesforce Sales Cloud.
layout: jsonld
name: Salesforce Sales Cloud Context
namespaces:
- prefix: sf
  uri: https://developer.salesforce.com/schemas/sales-cloud/
- prefix: schema
  uri: https://schema.org/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
- prefix: org
  uri: http://www.w3.org/ns/org#
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
properties:
- container: ''
  name: Account
  type: schema:Organization
- container: ''
  name: Contact
  type: schema:Person
- container: ''
  name: Lead
  type: schema:Person
- container: ''
  name: Opportunity
  type: gr:Offering
- container: ''
  name: Task
  type: schema:Action
- container: ''
  name: Case
  type: schema:CreativeWork
- container: ''
  name: Campaign
  type: schema:Event
- container: ''
  name: Id
  type: string
- container: ''
  name: CreatedDate
  type: dateTime
- container: ''
  name: LastModifiedDate
  type: dateTime
- container: ''
  name: SystemModstamp
  type: dateTime
property_count: 11
provider_name: Salesforce Sales Cloud
provider_slug: salesforce-sales-cloud
slug: salesforce-sales-cloud-context
source_filename: salesforce-sales-cloud-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://developer.salesforce.com/schemas/sales-cloud/\",\n    \"sf\": \"https://developer.salesforce.com/schemas/sales-cloud/\",\n    \"schema\": \"https://schema.org/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n    \"org\": \"http://www.w3.org/ns/org#\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n\n    \"Account\": {\n      \"@id\": \"sf:Account\",\n      \"@type\": \"schema:Organization\",\n      \"@context\": {\n        \"Name\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"Phone\": \"schema:telephone\",\n        \"Fax\": \"schema:faxNumber\",\n        \"Website\": \"schema:url\",\n        \"Industry\": \"schema:isicV4\",\n        \"AnnualRevenue\": \"schema:annualRevenue\"\
  ,\n        \"NumberOfEmployees\": \"schema:numberOfEmployees\",\n        \"BillingStreet\": \"schema:streetAddress\",\n        \"BillingCity\": \"schema:addressLocality\",\n        \"BillingState\": \"schema:addressRegion\",\n        \"BillingPostalCode\": \"schema:postalCode\",\n        \"BillingCountry\": \"schema:addressCountry\",\n        \"BillingLatitude\": \"schema:latitude\",\n        \"BillingLongitude\": \"schema:longitude\",\n        \"ShippingStreet\": \"schema:streetAddress\",\n        \"ShippingCity\": \"schema:addressLocality\",\n        \"ShippingState\": \"schema:addressRegion\",\n        \"ShippingPostalCode\": \"schema:postalCode\",\n        \"ShippingCountry\": \"schema:addressCountry\",\n        \"TickerSymbol\": \"schema:tickerSymbol\",\n        \"AccountNumber\": \"schema:identifier\",\n        \"Ownership\": \"schema:ownershipFundingInfo\",\n        \"DunsNumber\": \"schema:duns\",\n        \"NaicsCode\": \"schema:naics\",\n        \"CreatedDate\": {\n         \
  \ \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"LastModifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"OwnerId\": \"sf:ownedBy\",\n        \"ParentId\": \"schema:parentOrganization\",\n        \"Type\": \"sf:accountType\",\n        \"Rating\": \"schema:ratingValue\",\n        \"AccountSource\": \"sf:leadSource\",\n        \"Site\": \"schema:location\"\n      }\n    },\n\n    \"Contact\": {\n      \"@id\": \"sf:Contact\",\n      \"@type\": \"schema:Person\",\n      \"@context\": {\n        \"FirstName\": \"schema:givenName\",\n        \"LastName\": \"schema:familyName\",\n        \"MiddleName\": \"schema:additionalName\",\n        \"Name\": \"schema:name\",\n        \"Salutation\": \"schema:honorificPrefix\",\n        \"Suffix\": \"schema:honorificSuffix\",\n        \"Email\": \"schema:email\",\n        \"Phone\": \"schema:telephone\",\n        \"MobilePhone\": \"schema:telephone\"\
  ,\n        \"HomePhone\": \"schema:telephone\",\n        \"Fax\": \"schema:faxNumber\",\n        \"Title\": \"schema:jobTitle\",\n        \"Department\": \"schema:department\",\n        \"Birthdate\": {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"Description\": \"schema:description\",\n        \"MailingStreet\": \"schema:streetAddress\",\n        \"MailingCity\": \"schema:addressLocality\",\n        \"MailingState\": \"schema:addressRegion\",\n        \"MailingPostalCode\": \"schema:postalCode\",\n        \"MailingCountry\": \"schema:addressCountry\",\n        \"AccountId\": {\n          \"@id\": \"schema:worksFor\",\n          \"@type\": \"@id\"\n        },\n        \"ReportsToId\": {\n          \"@id\": \"org:reportsTo\",\n          \"@type\": \"@id\"\n        },\n        \"AssistantName\": \"sf:assistantName\",\n        \"LeadSource\": \"sf:leadSource\",\n        \"HasOptedOutOfEmail\": \"sf:emailOptOut\",\n        \"DoNotCall\"\
  : \"sf:doNotCall\",\n        \"CreatedDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"LastModifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"OwnerId\": \"sf:ownedBy\"\n      }\n    },\n\n    \"Lead\": {\n      \"@id\": \"sf:Lead\",\n      \"@type\": \"schema:Person\",\n      \"@context\": {\n        \"FirstName\": \"schema:givenName\",\n        \"LastName\": \"schema:familyName\",\n        \"Name\": \"schema:name\",\n        \"Salutation\": \"schema:honorificPrefix\",\n        \"Title\": \"schema:jobTitle\",\n        \"Company\": \"schema:worksFor\",\n        \"Email\": \"schema:email\",\n        \"Phone\": \"schema:telephone\",\n        \"MobilePhone\": \"schema:telephone\",\n        \"Fax\": \"schema:faxNumber\",\n        \"Website\": \"schema:url\",\n        \"Description\": \"schema:description\",\n        \"Street\": \"schema:streetAddress\",\n  \
  \      \"City\": \"schema:addressLocality\",\n        \"State\": \"schema:addressRegion\",\n        \"PostalCode\": \"schema:postalCode\",\n        \"Country\": \"schema:addressCountry\",\n        \"Latitude\": \"schema:latitude\",\n        \"Longitude\": \"schema:longitude\",\n        \"Industry\": \"schema:isicV4\",\n        \"AnnualRevenue\": \"schema:annualRevenue\",\n        \"NumberOfEmployees\": \"schema:numberOfEmployees\",\n        \"Status\": \"sf:leadStatus\",\n        \"Rating\": \"schema:ratingValue\",\n        \"LeadSource\": \"sf:leadSource\",\n        \"IsConverted\": \"sf:isConverted\",\n        \"ConvertedDate\": {\n          \"@id\": \"sf:convertedDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"ConvertedAccountId\": {\n          \"@id\": \"sf:convertedAccount\",\n          \"@type\": \"@id\"\n        },\n        \"ConvertedContactId\": {\n          \"@id\": \"sf:convertedContact\",\n          \"@type\": \"@id\"\n        },\n        \"ConvertedOpportunityId\"\
  : {\n          \"@id\": \"sf:convertedOpportunity\",\n          \"@type\": \"@id\"\n        },\n        \"HasOptedOutOfEmail\": \"sf:emailOptOut\",\n        \"DoNotCall\": \"sf:doNotCall\",\n        \"CreatedDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"LastModifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"OwnerId\": \"sf:ownedBy\"\n      }\n    },\n\n    \"Opportunity\": {\n      \"@id\": \"sf:Opportunity\",\n      \"@type\": \"gr:Offering\",\n      \"@context\": {\n        \"Name\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"Amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"StageName\": \"sf:salesStage\",\n        \"Probability\": \"sf:probability\",\n        \"ExpectedRevenue\": \"sf:expectedRevenue\",\n        \"CloseDate\": {\n          \"@id\": \"sf:closeDate\"\
  ,\n          \"@type\": \"xsd:date\"\n        },\n        \"Type\": \"sf:opportunityType\",\n        \"LeadSource\": \"sf:leadSource\",\n        \"NextStep\": \"sf:nextStep\",\n        \"ForecastCategoryName\": \"sf:forecastCategory\",\n        \"IsClosed\": \"sf:isClosed\",\n        \"IsWon\": \"sf:isWon\",\n        \"AccountId\": {\n          \"@id\": \"schema:seller\",\n          \"@type\": \"@id\"\n        },\n        \"ContactId\": {\n          \"@id\": \"sf:primaryContact\",\n          \"@type\": \"@id\"\n        },\n        \"CampaignId\": {\n          \"@id\": \"sf:sourceCampaign\",\n          \"@type\": \"@id\"\n        },\n        \"CreatedDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"LastModifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"OwnerId\": \"sf:ownedBy\"\n      }\n    },\n\n    \"Task\": {\n      \"@id\": \"sf:Task\",\n      \"@type\"\
  : \"schema:Action\",\n      \"@context\": {\n        \"Subject\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"Status\": \"schema:actionStatus\",\n        \"Priority\": \"sf:priority\",\n        \"ActivityDate\": {\n          \"@id\": \"sf:dueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"WhoId\": {\n          \"@id\": \"sf:relatedContact\",\n          \"@type\": \"@id\"\n        },\n        \"WhatId\": {\n          \"@id\": \"sf:relatedRecord\",\n          \"@type\": \"@id\"\n        },\n        \"OwnerId\": {\n          \"@id\": \"schema:agent\",\n          \"@type\": \"@id\"\n        },\n        \"IsClosed\": \"sf:isClosed\",\n        \"CallType\": \"sf:callType\",\n        \"CallDurationInSeconds\": \"sf:callDuration\",\n        \"CompletedDateTime\": {\n          \"@id\": \"schema:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"CreatedDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        },\n        \"LastModifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Case\": {\n      \"@id\": \"sf:Case\",\n      \"@type\": \"schema:CreativeWork\",\n      \"@context\": {\n        \"CaseNumber\": \"schema:identifier\",\n        \"Subject\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"Status\": \"sf:caseStatus\",\n        \"Priority\": \"sf:priority\",\n        \"Origin\": \"sf:caseOrigin\",\n        \"Reason\": \"sf:caseReason\",\n        \"Type\": \"sf:caseType\",\n        \"IsClosed\": \"sf:isClosed\",\n        \"IsEscalated\": \"sf:isEscalated\",\n        \"ClosedDate\": {\n          \"@id\": \"sf:closedDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"ContactId\": {\n          \"@id\": \"sf:reportedBy\",\n          \"@type\": \"@id\"\n        },\n        \"AccountId\": {\n          \"@id\": \"sf:relatedAccount\",\n\
  \          \"@type\": \"@id\"\n        },\n        \"OwnerId\": {\n          \"@id\": \"schema:agent\",\n          \"@type\": \"@id\"\n        },\n        \"ParentId\": {\n          \"@id\": \"sf:parentCase\",\n          \"@type\": \"@id\"\n        },\n        \"CreatedDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"LastModifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Campaign\": {\n      \"@id\": \"sf:Campaign\",\n      \"@type\": \"schema:Event\",\n      \"@context\": {\n        \"Name\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"Type\": \"sf:campaignType\",\n        \"Status\": \"schema:eventStatus\",\n        \"StartDate\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"EndDate\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\"\
  : \"xsd:date\"\n        },\n        \"IsActive\": \"sf:isActive\",\n        \"BudgetedCost\": \"sf:budgetedCost\",\n        \"ActualCost\": \"sf:actualCost\",\n        \"ExpectedRevenue\": \"sf:expectedRevenue\",\n        \"ExpectedResponse\": \"sf:expectedResponse\",\n        \"NumberSent\": \"sf:numberSent\",\n        \"NumberOfLeads\": \"schema:attendee\",\n        \"NumberOfContacts\": \"sf:numberOfContacts\",\n        \"NumberOfResponses\": \"sf:numberOfResponses\",\n        \"NumberOfOpportunities\": \"sf:numberOfOpportunities\",\n        \"NumberOfWonOpportunities\": \"sf:numberOfWonOpportunities\",\n        \"AmountAllOpportunities\": \"sf:totalOpportunityAmount\",\n        \"AmountWonOpportunities\": \"sf:wonOpportunityAmount\",\n        \"ParentId\": {\n          \"@id\": \"schema:superEvent\",\n          \"@type\": \"@id\"\n        },\n        \"OwnerId\": {\n          \"@id\": \"schema:organizer\",\n          \"@type\": \"@id\"\n        },\n        \"CreatedDate\": {\n    \
  \      \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"LastModifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Id\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedDate\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LastModifiedDate\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"SystemModstamp\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"IsDeleted\": \"sf:isDeleted\",\n    \"OwnerId\": \"sf:ownedBy\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/json-ld/salesforce-sales-cloud-context.jsonld
tags:
- Cloud
- CRM
- Customer Management
- Enterprise
- Sales
- JSON-LD
- Linked Data
- Semantic Web
---
