# ManaV2CircuitConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bgp_aggregations** | [**Dict[str, ManaV2NullableBgpAggregationsConfig]**](ManaV2NullableBgpAggregationsConfig.md) |  | [optional] 
**bgp_multipath** | [**ManaV2NullableBgpMultipathConfig**](ManaV2NullableBgpMultipathConfig.md) |  | [optional] 
**bgp_neighbors** | [**Dict[str, ManaV2NullableBgpNeighborConfig]**](ManaV2NullableBgpNeighborConfig.md) |  | [optional] 
**bgp_redistribution** | [**Dict[str, ManaV2NullableBgpRedistributeProtocolConfig]**](ManaV2NullableBgpRedistributeProtocolConfig.md) |  | [optional] 
**carrier** | **str** |  | [optional] 
**circuit_type** | **str** |  | [optional] 
**connection_type** | **str** |  | [optional] 
**description** | **str** |  | [optional] 
**dia_enabled** | **bool** |  | [optional] 
**drop_mechanism** | **str** |  | [optional] 
**label** | **str** |  | [optional] 
**last_resort** | **bool** |  | [optional] 
**link_down_speed_mbps** | **int** |  | [optional] 
**link_up_speed_mbps** | **int** |  | [optional] 
**loopback** | **bool** |  | [optional] 
**name** | **str** |  | [optional] 
**pat_addresses** | [**ManaV2NullableIpList**](ManaV2NullableIpList.md) |  | [optional] 
**qos_profile** | **str** |  | [optional] 
**qos_profile_type** | **str** |  | [optional] 
**static_routes** | [**Dict[str, ManaV2NullableStaticRouteConfig]**](ManaV2NullableStaticRouteConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_circuit_config import ManaV2CircuitConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2CircuitConfig from a JSON string
mana_v2_circuit_config_instance = ManaV2CircuitConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2CircuitConfig.to_json())

# convert the object into a dict
mana_v2_circuit_config_dict = mana_v2_circuit_config_instance.to_dict()
# create an instance of ManaV2CircuitConfig from a dict
mana_v2_circuit_config_from_dict = ManaV2CircuitConfig.from_dict(mana_v2_circuit_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


