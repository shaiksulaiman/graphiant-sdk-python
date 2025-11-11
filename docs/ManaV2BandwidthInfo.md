# ManaV2BandwidthInfo


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**combined_credits** | **float** | Sum of the credits associated with cloud and gateway networks | [optional] 
**core_bandwidth** | **float** | Soft-upper-bounded max speed in gigabytes per second associated with core network connections | [optional] 
**core_credits** | **float** | Credits derived from bandwidth on core network connections | [optional] 
**gw_bandwidth** | **float** | Soft-upper-bounded max speed in gigabytes per second associated with gateway connections | [optional] 
**gw_credits** | **float** | Credits derived from bandwidth on gateway network connections | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bandwidth_info import ManaV2BandwidthInfo

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BandwidthInfo from a JSON string
mana_v2_bandwidth_info_instance = ManaV2BandwidthInfo.from_json(json)
# print the JSON string representation of the object
print(ManaV2BandwidthInfo.to_json())

# convert the object into a dict
mana_v2_bandwidth_info_dict = mana_v2_bandwidth_info_instance.to_dict()
# create an instance of ManaV2BandwidthInfo from a dict
mana_v2_bandwidth_info_from_dict = ManaV2BandwidthInfo.from_dict(mana_v2_bandwidth_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


