# ![LOGO](logo.png) SubscriptionsManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SubscriptionsManagementClient API (version 2015-11-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-DelegatedProvider/2015-11-01/swagger.json<br/>
Generated at: 2019-06-11T18:13:34+03:00

## API Description

The Admin Subscriptions Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get the list of delegatedProviders.

*Tags:* `DelegatedProviders`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Get the specified delegated provider.

*Tags:* `DelegatedProviders`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `delegatedProvider` - _required_ - DelegatedProvider identifier.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-delegated-provider-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
