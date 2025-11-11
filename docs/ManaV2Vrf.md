# ManaV2Vrf


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bgp_aggregations** | [**List[ManaV2BgpAggregation]**](ManaV2BgpAggregation.md) |  | [optional] 
**bgp_multipath** | [**ManaV2BgpMultipath**](ManaV2BgpMultipath.md) |  | [optional] 
**bgp_neighbors** | [**List[ManaV2BgpNeighbor]**](ManaV2BgpNeighbor.md) |  | [optional] 
**bgp_redistributions** | [**ManaV2BgpRedistribute**](ManaV2BgpRedistribute.md) |  | [optional] 
**description** | **str** |  | [optional] 
**dhcp_subnets** | [**List[ManaV2DhcpServerPool]**](ManaV2DhcpServerPool.md) |  | [optional] 
**enterprise_id** | **int** |  | [optional] 
**function** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**ipfix_exporters** | [**List[ManaV2IpfixExporter]**](ManaV2IpfixExporter.md) |  | [optional] 
**name** | **str** |  | [optional] 
**nat_ruleset** | **str** |  | [optional] 
**networks** | **List[str]** |  | [optional] 
**ospfv2_process** | [**ManaV2OspFv2Process**](ManaV2OspFv2Process.md) |  | [optional] 
**ospfv3_process** | [**ManaV2OspFv3Process**](ManaV2OspFv3Process.md) |  | [optional] 
**overlay_filters** | [**ManaV2OverlayFilters**](ManaV2OverlayFilters.md) |  | [optional] 
**routable** | **bool** |  | [optional] 
**route_distinguisher** | **str** |  | [optional] 
**static_routes** | [**List[ManaV2StaticRoute]**](ManaV2StaticRoute.md) |  | [optional] 
**syslog_targets** | [**List[ManaV2SyslogCollector]**](ManaV2SyslogCollector.md) |  | [optional] 
**traffic_ruleset** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_vrf import ManaV2Vrf

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2Vrf from a JSON string
mana_v2_vrf_instance = ManaV2Vrf.from_json(json)
# print the JSON string representation of the object
print(ManaV2Vrf.to_json())

# convert the object into a dict
mana_v2_vrf_dict = mana_v2_vrf_instance.to_dict()
# create an instance of ManaV2Vrf from a dict
mana_v2_vrf_from_dict = ManaV2Vrf.from_dict(mana_v2_vrf_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


