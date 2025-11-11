# ManaV2IPsecGatewayDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination_address** | **str** |  | [optional] 
**ike_initiator** | **bool** |  | [optional] 
**mtu** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**remote_ike_peer_identity** | **str** |  | [optional] 
**routing** | [**ManaV2IpsecRoutingConfig**](ManaV2IpsecRoutingConfig.md) |  | [optional] 
**tcp_mss** | **int** |  | [optional] 
**tunnel1** | [**ManaV2IPsecGatewayTunnelDetails**](ManaV2IPsecGatewayTunnelDetails.md) |  | [optional] 
**tunnel2** | [**ManaV2IPsecGatewayTunnelDetails**](ManaV2IPsecGatewayTunnelDetails.md) |  | [optional] 
**vpn_profile** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_i_psec_gateway_details import ManaV2IPsecGatewayDetails

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2IPsecGatewayDetails from a JSON string
mana_v2_i_psec_gateway_details_instance = ManaV2IPsecGatewayDetails.from_json(json)
# print the JSON string representation of the object
print(ManaV2IPsecGatewayDetails.to_json())

# convert the object into a dict
mana_v2_i_psec_gateway_details_dict = mana_v2_i_psec_gateway_details_instance.to_dict()
# create an instance of ManaV2IPsecGatewayDetails from a dict
mana_v2_i_psec_gateway_details_from_dict = ManaV2IPsecGatewayDetails.from_dict(mana_v2_i_psec_gateway_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


