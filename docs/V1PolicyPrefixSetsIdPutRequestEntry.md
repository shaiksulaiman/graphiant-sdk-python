# V1PolicyPrefixSetsIdPutRequestEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ip_prefix** | **str** |  | [optional] 
**mask_lower** | **int** |  | [optional] 
**mask_upper** | **int** |  | [optional] 
**seq** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_policy_prefix_sets_id_put_request_entry import V1PolicyPrefixSetsIdPutRequestEntry

# TODO update the JSON string below
json = "{}"
# create an instance of V1PolicyPrefixSetsIdPutRequestEntry from a JSON string
v1_policy_prefix_sets_id_put_request_entry_instance = V1PolicyPrefixSetsIdPutRequestEntry.from_json(json)
# print the JSON string representation of the object
print(V1PolicyPrefixSetsIdPutRequestEntry.to_json())

# convert the object into a dict
v1_policy_prefix_sets_id_put_request_entry_dict = v1_policy_prefix_sets_id_put_request_entry_instance.to_dict()
# create an instance of V1PolicyPrefixSetsIdPutRequestEntry from a dict
v1_policy_prefix_sets_id_put_request_entry_from_dict = V1PolicyPrefixSetsIdPutRequestEntry.from_dict(v1_policy_prefix_sets_id_put_request_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


