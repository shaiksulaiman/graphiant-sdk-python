# ManaV2InternetAccessBandwidthInfo


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**internet_bandwidth** | **float** | Bandwidth value associated with dia gateways. This should either be 0, 10, or 100. | [optional] 
**internet_credits** | **float** | Additional credits to support the provided DIA bandwidth | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_internet_access_bandwidth_info import ManaV2InternetAccessBandwidthInfo

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2InternetAccessBandwidthInfo from a JSON string
mana_v2_internet_access_bandwidth_info_instance = ManaV2InternetAccessBandwidthInfo.from_json(json)
# print the JSON string representation of the object
print(ManaV2InternetAccessBandwidthInfo.to_json())

# convert the object into a dict
mana_v2_internet_access_bandwidth_info_dict = mana_v2_internet_access_bandwidth_info_instance.to_dict()
# create an instance of ManaV2InternetAccessBandwidthInfo from a dict
mana_v2_internet_access_bandwidth_info_from_dict = ManaV2InternetAccessBandwidthInfo.from_dict(mana_v2_internet_access_bandwidth_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


