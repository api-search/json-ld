---
class_count: 71
classes:
- AccessDeniedException
- Boolean
- CertificateType
- ConflictException
- CreateAliasInput
- CreateAliasOutput
- CreateKeyInput
- CreateKeyOutput
- DeleteAliasInput
- DeleteAliasOutput
- DeleteKeyInput
- DeleteKeyInputDeleteKeyInDaysInteger
- DeleteKeyOutput
- ExportKeyInput
- ExportKeyMaterial
- ExportKeyOutput
- ExportTokenId
- ExportTr31KeyBlock
- ExportTr34KeyBlock
- GetAliasInput
- GetAliasOutput
- GetKeyInput
- GetKeyOutput
- GetParametersForExportInput
- GetParametersForExportOutput
- GetParametersForImportInput
- GetParametersForImportOutput
- GetPublicKeyCertificateInput
- GetPublicKeyCertificateOutput
- HexLength16
- ImportKeyInput
- ImportKeyMaterial
- ImportKeyOutput
- ImportTokenId
- ImportTr31KeyBlock
- ImportTr34KeyBlock
- InternalServerException
- KeyArnOrKeyAliasType
- KeySummary
- KeySummaryList
- ListAliasesInput
- ListAliasesOutput
- ListKeysInput
- ListKeysOutput
- ListTagsForResourceInput
- ListTagsForResourceOutput
- PrimitiveBoolean
- ResourceNotFoundException
- RestoreKeyInput
- RestoreKeyOutput
- ServiceQuotaExceededException
- ServiceUnavailableException
- StartKeyUsageInput
- StartKeyUsageOutput
- StopKeyUsageInput
- StopKeyUsageOutput
- Tag
- TagKey
- TagResourceInput
- TagResourceOutput
- TagValue
- ThrottlingException
- Timestamp
- Tr31WrappedKeyBlock
- Tr34KeyBlockFormat
- Tr34WrappedKeyBlock
- UntagResourceInput
- UntagResourceOutput
- UpdateAliasInput
- UpdateAliasOutput
- ValidationException
context_file: json-ld/amazon-payment-cryptography-openapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-payment-cryptography/refs/heads/main/json-ld/amazon-payment-cryptography-openapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Payment Cryptography Openapi from Amazon Payment Cryptography.
layout: jsonld
name: Amazon Payment Cryptography Openapi Context
namespaces:
- prefix: payment
  uri: https://payment.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Alias
  type: string
- container: ''
  name: AliasName
  type: string
- container: ''
  name: Aliases
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: KeyAlgorithm
  type: string
- container: ''
  name: KeyArn
  type: string
- container: ''
  name: KeyAttributes
  type: string
- container: ''
  name: KeyCheckValue
  type: string
- container: ''
  name: KeyCheckValueAlgorithm
  type: string
- container: ''
  name: KeyClass
  type: string
- container: ''
  name: KeyMaterial
  type: string
- container: ''
  name: KeyMaterialType
  type: string
- container: ''
  name: KeyModesOfUse
  type: string
- container: ''
  name: KeyOrigin
  type: string
- container: ''
  name: KeyState
  type: string
- container: ''
  name: KeyUsage
  type: string
- container: ''
  name: MaxResults
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: ResourceArn
  type: string
- container: ''
  name: RootCertificatePublicKey
  type: string
- container: ''
  name: TagKeys
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: TrustedCertificatePublicKey
  type: string
- container: ''
  name: WrappedKey
  type: string
- container: ''
  name: WrappedKeyMaterialFormat
  type: string
- container: ''
  name: CertificateAuthorityPublicKeyIdentifier
  type: string
- container: ''
  name: CreateTimestamp
  type: string
- container: ''
  name: Decrypt
  type: string
- container: ''
  name: DeleteKeyInDays
  type: string
- container: ''
  name: DeletePendingTimestamp
  type: string
- container: ''
  name: DeleteTimestamp
  type: string
- container: ''
  name: DeriveKey
  type: string
- container: ''
  name: Enabled
  type: string
- container: ''
  name: Encrypt
  type: string
- container: ''
  name: ExportKeyIdentifier
  type: string
- container: ''
  name: ExportToken
  type: string
- container: ''
  name: Exportable
  type: string
- container: ''
  name: Generate
  type: string
- container: ''
  name: ImportToken
  type: string
- container: ''
  name: KeyBlockFormat
  type: string
- container: ''
  name: KeyCertificate
  type: string
- container: ''
  name: KeyCertificateChain
  type: string
- container: ''
  name: KeyIdentifier
  type: string
- container: ''
  name: Keys
  type: string
- container: ''
  name: NoRestrictions
  type: string
- container: ''
  name: ParametersValidUntilTimestamp
  type: string
- container: ''
  name: PublicKeyCertificate
  type: string
- container: ''
  name: RandomNonce
  type: string
- container: ''
  name: Sign
  type: string
- container: ''
  name: SigningKeyAlgorithm
  type: string
- container: ''
  name: SigningKeyCertificate
  type: string
- container: ''
  name: SigningKeyCertificateChain
  type: string
- container: ''
  name: Tr31KeyBlock
  type: string
- container: ''
  name: Tr34KeyBlock
  type: string
- container: ''
  name: Unwrap
  type: string
- container: ''
  name: UsageStartTimestamp
  type: string
- container: ''
  name: UsageStopTimestamp
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: Verify
  type: string
- container: ''
  name: Wrap
  type: string
- container: ''
  name: WrappedKeyBlock
  type: string
- container: ''
  name: WrappingKeyAlgorithm
  type: string
- container: ''
  name: WrappingKeyArn
  type: string
- container: ''
  name: WrappingKeyCertificate
  type: string
- container: ''
  name: WrappingKeyCertificateChain
  type: string
- container: ''
  name: WrappingKeyIdentifier
  type: string
property_count: 66
provider_name: Amazon Payment Cryptography
provider_slug: amazon-payment-cryptography
slug: amazon-payment-cryptography-openapi-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"payment\": \"https://payment.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccessDeniedException\": \"payment:AccessDeniedException\",\n    \"Alias\": {\n      \"@id\": \"payment:Alias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AliasName\": {\n      \"@id\": \"payment:AliasName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Aliases\": {\n      \"@id\": \"payment:Aliases\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Boolean\": \"payment:Boolean\",\n    \"CertificateType\": \"payment:CertificateType\",\n    \"ConflictException\": \"payment:ConflictException\",\n    \"CreateAliasInput\": \"payment:CreateAliasInput\",\n    \"CreateAliasOutput\": \"payment:CreateAliasOutput\",\n    \"CreateKeyInput\": \"payment:CreateKeyInput\",\n    \"CreateKeyOutput\": \"payment:CreateKeyOutput\",\n\
  \    \"DeleteAliasInput\": \"payment:DeleteAliasInput\",\n    \"DeleteAliasOutput\": \"payment:DeleteAliasOutput\",\n    \"DeleteKeyInput\": \"payment:DeleteKeyInput\",\n    \"DeleteKeyInputDeleteKeyInDaysInteger\": \"payment:DeleteKeyInputDeleteKeyInDaysInteger\",\n    \"DeleteKeyOutput\": \"payment:DeleteKeyOutput\",\n    \"ExportKeyInput\": \"payment:ExportKeyInput\",\n    \"ExportKeyMaterial\": \"payment:ExportKeyMaterial\",\n    \"ExportKeyOutput\": \"payment:ExportKeyOutput\",\n    \"ExportTokenId\": \"payment:ExportTokenId\",\n    \"ExportTr31KeyBlock\": \"payment:ExportTr31KeyBlock\",\n    \"ExportTr34KeyBlock\": \"payment:ExportTr34KeyBlock\",\n    \"GetAliasInput\": \"payment:GetAliasInput\",\n    \"GetAliasOutput\": \"payment:GetAliasOutput\",\n    \"GetKeyInput\": \"payment:GetKeyInput\",\n    \"GetKeyOutput\": \"payment:GetKeyOutput\",\n    \"GetParametersForExportInput\": \"payment:GetParametersForExportInput\",\n    \"GetParametersForExportOutput\": \"payment:GetParametersForExportOutput\"\
  ,\n    \"GetParametersForImportInput\": \"payment:GetParametersForImportInput\",\n    \"GetParametersForImportOutput\": \"payment:GetParametersForImportOutput\",\n    \"GetPublicKeyCertificateInput\": \"payment:GetPublicKeyCertificateInput\",\n    \"GetPublicKeyCertificateOutput\": \"payment:GetPublicKeyCertificateOutput\",\n    \"HexLength16\": \"payment:HexLength16\",\n    \"ImportKeyInput\": \"payment:ImportKeyInput\",\n    \"ImportKeyMaterial\": \"payment:ImportKeyMaterial\",\n    \"ImportKeyOutput\": \"payment:ImportKeyOutput\",\n    \"ImportTokenId\": \"payment:ImportTokenId\",\n    \"ImportTr31KeyBlock\": \"payment:ImportTr31KeyBlock\",\n    \"ImportTr34KeyBlock\": \"payment:ImportTr34KeyBlock\",\n    \"InternalServerException\": \"payment:InternalServerException\",\n    \"Key\": {\n      \"@id\": \"payment:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyAlgorithm\": {\n      \"@id\": \"payment:KeyAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyArn\": {\n\
  \      \"@id\": \"payment:KeyArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyArnOrKeyAliasType\": \"payment:KeyArnOrKeyAliasType\",\n    \"KeyAttributes\": {\n      \"@id\": \"payment:KeyAttributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyCheckValue\": {\n      \"@id\": \"payment:KeyCheckValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyCheckValueAlgorithm\": {\n      \"@id\": \"payment:KeyCheckValueAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyClass\": {\n      \"@id\": \"payment:KeyClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyMaterial\": {\n      \"@id\": \"payment:KeyMaterial\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyMaterialType\": {\n      \"@id\": \"payment:KeyMaterialType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyModesOfUse\": {\n      \"@id\": \"payment:KeyModesOfUse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyOrigin\": {\n      \"@id\": \"payment:KeyOrigin\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"KeyState\": {\n      \"@id\": \"payment:KeyState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeySummary\": \"payment:KeySummary\",\n    \"KeySummaryList\": \"payment:KeySummaryList\",\n    \"KeyUsage\": {\n      \"@id\": \"payment:KeyUsage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListAliasesInput\": \"payment:ListAliasesInput\",\n    \"ListAliasesOutput\": \"payment:ListAliasesOutput\",\n    \"ListKeysInput\": \"payment:ListKeysInput\",\n    \"ListKeysOutput\": \"payment:ListKeysOutput\",\n    \"ListTagsForResourceInput\": \"payment:ListTagsForResourceInput\",\n    \"ListTagsForResourceOutput\": \"payment:ListTagsForResourceOutput\",\n    \"MaxResults\": {\n      \"@id\": \"payment:MaxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"payment:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PrimitiveBoolean\": \"payment:PrimitiveBoolean\",\n    \"ResourceArn\": {\n      \"@id\": \"payment:ResourceArn\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceNotFoundException\": \"payment:ResourceNotFoundException\",\n    \"RestoreKeyInput\": \"payment:RestoreKeyInput\",\n    \"RestoreKeyOutput\": \"payment:RestoreKeyOutput\",\n    \"RootCertificatePublicKey\": {\n      \"@id\": \"payment:RootCertificatePublicKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceQuotaExceededException\": \"payment:ServiceQuotaExceededException\",\n    \"ServiceUnavailableException\": \"payment:ServiceUnavailableException\",\n    \"StartKeyUsageInput\": \"payment:StartKeyUsageInput\",\n    \"StartKeyUsageOutput\": \"payment:StartKeyUsageOutput\",\n    \"StopKeyUsageInput\": \"payment:StopKeyUsageInput\",\n    \"StopKeyUsageOutput\": \"payment:StopKeyUsageOutput\",\n    \"Tag\": \"payment:Tag\",\n    \"TagKey\": \"payment:TagKey\",\n    \"TagKeys\": {\n      \"@id\": \"payment:TagKeys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TagResourceInput\": \"payment:TagResourceInput\",\n    \"TagResourceOutput\"\
  : \"payment:TagResourceOutput\",\n    \"TagValue\": \"payment:TagValue\",\n    \"Tags\": {\n      \"@id\": \"payment:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ThrottlingException\": \"payment:ThrottlingException\",\n    \"Timestamp\": \"payment:Timestamp\",\n    \"Tr31WrappedKeyBlock\": \"payment:Tr31WrappedKeyBlock\",\n    \"Tr34KeyBlockFormat\": \"payment:Tr34KeyBlockFormat\",\n    \"Tr34WrappedKeyBlock\": \"payment:Tr34WrappedKeyBlock\",\n    \"TrustedCertificatePublicKey\": {\n      \"@id\": \"payment:TrustedCertificatePublicKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UntagResourceInput\": \"payment:UntagResourceInput\",\n    \"UntagResourceOutput\": \"payment:UntagResourceOutput\",\n    \"UpdateAliasInput\": \"payment:UpdateAliasInput\",\n    \"UpdateAliasOutput\": \"payment:UpdateAliasOutput\",\n    \"ValidationException\": \"payment:ValidationException\",\n    \"WrappedKey\": {\n      \"@id\": \"payment:WrappedKey\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"WrappedKeyMaterialFormat\": {\n      \"@id\": \"payment:WrappedKeyMaterialFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CertificateAuthorityPublicKeyIdentifier\": {\n      \"@id\": \"payment:CertificateAuthorityPublicKeyIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateTimestamp\": {\n      \"@id\": \"payment:CreateTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Decrypt\": {\n      \"@id\": \"payment:Decrypt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteKeyInDays\": {\n      \"@id\": \"payment:DeleteKeyInDays\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeletePendingTimestamp\": {\n      \"@id\": \"payment:DeletePendingTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteTimestamp\": {\n      \"@id\": \"payment:DeleteTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeriveKey\": {\n      \"@id\": \"payment:DeriveKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Enabled\": {\n      \"\
  @id\": \"payment:Enabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Encrypt\": {\n      \"@id\": \"payment:Encrypt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExportKeyIdentifier\": {\n      \"@id\": \"payment:ExportKeyIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExportToken\": {\n      \"@id\": \"payment:ExportToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Exportable\": {\n      \"@id\": \"payment:Exportable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Generate\": {\n      \"@id\": \"payment:Generate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImportToken\": {\n      \"@id\": \"payment:ImportToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyBlockFormat\": {\n      \"@id\": \"payment:KeyBlockFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyCertificate\": {\n      \"@id\": \"payment:KeyCertificate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyCertificateChain\": {\n      \"@id\": \"payment:KeyCertificateChain\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyIdentifier\": {\n      \"@id\": \"payment:KeyIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Keys\": {\n      \"@id\": \"payment:Keys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NoRestrictions\": {\n      \"@id\": \"payment:NoRestrictions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ParametersValidUntilTimestamp\": {\n      \"@id\": \"payment:ParametersValidUntilTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PublicKeyCertificate\": {\n      \"@id\": \"payment:PublicKeyCertificate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RandomNonce\": {\n      \"@id\": \"payment:RandomNonce\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Sign\": {\n      \"@id\": \"payment:Sign\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SigningKeyAlgorithm\": {\n      \"@id\": \"payment:SigningKeyAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SigningKeyCertificate\": {\n      \"@id\": \"payment:SigningKeyCertificate\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"SigningKeyCertificateChain\": {\n      \"@id\": \"payment:SigningKeyCertificateChain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tr31KeyBlock\": {\n      \"@id\": \"payment:Tr31KeyBlock\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tr34KeyBlock\": {\n      \"@id\": \"payment:Tr34KeyBlock\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Unwrap\": {\n      \"@id\": \"payment:Unwrap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UsageStartTimestamp\": {\n      \"@id\": \"payment:UsageStartTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UsageStopTimestamp\": {\n      \"@id\": \"payment:UsageStopTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"payment:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Verify\": {\n      \"@id\": \"payment:Verify\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Wrap\": {\n      \"@id\": \"payment:Wrap\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"WrappedKeyBlock\": {\n      \"@id\": \"payment:WrappedKeyBlock\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WrappingKeyAlgorithm\": {\n      \"@id\": \"payment:WrappingKeyAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WrappingKeyArn\": {\n      \"@id\": \"payment:WrappingKeyArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WrappingKeyCertificate\": {\n      \"@id\": \"payment:WrappingKeyCertificate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WrappingKeyCertificateChain\": {\n      \"@id\": \"payment:WrappingKeyCertificateChain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WrappingKeyIdentifier\": {\n      \"@id\": \"payment:WrappingKeyIdentifier\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-payment-cryptography/refs/heads/main/json-ld/amazon-payment-cryptography-openapi-context.jsonld
tags:
- AWS
- Cryptography
- Financial Services
- Payment Processing
- PCI
- JSON-LD
- Linked Data
- Semantic Web
---
