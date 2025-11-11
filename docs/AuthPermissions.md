# AuthPermissions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**billing_and_invoicing** | **str** |  | [optional] 
**licensing** | **str** |  | [optional] 
**order_status** | **str** |  | [optional] 
**support** | **str** |  | [optional] 
**user_and_tenant_management** | **str** |  | [optional] 
**asset_manager** | **str** |  | [optional] 
**global_services** | **str** |  | [optional] 
**network_configurations** | **str** |  | [optional] 
**safety_and_security** | **str** |  | [optional] 
**service_policies** | **str** |  | [optional] 
**compliance** | **str** |  | [optional] 
**developer_tools** | **str** |  | [optional] 
**insights** | **str** |  | [optional] 
**logs** | **str** |  | [optional] 
**monitoring_and_troubleshooting** | **str** |  | [optional] 
**reports** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.auth_permissions import AuthPermissions

# TODO update the JSON string below
json = "{}"
# create an instance of AuthPermissions from a JSON string
auth_permissions_instance = AuthPermissions.from_json(json)
# print the JSON string representation of the object
print(AuthPermissions.to_json())

# convert the object into a dict
auth_permissions_dict = auth_permissions_instance.to_dict()
# create an instance of AuthPermissions from a dict
auth_permissions_from_dict = AuthPermissions.from_dict(auth_permissions_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


