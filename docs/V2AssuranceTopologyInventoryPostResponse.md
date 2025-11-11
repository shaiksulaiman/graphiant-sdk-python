# V2AssuranceTopologyInventoryPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_names** | **List[str]** |  | [optional] 
**client_sites** | [**List[AssuranceSite]**](AssuranceSite.md) |  | [optional] 
**regions** | [**List[AssuranceRegion]**](AssuranceRegion.md) |  | [optional] 
**server_sites** | [**List[AssuranceSite]**](AssuranceSite.md) |  | [optional] 
**topology_change_ts** | [**List[GoogleProtobufTimestamp]**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_topology_inventory_post_response import V2AssuranceTopologyInventoryPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceTopologyInventoryPostResponse from a JSON string
v2_assurance_topology_inventory_post_response_instance = V2AssuranceTopologyInventoryPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceTopologyInventoryPostResponse.to_json())

# convert the object into a dict
v2_assurance_topology_inventory_post_response_dict = v2_assurance_topology_inventory_post_response_instance.to_dict()
# create an instance of V2AssuranceTopologyInventoryPostResponse from a dict
v2_assurance_topology_inventory_post_response_from_dict = V2AssuranceTopologyInventoryPostResponse.from_dict(v2_assurance_topology_inventory_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


