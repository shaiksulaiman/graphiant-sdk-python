# ManaV2RegionalAllocation


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**allocation_core** | **float** | Gigabytes per second allowed for core network connections on this region | [optional] 
**allocation_gw** | **float** | Gigabytes per second allowed for gateway connections on this region | [optional] 
**allocation_internet** | **float** | Gigabytes per second allowed for dia gateway internet access on this region. Must be 0, 10, or 100 | [optional] 
**credit_core** | **float** |  | [optional] 
**credit_gw** | **float** |  | [optional] 
**region_id** | **int** |  | [optional] 
**region_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_regional_allocation import ManaV2RegionalAllocation

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2RegionalAllocation from a JSON string
mana_v2_regional_allocation_instance = ManaV2RegionalAllocation.from_json(json)
# print the JSON string representation of the object
print(ManaV2RegionalAllocation.to_json())

# convert the object into a dict
mana_v2_regional_allocation_dict = mana_v2_regional_allocation_instance.to_dict()
# create an instance of ManaV2RegionalAllocation from a dict
mana_v2_regional_allocation_from_dict = ManaV2RegionalAllocation.from_dict(mana_v2_regional_allocation_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


