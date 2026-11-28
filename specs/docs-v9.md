---
type: api
title: "Elasticsearch API (v9)"
description: "Elasticsearch provides REST APIs that are used by the UI components and can be called directly to configure and access Elasticsearch features."
url: https://www.elastic.co/docs/api/elasticsearch
resource: https://www.elastic.co/docs/api/elasticsearch
products:
  - Elasticsearch
license: "Apache 2.0"
spec:
  json: https://www.elastic.co/docs/api/elasticsearch/v9.json
  yaml: https://www.elastic.co/docs/api/elasticsearch/v9.yaml
---

# Elasticsearch API (v9)

Elasticsearch provides REST APIs that are used by the UI components and can be called directly to configure and access Elasticsearch features.
## Documentation source and versions
This documentation is derived from the `9.6` branch of the [elasticsearch-specification](https://github.com/elastic/elasticsearch-specification) repository. It is provided under license [Attribution-NonCommercial-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nc-nd/4.0/).
This documentation contains work-in-progress information for future Elastic Stack releases.

- [Authentication](https://www.elastic.co/docs/api/elasticsearch/v9/authentication)
### [Behavioral analytics](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-analytics)

- [Create a behavioral analytics collection event](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-search-application-post-behavioral-analytics-event): `POST` `/_application/analytics/{collection_name}/event/{event_type}`
- [Get behavioral analytics collections](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-search-application-get-behavioral-analytics): `GET` `/_application/analytics/{name}`, `GET` `/_application/analytics`
- [Create a behavioral analytics collection](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-search-application-put-behavioral-analytics): `PUT` `/_application/analytics/{name}`
- [Delete a behavioral analytics collection](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-search-application-delete-behavioral-analytics): `DELETE` `/_application/analytics/{name}`
### [Cluster](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-cluster)

- [Ping the cluster](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ping): `HEAD` `/`
- [Explain the shard allocations](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cluster-allocation-explain): `POST` (also `GET`) `/_cluster/allocation/explain`
- [Get the cluster health status](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cluster-health): `GET` `/_cluster/health/{index}`, `GET` `/_cluster/health`
- [Get the pending cluster tasks](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cluster-pending-tasks): `GET` `/_cluster/pending_tasks`
- [Reroute the cluster](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cluster-reroute): `POST` `/_cluster/reroute`
- [Get cluster-wide settings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cluster-get-settings): `GET` `/_cluster/settings`
- [Update the cluster settings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cluster-put-settings): `PUT` `/_cluster/settings`
- [Get the cluster state](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cluster-state): `GET` `/_cluster/state/{metric}/{index}`, `GET` `/_cluster/state/{metric}`, `GET` `/_cluster/state`
- [Get cluster statistics](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cluster-stats): `GET` `/_cluster/stats/nodes/{node_id}`, `GET` `/_cluster/stats`
- [Update voting configuration exclusions](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cluster-post-voting-config-exclusions): `POST` `/_cluster/voting_config_exclusions`
- [Clear cluster voting config exclusions](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cluster-delete-voting-config-exclusions): `DELETE` `/_cluster/voting_config_exclusions`
- [Get cluster subsystem info](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cluster-info): `GET` `/_info/{target}`
- [Get cluster repositories metering](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-nodes-get-repositories-metering-info): `GET` `/_nodes/{node_id}/_repositories_metering`
- [Clear the archived repositories metering](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-nodes-clear-repositories-metering-archive): `DELETE` `/_nodes/{node_id}/_repositories_metering/{max_archive_version}`
- [Get the hot threads for nodes](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-nodes-hot-threads): `GET` `/_nodes/{node_id}/hot_threads`, `GET` `/_nodes/hot_threads`
- [Reload the keystore on nodes in the cluster](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-nodes-reload-secure-settings): `POST` `/_nodes/{node_id}/reload_secure_settings`, `POST` `/_nodes/reload_secure_settings`
- [Get node statistics](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-nodes-stats): `GET` `/_nodes/{node_id}/stats/{metric}/{index_metric}`, `GET` `/_nodes/stats/{metric}/{index_metric}`, `GET` `/_nodes/{node_id}/stats/{metric}`, `GET` `/_nodes/{node_id}/stats`, `GET` `/_nodes/stats/{metric}`, `GET` `/_nodes/stats`
- [Get feature usage information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-nodes-usage): `GET` `/_nodes/{node_id}/usage/{metric}`, `GET` `/_nodes/{node_id}/usage`, `GET` `/_nodes/usage/{metric}`, `GET` `/_nodes/usage`
- [Get node information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-nodes-info): `GET` `/_nodes/{node_id}/{metric}`, `GET` `/_nodes/{node_id}`, `GET` `/_nodes/{metric}`, `GET` `/_nodes`
- [Get remote cluster information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cluster-remote-info): `GET` `/_remote/info`
### [Cluster - Health](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-health_report)

- [Get the cluster health](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-health-report): `GET` `/_health_report/{feature}`, `GET` `/_health_report`
### [Compact and aligned text (CAT)](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-cat)

- [Get CAT help](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-help): `GET` `/_cat`
- [Get a compact list of aliases](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-aliases): `GET` `/_cat/aliases/{name}`, `GET` `/_cat/aliases`
- [Get shard allocation information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-allocation): `GET` `/_cat/allocation/{node_id}`, `GET` `/_cat/allocation`
- [Get circuit breakers statistics](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-circuit-breaker): `GET` `/_cat/circuit_breaker/{circuit_breaker_patterns}`, `GET` `/_cat/circuit_breaker`
- [Get a compact list of component templates](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-component-templates): `GET` `/_cat/component_templates/{name}`, `GET` `/_cat/component_templates`
- [Get a document count](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-count): `POST` (also `GET`) `/_cat/count/{index}`, `POST` (also `GET`) `/_cat/count`
- [Get field data cache information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-fielddata): `GET` `/_cat/fielddata/{fields}`, `GET` `/_cat/fielddata`
- [Get a compact cluster health summary](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-health): `GET` `/_cat/health`
- [Get a compact list of indices](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-indices): `GET` `/_cat/indices/{index}`, `GET` `/_cat/indices`
- [Get master node information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-master): `GET` `/_cat/master`
- [Get anomaly detection jobs](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-ml-jobs): `GET` `/_cat/ml/anomaly_detectors/{job_id}`, `GET` `/_cat/ml/anomaly_detectors`
- [Get data frame analytics jobs](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-ml-data-frame-analytics): `GET` `/_cat/ml/data_frame/analytics/{id}`, `GET` `/_cat/ml/data_frame/analytics`
- [Get datafeeds](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-ml-datafeeds): `GET` `/_cat/ml/datafeeds/{datafeed_id}`, `GET` `/_cat/ml/datafeeds`
- [Get trained models](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-ml-trained-models): `GET` `/_cat/ml/trained_models/{model_id}`, `GET` `/_cat/ml/trained_models`
- [Get node attribute information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-nodeattrs): `GET` `/_cat/nodeattrs`
- [Get a compact list of nodes](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-nodes): `GET` `/_cat/nodes`
- [Get pending task information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-pending-tasks): `GET` `/_cat/pending_tasks`
- [Get plugin information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-plugins): `GET` `/_cat/plugins`
- [Get shard recovery information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-recovery): `GET` `/_cat/recovery/{index}`, `GET` `/_cat/recovery`
- [Get a compact list of snapshot repositories](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-repositories): `GET` `/_cat/repositories`
- [Get segment information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-segments): `GET` `/_cat/segments/{index}`, `GET` `/_cat/segments`
- [Get shard information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-shards): `GET` `/_cat/shards/{index}`, `GET` `/_cat/shards`
- [Get a compact list of snapshots](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-snapshots): `GET` `/_cat/snapshots/{repository}`, `GET` `/_cat/snapshots`
- [Get a compact list of running tasks](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-tasks): `GET` `/_cat/tasks`
- [Get index template information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-templates): `GET` `/_cat/templates/{name}`, `GET` `/_cat/templates`
- [Get thread pool statistics](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-thread-pool): `GET` `/_cat/thread_pool/{thread_pool_patterns}`, `GET` `/_cat/thread_pool`
- [Get transform information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cat-transforms): `GET` `/_cat/transforms/{transform_id}`, `GET` `/_cat/transforms`
### [Connector](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-connector)

- [Get all connectors](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-list): `GET` `/_connector`
- [Create a connector](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-post): `POST` `/_connector`
- [Get all connector sync jobs](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-sync-job-list): `GET` `/_connector/_sync_job`
- [Create a connector sync job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-sync-job-post): `POST` `/_connector/_sync_job`
- [Get a connector sync job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-sync-job-get): `GET` `/_connector/_sync_job/{connector_sync_job_id}`
- [Delete a connector sync job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-sync-job-delete): `DELETE` `/_connector/_sync_job/{connector_sync_job_id}`
- [Cancel a connector sync job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-sync-job-cancel): `PUT` `/_connector/_sync_job/{connector_sync_job_id}/_cancel`
- [Check in a connector sync job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-sync-job-check-in): `PUT` `/_connector/_sync_job/{connector_sync_job_id}/_check_in`
- [Claim a connector sync job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-sync-job-claim): `PUT` `/_connector/_sync_job/{connector_sync_job_id}/_claim`
- [Set a connector sync job error](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-sync-job-error): `PUT` `/_connector/_sync_job/{connector_sync_job_id}/_error`
- [Set the connector sync job stats](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-sync-job-update-stats): `PUT` `/_connector/_sync_job/{connector_sync_job_id}/_stats`
- [Get a connector](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-get): `GET` `/_connector/{connector_id}`
- [Create or update a connector](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-put): `PUT` `/_connector/{connector_id}`, `PUT` `/_connector`
- [Delete a connector](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-delete): `DELETE` `/_connector/{connector_id}`
- [Update the connector API key ID](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-update-api-key-id): `PUT` `/_connector/{connector_id}/_api_key_id`
- [Check in a connector](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-check-in): `PUT` `/_connector/{connector_id}/_check_in`
- [Update the connector configuration](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-update-configuration): `PUT` `/_connector/{connector_id}/_configuration`
- [Update the connector error field](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-update-error): `PUT` `/_connector/{connector_id}/_error`
- [Update the connector features](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-update-features): `PUT` `/_connector/{connector_id}/_features`
- [Update the connector filtering](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-update-filtering): `PUT` `/_connector/{connector_id}/_filtering`
- [Activate the connector draft filter](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-update-active-filtering): `PUT` `/_connector/{connector_id}/_filtering/_activate`
- [Update the connector draft filtering validation](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-update-filtering-validation): `PUT` `/_connector/{connector_id}/_filtering/_validation`
- [Update the connector index name](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-update-index-name): `PUT` `/_connector/{connector_id}/_index_name`
- [Update the connector name and description](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-update-name): `PUT` `/_connector/{connector_id}/_name`
- [Update the connector is_native flag](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-update-native): `PUT` `/_connector/{connector_id}/_native`
- [Update the connector pipeline](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-update-pipeline): `PUT` `/_connector/{connector_id}/_pipeline`
- [Update the connector scheduling](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-update-scheduling): `PUT` `/_connector/{connector_id}/_scheduling`
- [Update the connector service type](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-update-service-type): `PUT` `/_connector/{connector_id}/_service_type`
- [Update the connector status](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-connector-update-status): `PUT` `/_connector/{connector_id}/_status`
### [Cross-cluster replication](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-ccr)

- [Get auto-follow patterns](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ccr-get-auto-follow-pattern): `GET` `/_ccr/auto_follow/{name}`, `GET` `/_ccr/auto_follow`
- [Create or update auto-follow patterns](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ccr-put-auto-follow-pattern): `PUT` `/_ccr/auto_follow/{name}`
- [Delete auto-follow patterns](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ccr-delete-auto-follow-pattern): `DELETE` `/_ccr/auto_follow/{name}`
- [Pause an auto-follow pattern](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ccr-pause-auto-follow-pattern): `POST` `/_ccr/auto_follow/{name}/pause`
- [Resume an auto-follow pattern](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ccr-resume-auto-follow-pattern): `POST` `/_ccr/auto_follow/{name}/resume`
- [Get cross-cluster replication stats](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ccr-stats): `GET` `/_ccr/stats`
- [Create a follower](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ccr-follow): `PUT` `/{index}/_ccr/follow`
- [Forget a follower](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ccr-forget-follower): `POST` `/{index}/_ccr/forget_follower`
- [Get follower information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ccr-follow-info): `GET` `/{index}/_ccr/info`
- [Pause a follower](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ccr-pause-follow): `POST` `/{index}/_ccr/pause_follow`
- [Resume a follower](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ccr-resume-follow): `POST` `/{index}/_ccr/resume_follow`
- [Get follower stats](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ccr-follow-stats): `GET` `/{index}/_ccr/stats`
- [Unfollow an index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ccr-unfollow): `POST` `/{index}/_ccr/unfollow`
### [Data stream](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-data-stream)

- [Convert an index alias to a data stream](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-migrate-to-data-stream): `POST` `/_data_stream/_migrate/{name}`
- [Update data streams](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-modify-data-stream): `POST` `/_data_stream/_modify`
- [Promote a data stream](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-promote-data-stream): `POST` `/_data_stream/_promote/{name}`
- [Get data streams](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-get-data-stream): `GET` `/_data_stream/{name}`, `GET` `/_data_stream`
- [Create a data stream](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-create-data-stream): `PUT` `/_data_stream/{name}`
- [Delete data streams](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-delete-data-stream): `DELETE` `/_data_stream/{name}`
- [Get data stream lifecycles](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-get-data-lifecycle): `GET` `/_data_stream/{name}/_lifecycle`
- [Update data stream lifecycles](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-put-data-lifecycle): `PUT` `/_data_stream/{name}/_lifecycle`
- [Get data stream mappings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-get-data-stream-mappings): `GET` `/_data_stream/{name}/_mappings`
- [Update data stream mappings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-put-data-stream-mappings): `PUT` `/_data_stream/{name}/_mappings`
- [Get data stream options](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-get-data-stream-options): `GET` `/_data_stream/{name}/_options`
- [Update data stream options](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-put-data-stream-options): `PUT` `/_data_stream/{name}/_options`
- [Delete data stream options](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-delete-data-stream-options): `DELETE` `/_data_stream/{name}/_options`
- [Get data stream settings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-get-data-stream-settings): `GET` `/_data_stream/{name}/_settings`
- [Update data stream settings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-put-data-stream-settings): `PUT` `/_data_stream/{name}/_settings`
- [Get data stream stats](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-data-streams-stats): `GET` `/_data_stream/{name}/_stats`, `GET` `/_data_stream/_stats`
- [Get data stream lifecycle stats](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-get-data-lifecycle-stats): `GET` `/_lifecycle/stats`
- [Downsample an index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-downsample): `POST` `/{index}/_downsample/{target_index}`
- [Get the status for a data stream lifecycle](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-explain-data-lifecycle): `GET` `/{index}/_lifecycle/explain`
### [Document](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-document)

- [Throttle a delete by query operation](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-delete-by-query-rethrottle): `POST` `/_delete_by_query/{task_id}/_rethrottle`
- [Reindex documents](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-reindex): `POST` `/_reindex`
- [Throttle a reindex operation](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-reindex-rethrottle): `POST` `/_reindex/{task_id}/_rethrottle`
- [Throttle an update by query operation](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-update-by-query-rethrottle): `POST` `/_update_by_query/{task_id}/_rethrottle`
- [Bulk index or delete documents](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-bulk): `POST` (also `PUT`) `/{index}/_bulk`, `POST` (also `PUT`) `/_bulk`
- [Create a new document in the index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-create): `POST` (also `PUT`) `/{index}/_create/{id}`
- [Delete documents](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-delete-by-query): `POST` `/{index}/_delete_by_query`
- [Get a document by its ID](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-get): `GET` `/{index}/_doc/{id}`
- [Create or update a document in an index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-index): `POST` (also `PUT`) `/{index}/_doc/{id}`, `POST` `/{index}/_doc`
- [Delete a document](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-delete): `DELETE` `/{index}/_doc/{id}`
- [Check a document](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-exists): `HEAD` `/{index}/_doc/{id}`
- [Get multiple documents](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-mget): `POST` (also `GET`) `/{index}/_mget`, `POST` (also `GET`) `/_mget`
- [Get multiple term vectors](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-mtermvectors): `POST` (also `GET`) `/{index}/_mtermvectors`, `POST` (also `GET`) `/_mtermvectors`
- [Get a document's source](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-get-source): `GET` `/{index}/_source/{id}`
- [Check for a document source](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-exists-source): `HEAD` `/{index}/_source/{id}`
- [Get term vector information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-termvectors): `POST` (also `GET`) `/{index}/_termvectors/{id}`, `POST` (also `GET`) `/{index}/_termvectors`
- [Update a document](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-update): `POST` `/{index}/_update/{id}`
- [Update documents](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-update-by-query): `POST` `/{index}/_update_by_query`
### [Enrich](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-enrich)

- [Get enrich stats](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-enrich-stats): `GET` `/_enrich/_stats`
- [Get an enrich policy](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-enrich-get-policy): `GET` `/_enrich/policy/{name}`, `GET` `/_enrich/policy`
- [Create an enrich policy](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-enrich-put-policy): `PUT` `/_enrich/policy/{name}`
- [Delete an enrich policy](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-enrich-delete-policy): `DELETE` `/_enrich/policy/{name}`
- [Run an enrich policy](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-enrich-execute-policy): `PUT` `/_enrich/policy/{name}/_execute`
### [EQL](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-eql)

- [Get the async EQL status](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-eql-get-status): `GET` `/_eql/search/status/{id}`
- [Get async EQL search results](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-eql-get): `GET` `/_eql/search/{id}`
- [Delete an async EQL search](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-eql-delete): `DELETE` `/_eql/search/{id}`
- [Get EQL search results](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-eql-search): `POST` (also `GET`) `/{index}/_eql/search`
### [ES|QL](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-esql)

- [Run an ES|QL query](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-esql-query): `POST` `/_query`
- [Run an async ES|QL query](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-esql-async-query): `POST` `/_query/async`
- [Get async ES|QL query results](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-esql-async-query-get): `GET` `/_query/async/{id}`
- [Delete an async ES|QL query](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-esql-async-query-delete): `DELETE` `/_query/async/{id}`
- [Stop async ES|QL query](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-esql-async-query-stop): `POST` `/_query/async/{id}/stop`
- [Get ES|QL data sources](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-esql-get-data-source): `GET` `/_query/data_source/{name}`, `GET` `/_query/data_source`
- [Create or update an ES|QL data source](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-esql-put-data-source): `PUT` `/_query/data_source/{name}`
- [Delete ES|QL data sources](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-esql-delete-data-source): `DELETE` `/_query/data_source/{name}`
- [Get ES|QL datasets](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-esql-get-dataset): `GET` `/_query/dataset/{name}`, `GET` `/_query/dataset`
- [Create or update an ES|QL dataset](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-esql-put-dataset): `PUT` `/_query/dataset/{name}`
- [Delete ES|QL datasets](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-esql-delete-dataset): `DELETE` `/_query/dataset/{name}`
- [Get running ES|QL queries information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-esql-list-queries): `GET` `/_query/queries`
- [Get a specific running ES|QL query information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-esql-get-query): `GET` `/_query/queries/{id}`
- [Get an ES|QL view](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-esql-get-view): `GET` `/_query/view/{name}`, `GET` `/_query/view`
- [Create or update an ES|QL view](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-esql-put-view): `PUT` `/_query/view/{name}`
- [Delete an ES|QL view](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-esql-delete-view): `DELETE` `/_query/view/{name}`
### [Features](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-features)

- [Get the features](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-features-get-features): `GET` `/_features`
- [Reset the features](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-features-reset-features): `POST` `/_features/_reset`
### [Fleet](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-fleet)

- [Run multiple Fleet searches](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-fleet-msearch): `POST` (also `GET`) `/{index}/_fleet/_fleet_msearch`, `POST` (also `GET`) `/_fleet/_fleet_msearch`
- [Run a Fleet search](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-fleet-search): `POST` (also `GET`) `/{index}/_fleet/_fleet_search`
- [Get global checkpoints](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-fleet-global-checkpoints): `GET` `/{index}/_fleet/global_checkpoints`
### [Graph explore](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-graph)

- [Explore graph analytics](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-graph-explore): `POST` (also `GET`) `/{index}/_graph/explore`
### [Index](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-indices)

- [Update aliases and delete indices atomically](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-update-aliases): `POST` `/_aliases`
- [Get component templates](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cluster-get-component-template): `GET` `/_component_template/{name}`, `GET` `/_component_template`
- [Create or update a component template](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cluster-put-component-template): `POST` (also `PUT`) `/_component_template/{name}`
- [Delete component templates](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cluster-delete-component-template): `DELETE` `/_component_template/{name}`
- [Check component templates](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cluster-exists-component-template): `HEAD` `/_component_template/{name}`
- [Get the dangling indices](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-dangling-indices-list-dangling-indices): `GET` `/_dangling`
- [Import a dangling index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-dangling-indices-import-dangling-index): `POST` `/_dangling/{index_uuid}`
- [Delete a dangling index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-dangling-indices-delete-dangling-index): `DELETE` `/_dangling/{index_uuid}`
- [Delete data stream lifecycles](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-delete-data-lifecycle): `DELETE` `/_data_stream/{name}/_lifecycle`
- [Simulate an index template](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-simulate-template): `POST` `/_index_template/_simulate/{name}`, `POST` `/_index_template/_simulate`
- [Simulate an index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-simulate-index-template): `POST` `/_index_template/_simulate_index/{name}`
- [Get index templates](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-get-index-template): `GET` `/_index_template/{name}`, `GET` `/_index_template`
- [Create or update an index template](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-put-index-template): `POST` (also `PUT`) `/_index_template/{name}`
- [Delete an index template](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-delete-index-template): `DELETE` `/_index_template/{name}`
- [Check index templates](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-exists-index-template): `HEAD` `/_index_template/{name}`
- [Resolve the cluster](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-resolve-cluster): `GET` `/_resolve/cluster/{name}`, `GET` `/_resolve/cluster`
- [Resolve indices](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-resolve-index): `POST` (also `GET`) `/_resolve/index/{name}`
- [Get legacy index templates](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-get-template): `GET` `/_template/{name}`, `GET` `/_template`
- [Create or update a legacy index template](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-put-template): `POST` (also `PUT`) `/_template/{name}`
- [Delete a legacy index template](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-delete-template): `DELETE` `/_template/{name}`
- [Check existence of index templates](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-exists-template): `HEAD` `/_template/{name}`
- [Roll over to a new index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-rollover): `POST` `/{alias}/_rollover/{new_index}`, `POST` `/{alias}/_rollover`
- [Get index information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-get): `GET` `/{index}`
- [Create an index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-create): `PUT` `/{index}`
- [Delete indices](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-delete): `DELETE` `/{index}`
- [Check indices](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-exists): `HEAD` `/{index}`
- [Get aliases](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-get-alias): `GET` `/{index}/_alias/{name}`, `GET` `/{index}/_alias`, `GET` `/_alias/{name}`, `GET` `/_alias`
- [Check aliases](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-exists-alias): `HEAD` `/{index}/_alias/{name}`, `HEAD` `/_alias/{name}`
- [Create or update an alias](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-put-alias): `POST` (also `PUT`) `/{index}/_aliases/{name}`, `POST` (also `PUT`) `/{index}/_alias/{name}`
- [Delete an alias](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-delete-alias): `DELETE` `/{index}/_aliases/{name}`, `DELETE` `/{index}/_alias/{name}`
- [Get tokens from text analysis](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-analyze): `POST` (also `GET`) `/{index}/_analyze`, `POST` (also `GET`) `/_analyze`
- [Add an index block](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-add-block): `PUT` `/{index}/_block/{block}`
- [Remove an index block](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-remove-block): `DELETE` `/{index}/_block/{block}`
- [Clear the cache](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-clear-cache): `POST` `/{index}/_cache/clear`, `POST` `/_cache/clear`
- [Clone an index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-clone): `POST` (also `PUT`) `/{index}/_clone/{target}`
- [Close an index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-close): `POST` `/{index}/_close`
- [Analyze the index disk usage](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-disk-usage): `POST` `/{index}/_disk_usage`
- [Get field usage stats](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-field-usage-stats): `GET` `/{index}/_field_usage_stats`
- [Flush data streams or indices](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-flush): `POST` (also `GET`) `/{index}/_flush`, `POST` (also `GET`) `/_flush`
- [Force a merge](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-forcemerge): `POST` `/{index}/_forcemerge`, `POST` `/_forcemerge`
- [Get mapping definitions](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-get-mapping): `GET` `/{index}/_mapping`, `GET` `/_mapping`
- [Update field mappings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-put-mapping): `POST` (also `PUT`) `/{index}/_mapping`
- [Get field mapping definitions](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-get-field-mapping): `GET` `/{index}/_mapping/field/{fields}`, `GET` `/_mapping/field/{fields}`
- [Open a closed index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-open): `POST` `/{index}/_open`
- [Get index recovery information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-recovery): `GET` `/{index}/_recovery`, `GET` `/_recovery`
- [Refresh an index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-refresh): `POST` (also `GET`) `/{index}/_refresh`, `POST` (also `GET`) `/_refresh`
- [Reload search analyzers](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-reload-search-analyzers): `POST` (also `GET`) `/{index}/_reload_search_analyzers`
- [Get index segments](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-segments): `GET` `/{index}/_segments`, `GET` `/_segments`
- [Update index settings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-put-settings): `PUT` `/{index}/_settings`, `PUT` `/_settings`
- [Get index settings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-get-settings): `GET` `/{index}/_settings/{name}`, `GET` `/{index}/_settings`, `GET` `/_settings/{name}`, `GET` `/_settings`
- [Get index shard stores](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-shard-stores): `GET` `/{index}/_shard_stores`, `GET` `/_shard_stores`
- [Shrink an index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-shrink): `POST` (also `PUT`) `/{index}/_shrink/{target}`
- [Split an index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-split): `POST` (also `PUT`) `/{index}/_split/{target}`
- [Get index statistics](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-stats): `GET` `/{index}/_stats/{metric}`, `GET` `/_stats/{metric}`, `GET` `/{index}/_stats`, `GET` `/_stats`
- [Validate a query](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-validate-query): `POST` (also `GET`) `/{index}/_validate/query`, `POST` (also `GET`) `/_validate/query`
### [Index lifecycle management](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-ilm)

- [Migrate to data tiers routing](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ilm-migrate-to-data-tiers): `POST` `/_ilm/migrate_to_data_tiers`
- [Move to a lifecycle step](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ilm-move-to-step): `POST` `/_ilm/move/{index}`
- [Get lifecycle policies](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ilm-get-lifecycle): `GET` `/_ilm/policy/{policy}`, `GET` `/_ilm/policy`
- [Create or update a lifecycle policy](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ilm-put-lifecycle): `PUT` `/_ilm/policy/{policy}`
- [Delete a lifecycle policy](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ilm-delete-lifecycle): `DELETE` `/_ilm/policy/{policy}`
- [Start the ILM plugin](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ilm-start): `POST` `/_ilm/start`
- [Get the ILM status](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ilm-get-status): `GET` `/_ilm/status`
- [Stop the ILM plugin](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ilm-stop): `POST` `/_ilm/stop`
- [Explain the lifecycle state](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ilm-explain-lifecycle): `GET` `/{index}/_ilm/explain`
- [Remove policies from an index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ilm-remove-policy): `POST` `/{index}/_ilm/remove`
- [Retry a policy](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ilm-retry): `POST` `/{index}/_ilm/retry`
### [Inference](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-inference)

- [Get the inference region policy](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-get-region-policy): `GET` `/_inference/_region_policy`
- [Create or update the inference region policy](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-region-policy): `PUT` `/_inference/_region_policy`
- [Delete the inference region policy](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-delete-region-policy): `DELETE` `/_inference/_region_policy`
- [Perform non-streaming chat completion inference on the service](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-non-streaming-chat-completion): `POST` `/_inference/chat_completion/{inference_id}`
- [Perform streaming chat completion inference on the service](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-chat-completion-unified): `POST` `/_inference/chat_completion/{inference_id}/_stream`
- [Perform completion inference on the service](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-completion): `POST` `/_inference/completion/{inference_id}`
- [Perform streaming completion inference on the service](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-stream-completion): `POST` `/_inference/completion/{inference_id}/_stream`
- [Perform decision inference on the service](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-decision): `POST` `/_inference/decision/{inference_id}`
- [Perform document extraction inference on the service](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-document-extraction): `POST` `/_inference/document_extraction/{inference_id}`
- [Perform dense embedding inference on the service](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-embedding): `POST` `/_inference/embedding/{inference_id}`
- [Perform reranking inference on the service](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-rerank): `POST` `/_inference/rerank/{inference_id}`
- [Perform sparse embedding inference on the service](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-sparse-embedding): `POST` `/_inference/sparse_embedding/{inference_id}`
- [Perform text embedding inference on the service](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-text-embedding): `POST` `/_inference/text_embedding/{inference_id}`
- [Create a AI21 inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-ai21): `PUT` `/_inference/{task_type}/{ai21_inference_id}`
- [Create an AlibabaCloud AI Search inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-alibabacloud): `PUT` `/_inference/{task_type}/{alibabacloud_inference_id}`
- [Create an Amazon Bedrock inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-amazonbedrock): `PUT` `/_inference/{task_type}/{amazonbedrock_inference_id}`
- [Create an Amazon SageMaker inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-amazonsagemaker): `PUT` `/_inference/{task_type}/{amazonsagemaker_inference_id}`
- [Create an Anthropic inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-anthropic): `PUT` `/_inference/{task_type}/{anthropic_inference_id}`
- [Create an Azure AI studio inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-azureaistudio): `PUT` `/_inference/{task_type}/{azureaistudio_inference_id}`
- [Create an Azure OpenAI inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-azureopenai): `PUT` `/_inference/{task_type}/{azureopenai_inference_id}`
- [Create a Cohere inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-cohere): `PUT` `/_inference/{task_type}/{cohere_inference_id}`
- [Create an Contextual AI inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-contextualai): `PUT` `/_inference/{task_type}/{contextualai_inference_id}`
- [Create a custom inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-custom): `PUT` `/_inference/{task_type}/{custom_inference_id}`
- [Create a DeepSeek inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-deepseek): `PUT` `/_inference/{task_type}/{deepseek_inference_id}`
- [Create an Elasticsearch inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-elasticsearch): `PUT` `/_inference/{task_type}/{elasticsearch_inference_id}`
- [Create an ELSER inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-elser): `PUT` `/_inference/{task_type}/{elser_inference_id}`
- [Create a Fireworks AI inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-fireworksai): `PUT` `/_inference/{task_type}/{fireworksai_inference_id}`
- [Create an Google AI Studio inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-googleaistudio): `PUT` `/_inference/{task_type}/{googleaistudio_inference_id}`
- [Create a Google Vertex AI inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-googlevertexai): `PUT` `/_inference/{task_type}/{googlevertexai_inference_id}`
- [Create a Groq inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-groq): `PUT` `/_inference/{task_type}/{groq_inference_id}`
- [Create a Hugging Face inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-hugging-face): `PUT` `/_inference/{task_type}/{huggingface_inference_id}`
- [Get an inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-get): `GET` `/_inference/{task_type}/{inference_id}`, `GET` `/_inference/{task_type}/_all`, `GET` `/_inference/{inference_id}`, `GET` `/_inference`
- [Perform inference on the service](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-inference): `POST` `/_inference/{task_type}/{inference_id}`, `POST` `/_inference/{inference_id}`
- [Create an inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put): `PUT` `/_inference/{task_type}/{inference_id}`, `PUT` `/_inference/{inference_id}`
- [Delete an inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-delete): `DELETE` `/_inference/{task_type}/{inference_id}`, `DELETE` `/_inference/{inference_id}`
- [Update an inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-update): `PUT` `/_inference/{task_type}/{inference_id}/_update`, `PUT` `/_inference/{inference_id}/_update`
- [Create an JinaAI inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-jinaai): `PUT` `/_inference/{task_type}/{jinaai_inference_id}`
- [Create a Llama inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-llama): `PUT` `/_inference/{task_type}/{llama_inference_id}`
- [Create a Mistral inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-mistral): `PUT` `/_inference/{task_type}/{mistral_inference_id}`
- [Create an Nvidia inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-nvidia): `PUT` `/_inference/{task_type}/{nvidia_inference_id}`
- [Create an OpenAI inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-openai): `PUT` `/_inference/{task_type}/{openai_inference_id}`
- [Create an OpenShift AI inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-openshift-ai): `PUT` `/_inference/{task_type}/{openshiftai_inference_id}`
- [Create a VoyageAI inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-voyageai): `PUT` `/_inference/{task_type}/{voyageai_inference_id}`
- [Create a Watsonx inference endpoint](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-inference-put-watsonx): `PUT` `/_inference/{task_type}/{watsonx_inference_id}`
### [Info](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-info)

- [Get cluster info](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-info): `GET` `/`
### [Ingest](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-ingest)

- [Get GeoIP database configurations](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ingest-get-geoip-database): `GET` `/_ingest/geoip/database/{id}`, `GET` `/_ingest/geoip/database`
- [Create or update a GeoIP database configuration](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ingest-put-geoip-database): `PUT` `/_ingest/geoip/database/{id}`
- [Delete GeoIP database configurations](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ingest-delete-geoip-database): `DELETE` `/_ingest/geoip/database/{id}`
- [Get GeoIP statistics](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ingest-geo-ip-stats): `GET` `/_ingest/geoip/stats`
- [Get IP geolocation database configurations](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ingest-get-ip-location-database): `GET` `/_ingest/ip_location/database/{id}`, `GET` `/_ingest/ip_location/database`
- [Create or update an IP geolocation database configuration](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ingest-put-ip-location-database): `PUT` `/_ingest/ip_location/database/{id}`
- [Delete IP geolocation database configurations](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ingest-delete-ip-location-database): `DELETE` `/_ingest/ip_location/database/{id}`
- [Get pipelines](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ingest-get-pipeline): `GET` `/_ingest/pipeline/{id}`, `GET` `/_ingest/pipeline`
- [Create or update a pipeline](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ingest-put-pipeline): `PUT` `/_ingest/pipeline/{id}`
- [Delete pipelines](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ingest-delete-pipeline): `DELETE` `/_ingest/pipeline/{id}`
- [Simulate a pipeline](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ingest-simulate): `POST` (also `GET`) `/_ingest/pipeline/{id}/_simulate`, `POST` (also `GET`) `/_ingest/pipeline/_simulate`
- [Run a grok processor](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ingest-processor-grok): `GET` `/_ingest/processor/grok`
- [Simulate data ingestion](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-simulate-ingest): `POST` (also `GET`) `/_ingest/{index}/_simulate`, `POST` (also `GET`) `/_ingest/_simulate`
### [Licensing](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-license)

- [Get license information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-license-get): `GET` `/_license`
- [Update the license](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-license-post): `POST` (also `PUT`) `/_license`
- [Delete the license](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-license-delete): `DELETE` `/_license`
- [Get the basic license status](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-license-get-basic-status): `GET` `/_license/basic_status`
- [Start a basic license](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-license-post-start-basic): `POST` `/_license/start_basic`
- [Start a trial](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-license-post-start-trial): `POST` `/_license/start_trial`
- [Get the trial status](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-license-get-trial-status): `GET` `/_license/trial_status`
### [Logstash](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-logstash)

- [Get Logstash pipelines](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-logstash-get-pipeline): `GET` `/_logstash/pipeline/{id}`, `GET` `/_logstash/pipeline`
- [Create or update a Logstash pipeline](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-logstash-put-pipeline): `PUT` `/_logstash/pipeline/{id}`
- [Delete a Logstash pipeline](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-logstash-delete-pipeline): `DELETE` `/_logstash/pipeline/{id}`
### [Machine learning](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-ml)

- [Get machine learning information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-info): `GET` `/_ml/info`
- [Get machine learning memory usage info](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-memory-stats): `GET` `/_ml/memory/{node_id}/_stats`, `GET` `/_ml/memory/_stats`
- [Set upgrade_mode for ML indices](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-set-upgrade-mode): `POST` `/_ml/set_upgrade_mode`
### [Machine learning anomaly detection](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-ml-anomaly)

- [Delete expired ML data](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-delete-expired-data): `DELETE` `/_ml/_delete_expired_data/{job_id}`, `DELETE` `/_ml/_delete_expired_data`
- [Estimate job model memory usage](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-estimate-model-memory): `POST` `/_ml/anomaly_detectors/_estimate_model_memory`
- [Get anomaly detection jobs configuration info](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-jobs): `GET` `/_ml/anomaly_detectors/{job_id}`, `GET` `/_ml/anomaly_detectors`
- [Create an anomaly detection job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-put-job): `PUT` `/_ml/anomaly_detectors/{job_id}`
- [Delete an anomaly detection job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-delete-job): `DELETE` `/_ml/anomaly_detectors/{job_id}`
- [Close anomaly detection jobs](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-close-job): `POST` `/_ml/anomaly_detectors/{job_id}/_close`
- [Send data to an anomaly detection job for analysis](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-post-data): `POST` `/_ml/anomaly_detectors/{job_id}/_data`
- [Force buffered data to be processed](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-flush-job): `POST` `/_ml/anomaly_detectors/{job_id}/_flush`
- [Predict future behavior of a time series](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-forecast): `POST` `/_ml/anomaly_detectors/{job_id}/_forecast`
- [Delete forecasts from a job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-delete-forecast): `DELETE` `/_ml/anomaly_detectors/{job_id}/_forecast/{forecast_id}`, `DELETE` `/_ml/anomaly_detectors/{job_id}/_forecast`
- [Open anomaly detection jobs](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-open-job): `POST` `/_ml/anomaly_detectors/{job_id}/_open`
- [Reset an anomaly detection job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-reset-job): `POST` `/_ml/anomaly_detectors/{job_id}/_reset`
- [Get anomaly detection job stats](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-job-stats): `GET` `/_ml/anomaly_detectors/{job_id}/_stats`, `GET` `/_ml/anomaly_detectors/_stats`
- [Update an anomaly detection job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-update-job): `POST` `/_ml/anomaly_detectors/{job_id}/_update`
- [Get model snapshots info](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-model-snapshots): `POST` (also `GET`) `/_ml/anomaly_detectors/{job_id}/model_snapshots/{snapshot_id}`, `POST` (also `GET`) `/_ml/anomaly_detectors/{job_id}/model_snapshots`
- [Delete a model snapshot](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-delete-model-snapshot): `DELETE` `/_ml/anomaly_detectors/{job_id}/model_snapshots/{snapshot_id}`
- [Revert to a snapshot](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-revert-model-snapshot): `POST` `/_ml/anomaly_detectors/{job_id}/model_snapshots/{snapshot_id}/_revert`
- [Update a snapshot](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-update-model-snapshot): `POST` `/_ml/anomaly_detectors/{job_id}/model_snapshots/{snapshot_id}/_update`
- [Upgrade a snapshot](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-upgrade-job-snapshot): `POST` `/_ml/anomaly_detectors/{job_id}/model_snapshots/{snapshot_id}/_upgrade`
- [Get anomaly detection job model snapshot upgrade usage info](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-model-snapshot-upgrade-stats): `GET` `/_ml/anomaly_detectors/{job_id}/model_snapshots/{snapshot_id}/_upgrade/_stats`
- [Get anomaly detection job results for buckets](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-buckets): `POST` (also `GET`) `/_ml/anomaly_detectors/{job_id}/results/buckets/{timestamp}`, `POST` (also `GET`) `/_ml/anomaly_detectors/{job_id}/results/buckets`
- [Get anomaly detection job results for categories](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-categories): `POST` (also `GET`) `/_ml/anomaly_detectors/{job_id}/results/categories/{category_id}`, `POST` (also `GET`) `/_ml/anomaly_detectors/{job_id}/results/categories`
- [Get anomaly detection job results for influencers](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-influencers): `POST` (also `GET`) `/_ml/anomaly_detectors/{job_id}/results/influencers`
- [Get overall bucket results](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-overall-buckets): `POST` (also `GET`) `/_ml/anomaly_detectors/{job_id}/results/overall_buckets`
- [Get anomaly records for an anomaly detection job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-records): `POST` (also `GET`) `/_ml/anomaly_detectors/{job_id}/results/records`
- [Get calendar configuration info](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-calendars): `POST` (also `GET`) `/_ml/calendars/{calendar_id}`, `POST` (also `GET`) `/_ml/calendars`
- [Create a calendar](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-put-calendar): `PUT` `/_ml/calendars/{calendar_id}`
- [Delete a calendar](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-delete-calendar): `DELETE` `/_ml/calendars/{calendar_id}`
- [Get info about events in calendars](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-calendar-events): `GET` `/_ml/calendars/{calendar_id}/events`
- [Add scheduled events to the calendar](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-post-calendar-events): `POST` `/_ml/calendars/{calendar_id}/events`
- [Delete events from a calendar](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-delete-calendar-event): `DELETE` `/_ml/calendars/{calendar_id}/events/{event_id}`
- [Add anomaly detection job to calendar](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-put-calendar-job): `PUT` `/_ml/calendars/{calendar_id}/jobs/{job_id}`
- [Delete anomaly jobs from a calendar](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-delete-calendar-job): `DELETE` `/_ml/calendars/{calendar_id}/jobs/{job_id}`
- [Get datafeeds configuration info](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-datafeeds): `GET` `/_ml/datafeeds/{datafeed_id}`, `GET` `/_ml/datafeeds`
- [Create a datafeed](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-put-datafeed): `PUT` `/_ml/datafeeds/{datafeed_id}`
- [Delete a datafeed](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-delete-datafeed): `DELETE` `/_ml/datafeeds/{datafeed_id}`
- [Preview a datafeed](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-preview-datafeed): `POST` (also `GET`) `/_ml/datafeeds/{datafeed_id}/_preview`, `POST` (also `GET`) `/_ml/datafeeds/_preview`
- [Start datafeeds](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-start-datafeed): `POST` `/_ml/datafeeds/{datafeed_id}/_start`
- [Get datafeed stats](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-datafeed-stats): `GET` `/_ml/datafeeds/{datafeed_id}/_stats`, `GET` `/_ml/datafeeds/_stats`
- [Stop datafeeds](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-stop-datafeed): `POST` `/_ml/datafeeds/{datafeed_id}/_stop`
- [Update a datafeed](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-update-datafeed): `POST` `/_ml/datafeeds/{datafeed_id}/_update`
- [Get filters](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-filters): `GET` `/_ml/filters/{filter_id}`, `GET` `/_ml/filters`
- [Create a filter](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-put-filter): `PUT` `/_ml/filters/{filter_id}`
- [Delete a filter](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-delete-filter): `DELETE` `/_ml/filters/{filter_id}`
- [Update a filter](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-update-filter): `POST` `/_ml/filters/{filter_id}/_update`
### [Machine learning data frame analytics](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-ml-data-frame)

- [Evaluate data frame analytics](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-evaluate-data-frame): `POST` `/_ml/data_frame/_evaluate`
- [Get data frame analytics job configuration info](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-data-frame-analytics): `GET` `/_ml/data_frame/analytics/{id}`, `GET` `/_ml/data_frame/analytics`
- [Create a data frame analytics job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-put-data-frame-analytics): `PUT` `/_ml/data_frame/analytics/{id}`
- [Delete a data frame analytics job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-delete-data-frame-analytics): `DELETE` `/_ml/data_frame/analytics/{id}`
- [Explain data frame analytics config](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-explain-data-frame-analytics): `POST` (also `GET`) `/_ml/data_frame/analytics/{id}/_explain`, `POST` (also `GET`) `/_ml/data_frame/analytics/_explain`
- [Preview features used by data frame analytics](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-preview-data-frame-analytics): `POST` (also `GET`) `/_ml/data_frame/analytics/{id}/_preview`, `POST` (also `GET`) `/_ml/data_frame/analytics/_preview`
- [Start a data frame analytics job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-start-data-frame-analytics): `POST` `/_ml/data_frame/analytics/{id}/_start`
- [Get data frame analytics job stats](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-data-frame-analytics-stats): `GET` `/_ml/data_frame/analytics/{id}/_stats`, `GET` `/_ml/data_frame/analytics/_stats`
- [Stop data frame analytics jobs](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-stop-data-frame-analytics): `POST` `/_ml/data_frame/analytics/{id}/_stop`
- [Update a data frame analytics job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-update-data-frame-analytics): `POST` `/_ml/data_frame/analytics/{id}/_update`
### [Machine learning trained model](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-ml-trained-model)

- [Get trained model configuration info](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-trained-models): `GET` `/_ml/trained_models/{model_id}`, `GET` `/_ml/trained_models`
- [Create a trained model](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-put-trained-model): `PUT` `/_ml/trained_models/{model_id}`
- [Delete an unreferenced trained model](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-delete-trained-model): `DELETE` `/_ml/trained_models/{model_id}`
- [Evaluate a trained model](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-infer-trained-model): `POST` `/_ml/trained_models/{model_id}/_infer`
- [Get trained models usage info](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-get-trained-models-stats): `GET` `/_ml/trained_models/{model_id}/_stats`, `GET` `/_ml/trained_models/_stats`
- [Create part of a trained model definition](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-put-trained-model-definition-part): `PUT` `/_ml/trained_models/{model_id}/definition/{part}`
- [Start a trained model deployment](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-start-trained-model-deployment): `POST` `/_ml/trained_models/{model_id}/deployment/_start`
- [Stop a trained model deployment](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-stop-trained-model-deployment): `POST` `/_ml/trained_models/{model_id}/deployment/_stop`
- [Update a trained model deployment](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-update-trained-model-deployment): `POST` `/_ml/trained_models/{model_id}/deployment/_update`
- [Clear trained model deployment cache](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-clear-trained-model-deployment-cache): `POST` `/_ml/trained_models/{model_id}/deployment/cache/_clear`
- [Create or update a trained model alias](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-put-trained-model-alias): `PUT` `/_ml/trained_models/{model_id}/model_aliases/{model_alias}`
- [Delete a trained model alias](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-delete-trained-model-alias): `DELETE` `/_ml/trained_models/{model_id}/model_aliases/{model_alias}`
- [Create a trained model vocabulary](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ml-put-trained-model-vocabulary): `PUT` `/_ml/trained_models/{model_id}/vocabulary`
### [Migration](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-migration)

- [Create an index from a source index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-create-from): `POST` (also `PUT`) `/_create_from/{source}/{dest}`
- [Reindex legacy backing indices](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-migrate-reindex): `POST` `/_migration/reindex`
- [Cancel a migration reindex operation](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-cancel-migrate-reindex): `POST` `/_migration/reindex/{index}/_cancel`
- [Get the migration reindexing status](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-indices-get-migrate-reindex-status): `GET` `/_migration/reindex/{index}/_status`
- [Get feature migration information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-migration-get-feature-upgrade-status): `GET` `/_migration/system_features`
- [Start the feature migration](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-migration-post-feature-upgrade): `POST` `/_migration/system_features`
- [Get deprecation information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-migration-deprecations): `GET` `/{index}/_migration/deprecations`, `GET` `/_migration/deprecations`
### [Prometheus](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-prometheus)

- [Ingest Prometheus remote write data](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-prometheus-remote-write): `POST` `/_prometheus/metrics/{dataset}/{namespace}/api/v1/write`, `POST` `/_prometheus/metrics/{dataset}/api/v1/write`, `POST` `/_prometheus/api/v1/write`
- [Get Prometheus label values](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-prometheus-label-values): `GET` `/_prometheus/{index}/api/v1/label/{name}/values`, `GET` `/_prometheus/api/v1/label/{name}/values`
- [Get Prometheus label names](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-prometheus-labels): `POST` (also `GET`) `/_prometheus/{index}/api/v1/labels`, `POST` (also `GET`) `/_prometheus/api/v1/labels`
- [Get Prometheus metric metadata](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-prometheus-metadata): `GET` `/_prometheus/{index}/api/v1/metadata`, `GET` `/_prometheus/api/v1/metadata`
- [Run a PromQL instant query](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-prometheus-query): `POST` (also `GET`) `/_prometheus/{index}/api/v1/query`, `POST` (also `GET`) `/_prometheus/api/v1/query`
- [Run a PromQL range query](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-prometheus-query-range): `POST` (also `GET`) `/_prometheus/{index}/api/v1/query_range`, `POST` (also `GET`) `/_prometheus/api/v1/query_range`
- [Find Prometheus series](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-prometheus-series): `POST` (also `GET`) `/_prometheus/{index}/api/v1/series`, `POST` (also `GET`) `/_prometheus/api/v1/series`
- [Get Prometheus build information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-prometheus-status-buildinfo): `GET` `/_prometheus/{index}/api/v1/status/buildinfo`, `GET` `/_prometheus/api/v1/status/buildinfo`
### [Query rules](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-query_rules)

- [Get all query rulesets](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-query-rules-list-rulesets): `GET` `/_query_rules`
- [Get a query ruleset](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-query-rules-get-ruleset): `GET` `/_query_rules/{ruleset_id}`
- [Create or update a query ruleset](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-query-rules-put-ruleset): `PUT` `/_query_rules/{ruleset_id}`
- [Delete a query ruleset](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-query-rules-delete-ruleset): `DELETE` `/_query_rules/{ruleset_id}`
- [Get a query rule](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-query-rules-get-rule): `GET` `/_query_rules/{ruleset_id}/_rule/{rule_id}`
- [Create or update a query rule](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-query-rules-put-rule): `PUT` `/_query_rules/{ruleset_id}/_rule/{rule_id}`
- [Delete a query rule](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-query-rules-delete-rule): `DELETE` `/_query_rules/{ruleset_id}/_rule/{rule_id}`
- [Test a query ruleset](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-query-rules-test): `POST` `/_query_rules/{ruleset_id}/_test`
### [Reindex](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-reindex)

- [Get information about all currently running reindex tasks](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-list-reindex): `GET` `/_reindex`
- [Get the status and progress of a specific reindex task](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-get-reindex): `GET` `/_reindex/{task_id}`
- [Cancel an ongoing reindex task](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-cancel-reindex): `POST` `/_reindex/{task_id}/_cancel`
### [Rollup](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-rollup)

- [Get the rollup job capabilities](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-rollup-get-rollup-caps): `GET` `/_rollup/data/{id}`, `GET` `/_rollup/data`
- [Get rollup job information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-rollup-get-jobs): `GET` `/_rollup/job/{id}`, `GET` `/_rollup/job`
- [Create a rollup job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-rollup-put-job): `PUT` `/_rollup/job/{id}`
- [Delete a rollup job](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-rollup-delete-job): `DELETE` `/_rollup/job/{id}`
- [Start rollup jobs](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-rollup-start-job): `POST` `/_rollup/job/{id}/_start`
- [Stop rollup jobs](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-rollup-stop-job): `POST` `/_rollup/job/{id}/_stop`
- [Get the rollup index capabilities](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-rollup-get-rollup-index-caps): `GET` `/{index}/_rollup/data`
- [Search rolled-up data](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-rollup-rollup-search): `POST` (also `GET`) `/{index}/_rollup_search`
### [Script](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-script)

- [Get script contexts](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-get-script-context): `GET` `/_script_context`
- [Get script languages](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-get-script-languages): `GET` `/_script_language`
- [Run a script](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-scripts-painless-execute): `POST` (also `GET`) `/_scripts/painless/_execute`
- [Get a script or search template](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-get-script): `GET` `/_scripts/{id}`
- [Delete a script or search template](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-delete-script): `DELETE` `/_scripts/{id}`
- [Create or update a script or search template](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-put-script): `POST` (also `PUT`) `/_scripts/{id}/{context}`, `POST` (also `PUT`) `/_scripts/{id}`
### [Search](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-search)

- [Get the async search status](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-async-search-status): `GET` `/_async_search/status/{id}`
- [Get async search results](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-async-search-get): `GET` `/_async_search/{id}`
- [Delete an async search](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-async-search-delete): `DELETE` `/_async_search/{id}`
- [Close a point in time](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-close-point-in-time): `DELETE` `/_pit`
- [Render a search template](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-render-search-template): `POST` (also `GET`) `/_render/template/{id}`, `POST` (also `GET`) `/_render/template`
- [Run a scrolling search](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-scroll): `POST` (also `GET`) `/_search/scroll/{scroll_id}`, `POST` (also `GET`) `/_search/scroll`
- [Clear a scrolling search](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-clear-scroll): `DELETE` `/_search/scroll/{scroll_id}`, `DELETE` `/_search/scroll`
- [Run an async search](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-async-search-submit): `POST` `/{index}/_async_search`, `POST` `/_async_search`
- [Count search results](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-count): `POST` (also `GET`) `/{index}/_count`, `POST` (also `GET`) `/_count`
- [Explain a document match result](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-explain): `POST` (also `GET`) `/{index}/_explain/{id}`
- [Get the field capabilities](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-field-caps): `POST` (also `GET`) `/{index}/_field_caps`, `POST` (also `GET`) `/_field_caps`
- [Evaluate kNN search settings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-knn-eval): `POST` (also `GET`) `/{index}/_knn_eval`
- [Run multiple searches](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-msearch): `POST` (also `GET`) `/{index}/_msearch`, `POST` (also `GET`) `/_msearch`
- [Run multiple templated searches](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-msearch-template): `POST` (also `GET`) `/{index}/_msearch/template`, `POST` (also `GET`) `/_msearch/template`
- [Search a vector tile](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-search-mvt): `POST` (also `GET`) `/{index}/_mvt/{field}/{zoom}/{x}/{y}`
- [Open a point in time](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-open-point-in-time): `POST` `/{index}/_pit`
- [Evaluate ranked search results](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-rank-eval): `POST` (also `GET`) `/{index}/_rank_eval`, `POST` (also `GET`) `/_rank_eval`
- [Run a search](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-search): `POST` (also `GET`) `/{index}/_search`, `POST` (also `GET`) `/_search`
- [Run a search with a search template](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-search-template): `POST` (also `GET`) `/{index}/_search/template`, `POST` (also `GET`) `/_search/template`
- [Get the search shards](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-search-shards): `POST` (also `GET`) `/{index}/_search_shards`, `POST` (also `GET`) `/_search_shards`
- [Get terms in an index](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-terms-enum): `POST` (also `GET`) `/{index}/_terms_enum`
### [Search application](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-search_application)

- [Get search applications](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-search-application-list): `GET` `/_application/search_application`
- [Get search application details](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-search-application-get): `GET` `/_application/search_application/{name}`
- [Create or update a search application](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-search-application-put): `PUT` `/_application/search_application/{name}`
- [Delete a search application](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-search-application-delete): `DELETE` `/_application/search_application/{name}`
- [Render a search application query](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-search-application-render-query): `POST` `/_application/search_application/{name}/_render_query`
- [Run a search application search](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-search-application-search): `POST` (also `GET`) `/_application/search_application/{name}/_search`
### [Searchable snapshots](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-searchable_snapshots)

- [Get cache statistics](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-searchable-snapshots-cache-stats): `GET` `/_searchable_snapshots/{node_id}/cache/stats`, `GET` `/_searchable_snapshots/cache/stats`
- [Mount a snapshot](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-searchable-snapshots-mount): `POST` `/_snapshot/{repository}/{snapshot}/_mount`
- [Clear the searchable snapshots shared cache](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-searchable-snapshots-clear-cache): `POST` `/{index}/_searchable_snapshots/cache/clear`, `POST` `/_searchable_snapshots/cache/clear`
- [Get searchable snapshot statistics](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-searchable-snapshots-stats): `GET` `/{index}/_searchable_snapshots/stats`, `GET` `/_searchable_snapshots/stats`
### [Security](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-security)

- [Reset the project encryption key](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-encryption-reset): `POST` `/_encryption/_reset`
- [Authenticate a user](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-authenticate): `GET` `/_security/_authenticate`
- [Find API keys with a query](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-query-api-keys): `POST` (also `GET`) `/_security/_query/api_key`
- [Find roles with a query](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-query-role): `POST` (also `GET`) `/_security/_query/role`
- [Find users with a query](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-query-user): `POST` (also `GET`) `/_security/_query/user`
- [Get API key information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-get-api-key): `GET` `/_security/api_key`
- [Create an API key](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-create-api-key): `POST` (also `PUT`) `/_security/api_key`
- [Invalidate API keys](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-invalidate-api-key): `DELETE` `/_security/api_key`
- [Bulk update API keys](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-bulk-update-api-keys): `POST` `/_security/api_key/_bulk_update`
- [Clone an API key](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-clone-api-key): `POST` (also `PUT`) `/_security/api_key/clone`
- [Grant an API key](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-grant-api-key): `POST` `/_security/api_key/grant`
- [Clear the API key cache](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-clear-api-key-cache): `POST` `/_security/api_key/{ids}/_clear_cache`
- [Update an API key](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-update-api-key): `PUT` `/_security/api_key/{id}`
- [Create a cross-cluster API key](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-create-cross-cluster-api-key): `POST` `/_security/cross_cluster/api_key`
- [Update a cross-cluster API key](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-update-cross-cluster-api-key): `PUT` `/_security/cross_cluster/api_key/{id}`
- [Delegate PKI authentication](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-delegate-pki): `POST` `/_security/delegate_pki`
- [Enroll Kibana](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-enroll-kibana): `GET` `/_security/enroll/kibana`
- [Enroll a node](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-enroll-node): `GET` `/_security/enroll/node`
- [Get a token](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-get-token): `POST` `/_security/oauth2/token`
- [Invalidate a token](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-invalidate-token): `DELETE` `/_security/oauth2/token`
- [Authenticate OpenID Connect](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-oidc-authenticate): `POST` `/_security/oidc/authenticate`
- [Logout of OpenID Connect](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-oidc-logout): `POST` `/_security/oidc/logout`
- [Prepare OpenID connect authentication](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-oidc-prepare-authentication): `POST` `/_security/oidc/prepare`
- [Create or update application privileges](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-put-privileges): `POST` (also `PUT`) `/_security/privilege`
- [Get builtin privileges](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-get-builtin-privileges): `GET` `/_security/privilege/_builtin`
- [Clear the privileges cache](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-clear-cached-privileges): `POST` `/_security/privilege/{application}/_clear_cache`
- [Get application privileges](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-get-privileges): `GET` `/_security/privilege/{application}/{name}`, `GET` `/_security/privilege/{application}`, `GET` `/_security/privilege`
- [Delete application privileges](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-delete-privileges): `DELETE` `/_security/privilege/{application}/{name}`
- [Activate a user profile](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-activate-user-profile): `POST` `/_security/profile/_activate`
- [Check user profile privileges](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-has-privileges-user-profile): `POST` (also `GET`) `/_security/profile/_has_privileges`
- [Suggest a user profile](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-suggest-user-profiles): `POST` (also `GET`) `/_security/profile/_suggest`
- [Get a user profile](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-get-user-profile): `GET` `/_security/profile/{uid}`
- [Update user profile data](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-update-user-profile-data): `POST` (also `PUT`) `/_security/profile/{uid}/_data`
- [Disable a user profile](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-disable-user-profile): `POST` (also `PUT`) `/_security/profile/{uid}/_disable`
- [Enable a user profile](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-enable-user-profile): `POST` (also `PUT`) `/_security/profile/{uid}/_enable`
- [Clear the user cache](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-clear-cached-realms): `POST` `/_security/realm/{realms}/_clear_cache`
- [Bulk create or update roles](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-bulk-put-role): `POST` `/_security/role`
- [Bulk delete roles](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-bulk-delete-role): `DELETE` `/_security/role`
- [Get roles](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-get-role): `GET` `/_security/role/{name}`, `GET` `/_security/role`
- [Create or update roles](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-put-role): `POST` (also `PUT`) `/_security/role/{name}`
- [Delete roles](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-delete-role): `DELETE` `/_security/role/{name}`
- [Clear the roles cache](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-clear-cached-roles): `POST` `/_security/role/{name}/_clear_cache`
- [Get role mappings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-get-role-mapping): `GET` `/_security/role_mapping/{name}`, `GET` `/_security/role_mapping`
- [Create or update role mappings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-put-role-mapping): `POST` (also `PUT`) `/_security/role_mapping/{name}`
- [Delete role mappings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-delete-role-mapping): `DELETE` `/_security/role_mapping/{name}`
- [Authenticate SAML](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-saml-authenticate): `POST` `/_security/saml/authenticate`
- [Logout of SAML completely](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-saml-complete-logout): `POST` `/_security/saml/complete_logout`
- [Invalidate SAML](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-saml-invalidate): `POST` `/_security/saml/invalidate`
- [Logout of SAML](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-saml-logout): `POST` `/_security/saml/logout`
- [Create SAML service provider metadata](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-saml-service-provider-metadata): `GET` `/_security/saml/metadata/{realm_name}`
- [Prepare SAML authentication](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-saml-prepare-authentication): `POST` `/_security/saml/prepare`
- [Get service accounts](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-get-service-accounts): `GET` `/_security/service/{namespace}/{service}`, `GET` `/_security/service/{namespace}`, `GET` `/_security/service`
- [Create user-managed service accounts](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-put-user-managed-service-account): `PUT` `/_security/service/{namespace}/{service}`
- [Delete user-managed service accounts](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-delete-user-managed-service-account): `DELETE` `/_security/service/{namespace}/{service}`
- [Get service account credentials](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-get-service-credentials): `GET` `/_security/service/{namespace}/{service}/credential`
- [Create a service account token](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-create-service-token): `POST` (also `PUT`) `/_security/service/{namespace}/{service}/credential/token/{name}`, `POST` `/_security/service/{namespace}/{service}/credential/token`
- [Delete service account tokens](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-delete-service-token): `DELETE` `/_security/service/{namespace}/{service}/credential/token/{name}`
- [Clear service account token caches](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-clear-cached-service-tokens): `POST` `/_security/service/{namespace}/{service}/credential/token/{name}/_clear_cache`
- [Get security index settings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-get-settings): `GET` `/_security/settings`
- [Update security index settings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-update-settings): `PUT` `/_security/settings`
- [Get security stats](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-get-stats): `GET` `/_security/stats`
- [Get user privileges](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-get-user-privileges): `GET` `/_security/user/_privileges`
- [Get users](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-get-user): `GET` `/_security/user/{username}`, `GET` `/_security/user`
- [Create or update users](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-put-user): `POST` (also `PUT`) `/_security/user/{username}`
- [Delete users](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-delete-user): `DELETE` `/_security/user/{username}`
- [Disable users](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-disable-user): `POST` (also `PUT`) `/_security/user/{username}/_disable`
- [Enable users](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-enable-user): `POST` (also `PUT`) `/_security/user/{username}/_enable`
- [Change passwords](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-change-password): `POST` (also `PUT`) `/_security/user/{username}/_password`, `POST` (also `PUT`) `/_security/user/_password`
- [Check user privileges](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-security-has-privileges): `POST` (also `GET`) `/_security/user/{user}/_has_privileges`, `POST` (also `GET`) `/_security/user/_has_privileges`
- [Get SSL certificates](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-ssl-certificates): `GET` `/_ssl/certificates`
### [Snapshot and restore](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-snapshot)

- [Get snapshot repository information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-snapshot-get-repository): `GET` `/_snapshot/{repository}`, `GET` `/_snapshot`
- [Create or update a snapshot repository](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-snapshot-create-repository): `POST` (also `PUT`) `/_snapshot/{repository}`
- [Delete snapshot repositories](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-snapshot-delete-repository): `DELETE` `/_snapshot/{repository}`
- [Analyze a snapshot repository](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-snapshot-repository-analyze): `POST` `/_snapshot/{repository}/_analyze`
- [Clean up the snapshot repository](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-snapshot-cleanup-repository): `POST` `/_snapshot/{repository}/_cleanup`
- [Verify a snapshot repository](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-snapshot-verify-repository): `POST` `/_snapshot/{repository}/_verify`
- [Verify the repository integrity](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-snapshot-repository-verify-integrity): `POST` `/_snapshot/{repository}/_verify_integrity`
- [Get snapshot information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-snapshot-get): `GET` `/_snapshot/{repository}/{snapshot}`
- [Create a snapshot](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-snapshot-create): `POST` (also `PUT`) `/_snapshot/{repository}/{snapshot}`
- [Delete snapshots](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-snapshot-delete): `DELETE` `/_snapshot/{repository}/{snapshot}`
- [Clone a snapshot](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-snapshot-clone): `PUT` `/_snapshot/{repository}/{snapshot}/_clone/{target_snapshot}`
- [Restore a snapshot](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-snapshot-restore): `POST` `/_snapshot/{repository}/{snapshot}/_restore`
- [Get the snapshot status](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-snapshot-status): `GET` `/_snapshot/{repository}/{snapshot}/_status`, `GET` `/_snapshot/{repository}/_status`, `GET` `/_snapshot/_status`
### [Snapshot lifecycle management](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-slm)

- [Run a retention policy](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-slm-execute-retention): `POST` `/_slm/_execute_retention`
- [Get policy information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-slm-get-lifecycle): `GET` `/_slm/policy/{policy_id}`, `GET` `/_slm/policy`
- [Create or update a policy](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-slm-put-lifecycle): `PUT` `/_slm/policy/{policy_id}`
- [Delete a policy](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-slm-delete-lifecycle): `DELETE` `/_slm/policy/{policy_id}`
- [Run a policy](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-slm-execute-lifecycle): `PUT` `/_slm/policy/{policy_id}/_execute`
- [Start snapshot lifecycle management](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-slm-start): `POST` `/_slm/start`
- [Get snapshot lifecycle management statistics](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-slm-get-stats): `GET` `/_slm/stats`
- [Get the snapshot lifecycle management status](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-slm-get-status): `GET` `/_slm/status`
- [Stop snapshot lifecycle management](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-slm-stop): `POST` `/_slm/stop`
### [SQL](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-sql)

- [Get SQL search results](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-sql-query): `POST` (also `GET`) `/_sql`
- [Delete an async SQL search](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-sql-delete-async): `DELETE` `/_sql/async/delete/{id}`
- [Get the async SQL search status](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-sql-get-async-status): `GET` `/_sql/async/status/{id}`
- [Get async SQL search results](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-sql-get-async): `GET` `/_sql/async/{id}`
- [Clear an SQL search cursor](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-sql-clear-cursor): `POST` `/_sql/close`
- [Translate SQL into Elasticsearch queries](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-sql-translate): `POST` (also `GET`) `/_sql/translate`
### [Streams](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-streams)

- [Get the status of streams](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-streams-status): `GET` `/_streams/status`
- [Disable a named stream](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-streams-logs-disable): `POST` `/_streams/{name}/_disable`
- [Enable a named stream](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-streams-logs-enable): `POST` `/_streams/{name}/_enable`
### [Synonyms](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-synonyms)

- [Get all synonym sets](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-synonyms-get-synonyms-sets): `GET` `/_synonyms`
- [Get a synonym set](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-synonyms-get-synonym): `GET` `/_synonyms/{id}`
- [Create or update a synonym set](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-synonyms-put-synonym): `PUT` `/_synonyms/{id}`
- [Delete a synonym set](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-synonyms-delete-synonym): `DELETE` `/_synonyms/{id}`
- [Get a synonym rule](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-synonyms-get-synonym-rule): `GET` `/_synonyms/{set_id}/{rule_id}`
- [Create or update a synonym rule](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-synonyms-put-synonym-rule): `PUT` `/_synonyms/{set_id}/{rule_id}`
- [Delete a synonym rule](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-synonyms-delete-synonym-rule): `DELETE` `/_synonyms/{set_id}/{rule_id}`
### [Task management](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-tasks)

- [Get all tasks](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-tasks-list): `GET` `/_tasks`
- [Get task information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-tasks-get): `GET` `/_tasks/{task_id}`
- [Cancel a task](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-tasks-cancel): `POST` `/_tasks/{task_id}/_cancel`, `POST` `/_tasks/_cancel`
### [Text structure](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-text_structure)

- [Find the structure of a text field](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-text-structure-find-field-structure): `GET` `/_text_structure/find_field_structure`
- [Find the structure of text messages](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-text-structure-find-message-structure): `POST` (also `GET`) `/_text_structure/find_message_structure`
- [Find the structure of a text file](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-text-structure-find-structure): `POST` `/_text_structure/find_structure`
- [Test a Grok pattern](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-text-structure-test-grok-pattern): `POST` (also `GET`) `/_text_structure/test_grok_pattern`
### [Transform](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-transform)

- [Get node stats](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-transform-get-node-stats): `GET` `/_transform/_node_stats`
- [Upgrade all transforms](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-transform-upgrade-transforms): `POST` `/_transform/_upgrade`
- [Set upgrade_mode for transform indices](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-transform-set-upgrade-mode): `POST` `/_transform/set_upgrade_mode`
- [Get transforms](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-transform-get-transform): `GET` `/_transform/{transform_id}`, `GET` `/_transform`
- [Create a transform](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-transform-put-transform): `PUT` `/_transform/{transform_id}`
- [Delete a transform](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-transform-delete-transform): `DELETE` `/_transform/{transform_id}`
- [Preview a transform](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-transform-preview-transform): `POST` (also `GET`) `/_transform/{transform_id}/_preview`, `POST` (also `GET`) `/_transform/_preview`
- [Reset a transform](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-transform-reset-transform): `POST` `/_transform/{transform_id}/_reset`
- [Schedule a transform to start now](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-transform-schedule-now-transform): `POST` `/_transform/{transform_id}/_schedule_now`
- [Start a transform](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-transform-start-transform): `POST` `/_transform/{transform_id}/_start`
- [Get transform stats](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-transform-get-transform-stats): `GET` `/_transform/{transform_id}/_stats`
- [Stop transforms](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-transform-stop-transform): `POST` `/_transform/{transform_id}/_stop`
- [Update a transform](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-transform-update-transform): `POST` `/_transform/{transform_id}/_update`
### [Usage](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-xpack)

- [Get information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-xpack-info): `GET` `/_xpack`
- [Get usage information](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-xpack-usage): `GET` `/_xpack/usage`
### [Watcher](https://www.elastic.co/docs/api/elasticsearch/v9/group/endpoint-watcher)

- [Query watches](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-watcher-query-watches): `POST` (also `GET`) `/_watcher/_query/watches`
- [Start the watch service](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-watcher-start): `POST` `/_watcher/_start`
- [Stop the watch service](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-watcher-stop): `POST` `/_watcher/_stop`
- [Get Watcher index settings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-watcher-get-settings): `GET` `/_watcher/settings`
- [Update Watcher index settings](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-watcher-update-settings): `PUT` `/_watcher/settings`
- [Get Watcher statistics](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-watcher-stats): `GET` `/_watcher/stats/{metric}`, `GET` `/_watcher/stats`
- [Get a watch](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-watcher-get-watch): `GET` `/_watcher/watch/{id}`
- [Create or update a watch](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-watcher-put-watch): `POST` (also `PUT`) `/_watcher/watch/{id}`
- [Delete a watch](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-watcher-delete-watch): `DELETE` `/_watcher/watch/{id}`
- [Run a watch](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-watcher-execute-watch): `POST` (also `PUT`) `/_watcher/watch/{id}/_execute`, `POST` (also `PUT`) `/_watcher/watch/_execute`
- [Acknowledge a watch](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-watcher-ack-watch): `POST` (also `PUT`) `/_watcher/watch/{watch_id}/_ack/{action_id}`, `POST` (also `PUT`) `/_watcher/watch/{watch_id}/_ack`
- [Activate a watch](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-watcher-activate-watch): `POST` (also `PUT`) `/_watcher/watch/{watch_id}/_activate`
- [Deactivate a watch](https://www.elastic.co/docs/api/elasticsearch/v9/operation/operation-watcher-deactivate-watch): `POST` (also `PUT`) `/_watcher/watch/{watch_id}/_deactivate`
### Types

### Query DSL

- [Query](https://www.elastic.co/docs/api/elasticsearch/v9/types/_types-query_dsl-querycontainer) (`_types.query_dsl.QueryContainer`)
### Aggregations

- [Aggregation](https://www.elastic.co/docs/api/elasticsearch/v9/types/_types-aggregations-aggregationcontainer) (`_types.aggregations.AggregationContainer`)
- [Aggregation result](https://www.elastic.co/docs/api/elasticsearch/v9/types/_types-aggregations-aggregate) (`_types.aggregations.Aggregate`)
### Ingest

- [Processor](https://www.elastic.co/docs/api/elasticsearch/v9/types/ingest-_types-processorcontainer) (`ingest._types.ProcessorContainer`)
