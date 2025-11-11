# V2AssuranceTopologyClientSessionsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sessions** | [**List[AssuranceClientSession]**](AssuranceClientSession.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_topology_client_sessions_post_response import V2AssuranceTopologyClientSessionsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceTopologyClientSessionsPostResponse from a JSON string
v2_assurance_topology_client_sessions_post_response_instance = V2AssuranceTopologyClientSessionsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceTopologyClientSessionsPostResponse.to_json())

# convert the object into a dict
v2_assurance_topology_client_sessions_post_response_dict = v2_assurance_topology_client_sessions_post_response_instance.to_dict()
# create an instance of V2AssuranceTopologyClientSessionsPostResponse from a dict
v2_assurance_topology_client_sessions_post_response_from_dict = V2AssuranceTopologyClientSessionsPostResponse.from_dict(v2_assurance_topology_client_sessions_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


