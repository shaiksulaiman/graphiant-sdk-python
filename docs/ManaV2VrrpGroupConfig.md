# ManaV2VrrpGroupConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**accept_mode** | **bool** |  | [optional] 
**allow_inter_operability** | **bool** |  | [optional] 
**description** | **str** |  | [optional] 
**enabled** | **bool** |  | [optional] 
**preempt** | **bool** |  | [optional] 
**priority** | **int** |  | [optional] 
**tracked_interfaces** | [**List[ManaV2NullableInterfacePriorityDecrement]**](ManaV2NullableInterfacePriorityDecrement.md) |  | [optional] 
**virtual_ip** | **str** |  | [optional] 
**virtual_router_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_vrrp_group_config import ManaV2VrrpGroupConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2VrrpGroupConfig from a JSON string
mana_v2_vrrp_group_config_instance = ManaV2VrrpGroupConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2VrrpGroupConfig.to_json())

# convert the object into a dict
mana_v2_vrrp_group_config_dict = mana_v2_vrrp_group_config_instance.to_dict()
# create an instance of ManaV2VrrpGroupConfig from a dict
mana_v2_vrrp_group_config_from_dict = ManaV2VrrpGroupConfig.from_dict(mana_v2_vrrp_group_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


