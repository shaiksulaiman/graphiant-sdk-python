# ManaV2DhcpRelayConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**relay_servers** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dhcp_relay_config import ManaV2DhcpRelayConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DhcpRelayConfig from a JSON string
mana_v2_dhcp_relay_config_instance = ManaV2DhcpRelayConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2DhcpRelayConfig.to_json())

# convert the object into a dict
mana_v2_dhcp_relay_config_dict = mana_v2_dhcp_relay_config_instance.to_dict()
# create an instance of ManaV2DhcpRelayConfig from a dict
mana_v2_dhcp_relay_config_from_dict = ManaV2DhcpRelayConfig.from_dict(mana_v2_dhcp_relay_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


