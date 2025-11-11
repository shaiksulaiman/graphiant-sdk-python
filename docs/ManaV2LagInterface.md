# ManaV2LagInterface


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**lacp_config** | [**ManaV2LacpConfig**](ManaV2LacpConfig.md) |  | [optional] 
**members** | **List[int]** |  | [optional] 
**minimum_members** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_lag_interface import ManaV2LagInterface

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2LagInterface from a JSON string
mana_v2_lag_interface_instance = ManaV2LagInterface.from_json(json)
# print the JSON string representation of the object
print(ManaV2LagInterface.to_json())

# convert the object into a dict
mana_v2_lag_interface_dict = mana_v2_lag_interface_instance.to_dict()
# create an instance of ManaV2LagInterface from a dict
mana_v2_lag_interface_from_dict = ManaV2LagInterface.from_dict(mana_v2_lag_interface_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


