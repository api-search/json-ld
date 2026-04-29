---
api_specs:
- filename: constant-contact-v3-openapi.yml
  format: yaml
  label: Constant Contact V3 API
  slug: v3
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/constant-contact/refs/heads/main/openapi/constant-contact-v3-openapi.yml
class_count: 0
classes: []
context_file: json-ld/constant-contact-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/constant-contact/refs/heads/main/json-ld/constant-contact-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Constant Contact from Constant Contact.
layout: jsonld
name: Constant Contact Context
namespaces:
- prefix: cc
  uri: https://developer.constantcontact.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Contact
  type: ''
- container: ''
  name: ContactList
  type: ''
- container: ''
  name: Tag
  type: ''
- container: ''
  name: Segment
  type: ''
- container: ''
  name: EmailCampaign
  type: ''
- container: ''
  name: CampaignActivity
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: Activity
  type: ''
property_count: 8
provider_name: Constant Contact
provider_slug: constant-contact
slug: constant-contact-context
source_filename: constant-contact-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cc\": \"https://developer.constantcontact.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Contact\": {\n      \"@id\": \"cc:Contact\",\n      \"@context\": {\n        \"id\": \"cc:contact_id\",\n        \"emailAddress\": \"schema:email\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"phoneNumber\": \"schema:telephone\",\n        \"createSource\": \"cc:create_source\",\n        \"updateSource\": \"cc:update_source\",\n        \"permissionToSend\": \"cc:permission_to_send\",\n        \"listMemberships\": \"cc:list_memberships\",\n        \"taggings\": \"cc:taggings\",\n        \"customFields\": \"cc:custom_fields\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\"\
  : {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ContactList\": {\n      \"@id\": \"cc:ContactList\",\n      \"@context\": {\n        \"id\": \"cc:list_id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"favorite\": \"cc:favorite\",\n        \"membershipCount\": \"cc:membership_count\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Tag\": {\n      \"@id\": \"cc:Tag\",\n      \"@context\": {\n        \"id\": \"cc:tag_id\",\n        \"name\": \"schema:name\",\n        \"tagSource\": \"cc:tag_source\",\n        \"contactsCount\": \"cc:contacts_count\"\n      }\n    },\n\n    \"Segment\": {\n      \"@id\": \"cc:Segment\",\n      \"@context\": {\n        \"\
  id\": \"cc:segment_id\",\n        \"name\": \"schema:name\",\n        \"segmentCriteria\": \"cc:segment_criteria\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"editableSegmentCriteria\": \"cc:editable_segment_criteria\"\n      }\n    },\n\n    \"EmailCampaign\": {\n      \"@id\": \"cc:EmailCampaign\",\n      \"@context\": {\n        \"id\": \"cc:campaign_id\",\n        \"name\": \"schema:name\",\n        \"type\": \"cc:type\",\n        \"currentStatus\": \"cc:current_status\",\n        \"campaignActivities\": \"cc:campaign_activities\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CampaignActivity\": {\n      \"@id\": \"cc:CampaignActivity\",\n      \"@context\": {\n        \"id\": \"cc:campaign_activity_id\"\
  ,\n        \"role\": \"cc:role\",\n        \"fromEmail\": \"schema:email\",\n        \"fromName\": \"schema:name\",\n        \"subject\": \"cc:subject\",\n        \"previewText\": \"cc:preview_text\",\n        \"htmlContent\": \"cc:html_content\",\n        \"physicalAddressInFooter\": \"cc:physical_address_in_footer\",\n        \"currentStatus\": \"cc:current_status\"\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"cc:Event\",\n      \"@context\": {\n        \"id\": \"cc:event_id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"cc:status\",\n        \"activeDateTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endDateTime\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"location\": \"schema:location\",\n        \"currency\": \"cc:currency\"\n      }\n    },\n\n    \"Activity\": {\n      \"@id\": \"\
  cc:Activity\",\n      \"@context\": {\n        \"id\": \"cc:activity_id\",\n        \"state\": \"cc:state\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"percentDone\": \"cc:percent_done\",\n        \"activityErrors\": \"cc:activity_errors\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/constant-contact/refs/heads/main/json-ld/constant-contact-context.jsonld
tags:
- Campaigns
- Contacts
- Email Marketing
- Events
- Reporting
- SMS
- Surveys
- JSON-LD
- Linked Data
- Semantic Web
---
