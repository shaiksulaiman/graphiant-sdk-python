# V1LldpInterfaceIdNeighborsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**neighbors** | [**List[ManaV2LldpNeighbor]**](ManaV2LldpNeighbor.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_lldp_interface_id_neighbors_get_response import V1LldpInterfaceIdNeighborsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1LldpInterfaceIdNeighborsGetResponse from a JSON string
v1_lldp_interface_id_neighbors_get_response_instance = V1LldpInterfaceIdNeighborsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1LldpInterfaceIdNeighborsGetResponse.to_json())

# convert the object into a dict
v1_lldp_interface_id_neighbors_get_response_dict = v1_lldp_interface_id_neighbors_get_response_instance.to_dict()
# create an instance of V1LldpInterfaceIdNeighborsGetResponse from a dict
v1_lldp_interface_id_neighbors_get_response_from_dict = V1LldpInterfaceIdNeighborsGetResponse.from_dict(v1_lldp_interface_id_neighbors_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


