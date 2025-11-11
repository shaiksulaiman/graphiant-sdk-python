# IpfixStats


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**avg_usage** | **float** | Average service usage in kbps | [optional] 
**peak_usage** | **float** | Peak service usage in kbps | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_stats import IpfixStats

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixStats from a JSON string
ipfix_stats_instance = IpfixStats.from_json(json)
# print the JSON string representation of the object
print(IpfixStats.to_json())

# convert the object into a dict
ipfix_stats_dict = ipfix_stats_instance.to_dict()
# create an instance of IpfixStats from a dict
ipfix_stats_from_dict = IpfixStats.from_dict(ipfix_stats_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


