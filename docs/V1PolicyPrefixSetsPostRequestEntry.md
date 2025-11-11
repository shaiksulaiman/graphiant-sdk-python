# V1PolicyPrefixSetsPostRequestEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ip_prefix** | **str** |  | [optional] 
**mask_lower** | **int** |  | [optional] 
**mask_upper** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_policy_prefix_sets_post_request_entry import V1PolicyPrefixSetsPostRequestEntry

# TODO update the JSON string below
json = "{}"
# create an instance of V1PolicyPrefixSetsPostRequestEntry from a JSON string
v1_policy_prefix_sets_post_request_entry_instance = V1PolicyPrefixSetsPostRequestEntry.from_json(json)
# print the JSON string representation of the object
print(V1PolicyPrefixSetsPostRequestEntry.to_json())

# convert the object into a dict
v1_policy_prefix_sets_post_request_entry_dict = v1_policy_prefix_sets_post_request_entry_instance.to_dict()
# create an instance of V1PolicyPrefixSetsPostRequestEntry from a dict
v1_policy_prefix_sets_post_request_entry_from_dict = V1PolicyPrefixSetsPostRequestEntry.from_dict(v1_policy_prefix_sets_post_request_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


