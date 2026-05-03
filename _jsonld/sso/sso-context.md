---
api_specs:
- filename: sso-saml-openapi.yml
  format: yaml
  label: SAML SSO Authentication API
  slug: saml-authentication
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sso/refs/heads/main/openapi/sso-saml-openapi.yml
- filename: sso-oidc-openapi.yml
  format: yaml
  label: OpenID Connect (OIDC) Authentication API
  slug: oidc-authentication
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sso/refs/heads/main/openapi/sso-oidc-openapi.yml
class_count: 32
classes:
- saml
- SSOProvider
- IdentityProvider
- ServiceProvider
- SAMLAssertion
- OIDCToken
- AuthorizationCode
- AccessToken
- IDToken
- RefreshToken
- subject
- nameId
- email
- name
- given_name
- family_name
- expires_in
- scope
- audience
- nonce
- authnContextClassRef
- sessionIndex
- SAML
- OIDC
- OAuth2
- AuthorizationCodeFlow
- ImplicitFlow
- ClientCredentialsFlow
- SingleSignOn
- SingleLogout
- AssertionConsumerService
- JWKS
context_file: json-ld/sso-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sso/refs/heads/main/json-ld/sso-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sso from SSO.
layout: jsonld
name: Sso Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sso
  uri: https://github.com/api-evangelist/sso#
- prefix: oidc
  uri: https://openid.net/connect/
properties:
- container: ''
  name: issuer
  type: reference
- container: ''
  name: picture
  type: reference
- container: ''
  name: notBefore
  type: schema:DateTime
- container: ''
  name: notOnOrAfter
  type: schema:DateTime
- container: ''
  name: authnInstant
  type: schema:DateTime
property_count: 5
provider_name: SSO
provider_slug: sso
slug: sso-context
source_filename: sso-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sso\": \"https://github.com/api-evangelist/sso#\",\n    \"saml\": \"urn:oasis:names:tc:SAML:2.0:\",\n    \"oidc\": \"https://openid.net/connect/\",\n\n    \"SSOProvider\": \"schema:Organization\",\n    \"IdentityProvider\": \"sso:IdentityProvider\",\n    \"ServiceProvider\": \"sso:ServiceProvider\",\n\n    \"SAMLAssertion\": \"sso:SAMLAssertion\",\n    \"OIDCToken\": \"sso:OIDCToken\",\n    \"AuthorizationCode\": \"sso:AuthorizationCode\",\n    \"AccessToken\": \"sso:AccessToken\",\n    \"IDToken\": \"sso:IDToken\",\n    \"RefreshToken\": \"sso:RefreshToken\",\n\n    \"issuer\": {\n      \"@id\": \"schema:creator\",\n      \"@type\": \"@id\"\n    },\n    \"subject\": \"schema:identifier\",\n    \"nameId\": \"schema:identifier\",\n    \"email\": \"schema:email\",\n    \"name\": \"schema:name\",\n    \"given_name\": \"schema:givenName\",\n    \"family_name\": \"schema:familyName\",\n\
  \    \"picture\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n\n    \"notBefore\": {\n      \"@id\": \"schema:validFrom\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"notOnOrAfter\": {\n      \"@id\": \"schema:validThrough\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"expires_in\": \"schema:duration\",\n    \"scope\": \"sso:scope\",\n    \"audience\": \"sso:audience\",\n    \"nonce\": \"sso:nonce\",\n\n    \"authnContextClassRef\": \"sso:authenticationContext\",\n    \"authnInstant\": {\n      \"@id\": \"sso:authenticationTime\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"sessionIndex\": \"sso:sessionIndex\",\n\n    \"SAML\": \"sso:SAMLProtocol\",\n    \"OIDC\": \"sso:OIDCProtocol\",\n    \"OAuth2\": \"sso:OAuth2Protocol\",\n\n    \"AuthorizationCodeFlow\": \"sso:AuthorizationCodeFlow\",\n    \"ImplicitFlow\": \"sso:ImplicitFlow\",\n    \"ClientCredentialsFlow\": \"sso:ClientCredentialsFlow\",\n\n    \"SingleSignOn\": \"sso:SingleSignOn\"\
  ,\n    \"SingleLogout\": \"sso:SingleLogout\",\n    \"AssertionConsumerService\": \"sso:AssertionConsumerService\",\n    \"JWKS\": \"sso:JSONWebKeySet\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sso/refs/heads/main/json-ld/sso-context.jsonld
tags:
- Authentication
- Authorization
- Identity
- OAuth
- OIDC
- SAML
- Security
- Single Sign-On
- SSO
- JSON-LD
- Linked Data
- Semantic Web
---
