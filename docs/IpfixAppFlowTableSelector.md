# IpfixAppFlowTableSelector


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuit_name** | **List[str]** |  | [optional] 
**sla_class** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_app_flow_table_selector import IpfixAppFlowTableSelector

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixAppFlowTableSelector from a JSON string
ipfix_app_flow_table_selector_instance = IpfixAppFlowTableSelector.from_json(json)
# print the JSON string representation of the object
print(IpfixAppFlowTableSelector.to_json())

# convert the object into a dict
ipfix_app_flow_table_selector_dict = ipfix_app_flow_table_selector_instance.to_dict()
# create an instance of IpfixAppFlowTableSelector from a dict
ipfix_app_flow_table_selector_from_dict = IpfixAppFlowTableSelector.from_dict(ipfix_app_flow_table_selector_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


