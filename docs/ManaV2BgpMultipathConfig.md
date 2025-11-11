# ManaV2BgpMultipathConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**enabled** | **bool** |  | [optional] 
**vrf_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bgp_multipath_config import ManaV2BgpMultipathConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BgpMultipathConfig from a JSON string
mana_v2_bgp_multipath_config_instance = ManaV2BgpMultipathConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2BgpMultipathConfig.to_json())

# convert the object into a dict
mana_v2_bgp_multipath_config_dict = mana_v2_bgp_multipath_config_instance.to_dict()
# create an instance of ManaV2BgpMultipathConfig from a dict
mana_v2_bgp_multipath_config_from_dict = ManaV2BgpMultipathConfig.from_dict(mana_v2_bgp_multipath_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


