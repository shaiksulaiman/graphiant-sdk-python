# ManaV2DhcpSubnetConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**default_lease_time_secs** | **int** |  | [optional] 
**description** | **str** |  | [optional] 
**domain_name** | **str** |  | [optional] 
**domain_name_server** | [**ManaV2DhcpServerDnsParametersConfig**](ManaV2DhcpServerDnsParametersConfig.md) |  | [optional] 
**interface** | **str** |  | [optional] 
**ip_gateway** | **str** |  | [optional] 
**ip_prefix** | **str** |  | [optional] 
**ip_ranges** | [**List[ManaV2DhcpipRangeConfig]**](ManaV2DhcpipRangeConfig.md) |  | [optional] 
**ip_ranges_v2** | [**ManaV2NullableDhcpipRangeList**](ManaV2NullableDhcpipRangeList.md) |  | [optional] 
**max_lease_time_secs** | **int** |  | [optional] 
**min_lease_time_secs** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**static_leases** | [**Dict[str, ManaV2NullableDhcpSubnetStaticLeaseConfig]**](ManaV2NullableDhcpSubnetStaticLeaseConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dhcp_subnet_config import ManaV2DhcpSubnetConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DhcpSubnetConfig from a JSON string
mana_v2_dhcp_subnet_config_instance = ManaV2DhcpSubnetConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2DhcpSubnetConfig.to_json())

# convert the object into a dict
mana_v2_dhcp_subnet_config_dict = mana_v2_dhcp_subnet_config_instance.to_dict()
# create an instance of ManaV2DhcpSubnetConfig from a dict
mana_v2_dhcp_subnet_config_from_dict = ManaV2DhcpSubnetConfig.from_dict(mana_v2_dhcp_subnet_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


