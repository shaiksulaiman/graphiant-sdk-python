# ManaV2DhcpServerDnsParametersConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**primary** | **str** |  | [optional] 
**secondary** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dhcp_server_dns_parameters_config import ManaV2DhcpServerDnsParametersConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DhcpServerDnsParametersConfig from a JSON string
mana_v2_dhcp_server_dns_parameters_config_instance = ManaV2DhcpServerDnsParametersConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2DhcpServerDnsParametersConfig.to_json())

# convert the object into a dict
mana_v2_dhcp_server_dns_parameters_config_dict = mana_v2_dhcp_server_dns_parameters_config_instance.to_dict()
# create an instance of ManaV2DhcpServerDnsParametersConfig from a dict
mana_v2_dhcp_server_dns_parameters_config_from_dict = ManaV2DhcpServerDnsParametersConfig.from_dict(mana_v2_dhcp_server_dns_parameters_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


