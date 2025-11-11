# V2MonitoringPolicyPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[V2MonitoringPolicyPostResponseData]**](V2MonitoringPolicyPostResponseData.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_policy_post_response import V2MonitoringPolicyPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringPolicyPostResponse from a JSON string
v2_monitoring_policy_post_response_instance = V2MonitoringPolicyPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringPolicyPostResponse.to_json())

# convert the object into a dict
v2_monitoring_policy_post_response_dict = v2_monitoring_policy_post_response_instance.to_dict()
# create an instance of V2MonitoringPolicyPostResponse from a dict
v2_monitoring_policy_post_response_from_dict = V2MonitoringPolicyPostResponse.from_dict(v2_monitoring_policy_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


