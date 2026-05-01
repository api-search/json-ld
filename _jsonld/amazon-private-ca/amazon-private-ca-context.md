---
api_specs:
- filename: amazon-private-ca-openapi-original.yaml
  format: yaml
  label: AWS Private CA API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-private-ca/refs/heads/main/openapi/amazon-private-ca-openapi-original.yaml
class_count: 59
classes:
- Extensions
- ExtendedKeyUsage
- KeyUsage
- AccessDescription
- AccessMethod
- ASN1Subject
- UpdateCertificateAuthorityRequest
- RevocationConfiguration
- ApiPassthrough
- DeleteCertificateAuthorityRequest
- GeneralName
- OtherName
- EdiPartyName
- Qualifier
- DescribeCertificateAuthorityRequest
- GetPolicyResponse
- ListPermissionsRequest
- DescribeCertificateAuthorityAuditReportResponse
- PutPolicyRequest
- DescribeCertificateAuthorityAuditReportRequest
- PolicyQualifierInfo
- CreateCertificateAuthorityRequest
- CertificateAuthorityConfiguration
- ListTagsRequest
- CsrExtensions
- IssueCertificateResponse
- GetCertificateRequest
- GetCertificateAuthorityCsrRequest
- GetCertificateAuthorityCertificateResponse
- CustomExtension
- CrlConfiguration
- GetCertificateAuthorityCsrResponse
- RestoreCertificateAuthorityRequest
- IssueCertificateRequest
- Validity
- CustomAttribute
- RevokeCertificateRequest
- GetCertificateAuthorityCertificateRequest
- Tag
- UntagCertificateAuthorityRequest
- TagCertificateAuthorityRequest
- PolicyInformation
- ImportCertificateAuthorityCertificateRequest
- CreateCertificateAuthorityAuditReportResponse
- Permission
- DeletePolicyRequest
- CreatePermissionRequest
- CreateCertificateAuthorityResponse
- GetPolicyRequest
- OcspConfiguration
- ListCertificateAuthoritiesRequest
- CreateCertificateAuthorityAuditReportRequest
- DescribeCertificateAuthorityResponse
- CertificateAuthority
- ListTagsResponse
- ListCertificateAuthoritiesResponse
- ListPermissionsResponse
- DeletePermissionRequest
- GetCertificateResponse
context_file: json-ld/amazon-private-ca-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-private-ca/refs/heads/main/json-ld/amazon-private-ca-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Private Ca from Amazon Private CA.
layout: jsonld
name: Amazon Private Ca Context
namespaces:
- prefix: pca
  uri: https://acm-pca.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: CertificatePolicies
  type: string
- container: ''
  name: SubjectAlternativeNames
  type: string
- container: ''
  name: CustomExtensions
  type: string
- container: ''
  name: AccessLocation
  type: string
- container: ''
  name: Country
  type: string
- container: ''
  name: Organization
  type: string
- container: ''
  name: OrganizationalUnit
  type: string
- container: ''
  name: DistinguishedNameQualifier
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: CommonName
  type: string
- container: ''
  name: SerialNumber
  type: string
- container: ''
  name: Locality
  type: string
- container: ''
  name: Title
  type: string
- container: ''
  name: Surname
  type: string
- container: ''
  name: GivenName
  type: string
- container: ''
  name: Initials
  type: string
- container: ''
  name: Pseudonym
  type: string
- container: ''
  name: GenerationQualifier
  type: string
- container: ''
  name: CustomAttributes
  type: string
- container: ''
  name: CertificateAuthorityArn
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: Subject
  type: string
- container: ''
  name: PermanentDeletionTimeInDays
  type: string
- container: ''
  name: Rfc822Name
  type: string
- container: ''
  name: DnsName
  type: string
- container: ''
  name: DirectoryName
  type: string
- container: ''
  name: UniformResourceIdentifier
  type: string
- container: ''
  name: IpAddress
  type: string
- container: ''
  name: RegisteredId
  type: string
- container: ''
  name: CpsUri
  type: string
- container: ''
  name: Policy
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: MaxResults
  type: string
- container: ''
  name: AuditReportStatus
  type: string
- container: ''
  name: S3BucketName
  type: string
- container: ''
  name: S3Key
  type: string
- container: ''
  name: CreatedAt
  type: string
- container: ''
  name: ResourceArn
  type: string
- container: ''
  name: AuditReportId
  type: string
- container: ''
  name: DigitalSignature
  type: string
- container: ''
  name: NonRepudiation
  type: string
- container: ''
  name: KeyEncipherment
  type: string
- container: ''
  name: DataEncipherment
  type: string
- container: ''
  name: KeyAgreement
  type: string
- container: ''
  name: KeyCertSign
  type: string
- container: ''
  name: CRLSign
  type: string
- container: ''
  name: EncipherOnly
  type: string
- container: ''
  name: DecipherOnly
  type: string
- container: ''
  name: PolicyQualifierId
  type: string
- container: ''
  name: CertificateAuthorityType
  type: string
- container: ''
  name: IdempotencyToken
  type: string
- container: ''
  name: KeyStorageSecurityStandard
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: UsageMode
  type: string
- container: ''
  name: KeyAlgorithm
  type: string
- container: ''
  name: SigningAlgorithm
  type: string
- container: ''
  name: CertificateArn
  type: string
- container: ''
  name: Certificate
  type: string
- container: ''
  name: CertificateChain
  type: string
- container: ''
  name: ObjectIdentifier
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: Critical
  type: string
- container: ''
  name: SubjectInformationAccess
  type: string
- container: ''
  name: Enabled
  type: string
- container: ''
  name: ExpirationInDays
  type: string
- container: ''
  name: CustomCname
  type: string
- container: ''
  name: S3ObjectAcl
  type: string
- container: ''
  name: Csr
  type: string
- container: ''
  name: TemplateArn
  type: string
- container: ''
  name: ValidityNotBefore
  type: string
- container: ''
  name: CertificateSerial
  type: string
- container: ''
  name: RevocationReason
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: CertPolicyId
  type: string
- container: ''
  name: PolicyQualifiers
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: PartyName
  type: string
- container: ''
  name: NameAssigner
  type: string
- container: ''
  name: Principal
  type: string
- container: ''
  name: SourceAccount
  type: string
- container: ''
  name: Actions
  type: string
- container: ''
  name: ExtendedKeyUsageType
  type: string
- container: ''
  name: ExtendedKeyUsageObjectIdentifier
  type: string
- container: ''
  name: OcspCustomCname
  type: string
- container: ''
  name: ResourceOwner
  type: string
- container: ''
  name: TypeId
  type: string
- container: ''
  name: AuditReportResponseFormat
  type: string
- container: ''
  name: Arn
  type: string
- container: ''
  name: OwnerAccount
  type: string
- container: ''
  name: LastStateChangeAt
  type: string
- container: ''
  name: Serial
  type: string
- container: ''
  name: NotBefore
  type: string
- container: ''
  name: NotAfter
  type: string
- container: ''
  name: FailureReason
  type: string
- container: ''
  name: RestorableUntil
  type: string
- container: ''
  name: CertificateAuthorities
  type: string
- container: ''
  name: Permissions
  type: string
- container: ''
  name: CustomObjectIdentifier
  type: string
- container: ''
  name: AccessMethodType
  type: string
property_count: 99
provider_name: Amazon Private CA
provider_slug: amazon-private-ca
slug: amazon-private-ca-context
source_filename: amazon-private-ca-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pca\": \"https://acm-pca.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Extensions\": \"pca:Extensions\",\n    \"CertificatePolicies\": {\n      \"@id\": \"pca:CertificatePolicies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExtendedKeyUsage\": \"pca:ExtendedKeyUsage\",\n    \"KeyUsage\": \"pca:KeyUsage\",\n    \"SubjectAlternativeNames\": {\n      \"@id\": \"pca:SubjectAlternativeNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomExtensions\": {\n      \"@id\": \"pca:CustomExtensions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccessDescription\": \"pca:AccessDescription\",\n    \"AccessMethod\": \"pca:AccessMethod\",\n    \"AccessLocation\": {\n      \"@id\": \"pca:AccessLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ASN1Subject\": \"pca:ASN1Subject\",\n  \
  \  \"Country\": {\n      \"@id\": \"pca:Country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Organization\": {\n      \"@id\": \"pca:Organization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OrganizationalUnit\": {\n      \"@id\": \"pca:OrganizationalUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DistinguishedNameQualifier\": {\n      \"@id\": \"pca:DistinguishedNameQualifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"State\": {\n      \"@id\": \"pca:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CommonName\": {\n      \"@id\": \"pca:CommonName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SerialNumber\": {\n      \"@id\": \"pca:SerialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Locality\": {\n      \"@id\": \"pca:Locality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Title\": {\n      \"@id\": \"pca:Title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Surname\": {\n      \"@id\": \"pca:Surname\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"GivenName\": {\n      \"@id\": \"pca:GivenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Initials\": {\n      \"@id\": \"pca:Initials\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Pseudonym\": {\n      \"@id\": \"pca:Pseudonym\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GenerationQualifier\": {\n      \"@id\": \"pca:GenerationQualifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomAttributes\": {\n      \"@id\": \"pca:CustomAttributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateCertificateAuthorityRequest\": \"pca:UpdateCertificateAuthorityRequest\",\n    \"CertificateAuthorityArn\": {\n      \"@id\": \"pca:CertificateAuthorityArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RevocationConfiguration\": \"pca:RevocationConfiguration\",\n    \"Status\": {\n      \"@id\": \"pca:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApiPassthrough\": \"pca:ApiPassthrough\",\n    \"Subject\": {\n      \"@id\": \"pca:Subject\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteCertificateAuthorityRequest\": \"pca:DeleteCertificateAuthorityRequest\",\n    \"PermanentDeletionTimeInDays\": {\n      \"@id\": \"pca:PermanentDeletionTimeInDays\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GeneralName\": \"pca:GeneralName\",\n    \"OtherName\": \"pca:OtherName\",\n    \"Rfc822Name\": {\n      \"@id\": \"pca:Rfc822Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DnsName\": {\n      \"@id\": \"pca:DnsName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DirectoryName\": {\n      \"@id\": \"pca:DirectoryName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EdiPartyName\": \"pca:EdiPartyName\",\n    \"UniformResourceIdentifier\": {\n      \"@id\": \"pca:UniformResourceIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IpAddress\": {\n      \"@id\": \"pca:IpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RegisteredId\": {\n      \"@id\": \"pca:RegisteredId\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"Qualifier\": \"pca:Qualifier\",\n    \"CpsUri\": {\n      \"@id\": \"pca:CpsUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeCertificateAuthorityRequest\": \"pca:DescribeCertificateAuthorityRequest\",\n    \"GetPolicyResponse\": \"pca:GetPolicyResponse\",\n    \"Policy\": {\n      \"@id\": \"pca:Policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListPermissionsRequest\": \"pca:ListPermissionsRequest\",\n    \"NextToken\": {\n      \"@id\": \"pca:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxResults\": {\n      \"@id\": \"pca:MaxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeCertificateAuthorityAuditReportResponse\": \"pca:DescribeCertificateAuthorityAuditReportResponse\",\n    \"AuditReportStatus\": {\n      \"@id\": \"pca:AuditReportStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3BucketName\": {\n      \"@id\": \"pca:S3BucketName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3Key\"\
  : {\n      \"@id\": \"pca:S3Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedAt\": {\n      \"@id\": \"pca:CreatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PutPolicyRequest\": \"pca:PutPolicyRequest\",\n    \"ResourceArn\": {\n      \"@id\": \"pca:ResourceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeCertificateAuthorityAuditReportRequest\": \"pca:DescribeCertificateAuthorityAuditReportRequest\",\n    \"AuditReportId\": {\n      \"@id\": \"pca:AuditReportId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DigitalSignature\": {\n      \"@id\": \"pca:DigitalSignature\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NonRepudiation\": {\n      \"@id\": \"pca:NonRepudiation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyEncipherment\": {\n      \"@id\": \"pca:KeyEncipherment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DataEncipherment\": {\n      \"@id\": \"pca:DataEncipherment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyAgreement\"\
  : {\n      \"@id\": \"pca:KeyAgreement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyCertSign\": {\n      \"@id\": \"pca:KeyCertSign\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CRLSign\": {\n      \"@id\": \"pca:CRLSign\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EncipherOnly\": {\n      \"@id\": \"pca:EncipherOnly\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DecipherOnly\": {\n      \"@id\": \"pca:DecipherOnly\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PolicyQualifierInfo\": \"pca:PolicyQualifierInfo\",\n    \"PolicyQualifierId\": {\n      \"@id\": \"pca:PolicyQualifierId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateCertificateAuthorityRequest\": \"pca:CreateCertificateAuthorityRequest\",\n    \"CertificateAuthorityConfiguration\": \"pca:CertificateAuthorityConfiguration\",\n    \"CertificateAuthorityType\": {\n      \"@id\": \"pca:CertificateAuthorityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdempotencyToken\": {\n      \"\
  @id\": \"pca:IdempotencyToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyStorageSecurityStandard\": {\n      \"@id\": \"pca:KeyStorageSecurityStandard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"pca:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UsageMode\": {\n      \"@id\": \"pca:UsageMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListTagsRequest\": \"pca:ListTagsRequest\",\n    \"KeyAlgorithm\": {\n      \"@id\": \"pca:KeyAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SigningAlgorithm\": {\n      \"@id\": \"pca:SigningAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CsrExtensions\": \"pca:CsrExtensions\",\n    \"IssueCertificateResponse\": \"pca:IssueCertificateResponse\",\n    \"CertificateArn\": {\n      \"@id\": \"pca:CertificateArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetCertificateRequest\": \"pca:GetCertificateRequest\",\n    \"GetCertificateAuthorityCsrRequest\": \"pca:GetCertificateAuthorityCsrRequest\"\
  ,\n    \"GetCertificateAuthorityCertificateResponse\": \"pca:GetCertificateAuthorityCertificateResponse\",\n    \"Certificate\": {\n      \"@id\": \"pca:Certificate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CertificateChain\": {\n      \"@id\": \"pca:CertificateChain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomExtension\": \"pca:CustomExtension\",\n    \"ObjectIdentifier\": {\n      \"@id\": \"pca:ObjectIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"pca:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Critical\": {\n      \"@id\": \"pca:Critical\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubjectInformationAccess\": {\n      \"@id\": \"pca:SubjectInformationAccess\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CrlConfiguration\": \"pca:CrlConfiguration\",\n    \"Enabled\": {\n      \"@id\": \"pca:Enabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExpirationInDays\": {\n      \"@id\": \"pca:ExpirationInDays\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomCname\": {\n      \"@id\": \"pca:CustomCname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3ObjectAcl\": {\n      \"@id\": \"pca:S3ObjectAcl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetCertificateAuthorityCsrResponse\": \"pca:GetCertificateAuthorityCsrResponse\",\n    \"Csr\": {\n      \"@id\": \"pca:Csr\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RestoreCertificateAuthorityRequest\": \"pca:RestoreCertificateAuthorityRequest\",\n    \"IssueCertificateRequest\": \"pca:IssueCertificateRequest\",\n    \"TemplateArn\": {\n      \"@id\": \"pca:TemplateArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Validity\": \"pca:Validity\",\n    \"ValidityNotBefore\": {\n      \"@id\": \"pca:ValidityNotBefore\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomAttribute\": \"pca:CustomAttribute\",\n    \"RevokeCertificateRequest\": \"pca:RevokeCertificateRequest\",\n    \"CertificateSerial\": {\n      \"@id\": \"\
  pca:CertificateSerial\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RevocationReason\": {\n      \"@id\": \"pca:RevocationReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetCertificateAuthorityCertificateRequest\": \"pca:GetCertificateAuthorityCertificateRequest\",\n    \"Tag\": \"pca:Tag\",\n    \"Key\": {\n      \"@id\": \"pca:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UntagCertificateAuthorityRequest\": \"pca:UntagCertificateAuthorityRequest\",\n    \"TagCertificateAuthorityRequest\": \"pca:TagCertificateAuthorityRequest\",\n    \"PolicyInformation\": \"pca:PolicyInformation\",\n    \"CertPolicyId\": {\n      \"@id\": \"pca:CertPolicyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PolicyQualifiers\": {\n      \"@id\": \"pca:PolicyQualifiers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImportCertificateAuthorityCertificateRequest\": \"pca:ImportCertificateAuthorityCertificateRequest\",\n    \"CreateCertificateAuthorityAuditReportResponse\": \"pca:CreateCertificateAuthorityAuditReportResponse\"\
  ,\n    \"Type\": {\n      \"@id\": \"pca:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PartyName\": {\n      \"@id\": \"pca:PartyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NameAssigner\": {\n      \"@id\": \"pca:NameAssigner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Permission\": \"pca:Permission\",\n    \"Principal\": {\n      \"@id\": \"pca:Principal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceAccount\": {\n      \"@id\": \"pca:SourceAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Actions\": {\n      \"@id\": \"pca:Actions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeletePolicyRequest\": \"pca:DeletePolicyRequest\",\n    \"CreatePermissionRequest\": \"pca:CreatePermissionRequest\",\n    \"ExtendedKeyUsageType\": {\n      \"@id\": \"pca:ExtendedKeyUsageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExtendedKeyUsageObjectIdentifier\": {\n      \"@id\": \"pca:ExtendedKeyUsageObjectIdentifier\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"CreateCertificateAuthorityResponse\": \"pca:CreateCertificateAuthorityResponse\",\n    \"GetPolicyRequest\": \"pca:GetPolicyRequest\",\n    \"OcspConfiguration\": \"pca:OcspConfiguration\",\n    \"OcspCustomCname\": {\n      \"@id\": \"pca:OcspCustomCname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListCertificateAuthoritiesRequest\": \"pca:ListCertificateAuthoritiesRequest\",\n    \"ResourceOwner\": {\n      \"@id\": \"pca:ResourceOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TypeId\": {\n      \"@id\": \"pca:TypeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateCertificateAuthorityAuditReportRequest\": \"pca:CreateCertificateAuthorityAuditReportRequest\",\n    \"AuditReportResponseFormat\": {\n      \"@id\": \"pca:AuditReportResponseFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeCertificateAuthorityResponse\": \"pca:DescribeCertificateAuthorityResponse\",\n    \"CertificateAuthority\": \"pca:CertificateAuthority\"\
  ,\n    \"ListTagsResponse\": \"pca:ListTagsResponse\",\n    \"Arn\": {\n      \"@id\": \"pca:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OwnerAccount\": {\n      \"@id\": \"pca:OwnerAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastStateChangeAt\": {\n      \"@id\": \"pca:LastStateChangeAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Serial\": {\n      \"@id\": \"pca:Serial\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotBefore\": {\n      \"@id\": \"pca:NotBefore\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotAfter\": {\n      \"@id\": \"pca:NotAfter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FailureReason\": {\n      \"@id\": \"pca:FailureReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RestorableUntil\": {\n      \"@id\": \"pca:RestorableUntil\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListCertificateAuthoritiesResponse\": \"pca:ListCertificateAuthoritiesResponse\",\n    \"CertificateAuthorities\": {\n      \"@id\"\
  : \"pca:CertificateAuthorities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListPermissionsResponse\": \"pca:ListPermissionsResponse\",\n    \"Permissions\": {\n      \"@id\": \"pca:Permissions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeletePermissionRequest\": \"pca:DeletePermissionRequest\",\n    \"GetCertificateResponse\": \"pca:GetCertificateResponse\",\n    \"CustomObjectIdentifier\": {\n      \"@id\": \"pca:CustomObjectIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccessMethodType\": {\n      \"@id\": \"pca:AccessMethodType\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-private-ca/refs/heads/main/json-ld/amazon-private-ca-context.jsonld
tags:
- Certificate Authority
- Certificates
- PKI
- Security
- X.509
- TLS
- IoT
- JSON-LD
- Linked Data
- Semantic Web
---
