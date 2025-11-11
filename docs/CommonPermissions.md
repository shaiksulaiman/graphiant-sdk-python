# CommonPermissions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**asset_manager** | **str** |  | [optional] 
**b2b** | **str** |  | [optional] 
**b2b_security_profile_external** | **str** |  | [optional] 
**billing_and_invoicing** | **str** |  | [optional] 
**compliance** | **str** |  | [optional] 
**developer_tools** | **str** |  | [optional] 
**gateway** | **str** |  | [optional] 
**global_services** | **str** |  | [optional] 
**insights** | **str** |  | [optional] 
**licensing** | **str** |  | [optional] 
**logs** | **str** |  | [optional] 
**monitoring_and_troubleshooting** | **str** |  | [optional] 
**network_configuration** | **str** |  | [optional] 
**order_status** | **str** |  | [optional] 
**reports** | **str** |  | [optional] 
**safety_and_security** | **str** |  | [optional] 
**service_policies** | **str** |  | [optional] 
**support** | **str** |  | [optional] 
**user_and_tenant_management** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.common_permissions import CommonPermissions

# TODO update the JSON string below
json = "{}"
# create an instance of CommonPermissions from a JSON string
common_permissions_instance = CommonPermissions.from_json(json)
# print the JSON string representation of the object
print(CommonPermissions.to_json())

# convert the object into a dict
common_permissions_dict = common_permissions_instance.to_dict()
# create an instance of CommonPermissions from a dict
common_permissions_from_dict = CommonPermissions.from_dict(common_permissions_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


