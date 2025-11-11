# ManaV2VrrpGroup


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**accept_mode** | **bool** |  | [optional] 
**allow_inter_operability** | **bool** |  | [optional] 
**description** | **str** |  | [optional] 
**effective_priority** | **int** |  | [optional] 
**enabled** | **bool** |  | [optional] 
**group_members** | [**List[ManaV2VRRPGroupMember]**](ManaV2VRRPGroupMember.md) |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**preempt** | **bool** |  | [optional] 
**priority** | **int** |  | [optional] 
**state** | **str** |  | [optional] 
**tracked_interfaces** | [**List[ManaV2VRRPGroupInterfacePriorityDecrement]**](ManaV2VRRPGroupInterfacePriorityDecrement.md) |  | [optional] 
**virtual_ip_address** | **str** |  | [optional] 
**virtual_mac_address** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_vrrp_group import ManaV2VrrpGroup

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2VrrpGroup from a JSON string
mana_v2_vrrp_group_instance = ManaV2VrrpGroup.from_json(json)
# print the JSON string representation of the object
print(ManaV2VrrpGroup.to_json())

# convert the object into a dict
mana_v2_vrrp_group_dict = mana_v2_vrrp_group_instance.to_dict()
# create an instance of ManaV2VrrpGroup from a dict
mana_v2_vrrp_group_from_dict = ManaV2VrrpGroup.from_dict(mana_v2_vrrp_group_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


