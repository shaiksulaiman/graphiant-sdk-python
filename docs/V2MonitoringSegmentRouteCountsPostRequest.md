# V2MonitoringSegmentRouteCountsPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_ids** | **List[int]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_segment_route_counts_post_request import V2MonitoringSegmentRouteCountsPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringSegmentRouteCountsPostRequest from a JSON string
v2_monitoring_segment_route_counts_post_request_instance = V2MonitoringSegmentRouteCountsPostRequest.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringSegmentRouteCountsPostRequest.to_json())

# convert the object into a dict
v2_monitoring_segment_route_counts_post_request_dict = v2_monitoring_segment_route_counts_post_request_instance.to_dict()
# create an instance of V2MonitoringSegmentRouteCountsPostRequest from a dict
v2_monitoring_segment_route_counts_post_request_from_dict = V2MonitoringSegmentRouteCountsPostRequest.from_dict(v2_monitoring_segment_route_counts_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


