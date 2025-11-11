# IpfixNatUsage


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**current_count** | **int** |  | [optional] 
**current_count_extranet** | **int** |  | [optional] 
**current_count_pat** | **int** |  | [optional] 
**current_count_static** | **int** |  | [optional] 
**max_count** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_nat_usage import IpfixNatUsage

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixNatUsage from a JSON string
ipfix_nat_usage_instance = IpfixNatUsage.from_json(json)
# print the JSON string representation of the object
print(IpfixNatUsage.to_json())

# convert the object into a dict
ipfix_nat_usage_dict = ipfix_nat_usage_instance.to_dict()
# create an instance of IpfixNatUsage from a dict
ipfix_nat_usage_from_dict = IpfixNatUsage.from_dict(ipfix_nat_usage_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


