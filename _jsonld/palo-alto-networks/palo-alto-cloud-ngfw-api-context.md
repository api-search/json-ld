---
class_count: 16
classes:
- Firewall
- FirewallRequest
- FirewallSummary
- FqdnListRequest
- FqdnListSummary
- PrefixListRequest
- PrefixListSummary
- ResponseStatus
- RuleDestination
- RuleSource
- RuleStack
- RuleStackRequest
- RuleStackSummary
- SecurityRule
- SecurityRuleRequest
- SecurityRuleSummary
context_file: json-ld/palo-alto-cloud-ngfw-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-cloud-ngfw-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Cloud Ngfw Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Cloud Ngfw Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: FqdnList
  type: string
- container: set
  name: PrefixList
  type: string
- container: ''
  name: Action
  type: string
- container: ''
  name: AntiSpywareProfile
  type: string
- container: ''
  name: AntiVirusProfile
  type: string
- container: set
  name: Applications
  type: string
- container: ''
  name: AssociatedRuleStack
  type: string
- container: set
  name: Attachments
  type: reference
- container: ''
  name: AuditComment
  type: string
- container: ''
  name: AvailabilityZone
  type: string
- container: ''
  name: Category
  type: reference
- container: set
  name: Cidrs
  type: string
- container: set
  name: Countries
  type: string
- container: ''
  name: DecryptionRuleType
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: Destination
  type: reference
- container: ''
  name: Enabled
  type: boolean
- container: ''
  name: EndpointId
  type: string
- container: ''
  name: ErrorCode
  type: integer
- container: set
  name: Feeds
  type: string
- container: ''
  name: FileBlockingProfile
  type: string
- container: ''
  name: FirewallEntry
  type: reference
- container: ''
  name: FirewallName
  type: string
- container: ''
  name: FirewallStatus
  type: reference
- container: ''
  name: FqdnListEntry
  type: reference
- container: ''
  name: FqdnListName
  type: string
- container: set
  name: FqdnLists
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: LookupXForwardedFor
  type: string
- container: ''
  name: MinAppIdVersion
  type: string
- container: ''
  name: NegateDestination
  type: boolean
- container: ''
  name: NegateSource
  type: boolean
- container: ''
  name: PrefixListEntry
  type: reference
- container: ''
  name: PrefixListName
  type: string
- container: set
  name: PrefixLists
  type: string
- container: ''
  name: Priority
  type: integer
- container: ''
  name: Profile
  type: reference
- container: ''
  name: Protocol
  type: string
- container: ''
  name: Reason
  type: string
- container: ''
  name: RuleEntry
  type: reference
- container: ''
  name: RuleName
  type: string
- container: ''
  name: RuleStackEntry
  type: reference
- container: ''
  name: RuleStackName
  type: string
- container: ''
  name: Scope
  type: string
- container: ''
  name: Source
  type: reference
- container: ''
  name: Status
  type: string
- container: ''
  name: SubnetId
  type: string
- container: set
  name: SubnetMappings
  type: reference
- container: set
  name: Tags
  type: reference
- container: set
  name: URLCategoryNames
  type: string
- container: ''
  name: URLFilteringProfile
  type: string
- container: ''
  name: UpdateToken
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: VpcId
  type: string
- container: ''
  name: VulnerabilityProfile
  type: string
property_count: 55
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-cloud-ngfw-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Firewall\": \"pan:Firewall\",\n    \"FirewallRequest\": \"pan:FirewallRequest\",\n    \"FirewallSummary\": \"pan:FirewallSummary\",\n    \"FqdnList\": {\n      \"@id\": \"pan:FqdnList\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FqdnListRequest\": \"pan:FqdnListRequest\",\n    \"FqdnListSummary\": \"pan:FqdnListSummary\",\n    \"PrefixList\": {\n      \"@id\": \"pan:PrefixList\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PrefixListRequest\": \"pan:PrefixListRequest\",\n    \"PrefixListSummary\": \"pan:PrefixListSummary\",\n    \"ResponseStatus\": \"pan:ResponseStatus\",\n    \"RuleDestination\": \"pan:RuleDestination\",\n    \"RuleSource\": \"pan:RuleSource\",\n\
  \    \"RuleStack\": \"pan:RuleStack\",\n    \"RuleStackRequest\": \"pan:RuleStackRequest\",\n    \"RuleStackSummary\": \"pan:RuleStackSummary\",\n    \"SecurityRule\": \"pan:SecurityRule\",\n    \"SecurityRuleRequest\": \"pan:SecurityRuleRequest\",\n    \"SecurityRuleSummary\": \"pan:SecurityRuleSummary\",\n    \"Action\": {\n      \"@id\": \"pan:Action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AntiSpywareProfile\": {\n      \"@id\": \"pan:AntiSpywareProfile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AntiVirusProfile\": {\n      \"@id\": \"pan:AntiVirusProfile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Applications\": {\n      \"@id\": \"pan:Applications\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociatedRuleStack\": {\n      \"@id\": \"pan:AssociatedRuleStack\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Attachments\": {\n      \"@id\": \"pan:Attachments\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\
  \n    },\n    \"AuditComment\": {\n      \"@id\": \"pan:AuditComment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AvailabilityZone\": {\n      \"@id\": \"pan:AvailabilityZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Category\": {\n      \"@id\": \"pan:Category\",\n      \"@type\": \"@id\"\n    },\n    \"Cidrs\": {\n      \"@id\": \"pan:Cidrs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Countries\": {\n      \"@id\": \"pan:Countries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DecryptionRuleType\": {\n      \"@id\": \"pan:DecryptionRuleType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"pan:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Destination\": {\n      \"@id\": \"pan:Destination\",\n      \"@type\": \"@id\"\n    },\n    \"Enabled\": {\n      \"@id\": \"pan:Enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"EndpointId\": {\n\
  \      \"@id\": \"pan:EndpointId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorCode\": {\n      \"@id\": \"pan:ErrorCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Feeds\": {\n      \"@id\": \"pan:Feeds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FileBlockingProfile\": {\n      \"@id\": \"pan:FileBlockingProfile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FirewallEntry\": {\n      \"@id\": \"pan:FirewallEntry\",\n      \"@type\": \"@id\"\n    },\n    \"FirewallName\": {\n      \"@id\": \"pan:FirewallName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FirewallStatus\": {\n      \"@id\": \"pan:FirewallStatus\",\n      \"@type\": \"@id\"\n    },\n    \"FqdnListEntry\": {\n      \"@id\": \"pan:FqdnListEntry\",\n      \"@type\": \"@id\"\n    },\n    \"FqdnListName\": {\n      \"@id\": \"pan:FqdnListName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FqdnLists\": {\n      \"@id\": \"pan:FqdnLists\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Key\": {\n      \"@id\": \"pan:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LookupXForwardedFor\": {\n      \"@id\": \"pan:LookupXForwardedFor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MinAppIdVersion\": {\n      \"@id\": \"pan:MinAppIdVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NegateDestination\": {\n      \"@id\": \"pan:NegateDestination\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"NegateSource\": {\n      \"@id\": \"pan:NegateSource\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"PrefixListEntry\": {\n      \"@id\": \"pan:PrefixListEntry\",\n      \"@type\": \"@id\"\n    },\n    \"PrefixListName\": {\n      \"@id\": \"pan:PrefixListName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PrefixLists\": {\n      \"@id\": \"pan:PrefixLists\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Priority\": {\n      \"@id\": \"pan:Priority\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"Profile\": {\n      \"@id\": \"pan:Profile\",\n      \"@type\": \"@id\"\n    },\n    \"Protocol\": {\n      \"@id\": \"pan:Protocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Reason\": {\n      \"@id\": \"pan:Reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RuleEntry\": {\n      \"@id\": \"pan:RuleEntry\",\n      \"@type\": \"@id\"\n    },\n    \"RuleName\": {\n      \"@id\": \"pan:RuleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RuleStackEntry\": {\n      \"@id\": \"pan:RuleStackEntry\",\n      \"@type\": \"@id\"\n    },\n    \"RuleStackName\": {\n      \"@id\": \"pan:RuleStackName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Scope\": {\n      \"@id\": \"pan:Scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Source\": {\n      \"@id\": \"pan:Source\",\n      \"@type\": \"@id\"\n    },\n    \"Status\": {\n      \"@id\": \"pan:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubnetId\": {\n      \"@id\": \"\
  pan:SubnetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubnetMappings\": {\n      \"@id\": \"pan:SubnetMappings\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"Tags\": {\n      \"@id\": \"pan:Tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"URLCategoryNames\": {\n      \"@id\": \"pan:URLCategoryNames\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"URLFilteringProfile\": {\n      \"@id\": \"pan:URLFilteringProfile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateToken\": {\n      \"@id\": \"pan:UpdateToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"pan:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcId\": {\n      \"@id\": \"pan:VpcId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VulnerabilityProfile\": {\n      \"@id\": \"pan:VulnerabilityProfile\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-cloud-ngfw-api-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
