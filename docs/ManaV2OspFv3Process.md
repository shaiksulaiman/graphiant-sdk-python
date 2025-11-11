# ManaV2OspFv3Process


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin_distance** | **int** | Administrative Distance for routes installed | [optional] 
**areas** | [**List[ManaV2OspfArea]**](ManaV2OspfArea.md) |  | [optional] 
**default_originate** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**redistributed_protocols** | [**List[ManaV2OspfRedistribute]**](ManaV2OspfRedistribute.md) |  | [optional] 
**router_id** | **str** |  | [optional] 
**version** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_osp_fv3_process import ManaV2OspFv3Process

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2OspFv3Process from a JSON string
mana_v2_osp_fv3_process_instance = ManaV2OspFv3Process.from_json(json)
# print the JSON string representation of the object
print(ManaV2OspFv3Process.to_json())

# convert the object into a dict
mana_v2_osp_fv3_process_dict = mana_v2_osp_fv3_process_instance.to_dict()
# create an instance of ManaV2OspFv3Process from a dict
mana_v2_osp_fv3_process_from_dict = ManaV2OspFv3Process.from_dict(mana_v2_osp_fv3_process_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


