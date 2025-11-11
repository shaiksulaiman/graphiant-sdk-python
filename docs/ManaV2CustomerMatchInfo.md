# ManaV2CustomerMatchInfo


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer_id** | **str** |  | [optional] 
**customer_name** | **str** |  | [optional] 
**emails** | **List[str]** |  | [optional] 
**match_id** | **int** |  | [optional] 
**matched_services** | **int** |  | [optional] 
**peer_type** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**updated_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_customer_match_info import ManaV2CustomerMatchInfo

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2CustomerMatchInfo from a JSON string
mana_v2_customer_match_info_instance = ManaV2CustomerMatchInfo.from_json(json)
# print the JSON string representation of the object
print(ManaV2CustomerMatchInfo.to_json())

# convert the object into a dict
mana_v2_customer_match_info_dict = mana_v2_customer_match_info_instance.to_dict()
# create an instance of ManaV2CustomerMatchInfo from a dict
mana_v2_customer_match_info_from_dict = ManaV2CustomerMatchInfo.from_dict(mana_v2_customer_match_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


