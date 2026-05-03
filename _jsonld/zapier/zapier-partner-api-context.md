---
api_specs:
- filename: zapier-partner-api.yml
  format: yaml
  label: Zapier Partner API
  slug: partner-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zapier/refs/heads/main/openapi/zapier-partner-api.yml
class_count: 72
classes:
- _ActionRunResponseError
- _ActionRunResponse
- _ActionTestRequest
- _AuthenticationCreateRequest
- _ListInputFieldsRequest
- _ListOutputFieldsRequest
- _RunActionRequest
- _RunActionResponse
- ActionRunResponse
- Action
- ActionTestRequest
- ActionTestResponse
- ActionsResponse
- AppCategory
- App
- AppsImages
- AppsResponse
- Apps
- AuthenticationCreateRequest
- AuthenticationResponse
- Authentication
- BaseMeta
- CategoriesResponse
- Category
- ChoiceParams
- ChoiceRequest
- ChoiceResponse
- Choice
- CreateZapRequest
- CreateZapRequestStep
- ErrorSource
- ExpandedAppsResponse
- ExpandedZap
- ExpandedZapStep
- ExpandedZapsResponse
- Fieldset
- InfoField
- InputField
- InputFieldsResponse
- InvalidZapGuesserResponse
- Links
- ListInputFieldsRequest
- ListOutputFieldsRequest
- Meta
- OutputField
- OutputFieldsResponse
- Profile
- RunActionRequest
- RunActionResponse
- WhitelabelAppLinks
- WhitelabelApp
- WhitelabelAppsResponse
- ZapGuesserRawStep
- ZapGuesserRequest
- ZapGuesserResponse
- ZapGuesserStep
- ZapRequest
- ZapRun
- ZapRunStep
- ZapRunsResponse
- Zap
- ZapStepApp
- ZapStep
- ZapTemplate
- ZapTemplateStepImages
- ZapTemplateStep
- ZapsResponse
- description
- url
- updatedAt
- email
- modifiedAt
context_file: json-ld/zapier-partner-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zapier/refs/heads/main/json-ld/zapier-partner-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zapier Partner Api from Zapier.
layout: jsonld
name: Zapier Partner Api Context
namespaces:
- prefix: zapier
  uri: https://zapier.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: code
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: detail
  type: string
- container: ''
  name: delay
  type: integer
- container: ''
  name: meta
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: status
  type: string
- container: set
  name: results
  type: string
- container: set
  name: errors
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: offset
  type: integer
- container: ''
  name: authentication
  type: string
- container: ''
  name: inputs
  type: reference
- container: ''
  name: app
  type: string
- container: ''
  name: authenticationFields
  type: reference
- container: ''
  name: fetchLiveSamples
  type: boolean
- container: ''
  name: action
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: actionType
  type: string
- container: ''
  name: isInstant
  type: boolean
- container: ''
  name: links
  type: string
- container: ''
  name: slug
  type: string
- container: ''
  name: typeOf
  type: string
- container: ''
  name: featuredEntrySlug
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: uuid
  type: string
- container: ''
  name: image
  type: string
- container: set
  name: categories
  type: string
- container: ''
  name: images
  type: reference
- container: ''
  name: appLatest
  type: string
- container: ''
  name: url16x16
  type: string
- container: ''
  name: url32x32
  type: string
- container: ''
  name: url64x64
  type: string
- container: ''
  name: url128x128
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: page
  type: integer
- container: ''
  name: pages
  type: integer
- container: ''
  name: perPage
  type: integer
- container: set
  name: objects
  type: string
- container: ''
  name: prevUrl
  type: string
- container: ''
  name: nextUrl
  type: string
- container: set
  name: actionTypes
  type: string
- container: ''
  name: hexColor
  type: string
- container: ''
  name: isExpired
  type: boolean
- container: ''
  name: count
  type: integer
- container: ''
  name: next
  type: string
- container: ''
  name: previous
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: value
  type: string
- container: set
  name: steps
  type: string
- container: ''
  name: alias
  type: string
- container: ''
  name: pointer
  type: string
- container: ''
  name: parameter
  type: string
- container: ''
  name: header
  type: string
- container: ''
  name: isEnabled
  type: boolean
- container: ''
  name: lastSuccessfulRunDate
  type: string
- container: ''
  name: fields
  type: string
- container: ''
  name: defaultValue
  type: string
- container: set
  name: dependsOn
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: invalidatesInputFields
  type: boolean
- container: ''
  name: isRequired
  type: boolean
- container: ''
  name: items
  type: reference
- container: ''
  name: placeholder
  type: string
- container: ''
  name: valueType
  type: string
- container: set
  name: messages
  type: string
- container: ''
  name: prev
  type: string
- container: ''
  name: sample
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: fullName
  type: string
- container: ''
  name: emailConfirmed
  type: boolean
- container: ''
  name: timezone
  type: string
- container: ''
  name: mcpAuthorizeUrl
  type: string
- container: ''
  name: mcpServerUrl
  type: string
- container: ''
  name: isOauth
  type: boolean
- container: ''
  name: hasFields
  type: boolean
- container: ''
  name: hasByoc
  type: boolean
- container: ''
  name: api
  type: string
- container: ''
  name: prefilledUrl
  type: string
- container: ''
  name: step
  type: string
- container: set
  name: alternatives
  type: string
- container: ''
  name: zapId
  type: integer
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: zapTitle
  type: string
- container: ''
  name: dataIn
  type: string
- container: ''
  name: dataOut
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: params
  type: reference
- container: ''
  name: descriptionPlain
  type: string
- container: ''
  name: descriptionRaw
  type: string
- container: ''
  name: createUrl
  type: string
property_count: 95
provider_name: Zapier
provider_slug: zapier
slug: zapier-partner-api-context
source_filename: zapier-partner-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"zapier\": \"https://zapier.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"_ActionRunResponseError\": \"zapier:_ActionRunResponseError\",\n    \"_ActionRunResponse\": \"zapier:_ActionRunResponse\",\n    \"_ActionTestRequest\": \"zapier:_ActionTestRequest\",\n    \"_AuthenticationCreateRequest\": \"zapier:_AuthenticationCreateRequest\",\n    \"_ListInputFieldsRequest\": \"zapier:_ListInputFieldsRequest\",\n    \"_ListOutputFieldsRequest\": \"zapier:_ListOutputFieldsRequest\",\n    \"_RunActionRequest\": \"zapier:_RunActionRequest\",\n    \"_RunActionResponse\": \"zapier:_RunActionResponse\",\n    \"ActionRunResponse\": \"zapier:ActionRunResponse\",\n    \"Action\": \"zapier:Action\",\n    \"ActionTestRequest\": \"zapier:ActionTestRequest\",\n    \"ActionTestResponse\": \"zapier:ActionTestResponse\",\n    \"\
  ActionsResponse\": \"zapier:ActionsResponse\",\n    \"AppCategory\": \"zapier:AppCategory\",\n    \"App\": \"zapier:App\",\n    \"AppsImages\": \"zapier:AppsImages\",\n    \"AppsResponse\": \"zapier:AppsResponse\",\n    \"Apps\": \"zapier:Apps\",\n    \"AuthenticationCreateRequest\": \"zapier:AuthenticationCreateRequest\",\n    \"AuthenticationResponse\": \"zapier:AuthenticationResponse\",\n    \"Authentication\": \"zapier:Authentication\",\n    \"BaseMeta\": \"zapier:BaseMeta\",\n    \"CategoriesResponse\": \"zapier:CategoriesResponse\",\n    \"Category\": \"zapier:Category\",\n    \"ChoiceParams\": \"zapier:ChoiceParams\",\n    \"ChoiceRequest\": \"zapier:ChoiceRequest\",\n    \"ChoiceResponse\": \"zapier:ChoiceResponse\",\n    \"Choice\": \"zapier:Choice\",\n    \"CreateZapRequest\": \"zapier:CreateZapRequest\",\n    \"CreateZapRequestStep\": \"zapier:CreateZapRequestStep\",\n    \"ErrorSource\": \"zapier:ErrorSource\",\n    \"ExpandedAppsResponse\": \"zapier:ExpandedAppsResponse\"\
  ,\n    \"ExpandedZap\": \"zapier:ExpandedZap\",\n    \"ExpandedZapStep\": \"zapier:ExpandedZapStep\",\n    \"ExpandedZapsResponse\": \"zapier:ExpandedZapsResponse\",\n    \"Fieldset\": \"zapier:Fieldset\",\n    \"InfoField\": \"zapier:InfoField\",\n    \"InputField\": \"zapier:InputField\",\n    \"InputFieldsResponse\": \"zapier:InputFieldsResponse\",\n    \"InvalidZapGuesserResponse\": \"zapier:InvalidZapGuesserResponse\",\n    \"Links\": \"zapier:Links\",\n    \"ListInputFieldsRequest\": \"zapier:ListInputFieldsRequest\",\n    \"ListOutputFieldsRequest\": \"zapier:ListOutputFieldsRequest\",\n    \"Meta\": \"zapier:Meta\",\n    \"OutputField\": \"zapier:OutputField\",\n    \"OutputFieldsResponse\": \"zapier:OutputFieldsResponse\",\n    \"Profile\": \"zapier:Profile\",\n    \"RunActionRequest\": \"zapier:RunActionRequest\",\n    \"RunActionResponse\": \"zapier:RunActionResponse\",\n    \"WhitelabelAppLinks\": \"zapier:WhitelabelAppLinks\",\n    \"WhitelabelApp\": \"zapier:WhitelabelApp\"\
  ,\n    \"WhitelabelAppsResponse\": \"zapier:WhitelabelAppsResponse\",\n    \"ZapGuesserRawStep\": \"zapier:ZapGuesserRawStep\",\n    \"ZapGuesserRequest\": \"zapier:ZapGuesserRequest\",\n    \"ZapGuesserResponse\": \"zapier:ZapGuesserResponse\",\n    \"ZapGuesserStep\": \"zapier:ZapGuesserStep\",\n    \"ZapRequest\": \"zapier:ZapRequest\",\n    \"ZapRun\": \"zapier:ZapRun\",\n    \"ZapRunStep\": \"zapier:ZapRunStep\",\n    \"ZapRunsResponse\": \"zapier:ZapRunsResponse\",\n    \"Zap\": \"zapier:Zap\",\n    \"ZapStepApp\": \"zapier:ZapStepApp\",\n    \"ZapStep\": \"zapier:ZapStep\",\n    \"ZapTemplate\": \"zapier:ZapTemplate\",\n    \"ZapTemplateStepImages\": \"zapier:ZapTemplateStepImages\",\n    \"ZapTemplateStep\": \"zapier:ZapTemplateStep\",\n    \"ZapsResponse\": \"zapier:ZapsResponse\",\n    \"code\": {\n      \"@id\": \"zapier:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"zapier:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\"\
  : {\n      \"@id\": \"zapier:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"delay\": {\n      \"@id\": \"zapier:delay\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"meta\": {\n      \"@id\": \"zapier:meta\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"zapier:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"zapier:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"results\": {\n      \"@id\": \"zapier:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"zapier:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"zapier:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"offset\": {\n      \"@id\": \"zapier:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"authentication\": {\n      \"@id\": \"zapier:authentication\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"inputs\": {\n      \"@id\": \"zapier:inputs\",\n      \"@type\": \"@id\"\n    },\n    \"app\": {\n      \"@id\": \"zapier:app\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authenticationFields\": {\n      \"@id\": \"zapier:authentication_fields\",\n      \"@type\": \"@id\"\n    },\n    \"fetchLiveSamples\": {\n      \"@id\": \"zapier:fetch_live_samples\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"action\": {\n      \"@id\": \"zapier:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"zapier:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"zapier:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"zapier:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionType\": {\n      \"@id\": \"zapier:action_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isInstant\": {\n      \"@id\": \"zapier:is_instant\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"description\"\
  : \"schema:description\",\n    \"links\": {\n      \"@id\": \"zapier:links\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slug\": {\n      \"@id\": \"zapier:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"typeOf\": {\n      \"@id\": \"zapier:type_of\",\n      \"@type\": \"xsd:string\"\n    },\n    \"featuredEntrySlug\": {\n      \"@id\": \"zapier:featured_entry_slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"zapier:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uuid\": {\n      \"@id\": \"zapier:uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"zapier:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"categories\": {\n      \"@id\": \"zapier:categories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"images\": {\n      \"@id\": \"zapier:images\",\n      \"@type\": \"@id\"\n    },\n    \"appLatest\": {\n      \"@id\": \"zapier:app_latest\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"url16x16\": {\n      \"@id\": \"zapier:url_16x16\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url32x32\": {\n      \"@id\": \"zapier:url_32x32\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url64x64\": {\n      \"@id\": \"zapier:url_64x64\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url128x128\": {\n      \"@id\": \"zapier:url_128x128\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"zapier:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"page\": {\n      \"@id\": \"zapier:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pages\": {\n      \"@id\": \"zapier:pages\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"perPage\": {\n      \"@id\": \"zapier:per_page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"objects\": {\n      \"@id\": \"zapier:objects\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prevUrl\": {\n      \"@id\": \"zapier:prev_url\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"nextUrl\": {\n      \"@id\": \"zapier:next_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionTypes\": {\n      \"@id\": \"zapier:action_types\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hexColor\": {\n      \"@id\": \"zapier:hex_color\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isExpired\": {\n      \"@id\": \"zapier:is_expired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"count\": {\n      \"@id\": \"zapier:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"next\": {\n      \"@id\": \"zapier:next\",\n      \"@type\": \"xsd:string\"\n    },\n    \"previous\": {\n      \"@id\": \"zapier:previous\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"zapier:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"zapier:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"steps\": {\n      \"@id\": \"zapier:steps\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alias\": {\n      \"@id\": \"zapier:alias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pointer\": {\n      \"@id\": \"zapier:pointer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameter\": {\n      \"@id\": \"zapier:parameter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"header\": {\n      \"@id\": \"zapier:header\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isEnabled\": {\n      \"@id\": \"zapier:is_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastSuccessfulRunDate\": {\n      \"@id\": \"zapier:last_successful_run_date\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": \"schema:dateModified\",\n    \"fields\": {\n      \"@id\": \"zapier:fields\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultValue\": {\n      \"@id\": \"zapier:default_value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dependsOn\": {\n      \"@id\": \"zapier:depends_on\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"zapier:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invalidatesInputFields\": {\n      \"@id\": \"zapier:invalidates_input_fields\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isRequired\": {\n      \"@id\": \"zapier:is_required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"items\": {\n      \"@id\": \"zapier:items\",\n      \"@type\": \"@id\"\n    },\n    \"placeholder\": {\n      \"@id\": \"zapier:placeholder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valueType\": {\n      \"@id\": \"zapier:value_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messages\": {\n      \"@id\": \"zapier:messages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prev\": {\n      \"@id\": \"zapier:prev\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sample\": {\n      \"@id\": \"zapier:sample\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"firstName\": {\n      \"@id\": \"zapier:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"zapier:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fullName\": {\n      \"@id\": \"zapier:full_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"emailConfirmed\": {\n      \"@id\": \"zapier:email_confirmed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"timezone\": {\n      \"@id\": \"zapier:timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mcpAuthorizeUrl\": {\n      \"@id\": \"zapier:mcp_authorize_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mcpServerUrl\": {\n      \"@id\": \"zapier:mcp_server_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isOauth\": {\n      \"@id\": \"zapier:is_oauth\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"hasFields\": {\n      \"@id\": \"zapier:has_fields\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"hasByoc\"\
  : {\n      \"@id\": \"zapier:has_byoc\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"api\": {\n      \"@id\": \"zapier:api\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prefilledUrl\": {\n      \"@id\": \"zapier:prefilled_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"step\": {\n      \"@id\": \"zapier:step\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alternatives\": {\n      \"@id\": \"zapier:alternatives\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zapId\": {\n      \"@id\": \"zapier:zap_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"startTime\": {\n      \"@id\": \"zapier:start_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endTime\": {\n      \"@id\": \"zapier:end_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"zapTitle\": {\n      \"@id\": \"zapier:zap_title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataIn\": {\n      \"@id\": \"zapier:data_in\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"dataOut\": {\n      \"@id\": \"zapier:data_out\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"zapier:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modifiedAt\": \"schema:dateModified\",\n    \"params\": {\n      \"@id\": \"zapier:params\",\n      \"@type\": \"@id\"\n    },\n    \"descriptionPlain\": {\n      \"@id\": \"zapier:description_plain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"descriptionRaw\": {\n      \"@id\": \"zapier:description_raw\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createUrl\": {\n      \"@id\": \"zapier:create_url\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zapier/refs/heads/main/json-ld/zapier-partner-api-context.jsonld
tags:
- Integrations
- iPaaS
- JSON-LD
- Linked Data
- Semantic Web
---
