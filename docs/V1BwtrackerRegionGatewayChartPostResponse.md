# V1BwtrackerRegionGatewayChartPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bwusage_chart** | [**StatsmonBandwidthtrackerBwUsageChart**](StatsmonBandwidthtrackerBwUsageChart.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_bwtracker_region_gateway_chart_post_response import V1BwtrackerRegionGatewayChartPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1BwtrackerRegionGatewayChartPostResponse from a JSON string
v1_bwtracker_region_gateway_chart_post_response_instance = V1BwtrackerRegionGatewayChartPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1BwtrackerRegionGatewayChartPostResponse.to_json())

# convert the object into a dict
v1_bwtracker_region_gateway_chart_post_response_dict = v1_bwtracker_region_gateway_chart_post_response_instance.to_dict()
# create an instance of V1BwtrackerRegionGatewayChartPostResponse from a dict
v1_bwtracker_region_gateway_chart_post_response_from_dict = V1BwtrackerRegionGatewayChartPostResponse.from_dict(v1_bwtracker_region_gateway_chart_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


