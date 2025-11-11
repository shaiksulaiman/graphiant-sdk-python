# V1EdgesHardwareAssignedGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**edges_summary** | [**List[SearchEdgeSummary]**](SearchEdgeSummary.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_edges_hardware_assigned_get_response import V1EdgesHardwareAssignedGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1EdgesHardwareAssignedGetResponse from a JSON string
v1_edges_hardware_assigned_get_response_instance = V1EdgesHardwareAssignedGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1EdgesHardwareAssignedGetResponse.to_json())

# convert the object into a dict
v1_edges_hardware_assigned_get_response_dict = v1_edges_hardware_assigned_get_response_instance.to_dict()
# create an instance of V1EdgesHardwareAssignedGetResponse from a dict
v1_edges_hardware_assigned_get_response_from_dict = V1EdgesHardwareAssignedGetResponse.from_dict(v1_edges_hardware_assigned_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


