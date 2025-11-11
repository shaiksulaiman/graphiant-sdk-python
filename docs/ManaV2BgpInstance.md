# ManaV2BgpInstance


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**asn** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**router_id** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bgp_instance import ManaV2BgpInstance

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BgpInstance from a JSON string
mana_v2_bgp_instance_instance = ManaV2BgpInstance.from_json(json)
# print the JSON string representation of the object
print(ManaV2BgpInstance.to_json())

# convert the object into a dict
mana_v2_bgp_instance_dict = mana_v2_bgp_instance_instance.to_dict()
# create an instance of ManaV2BgpInstance from a dict
mana_v2_bgp_instance_from_dict = ManaV2BgpInstance.from_dict(mana_v2_bgp_instance_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


