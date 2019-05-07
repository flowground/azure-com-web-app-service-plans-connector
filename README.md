# ![LOGO](logo.png) AppServicePlans API Client **flow**ground Connector

## Description

A generated **flow**ground connector for the AppServicePlans API Client API (version 2018-02-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/web-AppServicePlans/2018-02-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:21+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get all App Service plans for a subscription.

*Tags:* `AppServicePlans`

#### Input Parameters
* `detailed` - _optional_ - Specify <code>true</code> to return all App Service plan properties. The default is <code>false</code>, which returns a subset of the properties.
 Retrieval of all properties may increase the API latency.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get all App Service plans in a resource group.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Delete an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Creates or updates an App Service Plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Creates or updates an App Service Plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### List all capabilities of an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Delete a Hybrid Connection in use in an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `namespaceName` - _required_ - Name of the Service Bus namespace.
* `relayName` - _required_ - Name of the Service Bus relay.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Retrieve a Hybrid Connection in use in an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `namespaceName` - _required_ - Name of the Service Bus namespace.
* `relayName` - _required_ - Name of the Service Bus relay.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get the send key name and value of a Hybrid Connection.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `namespaceName` - _required_ - The name of the Service Bus namespace.
* `relayName` - _required_ - The name of the Service Bus relay.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get all apps that use a Hybrid Connection in an App Service Plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `namespaceName` - _required_ - Name of the Hybrid Connection namespace.
* `relayName` - _required_ - Name of the Hybrid Connection relay.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get the maximum number of Hybrid Connections allowed in an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Retrieve all Hybrid Connections in use in an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get metrics that can be queried for an App Service plan, and their definitions.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get metrics for an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `details` - _optional_ - Specify <code>true</code> to include instance details. The default is <code>false</code>.
* `$filter` - _optional_ - Return only usages/metrics specified in the filter. Filter conforms to odata syntax. Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq 2014-01-01T00:00:00Z and endTime eq 2014-12-31T23:59:59Z and timeGrain eq duration'[Hour|Minute|Day]'.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Restart all apps in an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `softRestart` - _optional_ - Specify <code>true</code> to perform a soft restart, applies the configuration settings and restarts the apps if necessary. The default is <code>false</code>, which always restarts and reprovisions the apps
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get all apps associated with an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `$skipToken` - _optional_ - Skip to a web app in the list of webapps associated with app service plan. If specified, the resulting list will contain web apps starting from (including) the skipToken. Otherwise, the resulting list contains web apps from the start of the list
* `$filter` - _optional_ - Supported filter: $filter=state eq running. Returns only web apps that are currently running
* `$top` - _optional_ - List page size. If specified, results are paged.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Gets all selectable SKUs for a given App Service Plan

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of App Service Plan
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Gets server farm usage information

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of App Service Plan
* `$filter` - _optional_ - Return only usages/metrics specified in the filter. Filter conforms to odata syntax. Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2').
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get all Virtual Networks associated with an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get a Virtual Network associated with an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `vnetName` - _required_ - Name of the Virtual Network.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get a Virtual Network gateway.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `vnetName` - _required_ - Name of the Virtual Network.
* `gatewayName` - _required_ - Name of the gateway. Only the 'primary' gateway is supported.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Update a Virtual Network gateway.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `vnetName` - _required_ - Name of the Virtual Network.
* `gatewayName` - _required_ - Name of the gateway. Only the 'primary' gateway is supported.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get all routes that are associated with a Virtual Network in an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `vnetName` - _required_ - Name of the Virtual Network.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Delete a Virtual Network route in an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `vnetName` - _required_ - Name of the Virtual Network.
* `routeName` - _required_ - Name of the Virtual Network route.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get a Virtual Network route in an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `vnetName` - _required_ - Name of the Virtual Network.
* `routeName` - _required_ - Name of the Virtual Network route.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Create or update a Virtual Network route in an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `vnetName` - _required_ - Name of the Virtual Network.
* `routeName` - _required_ - Name of the Virtual Network route.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Create or update a Virtual Network route in an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `vnetName` - _required_ - Name of the Virtual Network.
* `routeName` - _required_ - Name of the Virtual Network route.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Reboot a worker machine in an App Service plan.

*Tags:* `AppServicePlans`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the App Service plan.
* `workerName` - _required_ - Name of worker machine, which typically starts with RD.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

## License

**flow**ground :- Telekom iPaaS / azure-com-web-app-service-plans-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
