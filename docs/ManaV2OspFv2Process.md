# ManaV2OspFv2Process


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin_distance** | **int** | Administrative Distance for routes installed | [optional] 
**areas** | [**List[ManaV2OspfArea]**](ManaV2OspfArea.md) |  | [optional] 
**auto_router_id** | **bool** |  | [optional] 
**default_originate** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**redistributed_protocols** | [**List[ManaV2OspfRedistribute]**](ManaV2OspfRedistribute.md) |  | [optional] 
**router_id** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_osp_fv2_process import ManaV2OspFv2Process

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2OspFv2Process from a JSON string
mana_v2_osp_fv2_process_instance = ManaV2OspFv2Process.from_json(json)
# print the JSON string representation of the object
print(ManaV2OspFv2Process.to_json())

# convert the object into a dict
mana_v2_osp_fv2_process_dict = mana_v2_osp_fv2_process_instance.to_dict()
# create an instance of ManaV2OspFv2Process from a dict
mana_v2_osp_fv2_process_from_dict = ManaV2OspFv2Process.from_dict(mana_v2_osp_fv2_process_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


