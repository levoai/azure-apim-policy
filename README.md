# Azure API Management Instrumentation Policy

To instrument your Azure API Management Portal API endpoints, the following two steps are required:
1. Adding named values to the API Management instance.
2. Adding the policy to the API endpoints.

## Adding Named Values

Check the official Azure API Management Documentation: https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-properties?tabs=azure-portal#add-a-plain-or-secret-value-to-api-management

The supported named values are:
- `LevoOrgId`
- `LevoTracesEndpoint`
- `LevoEnv`

## Adding the Policy

The policy may only be added from the Azure Portal dashboard.

Check the official Azure API Management Documentation: https://learn.microsoft.com/en-us/azure/api-management/set-edit-policies?tabs=editor#configure-policy-in-the-portal

Copy the policy from the `policy.xml` file in this repo and paste it into the policy editor.

Ensure that the policy is added at the [API Scope](https://learn.microsoft.com/en-us/azure/api-management/set-edit-policies?tabs=editor#api-scope).
