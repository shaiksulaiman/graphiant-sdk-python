# ManaV2Consumer


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**vrfs** | **List[int]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_consumer import ManaV2Consumer

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2Consumer from a JSON string
mana_v2_consumer_instance = ManaV2Consumer.from_json(json)
# print the JSON string representation of the object
print(ManaV2Consumer.to_json())

# convert the object into a dict
mana_v2_consumer_dict = mana_v2_consumer_instance.to_dict()
# create an instance of ManaV2Consumer from a dict
mana_v2_consumer_from_dict = ManaV2Consumer.from_dict(mana_v2_consumer_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


