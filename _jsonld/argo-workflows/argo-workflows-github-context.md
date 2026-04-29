---
api_specs:
- filename: argo-workflows-openapi.json
  format: json
  label: Argo Workflows API
  slug: argo-workflows
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/openapi/argo-workflows-openapi.json
class_count: 122
classes:
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.S3Filter
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Container
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AWSLambdaTrigger
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.CatchupConfiguration
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AzureEventsHubEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GitArtifact
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SensorList
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.HTTPTrigger
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SensorSpec
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.MNSEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Backoff
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.WatchPathConfig
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AMQPQueueBindConfig
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.URLArtifact
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventPersistence
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TimeFilter
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Trigger
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.StatusPolicy
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.RateLimit
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EmitterEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventDependencyFilter
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.StorageGridEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ValueFromSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.StandardK8STrigger
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SlackEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TriggerPolicy
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.KafkaTrigger
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.NATSTrigger
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.OpenWhiskTrigger
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ArtifactLocation
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.S3Bucket
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SlackThread
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventDependency
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TriggerParameter
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.S3Artifact
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketServerRepository
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GithubEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.RedisStreamEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Metadata
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.FileEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.PulsarTrigger
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventSourceStatus
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AMQPExchangeDeclareConfig
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AMQPQueueDeclareConfig
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.NATSEventsSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BasicAuth
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventContext
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ConditionsResetCriteria
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Sensor
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Selector
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SQSEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GenericEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Amount
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GitCreds
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GitRemoteConfig
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventSourceFilter
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TLSConfig
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ConfigMapPersistence
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.K8SResourcePolicy
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ExprFilter
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.K8SResource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.MQTTEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GithubAppCreds
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AzureEventHubsTrigger
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SchemaRegistryConfig
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.PulsarEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SensorStatus
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.OwnedRepositories
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.RedisEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AzureServiceBusEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Status
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ConditionsResetByTime
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.PayloadField
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.PubSubEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.WebhookEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SFTPEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Int64OrString
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SecureHeader
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventDependencyTransformer
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ResourceEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.NSQEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventSourceSpec
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ArgoWorkflowTrigger
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.WebhookContext
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SlackSender
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventSourceList
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Service
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.CalendarEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.FileArtifact
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AzureServiceBusTrigger
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Template
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SlackTrigger
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AzureQueueStorageEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.CustomTrigger
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketBasicAuth
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GerritEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketRepository
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TriggerParameterSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ResourceFilter
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EmailTrigger
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.KafkaEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AMQPEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.HDFSEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketAuth
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.StorageGridFilter
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AMQPConsumeConfig
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TriggerTemplate
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Condition
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.NATSAuth
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.DataFilter
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.KafkaConsumerGroup
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.StripeEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SNSEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.LogTrigger
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SASLConfig
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketServerEventSource
- github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GitlabEventSource
- url
- version
- name
context_file: json-ld/argo-workflows-github-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/json-ld/argo-workflows-github-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Workflows Github from Argo Workflows.
layout: jsonld
name: Argo Workflows Github Context
namespaces:
- prefix: argo
  uri: https://argoproj.github.io/schema/argo-workflows/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: prefix
  type: string
- container: ''
  name: suffix
  type: string
- container: set
  name: env
  type: string
- container: set
  name: envFrom
  type: string
- container: ''
  name: imagePullPolicy
  type: string
- container: ''
  name: resources
  type: string
- container: ''
  name: securityContext
  type: string
- container: set
  name: volumeMounts
  type: string
- container: ''
  name: accessKey
  type: string
- container: ''
  name: functionName
  type: string
- container: ''
  name: invocationType
  type: string
- container: set
  name: parameters
  type: string
- container: set
  name: payload
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: roleARN
  type: string
- container: ''
  name: secretKey
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: maxDuration
  type: string
- container: ''
  name: filter
  type: string
- container: ''
  name: fqdn
  type: string
- container: ''
  name: hubName
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: sharedAccessKey
  type: string
- container: ''
  name: sharedAccessKeyName
  type: string
- container: ''
  name: branch
  type: string
- container: ''
  name: cloneDirectory
  type: string
- container: ''
  name: creds
  type: string
- container: ''
  name: filePath
  type: string
- container: ''
  name: insecureIgnoreHostKey
  type: boolean
- container: ''
  name: ref
  type: string
- container: ''
  name: remote
  type: string
- container: ''
  name: sshKeySecret
  type: string
- container: ''
  name: tag
  type: string
- container: set
  name: items
  type: string
- container: ''
  name: basicAuth
  type: string
- container: set
  name: dynamicHeaders
  type: string
- container: ''
  name: headers
  type: reference
- container: ''
  name: host
  type: string
- container: ''
  name: method
  type: string
- container: set
  name: secureHeaders
  type: string
- container: ''
  name: timeout
  type: string
- container: ''
  name: tls
  type: string
- container: set
  name: dependencies
  type: string
- container: ''
  name: errorOnFailedRound
  type: boolean
- container: ''
  name: eventBusName
  type: string
- container: ''
  name: loggingFields
  type: reference
- container: ''
  name: replicas
  type: integer
- container: ''
  name: revisionHistoryLimit
  type: integer
- container: ''
  name: template
  type: string
- container: set
  name: triggers
  type: string
- container: ''
  name: endpoint
  type: string
- container: ''
  name: jsonBody
  type: boolean
- container: ''
  name: queue
  type: string
- container: ''
  name: duration
  type: string
- container: ''
  name: factor
  type: string
- container: ''
  name: jitter
  type: string
- container: ''
  name: steps
  type: integer
- container: ''
  name: directory
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: pathRegexp
  type: string
- container: ''
  name: noWait
  type: boolean
- container: ''
  name: verifyCert
  type: boolean
- container: ''
  name: spec
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: catchup
  type: string
- container: ''
  name: configMap
  type: string
- container: ''
  name: start
  type: string
- container: ''
  name: stop
  type: string
- container: ''
  name: timezone
  type: string
- container: ''
  name: atLeastOnce
  type: boolean
- container: ''
  name: dlqTrigger
  type: string
- container: ''
  name: policy
  type: string
- container: ''
  name: rateLimit
  type: string
- container: ''
  name: retryStrategy
  type: string
- container: set
  name: allow
  type: string
- container: ''
  name: requestsPerUnit
  type: integer
- container: ''
  name: unit
  type: string
- container: ''
  name: broker
  type: string
- container: ''
  name: channelKey
  type: string
- container: ''
  name: channelName
  type: string
- container: ''
  name: connectionBackoff
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: context
  type: string
- container: set
  name: data
  type: string
- container: ''
  name: dataLogicalOperator
  type: string
- container: ''
  name: exprLogicalOperator
  type: string
- container: set
  name: exprs
  type: string
- container: ''
  name: script
  type: string
- container: ''
  name: time
  type: string
- container: ''
  name: apiURL
  type: string
- container: ''
  name: authToken
  type: string
- container: ''
  name: bucket
  type: string
- container: set
  name: events
  type: string
- container: ''
  name: topicArn
  type: string
- container: ''
  name: webhook
  type: string
- container: ''
  name: configMapKeyRef
  type: string
- container: ''
  name: secretKeyRef
  type: string
- container: ''
  name: liveObject
  type: boolean
- container: ''
  name: operation
  type: string
- container: ''
  name: patchStrategy
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: signingSecret
  type: string
- container: ''
  name: token
  type: string
- container: ''
  name: k8s
  type: string
- container: ''
  name: compress
  type: boolean
- container: ''
  name: flushFrequency
  type: integer
- container: ''
  name: partition
  type: integer
- container: ''
  name: partitioningKey
  type: string
- container: ''
  name: requiredAcks
  type: integer
- container: ''
  name: sasl
  type: string
- container: ''
  name: schemaRegistry
  type: string
- container: ''
  name: topic
  type: string
- container: ''
  name: auth
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: actionName
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: configmap
  type: string
- container: ''
  name: file
  type: string
- container: ''
  name: git
  type: string
- container: ''
  name: inline
  type: string
- container: ''
  name: resource
  type: string
- container: ''
  name: s3
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: broadcastMessageToChannel
  type: boolean
- container: ''
  name: messageAggregationKey
  type: string
- container: ''
  name: eventName
  type: string
- container: ''
  name: eventSourceName
  type: string
- container: ''
  name: filters
  type: string
- container: ''
  name: filtersLogicalOperator
  type: string
- container: ''
  name: transform
  type: string
- container: ''
  name: dest
  type: string
- container: ''
  name: src
  type: string
- container: ''
  name: caCertificate
  type: string
- container: ''
  name: insecure
  type: boolean
- container: ''
  name: projectKey
  type: string
- container: ''
  name: repositorySlug
  type: string
- container: ''
  name: active
  type: boolean
- container: ''
  name: apiToken
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: deleteHookOnFinish
  type: boolean
- container: ''
  name: githubApp
  type: string
- container: ''
  name: githubBaseURL
  type: string
- container: ''
  name: githubUploadURL
  type: string
- container: ''
  name: id
  type: string
- container: set
  name: organizations
  type: string
- container: ''
  name: owner
  type: string
- container: set
  name: repositories
  type: string
- container: ''
  name: repository
  type: string
- container: ''
  name: webhookSecret
  type: string
- container: ''
  name: consumerGroup
  type: string
- container: ''
  name: db
  type: integer
- container: ''
  name: hostAddress
  type: string
- container: ''
  name: maxMsgCountPerRead
  type: integer
- container: set
  name: streams
  type: string
- container: ''
  name: annotations
  type: reference
- container: ''
  name: labels
  type: reference
- container: ''
  name: eventType
  type: string
- container: ''
  name: polling
  type: boolean
- container: ''
  name: watchPathConfig
  type: string
- container: ''
  name: authAthenzParams
  type: reference
- container: ''
  name: authAthenzSecret
  type: string
- container: ''
  name: authTokenSecret
  type: string
- container: ''
  name: tlsAllowInsecureConnection
  type: boolean
- container: ''
  name: tlsTrustCertsSecret
  type: string
- container: ''
  name: tlsValidateHostname
  type: boolean
- container: ''
  name: autoDelete
  type: boolean
- container: ''
  name: durable
  type: boolean
- container: ''
  name: internal
  type: boolean
- container: ''
  name: arguments
  type: string
- container: ''
  name: exclusive
  type: boolean
- container: ''
  name: datacontenttype
  type: string
- container: ''
  name: specversion
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: byTime
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: dlq
  type: boolean
- container: ''
  name: queueAccountId
  type: string
- container: ''
  name: sessionToken
  type: string
- container: ''
  name: waitTimeSeconds
  type: string
- container: ''
  name: authSecret
  type: string
- container: ''
  name: config
  type: string
- container: set
  name: urls
  type: string
- container: ''
  name: expression
  type: string
- container: ''
  name: caCertSecret
  type: string
- container: ''
  name: clientCertSecret
  type: string
- container: ''
  name: clientKeySecret
  type: string
- container: ''
  name: insecureSkipVerify
  type: boolean
- container: ''
  name: createIfNotExist
  type: boolean
- container: ''
  name: backoff
  type: string
- container: ''
  name: errorOnBackoffTimeout
  type: boolean
- container: ''
  name: expr
  type: string
- container: set
  name: fields
  type: string
- container: ''
  name: clientId
  type: string
- container: ''
  name: appID
  type: string
- container: ''
  name: installationID
  type: string
- container: ''
  name: privateKey
  type: string
- container: ''
  name: schemaId
  type: integer
- container: set
  name: topics
  type: string
- container: set
  name: names
  type: string
- container: set
  name: channels
  type: string
- container: ''
  name: connectionString
  type: string
- container: ''
  name: deferDelete
  type: boolean
- container: ''
  name: fullyQualifiedNamespace
  type: string
- container: ''
  name: queueName
  type: string
- container: ''
  name: subscriptionName
  type: string
- container: ''
  name: topicName
  type: string
- container: set
  name: conditions
  type: string
- container: ''
  name: cron
  type: string
- container: ''
  name: credentialSecret
  type: string
- container: ''
  name: deleteSubscriptionOnFinish
  type: boolean
- container: ''
  name: projectID
  type: string
- container: ''
  name: subscriptionID
  type: string
- container: ''
  name: topicProjectID
  type: string
- container: ''
  name: webhookContext
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: pollIntervalDuration
  type: string
- container: ''
  name: int64Val
  type: string
- container: ''
  name: strVal
  type: string
- container: ''
  name: valueFrom
  type: string
- container: ''
  name: jq
  type: string
- container: set
  name: eventTypes
  type: string
- container: ''
  name: groupVersionResource
  type: string
- container: ''
  name: channel
  type: string
- container: ''
  name: amqp
  type: reference
- container: ''
  name: azureEventsHub
  type: reference
- container: ''
  name: azureQueueStorage
  type: reference
- container: ''
  name: azureServiceBus
  type: reference
- container: ''
  name: bitbucket
  type: reference
- container: ''
  name: bitbucketserver
  type: reference
- container: ''
  name: calendar
  type: reference
- container: ''
  name: emitter
  type: reference
- container: ''
  name: generic
  type: reference
- container: ''
  name: gerrit
  type: reference
- container: ''
  name: github
  type: reference
- container: ''
  name: gitlab
  type: reference
- container: ''
  name: hdfs
  type: reference
- container: ''
  name: kafka
  type: reference
- container: ''
  name: minio
  type: reference
- container: ''
  name: mns
  type: reference
- container: ''
  name: mqtt
  type: reference
- container: ''
  name: nats
  type: reference
- container: ''
  name: nsq
  type: reference
- container: ''
  name: pubSub
  type: reference
- container: ''
  name: pulsar
  type: reference
- container: ''
  name: redis
  type: reference
- container: ''
  name: redisStream
  type: reference
- container: ''
  name: service
  type: string
- container: ''
  name: sftp
  type: reference
- container: ''
  name: slack
  type: reference
- container: ''
  name: sns
  type: reference
- container: ''
  name: sqs
  type: reference
- container: ''
  name: storageGrid
  type: reference
- container: ''
  name: stripe
  type: reference
- container: set
  name: args
  type: string
- container: ''
  name: maxPayloadSize
  type: string
- container: ''
  name: port
  type: string
- container: ''
  name: serverCertSecret
  type: string
- container: ''
  name: serverKeySecret
  type: string
- container: ''
  name: icon
  type: string
- container: ''
  name: clusterIP
  type: string
- container: set
  name: ports
  type: string
- container: set
  name: exclusionDates
  type: string
- container: ''
  name: interval
  type: string
- container: ''
  name: persistence
  type: string
- container: ''
  name: schedule
  type: string
- container: ''
  name: affinity
  type: string
- container: ''
  name: container
  type: string
- container: set
  name: imagePullSecrets
  type: string
- container: ''
  name: nodeSelector
  type: reference
- container: ''
  name: priority
  type: integer
- container: ''
  name: priorityClassName
  type: string
- container: ''
  name: serviceAccountName
  type: string
- container: set
  name: tolerations
  type: string
- container: set
  name: volumes
  type: string
- container: ''
  name: attachments
  type: string
- container: ''
  name: blocks
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: sender
  type: string
- container: ''
  name: slackToken
  type: string
- container: ''
  name: thread
  type: string
- container: ''
  name: decodeMessage
  type: boolean
- container: ''
  name: storageAccountName
  type: string
- container: ''
  name: waitTimeInSeconds
  type: integer
- container: ''
  name: certSecret
  type: string
- container: ''
  name: secure
  type: boolean
- container: ''
  name: serverNameOverride
  type: string
- container: ''
  name: serverURL
  type: string
- container: ''
  name: gerritBaseURL
  type: string
- container: ''
  name: hookName
  type: string
- container: ''
  name: maxTries
  type: string
- container: set
  name: projects
  type: string
- container: ''
  name: sslVerify
  type: boolean
- container: ''
  name: contextKey
  type: string
- container: ''
  name: contextTemplate
  type: string
- container: ''
  name: dataKey
  type: string
- container: ''
  name: dataTemplate
  type: string
- container: ''
  name: dependencyName
  type: string
- container: ''
  name: useRawData
  type: boolean
- container: ''
  name: afterStart
  type: boolean
- container: ''
  name: createdBy
  type: string
- container: ''
  name: body
  type: string
- container: ''
  name: from
  type: string
- container: ''
  name: smtpPassword
  type: string
- container: set
  name: to
  type: string
- container: ''
  name: limitEventsPerSecond
  type: string
- container: ''
  name: consume
  type: string
- container: ''
  name: exchangeDeclare
  type: string
- container: ''
  name: exchangeName
  type: string
- container: ''
  name: exchangeType
  type: string
- container: ''
  name: queueBind
  type: string
- container: ''
  name: queueDeclare
  type: string
- container: ''
  name: routingKey
  type: string
- container: ''
  name: urlSecret
  type: string
- container: set
  name: addresses
  type: string
- container: ''
  name: checkInterval
  type: string
- container: ''
  name: hdfsUser
  type: string
- container: ''
  name: krbCCacheSecret
  type: string
- container: ''
  name: krbConfigConfigMap
  type: string
- container: ''
  name: krbKeytabSecret
  type: string
- container: ''
  name: krbRealm
  type: string
- container: ''
  name: krbServicePrincipalName
  type: string
- container: ''
  name: krbUsername
  type: string
- container: ''
  name: basic
  type: string
- container: ''
  name: oauthToken
  type: string
- container: ''
  name: autoAck
  type: boolean
- container: ''
  name: consumerTag
  type: string
- container: ''
  name: noLocal
  type: boolean
- container: ''
  name: argoWorkflow
  type: string
- container: ''
  name: awsLambda
  type: string
- container: ''
  name: azureEventHubs
  type: string
- container: set
  name: conditionsReset
  type: string
- container: ''
  name: custom
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: http
  type: string
- container: ''
  name: log
  type: string
- container: ''
  name: openWhisk
  type: string
- container: ''
  name: lastTransitionTime
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: credential
  type: string
- container: ''
  name: nkey
  type: string
- container: ''
  name: comparator
  type: string
- container: ''
  name: groupName
  type: string
- container: ''
  name: oldest
  type: boolean
- container: ''
  name: rebalanceStrategy
  type: string
- container: ''
  name: apiKey
  type: string
- container: ''
  name: createWebhook
  type: boolean
- container: set
  name: eventFilter
  type: string
- container: ''
  name: validateSignature
  type: boolean
- container: ''
  name: intervalSeconds
  type: string
- container: ''
  name: mechanism
  type: string
- container: ''
  name: passwordSecret
  type: string
- container: ''
  name: userSecret
  type: string
- container: ''
  name: accessToken
  type: string
- container: ''
  name: bitbucketserverBaseURL
  type: string
- container: ''
  name: oneEventPerChange
  type: boolean
- container: ''
  name: skipBranchRefsChangedOnOpenPR
  type: boolean
- container: ''
  name: enableSSLVerification
  type: boolean
- container: ''
  name: gitlabBaseURL
  type: string
- container: set
  name: groups
  type: string
- container: ''
  name: secretToken
  type: string
property_count: 361
provider_name: Argo Workflows
provider_slug: argo-workflows
slug: argo-workflows-github-context
source_filename: argo-workflows-github-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argo\": \"https://argoproj.github.io/schema/argo-workflows/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.S3Filter\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.S3Filter\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Container\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Container\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AWSLambdaTrigger\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AWSLambdaTrigger\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.CatchupConfiguration\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.CatchupConfiguration\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AzureEventsHubEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AzureEventsHubEventSource\"\
  ,\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GitArtifact\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GitArtifact\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SensorList\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SensorList\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.HTTPTrigger\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.HTTPTrigger\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SensorSpec\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SensorSpec\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.MNSEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.MNSEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Backoff\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Backoff\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.WatchPathConfig\"\
  : \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.WatchPathConfig\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AMQPQueueBindConfig\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AMQPQueueBindConfig\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.URLArtifact\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.URLArtifact\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventPersistence\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventPersistence\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TimeFilter\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TimeFilter\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Trigger\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Trigger\"\
  ,\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.StatusPolicy\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.StatusPolicy\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.RateLimit\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.RateLimit\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EmitterEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EmitterEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventDependencyFilter\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventDependencyFilter\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.StorageGridEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.StorageGridEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ValueFromSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ValueFromSource\"\
  ,\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.StandardK8STrigger\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.StandardK8STrigger\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SlackEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SlackEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TriggerPolicy\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TriggerPolicy\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.KafkaTrigger\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.KafkaTrigger\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.NATSTrigger\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.NATSTrigger\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.OpenWhiskTrigger\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.OpenWhiskTrigger\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ArtifactLocation\"\
  : \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ArtifactLocation\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.S3Bucket\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.S3Bucket\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SlackThread\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SlackThread\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventDependency\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventDependency\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TriggerParameter\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TriggerParameter\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.S3Artifact\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.S3Artifact\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketServerRepository\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketServerRepository\"\
  ,\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GithubEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GithubEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.RedisStreamEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.RedisStreamEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Metadata\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Metadata\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.FileEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.FileEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.PulsarTrigger\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.PulsarTrigger\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventSourceStatus\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventSourceStatus\"\
  ,\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AMQPExchangeDeclareConfig\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AMQPExchangeDeclareConfig\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AMQPQueueDeclareConfig\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AMQPQueueDeclareConfig\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.NATSEventsSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.NATSEventsSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BasicAuth\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BasicAuth\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventContext\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventContext\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ConditionsResetCriteria\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ConditionsResetCriteria\"\
  ,\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Sensor\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Sensor\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Selector\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Selector\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SQSEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SQSEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GenericEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GenericEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Amount\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Amount\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GitCreds\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GitCreds\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GitRemoteConfig\"\
  : \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GitRemoteConfig\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventSourceFilter\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventSourceFilter\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TLSConfig\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TLSConfig\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ConfigMapPersistence\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ConfigMapPersistence\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.K8SResourcePolicy\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.K8SResourcePolicy\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ExprFilter\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ExprFilter\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.K8SResource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.K8SResource\"\
  ,\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.MQTTEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.MQTTEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GithubAppCreds\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GithubAppCreds\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AzureEventHubsTrigger\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AzureEventHubsTrigger\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SchemaRegistryConfig\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SchemaRegistryConfig\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.PulsarEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.PulsarEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SensorStatus\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SensorStatus\"\
  ,\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.OwnedRepositories\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.OwnedRepositories\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.RedisEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.RedisEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AzureServiceBusEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AzureServiceBusEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Status\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Status\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ConditionsResetByTime\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ConditionsResetByTime\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.PayloadField\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.PayloadField\"\
  ,\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.PubSubEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.PubSubEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.WebhookEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.WebhookEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SFTPEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SFTPEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Int64OrString\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Int64OrString\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SecureHeader\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SecureHeader\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventDependencyTransformer\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventDependencyTransformer\"\
  ,\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ResourceEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ResourceEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.NSQEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.NSQEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventSourceSpec\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventSourceSpec\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ArgoWorkflowTrigger\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ArgoWorkflowTrigger\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.WebhookContext\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.WebhookContext\"\
  ,\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SlackSender\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SlackSender\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventSourceList\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EventSourceList\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Service\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Service\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.CalendarEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.CalendarEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.FileArtifact\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.FileArtifact\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AzureServiceBusTrigger\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AzureServiceBusTrigger\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Template\"\
  : \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Template\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SlackTrigger\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SlackTrigger\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AzureQueueStorageEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AzureQueueStorageEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.CustomTrigger\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.CustomTrigger\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketBasicAuth\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketBasicAuth\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GerritEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GerritEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketRepository\"\
  : \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketRepository\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TriggerParameterSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TriggerParameterSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ResourceFilter\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.ResourceFilter\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EmailTrigger\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.EmailTrigger\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.KafkaEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.KafkaEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AMQPEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AMQPEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.HDFSEventSource\"\
  : \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.HDFSEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketAuth\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketAuth\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.StorageGridFilter\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.StorageGridFilter\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AMQPConsumeConfig\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.AMQPConsumeConfig\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TriggerTemplate\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.TriggerTemplate\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Condition\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.Condition\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.NATSAuth\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.NATSAuth\"\
  ,\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.DataFilter\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.DataFilter\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.KafkaConsumerGroup\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.KafkaConsumerGroup\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.StripeEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.StripeEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SNSEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SNSEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.LogTrigger\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.LogTrigger\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SASLConfig\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.SASLConfig\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketServerEventSource\"\
  : \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.BitbucketServerEventSource\",\n    \"github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GitlabEventSource\": \"argo:github.com.argoproj.argo_events.pkg.apis.events.v1alpha1.GitlabEventSource\",\n    \"prefix\": {\n      \"@id\": \"argo:prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suffix\": {\n      \"@id\": \"argo:suffix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"env\": {\n      \"@id\": \"argo:env\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"envFrom\": {\n      \"@id\": \"argo:envFrom\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imagePullPolicy\": {\n      \"@id\": \"argo:imagePullPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resources\": {\n      \"@id\": \"argo:resources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityContext\": {\n      \"@id\": \"argo:securityContext\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"volumeMounts\": {\n      \"@id\": \"argo:volumeMounts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessKey\": {\n      \"@id\": \"argo:accessKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"functionName\": {\n      \"@id\": \"argo:functionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invocationType\": {\n      \"@id\": \"argo:invocationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"argo:parameters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payload\": {\n      \"@id\": \"argo:payload\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"argo:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleARN\": {\n      \"@id\": \"argo:roleARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretKey\": {\n      \"@id\": \"argo:secretKey\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"argo:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"maxDuration\": {\n      \"@id\": \"argo:maxDuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filter\": {\n      \"@id\": \"argo:filter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fqdn\": {\n      \"@id\": \"argo:fqdn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hubName\": {\n      \"@id\": \"argo:hubName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"argo:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"sharedAccessKey\": {\n      \"@id\": \"argo:sharedAccessKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sharedAccessKeyName\": {\n      \"@id\": \"argo:sharedAccessKeyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"branch\": {\n      \"@id\": \"argo:branch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloneDirectory\": {\n      \"@id\": \"argo:cloneDirectory\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"creds\": {\n      \"@id\": \"argo:creds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filePath\": {\n      \"@id\": \"argo:filePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"insecureIgnoreHostKey\": {\n      \"@id\": \"argo:insecureIgnoreHostKey\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ref\": {\n      \"@id\": \"argo:ref\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remote\": {\n      \"@id\": \"argo:remote\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sshKeySecret\": {\n      \"@id\": \"argo:sshKeySecret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tag\": {\n      \"@id\": \"argo:tag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"items\": {\n      \"@id\": \"argo:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"basicAuth\": {\n      \"@id\": \"argo:basicAuth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dynamicHeaders\": {\n      \"@id\": \"argo:dynamicHeaders\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headers\": {\n      \"@id\": \"argo:headers\",\n      \"@type\": \"@id\"\n    },\n    \"host\": {\n      \"@id\": \"argo:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"method\": {\n      \"@id\": \"argo:method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secureHeaders\": {\n      \"@id\": \"argo:secureHeaders\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeout\": {\n      \"@id\": \"argo:timeout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tls\": {\n      \"@id\": \"argo:tls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dependencies\": {\n      \"@id\": \"argo:dependencies\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorOnFailedRound\": {\n      \"@id\": \"argo:errorOnFailedRound\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"eventBusName\": {\n      \"@id\": \"argo:eventBusName\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"loggingFields\": {\n      \"@id\": \"argo:loggingFields\",\n      \"@type\": \"@id\"\n    },\n    \"replicas\": {\n      \"@id\": \"argo:replicas\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"revisionHistoryLimit\": {\n      \"@id\": \"argo:revisionHistoryLimit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"template\": {\n      \"@id\": \"argo:template\",\n      \"@type\": \"xsd:string\"\n    },\n    \"triggers\": {\n      \"@id\": \"argo:triggers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpoint\": {\n      \"@id\": \"argo:endpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jsonBody\": {\n      \"@id\": \"argo:jsonBody\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"queue\": {\n      \"@id\": \"argo:queue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"argo:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"factor\": {\n      \"@id\": \"argo:factor\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"jitter\": {\n      \"@id\": \"argo:jitter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"steps\": {\n      \"@id\": \"argo:steps\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"directory\": {\n      \"@id\": \"argo:directory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"argo:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pathRegexp\": {\n      \"@id\": \"argo:pathRegexp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"noWait\": {\n      \"@id\": \"argo:noWait\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"verifyCert\": {\n      \"@id\": \"argo:verifyCert\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"spec\": {\n      \"@id\": \"argo:spec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"argo:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"catchup\": {\n      \"@id\": \"argo:catchup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configMap\"\
  : {\n      \"@id\": \"argo:configMap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start\": {\n      \"@id\": \"argo:start\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stop\": {\n      \"@id\": \"argo:stop\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timezone\": {\n      \"@id\": \"argo:timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"atLeastOnce\": {\n      \"@id\": \"argo:atLeastOnce\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"dlqTrigger\": {\n      \"@id\": \"argo:dlqTrigger\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policy\": {\n      \"@id\": \"argo:policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rateLimit\": {\n      \"@id\": \"argo:rateLimit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retryStrategy\": {\n      \"@id\": \"argo:retryStrategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allow\": {\n      \"@id\": \"argo:allow\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestsPerUnit\"\
  : {\n      \"@id\": \"argo:requestsPerUnit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"unit\": {\n      \"@id\": \"argo:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"broker\": {\n      \"@id\": \"argo:broker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channelKey\": {\n      \"@id\": \"argo:channelKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channelName\": {\n      \"@id\": \"argo:channelName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionBackoff\": {\n      \"@id\": \"argo:connectionBackoff\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"argo:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": {\n      \"@id\": \"argo:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"context\": {\n      \"@id\": \"argo:context\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"argo:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"dataLogicalOperator\": {\n      \"@id\": \"argo:dataLogicalOperator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exprLogicalOperator\": {\n      \"@id\": \"argo:exprLogicalOperator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exprs\": {\n      \"@id\": \"argo:exprs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"script\": {\n      \"@id\": \"argo:script\",\n      \"@type\": \"xsd:string\"\n    },\n    \"time\": {\n      \"@id\": \"argo:time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apiURL\": {\n      \"@id\": \"argo:apiURL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authToken\": {\n      \"@id\": \"argo:authToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucket\": {\n      \"@id\": \"argo:bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"events\": {\n      \"@id\": \"argo:events\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topicArn\": {\n      \"@id\": \"argo:topicArn\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"webhook\": {\n      \"@id\": \"argo:webhook\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configMapKeyRef\": {\n      \"@id\": \"argo:configMapKeyRef\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretKeyRef\": {\n      \"@id\": \"argo:secretKeyRef\",\n      \"@type\": \"xsd:string\"\n    },\n    \"liveObject\": {\n      \"@id\": \"argo:liveObject\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"operation\": {\n      \"@id\": \"argo:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"patchStrategy\": {\n      \"@id\": \"argo:patchStrategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"argo:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signingSecret\": {\n      \"@id\": \"argo:signingSecret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token\": {\n      \"@id\": \"argo:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"k8s\": {\n      \"@id\": \"argo:k8s\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"compress\": {\n      \"@id\": \"argo:compress\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"flushFrequency\": {\n      \"@id\": \"argo:flushFrequency\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"partition\": {\n      \"@id\": \"argo:partition\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"partitioningKey\": {\n      \"@id\": \"argo:partitioningKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requiredAcks\": {\n      \"@id\": \"argo:requiredAcks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sasl\": {\n      \"@id\": \"argo:sasl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schemaRegistry\": {\n      \"@id\": \"argo:schemaRegistry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topic\": {\n      \"@id\": \"argo:topic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"auth\": {\n      \"@id\": \"argo:auth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\":\
  \ {\n      \"@id\": \"argo:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionName\": {\n      \"@id\": \"argo:actionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"argo:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configmap\": {\n      \"@id\": \"argo:configmap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"file\": {\n      \"@id\": \"argo:file\",\n      \"@type\": \"xsd:string\"\n    },\n    \"git\": {\n      \"@id\": \"argo:git\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inline\": {\n      \"@id\": \"argo:inline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resource\": {\n      \"@id\": \"argo:resource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3\": {\n      \"@id\": \"argo:s3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"argo:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"broadcastMessageToChannel\": {\n      \"@id\"\
  : \"argo:broadcastMessageToChannel\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"messageAggregationKey\": {\n      \"@id\": \"argo:messageAggregationKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventName\": {\n      \"@id\": \"argo:eventName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventSourceName\": {\n      \"@id\": \"argo:eventSourceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filters\": {\n      \"@id\": \"argo:filters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filtersLogicalOperator\": {\n      \"@id\": \"argo:filtersLogicalOperator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transform\": {\n      \"@id\": \"argo:transform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dest\": {\n      \"@id\": \"argo:dest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"src\": {\n      \"@id\": \"argo:src\",\n      \"@type\": \"xsd:string\"\n    },\n    \"caCertificate\": {\n      \"@id\": \"argo:caCertificate\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"insecure\": {\n      \"@id\": \"argo:insecure\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"projectKey\": {\n      \"@id\": \"argo:projectKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositorySlug\": {\n      \"@id\": \"argo:repositorySlug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active\": {\n      \"@id\": \"argo:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"apiToken\": {\n      \"@id\": \"argo:apiToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"argo:contentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deleteHookOnFinish\": {\n      \"@id\": \"argo:deleteHookOnFinish\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"githubApp\": {\n      \"@id\": \"argo:githubApp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"githubBaseURL\": {\n      \"@id\": \"argo:githubBaseURL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"githubUploadURL\": {\n      \"@id\": \"argo:githubUploadURL\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"argo:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizations\": {\n      \"@id\": \"argo:organizations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"argo:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositories\": {\n      \"@id\": \"argo:repositories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repository\": {\n      \"@id\": \"argo:repository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webhookSecret\": {\n      \"@id\": \"argo:webhookSecret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consumerGroup\": {\n      \"@id\": \"argo:consumerGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"db\": {\n      \"@id\": \"argo:db\",\n      \"@type\": \"xsd\n\n# --- truncated at 32 KB (50 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/json-ld/argo-workflows-github-context.jsonld\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/json-ld/argo-workflows-github-context.jsonld
tags:
- CNCF
- Containers
- Data Processing
- Kubernetes
- Machine Learning
- Open Source
- Workflow Engine
- JSON-LD
- Linked Data
- Semantic Web
---
