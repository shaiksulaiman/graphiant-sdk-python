# ManaV2CoreDeviceConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bgp_instance** | [**ManaV2BgpInstanceConfig**](ManaV2BgpInstanceConfig.md) |  | [optional] 
**core_vrf** | [**ManaV2VrfConfig**](ManaV2VrfConfig.md) |  | [optional] 
**interfaces** | [**Dict[str, ManaV2NullableInterfaceCoreConfig]**](ManaV2NullableInterfaceCoreConfig.md) |  | [optional] 
**ipfix_exporters** | [**Dict[str, ManaV2NullableIpfixExporterConfig]**](ManaV2NullableIpfixExporterConfig.md) |  | [optional] 
**isp_vrfs** | [**Dict[str, ManaV2VrfConfig]**](ManaV2VrfConfig.md) |  | [optional] 
**maintenance_mode** | **bool** |  | [optional] 
**name** | **str** |  | [optional] 
**prefix_sets** | [**Dict[str, ManaV2NullablePrefixSetConfig]**](ManaV2NullablePrefixSetConfig.md) |  | [optional] 
**prometheus** | [**ManaV2PrometheusConfig**](ManaV2PrometheusConfig.md) |  | [optional] 
**region** | **str** |  | [optional] 
**region_name** | **str** |  | [optional] 
**route_policies** | [**Dict[str, ManaV2NullableRoutingPolicyConfig]**](ManaV2NullableRoutingPolicyConfig.md) |  | [optional] 
**site** | [**ManaV2NewSite**](ManaV2NewSite.md) |  | [optional] 
**traffic_policy** | [**ManaV2ForwardingPolicyConfig**](ManaV2ForwardingPolicyConfig.md) |  | [optional] 
**vrfs** | [**Dict[str, ManaV2VrfConfig]**](ManaV2VrfConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_core_device_config import ManaV2CoreDeviceConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2CoreDeviceConfig from a JSON string
mana_v2_core_device_config_instance = ManaV2CoreDeviceConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2CoreDeviceConfig.to_json())

# convert the object into a dict
mana_v2_core_device_config_dict = mana_v2_core_device_config_instance.to_dict()
# create an instance of ManaV2CoreDeviceConfig from a dict
mana_v2_core_device_config_from_dict = ManaV2CoreDeviceConfig.from_dict(mana_v2_core_device_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


