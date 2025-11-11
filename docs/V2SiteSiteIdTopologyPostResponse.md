# V2SiteSiteIdTopologyPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**edges** | [**List[StatsmonV2Edge]**](StatsmonV2Edge.md) |  | [optional] 
**nodes** | [**List[StatsmonV2Node]**](StatsmonV2Node.md) |  | [optional] 
**snapshots** | [**List[V2SiteSiteIdTopologyPostResponseSnapshot]**](V2SiteSiteIdTopologyPostResponseSnapshot.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_site_site_id_topology_post_response import V2SiteSiteIdTopologyPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2SiteSiteIdTopologyPostResponse from a JSON string
v2_site_site_id_topology_post_response_instance = V2SiteSiteIdTopologyPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2SiteSiteIdTopologyPostResponse.to_json())

# convert the object into a dict
v2_site_site_id_topology_post_response_dict = v2_site_site_id_topology_post_response_instance.to_dict()
# create an instance of V2SiteSiteIdTopologyPostResponse from a dict
v2_site_site_id_topology_post_response_from_dict = V2SiteSiteIdTopologyPostResponse.from_dict(v2_site_site_id_topology_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


