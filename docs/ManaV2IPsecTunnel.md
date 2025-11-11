# ManaV2IPsecTunnel


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination_address** | **str** |  | [optional] 
**ike_initiator** | **bool** |  | [optional] 
**ipsec_label** | **str** |  | [optional] 
**lan** | **str** |  | [optional] 
**local_address_v4** | **str** |  | [optional] 
**local_address_v6** | **str** |  | [optional] 
**local_circuit** | **str** |  | [optional] 
**local_ike_peer_identity** | **str** |  | [optional] 
**mtu** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**preshared_key** | **str** |  | [optional] 
**remote_address_v4** | **str** |  | [optional] 
**remote_address_v6** | **str** |  | [optional] 
**remote_ike_peer_identity** | **str** |  | [optional] 
**routing** | [**ManaV2IpsecRoutingConfig**](ManaV2IpsecRoutingConfig.md) |  | [optional] 
**tcp_mss** | **int** |  | [optional] 
**vpn_profile** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_i_psec_tunnel import ManaV2IPsecTunnel

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2IPsecTunnel from a JSON string
mana_v2_i_psec_tunnel_instance = ManaV2IPsecTunnel.from_json(json)
# print the JSON string representation of the object
print(ManaV2IPsecTunnel.to_json())

# convert the object into a dict
mana_v2_i_psec_tunnel_dict = mana_v2_i_psec_tunnel_instance.to_dict()
# create an instance of ManaV2IPsecTunnel from a dict
mana_v2_i_psec_tunnel_from_dict = ManaV2IPsecTunnel.from_dict(mana_v2_i_psec_tunnel_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


