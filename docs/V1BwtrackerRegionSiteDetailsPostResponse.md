# V1BwtrackerRegionSiteDetailsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bwusage_details** | [**StatsmonBandwidthtrackerBwUsageBySiteDetails**](StatsmonBandwidthtrackerBwUsageBySiteDetails.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_bwtracker_region_site_details_post_response import V1BwtrackerRegionSiteDetailsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1BwtrackerRegionSiteDetailsPostResponse from a JSON string
v1_bwtracker_region_site_details_post_response_instance = V1BwtrackerRegionSiteDetailsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1BwtrackerRegionSiteDetailsPostResponse.to_json())

# convert the object into a dict
v1_bwtracker_region_site_details_post_response_dict = v1_bwtracker_region_site_details_post_response_instance.to_dict()
# create an instance of V1BwtrackerRegionSiteDetailsPostResponse from a dict
v1_bwtracker_region_site_details_post_response_from_dict = V1BwtrackerRegionSiteDetailsPostResponse.from_dict(v1_bwtracker_region_site_details_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


