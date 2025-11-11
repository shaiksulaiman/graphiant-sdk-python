# V1DevicesSessionStatusPostResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**core_bgp_neighbors_count** | **int** |  | [optional] 
**device_id** | **int** |  | [optional] 
**odp_bgp_neighbors_count** | **int** |  | [optional] 
**wan_interfaces_count** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_session_status_post_response_data import V1DevicesSessionStatusPostResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesSessionStatusPostResponseData from a JSON string
v1_devices_session_status_post_response_data_instance = V1DevicesSessionStatusPostResponseData.from_json(json)
# print the JSON string representation of the object
print(V1DevicesSessionStatusPostResponseData.to_json())

# convert the object into a dict
v1_devices_session_status_post_response_data_dict = v1_devices_session_status_post_response_data_instance.to_dict()
# create an instance of V1DevicesSessionStatusPostResponseData from a dict
v1_devices_session_status_post_response_data_from_dict = V1DevicesSessionStatusPostResponseData.from_dict(v1_devices_session_status_post_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


