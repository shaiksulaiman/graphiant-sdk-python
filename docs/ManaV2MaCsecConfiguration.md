# ManaV2MaCsecConfiguration


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**enabled** | **bool** | Whether MACsec is enabled or disabled (required) | 
**encryption_enforcement_mode** | **str** | The encryption enforcement mode (required) | 
**global_sak_configuration** | [**ManaV2NullableSakConfiguration**](ManaV2NullableSakConfiguration.md) |  | 
**key_server_priority** | **int** | The priority of the key server. Lower number means higher priority. | [optional] 
**psk_configurations** | [**List[ManaV2PskConfiguration]**](ManaV2PskConfiguration.md) |  | [optional] 
**psk_configurations_by_nickname** | [**Dict[str, ManaV2NullablePskConfiguration]**](ManaV2NullablePskConfiguration.md) |  | 
**sak_configurations** | [**List[ManaV2SakConfiguration]**](ManaV2SakConfiguration.md) |  | [optional] 
**sak_configurations_by_lag_member_interface_id** | [**Dict[str, ManaV2NullableSakConfiguration]**](ManaV2NullableSakConfiguration.md) |  | 
**split_sak_config_by_lag_member** | **bool** | Whether to allow individual SAK configurations for each lag member | [optional] 
**transparent_vlan** | **bool** | Whether transparent VLAN is enabled or disabled | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_ma_csec_configuration import ManaV2MaCsecConfiguration

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2MaCsecConfiguration from a JSON string
mana_v2_ma_csec_configuration_instance = ManaV2MaCsecConfiguration.from_json(json)
# print the JSON string representation of the object
print(ManaV2MaCsecConfiguration.to_json())

# convert the object into a dict
mana_v2_ma_csec_configuration_dict = mana_v2_ma_csec_configuration_instance.to_dict()
# create an instance of ManaV2MaCsecConfiguration from a dict
mana_v2_ma_csec_configuration_from_dict = ManaV2MaCsecConfiguration.from_dict(mana_v2_ma_csec_configuration_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


