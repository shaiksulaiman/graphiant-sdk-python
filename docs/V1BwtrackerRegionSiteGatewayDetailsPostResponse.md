# V1BwtrackerRegionSiteGatewayDetailsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bwusage_details** | [**StatsmonBandwidthtrackerBwUsageBySiteDetails**](StatsmonBandwidthtrackerBwUsageBySiteDetails.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_bwtracker_region_site_gateway_details_post_response import V1BwtrackerRegionSiteGatewayDetailsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1BwtrackerRegionSiteGatewayDetailsPostResponse from a JSON string
v1_bwtracker_region_site_gateway_details_post_response_instance = V1BwtrackerRegionSiteGatewayDetailsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1BwtrackerRegionSiteGatewayDetailsPostResponse.to_json())

# convert the object into a dict
v1_bwtracker_region_site_gateway_details_post_response_dict = v1_bwtracker_region_site_gateway_details_post_response_instance.to_dict()
# create an instance of V1BwtrackerRegionSiteGatewayDetailsPostResponse from a dict
v1_bwtracker_region_site_gateway_details_post_response_from_dict = V1BwtrackerRegionSiteGatewayDetailsPostResponse.from_dict(v1_bwtracker_region_site_gateway_details_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


