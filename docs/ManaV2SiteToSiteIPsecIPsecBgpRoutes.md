# ManaV2SiteToSiteIPsecIPsecBgpRoutes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address_families** | [**List[ManaV2BgpNeighborAddressFamily]**](ManaV2BgpNeighborAddressFamily.md) |  | [optional] 
**hold_timer** | **int** |  | [optional] 
**keepalive_timer** | **int** |  | [optional] 
**md5_password** | **str** |  | [optional] 
**peer_asn** | **int** |  | [optional] 
**send_community** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_site_to_site_i_psec_i_psec_bgp_routes import ManaV2SiteToSiteIPsecIPsecBgpRoutes

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SiteToSiteIPsecIPsecBgpRoutes from a JSON string
mana_v2_site_to_site_i_psec_i_psec_bgp_routes_instance = ManaV2SiteToSiteIPsecIPsecBgpRoutes.from_json(json)
# print the JSON string representation of the object
print(ManaV2SiteToSiteIPsecIPsecBgpRoutes.to_json())

# convert the object into a dict
mana_v2_site_to_site_i_psec_i_psec_bgp_routes_dict = mana_v2_site_to_site_i_psec_i_psec_bgp_routes_instance.to_dict()
# create an instance of ManaV2SiteToSiteIPsecIPsecBgpRoutes from a dict
mana_v2_site_to_site_i_psec_i_psec_bgp_routes_from_dict = ManaV2SiteToSiteIPsecIPsecBgpRoutes.from_dict(mana_v2_site_to_site_i_psec_i_psec_bgp_routes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


