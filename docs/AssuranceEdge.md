# AssuranceEdge


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**device_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_edge import AssuranceEdge

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceEdge from a JSON string
assurance_edge_instance = AssuranceEdge.from_json(json)
# print the JSON string representation of the object
print(AssuranceEdge.to_json())

# convert the object into a dict
assurance_edge_dict = assurance_edge_instance.to_dict()
# create an instance of AssuranceEdge from a dict
assurance_edge_from_dict = AssuranceEdge.from_dict(assurance_edge_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


