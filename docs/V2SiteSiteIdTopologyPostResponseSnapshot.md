# V2SiteSiteIdTopologyPostResponseSnapshot


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**quality** | **str** |  | [optional] 
**snapshot_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_site_site_id_topology_post_response_snapshot import V2SiteSiteIdTopologyPostResponseSnapshot

# TODO update the JSON string below
json = "{}"
# create an instance of V2SiteSiteIdTopologyPostResponseSnapshot from a JSON string
v2_site_site_id_topology_post_response_snapshot_instance = V2SiteSiteIdTopologyPostResponseSnapshot.from_json(json)
# print the JSON string representation of the object
print(V2SiteSiteIdTopologyPostResponseSnapshot.to_json())

# convert the object into a dict
v2_site_site_id_topology_post_response_snapshot_dict = v2_site_site_id_topology_post_response_snapshot_instance.to_dict()
# create an instance of V2SiteSiteIdTopologyPostResponseSnapshot from a dict
v2_site_site_id_topology_post_response_snapshot_from_dict = V2SiteSiteIdTopologyPostResponseSnapshot.from_dict(v2_site_site_id_topology_post_response_snapshot_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


