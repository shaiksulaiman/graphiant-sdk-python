# V2MonitoringSegmentRouteCountsPostResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**ipv4_route_count** | [**StatsmonV2StatsSample**](StatsmonV2StatsSample.md) |  | [optional] 
**ipv6_route_count** | [**StatsmonV2StatsSample**](StatsmonV2StatsSample.md) |  | [optional] 
**segment_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_segment_route_counts_post_response_data import V2MonitoringSegmentRouteCountsPostResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringSegmentRouteCountsPostResponseData from a JSON string
v2_monitoring_segment_route_counts_post_response_data_instance = V2MonitoringSegmentRouteCountsPostResponseData.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringSegmentRouteCountsPostResponseData.to_json())

# convert the object into a dict
v2_monitoring_segment_route_counts_post_response_data_dict = v2_monitoring_segment_route_counts_post_response_data_instance.to_dict()
# create an instance of V2MonitoringSegmentRouteCountsPostResponseData from a dict
v2_monitoring_segment_route_counts_post_response_data_from_dict = V2MonitoringSegmentRouteCountsPostResponseData.from_dict(v2_monitoring_segment_route_counts_post_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


