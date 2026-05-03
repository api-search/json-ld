---
api_specs:
- filename: wildapricot-admin-api-openapi.yml
  format: yaml
  label: WildApricot Admin API
  slug: wildapricot-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wildapricot/refs/heads/main/openapi/wildapricot-admin-api-openapi.yml
class_count: 10
classes:
- EmailDraft
- Event
- Bundle
- Account
- AuditLogItem
- Order
- EventRegistration
- Donation
- EventRegistrationType
- url
context_file: json-ld/wildapricot-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wildapricot/refs/heads/main/json-ld/wildapricot-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wildapricot from WildApricot.
layout: jsonld
name: Wildapricot Context
namespaces:
- prefix: wa
  uri: https://www.wildapricot.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: MembershipLevel
  type: string
- container: ''
  name: Contact
  type: string
- container: ''
  name: Id
  type: integer
- container: ''
  name: Name
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: PublicCanApply
  type: boolean
- container: ''
  name: Type
  type: string
- container: ''
  name: BundleMembersLimit
  type: integer
- container: ''
  name: MembershipFee
  type: decimal
- container: set
  name: MemberCanChangeToLevels
  type: string
- container: ''
  name: CreatedDate
  type: string
- container: ''
  name: Subject
  type: string
- container: ''
  name: Body
  type: string
- container: ''
  name: ReplyToName
  type: string
- container: ''
  name: ReplyToAddress
  type: string
- container: ''
  name: EventId
  type: integer
- container: ''
  name: IsLinkTrackingAllowed
  type: boolean
- container: ''
  name: LastChangedDate
  type: string
- container: ''
  name: IsScheduled
  type: boolean
- container: ''
  name: ScheduledDate
  type: string
- container: ''
  name: EventType
  type: string
- container: ''
  name: StartDate
  type: string
- container: ''
  name: StartTimeSpecified
  type: boolean
- container: ''
  name: EndDate
  type: string
- container: ''
  name: EndTimeSpecified
  type: boolean
- container: ''
  name: Location
  type: string
- container: ''
  name: RegistrationEnabled
  type: boolean
- container: ''
  name: HasEnabledRegistrationTypes
  type: boolean
- container: set
  name: Tags
  type: string
- container: set
  name: Sessions
  type: string
- container: ''
  name: RegistrationsLimit
  type: integer
- container: ''
  name: PendingRegistrationsCount
  type: integer
- container: ''
  name: ConfirmedRegistrationsCount
  type: integer
- container: ''
  name: CheckedInAttendeesNumber
  type: integer
- container: ''
  name: Email
  type: string
- container: ''
  name: ParticipantsCount
  type: integer
- container: ''
  name: Administrator
  type: string
- container: ''
  name: SpacesLeft
  type: integer
- container: set
  name: Members
  type: string
- container: ''
  name: FirstName
  type: string
- container: ''
  name: LastName
  type: string
- container: ''
  name: Organization
  type: string
- container: ''
  name: DisplayName
  type: string
- container: ''
  name: ProfileLastUpdated
  type: date
- container: ''
  name: MembershipEnabled
  type: boolean
- container: ''
  name: Status
  type: string
- container: ''
  name: IsAccountAdministrator
  type: boolean
- container: ''
  name: TermsOfUseAccepted
  type: boolean
- container: set
  name: FieldValues
  type: string
- container: ''
  name: PrimaryDomainName
  type: string
- container: ''
  name: IsFreeAccount
  type: boolean
- container: set
  name: Resources
  type: string
- container: ''
  name: Timestamp
  type: date
- container: ''
  name: Message
  type: string
- container: ''
  name: Severity
  type: string
- container: ''
  name: OrderType
  type: string
- container: ''
  name: Properties
  type: string
- container: ''
  name: Document
  type: string
- container: ''
  name: DocumentType
  type: string
- container: ''
  name: DocumentAction
  type: string
- container: ''
  name: contactId
  type: integer
- container: ''
  name: number
  type: string
- container: ''
  name: total
  type: decimal
- container: ''
  name: subTotal
  type: decimal
- container: ''
  name: isTaxesApplied
  type: boolean
- container: ''
  name: isTaxesIncludedTotal
  type: boolean
- container: ''
  name: invoiceId
  type: integer
- container: ''
  name: invoiceNumber
  type: integer
- container: set
  name: products
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: RegistrationTypeId
  type: integer
- container: ''
  name: IsCheckedIn
  type: boolean
- container: ''
  name: RegistrationFee
  type: decimal
- container: ''
  name: PaidSum
  type: decimal
- container: ''
  name: IsPaid
  type: boolean
- container: set
  name: RegistrationFields
  type: string
- container: ''
  name: ShowToPublic
  type: boolean
- container: ''
  name: RegistrationDate
  type: string
- container: ''
  name: Memo
  type: string
- container: ''
  name: IsGuestRegistration
  type: boolean
- container: ''
  name: OnWaitlist
  type: boolean
- container: ''
  name: RecreateInvoice
  type: boolean
- container: ''
  name: Payment
  type: string
- container: ''
  name: DonationDate
  type: date
- container: ''
  name: Phone
  type: string
- container: ''
  name: Comment
  type: string
- container: ''
  name: PublicComment
  type: string
- container: ''
  name: Value
  type: decimal
- container: ''
  name: IsEnabled
  type: boolean
- container: ''
  name: BasePrice
  type: decimal
- container: ''
  name: GuestPrice
  type: decimal
- container: ''
  name: UseTaxScopeSettings
  type: boolean
- container: ''
  name: RegistrationCode
  type: string
- container: set
  name: AvailableForMembershipLevels
  type: string
- container: ''
  name: AvailableFrom
  type: string
- container: ''
  name: AvailableThrough
  type: string
- container: ''
  name: MaximumRegistrantsCount
  type: integer
- container: ''
  name: CurrentRegistrantsCount
  type: integer
- container: ''
  name: CancellationDaysBeforeEvent
  type: integer
- container: ''
  name: IsWaitlistEnabled
  type: boolean
property_count: 101
provider_name: WildApricot
provider_slug: wildapricot
slug: wildapricot-context
source_filename: wildapricot-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wa\": \"https://www.wildapricot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MembershipLevel\": {\n      \"@id\": \"wa:MembershipLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EmailDraft\": \"wa:EmailDraft\",\n    \"Event\": \"wa:Event\",\n    \"Bundle\": \"wa:Bundle\",\n    \"Contact\": {\n      \"@id\": \"wa:Contact\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Account\": \"wa:Account\",\n    \"AuditLogItem\": \"wa:AuditLogItem\",\n    \"Order\": \"wa:Order\",\n    \"EventRegistration\": \"wa:EventRegistration\",\n    \"Donation\": \"wa:Donation\",\n    \"EventRegistrationType\": \"wa:EventRegistrationType\",\n    \"Id\": {\n      \"@id\": \"wa:Id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Name\": {\n      \"@id\": \"wa:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\"\
  : {\n      \"@id\": \"wa:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PublicCanApply\": {\n      \"@id\": \"wa:PublicCanApply\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Type\": {\n      \"@id\": \"wa:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BundleMembersLimit\": {\n      \"@id\": \"wa:BundleMembersLimit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"MembershipFee\": {\n      \"@id\": \"wa:MembershipFee\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"MemberCanChangeToLevels\": {\n      \"@id\": \"wa:MemberCanChangeToLevels\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedDate\": {\n      \"@id\": \"wa:CreatedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Subject\": {\n      \"@id\": \"wa:Subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Body\": {\n      \"@id\": \"wa:Body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplyToName\": {\n      \"@id\": \"wa:ReplyToName\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"ReplyToAddress\": {\n      \"@id\": \"wa:ReplyToAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventId\": {\n      \"@id\": \"wa:EventId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"IsLinkTrackingAllowed\": {\n      \"@id\": \"wa:IsLinkTrackingAllowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"LastChangedDate\": {\n      \"@id\": \"wa:LastChangedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsScheduled\": {\n      \"@id\": \"wa:IsScheduled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ScheduledDate\": {\n      \"@id\": \"wa:ScheduledDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventType\": {\n      \"@id\": \"wa:EventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartDate\": {\n      \"@id\": \"wa:StartDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartTimeSpecified\": {\n      \"@id\": \"wa:StartTimeSpecified\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"EndDate\"\
  : {\n      \"@id\": \"wa:EndDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndTimeSpecified\": {\n      \"@id\": \"wa:EndTimeSpecified\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Location\": {\n      \"@id\": \"wa:Location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RegistrationEnabled\": {\n      \"@id\": \"wa:RegistrationEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"HasEnabledRegistrationTypes\": {\n      \"@id\": \"wa:HasEnabledRegistrationTypes\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Tags\": {\n      \"@id\": \"wa:Tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Sessions\": {\n      \"@id\": \"wa:Sessions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RegistrationsLimit\": {\n      \"@id\": \"wa:RegistrationsLimit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"PendingRegistrationsCount\": {\n      \"@id\": \"wa:PendingRegistrationsCount\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"ConfirmedRegistrationsCount\": {\n      \"@id\": \"wa:ConfirmedRegistrationsCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CheckedInAttendeesNumber\": {\n      \"@id\": \"wa:CheckedInAttendeesNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Email\": {\n      \"@id\": \"wa:Email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ParticipantsCount\": {\n      \"@id\": \"wa:ParticipantsCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Administrator\": {\n      \"@id\": \"wa:Administrator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SpacesLeft\": {\n      \"@id\": \"wa:SpacesLeft\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Members\": {\n      \"@id\": \"wa:Members\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FirstName\": {\n      \"@id\": \"wa:FirstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastName\": {\n      \"@id\": \"wa:LastName\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Organization\": {\n      \"@id\": \"wa:Organization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DisplayName\": {\n      \"@id\": \"wa:DisplayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProfileLastUpdated\": {\n      \"@id\": \"wa:ProfileLastUpdated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"MembershipEnabled\": {\n      \"@id\": \"wa:MembershipEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Status\": {\n      \"@id\": \"wa:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsAccountAdministrator\": {\n      \"@id\": \"wa:IsAccountAdministrator\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"TermsOfUseAccepted\": {\n      \"@id\": \"wa:TermsOfUseAccepted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"FieldValues\": {\n      \"@id\": \"wa:FieldValues\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PrimaryDomainName\": {\n      \"@id\": \"wa:PrimaryDomainName\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"IsFreeAccount\": {\n      \"@id\": \"wa:IsFreeAccount\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Resources\": {\n      \"@id\": \"wa:Resources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Timestamp\": {\n      \"@id\": \"wa:Timestamp\",\n      \"@type\": \"xsd:date\"\n    },\n    \"Message\": {\n      \"@id\": \"wa:Message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Severity\": {\n      \"@id\": \"wa:Severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OrderType\": {\n      \"@id\": \"wa:OrderType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Properties\": {\n      \"@id\": \"wa:Properties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Document\": {\n      \"@id\": \"wa:Document\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DocumentType\": {\n      \"@id\": \"wa:DocumentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DocumentAction\": {\n      \"@id\": \"wa:DocumentAction\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"contactId\": {\n      \"@id\": \"wa:contactId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"number\": {\n      \"@id\": \"wa:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"wa:total\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"subTotal\": {\n      \"@id\": \"wa:subTotal\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"isTaxesApplied\": {\n      \"@id\": \"wa:isTaxesApplied\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isTaxesIncludedTotal\": {\n      \"@id\": \"wa:isTaxesIncludedTotal\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"invoiceId\": {\n      \"@id\": \"wa:invoiceId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"invoiceNumber\": {\n      \"@id\": \"wa:invoiceNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"products\": {\n      \"@id\": \"wa:products\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\"\
  : {\n      \"@id\": \"wa:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"wa:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"RegistrationTypeId\": {\n      \"@id\": \"wa:RegistrationTypeId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"IsCheckedIn\": {\n      \"@id\": \"wa:IsCheckedIn\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"RegistrationFee\": {\n      \"@id\": \"wa:RegistrationFee\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"PaidSum\": {\n      \"@id\": \"wa:PaidSum\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"IsPaid\": {\n      \"@id\": \"wa:IsPaid\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"RegistrationFields\": {\n      \"@id\": \"wa:RegistrationFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShowToPublic\": {\n      \"@id\": \"wa:ShowToPublic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"RegistrationDate\": {\n      \"@id\": \"wa:RegistrationDate\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"Memo\": {\n      \"@id\": \"wa:Memo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsGuestRegistration\": {\n      \"@id\": \"wa:IsGuestRegistration\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"OnWaitlist\": {\n      \"@id\": \"wa:OnWaitlist\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"RecreateInvoice\": {\n      \"@id\": \"wa:RecreateInvoice\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Payment\": {\n      \"@id\": \"wa:Payment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DonationDate\": {\n      \"@id\": \"wa:DonationDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"Phone\": {\n      \"@id\": \"wa:Phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Comment\": {\n      \"@id\": \"wa:Comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PublicComment\": {\n      \"@id\": \"wa:PublicComment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"wa:Value\",\n      \"@type\"\
  : \"xsd:decimal\"\n    },\n    \"IsEnabled\": {\n      \"@id\": \"wa:IsEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"BasePrice\": {\n      \"@id\": \"wa:BasePrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"GuestPrice\": {\n      \"@id\": \"wa:GuestPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"UseTaxScopeSettings\": {\n      \"@id\": \"wa:UseTaxScopeSettings\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"RegistrationCode\": {\n      \"@id\": \"wa:RegistrationCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AvailableForMembershipLevels\": {\n      \"@id\": \"wa:AvailableForMembershipLevels\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AvailableFrom\": {\n      \"@id\": \"wa:AvailableFrom\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AvailableThrough\": {\n      \"@id\": \"wa:AvailableThrough\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaximumRegistrantsCount\": {\n      \"@id\": \"wa:MaximumRegistrantsCount\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"CurrentRegistrantsCount\": {\n      \"@id\": \"wa:CurrentRegistrantsCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CancellationDaysBeforeEvent\": {\n      \"@id\": \"wa:CancellationDaysBeforeEvent\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"IsWaitlistEnabled\": {\n      \"@id\": \"wa:IsWaitlistEnabled\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wildapricot/refs/heads/main/json-ld/wildapricot-context.jsonld
tags:
- Membership Management
- Associations
- Nonprofit
- Events
- Payments
- JSON-LD
- Linked Data
- Semantic Web
---
