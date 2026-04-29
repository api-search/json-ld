---
class_count: 33
classes:
- AudioObject
- ContactObject
- ConversationAnalytics
- CreateFlowRequest
- CreateTemplateRequest
- CursorPaging
- DocumentObject
- Flow
- FlowValidationError
- InteractiveMessage
- ListSection
- LocationMessage
- MediaObject
- MessageTemplate
- PhoneNumber
- ReactionMessage
- SendMessageRequest
- SendMessageResponse
- StickerObject
- SuccessResponse
- TemplateAnalytics
- TemplateButton
- TemplateComponent
- TemplateComponentDefinition
- TemplateMessage
- TemplateParameter
- TextMessage
- UpdateFlowRequest
- WhatsApp Flow JSON
- WhatsApp Message
- WhatsApp Message Template
- WhatsApp Webhook Payload
- WhatsAppBusinessAccount
context_file: json-ld/whatsapp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/whatsapp/refs/heads/main/json-ld/whatsapp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Whatsapp from WhatsApp.
layout: jsonld
name: Whatsapp Context
namespaces:
- prefix: wa
  uri: https://developers.facebook.com/docs/whatsapp/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: account_mode
  type: string
- container: ''
  name: action
  type: reference
- container: ''
  name: add_security_recommendation
  type: boolean
- container: ''
  name: address
  type: string
- container: set
  name: addresses
  type: string
- container: ''
  name: application_id
  type: string
- container: ''
  name: audio
  type: string
- container: ''
  name: birthday
  type: string
- container: ''
  name: biz_opaque_callback_data
  type: string
- container: ''
  name: body
  type: reference
- container: ''
  name: business_verification_status
  type: string
- container: set
  name: buttons
  type: string
- container: ''
  name: caption
  type: string
- container: set
  name: categories
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: clone_flow_id
  type: string
- container: ''
  name: code_expiration_minutes
  type: integer
- container: ''
  name: code_verification_status
  type: string
- container: ''
  name: column_end
  type: integer
- container: ''
  name: column_start
  type: integer
- container: set
  name: components
  type: string
- container: set
  name: contacts
  type: string
- container: ''
  name: context
  type: reference
- container: ''
  name: conversation_analytics
  type: reference
- container: ''
  name: country
  type: string
- container: ''
  name: coupon_code
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: cursors
  type: reference
- container: ''
  name: data_api_version
  type: string
- container: ''
  name: date_time
  type: reference
- container: ''
  name: display_phone_number
  type: string
- container: ''
  name: document
  type: string
- container: set
  name: emails
  type: string
- container: ''
  name: emoji
  type: string
- container: ''
  name: endpoint_uri
  type: string
- container: set
  name: entry
  type: string
- container: ''
  name: error
  type: string
- container: ''
  name: error_type
  type: string
- container: ''
  name: example
  type: string
- container: ''
  name: filename
  type: string
- container: ''
  name: flow_action
  type: string
- container: ''
  name: flow_id
  type: string
- container: ''
  name: footer
  type: reference
- container: ''
  name: format
  type: string
- container: ''
  name: header
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: index
  type: string
- container: ''
  name: interactive
  type: string
- container: ''
  name: is_official_business_account
  type: boolean
- container: ''
  name: json_version
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: line_end
  type: integer
- container: ''
  name: line_start
  type: integer
- container: ''
  name: link
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: message
  type: string
- container: ''
  name: message_id
  type: string
- container: ''
  name: message_template_namespace
  type: string
- container: set
  name: messages
  type: string
- container: ''
  name: messaging_limit_tier
  type: string
- container: ''
  name: messaging_product
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: name_status
  type: string
- container: ''
  name: navigate_screen
  type: string
- container: ''
  name: next
  type: string
- container: ''
  name: object
  type: string
- container: ''
  name: org
  type: reference
- container: ''
  name: owner_business
  type: reference
- container: ''
  name: parameter_format
  type: string
- container: set
  name: parameters
  type: string
- container: ''
  name: payload
  type: string
- container: ''
  name: phone_number
  type: string
- container: set
  name: phones
  type: string
- container: ''
  name: platform_type
  type: string
- container: set
  name: pointers
  type: string
- container: ''
  name: preview
  type: reference
- container: ''
  name: preview_url
  type: boolean
- container: ''
  name: previous
  type: string
- container: ''
  name: primary_funding_id
  type: string
- container: ''
  name: purchase_order_number
  type: string
- container: ''
  name: quality_rating
  type: string
- container: ''
  name: quality_score
  type: reference
- container: ''
  name: reaction
  type: string
- container: ''
  name: recipient_type
  type: string
- container: ''
  name: routing_model
  type: reference
- container: set
  name: rows
  type: string
- container: set
  name: screens
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: sticker
  type: string
- container: ''
  name: sub_type
  type: string
- container: ''
  name: success
  type: boolean
- container: ''
  name: template
  type: string
- container: ''
  name: template_analytics
  type: reference
- container: ''
  name: text
  type: string
- container: ''
  name: throughput
  type: reference
- container: ''
  name: timezone_id
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: to
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: url
  type: string
- container: set
  name: urls
  type: string
- container: set
  name: validation_errors
  type: string
- container: ''
  name: verified_name
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: video
  type: string
- container: ''
  name: whatsapp_business_account
  type: reference
property_count: 109
provider_name: WhatsApp
provider_slug: whatsapp
slug: whatsapp-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wa\": \"https://developers.facebook.com/docs/whatsapp/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AudioObject\": \"wa:AudioObject\",\n    \"ContactObject\": \"wa:ContactObject\",\n    \"ConversationAnalytics\": \"wa:ConversationAnalytics\",\n    \"CreateFlowRequest\": \"wa:CreateFlowRequest\",\n    \"CreateTemplateRequest\": \"wa:CreateTemplateRequest\",\n    \"CursorPaging\": \"wa:CursorPaging\",\n    \"DocumentObject\": \"wa:DocumentObject\",\n    \"Flow\": \"wa:Flow\",\n    \"FlowValidationError\": \"wa:FlowValidationError\",\n    \"InteractiveMessage\": \"wa:InteractiveMessage\",\n    \"ListSection\": \"wa:ListSection\",\n    \"LocationMessage\": \"wa:LocationMessage\",\n    \"MediaObject\": \"wa:MediaObject\",\n    \"MessageTemplate\": \"wa:MessageTemplate\",\n    \"PhoneNumber\": \"wa:PhoneNumber\",\n    \"ReactionMessage\": \"wa:ReactionMessage\",\n\
  \    \"SendMessageRequest\": \"wa:SendMessageRequest\",\n    \"SendMessageResponse\": \"wa:SendMessageResponse\",\n    \"StickerObject\": \"wa:StickerObject\",\n    \"SuccessResponse\": \"wa:SuccessResponse\",\n    \"TemplateAnalytics\": \"wa:TemplateAnalytics\",\n    \"TemplateButton\": \"wa:TemplateButton\",\n    \"TemplateComponent\": \"wa:TemplateComponent\",\n    \"TemplateComponentDefinition\": \"wa:TemplateComponentDefinition\",\n    \"TemplateMessage\": \"wa:TemplateMessage\",\n    \"TemplateParameter\": \"wa:TemplateParameter\",\n    \"TextMessage\": \"wa:TextMessage\",\n    \"UpdateFlowRequest\": \"wa:UpdateFlowRequest\",\n    \"WhatsApp Flow JSON\": \"wa:WhatsApp Flow JSON\",\n    \"WhatsApp Message\": \"wa:WhatsApp Message\",\n    \"WhatsApp Message Template\": \"wa:WhatsApp Message Template\",\n    \"WhatsApp Webhook Payload\": \"wa:WhatsApp Webhook Payload\",\n    \"WhatsAppBusinessAccount\": \"wa:WhatsAppBusinessAccount\",\n    \"account_mode\": {\n      \"@id\": \"wa:account_mode\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"wa:action\",\n      \"@type\": \"@id\"\n    },\n    \"add_security_recommendation\": {\n      \"@id\": \"wa:add_security_recommendation\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"address\": {\n      \"@id\": \"wa:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addresses\": {\n      \"@id\": \"wa:addresses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application_id\": {\n      \"@id\": \"wa:application_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"audio\": {\n      \"@id\": \"wa:audio\",\n      \"@type\": \"xsd:string\"\n    },\n    \"birthday\": {\n      \"@id\": \"wa:birthday\",\n      \"@type\": \"xsd:string\"\n    },\n    \"biz_opaque_callback_data\": {\n      \"@id\": \"wa:biz_opaque_callback_data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"body\": {\n      \"@id\": \"wa:body\",\n      \"@type\": \"@id\"\n    },\n    \"business_verification_status\"\
  : {\n      \"@id\": \"wa:business_verification_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buttons\": {\n      \"@id\": \"wa:buttons\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"caption\": {\n      \"@id\": \"wa:caption\",\n      \"@type\": \"xsd:string\"\n    },\n    \"categories\": {\n      \"@id\": \"wa:categories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"wa:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clone_flow_id\": {\n      \"@id\": \"wa:clone_flow_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code_expiration_minutes\": {\n      \"@id\": \"wa:code_expiration_minutes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"code_verification_status\": {\n      \"@id\": \"wa:code_verification_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"column_end\": {\n      \"@id\": \"wa:column_end\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"column_start\": {\n      \"@id\": \"wa:column_start\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"components\": {\n      \"@id\": \"wa:components\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contacts\": {\n      \"@id\": \"wa:contacts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"context\": {\n      \"@id\": \"wa:context\",\n      \"@type\": \"@id\"\n    },\n    \"conversation_analytics\": {\n      \"@id\": \"wa:conversation_analytics\",\n      \"@type\": \"@id\"\n    },\n    \"country\": {\n      \"@id\": \"wa:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coupon_code\": {\n      \"@id\": \"wa:coupon_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"wa:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cursors\": {\n      \"@id\": \"wa:cursors\",\n      \"@type\": \"@id\"\n    },\n    \"data_api_version\": {\n      \"@id\": \"wa:data_api_version\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"date_time\": {\n      \"@id\": \"wa:date_time\",\n      \"@type\": \"@id\"\n    },\n    \"display_phone_number\": {\n      \"@id\": \"wa:display_phone_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"document\": {\n      \"@id\": \"wa:document\",\n      \"@type\": \"xsd:string\"\n    },\n    \"emails\": {\n      \"@id\": \"wa:emails\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"emoji\": {\n      \"@id\": \"wa:emoji\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpoint_uri\": {\n      \"@id\": \"wa:endpoint_uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entry\": {\n      \"@id\": \"wa:entry\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error\": {\n      \"@id\": \"wa:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error_type\": {\n      \"@id\": \"wa:error_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"example\": {\n     \
  \ \"@id\": \"wa:example\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filename\": {\n      \"@id\": \"wa:filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flow_action\": {\n      \"@id\": \"wa:flow_action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flow_id\": {\n      \"@id\": \"wa:flow_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"footer\": {\n      \"@id\": \"wa:footer\",\n      \"@type\": \"@id\"\n    },\n    \"format\": {\n      \"@id\": \"wa:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"header\": {\n      \"@id\": \"wa:header\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"wa:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"wa:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"index\": {\n      \"@id\": \"wa:index\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interactive\": {\n      \"@id\": \"wa:interactive\",\n      \"@type\": \"xsd:string\"\n    },\n    \"is_official_business_account\"\
  : {\n      \"@id\": \"wa:is_official_business_account\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"json_version\": {\n      \"@id\": \"wa:json_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"wa:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"wa:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"line_end\": {\n      \"@id\": \"wa:line_end\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"line_start\": {\n      \"@id\": \"wa:line_start\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"link\": {\n      \"@id\": \"wa:link\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"wa:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"longitude\": {\n      \"@id\": \"wa:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"message\": {\n      \"@id\": \"wa:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message_id\": {\n      \"@id\"\
  : \"wa:message_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message_template_namespace\": {\n      \"@id\": \"wa:message_template_namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messages\": {\n      \"@id\": \"wa:messages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messaging_limit_tier\": {\n      \"@id\": \"wa:messaging_limit_tier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messaging_product\": {\n      \"@id\": \"wa:messaging_product\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"wa:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name_status\": {\n      \"@id\": \"wa:name_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"navigate_screen\": {\n      \"@id\": \"wa:navigate_screen\",\n      \"@type\": \"xsd:string\"\n    },\n    \"next\": {\n      \"@id\": \"wa:next\",\n      \"@type\": \"xsd:string\"\n    },\n    \"object\": {\n      \"@id\": \"wa:object\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"org\": {\n      \"@id\": \"wa:org\",\n      \"@type\": \"@id\"\n    },\n    \"owner_business\": {\n      \"@id\": \"wa:owner_business\",\n      \"@type\": \"@id\"\n    },\n    \"parameter_format\": {\n      \"@id\": \"wa:parameter_format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"wa:parameters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payload\": {\n      \"@id\": \"wa:payload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phone_number\": {\n      \"@id\": \"wa:phone_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phones\": {\n      \"@id\": \"wa:phones\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform_type\": {\n      \"@id\": \"wa:platform_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pointers\": {\n      \"@id\": \"wa:pointers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"preview\": {\n      \"@id\": \"wa:preview\",\n      \"@type\": \"@id\"\n    },\n    \"preview_url\": {\n      \"@id\": \"wa:preview_url\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"previous\": {\n      \"@id\": \"wa:previous\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primary_funding_id\": {\n      \"@id\": \"wa:primary_funding_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purchase_order_number\": {\n      \"@id\": \"wa:purchase_order_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quality_rating\": {\n      \"@id\": \"wa:quality_rating\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quality_score\": {\n      \"@id\": \"wa:quality_score\",\n      \"@type\": \"@id\"\n    },\n    \"reaction\": {\n      \"@id\": \"wa:reaction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recipient_type\": {\n      \"@id\": \"wa:recipient_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routing_model\": {\n      \"@id\": \"wa:routing_model\",\n      \"\
  @type\": \"@id\"\n    },\n    \"rows\": {\n      \"@id\": \"wa:rows\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"screens\": {\n      \"@id\": \"wa:screens\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"wa:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sticker\": {\n      \"@id\": \"wa:sticker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sub_type\": {\n      \"@id\": \"wa:sub_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"success\": {\n      \"@id\": \"wa:success\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"template\": {\n      \"@id\": \"wa:template\",\n      \"@type\": \"xsd:string\"\n    },\n    \"template_analytics\": {\n      \"@id\": \"wa:template_analytics\",\n      \"@type\": \"@id\"\n    },\n    \"text\": {\n      \"@id\": \"wa:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"throughput\": {\n      \"@id\": \"wa:throughput\",\n      \"\
  @type\": \"@id\"\n    },\n    \"timezone_id\": {\n      \"@id\": \"wa:timezone_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"wa:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"to\": {\n      \"@id\": \"wa:to\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"wa:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"wa:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"urls\": {\n      \"@id\": \"wa:urls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validation_errors\": {\n      \"@id\": \"wa:validation_errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verified_name\": {\n      \"@id\": \"wa:verified_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"wa:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"video\": {\n      \"@id\": \"wa:video\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"whatsapp_business_account\": {\n      \"@id\": \"wa:whatsapp_business_account\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/whatsapp/refs/heads/main/json-ld/whatsapp-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
