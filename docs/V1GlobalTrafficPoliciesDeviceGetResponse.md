# V1GlobalTrafficPoliciesDeviceGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**traffic_policy** | [**ManaV2ForwardingPolicy**](ManaV2ForwardingPolicy.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_traffic_policies_device_get_response import V1GlobalTrafficPoliciesDeviceGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalTrafficPoliciesDeviceGetResponse from a JSON string
v1_global_traffic_policies_device_get_response_instance = V1GlobalTrafficPoliciesDeviceGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalTrafficPoliciesDeviceGetResponse.to_json())

# convert the object into a dict
v1_global_traffic_policies_device_get_response_dict = v1_global_traffic_policies_device_get_response_instance.to_dict()
# create an instance of V1GlobalTrafficPoliciesDeviceGetResponse from a dict
v1_global_traffic_policies_device_get_response_from_dict = V1GlobalTrafficPoliciesDeviceGetResponse.from_dict(v1_global_traffic_policies_device_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


