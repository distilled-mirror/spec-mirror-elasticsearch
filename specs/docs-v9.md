# Elasticsearch API

OpenAPI file: https://www.elastic.co/docs/api/doc/elasticsearch/v9.json

## Description

Last update on Aug 20, 2026.
Elasticsearch provides REST APIs that are used by the UI components and can be called directly to configure and access Elasticsearch features.
## Documentation source and versions
This documentation is derived from the `9.5` branch of the [elasticsearch-specification](https://github.com/elastic/elasticsearch-specification) repository. It is provided under license [Attribution-NonCommercial-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nc-nd/4.0/).


## Servers

- http://api.example.com: http://api.example.com ()


## Topics

### [Authentications](https://www.elastic.co/docs/api/doc/elasticsearch/v9/authentication.md)


## Endpoints

### [Behavioral analytics](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-analytics.md)

- [Get behavioral analytics collections
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-search-application-get-behavioral-analytics.md)

- [Create a behavioral analytics collection](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-search-application-put-behavioral-analytics.md)

- [Delete a behavioral analytics collection](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-search-application-delete-behavioral-analytics.md)

- [Create a behavioral analytics collection event](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-search-application-post-behavioral-analytics-event.md)


### [Compact and aligned text (CAT)](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-cat.md)

- [Get aliases
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-aliases.md)

- [Get shard allocation information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-allocation.md)

- [Get circuit breakers statistics
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-circuit-breaker.md)

- [Get component templates
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-component-templates.md)

- [Get a document count
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-count.md)

- [Get field data cache information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-fielddata.md)

- [Get the cluster health status](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-health.md)

- [Get CAT help](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-help.md)

- [Get index information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-indices.md)

- [Get master node information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-master.md)

- [Get data frame analytics jobs
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-ml-data-frame-analytics.md)

- [Get datafeeds
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-ml-datafeeds.md)

- [Get anomaly detection jobs
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-ml-jobs.md)

- [Get trained models
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-ml-trained-models.md)

- [Get node attribute information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-nodeattrs.md)

- [Get node information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-nodes.md)

- [Get pending task information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-pending-tasks.md)

- [Get plugin information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-plugins.md)

- [Get shard recovery information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-recovery.md)

- [Get snapshot repository information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-repositories.md)

- [Get segment information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-segments.md)

- [Get shard information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-shards.md)

- [Get snapshot information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-snapshots.md)

- [Get task information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-tasks.md)

- [Get index template information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-templates.md)

- [Get thread pool statistics
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-thread-pool.md)

- [Get transform information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cat-transforms.md)


### [Cluster](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-cluster.md)

- [Explain the shard allocations
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cluster-allocation-explain.md)

- [Update voting configuration exclusions](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cluster-post-voting-config-exclusions.md)

- [Clear cluster voting config exclusions](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cluster-delete-voting-config-exclusions.md)

- [Get cluster-wide settings](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cluster-get-settings.md)

- [Update the cluster settings](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cluster-put-settings.md)

- [Get the cluster health status
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cluster-health.md)

- [Get cluster info](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cluster-info.md)

- [Get the pending cluster tasks](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cluster-pending-tasks.md)

- [Get remote cluster information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cluster-remote-info.md)

- [Reroute the cluster](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cluster-reroute.md)

- [Get the cluster state
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cluster-state.md)

- [Get cluster statistics
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cluster-stats.md)

- [Ping the cluster](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ping.md)

- [Clear the archived repositories metering](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-nodes-clear-repositories-metering-archive.md)

- [Get cluster repositories metering](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-nodes-get-repositories-metering-info.md)

- [Get the hot threads for nodes
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-nodes-hot-threads.md)

- [Get node information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-nodes-info.md)

- [Reload the keystore on nodes in the cluster
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-nodes-reload-secure-settings.md)

- [Get node statistics
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-nodes-stats.md)

- [Get feature usage information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-nodes-usage.md)


### [Cluster - Health](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-health_report.md)

- [Get the cluster health
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-health-report.md)


### [Connector](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-connector.md)

- [Check in a connector](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-check-in.md)

- [Get a connector](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-get.md)

- [Create or update a connector
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-put.md)

- [Delete a connector](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-delete.md)

- [Get all connectors](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-list.md)

- [Create a connector](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-post.md)

- [Cancel a connector sync job](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-sync-job-cancel.md)

- [Check in a connector sync job](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-sync-job-check-in.md)

- [Claim a connector sync job](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-sync-job-claim.md)

- [Get a connector sync job](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-sync-job-get.md)

- [Delete a connector sync job](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-sync-job-delete.md)

- [Set a connector sync job error](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-sync-job-error.md)

- [Get all connector sync jobs](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-sync-job-list.md)

- [Create a connector sync job](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-sync-job-post.md)

- [Set the connector sync job stats](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-sync-job-update-stats.md)

- [Activate the connector draft filter](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-update-active-filtering.md)

- [Update the connector API key ID](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-update-api-key-id.md)

- [Update the connector configuration](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-update-configuration.md)

- [Update the connector error field](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-update-error.md)

- [Update the connector features](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-update-features.md)

- [Update the connector filtering](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-update-filtering.md)

- [Update the connector draft filtering validation](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-update-filtering-validation.md)

- [Update the connector index name](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-update-index-name.md)

- [Update the connector name and description](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-update-name.md)

- [Update the connector is_native flag](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-update-native.md)

- [Update the connector pipeline](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-update-pipeline.md)

- [Update the connector scheduling](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-update-scheduling.md)

- [Update the connector service type](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-update-service-type.md)

- [Update the connector status](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-connector-update-status.md)


### [Cross-cluster replication](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-ccr.md)

- [Get auto-follow patterns
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ccr-get-auto-follow-pattern.md)

- [Create or update auto-follow patterns](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ccr-put-auto-follow-pattern.md)

- [Delete auto-follow patterns](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ccr-delete-auto-follow-pattern.md)

- [Create a follower](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ccr-follow.md)

- [Get follower information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ccr-follow-info.md)

- [Get follower stats](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ccr-follow-stats.md)

- [Forget a follower](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ccr-forget-follower.md)

- [Pause an auto-follow pattern](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ccr-pause-auto-follow-pattern.md)

- [Pause a follower](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ccr-pause-follow.md)

- [Resume an auto-follow pattern](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ccr-resume-auto-follow-pattern.md)

- [Resume a follower](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ccr-resume-follow.md)

- [Get cross-cluster replication stats](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ccr-stats.md)

- [Unfollow an index](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ccr-unfollow.md)


### [Data stream](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-data-stream.md)

- [Get data streams
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-get-data-stream.md)

- [Create a data stream](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-create-data-stream.md)

- [Delete data streams](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-delete-data-stream.md)

- [Get data stream stats
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-data-streams-stats.md)

- [Get data stream lifecycles](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-get-data-lifecycle.md)

- [Update data stream lifecycles](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-put-data-lifecycle.md)

- [Get data stream options](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-get-data-stream-options.md)

- [Update data stream options](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-put-data-stream-options.md)

- [Delete data stream options](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-delete-data-stream-options.md)

- [Downsample an index](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-downsample.md)

- [Get the status for a data stream lifecycle](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-explain-data-lifecycle.md)

- [Get data stream lifecycle stats](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-get-data-lifecycle-stats.md)

- [Get data stream mappings](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-get-data-stream-mappings.md)

- [Update data stream mappings](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-put-data-stream-mappings.md)

- [Get data stream settings](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-get-data-stream-settings.md)

- [Update data stream settings](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-put-data-stream-settings.md)

- [Convert an index alias to a data stream](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-migrate-to-data-stream.md)

- [Update data streams](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-modify-data-stream.md)

- [Promote a data stream](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-promote-data-stream.md)


### [Document](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-document.md)

- [Bulk index or delete documents
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-bulk.md)

- [Create a new document in the index
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-create.md)

- [Get a document by its ID](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-get.md)

- [Create or update a document in an index
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-index.md)

- [Delete a document](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-delete.md)

- [Check a document](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-exists.md)

- [Delete documents](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-delete-by-query.md)

- [Throttle a delete by query operation](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-delete-by-query-rethrottle.md)

- [Get a document's source](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-get-source.md)

- [Check for a document source](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-exists-source.md)

- [Reindex documents](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-reindex.md)

- [Get multiple documents
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-mget.md)

- [Get multiple term vectors
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-mtermvectors.md)

- [Throttle a reindex operation](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-reindex-rethrottle.md)

- [Get term vector information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-termvectors.md)

- [Update a document](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-update.md)

- [Update documents](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-update-by-query.md)

- [Throttle an update by query operation](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-update-by-query-rethrottle.md)


### [Enrich](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-enrich.md)

- [Get an enrich policy
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-enrich-get-policy.md)

- [Create an enrich policy](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-enrich-put-policy.md)

- [Delete an enrich policy](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-enrich-delete-policy.md)

- [Run an enrich policy](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-enrich-execute-policy.md)

- [Get enrich stats](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-enrich-stats.md)


### [EQL](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-eql.md)

- [Get async EQL search results](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-eql-get.md)

- [Delete an async EQL search](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-eql-delete.md)

- [Get the async EQL status](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-eql-get-status.md)

- [Get EQL search results
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-eql-search.md)


### [ES|QL](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-esql.md)

- [Run an async ES|QL query](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-esql-async-query.md)

- [Get async ES|QL query results](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-esql-async-query-get.md)

- [Delete an async ES|QL query](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-esql-async-query-delete.md)

- [Stop async ES|QL query](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-esql-async-query-stop.md)

- [Get ES|QL data sources
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-esql-get-data-source.md)

- [Create or update an ES|QL data source](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-esql-put-data-source.md)

- [Delete ES|QL data sources](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-esql-delete-data-source.md)

- [Get ES|QL datasets
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-esql-get-dataset.md)

- [Create or update an ES|QL dataset](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-esql-put-dataset.md)

- [Delete ES|QL datasets](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-esql-delete-dataset.md)

- [Get an ES|QL view
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-esql-get-view.md)

- [Create or update an ES|QL view](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-esql-put-view.md)

- [Delete an ES|QL view](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-esql-delete-view.md)

- [Get a specific running ES|QL query information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-esql-get-query.md)

- [Get running ES|QL queries information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-esql-list-queries.md)

- [Run an ES|QL query](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-esql-query.md)


### [Features](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-features.md)

- [Get the features](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-features-get-features.md)

- [Reset the features](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-features-reset-features.md)


### [Fleet](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-fleet.md)

- [Get global checkpoints](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-fleet-global-checkpoints.md)

- [Run multiple Fleet searches
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-fleet-msearch.md)

- [Run a Fleet search
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-fleet-search.md)


### [Graph explore](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-graph.md)

- [Explore graph analytics
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-graph-explore.md)


### [Index](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-indices.md)

- [Get component templates
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cluster-get-component-template.md)

- [Create or update a component template
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cluster-put-component-template.md)

- [Delete component templates](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cluster-delete-component-template.md)

- [Check component templates](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cluster-exists-component-template.md)

- [Import a dangling index](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-dangling-indices-import-dangling-index.md)

- [Delete a dangling index](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-dangling-indices-delete-dangling-index.md)

- [Get the dangling indices](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-dangling-indices-list-dangling-indices.md)

- [Add an index block](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-add-block.md)

- [Remove an index block](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-remove-block.md)

- [Get tokens from text analysis
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-analyze.md)

- [Clear the cache
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-clear-cache.md)

- [Clone an index
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-clone.md)

- [Close an index](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-close.md)

- [Get index information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-get.md)

- [Create an index](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-create.md)

- [Delete indices](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-delete.md)

- [Check indices](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-exists.md)

- [Create or update an alias
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-put-alias.md)

- [Delete an alias
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-delete-alias.md)

- [Delete data stream lifecycles](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-delete-data-lifecycle.md)

- [Get index templates
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-get-index-template.md)

- [Create or update an index template
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-put-index-template.md)

- [Delete an index template](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-delete-index-template.md)

- [Check index templates](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-exists-index-template.md)

- [Get legacy index templates
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-get-template.md)

- [Create or update a legacy index template
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-put-template.md)

- [Delete a legacy index template](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-delete-template.md)

- [Check existence of index templates](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-exists-template.md)

- [Analyze the index disk usage](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-disk-usage.md)

- [Get aliases
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-get-alias.md)

- [Check aliases
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-exists-alias.md)

- [Get field usage stats](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-field-usage-stats.md)

- [Flush data streams or indices
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-flush.md)

- [Force a merge
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-forcemerge.md)

- [Get mapping definitions
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-get-field-mapping.md)

- [Get mapping definitions
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-get-mapping.md)

- [Update field mappings
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-put-mapping.md)

- [Get index settings
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-get-settings.md)

- [Open a closed index](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-open.md)

- [Update index settings
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-put-settings.md)

- [Get index recovery information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-recovery.md)

- [Refresh an index
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-refresh.md)

- [Reload search analyzers
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-reload-search-analyzers.md)

- [Resolve the cluster
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-resolve-cluster.md)

- [Resolve indices
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-resolve-index.md)

- [Roll over to a new index
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-rollover.md)

- [Get index segments
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-segments.md)

- [Get index shard stores
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-shard-stores.md)

- [Shrink an index
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-shrink.md)

- [Simulate an index](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-simulate-index-template.md)

- [Simulate an index template
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-simulate-template.md)

- [Split an index
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-split.md)

- [Get index statistics
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-stats.md)

- [Create or update an alias](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-update-aliases.md)

- [Validate a query
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-validate-query.md)


### [Index lifecycle management](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-ilm.md)

- [Get lifecycle policies
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ilm-get-lifecycle.md)

- [Create or update a lifecycle policy](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ilm-put-lifecycle.md)

- [Delete a lifecycle policy](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ilm-delete-lifecycle.md)

- [Explain the lifecycle state](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ilm-explain-lifecycle.md)

- [Get the ILM status](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ilm-get-status.md)

- [Migrate to data tiers routing](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ilm-migrate-to-data-tiers.md)

- [Move to a lifecycle step](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ilm-move-to-step.md)

- [Remove policies from an index](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ilm-remove-policy.md)

- [Retry a policy](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ilm-retry.md)

- [Start the ILM plugin](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ilm-start.md)

- [Stop the ILM plugin](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ilm-stop.md)


### [Inference](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-inference.md)

- [Perform chat completion inference on the service](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-chat-completion-unified.md)

- [Perform completion inference on the service](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-completion.md)

- [Get an inference endpoint
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-get.md)

- [Create an inference endpoint
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put.md)

- [Perform inference on the service
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-inference.md)

- [Delete an inference endpoint
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-delete.md)

- [Get the inference region policy](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-get-region-policy.md)

- [Create or update the inference region policy](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-region-policy.md)

- [Delete the inference region policy](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-delete-region-policy.md)

- [Perform dense embedding inference on the service](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-embedding.md)

- [Create a AI21 inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-ai21.md)

- [Create an AlibabaCloud AI Search inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-alibabacloud.md)

- [Create an Amazon Bedrock inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-amazonbedrock.md)

- [Create an Amazon SageMaker inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-amazonsagemaker.md)

- [Create an Anthropic inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-anthropic.md)

- [Create an Azure AI studio inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-azureaistudio.md)

- [Create an Azure OpenAI inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-azureopenai.md)

- [Create a Cohere inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-cohere.md)

- [Create an Contextual AI inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-contextualai.md)

- [Create a custom inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-custom.md)

- [Create a DeepSeek inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-deepseek.md)

- [Create an Elasticsearch inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-elasticsearch.md)

- [Create an ELSER inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-elser.md)

- [Create a Fireworks AI inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-fireworksai.md)

- [Create an Google AI Studio inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-googleaistudio.md)

- [Create a Google Vertex AI inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-googlevertexai.md)

- [Create a Groq inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-groq.md)

- [Create a Hugging Face inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-hugging-face.md)

- [Create an JinaAI inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-jinaai.md)

- [Create a Llama inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-llama.md)

- [Create a Mistral inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-mistral.md)

- [Create an Nvidia inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-nvidia.md)

- [Create an OpenAI inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-openai.md)

- [Create an OpenShift AI inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-openshift-ai.md)

- [Create a VoyageAI inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-voyageai.md)

- [Create a Watsonx inference endpoint](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-put-watsonx.md)

- [Perform reranking inference on the service](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-rerank.md)

- [Perform sparse embedding inference on the service](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-sparse-embedding.md)

- [Perform streaming completion inference on the service](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-stream-completion.md)

- [Perform text embedding inference on the service](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-text-embedding.md)

- [Update an inference endpoint
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-inference-update.md)


### [Info](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-info.md)

- [Get cluster info](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-info.md)


### [Ingest](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-ingest.md)

- [Get GeoIP database configurations
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ingest-get-geoip-database.md)

- [Create or update a GeoIP database configuration](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ingest-put-geoip-database.md)

- [Delete GeoIP database configurations](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ingest-delete-geoip-database.md)

- [Get IP geolocation database configurations
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ingest-get-ip-location-database.md)

- [Create or update an IP geolocation database configuration](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ingest-put-ip-location-database.md)

- [Delete IP geolocation database configurations](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ingest-delete-ip-location-database.md)

- [Get pipelines
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ingest-get-pipeline.md)

- [Create or update a pipeline](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ingest-put-pipeline.md)

- [Delete pipelines](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ingest-delete-pipeline.md)

- [Get GeoIP statistics](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ingest-geo-ip-stats.md)

- [Run a grok processor](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ingest-processor-grok.md)

- [Simulate a pipeline
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ingest-simulate.md)

- [Simulate data ingestion
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-simulate-ingest.md)


### [Licensing](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-license.md)

- [Get license information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-license-get.md)

- [Update the license
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-license-post.md)

- [Delete the license](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-license-delete.md)

- [Get the basic license status](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-license-get-basic-status.md)

- [Get the trial status](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-license-get-trial-status.md)

- [Start a basic license](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-license-post-start-basic.md)

- [Start a trial](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-license-post-start-trial.md)


### [Logstash](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-logstash.md)

- [Get Logstash pipelines
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-logstash-get-pipeline.md)

- [Create or update a Logstash pipeline](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-logstash-put-pipeline.md)

- [Delete a Logstash pipeline](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-logstash-delete-pipeline.md)


### [Machine learning](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-ml.md)

- [Get machine learning memory usage info
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-memory-stats.md)

- [Get machine learning information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-info.md)

- [Set upgrade_mode for ML indices](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-set-upgrade-mode.md)


### [Machine learning anomaly detection](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-ml-anomaly.md)

- [Close anomaly detection jobs](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-close-job.md)

- [Create a calendar](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-put-calendar.md)

- [Get calendar configuration info
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-calendars.md)

- [Delete a calendar](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-delete-calendar.md)

- [Delete events from a calendar](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-delete-calendar-event.md)

- [Add anomaly detection job to calendar](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-put-calendar-job.md)

- [Delete anomaly jobs from a calendar](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-delete-calendar-job.md)

- [Get datafeeds configuration info
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-datafeeds.md)

- [Create a datafeed](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-put-datafeed.md)

- [Delete a datafeed](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-delete-datafeed.md)

- [Delete expired ML data
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-delete-expired-data.md)

- [Get filters
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-filters.md)

- [Create a filter](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-put-filter.md)

- [Delete a filter](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-delete-filter.md)

- [Delete forecasts from a job
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-delete-forecast.md)

- [Get anomaly detection jobs configuration info
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-jobs.md)

- [Create an anomaly detection job](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-put-job.md)

- [Delete an anomaly detection job](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-delete-job.md)

- [Get model snapshots info
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-model-snapshots.md)

- [Delete a model snapshot](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-delete-model-snapshot.md)

- [Estimate job model memory usage](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-estimate-model-memory.md)

- [Force buffered data to be processed](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-flush-job.md)

- [Predict future behavior of a time series](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-forecast.md)

- [Get anomaly detection job results for buckets
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-buckets.md)

- [Get info about events in calendars](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-calendar-events.md)

- [Add scheduled events to the calendar](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-post-calendar-events.md)

- [Get anomaly detection job results for categories
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-categories.md)

- [Get datafeed stats
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-datafeed-stats.md)

- [Get anomaly detection job results for influencers
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-influencers.md)

- [Get anomaly detection job stats
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-job-stats.md)

- [Get anomaly detection job model snapshot upgrade usage info](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-model-snapshot-upgrade-stats.md)

- [Get overall bucket results
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-overall-buckets.md)

- [Get anomaly records for an anomaly detection job
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-records.md)

- [Open anomaly detection jobs](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-open-job.md)

- [Send data to an anomaly detection job for analysis](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-post-data.md)

- [Preview a datafeed
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-preview-datafeed.md)

- [Reset an anomaly detection job](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-reset-job.md)

- [Revert to a snapshot](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-revert-model-snapshot.md)

- [Start datafeeds](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-start-datafeed.md)

- [Stop datafeeds](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-stop-datafeed.md)

- [Update a datafeed](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-update-datafeed.md)

- [Update a filter](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-update-filter.md)

- [Update an anomaly detection job](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-update-job.md)

- [Update a snapshot](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-update-model-snapshot.md)

- [Upgrade a snapshot](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-upgrade-job-snapshot.md)


### [Machine learning data frame analytics](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-ml-data-frame.md)

- [Get data frame analytics job configuration info
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-data-frame-analytics.md)

- [Create a data frame analytics job](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-put-data-frame-analytics.md)

- [Delete a data frame analytics job](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-delete-data-frame-analytics.md)

- [Evaluate data frame analytics](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-evaluate-data-frame.md)

- [Explain data frame analytics config
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-explain-data-frame-analytics.md)

- [Get data frame analytics job stats
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-data-frame-analytics-stats.md)

- [Preview features used by data frame analytics
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-preview-data-frame-analytics.md)

- [Start a data frame analytics job](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-start-data-frame-analytics.md)

- [Stop data frame analytics jobs](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-stop-data-frame-analytics.md)

- [Update a data frame analytics job](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-update-data-frame-analytics.md)


### [Machine learning trained model](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-ml-trained-model.md)

- [Clear trained model deployment cache](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-clear-trained-model-deployment-cache.md)

- [Get trained model configuration info
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-trained-models.md)

- [Create a trained model](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-put-trained-model.md)

- [Delete an unreferenced trained model](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-delete-trained-model.md)

- [Create or update a trained model alias](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-put-trained-model-alias.md)

- [Delete a trained model alias](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-delete-trained-model-alias.md)

- [Get trained models usage info
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-get-trained-models-stats.md)

- [Evaluate a trained model](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-infer-trained-model.md)

- [Create part of a trained model definition](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-put-trained-model-definition-part.md)

- [Create a trained model vocabulary](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-put-trained-model-vocabulary.md)

- [Start a trained model deployment](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-start-trained-model-deployment.md)

- [Stop a trained model deployment](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-stop-trained-model-deployment.md)

- [Update a trained model deployment](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ml-update-trained-model-deployment.md)


### [Migration](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-migration.md)

- [Cancel a migration reindex operation](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-cancel-migrate-reindex.md)

- [Create an index from a source index
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-create-from.md)

- [Get the migration reindexing status](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-get-migrate-reindex-status.md)

- [Reindex legacy backing indices](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-indices-migrate-reindex.md)

- [Get deprecation information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-migration-deprecations.md)

- [Get feature migration information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-migration-get-feature-upgrade-status.md)

- [Start the feature migration](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-migration-post-feature-upgrade.md)


### [Query rules](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-query_rules.md)

- [Get a query rule](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-query-rules-get-rule.md)

- [Create or update a query rule](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-query-rules-put-rule.md)

- [Delete a query rule](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-query-rules-delete-rule.md)

- [Get a query ruleset](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-query-rules-get-ruleset.md)

- [Create or update a query ruleset](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-query-rules-put-ruleset.md)

- [Delete a query ruleset](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-query-rules-delete-ruleset.md)

- [Get all query rulesets](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-query-rules-list-rulesets.md)

- [Test a query ruleset](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-query-rules-test.md)


### [Reindex](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-reindex.md)

- [Cancel an ongoing reindex task](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-cancel-reindex.md)

- [Get the status and progress of a specific reindex task](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-get-reindex.md)

- [Get information about all currently running reindex tasks](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-list-reindex.md)


### [Rollup](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-rollup.md)

- [Get rollup job information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-rollup-get-jobs.md)

- [Create a rollup job](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-rollup-put-job.md)

- [Delete a rollup job](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-rollup-delete-job.md)

- [Get the rollup job capabilities
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-rollup-get-rollup-caps.md)

- [Get the rollup index capabilities](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-rollup-get-rollup-index-caps.md)

- [Search rolled-up data
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-rollup-rollup-search.md)

- [Start rollup jobs](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-rollup-start-job.md)

- [Stop rollup jobs](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-rollup-stop-job.md)


### [Script](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-script.md)

- [Get a script or search template](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-get-script.md)

- [Delete a script or search template](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-delete-script.md)

- [Get script contexts](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-get-script-context.md)

- [Get script languages](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-get-script-languages.md)

- [Create or update a script or search template
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-put-script.md)

- [Run a script
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-scripts-painless-execute.md)


### [Search](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-search.md)

- [Get async search results](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-async-search-get.md)

- [Delete an async search](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-async-search-delete.md)

- [Get the async search status](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-async-search-status.md)

- [Run an async search
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-async-search-submit.md)

- [Run a scrolling search
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-scroll.md)

- [Clear a scrolling search
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-clear-scroll.md)

- [Close a point in time](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-close-point-in-time.md)

- [Count search results
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-count.md)

- [Explain a document match result
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-explain.md)

- [Get the field capabilities
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-field-caps.md)

- [Run multiple searches
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-msearch.md)

- [Run multiple templated searches
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-msearch-template.md)

- [Open a point in time](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-open-point-in-time.md)

- [Evaluate ranked search results
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-rank-eval.md)

- [Render a search template
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-render-search-template.md)

- [Run a search
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-search.md)

- [Search a vector tile
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-search-mvt.md)

- [Get the search shards
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-search-shards.md)

- [Run a search with a search template
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-search-template.md)

- [Get terms in an index
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-terms-enum.md)


### [Search application](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-search_application.md)

- [Get search application details](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-search-application-get.md)

- [Create or update a search application](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-search-application-put.md)

- [Delete a search application](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-search-application-delete.md)

- [Get search applications](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-search-application-list.md)

- [Render a search application query](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-search-application-render-query.md)

- [Run a search application search
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-search-application-search.md)


### [Searchable snapshots](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-searchable_snapshots.md)

- [Get cache statistics
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-searchable-snapshots-cache-stats.md)

- [Clear the cache
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-searchable-snapshots-clear-cache.md)

- [Mount a snapshot](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-searchable-snapshots-mount.md)

- [Get searchable snapshot statistics
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-searchable-snapshots-stats.md)


### [Security](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-security.md)

- [Reset the project encryption key](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-encryption-reset.md)

- [Activate a user profile](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-activate-user-profile.md)

- [Authenticate a user](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-authenticate.md)

- [Bulk create or update roles](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-bulk-put-role.md)

- [Bulk delete roles](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-bulk-delete-role.md)

- [Bulk update API keys](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-bulk-update-api-keys.md)

- [Change passwords
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-change-password.md)

- [Clear the API key cache](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-clear-api-key-cache.md)

- [Clear the privileges cache](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-clear-cached-privileges.md)

- [Clear the user cache](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-clear-cached-realms.md)

- [Clear the roles cache](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-clear-cached-roles.md)

- [Clear service account token caches](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-clear-cached-service-tokens.md)

- [Clone an API key
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-clone-api-key.md)

- [Get API key information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-get-api-key.md)

- [Create an API key
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-create-api-key.md)

- [Invalidate API keys](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-invalidate-api-key.md)

- [Create a cross-cluster API key](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-create-cross-cluster-api-key.md)

- [Create a service account token
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-create-service-token.md)

- [Delete service account tokens](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-delete-service-token.md)

- [Delegate PKI authentication](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-delegate-pki.md)

- [Get application privileges
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-get-privileges.md)

- [Delete application privileges](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-delete-privileges.md)

- [Get roles
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-get-role.md)

- [Create or update roles
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-put-role.md)

- [Delete roles](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-delete-role.md)

- [Get role mappings
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-get-role-mapping.md)

- [Create or update role mappings
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-put-role-mapping.md)

- [Delete role mappings](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-delete-role-mapping.md)

- [Get users
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-get-user.md)

- [Create or update users
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-put-user.md)

- [Delete users](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-delete-user.md)

- [Disable users
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-disable-user.md)

- [Disable a user profile
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-disable-user-profile.md)

- [Enable users
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-enable-user.md)

- [Enable a user profile
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-enable-user-profile.md)

- [Enroll Kibana](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-enroll-kibana.md)

- [Enroll a node](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-enroll-node.md)

- [Get builtin privileges](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-get-builtin-privileges.md)

- [Get service accounts
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-get-service-accounts.md)

- [Get service account credentials](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-get-service-credentials.md)

- [Get security index settings](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-get-settings.md)

- [Update security index settings](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-update-settings.md)

- [Get security stats](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-get-stats.md)

- [Get a token](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-get-token.md)

- [Invalidate a token](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-invalidate-token.md)

- [Get user privileges](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-get-user-privileges.md)

- [Get a user profile](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-get-user-profile.md)

- [Grant an API key](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-grant-api-key.md)

- [Check user privileges
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-has-privileges.md)

- [Check user profile privileges
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-has-privileges-user-profile.md)

- [Authenticate OpenID Connect](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-oidc-authenticate.md)

- [Logout of OpenID Connect](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-oidc-logout.md)

- [Prepare OpenID connect authentication](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-oidc-prepare-authentication.md)

- [Create or update application privileges
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-put-privileges.md)

- [Find API keys with a query
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-query-api-keys.md)

- [Find roles with a query
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-query-role.md)

- [Find users with a query
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-query-user.md)

- [Authenticate SAML](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-saml-authenticate.md)

- [Logout of SAML completely](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-saml-complete-logout.md)

- [Invalidate SAML](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-saml-invalidate.md)

- [Logout of SAML](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-saml-logout.md)

- [Prepare SAML authentication](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-saml-prepare-authentication.md)

- [Create SAML service provider metadata](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-saml-service-provider-metadata.md)

- [Suggest a user profile
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-suggest-user-profiles.md)

- [Update an API key](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-update-api-key.md)

- [Update a cross-cluster API key](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-update-cross-cluster-api-key.md)

- [Update user profile data
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-security-update-user-profile-data.md)

- [Get SSL certificates](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-ssl-certificates.md)


### [Snapshot and restore](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-snapshot.md)

- [Clean up the snapshot repository](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-snapshot-cleanup-repository.md)

- [Clone a snapshot](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-snapshot-clone.md)

- [Get snapshot information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-snapshot-get.md)

- [Create a snapshot
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-snapshot-create.md)

- [Delete snapshots](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-snapshot-delete.md)

- [Get snapshot repository information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-snapshot-get-repository.md)

- [Create or update a snapshot repository
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-snapshot-create-repository.md)

- [Delete snapshot repositories](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-snapshot-delete-repository.md)

- [Analyze a snapshot repository](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-snapshot-repository-analyze.md)

- [Verify the repository integrity](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-snapshot-repository-verify-integrity.md)

- [Restore a snapshot](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-snapshot-restore.md)

- [Get the snapshot status
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-snapshot-status.md)

- [Verify a snapshot repository](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-snapshot-verify-repository.md)


### [Snapshot lifecycle management](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-slm.md)

- [Get policy information
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-slm-get-lifecycle.md)

- [Create or update a policy](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-slm-put-lifecycle.md)

- [Delete a policy](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-slm-delete-lifecycle.md)

- [Run a policy](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-slm-execute-lifecycle.md)

- [Run a retention policy](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-slm-execute-retention.md)

- [Get snapshot lifecycle management statistics](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-slm-get-stats.md)

- [Get the snapshot lifecycle management status](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-slm-get-status.md)

- [Start snapshot lifecycle management](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-slm-start.md)

- [Stop snapshot lifecycle management](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-slm-stop.md)


### [SQL](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-sql.md)

- [Clear an SQL search cursor](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-sql-clear-cursor.md)

- [Delete an async SQL search](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-sql-delete-async.md)

- [Get async SQL search results](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-sql-get-async.md)

- [Get the async SQL search status](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-sql-get-async-status.md)

- [Get SQL search results
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-sql-query.md)

- [Translate SQL into Elasticsearch queries
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-sql-translate.md)


### [Streams](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-streams.md)

- [Disable a named stream](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-streams-logs-disable.md)

- [Enable a named stream](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-streams-logs-enable.md)

- [Get the status of streams](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-streams-status.md)


### [Synonyms](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-synonyms.md)

- [Get a synonym set](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-synonyms-get-synonym.md)

- [Create or update a synonym set](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-synonyms-put-synonym.md)

- [Delete a synonym set](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-synonyms-delete-synonym.md)

- [Get a synonym rule](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-synonyms-get-synonym-rule.md)

- [Create or update a synonym rule](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-synonyms-put-synonym-rule.md)

- [Delete a synonym rule](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-synonyms-delete-synonym-rule.md)

- [Get all synonym sets](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-synonyms-get-synonyms-sets.md)


### [Task management](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-tasks.md)

- [Cancel a task
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-tasks-cancel.md)

- [Get task information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-tasks-get.md)

- [Get all tasks](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-tasks-list.md)


### [Text structure](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-text_structure.md)

- [Find the structure of a text field](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-text-structure-find-field-structure.md)

- [Find the structure of text messages
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-text-structure-find-message-structure.md)

- [Find the structure of a text file](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-text-structure-find-structure.md)

- [Test a Grok pattern
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-text-structure-test-grok-pattern.md)


### [Transform](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-transform.md)

- [Get transforms
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-transform-get-transform.md)

- [Create a transform](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-transform-put-transform.md)

- [Delete a transform](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-transform-delete-transform.md)

- [Get node stats](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-transform-get-node-stats.md)

- [Get transform stats](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-transform-get-transform-stats.md)

- [Preview a transform
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-transform-preview-transform.md)

- [Reset a transform](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-transform-reset-transform.md)

- [Schedule a transform to start now](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-transform-schedule-now-transform.md)

- [Set upgrade_mode for transform indices](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-transform-set-upgrade-mode.md)

- [Start a transform](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-transform-start-transform.md)

- [Stop transforms](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-transform-stop-transform.md)

- [Update a transform](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-transform-update-transform.md)

- [Upgrade all transforms](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-transform-upgrade-transforms.md)


### [Usage](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-xpack.md)

- [Get information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-xpack-info.md)

- [Get usage information](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-xpack-usage.md)


### [Watcher](https://www.elastic.co/docs/api/doc/elasticsearch/v9/group/endpoint-watcher.md)

- [Acknowledge a watch
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-watcher-ack-watch.md)

- [Activate a watch
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-watcher-activate-watch.md)

- [Deactivate a watch
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-watcher-deactivate-watch.md)

- [Get a watch](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-watcher-get-watch.md)

- [Create or update a watch
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-watcher-put-watch.md)

- [Delete a watch](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-watcher-delete-watch.md)

- [Run a watch
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-watcher-execute-watch.md)

- [Get Watcher index settings](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-watcher-get-settings.md)

- [Update Watcher index settings](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-watcher-update-settings.md)

- [Query watches
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-watcher-query-watches.md)

- [Start the watch service](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-watcher-start.md)

- [Get Watcher statistics
](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-watcher-stats.md)

- [Stop the watch service](https://www.elastic.co/docs/api/doc/elasticsearch/v9/operation/operation-watcher-stop.md)




[Powered by Bump.sh](https://bump.sh)
