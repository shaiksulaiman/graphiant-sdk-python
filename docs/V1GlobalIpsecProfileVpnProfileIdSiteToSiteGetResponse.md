# V1GlobalIpsecProfileVpnProfileIdSiteToSiteGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**site_to_site_vpn** | [**List[V1GlobalIpsecProfileVpnProfileIdSiteToSiteGetResponseSiteToSiteVpn]**](V1GlobalIpsecProfileVpnProfileIdSiteToSiteGetResponseSiteToSiteVpn.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_ipsec_profile_vpn_profile_id_site_to_site_get_response import V1GlobalIpsecProfileVpnProfileIdSiteToSiteGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalIpsecProfileVpnProfileIdSiteToSiteGetResponse from a JSON string
v1_global_ipsec_profile_vpn_profile_id_site_to_site_get_response_instance = V1GlobalIpsecProfileVpnProfileIdSiteToSiteGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalIpsecProfileVpnProfileIdSiteToSiteGetResponse.to_json())

# convert the object into a dict
v1_global_ipsec_profile_vpn_profile_id_site_to_site_get_response_dict = v1_global_ipsec_profile_vpn_profile_id_site_to_site_get_response_instance.to_dict()
# create an instance of V1GlobalIpsecProfileVpnProfileIdSiteToSiteGetResponse from a dict
v1_global_ipsec_profile_vpn_profile_id_site_to_site_get_response_from_dict = V1GlobalIpsecProfileVpnProfileIdSiteToSiteGetResponse.from_dict(v1_global_ipsec_profile_vpn_profile_id_site_to_site_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


