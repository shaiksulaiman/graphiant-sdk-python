# ManaV2BgpMultipath


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**enabled** | **bool** |  | [optional] 
**vrf_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bgp_multipath import ManaV2BgpMultipath

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BgpMultipath from a JSON string
mana_v2_bgp_multipath_instance = ManaV2BgpMultipath.from_json(json)
# print the JSON string representation of the object
print(ManaV2BgpMultipath.to_json())

# convert the object into a dict
mana_v2_bgp_multipath_dict = mana_v2_bgp_multipath_instance.to_dict()
# create an instance of ManaV2BgpMultipath from a dict
mana_v2_bgp_multipath_from_dict = ManaV2BgpMultipath.from_dict(mana_v2_bgp_multipath_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


