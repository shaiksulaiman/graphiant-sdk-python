# ManaV2DhcpServerPool


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**default_lease_time_secs** | **int** |  | [optional] 
**description** | **str** |  | [optional] 
**domain_name** | **str** |  | [optional] 
**gateway** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**interface** | **str** |  | [optional] 
**ip_prefix** | **str** |  | [optional] 
**ip_version** | **int** |  | [optional] 
**leases** | [**List[ManaV2DhcpLease]**](ManaV2DhcpLease.md) |  | [optional] 
**max_lease_time_secs** | **int** |  | [optional] 
**min_lease_time_secs** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**nameservers** | [**ManaV2DnsServers**](ManaV2DnsServers.md) |  | [optional] 
**ranges** | [**List[ManaV2DhcpServerIpRange]**](ManaV2DhcpServerIpRange.md) |  | [optional] 
**static_leases** | [**List[ManaV2DhcpStaticLease]**](ManaV2DhcpStaticLease.md) |  | [optional] 
**total_addresses** | **int** |  | [optional] 
**utilization** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dhcp_server_pool import ManaV2DhcpServerPool

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DhcpServerPool from a JSON string
mana_v2_dhcp_server_pool_instance = ManaV2DhcpServerPool.from_json(json)
# print the JSON string representation of the object
print(ManaV2DhcpServerPool.to_json())

# convert the object into a dict
mana_v2_dhcp_server_pool_dict = mana_v2_dhcp_server_pool_instance.to_dict()
# create an instance of ManaV2DhcpServerPool from a dict
mana_v2_dhcp_server_pool_from_dict = ManaV2DhcpServerPool.from_dict(mana_v2_dhcp_server_pool_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


