# V1PolicyPrefixSetsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prefix_set** | [**ManaV2PrefixSet**](ManaV2PrefixSet.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_policy_prefix_sets_post_response import V1PolicyPrefixSetsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1PolicyPrefixSetsPostResponse from a JSON string
v1_policy_prefix_sets_post_response_instance = V1PolicyPrefixSetsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1PolicyPrefixSetsPostResponse.to_json())

# convert the object into a dict
v1_policy_prefix_sets_post_response_dict = v1_policy_prefix_sets_post_response_instance.to_dict()
# create an instance of V1PolicyPrefixSetsPostResponse from a dict
v1_policy_prefix_sets_post_response_from_dict = V1PolicyPrefixSetsPostResponse.from_dict(v1_policy_prefix_sets_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


