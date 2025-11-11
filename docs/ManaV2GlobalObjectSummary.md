# ManaV2GlobalObjectSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attach_point** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**ip_version** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**num_attached_devices** | **int** |  | [optional] 
**num_attached_sites** | **int** |  | [optional] 
**num_failures** | **int** |  | [optional] 
**num_in_sync_devices** | **int** |  | [optional] 
**num_override_devices** | **int** |  | [optional] 
**num_policies** | **int** |  | [optional] 
**num_prefixes** | **int** |  | [optional] 
**num_rules** | **int** |  | [optional] 
**num_statements** | **int** |  | [optional] 
**traffic_policy_type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_global_object_summary import ManaV2GlobalObjectSummary

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2GlobalObjectSummary from a JSON string
mana_v2_global_object_summary_instance = ManaV2GlobalObjectSummary.from_json(json)
# print the JSON string representation of the object
print(ManaV2GlobalObjectSummary.to_json())

# convert the object into a dict
mana_v2_global_object_summary_dict = mana_v2_global_object_summary_instance.to_dict()
# create an instance of ManaV2GlobalObjectSummary from a dict
mana_v2_global_object_summary_from_dict = ManaV2GlobalObjectSummary.from_dict(mana_v2_global_object_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


