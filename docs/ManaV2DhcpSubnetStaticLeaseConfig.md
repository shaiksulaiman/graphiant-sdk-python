# ManaV2DhcpSubnetStaticLeaseConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**hostname** | **str** |  | [optional] 
**ip_address** | **str** |  | [optional] 
**mac_address** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dhcp_subnet_static_lease_config import ManaV2DhcpSubnetStaticLeaseConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DhcpSubnetStaticLeaseConfig from a JSON string
mana_v2_dhcp_subnet_static_lease_config_instance = ManaV2DhcpSubnetStaticLeaseConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2DhcpSubnetStaticLeaseConfig.to_json())

# convert the object into a dict
mana_v2_dhcp_subnet_static_lease_config_dict = mana_v2_dhcp_subnet_static_lease_config_instance.to_dict()
# create an instance of ManaV2DhcpSubnetStaticLeaseConfig from a dict
mana_v2_dhcp_subnet_static_lease_config_from_dict = ManaV2DhcpSubnetStaticLeaseConfig.from_dict(mana_v2_dhcp_subnet_static_lease_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


