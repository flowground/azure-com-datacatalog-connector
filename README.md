# ![LOGO](logo.png) Azure Data Catalog Resource Provider **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Data Catalog Resource Provider API (version 2016-03-30).

Generated from: https://api.apis.guru/v2/specs/azure.com/datacatalog/2016-03-30/swagger.json<br/>
Generated at: 2019-05-07T17:37:56+03:00

## API Description

The Azure Data Catalog Resource Provider Services API.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all the available Azure Data Catalog service operations.

*Tags:* `AzureDataCatalog`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### List catalogs in Resource Group (GET Resources)

> The List catalogs in Resource Group operation lists all the Azure Data Catalogs available under the given resource group.

*Tags:* `AzureDataCatalog`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.

### Delete Azure Data Catalog Service (DELETE Resource)

> The Delete Azure Data Catalog Service operation deletes an existing data catalog.

*Tags:* `AzureDataCatalog`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `catalogName` - _required_ - The name of the data catalog in the specified subscription and resource group.

### Get Azure Data Catalog service (GET Resources)

> The Get Azure Data Catalog Service operation retrieves a json representation of the data catalog.

*Tags:* `AzureDataCatalog`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `catalogName` - _required_ - The name of the data catalog in the specified subscription and resource group.

### Update Azure Data Catalog Service (PATCH Resource)

> The Update Azure Data Catalog Service operation can be used to update the existing deployment. The update call only supports the properties listed in the PATCH body.

*Tags:* `AzureDataCatalog`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `catalogName` - _required_ - The name of the data catalog in the specified subscription and resource group.

### Create or Update Azure Data Catalog service (PUT Resource)

> The Create Azure Data Catalog service operation creates a new data catalog service with the specified parameters. If the specific service already exists, then any patchable properties will be updated and any immutable properties will remain unchanged.

*Tags:* `AzureDataCatalog`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `catalogName` - _required_ - The name of the data catalog in the specified subscription and resource group.

## License

**flow**ground :- Telekom iPaaS / azure-com-datacatalog-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
