# ManaV2VRRPGroupMember


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuit** | **str** |  | [optional] 
**device_id** | **int** |  | [optional] 
**effective_priority** | **int** |  | [optional] 
**hostname** | **str** |  | [optional] 
**interface** | **str** |  | [optional] 
**lan** | **str** |  | [optional] 
**local_ip_address** | **str** |  | [optional] 
**priority** | **int** |  | [optional] 
**state** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_vrrp_group_member import ManaV2VRRPGroupMember

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2VRRPGroupMember from a JSON string
mana_v2_vrrp_group_member_instance = ManaV2VRRPGroupMember.from_json(json)
# print the JSON string representation of the object
print(ManaV2VRRPGroupMember.to_json())

# convert the object into a dict
mana_v2_vrrp_group_member_dict = mana_v2_vrrp_group_member_instance.to_dict()
# create an instance of ManaV2VRRPGroupMember from a dict
mana_v2_vrrp_group_member_from_dict = ManaV2VRRPGroupMember.from_dict(mana_v2_vrrp_group_member_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


