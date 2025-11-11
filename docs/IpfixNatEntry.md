# IpfixNatEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination_ip_address** | **str** |  | [optional] 
**destination_port** | **int** |  | [optional] 
**inside_global_ip_address** | **str** |  | [optional] 
**inside_global_port** | **int** |  | [optional] 
**inside_local_ip_address** | **str** |  | [optional] 
**inside_local_port** | **int** |  | [optional] 
**nat_type** | **str** |  | [optional] 
**outside_global_ip_address** | **str** |  | [optional] 
**outside_global_port** | **int** |  | [optional] 
**pre_destination_ip_address** | **str** |  | [optional] 
**pre_destination_port** | **int** |  | [optional] 
**vrf_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_nat_entry import IpfixNatEntry

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixNatEntry from a JSON string
ipfix_nat_entry_instance = IpfixNatEntry.from_json(json)
# print the JSON string representation of the object
print(IpfixNatEntry.to_json())

# convert the object into a dict
ipfix_nat_entry_dict = ipfix_nat_entry_instance.to_dict()
# create an instance of IpfixNatEntry from a dict
ipfix_nat_entry_from_dict = IpfixNatEntry.from_dict(ipfix_nat_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


