# V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**consumer_id** | **int** |  | [optional] 
**consumer_name** | **str** |  | [optional] 
**emails** | **List[str]** |  | [optional] 
**global_object_device_summaries** | [**Dict[str, ManaV2GlobalObjectServiceSummaries]**](ManaV2GlobalObjectServiceSummaries.md) |  | [optional] 
**global_object_summaries** | [**Dict[str, ManaV2GlobalObjectServiceSummaries]**](ManaV2GlobalObjectServiceSummaries.md) |  | [optional] 
**ipsec_tunnel_config** | [**List[V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponseIpsecVpnTunnelConfig]**](V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponseIpsecVpnTunnelConfig.md) |  | [optional] 
**match_details** | [**ManaV2B2bExtranetServiceCustomerMatchDetails**](ManaV2B2bExtranetServiceCustomerMatchDetails.md) |  | [optional] 
**peer_type** | **str** |  | [optional] 
**policy** | [**List[ManaV2B2bExtranetPeeringServiceConsumerLanSegmentPolicy]**](ManaV2B2bExtranetPeeringServiceConsumerLanSegmentPolicy.md) |  | [optional] 
**site_information** | [**List[ManaV2B2bSiteInformation]**](ManaV2B2bSiteInformation.md) |  | [optional] 
**site_to_site_vpn** | [**ManaV2GuestConsumerSiteToSiteVpnConfig**](ManaV2GuestConsumerSiteToSiteVpnConfig.md) |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get_response import V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse from a JSON string
v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get_response_instance = V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get_response_dict = v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get_response_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse from a dict
v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get_response_from_dict = V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse.from_dict(v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


