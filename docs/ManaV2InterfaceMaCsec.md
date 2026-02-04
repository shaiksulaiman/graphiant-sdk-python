# ManaV2InterfaceMaCsec


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**enabled** | **bool** |  | [optional] 
**encryption_enforcement_mode** | **str** |  | [optional] 
**key_server_priority** | **int** |  | [optional] 
**psk_configurations** | [**List[ManaV2PskConfiguration]**](ManaV2PskConfiguration.md) |  | [optional] 
**sak_configurations** | [**List[ManaV2SakConfiguration]**](ManaV2SakConfiguration.md) |  | [optional] 
**split_sak_config_by_lag_member** | **bool** |  | [optional] 
**transparent_vlan** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_interface_ma_csec import ManaV2InterfaceMaCsec

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2InterfaceMaCsec from a JSON string
mana_v2_interface_ma_csec_instance = ManaV2InterfaceMaCsec.from_json(json)
# print the JSON string representation of the object
print(ManaV2InterfaceMaCsec.to_json())

# convert the object into a dict
mana_v2_interface_ma_csec_dict = mana_v2_interface_ma_csec_instance.to_dict()
# create an instance of ManaV2InterfaceMaCsec from a dict
mana_v2_interface_ma_csec_from_dict = ManaV2InterfaceMaCsec.from_dict(mana_v2_interface_ma_csec_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


