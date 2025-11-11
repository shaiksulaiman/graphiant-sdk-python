# IpfixAppTopologySelector


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_id** | **int** | Filter by app ID | [optional] 
**app_name** | **str** | Filter by application name | [optional] 
**sla_class** | **str** | Filter by SLA class | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_app_topology_selector import IpfixAppTopologySelector

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixAppTopologySelector from a JSON string
ipfix_app_topology_selector_instance = IpfixAppTopologySelector.from_json(json)
# print the JSON string representation of the object
print(IpfixAppTopologySelector.to_json())

# convert the object into a dict
ipfix_app_topology_selector_dict = ipfix_app_topology_selector_instance.to_dict()
# create an instance of IpfixAppTopologySelector from a dict
ipfix_app_topology_selector_from_dict = IpfixAppTopologySelector.from_dict(ipfix_app_topology_selector_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


