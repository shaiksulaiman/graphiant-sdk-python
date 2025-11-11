# V1GatewaysGuestConsumerMatchIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination_prefixes** | **List[str]** |  | [optional] 
**ipsec_tunnel_config** | [**List[V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig]**](V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig.md) |  | [optional] 
**site_to_site_vpn** | [**ManaV2GuestConsumerSiteToSiteVpnConfig**](ManaV2GuestConsumerSiteToSiteVpnConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_gateways_guest_consumer_match_id_get_response import V1GatewaysGuestConsumerMatchIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GatewaysGuestConsumerMatchIdGetResponse from a JSON string
v1_gateways_guest_consumer_match_id_get_response_instance = V1GatewaysGuestConsumerMatchIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GatewaysGuestConsumerMatchIdGetResponse.to_json())

# convert the object into a dict
v1_gateways_guest_consumer_match_id_get_response_dict = v1_gateways_guest_consumer_match_id_get_response_instance.to_dict()
# create an instance of V1GatewaysGuestConsumerMatchIdGetResponse from a dict
v1_gateways_guest_consumer_match_id_get_response_from_dict = V1GatewaysGuestConsumerMatchIdGetResponse.from_dict(v1_gateways_guest_consumer_match_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


