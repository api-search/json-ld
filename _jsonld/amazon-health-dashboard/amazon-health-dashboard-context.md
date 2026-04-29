---
class_count: 39
classes:
- DescribeEventDetailsForOrganizationRequest
- EventAggregate
- EventTypeFilter
- DescribeEntityAggregatesResponse
- OrganizationEventDetailsErrorItem
- DescribeEntityAggregatesRequest
- EntityAggregate
- DescribeEventsResponse
- EventAccountFilter
- OrganizationAffectedEntitiesErrorItem
- EventDetails
- DescribeEventDetailsRequest
- EventFilter
- DescribeEventAggregatesResponse
- DescribeEventsForOrganizationRequest
- DescribeEventTypesResponse
- DescribeAffectedEntitiesResponse
- DescribeAffectedAccountsForOrganizationResponse
- tagSet
- EventDetailsErrorItem
- Event
- DescribeEventTypesRequest
- DescribeAffectedEntitiesRequest
- EntityFilter
- DescribeEventDetailsForOrganizationResponse
- DescribeAffectedAccountsForOrganizationRequest
- DateTimeRange
- DescribeEventAggregatesRequest
- EventDescription
- DescribeEventsForOrganizationResponse
- AffectedEntity
- DescribeAffectedEntitiesForOrganizationResponse
- OrganizationEventDetails
- DescribeEventsRequest
- DescribeHealthServiceStatusForOrganizationResponse
- OrganizationEventFilter
- DescribeEventDetailsResponse
- DescribeAffectedEntitiesForOrganizationRequest
- OrganizationEvent
context_file: json-ld/amazon-health-dashboard-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-health-dashboard/refs/heads/main/json-ld/amazon-health-dashboard-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Health Dashboard from Amazon Health Dashboard.
layout: jsonld
name: Amazon Health Dashboard Context
namespaces:
- prefix: health
  uri: https://aws.amazon.com/health/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: eventMetadata
  type: string
- container: ''
  name: organizationEventDetailFilters
  type: string
- container: ''
  name: locale
  type: string
- container: ''
  name: aggregateValue
  type: string
- container: ''
  name: count
  type: string
- container: ''
  name: eventTypeCodes
  type: string
- container: ''
  name: services
  type: string
- container: ''
  name: eventTypeCategories
  type: string
- container: ''
  name: entityAggregates
  type: string
- container: ''
  name: awsAccountId
  type: string
- container: ''
  name: eventArn
  type: string
- container: ''
  name: errorName
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: eventArns
  type: string
- container: ''
  name: events
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: event
  type: string
- container: ''
  name: eventDescription
  type: string
- container: ''
  name: regions
  type: string
- container: ''
  name: availabilityZones
  type: string
- container: ''
  name: startTimes
  type: string
- container: ''
  name: endTimes
  type: string
- container: ''
  name: lastUpdatedTimes
  type: string
- container: ''
  name: entityArns
  type: string
- container: ''
  name: entityValues
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: eventStatusCodes
  type: string
- container: ''
  name: eventAggregates
  type: string
- container: ''
  name: filter
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: eventTypes
  type: string
- container: ''
  name: entities
  type: string
- container: ''
  name: affectedAccounts
  type: string
- container: ''
  name: eventScopeCode
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: service
  type: string
- container: ''
  name: eventTypeCode
  type: string
- container: ''
  name: eventTypeCategory
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: availabilityZone
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: lastUpdatedTime
  type: string
- container: ''
  name: statusCode
  type: string
- container: ''
  name: statusCodes
  type: string
- container: ''
  name: successfulSet
  type: string
- container: ''
  name: failedSet
  type: string
- container: ''
  name: from
  type: string
- container: ''
  name: to
  type: string
- container: ''
  name: aggregateField
  type: string
- container: ''
  name: latestDescription
  type: string
- container: ''
  name: entityArn
  type: string
- container: ''
  name: entityValue
  type: string
- container: ''
  name: entityUrl
  type: string
- container: ''
  name: healthServiceAccessStatusForOrganization
  type: string
- container: ''
  name: awsAccountIds
  type: string
- container: ''
  name: organizationEntityFilters
  type: string
property_count: 57
provider_name: Amazon Health Dashboard
provider_slug: amazon-health-dashboard
slug: amazon-health-dashboard-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"health\": \"https://aws.amazon.com/health/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DescribeEventDetailsForOrganizationRequest\": \"health:DescribeEventDetailsForOrganizationRequest\",\n    \"EventAggregate\": \"health:EventAggregate\",\n    \"EventTypeFilter\": \"health:EventTypeFilter\",\n    \"DescribeEntityAggregatesResponse\": \"health:DescribeEntityAggregatesResponse\",\n    \"OrganizationEventDetailsErrorItem\": \"health:OrganizationEventDetailsErrorItem\",\n    \"DescribeEntityAggregatesRequest\": \"health:DescribeEntityAggregatesRequest\",\n    \"EntityAggregate\": \"health:EntityAggregate\",\n    \"DescribeEventsResponse\": \"health:DescribeEventsResponse\",\n    \"EventAccountFilter\": \"health:EventAccountFilter\",\n    \"OrganizationAffectedEntitiesErrorItem\": \"health:OrganizationAffectedEntitiesErrorItem\",\n    \"EventDetails\": \"health:EventDetails\"\
  ,\n    \"DescribeEventDetailsRequest\": \"health:DescribeEventDetailsRequest\",\n    \"EventFilter\": \"health:EventFilter\",\n    \"DescribeEventAggregatesResponse\": \"health:DescribeEventAggregatesResponse\",\n    \"DescribeEventsForOrganizationRequest\": \"health:DescribeEventsForOrganizationRequest\",\n    \"DescribeEventTypesResponse\": \"health:DescribeEventTypesResponse\",\n    \"DescribeAffectedEntitiesResponse\": \"health:DescribeAffectedEntitiesResponse\",\n    \"DescribeAffectedAccountsForOrganizationResponse\": \"health:DescribeAffectedAccountsForOrganizationResponse\",\n    \"eventMetadata\": {\n      \"@id\": \"health:eventMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tagSet\": \"health:tagSet\",\n    \"EventDetailsErrorItem\": \"health:EventDetailsErrorItem\",\n    \"Event\": \"health:Event\",\n    \"DescribeEventTypesRequest\": \"health:DescribeEventTypesRequest\",\n    \"DescribeAffectedEntitiesRequest\": \"health:DescribeAffectedEntitiesRequest\",\n   \
  \ \"EntityFilter\": \"health:EntityFilter\",\n    \"DescribeEventDetailsForOrganizationResponse\": \"health:DescribeEventDetailsForOrganizationResponse\",\n    \"DescribeAffectedAccountsForOrganizationRequest\": \"health:DescribeAffectedAccountsForOrganizationRequest\",\n    \"DateTimeRange\": \"health:DateTimeRange\",\n    \"DescribeEventAggregatesRequest\": \"health:DescribeEventAggregatesRequest\",\n    \"EventDescription\": \"health:EventDescription\",\n    \"DescribeEventsForOrganizationResponse\": \"health:DescribeEventsForOrganizationResponse\",\n    \"AffectedEntity\": \"health:AffectedEntity\",\n    \"DescribeAffectedEntitiesForOrganizationResponse\": \"health:DescribeAffectedEntitiesForOrganizationResponse\",\n    \"OrganizationEventDetails\": \"health:OrganizationEventDetails\",\n    \"DescribeEventsRequest\": \"health:DescribeEventsRequest\",\n    \"DescribeHealthServiceStatusForOrganizationResponse\": \"health:DescribeHealthServiceStatusForOrganizationResponse\",\n    \"OrganizationEventFilter\"\
  : \"health:OrganizationEventFilter\",\n    \"DescribeEventDetailsResponse\": \"health:DescribeEventDetailsResponse\",\n    \"DescribeAffectedEntitiesForOrganizationRequest\": \"health:DescribeAffectedEntitiesForOrganizationRequest\",\n    \"OrganizationEvent\": \"health:OrganizationEvent\",\n    \"organizationEventDetailFilters\": {\n      \"@id\": \"health:organizationEventDetailFilters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locale\": {\n      \"@id\": \"health:locale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aggregateValue\": {\n      \"@id\": \"health:aggregateValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"health:count\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventTypeCodes\": {\n      \"@id\": \"health:eventTypeCodes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"services\": {\n      \"@id\": \"health:services\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventTypeCategories\": {\n      \"@id\": \"health:eventTypeCategories\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"entityAggregates\": {\n      \"@id\": \"health:entityAggregates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awsAccountId\": {\n      \"@id\": \"health:awsAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventArn\": {\n      \"@id\": \"health:eventArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorName\": {\n      \"@id\": \"health:errorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"health:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventArns\": {\n      \"@id\": \"health:eventArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"events\": {\n      \"@id\": \"health:events\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"health:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"event\": {\n      \"@id\": \"health:event\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventDescription\": {\n      \"\
  @id\": \"health:eventDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regions\": {\n      \"@id\": \"health:regions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availabilityZones\": {\n      \"@id\": \"health:availabilityZones\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTimes\": {\n      \"@id\": \"health:startTimes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTimes\": {\n      \"@id\": \"health:endTimes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdatedTimes\": {\n      \"@id\": \"health:lastUpdatedTimes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityArns\": {\n      \"@id\": \"health:entityArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityValues\": {\n      \"@id\": \"health:entityValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"health:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventStatusCodes\": {\n      \"@id\": \"health:eventStatusCodes\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"eventAggregates\": {\n      \"@id\": \"health:eventAggregates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filter\": {\n      \"@id\": \"health:filter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"health:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventTypes\": {\n      \"@id\": \"health:eventTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entities\": {\n      \"@id\": \"health:entities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"affectedAccounts\": {\n      \"@id\": \"health:affectedAccounts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventScopeCode\": {\n      \"@id\": \"health:eventScopeCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"health:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"health:service\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventTypeCode\": {\n      \"@id\": \"health:eventTypeCode\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"eventTypeCategory\": {\n      \"@id\": \"health:eventTypeCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"health:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availabilityZone\": {\n      \"@id\": \"health:availabilityZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"health:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"health:endTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdatedTime\": {\n      \"@id\": \"health:lastUpdatedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusCode\": {\n      \"@id\": \"health:statusCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusCodes\": {\n      \"@id\": \"health:statusCodes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"successfulSet\": {\n      \"@id\": \"health:successfulSet\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"failedSet\": {\n      \"@id\": \"health:failedSet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"health:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"to\": {\n      \"@id\": \"health:to\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aggregateField\": {\n      \"@id\": \"health:aggregateField\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latestDescription\": {\n      \"@id\": \"health:latestDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityArn\": {\n      \"@id\": \"health:entityArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityValue\": {\n      \"@id\": \"health:entityValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityUrl\": {\n      \"@id\": \"health:entityUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"healthServiceAccessStatusForOrganization\": {\n      \"@id\": \"health:healthServiceAccessStatusForOrganization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awsAccountIds\"\
  : {\n      \"@id\": \"health:awsAccountIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationEntityFilters\": {\n      \"@id\": \"health:organizationEntityFilters\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-health-dashboard/refs/heads/main/json-ld/amazon-health-dashboard-context.jsonld
tags:
- AWS
- Health Monitoring
- Notifications
- Operations
- Service Status
- JSON-LD
- Linked Data
- Semantic Web
---
