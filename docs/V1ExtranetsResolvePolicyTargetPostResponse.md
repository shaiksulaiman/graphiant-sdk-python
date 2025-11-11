# V1ExtranetsResolvePolicyTargetPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**devices** | [**List[ManaV2Device]**](ManaV2Device.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_resolve_policy_target_post_response import V1ExtranetsResolvePolicyTargetPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsResolvePolicyTargetPostResponse from a JSON string
v1_extranets_resolve_policy_target_post_response_instance = V1ExtranetsResolvePolicyTargetPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsResolvePolicyTargetPostResponse.to_json())

# convert the object into a dict
v1_extranets_resolve_policy_target_post_response_dict = v1_extranets_resolve_policy_target_post_response_instance.to_dict()
# create an instance of V1ExtranetsResolvePolicyTargetPostResponse from a dict
v1_extranets_resolve_policy_target_post_response_from_dict = V1ExtranetsResolvePolicyTargetPostResponse.from_dict(v1_extranets_resolve_policy_target_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


