# ![LOGO](logo.png) MonitorManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the MonitorManagementClient API (version 2017-05-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/monitor-diagnosticsSettingsCategories_API/2017-05-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:26+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists the diagnostic settings categories for the specified resource.

*Tags:* `DiagnosticSettingsCategories`

#### Input Parameters
* `resourceUri` - _required_ - The identifier of the resource.
* `api-version` - _required_ - Client Api Version.

### Gets the diagnostic settings category for the specified resource.

*Tags:* `DiagnosticSettingsCategories`

#### Input Parameters
* `resourceUri` - _required_ - The identifier of the resource.
* `api-version` - _required_ - Client Api Version.
* `name` - _required_ - The name of the diagnostic setting.

## License

**flow**ground :- Telekom iPaaS / azure-com-monitor-diagnostics-settings-categories-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
