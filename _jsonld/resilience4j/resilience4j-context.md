---
class_count: 26
classes:
- CircuitBreaker
- RateLimiter
- Bulkhead
- Retry
- TimeLimiter
- Cache
- slidingWindowType
- slidingWindowSize
- failureRateThreshold
- slowCallRateThreshold
- waitDurationInOpenState
- maxAttempts
- waitDuration
- timeoutDuration
- maxConcurrentCalls
- limitForPeriod
- limitRefreshPeriod
- CircuitBreakerState
- CLOSED
- OPEN
- HALF_OPEN
- DISABLED
- FORCED_OPEN
- FaultTolerance
- Decorator
- Event
context_file: json-ld/resilience4j-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/resilience4j/refs/heads/main/json-ld/resilience4j-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Resilience4J from Resilience4j.
layout: jsonld
name: Resilience4J Context
namespaces:
- prefix: r4j
  uri: https://resilience4j.readme.io/vocab/
- prefix: SoftwareApplication
  uri: https://schema.org/SoftwareApplication
- prefix: SoftwareLibrary
  uri: https://schema.org/SoftwareSourceCode
- prefix: name
  uri: https://schema.org/name
- prefix: description
  uri: https://schema.org/description
- prefix: url
  uri: https://schema.org/url
- prefix: version
  uri: https://schema.org/softwareVersion
- prefix: programmingLanguage
  uri: https://schema.org/programmingLanguage
- prefix: license
  uri: https://schema.org/license
properties: []
property_count: 0
provider_name: Resilience4j
provider_slug: resilience4j
slug: resilience4j-context
source_filename: resilience4j-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"r4j\": \"https://resilience4j.readme.io/vocab/\",\n    \"SoftwareApplication\": \"https://schema.org/SoftwareApplication\",\n    \"SoftwareLibrary\": \"https://schema.org/SoftwareSourceCode\",\n    \"name\": \"https://schema.org/name\",\n    \"description\": \"https://schema.org/description\",\n    \"url\": \"https://schema.org/url\",\n    \"version\": \"https://schema.org/softwareVersion\",\n    \"programmingLanguage\": \"https://schema.org/programmingLanguage\",\n    \"license\": \"https://schema.org/license\",\n    \"CircuitBreaker\": \"r4j:CircuitBreaker\",\n    \"RateLimiter\": \"r4j:RateLimiter\",\n    \"Bulkhead\": \"r4j:Bulkhead\",\n    \"Retry\": \"r4j:Retry\",\n    \"TimeLimiter\": \"r4j:TimeLimiter\",\n    \"Cache\": \"r4j:Cache\",\n    \"slidingWindowType\": \"r4j:slidingWindowType\",\n    \"slidingWindowSize\": \"r4j:slidingWindowSize\",\n    \"failureRateThreshold\": \"r4j:failureRateThreshold\"\
  ,\n    \"slowCallRateThreshold\": \"r4j:slowCallRateThreshold\",\n    \"waitDurationInOpenState\": \"r4j:waitDurationInOpenState\",\n    \"maxAttempts\": \"r4j:maxAttempts\",\n    \"waitDuration\": \"r4j:waitDuration\",\n    \"timeoutDuration\": \"r4j:timeoutDuration\",\n    \"maxConcurrentCalls\": \"r4j:maxConcurrentCalls\",\n    \"limitForPeriod\": \"r4j:limitForPeriod\",\n    \"limitRefreshPeriod\": \"r4j:limitRefreshPeriod\",\n    \"CircuitBreakerState\": \"r4j:CircuitBreakerState\",\n    \"CLOSED\": \"r4j:CLOSED\",\n    \"OPEN\": \"r4j:OPEN\",\n    \"HALF_OPEN\": \"r4j:HALF_OPEN\",\n    \"DISABLED\": \"r4j:DISABLED\",\n    \"FORCED_OPEN\": \"r4j:FORCED_OPEN\",\n    \"FaultTolerance\": \"r4j:FaultTolerance\",\n    \"Decorator\": \"r4j:Decorator\",\n    \"Event\": \"r4j:Event\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/resilience4j/refs/heads/main/json-ld/resilience4j-context.jsonld
tags:
- Bulkhead
- Circuit Breaker
- Fault Tolerance
- Java
- Microservices
- Rate Limiter
- Resilience
- Retry
- Spring Boot
- Functional Programming
- JSON-LD
- Linked Data
- Semantic Web
---
