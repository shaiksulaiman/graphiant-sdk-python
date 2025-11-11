# IpfixAppBandwidthStats


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dl_bw** | **float** | Bandwidth in kilo bits per second | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**ul_bw** | **float** | Bandwidth in kilo bits per second | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_app_bandwidth_stats import IpfixAppBandwidthStats

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixAppBandwidthStats from a JSON string
ipfix_app_bandwidth_stats_instance = IpfixAppBandwidthStats.from_json(json)
# print the JSON string representation of the object
print(IpfixAppBandwidthStats.to_json())

# convert the object into a dict
ipfix_app_bandwidth_stats_dict = ipfix_app_bandwidth_stats_instance.to_dict()
# create an instance of IpfixAppBandwidthStats from a dict
ipfix_app_bandwidth_stats_from_dict = IpfixAppBandwidthStats.from_dict(ipfix_app_bandwidth_stats_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


