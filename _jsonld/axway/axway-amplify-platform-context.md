---
api_specs:
- filename: axway-amplify-platform-openapi-original.json
  format: json
  label: Axway Amplify Platform API
  slug: axway-amplify-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/axway/refs/heads/main/openapi/axway-amplify-platform-openapi-original.json
class_count: 38
classes:
- client_name
- consumer_name
- customQuery_name
- entitlement_description
- entitlements_name
- environment_name
- environment_url
- eventDataCentral_name
- identityProvider_description
- identityProvider_name
- org_name
- provider_description
- role_name
- sessionInfo_email
- team_name
- usageEntry_name
- user_email
- api_central.provisioned_url
- apicentral.credential.expire_name
- apicentral.documentresource.create_description
- marketplace.ai.disable_name
- marketplace.ai.enable_url
- marketplace.appearance.update_name
- marketplace.billing.disable_name
- marketplace.billing.enable_name
- marketplace.consumer.approve_name
- marketplace.consumer.signup_name
- marketplace.create_name
- marketplace.idp.create_name
- marketplace.lang.update_name
- marketplace.onboarding.disable_name
- marketplace.onboarding.enable_name
- marketplace.remove_name
- marketplace.remove_url
- marketplace.settings.update_name
- marketplace.user.remove_name
- platform.env.create_name
- platform.usage.report_name
context_file: json-ld/axway-amplify-platform-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/axway/refs/heads/main/json-ld/axway-amplify-platform-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Axway Amplify Platform from Axway.
layout: jsonld
name: Axway Amplify Platform Context
namespaces:
- prefix: axway
  uri: https://api-evangelist.com/schemas/axway/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Activation
  type: reference
- container: ''
  name: activation_created
  type: string
- container: ''
  name: activation_expire
  type: string
- container: ''
  name: activation_guid
  type: string
- container: ''
  name: activation_type
  type: string
- container: ''
  name: activation_updated
  type: string
- container: ''
  name: activation_user_guid
  type: string
- container: ''
  name: Application
  type: reference
- container: ''
  name: application__id
  type: string
- container: ''
  name: application_apis
  type: string
- container: ''
  name: application_automatic
  type: boolean
- container: ''
  name: application_env
  type: string
- container: ''
  name: application_guid
  type: string
- container: ''
  name: application_org_guid
  type: string
- container: ''
  name: application_platform
  type: string
- container: ''
  name: application_provider_guid
  type: string
- container: ''
  name: application_providers
  type: string
- container: ''
  name: application_source
  type: string
- container: ''
  name: application_subtype
  type: string
- container: ''
  name: application_type
  type: string
- container: ''
  name: ApplicationList
  type: reference
- container: ''
  name: Client
  type: reference
- container: ''
  name: client__id
  type: string
- container: ''
  name: client_client_id
  type: string
- container: ''
  name: client_guid
  type: string
- container: ''
  name: client_org_guid
  type: string
- container: ''
  name: client_roles
  type: string
- container: ''
  name: client_tags
  type: string
- container: ''
  name: client_type
  type: string
- container: ''
  name: ClientList
  type: reference
- container: ''
  name: Consumer
  type: reference
- container: ''
  name: consumer_active
  type: string
- container: ''
  name: consumer_consumer_id
  type: string
- container: ''
  name: consumer_guid
  type: string
- container: ''
  name: consumer_onboarding
  type: string
- container: ''
  name: consumer_org_id
  type: string
- container: ''
  name: consumer_pending
  type: string
- container: ''
  name: consumer_teams
  type: string
- container: ''
  name: consumer_users
  type: integer
- container: ''
  name: CustomQuery
  type: reference
- container: ''
  name: customQuery__id
  type: string
- container: ''
  name: customQuery_cross_org
  type: boolean
- container: ''
  name: customQuery_endpoint
  type: string
- container: ''
  name: customQuery_field
  type: string
- container: ''
  name: customQuery_filters
  type: string
- container: ''
  name: customQuery_granularity
  type: string
- container: ''
  name: customQuery_groupings
  type: string
- container: ''
  name: customQuery_grquantity
  type: integer
- container: ''
  name: customQuery_guid
  type: string
- container: ''
  name: customQuery_include
  type: string
- container: ''
  name: customQuery_limit
  type: integer
- container: ''
  name: customQuery_method
  type: string
- container: ''
  name: customQuery_offset
  type: integer
- container: ''
  name: customQuery_org_guid
  type: integer
- container: ''
  name: customQuery_rateGranularity
  type: string
- container: ''
  name: customQuery_sortField
  type: string
- container: ''
  name: customQuery_sortOrder
  type: integer
- container: ''
  name: customQuery_span
  type: integer
- container: ''
  name: customQuery_type
  type: string
- container: ''
  name: CustomQueryList
  type: reference
- container: ''
  name: DataExport
  type: reference
- container: ''
  name: dataExport__id
  type: string
- container: ''
  name: dataExport_completed
  type: string
- container: ''
  name: dataExport_created
  type: string
- container: ''
  name: dataExport_filename
  type: string
- container: ''
  name: dataExport_guid
  type: string
- container: ''
  name: dataExport_items
  type: string
- container: ''
  name: dataExport_org_guid
  type: string
- container: ''
  name: dataExport_status
  type: string
- container: ''
  name: dataExport_updated
  type: string
- container: ''
  name: dataExport_user_guid
  type: string
- container: ''
  name: DataExportList
  type: reference
- container: ''
  name: DefaultFields
  type: reference
- container: ''
  name: defaultFields_created
  type: string
- container: ''
  name: defaultFields_created_by
  type: string
- container: ''
  name: defaultFields_updated
  type: string
- container: ''
  name: Domain
  type: reference
- container: ''
  name: domain__id
  type: string
- container: ''
  name: domain_orgs
  type: string
- container: ''
  name: domain_provider_guid
  type: string
- container: ''
  name: domain_tld
  type: string
- container: ''
  name: DomainList
  type: reference
- container: ''
  name: Entitlement
  type: reference
- container: ''
  name: entitlement_title
  type: string
- container: ''
  name: entitlement_type
  type: string
- container: ''
  name: EntitlementList
  type: reference
- container: ''
  name: Entitlements
  type: reference
- container: ''
  name: entitlements_id
  type: string
- container: ''
  name: entitlements_ACT.Instances
  type: integer
- container: ''
  name: entitlements_AgentSDK.Transactions
  type: integer
- container: ''
  name: entitlements_provision_envs
  type: string
- container: ''
  name: entitlements_transactions
  type: integer
- container: ''
  name: entitlements_AI.Transactions
  type: integer
- container: ''
  name: entitlements_AISuite.Cores
  type: integer
- container: ''
  name: entitlements_AISuite.InputEvents
  type: integer
- container: ''
  name: entitlements_AISuite.Instances
  type: integer
- container: ''
  name: entitlements_AISuite.Users
  type: integer
- container: ''
  name: entitlements_AMPG.Transactions
  type: integer
- container: ''
  name: entitlements_AMPG.Volume
  type: decimal
- container: ''
  name: entitlements_AMPI.Transactions
  type: integer
- container: ''
  name: entitlements_AMPI.Volume
  type: decimal
- container: ''
  name: entitlements_AOB.Transactions
  type: integer
- container: ''
  name: entitlements_API.Transactions
  type: integer
- container: ''
  name: entitlements_APIB.Transactions
  type: integer
- container: ''
  name: entitlements_APIM.DRCores
  type: integer
- container: ''
  name: entitlements_APIM.NonProdCores
  type: integer
- container: ''
  name: Environment
  type: reference
- container: ''
  name: environment__id
  type: string
- container: ''
  name: environment_governance
  type: string
- container: ''
  name: environment_guid
  type: string
- container: ''
  name: environment_isProduction
  type: boolean
- container: ''
  name: environment_org_guid
  type: string
- container: ''
  name: environment_source
  type: string
- container: ''
  name: environment_type
  type: string
- container: ''
  name: EnvironmentList
  type: reference
- container: ''
  name: Event
  type: reference
- container: ''
  name: event_data
  type: string
- container: ''
  name: event_event
  type: string
- container: ''
  name: event_id
  type: string
- container: ''
  name: event_timestamp
  type: decimal
- container: ''
  name: event_version
  type: string
- container: ''
  name: EventDataActionClient
  type: reference
- container: ''
  name: eventDataActionClient_action_client_guid
  type: string
- container: ''
  name: eventDataActionClient_action_client_id
  type: string
- container: ''
  name: eventDataActionClient_action_client_name
  type: string
- container: ''
  name: EventDataActionUser
  type: reference
- container: ''
  name: eventDataActionUser_action_user_guid
  type: string
- container: ''
  name: EventDataActor
  type: reference
- container: ''
  name: EventDataCentral
  type: reference
- container: ''
  name: eventDataCentral_consumer_org_id
  type: string
- container: ''
  name: eventDataCentral_id
  type: string
- container: ''
  name: eventDataCentral_org_guid
  type: string
- container: ''
  name: eventDataCentral_org_id
  type: string
- container: ''
  name: EventDataChanges
  type: reference
- container: ''
  name: EventDataClient
  type: reference
- container: ''
  name: eventDataClient_client_guid
  type: string
- container: ''
  name: eventDataClient_client_id
  type: string
- container: ''
  name: eventDataClient_client_name
  type: string
- container: ''
  name: EventDataFrom
  type: reference
- container: ''
  name: EventDataModifiedBy
  type: reference
- container: ''
  name: EventDataOrg
  type: reference
- container: ''
  name: eventDataOrg_org_guid
  type: string
- container: ''
  name: eventDataOrg_org_id
  type: string
- container: ''
  name: eventDataOrg_org_name
  type: string
- container: ''
  name: eventDataOrg_provider_guid
  type: string
- container: ''
  name: eventDataOrg_region
  type: string
- container: ''
  name: EventDataUser
  type: reference
- container: ''
  name: eventDataUser_provider_guid
  type: string
- container: ''
  name: eventDataUser_user_guid
  type: string
- container: ''
  name: IdentityProvider
  type: reference
- container: ''
  name: identityProvider__id
  type: string
- container: ''
  name: identityProvider_guid
  type: string
- container: ''
  name: identityProvider_orgs
  type: string
- container: ''
  name: identityProvider_protocol
  type: string
- container: ''
  name: identityProvider_provider_guid
  type: string
- container: ''
  name: IdentityProviderList
  type: reference
- container: ''
  name: Org
  type: reference
- container: ''
  name: org__id
  type: string
- container: ''
  name: org_account_id
  type: integer
- container: ''
  name: org_active
  type: boolean
- container: ''
  name: org_analytics
  type: string
- container: ''
  name: org_api_central
  type: string
- container: ''
  name: org_branding
  type: string
- container: ''
  name: org_consumer_id
  type: string
- container: ''
  name: org_created_by
  type: string
- container: ''
  name: org_entitlements
  type: string
- container: ''
  name: org_guid
  type: string
- container: ''
  name: org_help_menu
  type: string
- container: ''
  name: org_last_login
  type: string
- container: ''
  name: org_logged_in_count
  type: decimal
- container: ''
  name: org_onboarding
  type: string
- container: ''
  name: org_onboarding_required
  type: string
- container: ''
  name: org_org_id
  type: integer
- container: ''
  name: org_origin
  type: string
- container: ''
  name: org_pending
  type: boolean
- container: ''
  name: org_provider_guid
  type: string
- container: ''
  name: PasswordPolicy
  type: reference
- container: ''
  name: passwordPolicy_length
  type: integer
- container: ''
  name: passwordPolicy_max_length
  type: integer
- container: ''
  name: passwordPolicy_lower
  type: integer
- container: ''
  name: passwordPolicy_upper
  type: integer
- container: ''
  name: passwordPolicy_special
  type: integer
- container: ''
  name: passwordPolicy_digit
  type: integer
- container: ''
  name: passwordPolicy_lockout
  type: integer
- container: ''
  name: passwordPolicy_renewal
  type: integer
- container: ''
  name: passwordPolicy_history
  type: integer
- container: ''
  name: Provider
  type: reference
- container: ''
  name: provider__id
  type: string
- container: ''
  name: provider_admin_teams
  type: string
- container: ''
  name: provider_consume_teams
  type: string
- container: ''
  name: provider_publish_teams
  type: string
- container: ''
  name: provider_ai
  type: string
- container: ''
  name: provider_appearance
  type: string
- container: ''
  name: provider_billing
  type: string
- container: ''
  name: provider_certificate
  type: string
- container: ''
  name: provider_certificate_expires
  type: string
- container: ''
  name: provider_console
  type: string
- container: ''
  name: provider_consumer
  type: boolean
- container: ''
  name: provider_consumer_approve
  type: boolean
- container: ''
  name: provider_footer
  type: string
- container: ''
  name: provider_guid
  type: string
- container: ''
  name: provider_help_menu
  type: string
- container: ''
  name: provider_help_menu_icon
  type: string
- container: ''
  name: provider_homepage
  type: string
- container: ''
  name: provider_idp
  type: boolean
- container: ''
  name: provider_idp_hint
  type: string
- container: ''
  name: ResponseMetadata
  type: reference
- container: ''
  name: responseMetadata_count
  type: decimal
- container: ''
  name: responseMetadata_limit
  type: decimal
- container: ''
  name: responseMetadata_matched
  type: decimal
- container: ''
  name: responseMetadata_page
  type: decimal
- container: ''
  name: responseMetadata_pages
  type: decimal
- container: ''
  name: responseMetadata_skip
  type: decimal
- container: ''
  name: Role
  type: reference
- container: ''
  name: role_client
  type: boolean
- container: ''
  name: role_consumer
  type: boolean
- container: ''
  name: role_default
  type: boolean
- container: ''
  name: role_disabled
  type: boolean
- container: ''
  name: role_entitlement
  type: string
- container: ''
  name: role_id
  type: string
- container: ''
  name: role_order
  type: decimal
- container: ''
  name: role_org
  type: boolean
- container: ''
  name: role_partner
  type: string
- container: ''
  name: role_platform_restricted
  type: boolean
- container: ''
  name: role_product
  type: string
- container: ''
  name: role_required_default_roles
  type: string
- container: ''
  name: role_subscription
  type: string
- container: ''
  name: role_team
  type: boolean
- container: ''
  name: role_web_only
  type: boolean
- container: ''
  name: RoleList
  type: reference
- container: ''
  name: SessionInfo
  type: reference
- container: ''
  name: sessionInfo_connect.sid
  type: string
- container: ''
  name: sessionInfo_deviceAuthRequired
  type: string
- container: ''
  name: sessionInfo_entitlements
  type: string
- container: ''
  name: sessionInfo_expiry
  type: string
- container: ''
  name: sessionInfo_firstname
  type: string
- container: ''
  name: sessionInfo_from
  type: string
- container: ''
  name: sessionInfo_guid
  type: string
- container: ''
  name: sessionInfo_idp
  type: string
- container: ''
  name: sessionInfo_lastname
  type: string
- container: ''
  name: sessionInfo_org
  type: string
- container: ''
  name: sessionInfo_org_id
  type: string
- container: ''
  name: sessionInfo_org_name
  type: string
- container: ''
  name: sessionInfo_orgs
  type: string
- container: ''
  name: sessionInfo_provider_org
  type: string
- container: ''
  name: sessionInfo_redirect
  type: string
- container: ''
  name: sessionInfo_role
  type: string
- container: ''
  name: sessionInfo_roles
  type: string
- container: ''
  name: sessionInfo_session
  type: string
- container: ''
  name: sessionInfo_sessionID
  type: string
- container: ''
  name: Subscription
  type: reference
- container: ''
  name: subscription_end_date
  type: string
- container: ''
  name: subscription_entitlements
  type: string
- container: ''
  name: subscription_governance
  type: string
- container: ''
  name: subscription_id
  type: string
- container: ''
  name: subscription_opportunity_id
  type: decimal
- container: ''
  name: subscription_plan
  type: string
- container: ''
  name: subscription_product
  type: string
- container: ''
  name: subscription_product_name
  type: string
- container: ''
  name: subscription_source
  type: string
- container: ''
  name: subscription_start_date
  type: string
- container: ''
  name: subscription_tier
  type: string
- container: ''
  name: SubscriptionList
  type: reference
- container: ''
  name: Team
  type: reference
- container: ''
  name: team__id
  type: string
- container: ''
  name: team_created
  type: string
- container: ''
  name: team_default
  type: boolean
- container: ''
  name: team_desc
  type: string
- container: ''
  name: team_guid
  type: string
- container: ''
  name: team_org_guid
  type: string
- container: ''
  name: team_tags
  type: string
- container: ''
  name: team_updated
  type: string
- container: ''
  name: team_users
  type: string
- container: ''
  name: TeamList
  type: reference
- container: ''
  name: UsageEntry
  type: reference
- container: ''
  name: usageEntry_created
  type: string
- container: ''
  name: usageEntry_created_by
  type: string
- container: ''
  name: usageEntry_downloadable
  type: boolean
- container: ''
  name: usageEntry_endDate
  type: string
- container: ''
  name: usageEntry_envId
  type: string
- container: ''
  name: usageEntry_fileId
  type: string
- container: ''
  name: usageEntry_governance
  type: string
- container: ''
  name: usageEntry_organizationId
  type: string
- container: ''
  name: usageEntry_startDate
  type: string
- container: ''
  name: usageEntry_status
  type: string
- container: ''
  name: usageEntry_unrecognized
  type: string
- container: ''
  name: usageEntry_uploadMethod
  type: string
- container: ''
  name: UsageEntryList
  type: reference
- container: ''
  name: User
  type: reference
- container: ''
  name: user__id
  type: string
- container: ''
  name: user_activated
  type: boolean
- container: ''
  name: user_active
  type: boolean
- container: ''
  name: user_authenticator_enabled
  type: boolean
- container: ''
  name: user_created
  type: string
- container: ''
  name: user_date_activated
  type: string
- container: ''
  name: user_default_org
  type: decimal
- container: ''
  name: user_external
  type: boolean
- container: ''
  name: user_firstname
  type: string
- container: ''
  name: user_guid
  type: string
- container: ''
  name: user_invited
  type: string
- container: ''
  name: user_last_logged_in_org
  type: decimal
- container: ''
  name: user_last_login
  type: string
- container: ''
  name: user_lastname
  type: string
- container: ''
  name: user_locale
  type: string
- container: ''
  name: user_logged_in_count
  type: decimal
- container: ''
  name: user_logged_in_from_cli
  type: boolean
- container: ''
  name: user_logged_in_from_other
  type: boolean
- container: ''
  name: user_logged_in_from_studio
  type: boolean
- container: ''
  name: UserDevice
  type: reference
- container: ''
  name: userDevice_authorized
  type: boolean
- container: ''
  name: userDevice_authorized_date
  type: string
- container: ''
  name: userDevice_browserVersion
  type: string
- container: ''
  name: userDevice_created
  type: string
- container: ''
  name: userDevice_ipaddress
  type: string
- container: ''
  name: userDevice_origin
  type: string
- container: ''
  name: userDevice_osVersion
  type: string
- container: ''
  name: userDevice_updated
  type: string
- container: ''
  name: userDevice_user_device
  type: string
- container: ''
  name: UserDeviceList
  type: reference
- container: ''
  name: UserTeams
  type: reference
- container: ''
  name: api_central.provision
  type: reference
- container: ''
  name: api_central.provision_teams
  type: string
- container: ''
  name: api_central.provision_trial
  type: boolean
- container: ''
  name: api_central.provisioned
  type: reference
- container: ''
  name: api_central.provisioned_org_guid
  type: string
- container: ''
  name: api_central.provisioned_org_id
  type: string
- container: ''
  name: api_central.provisioned_success
  type: boolean
- container: ''
  name: api_central.provisioned_user_guid
  type: string
- container: ''
  name: apic.ucs.catalogitem.create
  type: reference
- container: ''
  name: apic.ucs.catalogitem.create_catalogSubType
  type: string
- container: ''
  name: apic.ucs.catalogitem.create_catalogType
  type: string
- container: ''
  name: apic.ucs.catalogitem.create_envId
  type: string
- container: ''
  name: apic.ucs.catalogitem.remove
  type: reference
- container: ''
  name: apic.ucs.catalogitem.share
  type: reference
- container: ''
  name: apic.ucs.catalogitem.update
  type: reference
- container: ''
  name: apic.ucs.subscription.create
  type: reference
- container: ''
  name: apic.ucs.subscription.create_catalogItemId
  type: string
- container: ''
  name: apic.ucs.subscription.create_envId
  type: string
- container: ''
  name: apic.ucs.subscription.remove
  type: reference
- container: ''
  name: apic.ucs.subscription.update
  type: reference
- container: ''
  name: apicentral._._
  type: reference
- container: ''
  name: apicentral._.__group
  type: string
- container: ''
  name: apicentral._._.update
  type: reference
- container: ''
  name: apicentral._._.update_group
  type: string
- container: ''
  name: apicentral.agent.create
  type: reference
- container: ''
  name: apicentral.agent.create_agent_type
  type: string
- container: ''
  name: apicentral.agent.create_dataplane_type
  type: string
- container: ''
  name: apicentral.agent.create_envId
  type: string
- container: ''
  name: apicentral.agent.create_group
  type: string
- container: ''
  name: apicentral.agent.failed
  type: reference
- container: ''
  name: apicentral.agent.remove
  type: reference
- container: ''
  name: apicentral.agent.start
  type: reference
- container: ''
  name: apicentral.agent.start_agent_type
  type: string
- container: ''
  name: apicentral.agent.start_agent_version
  type: string
- container: ''
  name: apicentral.agent.start_dataplane_type
  type: string
- container: ''
  name: apicentral.agent.start_envId
  type: string
- container: ''
  name: apicentral.agent.start_group
  type: string
- container: ''
  name: apicentral.agent.stop
  type: reference
- container: ''
  name: apicentral.agent.unhealthy
  type: reference
- container: ''
  name: apicentral.apiservice.create
  type: reference
- container: ''
  name: apicentral.apiservice.create_automatic
  type: boolean
- container: ''
  name: apicentral.apiservice.create_envId
  type: string
- container: ''
  name: apicentral.apiservice.create_group
  type: string
- container: ''
  name: apicentral.apiservice.remove
  type: reference
- container: ''
  name: apicentral.apiservice.update
  type: reference
- container: ''
  name: apicentral.asset.create
  type: reference
- container: ''
  name: apicentral.asset.create_envIds
  type: string
- container: ''
  name: apicentral.asset.create_group
  type: string
- container: ''
  name: apicentral.asset.remove
  type: reference
- container: ''
  name: apicentral.asset.update
  type: reference
- container: ''
  name: apicentral.credential.expire
  type: reference
- container: ''
  name: apicentral.credential.expire_application_id
  type: string
- container: ''
  name: apicentral.credential.expire_application_name
  type: string
- container: ''
  name: apicentral.credential.expire_group
  type: string
- container: ''
  name: apicentral.credential.expire_id
  type: string
- container: ''
  name: apicentral.credential.expire_org_guid
  type: string
- container: ''
  name: apicentral.credential.expire_org_id
  type: string
- container: ''
  name: apicentral.credential.expire_product_id
  type: string
- container: ''
  name: apicentral.credential.expire_provider_guid
  type: string
- container: ''
  name: apicentral.credential.expire_timestamp
  type: decimal
- container: ''
  name: apicentral.credential.expire_user_guid
  type: string
- container: ''
  name: apicentral.documentresource.create
  type: reference
- container: ''
  name: apicentral.documentresource.create_fileType
  type: string
- container: ''
  name: apicentral.documentresource.create_group
  type: string
- container: ''
  name: apicentral.documentresource.create_provider_guid
  type: string
- container: ''
  name: apicentral.documentresource.create_type
  type: string
- container: ''
  name: apicentral.documentresource.create_version
  type: string
- container: ''
  name: apicentral.documentresource.remove
  type: reference
- container: ''
  name: apicentral.documentresource.update
  type: reference
- container: ''
  name: apicentral.env.create
  type: reference
- container: ''
  name: apicentral.env.create_governance
  type: string
- container: ''
  name: apicentral.env.create_group
  type: string
- container: ''
  name: apicentral.env.create_production
  type: boolean
- container: ''
  name: apicentral.env.create_user_guid
  type: string
- container: ''
  name: apicentral.env.remove
  type: reference
- container: ''
  name: apicentral.env.update
  type: reference
- container: ''
  name: apicentral.publisheddocumentresource.create
  type: reference
- container: ''
  name: apicentral.publisheddocumentresource.create_document_resource_id
  type: string
- container: ''
  name: apicentral.publisheddocumentresource.create_group
  type: string
- container: ''
  name: apicentral.publisheddocumentresource.create_provider_guid
  type: string
- container: ''
  name: apicentral.publisheddocumentresource.remove
  type: reference
- container: ''
  name: apicentral.publishedproduct.create
  type: reference
- container: ''
  name: apicentral.publishedproduct.create_group
  type: string
- container: ''
  name: apicentral.publishedproduct.create_product_id
  type: string
- container: ''
  name: apicentral.publishedproduct.create_provider_guid
  type: string
- container: ''
  name: apicentral.publishedproduct.remove
  type: reference
- container: ''
  name: apicentral.subscription.create
  type: reference
- container: ''
  name: apicentral.subscription.create_group
  type: string
- container: ''
  name: apicentral.subscription.create_provider_guid
  type: string
- container: ''
  name: apicentral.subscription.remove
  type: reference
- container: ''
  name: com.appcelerator.platform.org.user.create
  type: reference
- container: ''
  name: com.appcelerator.platform.org.user.create_idp
  type: string
- container: ''
  name: com.appcelerator.platform.org.user.create_role
  type: string
- container: ''
  name: com.appcelerator.platform.org.user.create_roles
  type: string
- container: ''
  name: com.appcelerator.platform.org.user.create_user_activated
  type: string
- container: ''
  name: com.appcelerator.platform.org.user.create_user_active
  type: string
- container: ''
  name: com.appcelerator.platform.org.user.remove
  type: reference
- container: ''
  name: marketplace.ai.disable
  type: reference
- container: ''
  name: marketplace.ai.disable_guid
  type: string
- container: ''
  name: marketplace.ai.enable
  type: reference
- container: ''
  name: marketplace.ai.enable_changes
  type: string
- container: ''
  name: marketplace.ai.enable_embedded
  type: string
- container: ''
  name: marketplace.ai.enable_stream
  type: string
- container: ''
  name: marketplace.ai.update
  type: reference
- container: ''
  name: marketplace.appearance.update
  type: reference
- container: ''
  name: marketplace.appearance.update_changes
  type: string
- container: ''
  name: marketplace.appearance.update_guid
  type: string
- container: ''
  name: marketplace.billing.disable
  type: reference
- container: ''
  name: marketplace.billing.disable_guid
  type: string
- container: ''
  name: marketplace.billing.enable
  type: reference
- container: ''
  name: marketplace.billing.enable_changes
  type: string
- container: ''
  name: marketplace.billing.enable_guid
  type: string
- container: ''
  name: marketplace.billing.enable_vendor
  type: string
- container: ''
  name: marketplace.billing.update
  type: reference
- container: ''
  name: marketplace.consumer.active
  type: reference
- container: ''
  name: marketplace.consumer.approve
  type: reference
- container: ''
  name: marketplace.consumer.approve_consumer_org_guid
  type: string
- container: ''
  name: marketplace.consumer.approve_consumer_org_id
  type: string
- container: ''
  name: marketplace.consumer.approve_consumer_org_name
  type: string
- container: ''
  name: marketplace.consumer.approve_guid
  type: string
- container: ''
  name: marketplace.consumer.deny
  type: reference
- container: ''
  name: marketplace.consumer.inactive
  type: reference
- container: ''
  name: marketplace.consumer.remove
  type: reference
- container: ''
  name: marketplace.consumer.signup
  type: reference
- container: ''
  name: marketplace.consumer.signup_consumer_org_guid
  type: string
- container: ''
  name: marketplace.consumer.signup_consumer_org_id
  type: string
- container: ''
  name: marketplace.consumer.signup_consumer_org_name
  type: string
- container: ''
  name: marketplace.consumer.signup_guid
  type: string
- container: ''
  name: marketplace.consumer.signup_pending
  type: boolean
- container: ''
  name: marketplace.create
  type: reference
- container: ''
  name: marketplace.create_admin_teams
  type: string
- container: ''
  name: marketplace.create_certificate_expires
  type: string
- container: ''
  name: marketplace.create_consume_teams
  type: string
- container: ''
  name: marketplace.create_consumer
  type: string
- container: ''
  name: marketplace.create_consumer_approve
  type: string
- container: ''
  name: marketplace.create_guid
  type: string
- container: ''
  name: marketplace.create_help_menu
  type: string
- container: ''
  name: marketplace.create_idp
  type: string
- container: ''
  name: marketplace.create_idp_hint
  type: string
- container: ''
  name: marketplace.create_lang_default
  type: string
- container: ''
  name: marketplace.create_oauth
  type: string
- container: ''
  name: marketplace.create_public
  type: string
- container: ''
  name: marketplace.create_publish_teams
  type: string
- container: ''
  name: marketplace.create_reviews
  type: string
- container: ''
  name: marketplace.create_signup
  type: string
- container: ''
  name: marketplace.create_sitename
  type: string
- container: ''
  name: marketplace.create_subdomain
  type: string
- container: ''
  name: marketplace.create_terms
  type: string
- container: ''
  name: marketplace.create_terms_updated
  type: string
- container: ''
  name: marketplace.idp.create
  type: reference
- container: ''
  name: marketplace.idp.create_guid
  type: string
- container: ''
  name: marketplace.idp.create_idp
  type: string
- container: ''
  name: marketplace.idp.remove
  type: reference
- container: ''
  name: marketplace.idp.update
  type: reference
- container: ''
  name: marketplace.idp.update_changes
  type: string
- container: ''
  name: marketplace.lang.update
  type: reference
- container: ''
  name: marketplace.lang.update_changes
  type: string
- container: ''
  name: marketplace.lang.update_guid
  type: string
- container: ''
  name: marketplace.lang.update_lang_default
  type: string
- container: ''
  name: marketplace.lang.update_lang_products
  type: string
- container: ''
  name: marketplace.lang.update_lang_supported
  type: string
- container: ''
  name: marketplace.onboarding.disable
  type: reference
- container: ''
  name: marketplace.onboarding.disable_guid
  type: string
- container: ''
  name: marketplace.onboarding.enable
  type: reference
- container: ''
  name: marketplace.onboarding.enable_changes
  type: string
- container: ''
  name: marketplace.onboarding.enable_guid
  type: string
- container: ''
  name: marketplace.onboarding.update
  type: reference
- container: ''
  name: marketplace.publisheddocumentresource.add
  type: reference
- container: ''
  name: marketplace.publisheddocumentresource.add_id
  type: string
- container: ''
  name: marketplace.publisheddocumentresource.add_provider_guid
  type: string
- container: ''
  name: marketplace.publisheddocumentresource.remove
  type: reference
- container: ''
  name: marketplace.publisheddocumentresource.remove_id
  type: string
- container: ''
  name: marketplace.publisheddocumentresource.remove_provider_guid
  type: string
- container: ''
  name: marketplace.remove
  type: reference
- container: ''
  name: marketplace.remove_guid
  type: string
- container: ''
  name: marketplace.remove_subdomain
  type: string
- container: ''
  name: marketplace.settings.update
  type: reference
- container: ''
  name: marketplace.settings.update_admin_teams
  type: string
- container: ''
  name: marketplace.settings.update_certificate_expires
  type: string
- container: ''
  name: marketplace.settings.update_changes
  type: string
- container: ''
  name: marketplace.settings.update_consume_teams
  type: string
- container: ''
  name: marketplace.settings.update_consumer
  type: string
- container: ''
  name: marketplace.settings.update_consumer_approve
  type: string
- container: ''
  name: marketplace.settings.update_guid
  type: string
- container: ''
  name: marketplace.settings.update_help_menu
  type: string
- container: ''
  name: marketplace.settings.update_idp
  type: string
- container: ''
  name: marketplace.settings.update_idp_hint
  type: string
- container: ''
  name: marketplace.settings.update_lang_default
  type: string
- container: ''
  name: marketplace.settings.update_oauth
  type: string
- container: ''
  name: marketplace.settings.update_public
  type: string
- container: ''
  name: marketplace.settings.update_publish_teams
  type: string
- container: ''
  name: marketplace.settings.update_reviews
  type: string
- container: ''
  name: marketplace.settings.update_signup
  type: string
- container: ''
  name: marketplace.settings.update_sitename
  type: string
- container: ''
  name: marketplace.settings.update_subdomain
  type: string
- container: ''
  name: marketplace.settings.update_terms
  type: string
- container: ''
  name: marketplace.user.remove
  type: reference
- container: ''
  name: marketplace.user.remove_guid
  type: string
- container: ''
  name: marketplace.user.remove_orgs
  type: string
- container: ''
  name: platform.activation.access
  type: reference
- container: ''
  name: platform.activation.access_activation_guid
  type: string
- container: ''
  name: platform.activation.access_activation_type
  type: string
- container: ''
  name: platform.activation.complete
  type: reference
- container: ''
  name: platform.activation.complete_orgs
  type: string
- container: ''
  name: platform.activation.send
  type: reference
- container: ''
  name: platform.activation.send_activation_type
  type: string
- container: ''
  name: platform.app.create
  type: reference
- container: ''
  name: platform.app.create_app
  type: string
- container: ''
  name: platform.app.remove
  type: reference
- container: ''
  name: platform.app.remove_app_guid
  type: string
- container: ''
  name: platform.app.remove_app_name
  type: string
- container: ''
  name: platform.app.update
  type: reference
- container: ''
  name: platform.app.update_app
  type: string
- container: ''
  name: platform.app.update_changes
  type: string
- container: ''
  name: platform.client.create
  type: reference
- container: ''
  name: platform.client.create_roles
  type: string
- container: ''
  name: platform.client.remove
  type: reference
- container: ''
  name: platform.client.update
  type: reference
- container: ''
  name: platform.client.update_changes
  type: string
- container: ''
  name: platform.documentresource.add
  type: reference
- container: ''
  name: platform.documentresource.add_id
  type: string
- container: ''
  name: platform.documentresource.add_provider_guid
  type: string
- container: ''
  name: platform.documentresource.remove
  type: reference
- container: ''
  name: platform.documentresource.remove_id
  type: string
- container: ''
  name: platform.documentresource.remove_provider_guid
  type: string
- container: ''
  name: platform.env.create
  type: reference
- container: ''
  name: platform.env.create_governance
  type: string
- container: ''
  name: platform.env.create_guid
  type: string
- container: ''
  name: platform.env.create_type
  type: string
- container: ''
  name: platform.env.remove
  type: reference
- container: ''
  name: platform.env.update
  type: reference
- container: ''
  name: platform.env.update_changes
  type: string
- container: ''
  name: platform.login
  type: reference
- container: ''
  name: platform.login_from
  type: string
- container: ''
  name: platform.login_ip
  type: string
- container: ''
  name: platform.login.failed
  type: reference
- container: ''
  name: platform.login.failed_from
  type: string
- container: ''
  name: platform.login.failed_ip
  type: string
- container: ''
  name: platform.logout
  type: reference
- container: ''
  name: platform.logout_from
  type: string
- container: ''
  name: platform.logout_ip
  type: string
- container: ''
  name: platform.org.active
  type: reference
- container: ''
  name: platform.org.branding.update
  type: reference
- container: ''
  name: platform.org.branding.update_changes
  type: string
- container: ''
  name: platform.org.create
  type: reference
- container: ''
  name: platform.org.create_from
  type: string
- container: ''
  name: platform.org.create_modified_by
  type: string
- container: ''
  name: platform.org.delete
  type: reference
- container: ''
  name: platform.org.delete_from
  type: string
- container: ''
  name: platform.org.delete_modified_by
  type: string
- container: ''
  name: platform.org.idp.create
  type: reference
- container: ''
  name: platform.org.idp.create_idp
  type: string
- container: ''
  name: platform.org.idp.create_modified_by
  type: string
- container: ''
  name: platform.org.idp.domain.associate
  type: reference
- container: ''
  name: platform.org.idp.domain.associate_idp
  type: string
- container: ''
  name: platform.org.idp.domain.associate_modified_by
  type: string
- container: ''
  name: platform.org.idp.domain.associate_tld
  type: string
- container: ''
  name: platform.org.idp.domain.confirm
  type: reference
- container: ''
  name: platform.org.idp.domain.create
  type: reference
- container: ''
  name: platform.org.idp.domain.create_modified_by
  type: string
- container: ''
  name: platform.org.idp.domain.create_tld
  type: string
- container: ''
  name: platform.org.idp.domain.dissociate
  type: reference
- container: ''
  name: platform.org.idp.domain.remove
  type: reference
- container: ''
  name: platform.org.idp.remove
  type: reference
- container: ''
  name: platform.org.idp.update
  type: reference
- container: ''
  name: platform.org.idp.update_changes
  type: string
- container: ''
  name: platform.org.inactive
  type: reference
- container: ''
  name: platform.org.security.update
  type: reference
- container: ''
  name: platform.org.security.update_changes
  type: string
- container: ''
  name: platform.org.security.update_from
  type: string
- container: ''
  name: platform.org.security.update_modified_by
  type: string
- container: ''
  name: platform.org.update
  type: reference
- container: ''
  name: platform.org.update_changes
  type: string
- container: ''
  name: platform.org.update_from
  type: string
- container: ''
  name: platform.org.update_modified_by
  type: string
- container: ''
  name: platform.org.user.idp.update
  type: reference
- container: ''
  name: platform.org.user.idp.update_idp
  type: string
- container: ''
  name: platform.org.user.idp.update_modified_by
  type: string
- container: ''
  name: platform.org.user.primary
  type: reference
- container: ''
  name: platform.org.user.primary_changes
  type: string
- container: ''
  name: platform.org.user.resent
  type: reference
- container: ''
  name: platform.org.user.resent_activation_type
  type: string
- container: ''
  name: platform.org.user.role.update
  type: reference
- container: ''
  name: platform.org.user.role.update_added_roles
  type: string
- container: ''
  name: platform.org.user.role.update_changes
  type: string
- container: ''
  name: platform.org.user.role.update_previous_role
  type: string
- container: ''
  name: platform.org.user.role.update_removed_roles
  type: string
- container: ''
  name: platform.org.user.role.update_role
  type: string
- container: ''
  name: platform.session.create
  type: reference
- container: ''
  name: platform.session.create_from
  type: string
- container: ''
  name: platform.session.create_idp
  type: string
- container: ''
  name: platform.session.create_ip
  type: string
- container: ''
  name: platform.session.create_role
  type: string
- container: ''
  name: platform.session.create_roles
  type: string
- container: ''
  name: platform.subscription.create
  type: reference
- container: ''
  name: platform.subscription.create_modified_by
  type: string
- container: ''
  name: platform.subscription.create_subscription
  type: string
- container: ''
  name: platform.subscription.delete
  type: reference
- container: ''
  name: platform.subscription.delete_modified_by
  type: string
- container: ''
  name: platform.subscription.delete_subscription
  type: string
- container: ''
  name: platform.subscription.expired
  type: reference
- container: ''
  name: platform.subscription.expired_modified_by
  type: string
- container: ''
  name: platform.subscription.expired_subscription
  type: string
- container: ''
  name: platform.subscription.update
  type: reference
- container: ''
  name: platform.subscription.update_changes
  type: string
- container: ''
  name: platform.subscription.update_modified_by
  type: string
- container: ''
  name: platform.subscription.update_subscription
  type: string
- container: ''
  name: platform.team.app.add
  type: reference
- container: ''
  name: platform.team.app.add_app_id
  type: string
- container: ''
  name: platform.team.app.add_app_name
  type: string
- container: ''
  name: platform.team.app.add_team_guid
  type: string
- container: ''
  name: platform.team.app.add_team_name
  type: string
- container: ''
  name: platform.team.app.remove
  type: reference
- container: ''
  name: platform.team.app.remove_app_id
  type: string
- container: ''
  name: platform.team.app.remove_app_name
  type: string
- container: ''
  name: platform.team.app.remove_team_guid
  type: string
- container: ''
  name: platform.team.app.remove_team_name
  type: string
- container: ''
  name: platform.team.create
  type: reference
- container: ''
  name: platform.team.create_team
  type: string
- container: ''
  name: platform.team.default
  type: reference
- container: ''
  name: platform.team.default_team
  type: string
- container: ''
  name: platform.team.remove
  type: reference
- container: ''
  name: platform.team.remove_reassign_team
  type: string
- container: ''
  name: platform.team.remove_team
  type: string
- container: ''
  name: platform.team.update
  type: reference
- container: ''
  name: platform.team.update_changes
  type: string
- container: ''
  name: platform.team.update_team
  type: string
- container: ''
  name: platform.team.user.add
  type: reference
- container: ''
  name: platform.team.user.add_roles
  type: string
- container: ''
  name: platform.team.user.add_team_guid
  type: string
- container: ''
  name: platform.team.user.add_team_name
  type: string
- container: ''
  name: platform.team.user.remove
  type: reference
- container: ''
  name: platform.team.user.remove_team_guid
  type: string
- container: ''
  name: platform.team.user.remove_team_name
  type: string
- container: ''
  name: platform.team.user.role.update
  type: reference
- container: ''
  name: platform.team.user.role.update_roles
  type: string
- container: ''
  name: platform.team.user.role.update_team_guid
  type: string
- container: ''
  name: platform.team.user.role.update_team_name
  type: string
- container: ''
  name: platform.terms.accept
  type: reference
- container: ''
  name: platform.usage.report
  type: reference
- container: ''
  name: platform.usage.report_end_date
  type: integer
- container: ''
  name: platform.usage.report_env_guid
  type: string
- container: ''
  name: platform.usage.report_guid
  type: string
- container: ''
  name: platform.usage.report_org_guid
  type: string
- container: ''
  name: platform.usage.report_product_name
  type: string
- container: ''
  name: platform.usage.report_product_version
  type: string
- container: ''
  name: platform.usage.report_start_date
  type: integer
- container: ''
  name: platform.usage.report_status
  type: string
- container: ''
  name: platform.usage.report_upload_method
  type: string
- container: ''
  name: platform.user.impersonate
  type: reference
- container: ''
  name: platform.user.mfa.app.add
  type: reference
- container: ''
  name: platform.user.mfa.app.remove
  type: reference
- container: ''
  name: platform.user.mfa.disabled
  type: reference
- container: ''
  name: platform.user.mfa.enabled
  type: reference
- container: ''
  name: platform.user.password.change
  type: reference
- container: ''
  name: platform.user.password.change_ip
  type: string
- container: ''
  name: platform.user.password.reset
  type: reference
- container: ''
  name: platform.user.remove
  type: reference
- container: ''
  name: platform.user.remove_orgs
  type: string
- container: ''
  name: platform.user.social.disable
  type: reference
- container: ''
  name: platform.user.social.enable
  type: reference
- container: ''
  name: platform.user.social.enable_service
  type: string
- container: ''
  name: platform.user.social.enable_service_name
  type: string
- container: ''
  name: platform.user.unimpersonate
  type: reference
- container: ''
  name: platform.user.update
  type: reference
- container: ''
  name: platform.user.update_changes
  type: string
property_count: 686
provider_name: Axway
provider_slug: axway
slug: axway-amplify-platform-context
source_filename: axway-amplify-platform-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"axway\": \"https://api-evangelist.com/schemas/axway/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"Activation\": {\n      \"@id\": \"axway:activation\",\n      \"@type\": \"@id\"\n    },\n    \"activation_created\": {\n      \"@id\": \"axway:activation/created\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activation_expire\": {\n      \"@id\": \"axway:activation/expire\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activation_guid\": {\n      \"@id\": \"axway:activation/guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activation_type\": {\n      \"@id\": \"axway:activation/type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activation_updated\": {\n      \"@id\": \"axway:activation/updated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activation_user_guid\": {\n      \"@id\": \"axway:activation/user_guid\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"Application\": {\n      \"@id\": \"axway:application\",\n      \"@type\": \"@id\"\n    },\n    \"application__id\": {\n      \"@id\": \"axway:application/_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application_apis\": {\n      \"@id\": \"axway:application/apis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application_automatic\": {\n      \"@id\": \"axway:application/automatic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"application_env\": {\n      \"@id\": \"axway:application/env\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application_guid\": {\n      \"@id\": \"axway:application/guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application_org_guid\": {\n      \"@id\": \"axway:application/org_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application_platform\": {\n      \"@id\": \"axway:application/platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application_provider_guid\": {\n\
  \      \"@id\": \"axway:application/provider_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application_providers\": {\n      \"@id\": \"axway:application/providers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application_source\": {\n      \"@id\": \"axway:application/source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application_subtype\": {\n      \"@id\": \"axway:application/subtype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application_type\": {\n      \"@id\": \"axway:application/type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApplicationList\": {\n      \"@id\": \"axway:application-list\",\n      \"@type\": \"@id\"\n    },\n    \"Client\": {\n      \"@id\": \"axway:client\",\n      \"@type\": \"@id\"\n    },\n    \"client__id\": {\n      \"@id\": \"axway:client/_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"client_client_id\": {\n      \"@id\": \"axway:client/client_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"client_guid\"\
  : {\n      \"@id\": \"axway:client/guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"client_name\": \"schema:name\",\n    \"client_org_guid\": {\n      \"@id\": \"axway:client/org_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"client_roles\": {\n      \"@id\": \"axway:client/roles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"client_tags\": {\n      \"@id\": \"axway:client/tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"client_type\": {\n      \"@id\": \"axway:client/type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClientList\": {\n      \"@id\": \"axway:client-list\",\n      \"@type\": \"@id\"\n    },\n    \"Consumer\": {\n      \"@id\": \"axway:consumer\",\n      \"@type\": \"@id\"\n    },\n    \"consumer_active\": {\n      \"@id\": \"axway:consumer/active\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consumer_consumer_id\": {\n      \"@id\": \"axway:consumer/consumer_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consumer_guid\": {\n  \
  \    \"@id\": \"axway:consumer/guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consumer_name\": \"schema:name\",\n    \"consumer_onboarding\": {\n      \"@id\": \"axway:consumer/onboarding\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consumer_org_id\": {\n      \"@id\": \"axway:consumer/org_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consumer_pending\": {\n      \"@id\": \"axway:consumer/pending\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consumer_teams\": {\n      \"@id\": \"axway:consumer/teams\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consumer_users\": {\n      \"@id\": \"axway:consumer/users\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CustomQuery\": {\n      \"@id\": \"axway:custom-query\",\n      \"@type\": \"@id\"\n    },\n    \"customQuery__id\": {\n      \"@id\": \"axway:custom-query/_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customQuery_cross_org\": {\n      \"@id\": \"axway:custom-query/cross_org\",\n      \"@type\"\
  : \"xsd:boolean\"\n    },\n    \"customQuery_endpoint\": {\n      \"@id\": \"axway:custom-query/endpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customQuery_field\": {\n      \"@id\": \"axway:custom-query/field\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customQuery_filters\": {\n      \"@id\": \"axway:custom-query/filters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customQuery_granularity\": {\n      \"@id\": \"axway:custom-query/granularity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customQuery_groupings\": {\n      \"@id\": \"axway:custom-query/groupings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customQuery_grquantity\": {\n      \"@id\": \"axway:custom-query/grquantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"customQuery_guid\": {\n      \"@id\": \"axway:custom-query/guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customQuery_include\": {\n      \"@id\": \"axway:custom-query/include\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"customQuery_limit\": {\n      \"@id\": \"axway:custom-query/limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"customQuery_method\": {\n      \"@id\": \"axway:custom-query/method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customQuery_name\": \"schema:name\",\n    \"customQuery_offset\": {\n      \"@id\": \"axway:custom-query/offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"customQuery_org_guid\": {\n      \"@id\": \"axway:custom-query/org_guid\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"customQuery_rateGranularity\": {\n      \"@id\": \"axway:custom-query/rateGranularity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customQuery_sortField\": {\n      \"@id\": \"axway:custom-query/sortField\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customQuery_sortOrder\": {\n      \"@id\": \"axway:custom-query/sortOrder\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"customQuery_span\": {\n      \"@id\": \"axway:custom-query/span\",\n    \
  \  \"@type\": \"xsd:integer\"\n    },\n    \"customQuery_type\": {\n      \"@id\": \"axway:custom-query/type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomQueryList\": {\n      \"@id\": \"axway:custom-query-list\",\n      \"@type\": \"@id\"\n    },\n    \"DataExport\": {\n      \"@id\": \"axway:data-export\",\n      \"@type\": \"@id\"\n    },\n    \"dataExport__id\": {\n      \"@id\": \"axway:data-export/_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataExport_completed\": {\n      \"@id\": \"axway:data-export/completed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataExport_created\": {\n      \"@id\": \"axway:data-export/created\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataExport_filename\": {\n      \"@id\": \"axway:data-export/filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataExport_guid\": {\n      \"@id\": \"axway:data-export/guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataExport_items\": {\n      \"@id\": \"axway:data-export/items\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"dataExport_org_guid\": {\n      \"@id\": \"axway:data-export/org_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataExport_status\": {\n      \"@id\": \"axway:data-export/status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataExport_updated\": {\n      \"@id\": \"axway:data-export/updated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataExport_user_guid\": {\n      \"@id\": \"axway:data-export/user_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DataExportList\": {\n      \"@id\": \"axway:data-export-list\",\n      \"@type\": \"@id\"\n    },\n    \"DefaultFields\": {\n      \"@id\": \"axway:default-fields\",\n      \"@type\": \"@id\"\n    },\n    \"defaultFields_created\": {\n      \"@id\": \"axway:default-fields/created\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultFields_created_by\": {\n      \"@id\": \"axway:default-fields/created_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultFields_updated\"\
  : {\n      \"@id\": \"axway:default-fields/updated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Domain\": {\n      \"@id\": \"axway:domain\",\n      \"@type\": \"@id\"\n    },\n    \"domain__id\": {\n      \"@id\": \"axway:domain/_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain_orgs\": {\n      \"@id\": \"axway:domain/orgs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain_provider_guid\": {\n      \"@id\": \"axway:domain/provider_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain_tld\": {\n      \"@id\": \"axway:domain/tld\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DomainList\": {\n      \"@id\": \"axway:domain-list\",\n      \"@type\": \"@id\"\n    },\n    \"Entitlement\": {\n      \"@id\": \"axway:entitlement\",\n      \"@type\": \"@id\"\n    },\n    \"entitlement_description\": \"schema:description\",\n    \"entitlement_title\": {\n      \"@id\": \"axway:entitlement/title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entitlement_type\"\
  : {\n      \"@id\": \"axway:entitlement/type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntitlementList\": {\n      \"@id\": \"axway:entitlement-list\",\n      \"@type\": \"@id\"\n    },\n    \"Entitlements\": {\n      \"@id\": \"axway:entitlements\",\n      \"@type\": \"@id\"\n    },\n    \"entitlements_id\": {\n      \"@id\": \"axway:entitlements/id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entitlements_name\": \"schema:name\",\n    \"entitlements_ACT.Instances\": {\n      \"@id\": \"axway:entitlements/ACT.Instances\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entitlements_AgentSDK.Transactions\": {\n      \"@id\": \"axway:entitlements/AgentSDK.Transactions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entitlements_provision_envs\": {\n      \"@id\": \"axway:entitlements/provision_envs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entitlements_transactions\": {\n      \"@id\": \"axway:entitlements/transactions\",\n      \"@type\": \"xsd:integer\"\n\
  \    },\n    \"entitlements_AI.Transactions\": {\n      \"@id\": \"axway:entitlements/AI.Transactions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entitlements_AISuite.Cores\": {\n      \"@id\": \"axway:entitlements/AISuite.Cores\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entitlements_AISuite.InputEvents\": {\n      \"@id\": \"axway:entitlements/AISuite.InputEvents\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entitlements_AISuite.Instances\": {\n      \"@id\": \"axway:entitlements/AISuite.Instances\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entitlements_AISuite.Users\": {\n      \"@id\": \"axway:entitlements/AISuite.Users\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entitlements_AMPG.Transactions\": {\n      \"@id\": \"axway:entitlements/AMPG.Transactions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entitlements_AMPG.Volume\": {\n      \"@id\": \"axway:entitlements/AMPG.Volume\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"entitlements_AMPI.Transactions\"\
  : {\n      \"@id\": \"axway:entitlements/AMPI.Transactions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entitlements_AMPI.Volume\": {\n      \"@id\": \"axway:entitlements/AMPI.Volume\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"entitlements_AOB.Transactions\": {\n      \"@id\": \"axway:entitlements/AOB.Transactions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entitlements_API.Transactions\": {\n      \"@id\": \"axway:entitlements/API.Transactions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entitlements_APIB.Transactions\": {\n      \"@id\": \"axway:entitlements/APIB.Transactions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entitlements_APIM.DRCores\": {\n      \"@id\": \"axway:entitlements/APIM.DRCores\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entitlements_APIM.NonProdCores\": {\n      \"@id\": \"axway:entitlements/APIM.NonProdCores\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Environment\": {\n      \"@id\": \"axway:environment\",\n\
  \      \"@type\": \"@id\"\n    },\n    \"environment__id\": {\n      \"@id\": \"axway:environment/_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environment_governance\": {\n      \"@id\": \"axway:environment/governance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environment_guid\": {\n      \"@id\": \"axway:environment/guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environment_isProduction\": {\n      \"@id\": \"axway:environment/isProduction\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"environment_name\": \"schema:name\",\n    \"environment_org_guid\": {\n      \"@id\": \"axway:environment/org_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environment_source\": {\n      \"@id\": \"axway:environment/source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environment_type\": {\n      \"@id\": \"axway:environment/type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environment_url\": \"schema:url\",\n    \"EnvironmentList\": {\n      \"@id\"\
  : \"axway:environment-list\",\n      \"@type\": \"@id\"\n    },\n    \"Event\": {\n      \"@id\": \"axway:event\",\n      \"@type\": \"@id\"\n    },\n    \"event_data\": {\n      \"@id\": \"axway:event/data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"event_event\": {\n      \"@id\": \"axway:event/event\",\n      \"@type\": \"xsd:string\"\n    },\n    \"event_id\": {\n      \"@id\": \"axway:event/id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"event_timestamp\": {\n      \"@id\": \"axway:event/timestamp\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"event_version\": {\n      \"@id\": \"axway:event/version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventDataActionClient\": {\n      \"@id\": \"axway:event-data-action-client\",\n      \"@type\": \"@id\"\n    },\n    \"eventDataActionClient_action_client_guid\": {\n      \"@id\": \"axway:event-data-action-client/action_client_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventDataActionClient_action_client_id\"\
  : {\n      \"@id\": \"axway:event-data-action-client/action_client_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventDataActionClient_action_client_name\": {\n      \"@id\": \"axway:event-data-action-client/action_client_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventDataActionUser\": {\n      \"@id\": \"axway:event-data-action-user\",\n      \"@type\": \"@id\"\n    },\n    \"eventDataActionUser_action_user_guid\": {\n      \"@id\": \"axway:event-data-action-user/action_user_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventDataActor\": {\n      \"@id\": \"axway:event-data-actor\",\n      \"@type\": \"@id\"\n    },\n    \"EventDataCentral\": {\n      \"@id\": \"axway:event-data-central\",\n      \"@type\": \"@id\"\n    },\n    \"eventDataCentral_consumer_org_id\": {\n      \"@id\": \"axway:event-data-central/consumer_org_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventDataCentral_id\": {\n      \"@id\": \"axway:event-data-central/id\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"eventDataCentral_name\": \"schema:name\",\n    \"eventDataCentral_org_guid\": {\n      \"@id\": \"axway:event-data-central/org_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventDataCentral_org_id\": {\n      \"@id\": \"axway:event-data-central/org_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventDataChanges\": {\n      \"@id\": \"axway:event-data-changes\",\n      \"@type\": \"@id\"\n    },\n    \"EventDataClient\": {\n      \"@id\": \"axway:event-data-client\",\n      \"@type\": \"@id\"\n    },\n    \"eventDataClient_client_guid\": {\n      \"@id\": \"axway:event-data-client/client_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventDataClient_client_id\": {\n      \"@id\": \"axway:event-data-client/client_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventDataClient_client_name\": {\n      \"@id\": \"axway:event-data-client/client_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventDataFrom\"\
  : {\n      \"@id\": \"axway:event-data-from\",\n      \"@type\": \"@id\"\n    },\n    \"EventDataModifiedBy\": {\n      \"@id\": \"axway:event-data-modified-by\",\n      \"@type\": \"@id\"\n    },\n    \"EventDataOrg\": {\n      \"@id\": \"axway:event-data-org\",\n      \"@type\": \"@id\"\n    },\n    \"eventDataOrg_org_guid\": {\n      \"@id\": \"axway:event-data-org/org_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventDataOrg_org_id\": {\n      \"@id\": \"axway:event-data-org/org_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventDataOrg_org_name\": {\n      \"@id\": \"axway:event-data-org/org_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventDataOrg_provider_guid\": {\n      \"@id\": \"axway:event-data-org/provider_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventDataOrg_region\": {\n      \"@id\": \"axway:event-data-org/region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventDataUser\": {\n      \"@id\": \"axway:event-data-user\",\n\
  \      \"@type\": \"@id\"\n    },\n    \"eventDataUser_provider_guid\": {\n      \"@id\": \"axway:event-data-user/provider_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventDataUser_user_guid\": {\n      \"@id\": \"axway:event-data-user/user_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentityProvider\": {\n      \"@id\": \"axway:identity-provider\",\n      \"@type\": \"@id\"\n    },\n    \"identityProvider__id\": {\n      \"@id\": \"axway:identity-provider/_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identityProvider_description\": \"schema:description\",\n    \"identityProvider_guid\": {\n      \"@id\": \"axway:identity-provider/guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identityProvider_name\": \"schema:name\",\n    \"identityProvider_orgs\": {\n      \"@id\": \"axway:identity-provider/orgs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identityProvider_protocol\": {\n      \"@id\": \"axway:identity-provider/protocol\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"identityProvider_provider_guid\": {\n      \"@id\": \"axway:identity-provider/provider_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentityProviderList\": {\n      \"@id\": \"axway:identity-provider-list\",\n      \"@type\": \"@id\"\n    },\n    \"Org\": {\n      \"@id\": \"axway:org\",\n      \"@type\": \"@id\"\n    },\n    \"org__id\": {\n      \"@id\": \"axway:org/_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"org_account_id\": {\n      \"@id\": \"axway:org/account_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"org_active\": {\n      \"@id\": \"axway:org/active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"org_analytics\": {\n      \"@id\": \"axway:org/analytics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"org_api_central\": {\n      \"@id\": \"axway:org/api_central\",\n      \"@type\": \"xsd:string\"\n    },\n    \"org_branding\": {\n      \"@id\": \"axway:org/branding\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"org_consumer_id\": {\n      \"@id\": \"axway:org/consumer_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"org_created_by\": {\n      \"@id\": \"axway:org/created_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"org_entitlements\": {\n      \"@id\": \"axway:org/entitlements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"org_guid\": {\n      \"@id\": \"axway:org/guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"org_help_menu\": {\n      \"@id\": \"axway:org/help_menu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"org_last_login\": {\n      \"@id\": \"axway:org/last_login\",\n      \"@type\": \"xsd:string\"\n    },\n    \"org_logged_in_count\": {\n      \"@id\": \"axway:org/logged_in_count\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"org_name\": \"schema:name\",\n    \"org_onboarding\": {\n      \"@id\": \"axway:org/onboarding\",\n      \"@type\": \"xsd:string\"\n    },\n    \"org_onboarding_required\": {\n      \"@id\": \"axway:org/onboarding_required\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"org_org_id\": {\n      \"@id\": \"axway:org/org_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"org_origin\": {\n      \"@id\": \"axway:org/origin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"org_pending\": {\n      \"@id\": \"axway:org/pending\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"org_provider_guid\": {\n      \"@id\": \"axway:org/provider_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PasswordPolicy\": {\n      \"@id\": \"axway:password-policy\",\n      \"@type\": \"@id\"\n    },\n    \"passwordPolicy_length\": {\n      \"@id\": \"axway:password-policy/length\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"passwordPolicy_max_length\": {\n      \"@id\": \"axway:password-policy/max_length\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"passwordPolicy_lower\": {\n      \"@id\": \"axway:password-policy/lower\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"passwordPolicy_upper\": {\n      \"\
  @id\": \"axway:password-policy/upper\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"passwordPolicy_special\": {\n      \"@id\": \"axway:password-policy/special\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"passwordPolicy_digit\": {\n      \"@id\": \"axway:password-policy/digit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"passwordPolicy_lockout\": {\n      \"@id\": \"axway:password-policy/lockout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"passwordPolicy_renewal\": {\n      \"@id\": \"axway:password-policy/renewal\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"passwordPolicy_history\": {\n      \"@id\": \"axway:password-policy/history\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Provider\": {\n      \"@id\": \"axway:provider\",\n      \"@type\": \"@id\"\n    },\n    \"provider__id\": {\n      \"@id\": \"axway:provider/_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider_admin_teams\": {\n      \"@id\": \"axway:provider/admin_teams\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"provider_consume_teams\": {\n      \"@id\": \"axway:provider/consume_teams\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider_publish_teams\": {\n      \"@id\": \"axway:provider/publish_teams\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider_ai\": {\n      \"@id\": \"axway:provider/ai\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider_appearance\": {\n      \"@id\": \"axway:provider/appearance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider_billing\": {\n      \"@id\": \"axway:provider/billing\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider_certificate\": {\n      \"@id\": \"axway:provider/certificate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider_certificate_expires\": {\n      \"@id\": \"axway:provider/certificate_expires\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider_console\": {\n      \"@id\": \"axway:provider/console\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"provider_consumer\": {\n      \"@id\": \"axway:provider/consumer\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"provider_consumer_approve\": {\n      \"@id\": \"axway:provider/consumer_approve\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"provider_description\": \"schema:description\",\n    \"provider_footer\": {\n      \"@id\": \"axway:provider/footer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider_guid\": {\n      \"@id\": \"axway:provider/guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider_help_menu\": {\n      \"@id\": \"axway:provider/help_menu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider_help_menu_icon\": {\n      \"@id\": \"axway:provider/help_menu_icon\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider_homepage\": {\n      \"@id\": \"axway:provider/homepage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider_idp\": {\n      \"@id\": \"axway:provider/idp\",\n      \"@type\": \"xsd:boolean\"\n    },\n\
  \    \"provider_idp_hint\": {\n      \"@id\": \"axway:provider/idp_hint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResponseMetadata\": {\n      \"@id\": \"axway:response-metadata\",\n      \"@type\": \"@id\"\n    },\n    \"responseMetadata_count\": {\n      \"@id\": \"axway:response-metadata/count\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"responseMetadata_limit\": {\n      \"@id\": \"axway:response-metadata/limit\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"responseMetadata_matched\": {\n      \"@id\": \"axway:response-metadata/matched\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"responseMetadata_page\": {\n      \"@id\": \"axway:response-metadata/page\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"responseMetadata_pages\": {\n      \"@id\": \"axway:response-metadata/pages\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"responseMetadata_skip\": {\n      \"@id\": \"axway:response-metadata/skip\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"\
  Role\": {\n      \"@id\": \"axway:role\",\n      \"@type\": \"@id\"\n    },\n    \"role_client\": {\n      \"@id\": \"axway:role/client\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"role_consumer\": {\n      \"@id\": \"axway:role/consumer\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"role_default\": {\n      \"@id\": \"axway:role/default\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"role_disabled\": {\n      \"@id\": \"axway:role/disabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"role_entitlement\": {\n      \"@id\": \"axway:role/entitlement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role_id\": {\n      \"@id\": \"axway:role/id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role_name\": \"schema:name\",\n    \"role_order\": {\n      \"@id\": \"axway:role/order\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"role_org\": {\n      \"@id\": \"axway:role/org\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"role_partner\": {\n      \"@id\": \"axway:role/partner\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"role_platform_restricted\": {\n      \"@id\": \"axway:role/platform_restricted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"role_product\": {\n      \"@id\": \"axway:role/product\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role_required_default_roles\": {\n      \"@id\": \"axway:role/required_default_roles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role_subscription\": {\n      \"@id\": \"axway:role/subscription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role_team\": {\n      \"@id\": \"axway:role/team\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"role_web_only\": {\n      \"@id\": \"axway:role/web_only\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"RoleList\": {\n      \"@id\": \"axway:role-list\",\n      \"@type\": \"@id\"\n    },\n    \"SessionInfo\": {\n      \"@id\": \"axway:session-info\",\n      \"@type\": \"@id\"\n    },\n    \"sessionInfo_connect.sid\": {\n      \"@id\": \"axway:session-info/connect.sid\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_deviceAuthRequired\": {\n      \"@id\": \"axway:session-info/deviceAuthRequired\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_email\": \"schema:email\",\n    \"sessionInfo_entitlements\": {\n      \"@id\": \"axway:session-info/entitlements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_expiry\": {\n      \"@id\": \"axway:session-info/expiry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_firstname\": {\n      \"@id\": \"axway:session-info/firstname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_from\": {\n      \"@id\": \"axway:session-info/from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_guid\": {\n      \"@id\": \"axway:session-info/guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_idp\": {\n      \"@id\": \"axway:session-info/idp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_lastname\": {\n      \"@id\": \"\
  axway:session-info/lastname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_org\": {\n      \"@id\": \"axway:session-info/org\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_org_id\": {\n      \"@id\": \"axway:session-info/org_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_org_name\": {\n      \"@id\": \"axway:session-info/org_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_orgs\": {\n      \"@id\": \"axway:session-info/orgs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_provider_org\": {\n      \"@id\": \"axway:session-info/provider_org\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_redirect\": {\n      \"@id\": \"axway:session-info/redirect\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_role\": {\n      \"@id\": \"axway:session-info/role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_roles\": {\n      \"@id\": \"axway:session-info/roles\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"sessionInfo_session\": {\n      \"@id\": \"axway:session-info/session\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInfo_sessionID\": {\n      \"@id\": \"axway:session-info/sessionID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Subscription\": {\n      \"@id\": \"axway:subscription\",\n      \"@type\": \"@id\"\n    },\n    \"subscription_end_date\": {\n      \"@id\": \"axway:subscription/end_date\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscription_entitlements\": {\n      \"@id\": \"axway:subscription/entitlements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscription_governance\": {\n      \"@id\": \"axway:subscription/governance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscription_id\": {\n      \"@id\": \"axway:subscription/id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscription_opportunity_id\": {\n      \"@id\": \"axway:subscription/opportunity_id\",\n      \"@type\": \"xsd:decimal\"\n   \
  \ },\n    \"subscription_plan\": {\n      \"@id\": \"axway:subscription/plan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscription_product\": {\n      \"@id\": \"axway:subscription/product\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscription_product_name\": {\n      \"@id\": \"axway:subscription/product_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscription_source\": {\n      \"@id\": \"axway:subscription/source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscription_start_date\": {\n      \"@id\": \"axway:subscription/start_date\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscription_tier\": {\n      \"@id\": \"axway:subscription/tier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubscriptionList\": {\n      \"@id\": \"axway:subscription-list\",\n      \"@type\": \"@id\"\n    },\n    \"Team\": {\n      \"@id\": \"axway:team\",\n      \"@type\": \"@id\"\n    },\n    \"team__id\": {\n      \"@id\": \"axway:team/_id\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"team_created\": {\n      \"@id\": \"axway:team/created\",\n      \"@type\": \"xsd:string\"\n    },\n    \"team_default\": {\n      \"@id\": \"axway:team/default\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"team_desc\": {\n      \"@id\": \"axway:team/desc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"team_guid\": {\n      \"@id\": \"axway:team/guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"team_name\": \"schema:name\",\n    \"team_org_guid\": {\n      \"@id\": \"axway:team/org_guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"team_tags\": {\n      \"@id\": \"axway:team/tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"team_updated\": {\n      \"@id\": \"axway:team/updated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"team_users\": {\n      \"@id\": \"axway:team/users\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TeamList\": {\n      \"@id\": \"axway:team-list\",\n      \"@type\": \"@id\"\n    },\n    \"UsageEntry\"\
  : {\n      \"@id\": \"axway:usage-entry\",\n      \"@type\": \"@id\"\n    },\n    \"usageEntry_created\": {\n      \"@id\": \"axway:usage-entry/created\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usageEntry_created_by\": {\n      \"@id\": \"axway:usage-entry/created_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usageEntry_downloadable\": {\n      \"@id\": \"axway:usage-entry/downloadable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"usageEntry_endDate\": {\n      \"@id\": \"axway:usage-entry/endDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usageEntry_envId\": {\n      \"@id\": \"axway:usage-entry/envId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usageEntry_fileId\": {\n      \"@id\": \"axway:usage-entry/fileId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usageEntry_governance\": {\n      \"@id\": \"axway:usage-entry/governance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usageEntry_name\": \"schema:name\",\n    \"usageEntry_organizationId\"\
  : {\n      \"@id\": \"axway:usage-entry/organizationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usageEntry_startDate\": {\n      \"@id\": \"axway:usage-entry/startDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usageEntry_status\": {\n      \"@id\": \"axway:usage-entry/status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usageEntry_unrecognized\": {\n      \"@id\": \"axway:usage-entry/unrecognized\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usageEntry_uploadMethod\": {\n      \"@id\": \"axway:usage-entry/uploadMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UsageEntryList\": {\n      \"@id\": \"axway:usage-entry-list\",\n      \"@type\": \"@id\"\n    },\n    \"User\": {\n      \"@id\": \"axway:user\",\n      \"@type\": \"@id\"\n    },\n    \"user__id\": {\n      \"@id\": \"axway:user/_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user_activated\": {\n      \"@id\": \"axway:user/activated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"\
  user_active\": {\n      \"@id\": \"axway:user/active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"user_authenticator_enabled\": {\n      \"@id\": \"axway:user/authenticator_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"user_created\": {\n      \"@id\": \"axway:user/created\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user_date_activated\": {\n      \"@id\": \"axway:user/date_activated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user_default_org\": {\n      \"@id\": \"axway:user/default_org\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"user_email\": \"schema:email\",\n    \"user_external\": {\n      \"@id\": \"axway:user/external\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"user_firstname\": {\n      \"@id\": \"axway:user/firstname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user_guid\": {\n      \"@id\": \"axway:user/guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user_invited\": {\n      \"@id\": \"axway:user/invited\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"user_last_logged_in_org\": {\n      \"@id\": \"axway:user/last_logged_in_org\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"user_last_login\": {\n      \"@id\": \"axway:user/last_login\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user_lastname\": {\n      \"@id\": \"axway:user/lastname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user_locale\": {\n      \"@id\": \"axway:user/locale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user_logged_in_count\": {\n      \"@id\": \"axway:user/logged_in_count\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"user_logged_in_from_cli\": {\n      \"@id\": \"axway:user/logged_in_from_cli\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"user_logged_in_from_other\": {\n      \"@id\": \"axway:user/logged_in_from_other\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"user_logged_in_from_studio\": {\n      \"@id\": \"axway:user/logged_in_from_studio\",\n      \"@type\": \"xsd:boolean\"\
  \n    },\n    \"UserDevice\": {\n      \"@id\": \"axway:user-device\",\n      \"@type\": \"@id\"\n    },\n  \n\n# --- truncated at 32 KB (79 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/axway/refs/heads/main/json-ld/axway-amplify-platform-context.jsonld\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/axway/refs/heads/main/json-ld/axway-amplify-platform-context.jsonld
tags:
- API Management
- Enterprise
- Integration
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
