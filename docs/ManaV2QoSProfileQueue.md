# ManaV2QoSProfileQueue


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bandwidth_percent** | **int** |  | [optional] 
**default_queue** | **bool** |  | [optional] 
**sla_class** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_qo_s_profile_queue import ManaV2QoSProfileQueue

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2QoSProfileQueue from a JSON string
mana_v2_qo_s_profile_queue_instance = ManaV2QoSProfileQueue.from_json(json)
# print the JSON string representation of the object
print(ManaV2QoSProfileQueue.to_json())

# convert the object into a dict
mana_v2_qo_s_profile_queue_dict = mana_v2_qo_s_profile_queue_instance.to_dict()
# create an instance of ManaV2QoSProfileQueue from a dict
mana_v2_qo_s_profile_queue_from_dict = ManaV2QoSProfileQueue.from_dict(mana_v2_qo_s_profile_queue_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


