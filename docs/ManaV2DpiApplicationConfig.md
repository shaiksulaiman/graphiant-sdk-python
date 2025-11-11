# ManaV2DpiApplicationConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**destination_network** | **str** |  | [optional] 
**destination_network_list** | **str** |  | [optional] 
**destination_networks** | [**ManaV2IpNetworkListConfig**](ManaV2IpNetworkListConfig.md) |  | [optional] 
**destination_port** | **int** |  | [optional] 
**destination_port_list** | **str** |  | [optional] 
**destination_ports** | [**ManaV2L4PortListConfig**](ManaV2L4PortListConfig.md) |  | [optional] 
**icmp_type** | **int** |  | [optional] 
**ip_protocol** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**source_network** | **str** |  | [optional] 
**source_network_list** | **str** |  | [optional] 
**source_networks** | [**ManaV2IpNetworkListConfig**](ManaV2IpNetworkListConfig.md) |  | [optional] 
**source_port** | **int** |  | [optional] 
**source_port_list** | **str** |  | [optional] 
**source_ports** | [**ManaV2L4PortListConfig**](ManaV2L4PortListConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dpi_application_config import ManaV2DpiApplicationConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DpiApplicationConfig from a JSON string
mana_v2_dpi_application_config_instance = ManaV2DpiApplicationConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2DpiApplicationConfig.to_json())

# convert the object into a dict
mana_v2_dpi_application_config_dict = mana_v2_dpi_application_config_instance.to_dict()
# create an instance of ManaV2DpiApplicationConfig from a dict
mana_v2_dpi_application_config_from_dict = ManaV2DpiApplicationConfig.from_dict(mana_v2_dpi_application_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


