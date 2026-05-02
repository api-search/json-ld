---
api_specs:
- filename: keyvault.json
  format: json
  label: Azure Key Vault API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/keyvault/resource-manager/Microsoft.KeyVault/stable/2023-02-01/keyvault.json
- filename: keyvault.json
  format: json
  label: Azure Key Vault Data Plane API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/keyvault/data-plane/Microsoft.KeyVault/stable/7.4/keyvault.json
class_count: 0
classes: []
context_file: json-ld/azure-key-vault-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-key-vault/refs/heads/main/json-ld/azure-key-vault-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Key Vault from Azure Key Vault.
layout: jsonld
name: Azure Key Vault Context
namespaces:
- prefix: kv
  uri: https://schema.api.gov/azure/key-vault/
- prefix: azure
  uri: https://schema.api.gov/azure/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: sec
  uri: https://w3id.org/security#
- prefix: jwk
  uri: https://www.iana.org/assignments/jose/
properties:
- container: ''
  name: KeyVault
  type: reference
- container: ''
  name: SecretBundle
  type: reference
- container: ''
  name: KeyBundle
  type: reference
- container: ''
  name: CertificateBundle
  type: reference
- container: ''
  name: CertificatePolicy
  type: reference
- container: ''
  name: CertificateOperation
  type: reference
- container: ''
  name: JsonWebKey
  type: reference
- container: ''
  name: id
  type: reference
- container: ''
  name: kid
  type: reference
- container: ''
  name: sid
  type: reference
- container: ''
  name: value
  type: ''
- container: ''
  name: contentType
  type: ''
- container: ''
  name: attributes
  type: reference
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: nbf
  type: integer
- container: ''
  name: exp
  type: integer
- container: ''
  name: created
  type: integer
- container: ''
  name: updated
  type: integer
- container: ''
  name: recoveryLevel
  type: ''
- container: ''
  name: recoverableDays
  type: integer
- container: ''
  name: managed
  type: boolean
- container: ''
  name: tags
  type: ''
- container: ''
  name: key
  type: reference
- container: ''
  name: kty
  type: ''
- container: ''
  name: key_ops
  type: ''
- container: ''
  name: key_size
  type: integer
- container: ''
  name: crv
  type: ''
- container: ''
  name: n
  type: ''
- container: ''
  name: e
  type: ''
- container: ''
  name: d
  type: ''
- container: ''
  name: x
  type: ''
- container: ''
  name: y
  type: ''
- container: ''
  name: release_policy
  type: reference
- container: ''
  name: exportable
  type: boolean
- container: ''
  name: policy
  type: reference
- container: ''
  name: key_props
  type: reference
- container: ''
  name: secret_props
  type: reference
- container: ''
  name: x509_props
  type: reference
- container: ''
  name: issuer
  type: reference
- container: ''
  name: subject
  type: ''
- container: ''
  name: sans
  type: reference
- container: ''
  name: dns_names
  type: ''
- container: ''
  name: emails
  type: ''
- container: ''
  name: validity_months
  type: integer
- container: ''
  name: lifetime_actions
  type: ''
- container: ''
  name: reuse_key
  type: boolean
- container: ''
  name: cer
  type: ''
- container: ''
  name: x5t
  type: ''
- container: ''
  name: csr
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: request_id
  type: ''
- container: ''
  name: recoveryId
  type: reference
- container: ''
  name: scheduledPurgeDate
  type: integer
- container: ''
  name: deletedDate
  type: integer
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: url
  type: reference
property_count: 57
provider_name: Azure Key Vault
provider_slug: microsoft-azure-key-vault
slug: azure-key-vault-context
source_filename: azure-key-vault-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.api.gov/azure/key-vault/\",\n    \"kv\": \"https://schema.api.gov/azure/key-vault/\",\n    \"azure\": \"https://schema.api.gov/azure/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"jwk\": \"https://www.iana.org/assignments/jose/\",\n\n    \"KeyVault\": {\n      \"@id\": \"kv:KeyVault\",\n      \"@type\": \"@id\",\n      \"comment\": \"An Azure Key Vault instance that securely stores and manages keys, secrets, and certificates.\"\n    },\n\n    \"SecretBundle\": {\n      \"@id\": \"kv:SecretBundle\",\n      \"@type\": \"@id\",\n      \"comment\": \"A secret consisting of a value, identifier, and its management attributes.\"\n    },\n    \"KeyBundle\": {\n      \"@id\": \"kv:KeyBundle\",\n      \"@type\": \"@id\",\n      \"comment\": \"A key bundle consisting of a JSON Web Key plus its attributes.\"\n    },\n    \"CertificateBundle\"\
  : {\n      \"@id\": \"kv:CertificateBundle\",\n      \"@type\": \"@id\",\n      \"comment\": \"A certificate bundle consisting of an X.509 certificate plus its attributes and policy.\"\n    },\n    \"CertificatePolicy\": {\n      \"@id\": \"kv:CertificatePolicy\",\n      \"@type\": \"@id\",\n      \"comment\": \"Management policy for a certificate including key properties, issuer, and X.509 properties.\"\n    },\n    \"CertificateOperation\": {\n      \"@id\": \"kv:CertificateOperation\",\n      \"@type\": \"@id\",\n      \"comment\": \"A certificate operation returned for asynchronous certificate creation requests.\"\n    },\n    \"JsonWebKey\": {\n      \"@id\": \"kv:JsonWebKey\",\n      \"@type\": \"@id\",\n      \"comment\": \"A JSON Web Key as defined in RFC 7517.\"\n    },\n\n    \"id\": {\n      \"@id\": \"kv:identifier\",\n      \"@type\": \"@id\",\n      \"comment\": \"The unique identifier (URI) of a key, secret, or certificate in the vault.\"\n    },\n    \"kid\": {\n      \"\
  @id\": \"kv:keyIdentifier\",\n      \"@type\": \"@id\",\n      \"comment\": \"The key identifier URI.\"\n    },\n    \"sid\": {\n      \"@id\": \"kv:secretIdentifier\",\n      \"@type\": \"@id\",\n      \"comment\": \"The secret identifier URI.\"\n    },\n    \"value\": {\n      \"@id\": \"kv:value\",\n      \"comment\": \"The value of a secret or the result of a cryptographic operation.\"\n    },\n    \"contentType\": {\n      \"@id\": \"kv:contentType\",\n      \"comment\": \"The content type (MIME type) of the secret or certificate.\"\n    },\n\n    \"attributes\": {\n      \"@id\": \"kv:attributes\",\n      \"@type\": \"@id\",\n      \"comment\": \"The management attributes of a key, secret, or certificate.\"\n    },\n    \"enabled\": {\n      \"@id\": \"kv:enabled\",\n      \"@type\": \"xsd:boolean\",\n      \"comment\": \"Determines whether the object is enabled.\"\n    },\n    \"nbf\": {\n      \"@id\": \"kv:notBefore\",\n      \"@type\": \"xsd:integer\",\n      \"comment\": \"\
  Not before date in UTC as a Unix timestamp.\"\n    },\n    \"exp\": {\n      \"@id\": \"kv:expires\",\n      \"@type\": \"xsd:integer\",\n      \"comment\": \"Expiry date in UTC as a Unix timestamp.\"\n    },\n    \"created\": {\n      \"@id\": \"kv:created\",\n      \"@type\": \"xsd:integer\",\n      \"comment\": \"Creation time in UTC as a Unix timestamp.\"\n    },\n    \"updated\": {\n      \"@id\": \"kv:updated\",\n      \"@type\": \"xsd:integer\",\n      \"comment\": \"Last updated time in UTC as a Unix timestamp.\"\n    },\n    \"recoveryLevel\": {\n      \"@id\": \"kv:recoveryLevel\",\n      \"comment\": \"Reflects the deletion recovery level currently in effect.\"\n    },\n    \"recoverableDays\": {\n      \"@id\": \"kv:recoverableDays\",\n      \"@type\": \"xsd:integer\",\n      \"comment\": \"Soft-delete data retention days (7-90 when enabled, otherwise 0).\"\n    },\n\n    \"managed\": {\n      \"@id\": \"kv:managed\",\n      \"@type\": \"xsd:boolean\",\n      \"comment\": \"\
  True if the object's lifetime is managed by Key Vault (e.g., backing a certificate).\"\n    },\n    \"tags\": {\n      \"@id\": \"kv:tags\",\n      \"comment\": \"Application-specific metadata in the form of key-value pairs.\"\n    },\n\n    \"key\": {\n      \"@id\": \"kv:key\",\n      \"@type\": \"@id\",\n      \"comment\": \"The JSON Web Key within a KeyBundle.\"\n    },\n    \"kty\": {\n      \"@id\": \"kv:keyType\",\n      \"comment\": \"JSON Web Key type (RSA, EC, oct, RSA-HSM, EC-HSM, oct-HSM).\"\n    },\n    \"key_ops\": {\n      \"@id\": \"kv:keyOperations\",\n      \"comment\": \"Permitted JSON Web Key operations (encrypt, decrypt, sign, verify, wrapKey, unwrapKey).\"\n    },\n    \"key_size\": {\n      \"@id\": \"kv:keySize\",\n      \"@type\": \"xsd:integer\",\n      \"comment\": \"The key size in bits (e.g., 2048, 3072, 4096 for RSA).\"\n    },\n    \"crv\": {\n      \"@id\": \"kv:curveName\",\n      \"comment\": \"Elliptic curve name (P-256, P-384, P-521, P-256K).\"\n   \
  \ },\n    \"n\": {\n      \"@id\": \"jwk:n\",\n      \"comment\": \"RSA modulus (base64url encoded).\"\n    },\n    \"e\": {\n      \"@id\": \"jwk:e\",\n      \"comment\": \"RSA public exponent (base64url encoded).\"\n    },\n    \"d\": {\n      \"@id\": \"jwk:d\",\n      \"comment\": \"RSA private exponent or EC private key D component (base64url encoded).\"\n    },\n    \"x\": {\n      \"@id\": \"jwk:x\",\n      \"comment\": \"X component of an EC public key (base64url encoded).\"\n    },\n    \"y\": {\n      \"@id\": \"jwk:y\",\n      \"comment\": \"Y component of an EC public key (base64url encoded).\"\n    },\n    \"release_policy\": {\n      \"@id\": \"kv:releasePolicy\",\n      \"@type\": \"@id\",\n      \"comment\": \"The policy rules under which the key can be exported.\"\n    },\n    \"exportable\": {\n      \"@id\": \"kv:exportable\",\n      \"@type\": \"xsd:boolean\",\n      \"comment\": \"Indicates if the private key can be exported.\"\n    },\n\n    \"policy\": {\n      \"\
  @id\": \"kv:policy\",\n      \"@type\": \"@id\",\n      \"comment\": \"The management policy for a certificate.\"\n    },\n    \"key_props\": {\n      \"@id\": \"kv:keyProperties\",\n      \"@type\": \"@id\",\n      \"comment\": \"Properties of the key pair backing a certificate.\"\n    },\n    \"secret_props\": {\n      \"@id\": \"kv:secretProperties\",\n      \"@type\": \"@id\",\n      \"comment\": \"Properties of the secret backing a certificate.\"\n    },\n    \"x509_props\": {\n      \"@id\": \"kv:x509Properties\",\n      \"@type\": \"@id\",\n      \"comment\": \"Properties of the X.509 component of a certificate.\"\n    },\n    \"issuer\": {\n      \"@id\": \"kv:issuer\",\n      \"@type\": \"@id\",\n      \"comment\": \"Parameters for the issuer of the X.509 component of a certificate.\"\n    },\n    \"subject\": {\n      \"@id\": \"kv:subject\",\n      \"comment\": \"The X.509 subject distinguished name.\"\n    },\n    \"sans\": {\n      \"@id\": \"kv:subjectAlternativeNames\",\n\
  \      \"@type\": \"@id\",\n      \"comment\": \"The Subject Alternative Names of a X.509 object.\"\n    },\n    \"dns_names\": {\n      \"@id\": \"kv:dnsNames\",\n      \"comment\": \"Domain names in Subject Alternative Names.\"\n    },\n    \"emails\": {\n      \"@id\": \"kv:emails\",\n      \"comment\": \"Email addresses in Subject Alternative Names.\"\n    },\n    \"validity_months\": {\n      \"@id\": \"kv:validityMonths\",\n      \"@type\": \"xsd:integer\",\n      \"comment\": \"The duration that the certificate is valid in months.\"\n    },\n    \"lifetime_actions\": {\n      \"@id\": \"kv:lifetimeActions\",\n      \"comment\": \"Actions performed by Key Vault over the lifetime of a certificate.\"\n    },\n    \"reuse_key\": {\n      \"@id\": \"kv:reuseKey\",\n      \"@type\": \"xsd:boolean\",\n      \"comment\": \"Indicates if the same key pair will be used on certificate renewal.\"\n    },\n\n    \"cer\": {\n      \"@id\": \"kv:certificateData\",\n      \"comment\": \"CER contents\
  \ of the X.509 certificate (base64 encoded).\"\n    },\n    \"x5t\": {\n      \"@id\": \"kv:thumbprint\",\n      \"comment\": \"Thumbprint of the certificate (base64url encoded).\"\n    },\n    \"csr\": {\n      \"@id\": \"kv:certificateSigningRequest\",\n      \"comment\": \"The certificate signing request (CSR) used in the certificate operation.\"\n    },\n    \"status\": {\n      \"@id\": \"kv:status\",\n      \"comment\": \"Status of a certificate operation.\"\n    },\n    \"request_id\": {\n      \"@id\": \"kv:requestId\",\n      \"comment\": \"Identifier for a certificate operation request.\"\n    },\n\n    \"recoveryId\": {\n      \"@id\": \"kv:recoveryId\",\n      \"@type\": \"@id\",\n      \"comment\": \"The URL of the recovery object, used to identify and recover a deleted object.\"\n    },\n    \"scheduledPurgeDate\": {\n      \"@id\": \"kv:scheduledPurgeDate\",\n      \"@type\": \"xsd:integer\",\n      \"comment\": \"The time when the deleted object is scheduled to be purged,\
  \ as a Unix timestamp.\"\n    },\n    \"deletedDate\": {\n      \"@id\": \"kv:deletedDate\",\n      \"@type\": \"xsd:integer\",\n      \"comment\": \"The time when the object was deleted, as a Unix timestamp.\"\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"comment\": \"The name of a key, secret, certificate, or issuer.\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"comment\": \"A human-readable description.\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\",\n      \"comment\": \"A URL associated with the resource.\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-key-vault/refs/heads/main/json-ld/azure-key-vault-context.jsonld
tags:
- Certificates
- Cloud Security
- Cryptography
- Key Management
- Secrets Management
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
