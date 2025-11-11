# V1GatewaysStatusPostRequestDeviceInfo


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**interface_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_gateways_status_post_request_device_info import V1GatewaysStatusPostRequestDeviceInfo

# TODO update the JSON string below
json = "{}"
# create an instance of V1GatewaysStatusPostRequestDeviceInfo from a JSON string
v1_gateways_status_post_request_device_info_instance = V1GatewaysStatusPostRequestDeviceInfo.from_json(json)
# print the JSON string representation of the object
print(V1GatewaysStatusPostRequestDeviceInfo.to_json())

# convert the object into a dict
v1_gateways_status_post_request_device_info_dict = v1_gateways_status_post_request_device_info_instance.to_dict()
# create an instance of V1GatewaysStatusPostRequestDeviceInfo from a dict
v1_gateways_status_post_request_device_info_from_dict = V1GatewaysStatusPostRequestDeviceInfo.from_dict(v1_gateways_status_post_request_device_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


