# ManaV2BgpRedistribute


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bgp** | **bool** |  | [optional] 
**connected** | **bool** |  | [optional] 
**dia** | **bool** |  | [optional] 
**ospfv2** | **bool** |  | [optional] 
**static** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bgp_redistribute import ManaV2BgpRedistribute

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BgpRedistribute from a JSON string
mana_v2_bgp_redistribute_instance = ManaV2BgpRedistribute.from_json(json)
# print the JSON string representation of the object
print(ManaV2BgpRedistribute.to_json())

# convert the object into a dict
mana_v2_bgp_redistribute_dict = mana_v2_bgp_redistribute_instance.to_dict()
# create an instance of ManaV2BgpRedistribute from a dict
mana_v2_bgp_redistribute_from_dict = ManaV2BgpRedistribute.from_dict(mana_v2_bgp_redistribute_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


