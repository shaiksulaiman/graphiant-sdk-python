# ManaV2QoSProfile


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**kind** | **str** |  | [optional] 
**profile** | **str** |  | [optional] 
**queues** | [**List[ManaV2QoSProfileQueue]**](ManaV2QoSProfileQueue.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_qo_s_profile import ManaV2QoSProfile

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2QoSProfile from a JSON string
mana_v2_qo_s_profile_instance = ManaV2QoSProfile.from_json(json)
# print the JSON string representation of the object
print(ManaV2QoSProfile.to_json())

# convert the object into a dict
mana_v2_qo_s_profile_dict = mana_v2_qo_s_profile_instance.to_dict()
# create an instance of ManaV2QoSProfile from a dict
mana_v2_qo_s_profile_from_dict = ManaV2QoSProfile.from_dict(mana_v2_qo_s_profile_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


