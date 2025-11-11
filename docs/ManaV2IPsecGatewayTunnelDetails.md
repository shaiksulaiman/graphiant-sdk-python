# ManaV2IPsecGatewayTunnelDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**inside_ipv4_cidr** | **str** |  | [optional] 
**inside_ipv6_cidr** | **str** |  | [optional] 
**local_ike_peer_identity** | **str** |  | [optional] 
**psk** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_i_psec_gateway_tunnel_details import ManaV2IPsecGatewayTunnelDetails

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2IPsecGatewayTunnelDetails from a JSON string
mana_v2_i_psec_gateway_tunnel_details_instance = ManaV2IPsecGatewayTunnelDetails.from_json(json)
# print the JSON string representation of the object
print(ManaV2IPsecGatewayTunnelDetails.to_json())

# convert the object into a dict
mana_v2_i_psec_gateway_tunnel_details_dict = mana_v2_i_psec_gateway_tunnel_details_instance.to_dict()
# create an instance of ManaV2IPsecGatewayTunnelDetails from a dict
mana_v2_i_psec_gateway_tunnel_details_from_dict = ManaV2IPsecGatewayTunnelDetails.from_dict(mana_v2_i_psec_gateway_tunnel_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


