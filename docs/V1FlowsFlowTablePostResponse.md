# V1FlowsFlowTablePostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cursor_ref** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**flow_table** | [**List[IpfixAppFlowTable]**](IpfixAppFlowTable.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_flows_flow_table_post_response import V1FlowsFlowTablePostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1FlowsFlowTablePostResponse from a JSON string
v1_flows_flow_table_post_response_instance = V1FlowsFlowTablePostResponse.from_json(json)
# print the JSON string representation of the object
print(V1FlowsFlowTablePostResponse.to_json())

# convert the object into a dict
v1_flows_flow_table_post_response_dict = v1_flows_flow_table_post_response_instance.to_dict()
# create an instance of V1FlowsFlowTablePostResponse from a dict
v1_flows_flow_table_post_response_from_dict = V1FlowsFlowTablePostResponse.from_dict(v1_flows_flow_table_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


