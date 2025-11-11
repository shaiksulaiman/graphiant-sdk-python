# ManaV2NetworkSlicePeer


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bgp_connection** | [**ManaV2BgpConnection**](ManaV2BgpConnection.md) |  | [optional] 
**connection_quality** | **str** |  | [optional] 
**device_id** | **int** |  | [optional] 
**gdi** | **int** |  | [optional] 
**hostname** | **str** |  | [optional] 
**ipsec_connection** | [**ManaV2InterfaceTunnel**](ManaV2InterfaceTunnel.md) |  | [optional] 
**state** | **str** |  | [optional] 
**wan_addresses** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_network_slice_peer import ManaV2NetworkSlicePeer

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2NetworkSlicePeer from a JSON string
mana_v2_network_slice_peer_instance = ManaV2NetworkSlicePeer.from_json(json)
# print the JSON string representation of the object
print(ManaV2NetworkSlicePeer.to_json())

# convert the object into a dict
mana_v2_network_slice_peer_dict = mana_v2_network_slice_peer_instance.to_dict()
# create an instance of ManaV2NetworkSlicePeer from a dict
mana_v2_network_slice_peer_from_dict = ManaV2NetworkSlicePeer.from_dict(mana_v2_network_slice_peer_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


