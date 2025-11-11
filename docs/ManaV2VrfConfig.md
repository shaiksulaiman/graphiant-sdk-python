# ManaV2VrfConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bgp_aggregations** | [**Dict[str, ManaV2NullableBgpAggregationsConfig]**](ManaV2NullableBgpAggregationsConfig.md) |  | [optional] 
**bgp_neighbors** | [**Dict[str, ManaV2NullableBgpNeighborConfig]**](ManaV2NullableBgpNeighborConfig.md) |  | [optional] 
**bgp_redistribution** | [**Dict[str, ManaV2NullableBgpRedistributeProtocolConfig]**](ManaV2NullableBgpRedistributeProtocolConfig.md) |  | [optional] 
**dhcp_subnets** | [**Dict[str, ManaV2NullableDhcpSubnetConfig]**](ManaV2NullableDhcpSubnetConfig.md) |  | [optional] 
**ebgp_multipath** | [**ManaV2NullableBgpMultipathConfig**](ManaV2NullableBgpMultipathConfig.md) |  | [optional] 
**ipfix_exporters** | [**Dict[str, ManaV2NullableIpfixExporterConfig]**](ManaV2NullableIpfixExporterConfig.md) |  | [optional] 
**nat_ruleset** | [**ManaV2NullableNatPolicyRulesetName**](ManaV2NullableNatPolicyRulesetName.md) |  | [optional] 
**networks** | **List[str]** |  | [optional] 
**ospfv2** | [**ManaV2NullableOspfProcessConfig**](ManaV2NullableOspfProcessConfig.md) |  | [optional] 
**ospfv3** | [**ManaV2NullableOspfProcessConfig**](ManaV2NullableOspfProcessConfig.md) |  | [optional] 
**overlay_filters** | [**ManaV2OverlayFilterConfig**](ManaV2OverlayFilterConfig.md) |  | [optional] 
**static_routes** | [**Dict[str, ManaV2NullableStaticRouteConfig]**](ManaV2NullableStaticRouteConfig.md) |  | [optional] 
**syslog_targets** | [**Dict[str, ManaV2NullableSyslogCollectorConfig]**](ManaV2NullableSyslogCollectorConfig.md) |  | [optional] 
**traffic_ruleset** | [**ManaV2NullableTrafficPolicyRulesetName**](ManaV2NullableTrafficPolicyRulesetName.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_vrf_config import ManaV2VrfConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2VrfConfig from a JSON string
mana_v2_vrf_config_instance = ManaV2VrfConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2VrfConfig.to_json())

# convert the object into a dict
mana_v2_vrf_config_dict = mana_v2_vrf_config_instance.to_dict()
# create an instance of ManaV2VrfConfig from a dict
mana_v2_vrf_config_from_dict = ManaV2VrfConfig.from_dict(mana_v2_vrf_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


