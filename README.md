# ![LOGO](logo.png) Security Center **flow**ground Connector

## Description

A generated **flow**ground connector for the Security Center API (version 2017-08-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/security/2017-08-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:55+03:00

## API Description

API spec for Microsoft.Security (Azure Security Center) resource provider

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Exposes the auto provisioning settings of the subscriptions

*Tags:* `AutoProvisioningSettings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID

### Details of a specific setting

*Tags:* `AutoProvisioningSettings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `settingName` - _required_ - Auto provisioning setting key

### Details of a specific setting

*Tags:* `AutoProvisioningSettings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `settingName` - _required_ - Auto provisioning setting key

### Security pricing configurations in the subscription

*Tags:* `Pricings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID

### Security pricing configuration in the subscriptionSecurity pricing configuration in the subscription

*Tags:* `Pricings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `pricingName` - _required_ - name of the pricing configuration

### Security pricing configuration in the subscription

*Tags:* `Pricings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `pricingName` - _required_ - name of the pricing configuration

### Security contact configurations for the subscription

*Tags:* `Security Contacts`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID

### Security contact configurations for the subscription

*Tags:* `Security Contacts`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `securityContactName` - _required_ - Name of the security contact object

### Security contact configurations for the subscription

*Tags:* `Security Contacts`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `securityContactName` - _required_ - Name of the security contact object

### Security contact configurations for the subscription

*Tags:* `Security Contacts`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `securityContactName` - _required_ - Name of the security contact object

### Security contact configurations for the subscription

*Tags:* `Security Contacts`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `securityContactName` - _required_ - Name of the security contact object

### Settings about different configurations in security center

*Tags:* `Settings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID

### Settings of different configurations in security center

*Tags:* `Settings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `settingName` - _required_ - Name of setting: (MCAS/WDATP)
    Possible values: MCAS, WDATP.

### updating settings about different configurations in security center

*Tags:* `Settings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `settingName` - _required_ - Name of setting: (MCAS/WDATP)
    Possible values: MCAS, WDATP.

### Settings about where we should store your security data and logs. If the result is empty, it means that no custom-workspace configuration was set

*Tags:* `Workspace Settings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID

### Deletes the custom workspace settings for this subscription. new VMs will report to the default workspace

*Tags:* `Workspace Settings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `workspaceSettingName` - _required_ - Name of the security setting

### Settings about where we should store your security data and logs. If the result is empty, it means that no custom-workspace configuration was set

*Tags:* `Workspace Settings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `workspaceSettingName` - _required_ - Name of the security setting

### Settings about where we should store your security data and logs

*Tags:* `Workspace Settings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `workspaceSettingName` - _required_ - Name of the security setting

### creating settings about where we should store your security data and logs

*Tags:* `Workspace Settings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `workspaceSettingName` - _required_ - Name of the security setting

### Security pricing configurations in the resource group

*Tags:* `Pricings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.

### Security pricing configuration in the resource group

*Tags:* `Pricings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `pricingName` - _required_ - name of the pricing configuration

### Security pricing configuration in the resource group

*Tags:* `Pricings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `pricingName` - _required_ - name of the pricing configuration

### Gets the Advanced Threat Protection settings for the specified resource.

*Tags:* `AdvancedThreatProtection`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `resourceId` - _required_ - The identifier of the resource.
* `settingName` - _required_ - Advanced Threat Protection setting name.
    Possible values: current.

### Creates or updates the Advanced Threat Protection settings on a specified resource.

*Tags:* `AdvancedThreatProtection`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `resourceId` - _required_ - The identifier of the resource.
* `settingName` - _required_ - Advanced Threat Protection setting name.
    Possible values: current.

### The Compliance scores of the specific management group.

*Tags:* `Compliances`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `scope` - _required_ - Scope of the query, can be subscription (/subscriptions/0b06d9ea-afe6-4779-bd59-30e5c2d9d13f) or management group (/providers/Microsoft.Management/managementGroups/mgName).

### Details of a specific Compliance.

*Tags:* `Compliances`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `scope` - _required_ - Scope of the query, can be subscription (/subscriptions/0b06d9ea-afe6-4779-bd59-30e5c2d9d13f) or management group (/providers/Microsoft.Management/managementGroups/mgName).
* `complianceName` - _required_ - name of the Compliance

### Information protection policies of a specific management group.

*Tags:* `InformationProtectionPolicies`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `scope` - _required_ - Scope of the query, can be subscription (/subscriptions/0b06d9ea-afe6-4779-bd59-30e5c2d9d13f) or management group (/providers/Microsoft.Management/managementGroups/mgName).

### Details of the information protection policy.

*Tags:* `InformationProtectionPolicies`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `scope` - _required_ - Scope of the query, can be subscription (/subscriptions/0b06d9ea-afe6-4779-bd59-30e5c2d9d13f) or management group (/providers/Microsoft.Management/managementGroups/mgName).
* `informationProtectionPolicyName` - _required_ - Name of the information protection policy.
    Possible values: effective, custom.

### Details of the information protection policy.

*Tags:* `InformationProtectionPolicies`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2017-08-01-preview.
* `scope` - _required_ - Scope of the query, can be subscription (/subscriptions/0b06d9ea-afe6-4779-bd59-30e5c2d9d13f) or management group (/providers/Microsoft.Management/managementGroups/mgName).
* `informationProtectionPolicyName` - _required_ - Name of the information protection policy.
    Possible values: effective, custom.

## License

**flow**ground :- Telekom iPaaS / azure-com-security-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
