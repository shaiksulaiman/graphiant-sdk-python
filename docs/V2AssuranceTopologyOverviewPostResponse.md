# V2AssuranceTopologyOverviewPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**num_applications** | **int** |  | [optional] 
**num_flows** | **int** |  | [optional] 
**topology** | [**AssuranceTopology**](AssuranceTopology.md) |  | [optional] 
**topology_change_ts** | [**List[GoogleProtobufTimestamp]**](GoogleProtobufTimestamp.md) |  | [optional] 
**traffic_regions** | [**List[V2AssuranceTopologyOverviewPostResponseGeoregion]**](V2AssuranceTopologyOverviewPostResponseGeoregion.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_topology_overview_post_response import V2AssuranceTopologyOverviewPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceTopologyOverviewPostResponse from a JSON string
v2_assurance_topology_overview_post_response_instance = V2AssuranceTopologyOverviewPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceTopologyOverviewPostResponse.to_json())

# convert the object into a dict
v2_assurance_topology_overview_post_response_dict = v2_assurance_topology_overview_post_response_instance.to_dict()
# create an instance of V2AssuranceTopologyOverviewPostResponse from a dict
v2_assurance_topology_overview_post_response_from_dict = V2AssuranceTopologyOverviewPostResponse.from_dict(v2_assurance_topology_overview_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


