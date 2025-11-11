# V1PolicyPrefixSetsPostRequestPrefixSetEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ip_prefix** | **str** |  | [optional] 
**mask_lower** | **int** |  | [optional] 
**mask_upper** | **int** |  | [optional] 
**seq** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_policy_prefix_sets_post_request_prefix_set_entry import V1PolicyPrefixSetsPostRequestPrefixSetEntry

# TODO update the JSON string below
json = "{}"
# create an instance of V1PolicyPrefixSetsPostRequestPrefixSetEntry from a JSON string
v1_policy_prefix_sets_post_request_prefix_set_entry_instance = V1PolicyPrefixSetsPostRequestPrefixSetEntry.from_json(json)
# print the JSON string representation of the object
print(V1PolicyPrefixSetsPostRequestPrefixSetEntry.to_json())

# convert the object into a dict
v1_policy_prefix_sets_post_request_prefix_set_entry_dict = v1_policy_prefix_sets_post_request_prefix_set_entry_instance.to_dict()
# create an instance of V1PolicyPrefixSetsPostRequestPrefixSetEntry from a dict
v1_policy_prefix_sets_post_request_prefix_set_entry_from_dict = V1PolicyPrefixSetsPostRequestPrefixSetEntry.from_dict(v1_policy_prefix_sets_post_request_prefix_set_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


