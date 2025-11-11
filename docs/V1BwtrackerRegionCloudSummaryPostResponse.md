# V1BwtrackerRegionCloudSummaryPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bwusage_summary** | [**StatsmonBandwidthtrackerBwUsageByRegionCloudSummary**](StatsmonBandwidthtrackerBwUsageByRegionCloudSummary.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_bwtracker_region_cloud_summary_post_response import V1BwtrackerRegionCloudSummaryPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1BwtrackerRegionCloudSummaryPostResponse from a JSON string
v1_bwtracker_region_cloud_summary_post_response_instance = V1BwtrackerRegionCloudSummaryPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1BwtrackerRegionCloudSummaryPostResponse.to_json())

# convert the object into a dict
v1_bwtracker_region_cloud_summary_post_response_dict = v1_bwtracker_region_cloud_summary_post_response_instance.to_dict()
# create an instance of V1BwtrackerRegionCloudSummaryPostResponse from a dict
v1_bwtracker_region_cloud_summary_post_response_from_dict = V1BwtrackerRegionCloudSummaryPostResponse.from_dict(v1_bwtracker_region_cloud_summary_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


