# V1GlobalDeviceStatusGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ipfix_exported_id** | **int** |  | [optional] 
**prefix_set_id** | **int** |  | [optional] 
**routing_policy_id** | **int** |  | [optional] 
**snmp_id** | **int** |  | [optional] 
**syslog_server_id** | **int** |  | [optional] 
**traffic_policy_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_device_status_get_request import V1GlobalDeviceStatusGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalDeviceStatusGetRequest from a JSON string
v1_global_device_status_get_request_instance = V1GlobalDeviceStatusGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1GlobalDeviceStatusGetRequest.to_json())

# convert the object into a dict
v1_global_device_status_get_request_dict = v1_global_device_status_get_request_instance.to_dict()
# create an instance of V1GlobalDeviceStatusGetRequest from a dict
v1_global_device_status_get_request_from_dict = V1GlobalDeviceStatusGetRequest.from_dict(v1_global_device_status_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


