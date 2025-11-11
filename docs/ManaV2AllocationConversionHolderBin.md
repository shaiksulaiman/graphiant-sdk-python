# ManaV2AllocationConversionHolderBin


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**allocation_upper_bound** | **float** | Int32 value indicating the conversion rates apply from the prior highest upper bound to this upper bound | [optional] 
**core_conversion_factor** | **float** | Conversion rate from gigabytes per second to Graphiant credits for connections to core devices | [optional] 
**core_conversion_rate** | **int** |  | [optional] 
**gw_conversion_factor** | **float** | Conversion rate from gigabytes per second to Graphiant credits for connections to gateway devices | [optional] 
**gw_conversion_rate** | **int** |  | [optional] 
**is_private** | **bool** | True-only flag indicating the conversion rates apply within a private context such as in-country | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_allocation_conversion_holder_bin import ManaV2AllocationConversionHolderBin

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2AllocationConversionHolderBin from a JSON string
mana_v2_allocation_conversion_holder_bin_instance = ManaV2AllocationConversionHolderBin.from_json(json)
# print the JSON string representation of the object
print(ManaV2AllocationConversionHolderBin.to_json())

# convert the object into a dict
mana_v2_allocation_conversion_holder_bin_dict = mana_v2_allocation_conversion_holder_bin_instance.to_dict()
# create an instance of ManaV2AllocationConversionHolderBin from a dict
mana_v2_allocation_conversion_holder_bin_from_dict = ManaV2AllocationConversionHolderBin.from_dict(mana_v2_allocation_conversion_holder_bin_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


