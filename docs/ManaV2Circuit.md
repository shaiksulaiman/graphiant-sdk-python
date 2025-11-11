# ManaV2Circuit


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bgp_aggregations** | [**List[ManaV2BgpAggregation]**](ManaV2BgpAggregation.md) |  | [optional] 
**bgp_multipath** | [**ManaV2BgpMultipath**](ManaV2BgpMultipath.md) |  | [optional] 
**bgp_neighbors** | [**List[ManaV2BgpNeighbor]**](ManaV2BgpNeighbor.md) |  | [optional] 
**bgp_redistributions** | [**ManaV2BgpRedistribute**](ManaV2BgpRedistribute.md) |  | [optional] 
**carrier** | **str** |  | [optional] 
**circuit_type** | **str** |  | [optional] 
**connection_type** | **str** |  | [optional] 
**core_logical_interfaces_v2** | [**List[ManaV2CircuitInterface]**](ManaV2CircuitInterface.md) |  | [optional] 
**description** | **str** |  | [optional] 
**dia_enabled** | **bool** |  | [optional] 
**dia_snmp_index** | **int** |  | [optional] 
**discovered_public_ip** | **str** |  | [optional] 
**drop_mechanism** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**interface_name** | **str** |  | [optional] 
**label** | **str** |  | [optional] 
**last_resort** | **bool** |  | [optional] 
**link_down_speed_mbps** | **int** |  | [optional] 
**link_up_speed_mbps** | **int** |  | [optional] 
**loopback** | **bool** |  | [optional] 
**name** | **str** |  | [optional] 
**pat_addresses** | **List[str]** |  | [optional] 
**private_ip** | **str** |  | [optional] 
**profile** | [**ManaV2QoSProfile**](ManaV2QoSProfile.md) |  | [optional] 
**qos_profile** | **str** |  | [optional] 
**qos_profile_type** | **str** |  | [optional] 
**snmp_index** | **int** |  | [optional] 
**static_routes** | [**List[ManaV2StaticRoute]**](ManaV2StaticRoute.md) |  | [optional] 
**wan_interface_v2** | [**ManaV2CircuitInterface**](ManaV2CircuitInterface.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_circuit import ManaV2Circuit

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2Circuit from a JSON string
mana_v2_circuit_instance = ManaV2Circuit.from_json(json)
# print the JSON string representation of the object
print(ManaV2Circuit.to_json())

# convert the object into a dict
mana_v2_circuit_dict = mana_v2_circuit_instance.to_dict()
# create an instance of ManaV2Circuit from a dict
mana_v2_circuit_from_dict = ManaV2Circuit.from_dict(mana_v2_circuit_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


