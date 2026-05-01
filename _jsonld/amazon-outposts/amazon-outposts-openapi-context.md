---
api_specs:
- filename: amazon-outposts-openapi.yml
  format: yaml
  label: AWS Outposts API
  slug: aws-outposts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-outposts/refs/heads/main/openapi/amazon-outposts-openapi.yml
class_count: 118
classes:
- AccessDeniedException
- Arn
- AssetInfo
- AssetListDefinition
- AssetState
- AvailabilityZoneIdList
- AvailabilityZoneList
- CIDR
- CIDRList
- CancelOrderInput
- CancelOrderOutput
- CatalogItemClass
- CatalogItemClassList
- CatalogItemListDefinition
- CatalogItemPowerKva
- CatalogItemStatus
- CatalogItemWeightLbs
- CityList
- ComputeAssetState
- ConflictException
- CountryCodeList
- CreateOrderInput
- CreateOrderOutput
- CreateOutpostInput
- CreateOutpostOutput
- CreateSiteInput
- CreateSiteOutput
- DeleteOutpostInput
- DeleteOutpostOutput
- DeleteSiteInput
- DeleteSiteOutput
- EC2Capacity
- EC2CapacityListDefinition
- EC2FamilyList
- GetCatalogItemInput
- GetCatalogItemOutput
- GetConnectionRequest
- GetConnectionResponse
- GetOrderInput
- GetOrderOutput
- GetOutpostInput
- GetOutpostInstanceTypesInput
- GetOutpostInstanceTypesOutput
- GetOutpostOutput
- GetSiteAddressInput
- GetSiteAddressOutput
- GetSiteInput
- GetSiteOutput
- HostIdList
- ISO8601Timestamp
- InstanceTypeItem
- InstanceTypeListDefinition
- InternalServerException
- LifeCycleStatusList
- LineItem
- LineItemAssetInformation
- LineItemAssetInformationList
- LineItemListDefinition
- LineItemQuantity
- LineItemRequest
- LineItemRequestListDefinition
- LineItemStatus
- LineItemStatusCounts
- ListAssetsInput
- ListAssetsOutput
- ListCatalogItemsInput
- ListCatalogItemsOutput
- ListOrdersInput
- ListOrdersOutput
- ListOutpostsInput
- ListOutpostsOutput
- ListSitesInput
- ListSitesOutput
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- MacAddress
- MaxResults1000
- NotFoundException
- OrderStatus
- OrderSummary
- OrderSummaryListDefinition
- OutpostDescription
- OutpostIdOnly
- OutpostName
- ServiceQuotaExceededException
- SiteDescription
- SiteName
- SiteNotes
- SkuCode
- StartConnectionRequest
- StartConnectionResponse
- StateOrRegionList
- StatusList
- SupportedStorageEnum
- SupportedStorageList
- SupportedUplinkGbpsListDefinition
- TagKey
- TagKeyList
- TagMap
- TagResourceRequest
- TagResourceResponse
- TagValue
- Token
- TrackingId
- UntagResourceRequest
- UntagResourceResponse
- UpdateOutpostInput
- UpdateOutpostOutput
- UpdateSiteAddressInput
- UpdateSiteAddressOutput
- UpdateSiteInput
- UpdateSiteOutput
- UpdateSiteRackPhysicalPropertiesInput
- UpdateSiteRackPhysicalPropertiesOutput
- ValidationException
- WireGuardPublicKey
- outpostListDefinition
- siteListDefinition
context_file: json-ld/amazon-outposts-openapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-outposts/refs/heads/main/json-ld/amazon-outposts-openapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Outposts Openapi from Amazon Outposts.
layout: jsonld
name: Amazon Outposts Openapi Context
namespaces:
- prefix: outposts
  uri: https://outposts.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: AccountId
  type: string
- container: ''
  name: Address
  type: string
- container: ''
  name: AddressLine1
  type: string
- container: ''
  name: AddressLine2
  type: string
- container: ''
  name: AddressLine3
  type: string
- container: ''
  name: AddressType
  type: string
- container: ''
  name: AssetId
  type: string
- container: ''
  name: AssetLocation
  type: string
- container: ''
  name: AssetType
  type: string
- container: ''
  name: AvailabilityZone
  type: string
- container: ''
  name: AvailabilityZoneId
  type: string
- container: ''
  name: CatalogItem
  type: string
- container: ''
  name: City
  type: string
- container: ''
  name: ComputeAttributes
  type: string
- container: ''
  name: ConnectionDetails
  type: string
- container: ''
  name: ConnectionId
  type: string
- container: ''
  name: ContactName
  type: string
- container: ''
  name: ContactPhoneNumber
  type: string
- container: ''
  name: CountryCode
  type: string
- container: ''
  name: DeviceSerialNumber
  type: string
- container: ''
  name: DistrictOrCounty
  type: string
- container: ''
  name: Family
  type: string
- container: ''
  name: FiberOpticCableType
  type: string
- container: ''
  name: HostId
  type: string
- container: ''
  name: InstanceType
  type: string
- container: ''
  name: LifeCycleStatus
  type: string
- container: ''
  name: LineItemId
  type: string
- container: ''
  name: MacAddressList
  type: string
- container: ''
  name: MaxSize
  type: string
- container: ''
  name: MaximumSupportedWeightLbs
  type: string
- container: ''
  name: Municipality
  type: string
- container: ''
  name: NetworkInterfaceDeviceIndex
  type: string
- container: ''
  name: OpticalStandard
  type: string
- container: ''
  name: Order
  type: string
- container: ''
  name: OrderId
  type: string
- container: ''
  name: OrderType
  type: string
- container: ''
  name: Outpost
  type: string
- container: ''
  name: OutpostArn
  type: string
- container: ''
  name: OutpostId
  type: string
- container: ''
  name: OutpostIdentifier
  type: string
- container: ''
  name: OwnerId
  type: string
- container: ''
  name: PaymentOption
  type: string
- container: ''
  name: PaymentTerm
  type: string
- container: ''
  name: PostalCode
  type: string
- container: ''
  name: PowerConnector
  type: string
- container: ''
  name: PowerDrawKva
  type: string
- container: ''
  name: PowerFeedDrop
  type: string
- container: ''
  name: PowerPhase
  type: string
- container: ''
  name: Quantity
  type: string
- container: ''
  name: RackElevation
  type: string
- container: ''
  name: RackId
  type: string
- container: ''
  name: RackPhysicalProperties
  type: string
- container: ''
  name: ServerEndpoint
  type: string
- container: ''
  name: ShipmentCarrier
  type: string
- container: ''
  name: ShipmentInformation
  type: string
- container: ''
  name: Site
  type: string
- container: ''
  name: SiteArn
  type: string
- container: ''
  name: SiteId
  type: string
- container: ''
  name: StateOrRegion
  type: string
- container: ''
  name: SupportedHardwareType
  type: string
- container: ''
  name: SupportedUplinkGbps
  type: string
- container: ''
  name: UnderlayIpAddress
  type: string
- container: ''
  name: UplinkCount
  type: string
- container: ''
  name: UplinkGbps
  type: string
- container: ''
  name: AllowedIps
  type: string
- container: ''
  name: AssetInformationList
  type: string
- container: ''
  name: Assets
  type: string
- container: ''
  name: CatalogItemId
  type: string
- container: ''
  name: CatalogItems
  type: string
- container: ''
  name: ClientPublicKey
  type: string
- container: ''
  name: ClientTunnelAddress
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: EC2Capacities
  type: string
- container: ''
  name: InstanceTypes
  type: string
- container: ''
  name: ItemStatus
  type: string
- container: ''
  name: LineItemCountsByStatus
  type: string
- container: ''
  name: LineItems
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: Notes
  type: string
- container: ''
  name: OperatingAddress
  type: string
- container: ''
  name: OperatingAddressCity
  type: string
- container: ''
  name: OperatingAddressCountryCode
  type: string
- container: ''
  name: OperatingAddressStateOrRegion
  type: string
- container: ''
  name: OrderFulfilledDate
  type: string
- container: ''
  name: OrderSubmissionDate
  type: string
- container: ''
  name: Orders
  type: string
- container: ''
  name: Outposts
  type: string
- container: ''
  name: PowerKva
  type: string
- container: ''
  name: PreviousLineItemId
  type: string
- container: ''
  name: PreviousOrderId
  type: string
- container: ''
  name: ServerPublicKey
  type: string
- container: ''
  name: ServerTunnelAddress
  type: string
- container: ''
  name: ShipmentTrackingNumber
  type: string
- container: ''
  name: ShippingAddress
  type: string
- container: ''
  name: Sites
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: SupportedStorage
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: WeightLbs
  type: string
property_count: 101
provider_name: Amazon Outposts
provider_slug: amazon-outposts
slug: amazon-outposts-openapi-context
source_filename: amazon-outposts-openapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"outposts\": \"https://outposts.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccessDeniedException\": \"outposts:AccessDeniedException\",\n    \"AccountId\": {\n      \"@id\": \"outposts:AccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Address\": {\n      \"@id\": \"outposts:Address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AddressLine1\": {\n      \"@id\": \"outposts:AddressLine1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AddressLine2\": {\n      \"@id\": \"outposts:AddressLine2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AddressLine3\": {\n      \"@id\": \"outposts:AddressLine3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AddressType\": {\n      \"@id\": \"outposts:AddressType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Arn\": \"outposts:Arn\",\n\
  \    \"AssetId\": {\n      \"@id\": \"outposts:AssetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssetInfo\": \"outposts:AssetInfo\",\n    \"AssetListDefinition\": \"outposts:AssetListDefinition\",\n    \"AssetLocation\": {\n      \"@id\": \"outposts:AssetLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssetState\": \"outposts:AssetState\",\n    \"AssetType\": {\n      \"@id\": \"outposts:AssetType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AvailabilityZone\": {\n      \"@id\": \"outposts:AvailabilityZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AvailabilityZoneId\": {\n      \"@id\": \"outposts:AvailabilityZoneId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AvailabilityZoneIdList\": \"outposts:AvailabilityZoneIdList\",\n    \"AvailabilityZoneList\": \"outposts:AvailabilityZoneList\",\n    \"CIDR\": \"outposts:CIDR\",\n    \"CIDRList\": \"outposts:CIDRList\",\n    \"CancelOrderInput\": \"outposts:CancelOrderInput\",\n    \"CancelOrderOutput\"\
  : \"outposts:CancelOrderOutput\",\n    \"CatalogItem\": {\n      \"@id\": \"outposts:CatalogItem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CatalogItemClass\": \"outposts:CatalogItemClass\",\n    \"CatalogItemClassList\": \"outposts:CatalogItemClassList\",\n    \"CatalogItemListDefinition\": \"outposts:CatalogItemListDefinition\",\n    \"CatalogItemPowerKva\": \"outposts:CatalogItemPowerKva\",\n    \"CatalogItemStatus\": \"outposts:CatalogItemStatus\",\n    \"CatalogItemWeightLbs\": \"outposts:CatalogItemWeightLbs\",\n    \"City\": {\n      \"@id\": \"outposts:City\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CityList\": \"outposts:CityList\",\n    \"ComputeAssetState\": \"outposts:ComputeAssetState\",\n    \"ComputeAttributes\": {\n      \"@id\": \"outposts:ComputeAttributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConflictException\": \"outposts:ConflictException\",\n    \"ConnectionDetails\": {\n      \"@id\": \"outposts:ConnectionDetails\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"ConnectionId\": {\n      \"@id\": \"outposts:ConnectionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ContactName\": {\n      \"@id\": \"outposts:ContactName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ContactPhoneNumber\": {\n      \"@id\": \"outposts:ContactPhoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CountryCode\": {\n      \"@id\": \"outposts:CountryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CountryCodeList\": \"outposts:CountryCodeList\",\n    \"CreateOrderInput\": \"outposts:CreateOrderInput\",\n    \"CreateOrderOutput\": \"outposts:CreateOrderOutput\",\n    \"CreateOutpostInput\": \"outposts:CreateOutpostInput\",\n    \"CreateOutpostOutput\": \"outposts:CreateOutpostOutput\",\n    \"CreateSiteInput\": \"outposts:CreateSiteInput\",\n    \"CreateSiteOutput\": \"outposts:CreateSiteOutput\",\n    \"DeleteOutpostInput\": \"outposts:DeleteOutpostInput\",\n    \"DeleteOutpostOutput\": \"outposts:DeleteOutpostOutput\"\
  ,\n    \"DeleteSiteInput\": \"outposts:DeleteSiteInput\",\n    \"DeleteSiteOutput\": \"outposts:DeleteSiteOutput\",\n    \"DeviceSerialNumber\": {\n      \"@id\": \"outposts:DeviceSerialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DistrictOrCounty\": {\n      \"@id\": \"outposts:DistrictOrCounty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EC2Capacity\": \"outposts:EC2Capacity\",\n    \"EC2CapacityListDefinition\": \"outposts:EC2CapacityListDefinition\",\n    \"EC2FamilyList\": \"outposts:EC2FamilyList\",\n    \"Family\": {\n      \"@id\": \"outposts:Family\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FiberOpticCableType\": {\n      \"@id\": \"outposts:FiberOpticCableType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetCatalogItemInput\": \"outposts:GetCatalogItemInput\",\n    \"GetCatalogItemOutput\": \"outposts:GetCatalogItemOutput\",\n    \"GetConnectionRequest\": \"outposts:GetConnectionRequest\",\n    \"GetConnectionResponse\": \"outposts:GetConnectionResponse\"\
  ,\n    \"GetOrderInput\": \"outposts:GetOrderInput\",\n    \"GetOrderOutput\": \"outposts:GetOrderOutput\",\n    \"GetOutpostInput\": \"outposts:GetOutpostInput\",\n    \"GetOutpostInstanceTypesInput\": \"outposts:GetOutpostInstanceTypesInput\",\n    \"GetOutpostInstanceTypesOutput\": \"outposts:GetOutpostInstanceTypesOutput\",\n    \"GetOutpostOutput\": \"outposts:GetOutpostOutput\",\n    \"GetSiteAddressInput\": \"outposts:GetSiteAddressInput\",\n    \"GetSiteAddressOutput\": \"outposts:GetSiteAddressOutput\",\n    \"GetSiteInput\": \"outposts:GetSiteInput\",\n    \"GetSiteOutput\": \"outposts:GetSiteOutput\",\n    \"HostId\": {\n      \"@id\": \"outposts:HostId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HostIdList\": \"outposts:HostIdList\",\n    \"ISO8601Timestamp\": \"outposts:ISO8601Timestamp\",\n    \"InstanceType\": {\n      \"@id\": \"outposts:InstanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceTypeItem\": \"outposts:InstanceTypeItem\",\n    \"InstanceTypeListDefinition\"\
  : \"outposts:InstanceTypeListDefinition\",\n    \"InternalServerException\": \"outposts:InternalServerException\",\n    \"LifeCycleStatus\": {\n      \"@id\": \"outposts:LifeCycleStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LifeCycleStatusList\": \"outposts:LifeCycleStatusList\",\n    \"LineItem\": \"outposts:LineItem\",\n    \"LineItemAssetInformation\": \"outposts:LineItemAssetInformation\",\n    \"LineItemAssetInformationList\": \"outposts:LineItemAssetInformationList\",\n    \"LineItemId\": {\n      \"@id\": \"outposts:LineItemId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LineItemListDefinition\": \"outposts:LineItemListDefinition\",\n    \"LineItemQuantity\": \"outposts:LineItemQuantity\",\n    \"LineItemRequest\": \"outposts:LineItemRequest\",\n    \"LineItemRequestListDefinition\": \"outposts:LineItemRequestListDefinition\",\n    \"LineItemStatus\": \"outposts:LineItemStatus\",\n    \"LineItemStatusCounts\": \"outposts:LineItemStatusCounts\",\n    \"ListAssetsInput\"\
  : \"outposts:ListAssetsInput\",\n    \"ListAssetsOutput\": \"outposts:ListAssetsOutput\",\n    \"ListCatalogItemsInput\": \"outposts:ListCatalogItemsInput\",\n    \"ListCatalogItemsOutput\": \"outposts:ListCatalogItemsOutput\",\n    \"ListOrdersInput\": \"outposts:ListOrdersInput\",\n    \"ListOrdersOutput\": \"outposts:ListOrdersOutput\",\n    \"ListOutpostsInput\": \"outposts:ListOutpostsInput\",\n    \"ListOutpostsOutput\": \"outposts:ListOutpostsOutput\",\n    \"ListSitesInput\": \"outposts:ListSitesInput\",\n    \"ListSitesOutput\": \"outposts:ListSitesOutput\",\n    \"ListTagsForResourceRequest\": \"outposts:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"outposts:ListTagsForResourceResponse\",\n    \"MacAddress\": \"outposts:MacAddress\",\n    \"MacAddressList\": {\n      \"@id\": \"outposts:MacAddressList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxResults1000\": \"outposts:MaxResults1000\",\n    \"MaxSize\": {\n      \"@id\": \"outposts:MaxSize\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"MaximumSupportedWeightLbs\": {\n      \"@id\": \"outposts:MaximumSupportedWeightLbs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Municipality\": {\n      \"@id\": \"outposts:Municipality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NetworkInterfaceDeviceIndex\": {\n      \"@id\": \"outposts:NetworkInterfaceDeviceIndex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotFoundException\": \"outposts:NotFoundException\",\n    \"OpticalStandard\": {\n      \"@id\": \"outposts:OpticalStandard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Order\": {\n      \"@id\": \"outposts:Order\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OrderId\": {\n      \"@id\": \"outposts:OrderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OrderStatus\": \"outposts:OrderStatus\",\n    \"OrderSummary\": \"outposts:OrderSummary\",\n    \"OrderSummaryListDefinition\": \"outposts:OrderSummaryListDefinition\",\n    \"OrderType\": {\n     \
  \ \"@id\": \"outposts:OrderType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Outpost\": {\n      \"@id\": \"outposts:Outpost\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutpostArn\": {\n      \"@id\": \"outposts:OutpostArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutpostDescription\": \"outposts:OutpostDescription\",\n    \"OutpostId\": {\n      \"@id\": \"outposts:OutpostId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutpostIdOnly\": \"outposts:OutpostIdOnly\",\n    \"OutpostIdentifier\": {\n      \"@id\": \"outposts:OutpostIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutpostName\": \"outposts:OutpostName\",\n    \"OwnerId\": {\n      \"@id\": \"outposts:OwnerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentOption\": {\n      \"@id\": \"outposts:PaymentOption\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentTerm\": {\n      \"@id\": \"outposts:PaymentTerm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PostalCode\"\
  : {\n      \"@id\": \"outposts:PostalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PowerConnector\": {\n      \"@id\": \"outposts:PowerConnector\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PowerDrawKva\": {\n      \"@id\": \"outposts:PowerDrawKva\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PowerFeedDrop\": {\n      \"@id\": \"outposts:PowerFeedDrop\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PowerPhase\": {\n      \"@id\": \"outposts:PowerPhase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Quantity\": {\n      \"@id\": \"outposts:Quantity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RackElevation\": {\n      \"@id\": \"outposts:RackElevation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RackId\": {\n      \"@id\": \"outposts:RackId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RackPhysicalProperties\": {\n      \"@id\": \"outposts:RackPhysicalProperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServerEndpoint\": {\n      \"@id\"\
  : \"outposts:ServerEndpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceQuotaExceededException\": \"outposts:ServiceQuotaExceededException\",\n    \"ShipmentCarrier\": {\n      \"@id\": \"outposts:ShipmentCarrier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShipmentInformation\": {\n      \"@id\": \"outposts:ShipmentInformation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Site\": {\n      \"@id\": \"outposts:Site\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SiteArn\": {\n      \"@id\": \"outposts:SiteArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SiteDescription\": \"outposts:SiteDescription\",\n    \"SiteId\": {\n      \"@id\": \"outposts:SiteId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SiteName\": \"outposts:SiteName\",\n    \"SiteNotes\": \"outposts:SiteNotes\",\n    \"SkuCode\": \"outposts:SkuCode\",\n    \"StartConnectionRequest\": \"outposts:StartConnectionRequest\",\n    \"StartConnectionResponse\": \"outposts:StartConnectionResponse\"\
  ,\n    \"StateOrRegion\": {\n      \"@id\": \"outposts:StateOrRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StateOrRegionList\": \"outposts:StateOrRegionList\",\n    \"StatusList\": \"outposts:StatusList\",\n    \"SupportedHardwareType\": {\n      \"@id\": \"outposts:SupportedHardwareType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SupportedStorageEnum\": \"outposts:SupportedStorageEnum\",\n    \"SupportedStorageList\": \"outposts:SupportedStorageList\",\n    \"SupportedUplinkGbps\": {\n      \"@id\": \"outposts:SupportedUplinkGbps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SupportedUplinkGbpsListDefinition\": \"outposts:SupportedUplinkGbpsListDefinition\",\n    \"TagKey\": \"outposts:TagKey\",\n    \"TagKeyList\": \"outposts:TagKeyList\",\n    \"TagMap\": \"outposts:TagMap\",\n    \"TagResourceRequest\": \"outposts:TagResourceRequest\",\n    \"TagResourceResponse\": \"outposts:TagResourceResponse\",\n    \"TagValue\": \"outposts:TagValue\",\n    \"Token\": \"\
  outposts:Token\",\n    \"TrackingId\": \"outposts:TrackingId\",\n    \"UnderlayIpAddress\": {\n      \"@id\": \"outposts:UnderlayIpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UntagResourceRequest\": \"outposts:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"outposts:UntagResourceResponse\",\n    \"UpdateOutpostInput\": \"outposts:UpdateOutpostInput\",\n    \"UpdateOutpostOutput\": \"outposts:UpdateOutpostOutput\",\n    \"UpdateSiteAddressInput\": \"outposts:UpdateSiteAddressInput\",\n    \"UpdateSiteAddressOutput\": \"outposts:UpdateSiteAddressOutput\",\n    \"UpdateSiteInput\": \"outposts:UpdateSiteInput\",\n    \"UpdateSiteOutput\": \"outposts:UpdateSiteOutput\",\n    \"UpdateSiteRackPhysicalPropertiesInput\": \"outposts:UpdateSiteRackPhysicalPropertiesInput\",\n    \"UpdateSiteRackPhysicalPropertiesOutput\": \"outposts:UpdateSiteRackPhysicalPropertiesOutput\",\n    \"UplinkCount\": {\n      \"@id\": \"outposts:UplinkCount\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"UplinkGbps\": {\n      \"@id\": \"outposts:UplinkGbps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ValidationException\": \"outposts:ValidationException\",\n    \"WireGuardPublicKey\": \"outposts:WireGuardPublicKey\",\n    \"outpostListDefinition\": \"outposts:outpostListDefinition\",\n    \"siteListDefinition\": \"outposts:siteListDefinition\",\n    \"AllowedIps\": {\n      \"@id\": \"outposts:AllowedIps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssetInformationList\": {\n      \"@id\": \"outposts:AssetInformationList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Assets\": {\n      \"@id\": \"outposts:Assets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CatalogItemId\": {\n      \"@id\": \"outposts:CatalogItemId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CatalogItems\": {\n      \"@id\": \"outposts:CatalogItems\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClientPublicKey\": {\n      \"@id\": \"outposts:ClientPublicKey\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"ClientTunnelAddress\": {\n      \"@id\": \"outposts:ClientTunnelAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"outposts:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EC2Capacities\": {\n      \"@id\": \"outposts:EC2Capacities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceTypes\": {\n      \"@id\": \"outposts:InstanceTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ItemStatus\": {\n      \"@id\": \"outposts:ItemStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LineItemCountsByStatus\": {\n      \"@id\": \"outposts:LineItemCountsByStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LineItems\": {\n      \"@id\": \"outposts:LineItems\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"outposts:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"outposts:NextToken\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Notes\": {\n      \"@id\": \"outposts:Notes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OperatingAddress\": {\n      \"@id\": \"outposts:OperatingAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OperatingAddressCity\": {\n      \"@id\": \"outposts:OperatingAddressCity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OperatingAddressCountryCode\": {\n      \"@id\": \"outposts:OperatingAddressCountryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OperatingAddressStateOrRegion\": {\n      \"@id\": \"outposts:OperatingAddressStateOrRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OrderFulfilledDate\": {\n      \"@id\": \"outposts:OrderFulfilledDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OrderSubmissionDate\": {\n      \"@id\": \"outposts:OrderSubmissionDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Orders\": {\n      \"@id\": \"outposts:Orders\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Outposts\": {\n      \"\
  @id\": \"outposts:Outposts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PowerKva\": {\n      \"@id\": \"outposts:PowerKva\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PreviousLineItemId\": {\n      \"@id\": \"outposts:PreviousLineItemId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PreviousOrderId\": {\n      \"@id\": \"outposts:PreviousOrderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServerPublicKey\": {\n      \"@id\": \"outposts:ServerPublicKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServerTunnelAddress\": {\n      \"@id\": \"outposts:ServerTunnelAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShipmentTrackingNumber\": {\n      \"@id\": \"outposts:ShipmentTrackingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShippingAddress\": {\n      \"@id\": \"outposts:ShippingAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Sites\": {\n      \"@id\": \"outposts:Sites\",\n      \"@type\": \"xsd:string\"\n    },\n    \"State\"\
  : {\n      \"@id\": \"outposts:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"outposts:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SupportedStorage\": {\n      \"@id\": \"outposts:SupportedStorage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"outposts:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WeightLbs\": {\n      \"@id\": \"outposts:WeightLbs\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-outposts/refs/heads/main/json-ld/amazon-outposts-openapi-context.jsonld
tags:
- Edge Computing
- Hybrid Cloud
- Infrastructure
- On-Premises
- JSON-LD
- Linked Data
- Semantic Web
---
