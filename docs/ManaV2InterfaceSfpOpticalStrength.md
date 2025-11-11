# ManaV2InterfaceSfpOpticalStrength


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**index** | **int** |  | [optional] 
**rx_power** | **float** |  | [optional] 
**tx_bias** | **float** |  | [optional] 
**tx_power** | **float** |  | [optional] 
**voltage** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_interface_sfp_optical_strength import ManaV2InterfaceSfpOpticalStrength

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2InterfaceSfpOpticalStrength from a JSON string
mana_v2_interface_sfp_optical_strength_instance = ManaV2InterfaceSfpOpticalStrength.from_json(json)
# print the JSON string representation of the object
print(ManaV2InterfaceSfpOpticalStrength.to_json())

# convert the object into a dict
mana_v2_interface_sfp_optical_strength_dict = mana_v2_interface_sfp_optical_strength_instance.to_dict()
# create an instance of ManaV2InterfaceSfpOpticalStrength from a dict
mana_v2_interface_sfp_optical_strength_from_dict = ManaV2InterfaceSfpOpticalStrength.from_dict(mana_v2_interface_sfp_optical_strength_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


