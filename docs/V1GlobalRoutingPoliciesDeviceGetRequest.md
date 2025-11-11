# V1GlobalRoutingPoliciesDeviceGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_routing_policies_device_get_request import V1GlobalRoutingPoliciesDeviceGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalRoutingPoliciesDeviceGetRequest from a JSON string
v1_global_routing_policies_device_get_request_instance = V1GlobalRoutingPoliciesDeviceGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1GlobalRoutingPoliciesDeviceGetRequest.to_json())

# convert the object into a dict
v1_global_routing_policies_device_get_request_dict = v1_global_routing_policies_device_get_request_instance.to_dict()
# create an instance of V1GlobalRoutingPoliciesDeviceGetRequest from a dict
v1_global_routing_policies_device_get_request_from_dict = V1GlobalRoutingPoliciesDeviceGetRequest.from_dict(v1_global_routing_policies_device_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


