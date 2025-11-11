# ManaV2OspfRedistribute


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**metric** | **int** |  | [optional] 
**metric_type** | **str** |  | [optional] 
**redist_type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_ospf_redistribute import ManaV2OspfRedistribute

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2OspfRedistribute from a JSON string
mana_v2_ospf_redistribute_instance = ManaV2OspfRedistribute.from_json(json)
# print the JSON string representation of the object
print(ManaV2OspfRedistribute.to_json())

# convert the object into a dict
mana_v2_ospf_redistribute_dict = mana_v2_ospf_redistribute_instance.to_dict()
# create an instance of ManaV2OspfRedistribute from a dict
mana_v2_ospf_redistribute_from_dict = ManaV2OspfRedistribute.from_dict(mana_v2_ospf_redistribute_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


