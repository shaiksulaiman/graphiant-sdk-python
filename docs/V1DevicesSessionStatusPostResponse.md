# V1DevicesSessionStatusPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bgp_session_data_map** | [**Dict[str, V1DevicesSessionStatusPostResponseData]**](V1DevicesSessionStatusPostResponseData.md) |  | [optional] 
**bgp_session_map** | [**Dict[str, V1DevicesSessionStatusPostResponseData]**](V1DevicesSessionStatusPostResponseData.md) |  | [optional] 
**bgp_session_states** | [**List[V1DevicesSessionStatusPostResponseData]**](V1DevicesSessionStatusPostResponseData.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_session_status_post_response import V1DevicesSessionStatusPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesSessionStatusPostResponse from a JSON string
v1_devices_session_status_post_response_instance = V1DevicesSessionStatusPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesSessionStatusPostResponse.to_json())

# convert the object into a dict
v1_devices_session_status_post_response_dict = v1_devices_session_status_post_response_instance.to_dict()
# create an instance of V1DevicesSessionStatusPostResponse from a dict
v1_devices_session_status_post_response_from_dict = V1DevicesSessionStatusPostResponse.from_dict(v1_devices_session_status_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


