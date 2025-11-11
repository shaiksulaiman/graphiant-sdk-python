# IpfixNatEntryFilter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination_ip** | **str** |  | [optional] 
**destination_port** | **int** |  | [optional] 
**inside_local_ip** | **str** |  | [optional] 
**inside_local_port** | **int** |  | [optional] 
**nat_type** | **str** |  | [optional] 
**outside_global_ip** | **str** |  | [optional] 
**outside_global_port** | **int** |  | [optional] 
**vrf_ids** | **List[int]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_nat_entry_filter import IpfixNatEntryFilter

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixNatEntryFilter from a JSON string
ipfix_nat_entry_filter_instance = IpfixNatEntryFilter.from_json(json)
# print the JSON string representation of the object
print(IpfixNatEntryFilter.to_json())

# convert the object into a dict
ipfix_nat_entry_filter_dict = ipfix_nat_entry_filter_instance.to_dict()
# create an instance of IpfixNatEntryFilter from a dict
ipfix_nat_entry_filter_from_dict = IpfixNatEntryFilter.from_dict(ipfix_nat_entry_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


