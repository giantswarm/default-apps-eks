# Values schema documentation

This page lists all available configuration options, based on the [configuration values schema](values.schema.json).

<!-- DOCS_START -->

### Apps

Properties within the `.apps` top-level object

| **Property** | **Description** | **More Details** |
| :----------- | :-------------- | :--------------- |
| `apps.capi-node-labeler` |**None**|**Type:** `object`<br/>|
| `apps.capi-node-labeler.appName` |**None**|**Type:** `string`<br/>|
| `apps.capi-node-labeler.catalog` |**None**|**Type:** `string`<br/>|
| `apps.capi-node-labeler.chartName` |**None**|**Type:** `string`<br/>|
| `apps.capi-node-labeler.clusterValues` |**None**|**Type:** `object`<br/>|
| `apps.capi-node-labeler.clusterValues.configMap` |**None**|**Type:** `boolean`<br/>|
| `apps.capi-node-labeler.clusterValues.secret` |**None**|**Type:** `boolean`<br/>|
| `apps.capi-node-labeler.enabled` |**None**|**Type:** `boolean`<br/>|
| `apps.capi-node-labeler.forceUpgrade` |**None**|**Type:** `boolean`<br/>|
| `apps.capi-node-labeler.namespace` |**None**|**Type:** `string`<br/>|
| `apps.capi-node-labeler.version` |**None**|**Type:** `string`<br/>|
| `apps.certExporter` |**None**|**Type:** `object`<br/>|
| `apps.certExporter.appName` |**None**|**Type:** `string`<br/>|
| `apps.certExporter.catalog` |**None**|**Type:** `string`<br/>|
| `apps.certExporter.chartName` |**None**|**Type:** `string`<br/>|
| `apps.certExporter.clusterValues` |**None**|**Type:** `object`<br/>|
| `apps.certExporter.clusterValues.configMap` |**None**|**Type:** `boolean`<br/>|
| `apps.certExporter.clusterValues.secret` |**None**|**Type:** `boolean`<br/>|
| `apps.certExporter.dependsOn` |**None**|**Type:** `string`<br/>|
| `apps.certExporter.enabled` |**None**|**Type:** `boolean`<br/>|
| `apps.certExporter.forceUpgrade` |**None**|**Type:** `boolean`<br/>|
| `apps.certExporter.namespace` |**None**|**Type:** `string`<br/>|
| `apps.certExporter.version` |**None**|**Type:** `string`<br/>|
| `apps.certManager` |**None**|**Type:** `object`<br/>|
| `apps.certManager.appName` |**None**|**Type:** `string`<br/>|
| `apps.certManager.catalog` |**None**|**Type:** `string`<br/>|
| `apps.certManager.chartName` |**None**|**Type:** `string`<br/>|
| `apps.certManager.clusterValues` |**None**|**Type:** `object`<br/>|
| `apps.certManager.clusterValues.configMap` |**None**|**Type:** `boolean`<br/>|
| `apps.certManager.clusterValues.secret` |**None**|**Type:** `boolean`<br/>|
| `apps.certManager.enabled` |**None**|**Type:** `boolean`<br/>|
| `apps.certManager.forceUpgrade` |**None**|**Type:** `boolean`<br/>|
| `apps.certManager.namespace` |**None**|**Type:** `string`<br/>|
| `apps.certManager.version` |**None**|**Type:** `string`<br/>|
| `apps.chartOperatorExtensions` |**None**|**Type:** `object`<br/>|
| `apps.chartOperatorExtensions.appName` |**None**|**Type:** `string`<br/>|
| `apps.chartOperatorExtensions.catalog` |**None**|**Type:** `string`<br/>|
| `apps.chartOperatorExtensions.chartName` |**None**|**Type:** `string`<br/>|
| `apps.chartOperatorExtensions.clusterValues` |**None**|**Type:** `object`<br/>|
| `apps.chartOperatorExtensions.clusterValues.configMap` |**None**|**Type:** `boolean`<br/>|
| `apps.chartOperatorExtensions.clusterValues.secret` |**None**|**Type:** `boolean`<br/>|
| `apps.chartOperatorExtensions.dependsOn` |**None**|**Type:** `string`<br/>|
| `apps.chartOperatorExtensions.enabled` |**None**|**Type:** `boolean`<br/>|
| `apps.chartOperatorExtensions.namespace` |**None**|**Type:** `string`<br/>|
| `apps.chartOperatorExtensions.version` |**None**|**Type:** `string`<br/>|
| `apps.externalDns` |**None**|**Type:** `object`<br/>|
| `apps.externalDns.appName` |**None**|**Type:** `string`<br/>|
| `apps.externalDns.catalog` |**None**|**Type:** `string`<br/>|
| `apps.externalDns.chartName` |**None**|**Type:** `string`<br/>|
| `apps.externalDns.clusterValues` |**None**|**Type:** `object`<br/>|
| `apps.externalDns.clusterValues.configMap` |**None**|**Type:** `boolean`<br/>|
| `apps.externalDns.clusterValues.secret` |**None**|**Type:** `boolean`<br/>|
| `apps.externalDns.enabled` |**None**|**Type:** `boolean`<br/>|
| `apps.externalDns.forceUpgrade` |**None**|**Type:** `boolean`<br/>|
| `apps.externalDns.namespace` |**None**|**Type:** `string`<br/>|
| `apps.externalDns.version` |**None**|**Type:** `string`<br/>|
| `apps.metricsServer` |**None**|**Type:** `object`<br/>|
| `apps.metricsServer.appName` |**None**|**Type:** `string`<br/>|
| `apps.metricsServer.catalog` |**None**|**Type:** `string`<br/>|
| `apps.metricsServer.chartName` |**None**|**Type:** `string`<br/>|
| `apps.metricsServer.clusterValues` |**None**|**Type:** `object`<br/>|
| `apps.metricsServer.clusterValues.configMap` |**None**|**Type:** `boolean`<br/>|
| `apps.metricsServer.clusterValues.secret` |**None**|**Type:** `boolean`<br/>|
| `apps.metricsServer.enabled` |**None**|**Type:** `boolean`<br/>|
| `apps.metricsServer.forceUpgrade` |**None**|**Type:** `boolean`<br/>|
| `apps.metricsServer.namespace` |**None**|**Type:** `string`<br/>|
| `apps.metricsServer.version` |**None**|**Type:** `string`<br/>|
| `apps.netExporter` |**None**|**Type:** `object`<br/>|
| `apps.netExporter.appName` |**None**|**Type:** `string`<br/>|
| `apps.netExporter.catalog` |**None**|**Type:** `string`<br/>|
| `apps.netExporter.chartName` |**None**|**Type:** `string`<br/>|
| `apps.netExporter.clusterValues` |**None**|**Type:** `object`<br/>|
| `apps.netExporter.clusterValues.configMap` |**None**|**Type:** `boolean`<br/>|
| `apps.netExporter.clusterValues.secret` |**None**|**Type:** `boolean`<br/>|
| `apps.netExporter.dependsOn` |**None**|**Type:** `string`<br/>|
| `apps.netExporter.enabled` |**None**|**Type:** `boolean`<br/>|
| `apps.netExporter.forceUpgrade` |**None**|**Type:** `boolean`<br/>|
| `apps.netExporter.namespace` |**None**|**Type:** `string`<br/>|
| `apps.netExporter.version` |**None**|**Type:** `string`<br/>|
| `apps.nodeExporter` |**None**|**Type:** `object`<br/>|
| `apps.nodeExporter.appName` |**None**|**Type:** `string`<br/>|
| `apps.nodeExporter.catalog` |**None**|**Type:** `string`<br/>|
| `apps.nodeExporter.chartName` |**None**|**Type:** `string`<br/>|
| `apps.nodeExporter.clusterValues` |**None**|**Type:** `object`<br/>|
| `apps.nodeExporter.clusterValues.configMap` |**None**|**Type:** `boolean`<br/>|
| `apps.nodeExporter.clusterValues.secret` |**None**|**Type:** `boolean`<br/>|
| `apps.nodeExporter.enabled` |**None**|**Type:** `boolean`<br/>|
| `apps.nodeExporter.forceUpgrade` |**None**|**Type:** `boolean`<br/>|
| `apps.nodeExporter.namespace` |**None**|**Type:** `string`<br/>|
| `apps.nodeExporter.version` |**None**|**Type:** `string`<br/>|
| `apps.observabilityBundle` |**None**|**Type:** `object`<br/>|
| `apps.observabilityBundle.appName` |**None**|**Type:** `string`<br/>|
| `apps.observabilityBundle.catalog` |**None**|**Type:** `string`<br/>|
| `apps.observabilityBundle.chartName` |**None**|**Type:** `string`<br/>|
| `apps.observabilityBundle.clusterValues` |**None**|**Type:** `object`<br/>|
| `apps.observabilityBundle.clusterValues.configMap` |**None**|**Type:** `boolean`<br/>|
| `apps.observabilityBundle.clusterValues.secret` |**None**|**Type:** `boolean`<br/>|
| `apps.observabilityBundle.enabled` |**None**|**Type:** `boolean`<br/>|
| `apps.observabilityBundle.forceUpgrade` |**None**|**Type:** `boolean`<br/>|
| `apps.observabilityBundle.inCluster` |**None**|**Type:** `boolean`<br/>|
| `apps.observabilityBundle.namespace` |**None**|**Type:** `string`<br/>|
| `apps.observabilityBundle.version` |**None**|**Type:** `string`<br/>|
| `apps.vpa` |**None**|**Type:** `object`<br/>|
| `apps.vpa.appName` |**None**|**Type:** `string`<br/>|
| `apps.vpa.catalog` |**None**|**Type:** `string`<br/>|
| `apps.vpa.chartName` |**None**|**Type:** `string`<br/>|
| `apps.vpa.clusterValues` |**None**|**Type:** `object`<br/>|
| `apps.vpa.clusterValues.configMap` |**None**|**Type:** `boolean`<br/>|
| `apps.vpa.clusterValues.secret` |**None**|**Type:** `boolean`<br/>|
| `apps.vpa.dependsOn` |**None**|**Type:** `string`<br/>|
| `apps.vpa.enabled` |**None**|**Type:** `boolean`<br/>|
| `apps.vpa.forceUpgrade` |**None**|**Type:** `boolean`<br/>|
| `apps.vpa.namespace` |**None**|**Type:** `string`<br/>|
| `apps.vpa.version` |**None**|**Type:** `string`<br/>|

### User Config

Properties within the `.userConfig` top-level object

| **Property** | **Description** | **More Details** |
| :----------- | :-------------- | :--------------- |
| `userConfig.certManager` |**None**|**Type:** `object`<br/>|
| `userConfig.certManager.configMap` |**None**|**Type:** `object`<br/>|
| `userConfig.certManager.configMap.values` |**None**|**Types:** `object, string`<br/>|
| `userConfig.externalDns` |**None**|**Type:** `object`<br/>|
| `userConfig.externalDns.configMap` |**None**|**Type:** `object`<br/>|
| `userConfig.externalDns.configMap.values` |**None**|**Types:** `object, string`<br/>|
| `userConfig.metricsServer` |**None**|**Type:** `object`<br/>|
| `userConfig.metricsServer.configMap` |**None**|**Type:** `object`<br/>|
| `userConfig.metricsServer.configMap.values` |**None**|**Types:** `object, string`<br/>|
| `userConfig.netExporter` |**None**|**Type:** `object`<br/>|
| `userConfig.netExporter.configMap` |**None**|**Type:** `object`<br/>|
| `userConfig.netExporter.configMap.values` |**None**|**Types:** `object, string`<br/>|

### AWS settings

Properties within the `.providerSpecific` top-level object

| **Property** | **Description** | **More Details** |
| :----------- | :-------------- | :--------------- |
| `providerSpecific.awsAccountId` | **AWS account ID** - AWS Account ID of the AWSClusterRoleIdentity IAM role, recommendation is to leave this value empty as it will be automatically calculated. This value is needed for tests.|**Type:** `string`<br/>**Value pattern:** `^[0-9]{0,12}$`<br/>**Default:** `""`|
| `providerSpecific.awsClusterRoleIdentityName` | **Cluster role identity name** - Name of an AWSClusterRoleIdentity object. Recommendation is to leave this value empty as it will be automatically calculated.|**Type:** `string`<br/>**Default:** `""`|

### Other

| **Property** | **Description** | **More Details** |
| :----------- | :-------------- | :--------------- |
| `awsAccoundID` |**None**|**Type:** `string`<br/>|
| `clusterName` |**None**|**Type:** `string`<br/>|
| `organization` |**None**|**Type:** `string`<br/>|

<!-- DOCS_END -->
