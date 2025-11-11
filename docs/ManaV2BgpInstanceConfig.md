# ManaV2BgpInstanceConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address_families** | **List[str]** |  | [optional] 
**asn** | **int** |  | [optional] 
**route_server** | **bool** |  | [optional] 
**router_id** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bgp_instance_config import ManaV2BgpInstanceConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BgpInstanceConfig from a JSON string
mana_v2_bgp_instance_config_instance = ManaV2BgpInstanceConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2BgpInstanceConfig.to_json())

# convert the object into a dict
mana_v2_bgp_instance_config_dict = mana_v2_bgp_instance_config_instance.to_dict()
# create an instance of ManaV2BgpInstanceConfig from a dict
mana_v2_bgp_instance_config_from_dict = ManaV2BgpInstanceConfig.from_dict(mana_v2_bgp_instance_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


