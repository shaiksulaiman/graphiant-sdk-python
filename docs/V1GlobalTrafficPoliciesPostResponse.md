# V1GlobalTrafficPoliciesPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**traffic_policy** | [**ManaV2ForwardingPolicy**](ManaV2ForwardingPolicy.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_traffic_policies_post_response import V1GlobalTrafficPoliciesPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalTrafficPoliciesPostResponse from a JSON string
v1_global_traffic_policies_post_response_instance = V1GlobalTrafficPoliciesPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalTrafficPoliciesPostResponse.to_json())

# convert the object into a dict
v1_global_traffic_policies_post_response_dict = v1_global_traffic_policies_post_response_instance.to_dict()
# create an instance of V1GlobalTrafficPoliciesPostResponse from a dict
v1_global_traffic_policies_post_response_from_dict = V1GlobalTrafficPoliciesPostResponse.from_dict(v1_global_traffic_policies_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


